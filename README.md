# library-manager

This simple JavaScript program displays information about a collection of books, including their authors, summaries, and total page count.

🧠 Overview

The program works with a predefined array of book objects named library.
Each object contains:

title: The book’s title

author: The author or authors

about: A short summary of what the book is about

pages: The total number of pages in the book

It then uses functions to:

Display book titles and authors

Display book summaries

Show the total number of pages across all books

⚙️ Functions
getBookInformation(catalog)

Takes the library array as input.

Returns a formatted list of all books with their authors.

Example output:

Atomic Habits by James Clear
Rich Dad Poor Dad by Robert Kiyosaki and Sharon Lechter

getBookSummaries(catalog)

Returns a list of summaries (about) for each book.

getTotalPages(catalog)

Uses reduce() to calculate the total number of pages in the entire library.

Example output:

-2512

🧩 Concepts Used

Array of objects

Array methods: .map() and .reduce()

Template literals for clean string formatting

Console output using console.log()
