# BookFinder personal library manager

Project planning repo for BookFindr project

## MVP features

- Search for books by
  - ISBN
  - Author/Editor/title/subject
  - EAN/ASIN
  - LOC number
  - Text string (for Google fulltext book search)
- Custom entries when book not found (exportable to cloud)
- Local edits of book data (overrides API data)
- Tagging, listing, collections, and libraries
  - Tags &ndash; non-hierarchical
  - Books can be part of one or more lists
  - Lists can be owned by collections
  - Collections can be owned by libraries
- Write notes
  - Can be attached to hierarchical records
  - Can be attached to authors, editors, and publishers
  - Fulltext-searchable
- Collect and display review data from APIs
- Allow user ratings and reviews
  - Reviews &ndash; extension of notes
- Automatic retrieval of cover art and bibliographic info
- All relevant data can be retrieved as part of book record
- Add to list directly from search/filter result
- Add _all_ search/filter results to list
- Display as list of books or individual book records
- Individual records show links to similar books in own libraries
- Individual record can show recommended books
- User registration with bcrypt password hashing
- User authentication with JWTs
- Self-management of user profile data
- Personal preferences/settings can be saved
- Data storage/retrieval via ArangoDB and GraphQL
- Fully responsive UI with transitions and animations
- Dark mode
- Search omnibar with optional form expansion for advanced options
- Settings for advanced options can be saved
- Live Ajax updated options for search
- Views
  - Summary home page
  - Profile view/edit
  - Search/view results
  - List/Collection/Library view
  - Single book view
  - Author view
  - Book controls available from any view
    - Add to Goodreads/Amazon wishlist/Google shelf
    - Find in local library
    - Buy the book (aff. links)
  - All editable fields can be edited directly from each view
