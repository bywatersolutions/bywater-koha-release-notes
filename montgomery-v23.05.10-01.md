
# Release Notes for montgomery-v23.05.10-01

## About

- [[36134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36134) Elasticsearch authentication using userinfo parameter crashes about.pl

## Accessibility

- [[36140]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36140) Wrong for attribute on Invoice number: label in invoice.tt

## Acquisitions

- [[36233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36233) Cannot search invoices if too many vendors
- [[35916]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35916) Purchase suggestions bibliographic filter should be a "contains" search
- [[35911]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35911) Archived suggestions show in patron's account
- [[35892]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35892) Fallback to GetMarcPrice in addorderiso2907 no longer works
- [[36047]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36047) Apostrophe in suggestion status reason blocks order receipt
- [[35398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35398) EDI: Fix support for LRP (Library Rotation Plan) for Koha with Stock Rotation enabled

## Architecture, internals, and plumbing

- [[24879]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24879) Add missing authentication checks
- [[36176]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36176) [23.11 and below] We need tests to check for 'cud-' operations in stable branches (pre-24.05)
- [[36323]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36323) koha_perl_deps.pl can be run from the UI
- [[36322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36322) Can run docs/**/*.pl from the UI
- [[36244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36244) Template toolkit syntax not escaped in letter templates
- [[35960]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35960) XSS in staff login form
- [[33898]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33898) background_jobs_worker.pl may leave defunct children processes for extended periods of time
- [[35955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35955) New CSRF token generated everytime we need one
- [[36056]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36056) Clarify subpermissions check behavior in C4::Auth
- [[36212]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36212) transferbook should not look for items without barcode
- [[36170]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36170) Wrong warning in memberentry
- [[34913]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34913) Upgrade DataTables from 1.10.18 to 1.13.6
- [[35819]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35819) "No job found" error for BatchUpdateBiblioHoldsQueue (race condition)
- [[36000]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36000) Fix CGI::param called in list context from catalogue/search.pl
- [[36088]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36088) Remove useless code form opac-account-pay.pl

## Authentication

- [[34755]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34755) Error authenticating to external OpenID Connect (OIDC) identity provider : wrong_csrf_token
- [[36098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36098) Create Koha::Session module

## Cataloging

- [[29522]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29522) Bib record not correctly updated when merging identical authorities with LinkerModule set to First Match
- [[32029]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32029) Automatic item modifications by age missing biblio table
- [[34234]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34234) Item groups dropdown in detail page modal does not respect display order
- [[35963]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35963) Problem using some filters in the bundled items table
- [[35554]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35554) Authority search popup is only 700px
- [[36156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36156) Duplicate selected value when a field or subfield is cloned

## Circulation

- [[35983]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35983) Library specific refund lost item replacement fee cannot be 'refund_unpaid'

## Command-line Utilities

- [[36009]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36009) Document koha-worker --queue elastic_index

## Hold requests

- [[36103]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36103) Remove the "Cancel hold" link for item level holds

## OPAC

- [[36004]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36004) Typo in "Your concern was successfully submitted" OPAC text
- [[36032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36032) The "Next" pagination button has a double instead of a single angle
- [[35538]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35538) List of libraries on OPAC self registration form should sort by branchname rather than branchcode
- [[36359]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36359) Broken OPAC mainpage layouts in 23.05.09
- [[35952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35952) Removed unnecessary  line in opac-blocked.pl
- [[35941]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35941) OPAC user can guess clubs of other users

## Patrons

- [[36292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36292) 'See all charges' hyperlink to view guarantee fees is not linked correctly
- [[36298]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36298) In patrons search road type authorized value code displayed in patron address
- [[35796]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35796) Patron password expiration date lost when patron edited by superlibrarian
- [[36076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36076) paycollect.tt is missing permission checks for manual credit and invoice

## Reports

- [[31988]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31988) manager.pl is only user for "Catalog by item type" report
- [[35949]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35949) Useless code pointing to branchreserves.pl in request.tt

## REST API

- [[36066]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36066) REST API: We should only allow deleting cancelled order lines

## Staff interface

- [[35800]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35800) edit_any_item permission required to see patron name in detail page
- [[36005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36005) Typo in "Your concern was successfully submitted" in staff interface
- [[36099]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36099) JS error in console on non-existent biblio record
- [[35935]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35935) Wrong branch picked after an incorrect login

## Templates

- [[35934]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35934) Items in transit show as both in-transit and Available on holdings list
- [[36224]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36224) It looks like spsuggest functionality was removed years ago, but the templates still refer to it
- [[36332]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36332) JS error on moremember
- [[35351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35351) Adjust basket details template to avoid showing empty page-section

## Test Suite

- [[36277]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36277) t/db_dependent/api/v1/transfer_limits.t  is failing
- [[32671]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32671) basic_workflow.t is failing on slow servers
- [[36010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36010) Items/AutomaticItemModificationByAge.t is failing
- [[35922]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35922) t/db_dependent/www/batch.t is failing


