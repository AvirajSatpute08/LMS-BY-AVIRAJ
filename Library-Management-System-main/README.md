
TO RUN THE APPLICATION:

&nbsp; * LMS Angular 

&emsp; -> npm install 

&emsp; -> npm start

&nbsp; * LMS Server 

&emsp;-> npm start

***

API’s BASED ON ROLES:

&nbsp; * Users

&emsp; POST - /api/usersauth/userregister

&emsp; POST - /api/usersauth/userlogin

&emsp; GET - /api/users/bookcount/book_id (view stock count of a book)

&emsp; GET - /api/users/userbooks?page=1&limit=2 (view all books owned by a user)

&emsp; GET - /api/users/userbooks (view all books owned by a user)

&emsp; GET - /api/users/user (view signed in user)
 
&emsp; GET - /api/books/categorybooks (for getting a category of books)

&emsp; GET - /api/books/allbooks (view all books)

&nbsp; * Admins

&emsp; POST - /api/adminsauth/adminregister

&emsp; POST - /api/adminsauth/adminlogin

&emsp; GET - /api/admins/alladmins (view all admins)

&emsp; GET- /api/admins/allmembers (view all members)

&emsp; GET- /api/admins/alllibrarians (view all librarians)

&emsp; GET - /api/admins/users/allusers (view all users)

&emsp; POST- /api/admins (add an admin)

&emsp; GET - /api/admins/admin_id (view an admin)

&emsp; PUT - /api/admins/admin_id (update an admin)

&emsp; DELETE - /api/admins/admin_id (delete an admin)

&emsp; POST- /api/admins/users ( add a user)

&emsp; GET - /api/admins/users/user_id (view a user)

&emsp; PUT - /api/admins/users/user_id (update a user)

&emsp; DELETE - /api/admins/users/user_id (delete a user)

&nbsp; * Librarians

&emsp; GET - /api/librarians/userbooks (view details of books owned by a user)

&emsp; GET - /api/librarians/bookusers/book_id (view details of users who own a book with same id)

&emsp; GET - /api/librarians/status/pending (for getting pending status user details)

&emsp; GET - /api/librarians/status/returned (for getting status returned user details)

&emsp; GET - /api/issuebooks/issue_id (for getting all records in IssueBooks)

&emsp; POST - /api/issuebooks/issue_id (for adding a record in IssueBooks)

&emsp; PUT- /api/issuebooks/issue_id (for updating a record in IssueBooks)

&emsp; DELETE - /api/issuebooks/issue_id (for deleting a record in IssueBooks)

&emsp; PUT - /api/librarians/fineentry/issue_id (for updating fine amount)

&emsp; POST - /api/books/book_id (for adding a book)

&emsp; PUT - /api/librarians/bulkupload (for bulk uploading books)

&emsp; GET - /api/books/book_id (for getting details of a book)

&emsp; PUT- /api/books/book_id (for updating a book details)

&emsp; DELETE - /api/books/book_id (for deleting a book)

&emsp; PUT - /api/librarians/bulkdelete (for bulk deleting with book id’s)

***
