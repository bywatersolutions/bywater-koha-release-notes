
# Release Notes for barcodeprfx-v20.05.06-01

## Acquisitions

- [[26738]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26738) Unable to change manager of purchase suggestion
- [[26908]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26908) EDI vendor accounts edit no longer allows plugins to be selected for an account
- [[26190]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26190) Cannot close baskets when all lines have been cancelled
- [[26496]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26496) Budget plan save button doesn't save plans

## Architecture, internals, and plumbing

- [[26904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26904) OPAC password recovery allows regexp in email
- [[26639]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26639) Turn auto_savepoint ON
- [[26673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26673) Remove Perl shebangs from Perl modules
- [[26569]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26569) Use gender-neutral pronouns in systempreference explanation field in DB
- [[26600]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26600) Missing module in Indexer.pm

## Authentication

- [[26191]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26191) Relocate track_login call in Auth.pm (see 22543)

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Add Slack DM notification for when a build succeeds

## Cataloging

- [[11460]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11460) Correction to default itemcallnumber system preference in UNIMARC
- [[26605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26605) Correctly URI-encode query string in call number browse plugin
- [[17515]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17515) Advanced Editor - Rancor - Z39 sources not sorted properly
- [[18051]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18051) Advanced Editor - Rancor - encoding issues with some sources
- [[25353]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25353) Correct eslint errors in additems.js
- [[26613]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26613) In the unimarc_framework.sql file in the it-IT translation there are wrong value fields for 995 r record

## Circulation

- [[25758]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25758) Items scheduled for automatic renewal do not show that they will not renew due to a hold
- [[26583]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26583) Unnecessary code in AddIssue
- [[26627]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26627) Print and confirming a hold can cause an infinite loop
- [[26232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26232) undefined fine grace period kills koha
- [[26675]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26675) Typo in line 341 of process_koc.pl

## Command-line Utilities

- [[26601]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26601) Add utf8 output to text output of overdue_notices.pl

## Database

- [[18050]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18050) Missing constraint on aqbudgets.budget_period_id in aqbudgets

## Fines and fees

- [[26915]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26915) Koha explodes when writing off a fee with FinePaymentAutoPopup
- [[26506]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26506) Koha::Account::pay will fail if $userenv is not set

## Hold requests

- [[26988]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26988) Defer loading the hold pickup locations until the dropdown is selected
- [[26990]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26990) No feedback if holds override is disabled and hold fails
- [[26900]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26900) Fixes Koka::Libraries typo in C4/Reserves.pm
- [[26762]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26762) OPAC hold template markup error
- [[26429]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26429) If a waiting hold has expired the expiration date on the holds page shows for tomorrow

## Installation and upgrade (web-based installer)

- [[26612]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26612) Error during web install for it-IT translation

## MARC Authority data support

- [[26606]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26606) Correctly URI-encode query string in URL loaded after deleting an authority record

## MARC Bibliographic data support

- [[26018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26018) Not all subfields for the following tags are in the same tab (or marked 'ignored')

## MARC Bibliographic record staging/import

- [[26853]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26853) Data lost due to "Data too long for column" errors during MARC import

## OPAC

- [[26766]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26766) Don't show star rating in dialog when saving a checkout note
- [[26619]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26619) Cart - The "Print" button is only translated when you are in "More details" mode
- [[26526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26526) Use of checkout notes not clear in OPAC
- [[26647]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26647) Add translation context to cancel hold button in OPAC
- [[26389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26389) OPAC renewal failure due to automatic renewal does not have a failure message
- [[26184]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26184) Wrap 'items available for pick-up' note when placing a hold in the OPAC in a div element

## Patrons

- [[26594]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26594) Patrons merge problem with restriction
- [[26686]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26686) Sorting for "Updated on" broken on patron's "Notices" tab

## Plugin architecture

- [[24633]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24633) Add support for gitlab searching of plugins
- [[26751]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26751) Fatal exception if only one repo defined
- [[25549]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25549) Broken plugins should not break Koha (Install plugin script/method should highlight broken plugins)

## Searching - Elasticsearch

- [[27070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27070) Elasticsearch - with Elasticsearch 6 searches failing unless all terms are in the same field
- [[26832]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26832) Elasticsearch mappings export should use UTF-8
- [[26487]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26487) Add all MARC flavours for not-onloan-count search field
- [[23828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23828) Elasticsearch - ES - Authority record results not ordered correctly

## Searching - Zebra

- [[26581]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26581) Elasticsearch - Records can be indexed multiple times during returns
- [[26599]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26599) Unused parameter name in POD of ModZebra

## Serials

- [[26987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26987) No property notforloan for Koha::Serial::Item
- [[26604]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26604) "Generate next" button gives error on serials-collection.pl

## Staff Client

- [[26445]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26445) Search results browser in staff has broken link back to results
- [[23432]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23432) Stock rotation: cancelled transfer result in stockrotation failures
- [[26137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26137) Warn on malformed param on log viewer (viewlog.pl)

## System Administration

- [[20804]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20804) Sanitize input of timeout syspref

## Templates

- [[26727]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26727) Fix <p/> appearing in the templates
- [[26696]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26696) Make payment table has a display issue when credits exist
- [[26723]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26723) Improve link text on OverDriveAuthName system preference
- [[26816]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26816) Remove extra space before comma in staff results item list
- [[26726]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26726) Improve link text on Transport cost matrix page
- [[26450]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26450) Typo in UNIMARC field 105 plugin template
- [[26725]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26725) Improve link text on Patron attributes administration page
- [[26756]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26756) Fix quotes showing behind some system preference descriptions
- [[26538]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26538) Display cities list before input text
- [[26449]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26449) Small typo in web installer template
- [[26551]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26551) When importing a framework, the modal heading is too long and runs outside of the dialog

## Test Suite

- [[26589]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26589) t/db_dependent/OAI/Sets.t unit test fails due to OAI-PMH:AutoUpdateSets syspref

## Tools

- [[26557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26557) Batch import fails when incoming records contain itemnumber
- [[25167]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25167) Fix not for loan filter in inventory tool
- [[26784]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26784) Editing a MARC modification template is noisy
- [[26781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26781) Marc Modification Templates treat subfield 0 and no subfield set
- [[8437]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8437) Large database backups and large exports from export.pl fail under plack
- [[9118]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=9118) Show only sensible options when editing a unique holiday


