# offline-search-mobile

# Requirements

 - App uses SQLite file to manage links
 - App needs to be distributed with "minimal" SQLite file that will allow any user to check how it looks and feels
 - User is able to point to own SQLite file, probably downloaded from web, or point to URL, which contains a SQLfile (or zip file?)
 - User should be able to add new links
 - User should be able to modify existing links

# SQLite format

Should be able to support tables exactly like here https://github.com/rumca-js/Django-link-archive

For example:
 - linkdatamodel
 - sourcedatamodel

linkdatamodel should contain .link fields, etc.

# Views
 - SQLite file selection
 - Google-like search
 - Entry Detail view (should display one link data)
 - 
