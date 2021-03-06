
# Release Notes for roundrock-v19.05.06-04

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Add Auto-rebasing of XSLT branches, leave disabled

## Circulation

- [[24547]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24547) Add more action logs for holds



# Release Notes for roundrock-v19.05.06-03



# Release Notes for roundrock-v19.05.06-02

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Prevent workflow from running on tags, associate release with correct branch

## Custom For Instance

- NOT IN BUGZILLA - Possibly the solution for RT 46756
- NOT IN BUGZILLA - Hard coded SMS causes unit tests to fail, delete them
- NOT IN BUGZILLA - BUG FIX - SUBMIT TO COMMUNITY - SIP2 Fee items bug
- NOT IN BUGZILLA - Change SMS email
- NOT IN BUGZILLA - BWS: Modified spinelabel.css, per rt 34841
- NOT IN BUGZILLA - Temporarily hardcode SMS for RT 33100



# Release Notes for roundrock-v19.05.06-01

## About

- [[24136]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24136) Add libraries (sponsors) to the about page

## Architecture, internals, and plumbing

- [[24243]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24243) Bad characters in MARC cause internal server error when searching catalog

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Build Debian packaage
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Circulation

- [[24138]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24138) suspension miscalculated when Suspension charging interval bigger than 1 and Max. suspension duration  is defined
- [[23427]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23427) Better sorting of previous checkouts
- [[13958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13958) Add a suspensionsCalendar syspref
- [[24024]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24024) Holds Awaiting Pickup (Both Active and Expired) Sorts by Firstname

## Command-line Utilities

- [[24164]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24164) Patron emailer cronjob is not generating unique content for notices

## Course reserves

- [[23952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23952) Fix body id on OPAC course details page

## Fines and fees

- [[23483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23483) When writing off a fine, the title of the patron is shown as description

## Hold requests

- [[24168]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24168) Errors with use of CanItemBeReserved return value

## I18N/L10N

- [[13749]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13749) On loading holds in patron account 'processing' is not translatable

## MARC Bibliographic data support

- [[17831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17831) Remove non-existing bibliosubject.subject mapping from frameworks

## Notices

- [[24072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24072) Typos in advance_notices.pl causes DUEDGST not to be sent
- [[24064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24064) DUEDGST typoed as DUEGST

## OPAC

- [[23785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23785) Software error Can't call method "get_coins" on an undefined value at /usr/share/koha/opac/cgi-bin/opac/opac-search.pl line 692.
- [[23506]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23506) Sound material type displays wrong icon in OPAC/Staff details

## Patrons

- [[21939]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21939) Permission for holds history tab is too strict

## Reports

- [[23389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23389) Add 'All' option to report value dropdowns

## Searching

- [[23970]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23970) itemsearch - publication date not taken into account if not used in the first field
- [[23768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23768) ISBN search in IntranetCatalogPulldown searches nothing if passed an invalid ISBN and using SearchWithISBNVariations
- [[24120]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24120) Search terms in search dropdown must be URI filtered

## Searching - Elasticsearch

- [[24128]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24128) Add alias for biblionumber => local-number
- [[23089]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23089) Elasticsearch - cannot sort on non-text fields

## Staff Client

- [[23246]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23246) Record detail page jumps into the 'images' tab if no holdings
- [[23987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23987) batchMod.pl provides a link back to the record after the record is deleted

## System Administration

- [[24170]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24170) sysprefs search result does not have a consistent order
- [[23751]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23751) Description of staffaccess permission should be improved

## Templates

- [[23954]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23954) Format notes in suggestion management

## Test Suite

- [[24199]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24199) t/Auth_with_shibboleth.t is failing randomly

## Tools

- [[24124]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24124) Cannot select authorities in batch deletion tool in Chrome

## Web services

- [[22677]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22677) Include hint on OAI-PMH URL for Koha in system preference



# Release Notes for roundrock-v19.05.05-09

## Tools

- [[24330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24330) When importing patrons from CSV, automatically strip BOM from file if it exists



# Release Notes for roundrock-v19.05.05-08

## SIP2

- [[24175]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24175) Cannot cancel holds - wrong parameter passed for itemnumber



# Release Notes for roundrock-v19.05.05-07



# Release Notes for roundrock-v19.05.05-06

## Custom For Instance

- NOT IN BUGZILLA - Typos in advance_notices.pl causes DUEDGST not to be sent



# Release Notes for roundrock-v19.05.05-05

## Architecture, internals, and plumbing

- [[24106]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24106) In returns.pl, don't search for item if no barcode is provided

## Bywater Only

- NOT IN BUGZILLA - Fix error caused by backport, causes failure in t/Auth_with_shibboleth.t

## Circulation

- [[24085]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24085) Double submission of forms on returns.pl



# Release Notes for roundrock-v19.05.05-04

## Circulation

- [[24024]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24024) Holds Awaiting Pickup (Both Active and Expired) Sorts by Firstname

## Command-line Utilities

- [[24164]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24164) Patron emailer cronjob is not generating unique content for notices

## Notices

- [[24064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24064) DUEDGST typoed as DUEGST


