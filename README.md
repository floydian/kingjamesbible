King James Bible
==============

The King James Bible in MySQL Format

You can either downlaod the sql file and import in to your databse or you can use the text documents with the extract.php file to import the bible into your database.

kingjamesbible.sql is the original sql backup.

kjvdata.sql is the new one.

It has been updated to change Chapter_Name field to Book_Name. Additionally, a Book_Id field has been added with Genesis = 1 and Revelation = 66. The other numeric fields (Chapter_Id and Verse_Id) have been converted from tinytext (or varchar, whatever text type they were) to int).
