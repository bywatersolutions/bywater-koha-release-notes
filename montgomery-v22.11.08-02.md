
# Release Notes for montgomery-v22.11.08-02

## About

- [[33899]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33899) Release team 23.11

## Acquisitions

- [[34261]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34261) Deleting an EDIFACT ordering account throws an error
- [[33939]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33939) JavaScript needs to distinguish between order budgets and default budgets when adding to staged file form a basket
- [[34002]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34002) Check for stage_marc_import permission when adding to basket from a new file
- [[33993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33993) The GET orders endpoint needs to allow users with order_receive permission

## Architecture, internals, and plumbing

- [[33167]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33167) Cleanup staff interface catalog details page
- [[34303]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34303) t/00-testcritic.t should only test files part of git repo
- [[33270]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33270) OAI-PMH should not die on record errors
- [[33496]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33496) Add 'host_items' param to Koha::Biblio->items
- [[34243]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34243) Too many cities are created (at least in comments)
- [[33047]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33047) Local cover image fetchers return 500 internal error when image not available
- [[18855]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18855) Fines cronjob can cause duplicate fines if run during active circulation
- [[24517]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24517) Zebra: date-entered-on-file misses 6th position
- [[33500]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33500) Failing test for t/db_dependent/Circulation.t when RecordLocalUseOnReturn is set to record
- [[34051]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34051) Koha::AuthorisedValues->get_description_by_koha_field not caching results for non-existent values
- [[34033]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34033) DB update problems from bug 30649
- [[33844]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33844) item->is_denied_renewal should check column from associated pref
- [[32478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32478) Remove Koha::Config::SysPref->find since bypasses cache
- [[30002]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30002) Add project-level perltidyrc
- [[30649]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30649) Vendor EDI account passwords should be encrypted in the database
- [[33967]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33967) REMOTE_ADDR incorrect in plack.log when run behind a proxy
- [[33937]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33937) Incorrect export in C4::Members
- [[33951]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33951) normalized_oclc not defined in opac-readingrecord.tt
- [[33950]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33950) Unnecessary processing in opac-readingrec if BakerTaylor and Syndetics off
- [[32894]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32894) Objects cache methods' result without invalidation

## Authentication

- [[33879]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33879) check_cookie_auth overwrites interface set by get_template_and_user
- [[31651]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31651) Log message incorrect in Auth_with_shibboleth.pm
- [[33880]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33880) "Enable two-factor authentication" fails if patron's library branchname is too long
- [[33904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33904) 2FA registration fails if library name has non-latin characters

## Bywater Only

- NOT IN BUGZILLA - Remove bad test
- NOT IN BUGZILLA - remove xt/find-misplaced-executables.t
- NOT IN BUGZILLA - GitHub Actions - Add support for security repo
- NOT IN BUGZILLA - GitHub Actions - Disable ZAP scans until we can get them passing
- NOT IN BUGZILLA - Fix translations for Koha 22.11.08
- NOT IN BUGZILLA - Bug 30524: (QA follow-up) Unit tests for GenerateCSRF()
- NOT IN BUGZILLA - Bug 34023: Prevent HTML injection in "back to results" link from search page
- NOT IN BUGZILLA - Bug 22990: (follow-up) Fix suggestion.pl
- NOT IN BUGZILLA - Bug 34368: Add CSRF token to Content Management pages

## Cataloging

- [[34251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34251) MARC editor with JS error when using fast add framework
- [[34029]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34029) Import breaks when data exceeds size of mapped database columns
- [[34182]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34182) AddBiblio shouldn't set biblio.serial based on biblio.seriestitle
- [[34097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34097) Using the three ellipses to set the date accessioned for an item repositions the screen to the top
- [[34218]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34218) XSLT parse on record directly breaks OPAC display
- [[34146]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34146) How to limit number of copies (on additem and serials-edit)?

## Circulation

- [[34232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34232) Item groups dropdown on add item form does not respect display order
- [[31082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31082) Add tooltip to buttons when item bundles cannot be changed while checked out
- [[33817]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33817) Composition of an item bundle can be changed if checked out
- [[31147]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31147) Recalls due date to the minute rather than 23:59
- [[34072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34072) Holds queue search interface hidden on small screens
- [[34086]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34086) On detail.tt if item.permanent_location is NULL no shelving location will show
- [[33858]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33858) Date for pending offline circulation is unformatted
- [[34071]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34071) Change the phrasing of 'automatic checkin' to fit consistent terminology
- [[33976]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33976) Claims returned option is not disabled in moredetail.pl if the item has a different lost status
- [[33944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33944) When listing checkouts, don't fetch item object if not using recalls
- [[33806]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33806) Overridden checkin date not retained when CircConfirmItemParts enabled
- [[33888]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33888) Overdues with fines report displays error 500

## Custom For Instance

- NOT IN BUGZILLA - One should be able to assign an SMTP server as the default

## Documentation

- [[33790]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33790) Fix and add various links to the manual

## ERM

- [[34214]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34214) Toolbar component should make the icon configurable
- [[34201]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34201) Missing sorting indicator on the ERM tables
- [[34107]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34107) Sorting agreements by Name actually sorts by ID
- [[33973]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33973) Sorting broken on ERM tables
- [[33417]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33417) Create one standard Toolbar component
- [[33941]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33941) EBSCO Packages filter failing
- [[34206]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34206) [22.11] Vendor options do not show on agreements and licenses form

## Hold requests

- [[33573]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33573) Add public endpoint for cancelling holds
- [[34233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34233) Pickup location pulldowns when placing holds in staff are blank
- [[34137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34137) Requested cancellation date column missing from holds awaiting pickup table config

## Installation and upgrade (web-based installer)

- [[33671]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33671) Database update 22.06.00.048  breaks update process
- [[33581]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33581) Error in web installer concerning sample holidays and patrons requiring sample libraries

## Label/patron card printing

- [[34209]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34209) Follow up on Bug 28726 - move whole search header div into checkbox column condition
- [[28726]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28726) Add sort1 and sort2 to patron card creator patron search

## MARC Authority data support

- [[33404]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33404) Authorities imported from Z39.50 in encodings other than UTF-8 are corrupted
- [[34180]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34180) Template variable in JavaScript triggers error when showing authority MARC preview

## MARC Bibliographic data support

- [[29471]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29471) MARC21: 520 - Summary etc. doesn't display in staff interface
- [[26862]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26862) MARC21 530 is missing from staff interface and has no label
- [[31618]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31618) Typo in POD for C4::ImportBatch::RecordsFromMARCXMLFile

## Notices

- [[33900]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33900) advance_notices.pl cronjob hangs

## OPAC

- [[33808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33808) Accessibility: Non-descriptive links
- [[33933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33933) Use restrictions appear twice for items on OPAC
- [[34005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34005) Toggling the search term highlighting is not always working in the bibliographic record details page
- [[34174]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34174) Saving RIS results to Error 505
- [[34015]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34015) Terminology: Relative issues should be Relative's checkouts
- [[33957]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33957) normalized_oclc not defined in opac-user.tt
- [[32341]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32341) Some OPAC tables are not displayed well in mobile mode

## Packaging

- [[33720]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33720) updatedatabase.pl should purge memcached

## Patrons

- [[34256]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34256) Patron search: search for borrowernumber starts with fails
- [[34092]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34092) patron-autocomplete.js and patron-search.inc search logic should match
- [[34106]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34106) Patron search in member-search-box.inc always defaults to 'Starts with' search
- [[33968]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33968) Two colons missing on guarantor labels in memberentry.pl form
- [[34083]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34083) Patron auto-complete fails if organization patron full name is in a single field separated by a space
- [[33117]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33117) Patron checkout search not working if searching with second surname
- [[33176]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33176) Improve enforcing of RequirePaymentType

## Reports

- [[27824]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27824) Report batch operations break with space in placeholder
- [[29664]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29664) Do not show voided payments in cash register statistics wizard

## REST API

- [[33974]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33974) Add ability to search biblios endpoint any biblioitem attribute
- [[34211]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34211) Add +strings for GET /api/v1/biblios/:biblio_id/items
- [[32801]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32801) /checkouts?checked_in=1 errors when itemnumber is null

## Searching

- [[28196]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28196) In page anchors on additem.pl don't always go to the right place
- [[31253]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31253) Item search in staff interface should call barcodedecode if the search index is a barcode
- [[33896]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33896) Catalog search from the masthead searchbar produces a warning in the logs

## Serials

- [[23775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23775) Claiming a serial issue doesn't create the next one
- [[34052]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34052) Fix link to subscription from serial collection page
- [[33901]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33901) Only one issue shown when testing prediction pattern

## Staff interface

- [[33497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33497) Reduce DB calls on staff detail page
- [[33946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33946) biblio-title.inc should not add a link if biblio does not exist
- [[34094]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34094) Apply DefaultPatronSearchMethod to all patron search forms
- [[34116]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34116) Add page-sectioning to item search in label creator
- [[34131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34131) Plugins page breadcrumbs and side menu not consistent
- [[32245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32245) Deleting news entries from Koha's staff start page is broken

## System Administration

- [[33578]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33578) Cannot edit patron restriction types

## Templates

- [[34184]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34184) "Document type" in suggestions form should have an empty entry
- [[33893]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33893) Use template wrapper for tabs: OPAC checkout history
- [[34244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34244) Improve contrast in staff interface main page layered icons
- [[34074]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34074) Improve translations of strings on the about page
- [[33781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33781) Terminology: Item already issued to other borrower.
- [[33999]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33999) Subscription details link on bibliographic detail page should have permission check
- [[34103]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34103) Capitalization: Currencies & Exchange rates
- [[33894]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33894) Use template wrapper for tabs: OPAC search history
- [[34013]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34013) Recalls awaiting pickup doesn't show count on each tab
- [[34012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34012) Use template wrapper for tabs: Recalls awaiting pickup
- [[34010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34010) Template corrections to recall pages
- [[33897]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33897) Use template wrapper for tabs: OPAC bibliographic detail page
- [[33855]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33855) Clean up forms and page sections on 'manage MARC imports' page

## Test Suite

- [[33727]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33727) Merge Calendar tests
- [[33852]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33852) jobs.t is not testing only_current

## Tools

- [[34288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34288) Cannot use cataloguing tools without cataloguing permissions
- [[29762]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29762) Patron batch modification tool - mobile phone number column naming
- [[34220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34220) Running log viewer for only Catalog module loads wrong side navbar
- [[33667]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33667) 'Copy to all libraries' doesn't work on editing holidays
- [[33972]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33972) Remove unnecessary batch status change in C4::ImportBatch
- [[33989]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33989) Inventory tool performs unnecessary authorized value lookups
- [[33987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33987) Combine multiple db updates in C4::ImportBatch::BatchCommitRecords for efficiency/avoiding possible deadlocks


