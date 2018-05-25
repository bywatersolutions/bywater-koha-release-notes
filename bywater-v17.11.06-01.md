
# Release Notes for bywater-v17.11.06-01

## Acquisitions

- [[19030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19030) Link order <-> subscription is lost when an order is edited
- [[20426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20426) Can't import all titles from a stage file with default values
- [[3841]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=3841) Add a Default ACQ framework
- [[19812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19812) Holds count in "Already received" table has confusing and unexpected values
- [[20318]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20318) Merge invoices can lead to an merged invoice without Invoice number
- [[19916]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19916) Can't search keyword or standard ID from Acquisitions external source / z3950
- [[18593]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18593) Suggestions aren't updated when one biblio is merged with another

## Architecture, internals, and plumbing

- [[20325]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20325) C4::Accounts::purge_zero_balance_fees does not check account_offsets
- [[19739]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19739) Add default ES configuration to koha-conf.xml
- [[20229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20229) Remove problematic SQL modes

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Bug 20701: (17.11 follow-up) Move csrf token after checkauth and use scalar
- NOT IN BUGZILLA - Bug 20730: Move the authentication block before doing anything

## Cataloging

- [[19267]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19267) Advanced Editor - Rancor - Add warning before leaving page if there are unsaved modifications
- [[20067]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20067) Wrong display of authorised value for items.materials on staff detail page
- [[20341]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20341) Show authorized value description for withdrawn like damaged and lost

## Circulation

- [[20536]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20536) ILL: authnotrequired not explicitly unset

## Command-line Utilities

- [[19955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19955) Add ability to process only one 'type' of message ( sms, email, etc ) for a given run of process_message_queue.pl
- [[11936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11936) Consistent log message for item insert
- [[12812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12812) Longoverdue.pl --mark-returned doesn't return items
- [[17717]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17717) Fix broken cronjobs due to permissions of the current directory
- [[20234]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20234) Make maintenance scripts use koha-zebra instead of koha-*-zebra

## Course reserves

- [[20282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20282) Wrong attribute in template calls to match holding branch when adding/editing a course reserve item

## Database

- [[19547]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19547) Maria DB doesn't have a debian.cnf

## Fines and fees

- [[20562]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20562) issue_id is not stored in accountlines for rental fees

## Hold requests

- [[18474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18474) Placing multiple holds from results breaks when patron is searched for

## I18N/L10N

- [[20330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20330) Allow translating more of quote upload
- [[20302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20302) Allow translating Delete button in Patron batch mod tool
- [[20301]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20301) Allow translating "View" in manage MARC import
- [[20141]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20141) Untranslatable string in Transport cost matrix
- [[20296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20296) Untranslatable "All" in patrons table filter
- [[20295]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20295) Allow translating link title in ILL module
- [[20142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20142) Allow translating offline circ message
- [[20147]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20147) Allow translating prompt in label edit batch
- [[20140]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20140) Allow translating more of OAI sets

## ILL

- [[20556]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20556) Marking ILL request as complete results in "Internal server error"

## Lists

- [[11943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11943) Koha::Virtualshelfshare duplicates rows for the same list
- [[20687]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20687) Multiple invitations to share lists prevents some users from accepting

## MARC Authority data support

- [[20430]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20430) Z39.50 button display depends on wrong server count

## Notices

- [[18725]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18725) process_message_queue.pl sends duplicate emails if message_queue is not writable
- [[19578]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19578) TT syntax for notices - There is no way to pre-process DB fields
- [[18570]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18570) Password recovery e-mail only sent after message queue is processed

## OPAC

- [[20286]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20286) Subscribing to a search via rss goes to an empty page

## Patrons

- [[19907]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19907) Email validation on patron add/edit not working
- [[19673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19673) Patron batch modification tool cannot use authorised value "0"
- [[20455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20455) Can't sort patron search on date expired
- [[19908]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19908) Password should not be mandatory

## Reports

- [[19910]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19910) Download report as 'Comma separated' is misleading
- [[19583]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19583) Report updater triggers on auth_header.marcxml

## REST api

- [[19546]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19546) Make koha-plack run Starman from the instance's directory

## Searching

- [[20369]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20369) Analytics search is broken with QueryAutoTruncate set to 'only if * is added'

## Searching - Elasticsearch

- [[19581]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19581) Elasticsearch - Catmandu split option adds extra null fields to indexes
- [[20385]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20385) ElasticSearch authority search raises Software error
- [[19564]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19564) Fix extraction of sort order from sort condition name
- [[20386]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20386) Improve warning and error messages for Search Engine Configuration
- [[19582]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19582) Elasticsearch: Auth-finder.pl must use search_auth_compat

## Serials

- [[20461]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20461) New subscription form: "Item type" and "item type for older issues" fields are ignored

## Staff Client

- [[19223]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19223) Avoid encoding issues in plugins by providing helper methods to output headers correctly
- [[19953]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19953) Add column for invoice in acquisition details tab

## System Administration

- [[20383]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20383) Hide link to plugin management if plugins are not enabled

## Templates

- [[20552]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20552) Fix HTML tag for search facets
- [[19892]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19892) Replace numbersphr variable with Koha.Preference('OPACNumbersPreferPhrase') in OPAC
- [[20372]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20372) Correct toolbar markup on some pages
- [[20290]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20290) Fix capitalization: Routing List
- [[20240]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20240) Remove space before : when searching for a vendor in serials (Vendor name :)
- [[20239]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20239) Fix spelling on authority linker plugin

## Test Suite

- [[20584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20584) Koha/Patron/Categories.t is failing on slow servers
- [[20721]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20721) Circulation.t keeps failing randomly
- [[20503]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20503) Borrower_PrevCheckout.t  is failing randomly
- [[20490]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20490) Correct wrong bug number in comment in Circulation.t
- [[20474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20474) Passwordrecovery.t should mock Mail::Sendmail::sendmail
- [[20311]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20311) get_age tests can fail on February 28th

## Tools

- [[20462]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20462) Duplicate barcodes in batch item deletion cause software error if deleting biblio records
- [[20376]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20376) "Select all" button no longer selects disabled checkboxes in Batch Record Deletion Tool



# Release Notes for bywater-v17.11.04-05

## Command-line Utilities

- [[20795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20795) koha-rebuild-zebra should pass through increased verbosity

## Notices

- [[20685]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20685) Modify letter template does not render correctly

## Templates

- [[19882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19882) Add Novelist Select staff client profile


