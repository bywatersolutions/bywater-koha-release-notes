
# Release Notes for bywater-v18.11.10-02

## Authentication

- [[23771]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23771) CAS/Shib Authentication can fail when multiple users with no userid/cardnumber defined and one of them is locked

## Reports

- [[23626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23626) Add a system preference to limit the number of rows of data used when charting or exporting report results



# Release Notes for bywater-v18.11.10-01

## Acquisitions

- [[22786]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22786) Can create new funds for locked budgets
- [[23338]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23338) Cannot specify replacement price when ordering from file if not using fields to order
- [[23294]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23294) Restore actual cost input field on order page
- [[23251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23251) EDI Order line incorrectly terminated when it ends with a quoted apostrophe

## Architecture, internals, and plumbing

- [[23237]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23237) Plugin allow [% INCLUDE %] from template

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[22830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22830) correct for loop in value_builder/unimarc_field_4XX.pl value_builder
- [[23436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23436) Save to 'undefined' showing in Advanced cataloging editor
- [[21518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21518) Material type "three-dimensional artifact" displays as "visual material"

## Circulation

- [[23273]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23273) Downloading from overdues.pl doesn't use set filters
- [[23518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23518) Problem with borrower search  autocomplete
- [[23408]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23408) Relatives' checkout table columns are not configured properly

## Command-line Utilities

- [[23345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23345) Wrong parameter name in koha-dump usage statement

## Database

- [[23265]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23265) Update to DB revision 16.12.00.032 fails: Unknown column 'me.item_level_hold'

## Hold requests

- [[23502]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23502) Staff client "revert status" buttons should not depend on SuspendHoldsIntranet preference

## I18N/L10N

- [[10492]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10492) Translation problems with TT directives in po files

## MARC Authority data support

- [[23437]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23437) When UseAuthoritiesForTracing is 'Use' we should use series authorities

## MARC Bibliographic record staging/import

- [[23324]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23324) Need an ISBN normalization routine

## OPAC

- [[23530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23530) Opac-basket.pl script accidentally displays 'hidden' items
- [[23210]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23210) login4tags should be a link
- [[23151]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23151) Patron self modification sends null dateofbirth
- [[23099]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23099) OPAC Search result sorting "go" button flashes on page load

## Searching

- [[11677]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11677) Limit to Only items currently available for loan or reference not working

## Searching - Elasticsearch

- [[22524]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22524) Elasticsearch - Date range in advanced search

## SIP2

- [[23057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23057) If checked_in_ok is set and item is not checked out, alert flag is supressed for *any* reason

## Staff Client

- [[21716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21716) Item Search hangs when \ exists in MARC fields

## System Administration

- [[23309]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23309) Can't add new subfields to bibliographic frameworks in strict mode

## Templates

- [[23446]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23446) Fix display issue with serials navigation
- [[23226]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23226) Remove type attribute from script tags: Cataloging

## Tools

- [[22799]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22799) Batch item modification is case sensitive

## Z39.50 / SRU / OpenSearch Servers

- [[23242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23242) Error when adding new Z39.50/SRU server in DB strict mode



# Release Notes for bywater-v18.11.09-05

## SIP2

- [[22037]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22037) regression: guarantor no longer blocked (debarred) if child is over limit, when checking out via SIP.



# Release Notes for bywater-v18.11.09-04

## Reports

- [[23624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23624) Count rows in report without (potentially) consuming all memory



# Release Notes for bywater-v18.11.09-03

## Circulation

- [[23658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23658) WrongTransfer modal drops off specified checkin date on returns.pl



# Release Notes for bywater-v18.11.09-02

## ILL

- [[21406]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21406) Not adding author to request can cause JS errors

## OPAC

- [[23537]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23537) Overdrive won't show complete results if the Overdrive object doesn't have a primaryCreator



# Release Notes for bywater-v18.11.09-01

## Acquisitions

- [[21316]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21316) Adding controlfields to the ACQ framework causes issues when adding to basket

## Architecture, internals, and plumbing

- [[23230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23230) Make Koha::Plugins::Base::_version_compare OO

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[23045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23045) Advanced cataloging editor (rancor) throws a JS error on incomplete/blank lines

## Circulation

- [[23405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23405) Circulation autocomplete for patron lookup broken if cardnumber is empty
- [[22617]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22617) Checkout notes pending dashboard link - error received even though manage_checkout_notes permission set
- [[23103]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23103) Cannot checkin items lost by deleted patrons with fines attached
- [[23145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23145) Confirming transfer during checkin clears the table of previously checked-in items
- [[21027]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21027) Totals in statistics tab change when StatisticsFields is changed
- [[23192]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23192) Cancelling holds over returning to wrong tab on waitingreserves.pl
- [[23255]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23255) HomeOrHoldingbranch system preference options are described wrong
- [[23220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23220) Cancelling transfer on returns.pl is subject to a race condition
- [[23098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23098) KOC upload process has misleading wording

## Command-line Utilities

- [[22128]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22128) koha-remove fails mysql ERROR 1133 (42000) at line 2: Can't find any matching row in the user table
- [[22566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22566) Stock rotation cronjob reporting has issues

## Course reserves

- [[22142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22142) An item's current location changes to blank when it is removed from Course Reserves
- [[23083]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23083) Course reserve item edit fails if one does not set all values

## Fines and fees

- [[23143]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23143) [18.11] Filter paid transactions not working
- [[23115]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23115) Totals are unclear when a credit is involved on the OPAC 'Fines and charges' screen

## Hold requests

- [[22021]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22021) Item status not shown accurately on request.pl

## ILL

- [[23229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23229) "Get all requests" API call fired when loading any ILL page

## Label/patron card printing

- [[23455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23455) Patron card printing from Patron lists is broken

## Lists

- [[23266]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23266) Add to cart fires twice on shelf page

## Notices

- [[23278]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23278) Reopen last panel upon "Save and continue" in notices

## OPAC

- [[23428]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23428) Self registration with a verification by email is broken
- [[23078]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23078) Use Koha.Preference in OPAC global header include
- [[23308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23308) Contents of "OpacMaintenanceNotice" HTML escaped on display
- [[12537]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12537) Editions tab showing on bibs with more than one ISBN
- [[23194]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23194) Public notes items in the OPAC should allow for HTML tags
- [[22951]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22951) Markup error in OPAC holds template
- [[23151]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23151) Patron self modification sends null dateofbirth
- [[22949]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22949) Markup error in OPAC course reserves template

## Packaging

- [[21000]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21000) debian/build-git-snapshot script ignores -D

## Patrons

- [[23218]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23218) Batch patron modification empty attribute causes improper handling of values
- [[23199]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23199) Koha::Patron->store and uppercasesurname syspref
- [[23077]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23077) Can't import patrons without cardnumber

## Searching

- [[23132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23132) Encoding issues in facets with show more link

## Searching - Elasticsearch

- [[23322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23322) Elasticsearch - Record matching fails when multiple keys exist
- [[21534]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21534) ElasticSearch - Wildcards not being analyzed

## SIP2

- [[23057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23057) If checked_in_ok is set and item is not checked out, alert flag is supressed for *any* reason

## System Administration

- [[23179]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23179) Add 'Edit subfields' to framework management tag dropdown and clarify options

## Templates

- [[23304]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23304) Reindent cataloguing/z3950_search.tt
- [[22710]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22710) [18.11] Return to the last advanced search link not filtering correctly
- [[23221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23221) Reindent tools/manage-marc-import.tt
- [[23227]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23227) Remove type attribute from script tags: Reports
- [[22957]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22957) Remove type attribute from script tags: Staff client includes 1/2
- [[23183]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23183) Reindent cataloging.js
- [[22935]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22935) Improve style of Bootstrap pagination

## Test Suite

- [[23177]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23177) Rollback cleanup in Circulation.t
- [[23280]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23280) Warning in t/db_dependent/selenium/patrons_search.t
- [[23211]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23211) SIP/Transaction.t is failing randomly

## Tools

- [[11642]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11642) Improve Batch patron deletion and anonymization GUI to make consequences clearer
- [[18707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18707) Background jobs post disabled inputs
- [[19012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19012) Note additional columns that are required during patron import

## Web services

- [[23156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23156) Add pagination to checkouts in ILS-DI GetPatronInfo service



# Release Notes for bywater-v18.11.08-04

## Bywater Only

- NOT IN BUGZILLA - Fix object being treated as a hashref, preventing item level holds



# Release Notes for bywater-v18.11.08-03

## Acquisitions

- [[23363]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23363) Clicking on shipping cost invoice link from spent.pl causes internal server error


