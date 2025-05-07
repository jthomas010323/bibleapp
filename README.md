# Bible App

This application is used to read and search the bible. Contains a variety of translations that you can read from and allows you to search for the usage of a word or string used in The Bible.

## How to access

https://jthomas010323.github.io/bibleapp/index.html

### Usage

Use select on top left corner to navigate through different translations

Use left box in order to search for a specific book and chapter. On chapter page, there are buttons to go to the next or previous chapter. Also a button to return

Use right box to search for a string used in The Bible.

To go back to the main page at any time, click the logo in the top right

### API Used

NEED AN API KEY TO ACCESS THIS API

https://api.scripture.api.bible/v1/

Used 5 endpoints:

/v1/bibles - To get the versions

/v1/bibles/{bibleId}/books - to get the books of a specific version

​/v1​/bibles​/{bibleId}​/books​/{bookId}​/chapters - to get the all the chapters of a specific version and book

/v1/bibles/{bibleId}/chapters/{chapterId} - To get chapter details, including content and reference

/v1/bibles/{bibleId}/search - To get verses that for a given String.
