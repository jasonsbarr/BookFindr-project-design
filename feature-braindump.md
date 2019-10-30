# BookFindr personal library manager

## Searching, saving, & organizing

- Search API(s) by one or more of:
	- ISBN
	- LOC classification
	- Title
	- Author(s)/Editor(s)
	- Subject
	- Pub date
	- EAN and/or ASIN (where applicable)
	- ISSN

- Also locally searchable/listable by any/all of those when saved
- Enable custom entries for when book(s) not found
- Locally edit book attribute fields (overrides data from API)
- Saving book records locally
	- Local DB basic info (tagged/listable by all of the above)
	- Create own:
		- books
			- manual entry for rare, antique, self-published, and other books not listed in APIs
			- own books are exportable to be added to the global collection - searchable for all users
			- don't _have_ to be exported though
		- tags
		- lists/collections/libraries
			- list is a list of books
			- collection is a list of lists - like a notebook stack in Evernote
			- library can have lists or collections and enables extra features (paid feature?)
				- lending
				- tracking
				- reminders
			- can add _directly_ to list when adding a book record - don't have to add book first then add to list in 2 separate steps
	- include edition number in record where applicable
	- tag for ebook, softcover, hardback, audiobook
	- tags can go on any entity - books, lists, notes, etc.
- Predefined lists:
	- Favorites
	- To-read
	- Reading-now
	- Have-read
	- Reviewed (automatically generated based on user's reviews)
	- Recently-viewed
	- Owned
	- Recommendations
	- Wishlist
- Designate books as borrowed with due dates, home libraries, reminders via email/text/push
- Incorporate Google's text search
- Enable star rating (1-5), display/filter by star rating or range
	- use Amazon/Google/Goodreads for ratings for defaults before user rates
- Add notes for books, lists, and authors
- Make notes searchable
- Book journaling (extension for notes)
- Add book to Goodreads shelf
- Add book to Amazon wish list
- Check out/acquire book from online lender or (if free) provider
- Buy book (affiliate programs)
- All data items associated with a book (lists it's on, reviews, notes, etc.) can be retrieved as part of the book's record
- Automatic cover art and bibliographic information
- Automatic citation generation for various citation formats
- Bibliography manager (plus notes = full academic library manager)

### Stretch goals

- See if can get similar items, e.g. "you have/want this, you might also like that"?
- Camera scanner if PWA?
	- bar codes
	- covers/title pages
- Voice search?
- Autocomplete in search would be nice
- Keep track of loaned books

### Display local records

- Tags, subjects, etc. can be displayed/filtered as unions (e.g. all books with subject Archery on a wishlist)
- Can also display/filter based on boolean, e.g. is not, is also, etc.
- Can be displayed as list items or individual book record
- Lists can be ordered asc or desc by any table column (default to date desc)
- Get current prices for books not owned (with links to purchase)
- If book is in local library give option to search online anyway

## Reading and personal goals

- Time tracking
- Update progress for one or more books
- Set reading goals
- Track progress on goals
- Data analysis and statistics (graphs!)

## User management

- Node backend with JWT auth
- Permissions-based auth
- Group permissions into roles
- Custom setting of roles/permissions in admin
- User can self-manage password, profile info, avatar
- Sign up via email/password

### Stretch goals

- Auth with OAuth via Google, Facebook, Twitter, & GitHub
- Allow passwordless login via email link
- Enable pubkey based auth

## Data storage

- Online database/cloud for data storage

### Stretch goals

- Ability to import/export as spreadsheet/CSV/XML/JSON (filtered or all)
- Export as PDF
- Backup/sync data via Google Drive, Dropbox, or other service(s)
- Make PWA with local persistence & caching

## UI

- Fully responsive
- Dark/light modes
- Search omnibar
- Optional expandable fields (goal to have all search params accessible via omnibar)
- Ajax search suggestions/autocomplete
- Results update live with option change
	- when editing expandable field
	- after first search
- Summary home page
- Profile view/edit screen(s)
- Search/view search results
- List view
- Single book view
- Author view (with image of author) that include books authored, co-authored, edited, and co-edited
- View my library
- Add/remove books from any list or single view
- Edit links in list and single view (if list open single edit UI)

## Social features

- Can make lists, reviews, notes, tags, etc. visible to friends, all users, whole world
- Can comment on ^^^ any of those things (except tags)
- Can recommend books to other users based on their interests/books/lists
- Book blogging/social posting (with comments)?
- Social sharing of reviews, lists, etc.
- Inter-user lending, marketplace
- Following (one-way, public data only) and friending (two-way, friends-only)

## Monetization

- Amazon and/or other referral links
- Additional paid features, especially for authors/publishers
- Author/publisher advertising
- Native ads (book reviews, promotional posts)

## Possible APIs to use

- Google Books
- Amazon Advertising (XML)
- MediaHound
- Goodreads
- ISBNdb
