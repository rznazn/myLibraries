# myLibraries
a collection of some self made libraries

to use these libraries you can add them to your android project in the same directory as "app" 
then add "compile project(':libraryName') to the app level build.gradle.

for the mylocationlibrary you can create an instance of LocationAccess(Context context) in your activity then call the 
getter methods to get the desired information

for the mydatabaselibrary, this is just starter code and will need editing for purpose. In this case there 
are two tables generated, one that creates a list of "tags" that can be applied to 
items in the second table. this essentially creates user generated tables. just query the second table for 
items "tagged" with the first table entry. Delete deletes from the "directory" table and all items
"tagged" for that entry in the second table. 

android, library, location, google client, compass, database, SQLite
