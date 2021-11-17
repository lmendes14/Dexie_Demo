# Lab 7 - Starter Code

Local storage is as follows:
  On opening of website:
    1. If "file" exists on localStorage:
       a. Convert "file" string into Blob
       b. Import blob into database
    2. Else:
       a. Fetch recipe JSONs from array
       b. Initialize database to those JSONs

  On CREATE/UPDATE/DELETE:
    1. Export database onto Blob
    2. Convert Blob into JSON string
    3. Save JSON string onto localStorage as "file"