# Chinook
Chinook queries and analysis
Chinook is a sample database available for SQL Server, Oracle, MySQL, etc. It can be created by running a single SQL script.

# Table Description
There are 11 tables in the chinook sample database-

Employees table: stores employees data such as employee id, last name, first name, etc. It also has a field named ReportsTo to specify who reports to whom.

Customers table: stores customers data.

 Invoices & Invoice_items tables: these two tables store invoice data. The invoices table stores invoice header data and the invoice_items table stores the invoice line items data.
 
 Artists table: stores artists data. It is a simple table that contains only artist id and name.
 
 Albums table: stores data about a list of tracks. Each album belongs to one artist. However, one artist may have multiple albums.
 Media_types table: stores media types such as MPEG audio and AAC audio file.
 
 Genres table: stores music types such as rock, jazz, metal, etc.
 
Tracks table: store the data of songs. Each track belongs to one album.

 Playlists & Playlist_track tables: playlists table store data about playlists. Each playlist contains a list of tracks. Each track may belong to multiple playlists. The relationship between the playlists table and tracks table is many-to-many. The playlist_track table is used to reflect this relationship.
 
# Data Model
The Chinook data model represents a digital media store, including tables for artists, albums, media tracks, invoices and customers.
