# Uni-Homework-3
A java console library manager program.(in french)


In context :
The owner of your city's library seeks your knowledge in designing
software and wants you to produce a program in console mode so that you can manage
the different documents he has: books (novels and manuals), magazines and dictionaries.

Objective 1: Identification of classes and methods based on the needs of the
customer

In this work, it is still up to you to identify the different classes, variables, methods and the
hierarchy allowing the design and development of the program (we can, again
once, provide you with assistance (consultation) during troubleshooting sessions).

Description of customer needs:
The client wishes to be able to manage a list of documents. All documents have a number
single record of 10 mixed letters and numbers, title and number of copies. The
number of copies can be incremented and decremented when using the program. The
documents define all library books, journals and dictionaries.

Library books define novels and textbooks. Each book is defined (in
plus its registration number, title and number of copies) by name
and a number of pages.

Each novel, in addition to having the characteristics of a document and a book, has a list of
literary prizes he won (ex: Prix Goncourt).

Each manual, in addition to having the characteristics of a document and a book as well, has a
associated domain among those of the following list: computing, chemistry, physics,
math, health, education.

Each journal, in addition to having the characteristics of a document, has a month and a year of
publication.

Finally, each dictionary, in addition to having the characteristics of a document, has a
language among the following languages: French, English, Spanish, Latin, German.
Each more specific document (novel, manual, journal, dictionary) has, in addition, a
description by type: *
Novel: "This document is of the novel type, a novel is ..."
Manual: "This document is manual, a manual is ..."
Review: "This document is of the review type, a review is ..."
Dictionary: "This document is of dictionary type, a dictionary is ..."
* The sentences can be completed by the student.
Objective 2: Implementation of a menu in console mode as needed
of the user
Regarding the menu allowing him to manage his different documents, the owner of the
library wants to be able to:

Addition and deletion of novels, manuals, magazines and dictionaries
o Add to a list of documents
 Choice of the field of the manual from the predefined list of types
previously given
 Choice of the language of a dictionary from the predefined list of
languages
o Deletion of a document
 If the list includes elements
 The document will be chosen from a displayed list of documents by their
title and registration number
 Request confirmation before deletion
 
Display the list of all documents:
o Display only the title and registration number
o Only if the list includes elements

Display the different characteristics concerning a document:
o By entering the document registration number
o Ex: for a novel, display the characteristics of the document, the book and the
novel (a novel being a book and a book being a document)
o Only if the list includes elements

Display the literary price list for a novel
o Choice among the novels displayed using their title and author taken from the list
of documents
o Only if the list includes elements of the novel type
Increase or decrease in number of copies of document
o Selected by its registration number
Changing the title of a document
o The document will be chosen from a list of documents displayed using the title
and the registration number
o Request confirmation
Changing the author of a book
o The book will be chosen from a list of books displayed using their title and
author
o Request confirmation
Creation and addition of predefined documents
o 2 predefined documents of each specific type (novel, manual, review,
dictionary)
Exit the menu

Additional specifications:
In order to practice certain concepts seen in class, although the return of sentences
specific to the type of document by the instance ("This document is of type ...") can
be done in several ways, you are here required to do it using a method
including the same signature for each type of document, but returning a
different sentence for each type as described earlier in this document. think,
when designing this project, to use the concepts of inheritance, redefinition and
polymorphism if they should be used.

In addition, for each menu and submenu, we ask that the option be
implemented in a separate method if the option code represents more than three
instructions.
