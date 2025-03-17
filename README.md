# offline-search-mobile

# Requirements

 - App uses SQLite file to manage links
 - App needs to be distributed with "minimal" SQLite file that will allow any user to check how it looks and feels
 - User is able to point to own SQLite file, probably downloaded from web, or point to URL, which contains a SQLfile (or zip file?)
 - User should be able to add new links
 - User should be able to modify existing links
 - User should be able to tag links
 - User should be able to comment on links
 - User should be able to vote on links

# SQLite format

 - Should be able to support tables exactly like here https://github.com/rumca-js/Django-link-archive.
 - If possible, it should not complain if tables contain more fields

For example:
 - linkdatamodel (fields .link, .title, .description)
 - sourcedatamodel

# Views
 - SQLite file selection
 - Google-like search (by .link, .title, .description, by tag)
 - Entry Detail view (should display one link data)
