
# Release Notes for mtpl-v18.11.10-02

## Authentication

- [[23771]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23771) CAS/Shib Authentication can fail when multiple users with no userid/cardnumber defined and one of them is locked

## Reports

- [[23626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23626) Add a system preference to limit the number of rows of data used when charting or exporting report results



# Release Notes for mtpl-v18.11.10-01

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



# Release Notes for mtpl-v18.11.09-05

## SIP2

- [[22037]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22037) regression: guarantor no longer blocked (debarred) if child is over limit, when checking out via SIP.



# Release Notes for mtpl-v18.11.09-04

## Reports

- [[23624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23624) Count rows in report without (potentially) consuming all memory



# Release Notes for mtpl-v18.11.09-03

## Circulation

- [[23658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23658) WrongTransfer modal drops off specified checkin date on returns.pl



# Release Notes for mtpl-v18.11.09-02

## ILL

- [[21406]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21406) Not adding author to request can cause JS errors

## OPAC

- [[23537]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23537) Overdrive won't show complete results if the Overdrive object doesn't have a primaryCreator



# Release Notes for mtpl-v18.11.09-01

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



# Release Notes for mtpl-v18.11.08-04

## Bywater Only

- NOT IN BUGZILLA - Fix object being treated as a hashref, preventing item level holds



# Release Notes for mtpl-v18.11.08-03

## Acquisitions

- [[23363]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23363) Clicking on shipping cost invoice link from spent.pl causes internal server error

## Architecture, internals, and plumbing

- [[21180]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21180) Allow Talking Tech outbound script to limit based on patron home library branchcode
- [[23144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23144) Bad POD breaks svc/barcode

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Circulation

- [[23097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23097) Circulation Overdues report patron link  goes to patron's holds tab

## Hold requests

- [[13640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13640) Holds To Pull List includes items unreserveable items

## Installation and upgrade (command-line installer)

- [[23250]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23250) koha-create generates broken mysql password
- [[23090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23090) MySQL validate_password plugin breaks koha-create

## OPAC

- [[23431]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23431) having Date of birth in PatronSelfModificationBorrowerUnwantedField causes DOB to be nullified
- [[23151]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23151) Patron self modification sends null dateofbirth
- [[23150]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23150) GDPR feature breaks patron self modification on OPAC
- [[22946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22946) Markup error in OPAC search results around selection links

## Self checkout

- [[23198]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23198) [18.11] Wrong icons/paths in 18.11 for self check modules

## Serials

- [[23065]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23065) 'New subscription' button in serials sometimes uses a blank form and sometimes defaults to current serial

## SIP2

- [[23057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23057) If checked_in_ok is set and item is not checked out, alert flag is supressed for *any* reason

## System Administration

- [[23153]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23153) In framework management action subfields goes directly to edition

## Templates

- [[22851]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22851) Navigation links in the serials module should be styled the same as other modules

## Tools

- [[15814]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15814) Templates for MARC modification: Edit action does not work when Description contains '



# Release Notes for mtpl-v18.11.07-06



# Release Notes for mtpl-v18.11.07-05

## Architecture, internals, and plumbing

- [[23144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23144) Bad POD breaks svc/barcode

## Patrons

- [[23283]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23283) cannot view/edit additional attributes in 18.11.x

## SIP2

- [[23057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23057) If checked_in_ok is set and item is not checked out, alert flag is supressed for *any* reason



# Release Notes for mtpl-v18.11.07-04

## Bywater Only

- NOT IN BUGZILLA - Fix for error in placerequest.pl



# Release Notes for mtpl-v18.11.07-03

## Bywater Only

- NOT IN BUGZILLA - Fix for backported Bug 22877



# Release Notes for mtpl-v18.11.07-02

## Circulation

- [[23018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23018) Refunding a lost item fee may trigger error if any fee has been written off related to that item



# Release Notes for mtpl-v18.11.07-01

## Architecture, internals, and plumbing

- [[16750]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16750) Redirect from selectbranchprinter.pl to additem.pl causes software error

## Authentication

- [[22585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22585) Fix remaining double-escaped CAS links

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Bug 23058: Prevent XSS vulnerabiliies when 'tag' is passed to opac-search

## Cataloging

- [[7890]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7890) Required fields in the MARC editor should be highlighted
- [[21887]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21887) 856$u link problem in XSLT result lists and detail page

## Circulation

- [[18344]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18344) Overdue fines 'cap at replacement price' and 'cap by amount' should work together

## Database

- [[23022]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23022) Koha is not compatible with MySQL >= 8.0.11 because of NO_AUTO_CREATE_USER mode

## ILL

- [[22099]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22099) "List requests" button displays when listing requests

## Installation and upgrade (web-based installer)

- [[22770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22770) Typo in German translation for Greek in language pull down

## Lists

- [[22941]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22941) Giving malformed sortfield to list results in Internal Server Error

## MARC Authority data support

- [[23053]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23053) Local-Number cannot be used for authority matching due to non-existence of 'phrase' index
- [[22919]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22919) Authorities MARC Structure not inserted with SQL strict modes

## MARC Bibliographic data support

- [[20986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20986) MARC21 Supplement and Index Textual Holdings don't display

## OPAC

- [[22945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22945) Markup error in OPAC search results around lists display
- [[23076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23076) Include OpacUserJS on OPAC maintenance page
- [[22954]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22954) Minor markup error in OPAC messaging template
- [[22952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22952) Markup error in OPAC suggestions template
- [[22948]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22948) Markup error in OPAC bibliographic detail template
- [[22955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22955) Markup error in OPAC lists template
- [[22950]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22950) Markup error in OPAC recent comment template
- [[22953]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22953) Markup warning in OPAC user summary template

## Patrons

- [[22910]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22910) Unique attributes should not be copied when duplicating a patron

## Searching

- [[14794]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14794) Searching patron by birthday returns no results if format incorrect

## Serials

- [[10215]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10215) Increase the size of opacnote and librariannote for table subscriptionhistory
- [[11492]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11492) Receiving a serial item causes routing list notes to be lost

## SIP2

- [[19457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19457) If CheckPrevCheckout is set to "Do", then checkouts are blocked at the SIPServer

## Staff Client

- [[22958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22958) The Help link on SMS providers page should link to the correct chapter in the manual

## System Administration

- [[8558]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8558) Better confirmation message for importing frameworks
- [[22947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22947) Markup error in OPAC preferences file

## Tools

- [[23006]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23006) Can't use inventory tool with barcodes that contain regex relevant characters ($,...)



# Release Notes for mtpl-v18.11.06-09

## Cataloging

- [[23045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23045) Advanced cataloging editor (rancor) throws a JS error on incomplete/blank lines



# Release Notes for mtpl-v18.11.06-08

## Hold requests

- [[23116]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23116) Cannot place overridden holds



# Release Notes for mtpl-v18.11.06-07

## Patrons

- [[23082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23082) Fatal error editing a restricted patron



# Release Notes for mtpl-v18.11.06-06

## Circulation

- [[23120]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23120) Internal server error when checking in item to transfer and printing slip



# Release Notes for mtpl-v18.11.06-05

## Circulation

- [[23140]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23140) Typo in returns.tt prevents printing branchcode in transfer slips



# Release Notes for mtpl-v18.11.06-04

## Circulation

- [[22877]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22877) Returning a lost item not marked as returned can generate additional overdue fines



# Release Notes for mtpl-v18.11.06-03

## Bywater Only

- NOT IN BUGZILLA - SUBMIT TO COMMUNITY - Supress Holds Queue warning if request has no item but request has an itemtype

## Self checkout

- [[23102]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23102) 404 errors on page causes SCI user to be logged out

## SIP2

- [[23057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23057) If checked_in_ok is set and item is not checked out, alert flag is supressed for *any* reason



# Release Notes for mtpl-v18.11.06-02

## Authentication

- [[22585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22585) CAS login link for staff intranet is double-escaped

## Circulation

- [[22982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22982) Paying lost fee does not always remove lost item from checkouts

## SIP2

- [[23057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23057) If checked_in_ok is set and item is not checked out, alert flag is supressed for *any* reason



# Release Notes for mtpl-v18.11.06-01

## Acquisitions

- [[22908]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22908) Modsuggestion will generate a notice even if the modification failed
- [[22907]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22907) Cannot add new suggestion with strict SQL modes turned on
- [[22225]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22225) Tax hints and prices on orderreceive.pl may not match
- [[22713]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22713) Replacement price removed when receiving if using MarcItemFieldstoOrder
- [[22791]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22791) Calculation differs on aqui-home/spent and ordered.pl

## Architecture, internals, and plumbing

- [[7862]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7862) Warns when creating a new notice
- [[22478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22478) Cross-site scripting vulnerability in paginations
- [[21036]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21036) Fix a bunch of older warnings
- [[22813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22813) searchResults queries the Koha::Patron object inside two nested loops

## Authentication

- [[22717]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22717) Google OAuth auto registration error

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[22886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22886) Missing space between fields from Keyword to MARC mapping in cataloguing search
- [[21709]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21709) Addbiblio shows clickable tag editor icons which do nothing

## Circulation

- [[22896]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22896) Item to be transferred at checkin clears overridden due date
- [[15524]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15524) Set limit on maximum possible holds per patron by category

## Command-line Utilities

- [[20537]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20537) Warnings in overdue_notices.pl
- [[22875]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22875) Documentation misleading for import_patrons command line script

## Course reserves

- [[22899]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22899) Cannot view course details

## Database

- [[22782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22782) Schema change for SocialData

## Fines and fees

- [[22724]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22724) Staff without writeoff permissions have access to 'Write off selected' button on Pay Fines tab

## Installation and upgrade (web-based installer)

- [[21651]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21651) Force insert of notices related tables during the install process
- [[22527]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22527) Web installer links to wrong database manual when database user doesn't have required privileges

## Label/patron card printing

- [[22878]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22878) Cannot add a patron card layout with mysql strict mode on

## MARC Authority data support

- [[21450]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21450) link_bibs_to_authorities.pl is caching searches without the auth type

## OPAC

- [[14385]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14385) Extend OpacHiddenItems to allow specifying exempt borrower categories
- [[11853]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11853) Cannot clear date of birth via OPAC patron update
- [[22881]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22881) Trying to clear search history via the navbar X doesn't clear any searches
- [[22816]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22816) OPAC detail holdings table doesn't fill it's container
- [[22420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22420) Tag cloud feature broken

## Patrons

- [[20514]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20514) Searching for a patrons using the address option doesn't work with streetnumber
- [[22781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22781) Fields on patron search results should be html/json filtered

## Reports

- [[22357]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22357) Every run of runreport.pl with --store-results creates a new row in saved reports

## Searching

- [[22901]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22901) On item search authorised values select disappears on conditional change
- [[22787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22787) Mapping missing for ů to u in word-phrase-utf-chr
- [[22010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22010) RecordedBooks and OverDrive should check preferences over passing variables

## Searching - Elasticsearch

- [[22705]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22705) Change default value of Elasticsearch cxn_pool to 'Static'

## Serials

- [[22812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22812) Cannot add new subscription with strict SQL modes turned on

## SIP2

- [[15221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15221) SIP server always sets the alert flag when item not returned

## Staff Client

- [[22914]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22914) Add holds column to batch item delete to fix show/hide columns behaviour
- [[17698]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17698) Make patron notes show up on staff dashboard

## System Administration

- [[22965]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22965) Typo in Classification Sources description on Admin homepage (admin-home.tt)
- [[22847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22847) Specific circ rule by patron category is displaying the default (or not displaying)

## Templates

- [[22932]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22932) GetLatestSerials should not return formatted date
- [[22904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22904) Untranslatable strings in members-menu.js
- [[22800]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22800) No need to raw filter the mandatory fields var (OPAC suggestions)

## Test Suite

- [[22917]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22917) Circulation.t fails if tests are ran slowly
- [[22930]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22930) Make TestBuilder more strict about wrong arguments
- [[22836]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22836) Tests catching XSS vulnerabilities in pagination are not correct
- [[22433]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22433) SIP/Transaction.t is failing randomly
- [[21671]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21671) Koha/Patron/Modifications.t is failing randomly
- [[22453]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22453) TestBuilder should generate now() using the current timezone
- [[22808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22808) Move Cache.t to db_dependent

## Tools

- [[21831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21831) Marc modification templates move all action moves only one field



# Release Notes for mtpl-v18.11.05-05

## Acquisitions

- [[22802]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22802) When ordering from a staged file, if funds are populated per item order level fund should not be required

## Templates

- [[22734]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22734) Fund not marked as mandatory when ordering from a staged file



# Release Notes for mtpl-v18.11.05-04

## Circulation

- [[22761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22761) Move "Fee receipt" from template to a slip

## Course reserves

- [[22899]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22899) Cannot view course details

## Hold requests

- [[22895]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22895) [18.11] cannot place item level holds



# Release Notes for mtpl-v18.11.05-03

## Bywater Only

- NOT IN BUGZILLA - Fix atomic updates



# Release Notes for mtpl-v18.11.05-02

## Circulation

- [[22809]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22809) Move "INVOICE" from template to a slip
- [[22761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22761) Move "Fee receipt" from template to a slip



# Release Notes for mtpl-v18.11.05-01

## Acquisitions

- [[22762]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22762) Collection codes not displayed on receiving
- [[20830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20830) Make sure a fund is selected when ordering from staged file
- [[22444]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22444) currencies_manage permission doesn't provide link to manage currencies when selected alone
- [[21659]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21659) Link to basket groups from order receive page are broken
- [[22541]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22541) Invoice adjustments: show invoice number and include link on ordered.pl and spent.pl
- [[22390]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22390) When duplicating existing order lines new items are not created
- [[22611]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22611) Typo introduced into Koha::EDI by bug 15685

## Architecture, internals, and plumbing

- [[22542]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22542) Back browser should not allow to see other patrons details (see bug 5371)
- [[22478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22478) Cross-site scripting vulnerability in paginations
- [[22723]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22723) Syntax error on confess call in Koha/MetadataRecord/Authority.pm
- [[21172]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21172) Warning in addbiblio.pl - Argument "01e" isn't numeric in numeric ne (!=)
- [[22044]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22044) NoRenewalBeforePrecision should be set by default for new installations
- [[22451]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22451) Asset plugin is using the version from the DB
- [[22472]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22472) Should column_exists explode if the table does not exist?
- [[22618]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22618) Tests in t/Acquisition.t are actually context dependent
- [[22607]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22607) Default value in issues.renewals should be '0' not null
- [[21622]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21622) Incorrect GROUP BY clause in acqui/ scripts
- [[21998]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21998) Add pattern parameter in Koha::Token

## Authentication

- [[22692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22692) Logging in via cardnumber circumvents account logout
- [[22461]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22461) Regression in #20287: LDAP user replication broken with mapped extended patron attributes

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Bug 22068: (QA follow-up) Return meaningful error codes

## Cataloging

- [[16232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16232) Edit as new (duplicate) doesn't work correctly with Rancor
- [[21937]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21937) Syspref autoBarcode annual doesn't increment properly barcode in some cases
- [[22288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22288) Barcode file does not work in modifying items in batch
- [[10345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10345) Copy number should be incremented when adding multiple items at once
- [[21049]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21049) Rancor 007 field does not retain value

## Circulation

- [[21346]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21346) Clean up dialogs in returns.pl
- [[21013]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21013) Missing itemtype for checkut makes patron summary print explode
- [[22648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22648) Typo in SQL in smart-rules.pl
- [[22536]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22536) Display problem in Holds to Pull report

## Command-line Utilities

- [[20692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20692) koha-plack doesn't check for Include *-plack.conf line in /etc/apache2/sites-available/$INSTANCE.conf
- [[21975]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21975) Unnecessary substitutions in automatic item modification by age
- [[17746]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17746) koha-reset-passwd should use Koha::Patron->set_password

## Course reserves

- [[22652]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22652) Editing Course reserves is broken
- [[21003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21003) Don't show warning when editing a reserve item

## Database

- [[22642]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22642) DB upgrade 18.06.00.005 can fail
- [[22634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22634) Standardize table creation for stockrotation* tables in kohacstructure.sql

## Documentation

- [[22687]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22687) Typo in Koha::Manual breaks Portuguese links
- [[22174]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22174) Add link to help page for API key management
- [[19747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19747) No help page linked for article requests

## Fines and fees

- [[22626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22626) 'Filter paid transactions' broken on Transactions tab in staff

## Hold requests

- [[22650]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22650) Can place multiple item level holds on a single item
- [[22753]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22753) Move hold to top button doesn't work if waiting holds exist
- [[15505]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15505) Mark Hold Items 'On hold' instead of 'Available'
- [[22688]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22688) TT plugin for pickup locations code wrong
- [[21263]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21263) Pickup library not set correctly when using Default holds policy by item type
- [[17978]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17978) Include 'Next available'/title level holds in holds count when placing holds (opac and staff)

## I18N/L10N

- [[19497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19497) Translatability: Get rid of "Edit [% field.name |html %] field"

## ILL

- [[22464]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22464) Copyright notice does not pass forward request properties
- [[22121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22121) Display 'Price paid' on ILL requests according to CurrencyFormat pref

## Installation and upgrade (web-based installer)

- [[21545]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21545) Update German web Installer for 18.11

## Lists

- [[20891]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20891) Lists in staff don't load when \ was used in the description

## MARC Authority data support

- [[21957]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21957) LinkBibHeadingsToAuthorities can be called twice when running link_bibs_to_authorities

## MARC Bibliographic data support

- [[21899]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21899) Update MARC21 frameworks to Update 27 (November 2018)
- [[19648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19648) Repeated positions and some options missing in cataloguing plugin 007 (XML file)

## Notices

- [[22139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22139) Fields of ACCTDETAILS not working properly
- [[14358]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14358) Changing the module refreshes the page and resets library choice
- [[20937]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20937) PrintNoticesMaxLines is not effective for overdue notices with a print type specified where a patron has an email

## OPAC

- [[21589]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21589) Series link formed from 830 field is incorrect
- [[22551]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22551) Stray "//" appears at bottom of opac-detail.tt
- [[19241]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19241) Items with status of hold show as available in cart
- [[22743]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22743) OverDrive results page is missing overdrive-login include
- [[22735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22735) Broken MARC and ISBD views
- [[22501]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22501) OPAC course reserves notes should allow html links
- [[22624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22624) Show OPAC description for authorised values in OPAC
- [[13629]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13629) SingleBranchMode removes both library and availability search from advanced search
- [[22680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22680) OPAC language footer not positioned correctly
- [[22075]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22075) Encoding problem with RIS export
- [[22620]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22620) OPAC description for collection in opac-reserve.tt
- [[22560]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22560) Forgotten password "token expired" page still shows boxes to reset password
- [[22561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22561) Forgotten password requirements hint doesn't list all rules for new passwords
- [[22550]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22550) OPAC suggestion form doesn't require mandatory fields

## Patrons

- [[22715]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22715) Searching for patrons with "" in the circulation note hangs patron search
- [[22646]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22646) Fix use of PrivacyPolicyURL

## Reports

- [[22090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22090) Cash register report missing data in CSV export

## REST api

- [[13895]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13895) Add routes for checkouts retrieval and renewal
- [[19661]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19661) Add routes for funds

## Searching

- [[22154]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22154) Subtype search for Format - Braille doesn't look for the right codes
- [[22595]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22595) Items search is mixing inputs
- [[12441]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12441) search.pl has incorrect reference to OPACdefaultSortField and OPACdefaultSortOrder
- [[22596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22596) html TT filter is breaking items search with custom field

## Searching - Elasticsearch

- [[22413]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22413) Elasticsearch - Search settings are lost after sorting, faceting or paging
- [[22339]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22339) Elasticsearch - fixed field mappings should match MARC ranges
- [[22474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22474) Authority and biblio field mapping improperly shared
- [[19670]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19670) search_marc_map.marc_field should have COLLATE= utf8mb4_bin
- [[22295]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22295) Elasticsearch - Advanced search should group terms entered in a single input
- [[22495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22495) Restore su-geo field in Elasticsearch mappings
- [[21974]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21974) cxn_pool must be configurable

## Self checkout

- [[22739]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22739) Self check in module JS breaks if  SelfCheckInTimeout  is unset
- [[18387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18387) 404 errors on page causes SCO user to be logged out
- [[22641]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22641) Incorrect filter on SCO printslip

## Serials

- [[22621]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22621) Filters on subscription result list search the wrong column

## System Administration

- [[18011]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18011) Enrollment period date on patron category can be set in the past without any error/warning messages
- [[22575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22575) Item type administration uses invalid error class for dialog

## Templates

- [[22716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22716) Use gender-neutral pronouns in system preference descriptions
- [[22702]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22702) Circulation note on patron page should allow for HTML tags
- [[22475]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22475) Shelving location doesn't appear on tags list view
- [[22586]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22586) IntranetReportsHomeHTML no longer renders as HTML on reports-home.pl
- [[21948]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21948) Clean up style of item detail page

## Tools

- [[22365]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22365) Warn on Log Viewer
- [[22069]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22069) Log viewer not displaying item renewals

## Web services

- [[22597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22597) Remove "more_subfields_xml" from GetPatronInfo response (xml broken)



# Release Notes for mtpl-v18.11.04-03

## Bywater Only

- NOT IN BUGZILLA - Fix bug introduced by rebase



# Release Notes for mtpl-v18.11.04-02

## Architecture, internals, and plumbing

- [[22618]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22618) Tests in t/Acquisition.t are actually database dependent



# Release Notes for mtpl-v18.11.04-01

## About

- [[7143]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7143) Bug for tracking changes to the about page

## Acquisitions

- [[22565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22565) Partially receiving order and adding internal note on invoice updates note on every order on the system
- [[18736]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18736) Problems in order calculations (rounding errors)
- [[20782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20782) EDI: Clicking the 'Invoice' link on the 'EDI Messages' page does not take you directly to the corresponding invoice
- [[22296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22296) Invoice adjustments are not populating to budget views
- [[22498]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22498) Can not select any funds for invoice adjustments
- [[14850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14850) Funds from inactive budgets appear in 'Funds' dropdown on acqui/invoice.pl
- [[18166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18166) Show internal and vendor notes for received orders
- [[21427]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21427) Format prices on ordered/spent lists
- [[21966]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21966) Fix descriptions of acquisition permissions to be more clear (again)
- [[22171]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22171) Format shipping cost on invoice.pl with with 2 decimals

## Architecture, internals, and plumbing

- [[22219]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22219) C4::Biblio->GetItemsForInventory can return wrong count / duplicated items when skipping waiting holds
- [[21987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21987) Local cover 'thumbnail' size is bigger than 'imagefile' size in biblioimages table
- [[18584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18584) Our legacy code contains trailing-spaces
- [[22084]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22084) Plugin upgrade method and database plugin version storage will never be triggered for existing installs
- [[21622]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21622) Incorrect GROUP BY clause in acqui/ scripts
- [[22391]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22391) Incorrect GROUP BY in /acqui/ajax-getauthvaluedropbox.pl
- [[22388]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22388) svc/split_callnumbers should have execute flag set

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[16251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16251) Material type is not correctly set for Rancor 008 widget
- [[22140]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22140) More use of EasyAnalyticalRecords pref

## Circulation

- [[13763]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13763) Renew feature does not check for the BarcodeInputFilter option
- [[21030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21030) Date widget on suspend modal not working correctly
- [[18957]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18957) Item renewed online does not show the time of renewal
- [[22130]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22130) Batch checkout: authorized value description is never shown with notforloan status
- [[17236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17236) Add minute and hours to last checked out item display for hourly loans
- [[22351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22351) SCSS conversion broke style on last checked out information

## Command-line Utilities

- [[22397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22397) Wrong message in koha-sip --start
- [[22396]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22396) koha-sip script does not start the server correctly
- [[22323]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22323) Cronjob runreport.pl has a CSV encoding issue
- [[12488]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12488) Make bulkmarcimport.pl -d use DELETE instead of TRUNCATE

## Database

- [[22476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22476) MarkLostItemsAsReturned has wrong defaults for new installs
- [[13515]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13515) Table messages is missing FK constraints and is never cleaned up

## Developer documentation

- [[20544]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20544) Wrong comment in database documentation for items.itemnotes

## Hold requests

- [[21765]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21765) AutoUnsuspendReserves manually sets holds fields instead of calling ->resume

## Installation and upgrade (command-line installer)

- [[17496]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17496) install-CPAN.pl documentation/removal
- [[20174]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20174) Remove xml_sax.pl target from Makefile.pl

## Installation and upgrade (web-based installer)

- [[21710]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21710) Fix typo atributes in some installer files

## Label/patron card printing

- [[22429]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22429) Infinite loop in patron card printing
- [[22275]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22275) 18.06.00.060 DB update fails (incomplete/incorrect defaults)

## OPAC

- [[21846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21846) Using emoji as tags doesn't discriminate between emoji when calculating weights or searching
- [[22360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22360) On order information missing in OPAC normal display
- [[21335]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21335) Remove redundant includes of right-to-left.css
- [[10676]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10676) OpacHiddenItems not working for restricted on OPAC detail

## Patrons

- [[16276]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16276) When automatically deleting expired borrowers, make sure they didn't log in recently
- [[22386]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22386) Importing using attributes as matchpoint broken
- [[22067]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22067) Koha::Patron->can_see_patron_infos should return if no patron is passed

## Reports

- [[21560]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21560) Optimize ODS exports
- [[22147]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22147) Hide 'Batch modify' button when printing reports
- [[18393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18393) Statistics wizard for acquisitions not filtering correctly by collection code
- [[22287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22287) Correct new charts CSS

## REST api

- [[22206]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22206) Add route to handle holds suspensions
- [[20006]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20006) Adapt /v1/holds to new naming guidelines
- [[16497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16497) Add API routes for libraries

## Searching

- [[20823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20823) UNIMARC XSLT does not display 604$t
- [[22442]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22442) Item search CSV export broken

## Searching - Elasticsearch

- [[22246]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22246) Elasticsearch indexing needs a maximum length for `__sort` fields
- [[20535]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20535) ModZebra called with $record with items stripped in ModBiblioMarc
- [[22228]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22228) Elasticsearch - standalone colons should be escaped when performing a search
- [[19575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19575) Use canonical field names and resolve aliased fields

## Self checkout

- [[22378]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22378) Fix sound alerts on SCO

## Serials

- [[13735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13735) Item form in serials module doesn't respect max length set in the frameworks
- [[22404]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22404) Some labels in subscription add form has wrong parameter "for"
- [[15149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15149) Serials: Test prediction pattern does not consider Subscription start and end date
- [[21845]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21845) Sort of issues in OPAC subscription table
- [[22156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22156) Subscription result list sorts on "checkbox" by default
- [[22239]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22239) JavaScript error on subscription detail page when there are no orders

## SIP2

- [[21997]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21997) SIP patron information requests can lock patron out of account
- [[19832]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19832) SIP checkout removes extra hold on same biblio

## Staff Client

- [[19046]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19046) IntranetCatalogSearchPulldown doesn't retain last selection
- [[22419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22419) Removing multiple records from intranet cart causes browser timeout
- [[21904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21904) Patron search library dropdown should be limited  by group if "Hide patron info" is enabled for group

## System Administration

- [[22170]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22170) Library group description input field should be longer
- [[22389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22389) Classification splitting sources regex - cannot consistentlyadd/delete
- [[18143]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18143) Silence floody MARC framework export

## Templates

- [[21130]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21130) Detail XSLT produces translatable HTML class
- [[20658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20658) Move template JavaScript to the footer: Installer and onboarding
- [[22477]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22477) Missing DataTables configuration when searching patrons for holds
- [[22422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22422) improve item location display with class "shelvingloc"
- [[22303]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22303) Wrong bottom in virtualshelves/addbybiblionumber.tt
- [[22466]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22466) TT methods must not be escaped
- [[22300]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22300) Staff search results: Opt groups in 'sort' pull down are not well formatted
- [[22080]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22080) Easier translation of ElasticSearch mappings page
- [[20102]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20102) Remove attribute "text/css" for style element used in staff client templates
- [[8387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8387) Hide headings in tools when user has no permissions for any listed below

## Test Suite

- [[22493]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22493) DecreaseLoanHighHolds.t creates some items/patrons with set values
- [[22416]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22416) Search.t tests need adjustment for EasyAnalyticRecords syspref
- [[21692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21692) Koha::Account->new has no tests
- [[21798]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21798) We need t::lib::TestBuilder::build_sample_biblio
- [[21971]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21971) TestBuilder::build_sample_item

## Tools

- [[22411]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22411) Dates in log viewer not formatted correctly

## Web services

- [[21832]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21832) Restore is_expired in ILS-DI GetPatronInfo service


