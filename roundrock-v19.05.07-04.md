
# Release Notes for roundrock-v19.05.07-04

## Searching - Elasticsearch

- [[23719]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23719) Record matching for authorities using defined fields is broken under ES



# Release Notes for roundrock-v19.05.07-03

## SIP2

- [[24705]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24705) Holds placed via SIP will be given first priority



# Release Notes for roundrock-v19.05.07-02

## SIP2

- [[24566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24566) UpdateItemLocationOnCheckin triggers SIP2 alert flag, even with checked_in_ok enabled



# Release Notes for roundrock-v19.05.07-01

## Acquisitions

- [[24244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24244) Cannot create suggestion with branch set to 'Any'
- [[24242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24242) Funds with no library assigned do not appear on edit suggestions page
- [[5365]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=5365) It should be more clear how to reopen a basket in a basket group

## Architecture, internals, and plumbing

- [[23997]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23997) sample_z3950_servers.sql is failing on MySQL 8

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[24173]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24173) Advanced Editor: Show subtitle & published date on the search page
- [[24232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24232) Fix permissions for deleting a bib record after attaching the last item to another bib
- [[11500]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11500) Use dateformat syspref and datepicker on additems.pl (and other item cataloguing pages)
- [[24090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24090) Subfield text in red when mandatory in record edition

## Circulation

- [[23382]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23382) Issuing rules failing after bug 20912
- [[24166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24166) Barcode removal breaks circulation.pl/moremember.pl
- [[24337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24337) Checkout note cannot be marked seen if more than 20 exist
- [[24335]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24335) Cannot mark checkout notes seen/not seen in bulk
- [[24308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24308) Suggestions table on suggestions.pl should have separate columns for dates
- [[24259]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24259) Circulation fails if no circ rule defined but checkout override confirmed

## Command-line Utilities

- [[19465]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19465) Allow choosing Elasticsearch server on instance creation

## Course reserves

- [[24283]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24283) Missing close parens and closing strong tag in course reserves

## Database

- [[23995]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23995) Check constraints are supported differently by MySQL and MariaDB so we should remove them for now.

## Hold requests

- [[24485]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24485) AllowHoldPolicyOverride should allow Staff to override the Holds Per Record Rule
- [[20948]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20948) Item-level hold info displayed regardless its priority (detail.pl)

## I18N/L10N

- [[24063]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24063) Add Sami language characters to Zebra
- [[24358]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24358) "Bibliographic record does not exist!" is not translatable
- [[18688]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18688) Warnings about UTF-8 charset when creating a new language
- [[24046]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24046) 'Activate filters' untranslatable

## ILL

- [[21270]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21270) "Not finding what you're looking" display needs to be fixed

## Installation and upgrade (command-line installer)

- [[24328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24328) Bibliographic frameworks fail to install

## Installation and upgrade (web-based installer)

- [[24314]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24314) Update de-DE MARC21 frameworks for updates 28+29 (May and November 2019)
- [[24137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24137) Marc21 bibliographic fails to install for ru-Ru and uk-UA

## MARC Authority data support

- [[24267]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24267) C4::Breeding::ImportBreedingAuth is ineffective

## MARC Bibliographic data support

- [[24312]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24312) Update MARC21 frameworks to Updates 28+29 (May and November 2019)
- [[24274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24274) New installations should not contain field 01e Coded field error (RLIN)
- [[24281]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24281) Fix the list of types of visual materials
- [[23731]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23731) Display LC call number in OPAC and staff detail pages

## Notices

- [[24235]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24235) /misc/cronjobs/advance_notices.pl DUEDGST does NOT send sms, just e-mail

## OPAC

- [[24212]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24212) OPAC send list dialog opens too small in IE
- [[24245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24245) opac-registration-confirmation.tt has incorrect HTML body id
- [[24240]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24240) List on opac missing close form tag under some conditions

## Reports

- [[13806]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13806) No input sanitization where creating Reports subgroup

## REST API

- [[24191]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24191) Sorting doesn't use to_model

## Searching

- [[24121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24121) Item types icons in intra search results are requesting icons from opac images path
- [[14419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14419) Expanding facets (Show more) performs a new search

## Searching - Elasticsearch

- [[24264]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24264) Elasticsearch - Cannot search for genre/form authorities

## Serials

- [[21232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21232) Problems when linking a subscription to a non-existing biblionumber

## Staff Client

- [[22381]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22381) Wording on Calendar-related system preferences not standardized

## System Administration

- [[24184]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24184) Reword FallbackToSMSIfNoEmail syspref text

## Templates

- [[24054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24054) Typo in ClaimReturnedWarningThreshold system preference
- [[24104]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24104) Item search - dropdown buttons overflow
- [[10469]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10469) Display more when editing subfields in frameworks
- [[23956]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23956) Replace famfamfam calendar icon in staff client with CSS data-url
- [[23889]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23889) Improve style of menu header in advanced cataloging editor
- [[24282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24282) SCSS conversion broke style in search results item status
- [[24230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24230) intranet_js plugin hook is after body end tag



# Release Notes for roundrock-v19.05.06-05

## Database

- [[24377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24377) Record branch in statistics for auto-renewal



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


