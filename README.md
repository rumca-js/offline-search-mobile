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
 - linkdatamodel (fields .link, .title, .description) -> https://github.com/rumca-js/Django-link-archive/blob/main/rsshistory/models/entries.py
 - sourcedatamodel -> https://github.com/rumca-js/Django-link-archive/blob/main/rsshistory/models/sources.py
 - usertags
 - usercomments
 - uservotes

# Views
 - mocks are available in design.pdf
 - Google-like search (by .link, .title, .description, by tag), similar to https://rumca-js.github.io/search
 - Entry Detail view (should display one link data)  https://rumca-js.github.io/search -> preview
 - settings view
 - about view - add email to Samos and rozbujnik@gmail.com?
 - Link add view (user only specifies link)
