
# Release Notes for cuyahoga-v25.11.03-01

## About

- [[41102]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41102) Error 500 on the "About" page when biblioserver Zebra configuration is missing

## Accessibility

- [[38643]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38643) Advanced Search input fields need placeholders
- [[40726]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40726) Clicking off of a dropdown in the user menu branch switching closes the dropdown

## Acquisitions

- [[41420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41420) Syntax error in referrer in parcel.tt
- [[41546]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41546) Cannot unarchive suggestions
- [[39514]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39514) If one basket has uncertain prices, all baskets are displayed in red
- [[41088]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41088) Fix translatability for "Add new" and "Remove this" in vue
- [[40942]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40942) Vendor's contacts  not displayed nicely on the vendor detail view
- [[41119]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41119) Autocompletion of basket creator does not work in acquisition-home.pl
- [[20253]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20253) Optionally use buyer's purchase order number from EDIFACT quote in basket name
- [[40334]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40334) When EDIFACT is enabled, one should be able view the corresponding EDIFACT QUOTE and ORDER messages on the Koha Basket page
- [[38208]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38208) Provide a link to ERM agreements and licenses from a vendor record
- [[40333]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40333) When EDIFACT is enabled, one should be able view the corresponding EDIFACT INVOICE message on the Koha Invoice page
- [[7132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7132) Check for duplicates when creating a new record in acquisitions
- [[39980]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39980) Vendors pages are broken when using Koha as a Mojolicious application

## Architecture, internals, and plumbing

- [[42098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42098) EDIFACT edi_cron.pl runs disabled plugins due to bug in Koha::Plugins::Handler::run
- [[40811]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40811) Enhance Koha::File::Transport API
- [[42068]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42068) Update on bug 26993 breaks items deletions with a corrupted foreign key
- [[38384]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38384) General fix for plugins breaking database transactions
- [[38426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38426) Node.js v18 EOL around 25.05 release time
- [[41747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41747) xt/js_tidy is failing on ill js files
- [[41701]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41701) Fix definition of OAI-PMH:DeletedRecord preference in sysprefs.sql
- [[41617]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41617) CSV export from item search results - incorrect spaces after comma separator causes issues
- [[41268]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41268) Circulation rules script has many  conditionals
- [[41043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41043) Use op 'add_form' and 'edit_form' instead of 'add' and 'edit'
- [[41076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41076) Perltidy config needs to be refined to not cause changes with perltidy 20250105
- [[41287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41287) Using locale sorting may have a negative impact on search speeds
- [[41561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41561) "tab" variable in admin/aqbudgetperiods.pl,tt is not used and should be removed
- [[41560]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41560) Useless (and confusing) id attribute on a couple of script tag
- [[41557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41557) LoginFirstname, LoginSurname and emailaddress sent to template but never used
- [[35423]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35423) AuthoritiesMarc: Warnings substr outside of string and Use of uninitialized value $type in string eq
- [[32370]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32370) Provide a generic set of tools for JSON fields
- [[41327]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41327) `yarn css:build` generates several warnings
- [[41545]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41545) JS warning "redeclaration of let filters_options"
- [[27115]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27115) Restarting koha-common fails to restart SIP2 server
- [[41329]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41329) yarn install generates 2 warnings regarding datatables-.net-vue3
- [[41523]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41523) Bug 41409 update statement is not accurate
- [[41328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41328) All KohaTable tables broken in Vue components
- [[40989]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40989) t/db_dependent/OAI/Server.t fails on Debian 13
- [[41238]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41238) Pseudonymize statistic jobs don't update progress
- [[40041]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40041) Update mailmap for 25.11.x
- [[41357]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41357) New SIP2 module is broken
- [[41336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41336) Vue Router warn on Vue datatable pages
- [[41355]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41355) No 'show' view for record sources
- [[41354]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41354) Error when loading "Record sources" Vue app
- [[38311]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38311) DataTables - Simplify the building of the dropdown list filters
- [[38363]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38363) get_template_and_user and checkauth don't use C4::Output for rendering auth pages
- [[41031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41031) Extractor::MARC->new does not check if metadata is a MARC::Record
- [[40680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40680) Many warnings on Perl 5.40 due to importing methods from not yet defined packages
- [[41271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41271) pod_coverage.t unintentionally attempts to launch a SIP server when checking SIPServer.pm
- [[41262]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41262) Duplicate import in Koha::Patron
- [[18584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18584) Our legacy code contains trailing-spaces
- [[41153]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41153) (Follow-up of 40559) Cleanup catalogue/MARCdetail.pl
- [[35451]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35451) Add tablename field to additional_field_values
- [[40995]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40995) Patron search autocomplete adds extraneous spacing and punctuation when patron lacks surname
- [[32176]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32176) Correctly display patrons when selected after autocomplete (was js/patron-autocomplete.js need another option)
- [[40958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40958) Move patron_to_html (from js-patron-format.inc) to a standalone JS file
- [[31149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31149) Use dayjs to parse dates
- [[38489]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38489) EDI should be updated to use the new FTP/SFTP Servers management page
- [[39190]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39190) Rework new (S)FTP classes to be polymorphic classes
- [[38201]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38201) VueJS architecture rethink
- [[40286]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40286) Make C4::Auth::checkpw_internal use Koha::Patrons->find_by_identifier
- [[38936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38936) Move suppressed record redirection into a sub
- [[30915]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30915) "Scalar" TT plugin no longer needed
- [[35761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35761) Add an administration editor for FTP and SFTP servers
- [[39488]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39488) Update Koha::Object(s) to allow for polymorphic classing
- [[40663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40663) Package GD::Barcode::QRcode@2.01
- [[40636]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40636) C4::Reserves::CancelExpiredReserves behavior depends on date it is run
- [[35467]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35467) NewsLog should be renamed
- [[40037]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40037) Redundant check in `notices_content` hook handling
- [[40405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40405) systempreferences.value cannot be set to NULL
- [[40337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40337) checkprevcheckout must be defined as ENUM at DB level

## Authentication

- [[33782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33782) OAuth2/OIDC identity providers code is not covered by unit tests
- [[40943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40943) Store session_id in userenv
- [[37711]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37711) IdP auto-register should work on the staff interface
- [[30724]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30724) Add ability for administrator to reset a users 2FA

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Skip repo version check for bywater-koha-devel
- NOT IN BUGZILLA - GitHub Actions - Skip stress tests for devel
- NOT IN BUGZILLA - GitHub Actions - check-repo should pass for all pull requests
- NOT IN BUGZILLA - GitHub Actions - Fail if any commits in pull request do not start with 'BWS-PKG - '
- NOT IN BUGZILLA - GitHub Actions - Split unit tests into separate runs for perl and cypress tests
- NOT IN BUGZILLA - GitHub Actions - Remove community GHA for closing pull request
- NOT IN BUGZILLA - Update DBIC Schema files
- NOT IN BUGZILLA - GitHub Actions - Require dbic for building packages
- NOT IN BUGZILLA - GitHub Actions - Test for needed updates to dbic schema files
- NOT IN BUGZILLA - Supress es deprecations in logs
- NOT IN BUGZILLA - GitHub Actions - Run github actions for pull requests
- NOT IN BUGZILLA - GitHub Actions - Update aptly token name
- NOT IN BUGZILLA - GitHub Actions - 'Notify package importer' step should fail if apt api response code is a failure code
- NOT IN BUGZILLA - GitHub Actions - Update aptly token name
- NOT IN BUGZILLA - Add fix for failing bookingsModalDatePicker_spec.ts
- NOT IN BUGZILLA - Add es-indexer files to logrotate file
- NOT IN BUGZILLA - GHA - Use koha_tests_runner.pl - Fix PBP violation
- NOT IN BUGZILLA - Fix number of tests in t/db_dependent/Circulation.t
- NOT IN BUGZILLA - Fix items_last_borrower table structure
- NOT IN BUGZILLA - GHA - Use koha_tests_runner.pl
- NOT IN BUGZILLA - RMaint: Tidy files for xt/perltidy.t failures
- NOT IN BUGZILLA - 25.11.00: Update kohastructure.sql
- NOT IN BUGZILLA - 25.11.00: Update history.txt
- NOT IN BUGZILLA - 25.11.00 Update contributors.yaml

## Cataloging

- [[40154]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40154) Deleting an item does not warn about an item level hold
- [[41588]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41588) Link from 856$u breaks with leading or trailing spaces
- [[41475]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41475) 500 error when placing a hold on records with multiple 773 entries
- [[34879]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34879) ./catalogue/getitem-ajax.pl appears to be unused
- [[40031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40031) Creation of a new MARC modification template should redirect to have the template ID in the URL
- [[41047]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41047) Current library and home library sort by code instead of description
- [[40777]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40777) 500 Error: Something went wrong when loading the table Should Exit Cleanly
- [[41081]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41081) Link from 856$u points to http://%20%20%20%20
- [[41015]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41015) Z39.50 searching in Advanced Cataloging Editor is not clearly labeled
- [[40017]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40017) Z39.50 search: Allow leader and specific control field positions in Additional fields
- [[39880]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39880) Add shelving location to cn_browser.tt
- [[29980]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29980) Validate ISBN when cataloguing bibliographic records
- [[38330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38330) Make bib-level suppression a biblio table field instead of part of a MARC tag
- [[39507]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39507) Make the MARC21 008 plugin more precise for MU

## Circulation

- [[42062]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42062) Patron column missing from checkout history on biblio record
- [[30331]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30331) Allow RenewalPeriodBase behavior to differ between manual and automatic renewals
- [[26993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26993) Allow StoreLastBorrower to retain a locally-defined number of previous borrowers
- [[40364]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40364) Add permission for viewing patron holds history
- [[32682]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32682) Add permission for viewing patron reading history
- [[41055]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41055) Missing accesskey attribute for print button (shortcut P)
- [[40134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40134) Fix and optimise 'Any item' functionality of bookings
- [[41457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41457) Hold history table does not deal with column visibility correctly
- [[41035]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41035) bundle_remove click handler in returns.tt has invalid path component "item"
- [[41539]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41539) Include item barcode in waiting hold message on patron record
- [[39584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39584) Booking post-processing time cuts into circulation period
- [[39916]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39916) The 'Place booking' modal should have cypress tests
- [[16131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16131) Error messages for library transfers show with bullet points
- [[41456]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41456) Item type filter on the hold history view does not work correctly
- [[41352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41352) Bookings to Collect Help does not take you to the correct place in the manual
- [[41451]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41451) Hold history search fails when itemtype column present
- [[40949]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40949) Bookings to collect shouldn't tell staff to check in items
- [[41211]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41211) Cannot cancel patron holds in some cases
- [[39642]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39642) Add SMS number to hold found modals on return.tt
- [[40665]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40665) Add booking_id field to issues to link checkouts to bookings that were fulfilled by them
- [[34596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34596) Items in transit should not show up in the holds queue
- [[37661]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37661) Disable/Enable Bookings
- [[20644]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20644) Per itemtype setting for CheckPrevCheckout
- [[23010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23010) If an item is checked out or in transit it should not be able to be marked withdrawn

## Command-line Utilities

- [[41315]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41315) Using patron-homelibrary option for overdue notices may not send notices to all branches
- [[39532]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39532) Script debar_patrons_with_fines.pl should not use MANUAL restriction type
- [[40964]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40964) koha-elasticsearch is missing --where option
- [[38306]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38306) Make automatic_renewals.pl cronjob quiet if EnhancedMessagingPreferences syspref is off
- [[38115]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38115) Add FTP support to export_records.pl
- [[41099]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41099) koha-mysql doesn't work out of the box on Debian 13
- [[40545]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40545) Add a CLI script to manually reset 2FA settings
- [[39740]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39740) [Follow-up of 36932] Split dev_install into git_install and debug_mode
- [[40144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40144) `sip_cli_emulator.pl` warnings
- [[39961]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39961) koha-create doesn't start all queues

## Course reserves

- [[40699]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40699) Preferred name not displayed for instructors in course reserves in staff interface

## Database

- [[41409]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41409) Streetnumber has a different data type in borrower_modifications
- [[41421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41421) Bug 35830 DB update must be idempotent
- [[36033]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36033) Table pseudonymized_transactions needs more indexes

## Developer documentation

- [[42421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42421) Only run GitHub Actions for closing pull requests (close-pr.yml) on the community repo

## ERM

- [[41120]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41120) Click on New data provider breaks functionality
- [[41520]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41520) Using additional fields on ERM agreements results in an error when loading the agreements table
- [[41063]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41063) Additional fields are broken in Vue (values entered are not saved)
- [[41103]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41103) Click on data providers platform breaks functionality
- [[40141]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40141) Add "Run" and "Test" buttons to data provider toolbar
- [[36831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36831) Add support for .txt files to the KBART import tool
- [[36942]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36942) Throw an exception if a KBART file can't be read

## Hold requests

- [[41880]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41880) Logs for moved holds don't indicate original bib number/item number
- [[41959]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41959) Holds queue builder doesn't always check all holds when using transport cost matrix
- [[41781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41781) Holds queue builder ( build_holds_queue.pl ) fails if HoldsQueueParallelLoopsCount is greater than 1
- [[40769]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40769) Highlight hold fees when placing a hold from the staff interface
- [[41416]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41416) Poor performance when clicking 'Update hold(s)' on request.pl for records with many holds
- [[41432]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41432) Add prefetch to improve performance of holds page
- [[40613]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40613) Allow ungrouping holds
- [[40551]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40551) Make patron page holds table use API endpoint for cancellation
- [[40552]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40552) Allow selecting all holds from a group
- [[40529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40529) Update how hold groups work
- [[40517]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40517) Allow grouping existing holds
- [[40335]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40335) Holds queue does not allow multiselect
- [[15516]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15516) Allow to place a hold on first available item from a group of titles
- [[40929]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40929) Can't call method "borrowernumber" on an undefined value at opac-modrequest.pl
- [[31698]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31698) Add ability to move a hold to a new bibliographic record/item
- [[36135]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36135) Add tool to batch modify holds

## I18N/L10N

- [[41689]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41689) "Staff note" and "OPAC" message types in patron files untranslatable
- [[40287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40287) Fix untranslatable strings in more statistics wizards

## ILL

- [[41204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41204) OpenURL ILL no longer defaults to Standard if FreeForm
- [[41281]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41281) ILL request metadata doesn't show if falsy
- [[41512]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41512) ILLCheckAvailability stage table doesn't render
- [[41478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41478) AutoILLBackendPriority - Unauthenticated request shows backend form if wrong captcha
- [[41465]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41465) Unauthenticated request does not display 'type' correctly
- [[41009]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41009) When editing an ILL request, the user is returned to the list
- [[41054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41054) Standard ILL form should consider eISSN field
- [[37901]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37901) Add ILL pseudonymization
- [[40005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40005) Manage request page should show accessurl
- [[39918]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39918) Unauthenticated request data should show when editing a request
- [[40012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40012) Standard form missing publisher for journal articles
- [[40856]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40856) Improve Standard backend metadata retrieval
- [[40024]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40024) Backends that don't support get_requested_partners capability show a '(0)' in status
- [[40855]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40855) Standard backend uses plain SQL
- [[40850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40850) Add `Koha::ILL::Request->add_or_update_attributes`
- [[40262]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40262) ILL - Save the fact that copyright clearance has been confirmed by the patron

## Installation and upgrade (command-line installer)

- [[40292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40292) SQL syntax error when upgrading to 25.05 on MariaDB 10.3, RENAME COLUMN unsupported

## Installation and upgrade (web-based installer)

- [[40006]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40006) Upgrading install.pl shows code vs HTML

## Label/patron card printing

- [[40366]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40366) Update the label export process to avoid Greybox modal
- [[40412]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40412) Update the patron card export process to avoid Greybox modal

## Lists

- [[39145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39145) Differentiate between deleting or transferring public and shared lists

## MARC Authority data support

- [[33296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33296) Linker should search for authority records with an appropriate 008/14,15,16 value
- [[40119]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40119) Merge should not leave empty 6XX subfield $2 (MARC 21)

## MARC Bibliographic data support

- [[41000]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41000) Update label on record detail pages for 041$d - "Spoken language" to "Sung or spoken language"
- [[39860]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39860) Add a way to allow for additional/custom MARC fields in the record display
- [[40272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40272) Add an alert for incorrect (MARC21) fixed-length control fields
- [[40284]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40284) MARC21: Adjust maxlength for 005, 006 and 007

## Notices

- [[39781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39781) Cannot limit by library when creating custom patron email sent via patron details page
- [[42083]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42083) Email and SMS messages from patron record should have distinct permissions
- [[40960]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40960) Only generate a notice for patrons about holds filled if they have set messaging preferences
- [[28308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28308) Select 'Days in advance' = 0 for Advance notice effectively disables PREDUE notices
- [[40719]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40719) Explicit turn off RELATIVE file paths for plugins for user-entered templates
- [[39280]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39280) Generalize ODUE notice text - remove "If an item becomes more than 30 days overdue, you will be unable to use your library card until the item is returned."
- [[40305]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40305) Collected and change variables are inconsistent in controllers and notice templates

## OPAC

- [[42020]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42020) (Bug 39482 follow-up) Library info link shown in OPAC without OpacLibraryInfo and library URL
- [[41655]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41655) Local OPAC covers are not displayed in OPAC lists
- [[23308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23308) Contents of "OpacMaintenanceNotice" HTML escaped on display
- [[40822]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40822) Custom cover images not displayed in search results
- [[40619]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40619) Remove OverDrive star ratings from the OPAC
- [[30633]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30633) Move OPACHoldingsDefaultSortField to table settings configuration
- [[40221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40221) Replace layout tables for component part display

## Packaging

- [[40164]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40164) Add Template::Plugin::JSON to handle JSON in Template Toolkit

## Patrons

- [[42423]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42423) Submit button in patron search from header never submits
- [[41040]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41040) Empty patron search from the header should not trigger a patron search
- [[41752]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41752) Guarantor first name and guarantor surname mislabeled in system preferences
- [[36360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36360) Link ILL requests to surviving patron record when patrons are merged
- [[29768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29768) hidepatronname hides guarantor name on borrower edit screen
- [[41497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41497) ul.patronbriefinfo inconsistent in coding structure
- [[40794]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40794) Add an id to the div containing payments tabs
- [[41411]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41411) Streetnumber field is limited to 10 characters despite being tinytext
- [[39014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39014) Storing a guarantee fails due to TrackLastPatronActivityTriggers "creating a patron"
- [[41363]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41363) Don't hide patron category limitation warning behind icon
- [[41145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41145) Logging patron attributes logs even if there's no changes
- [[26258]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26258) Circulation tabs inconsistent with counters
- [[40082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40082) PatronDuplicateMatchingAddFields isn't respected in the OPAC or the API
- [[33647]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33647) Display borrowers.lastseen in patron record
- [[40245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40245) Support option to display firstname in patron search results when different than preferred_name
- [[35830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35830) Add separate permission for Merging Patrons
- [[40936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40936) Add index for default patron sort order

## Plugin architecture

- [[39522]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39522) Add hooks to allow 'Valuebuilder' plugins to be installable
- [[41684]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41684) notices_content hook is not checking if individual plugins are enabled and is reloading plugins
- [[41603]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41603) Plugin hook causing DB locks when cancelling holds
- [[40983]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40983) Remove deprecated syntax for 'after_biblio_action' hooks

## Point of Sale

- [[41408]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41408) POS Inline Editing Triggers Form Submission on Enter Key

## Reports

- [[41292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41292) Add "force_password_reset_when_set_by_staff" to the allowed column name list

## REST API

- [[29668]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29668) Add API route to create a basket
- [[28701]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28701) primary_contact_method not part of the REST API spec
- [[40550]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40550) Add /holds/cancellation_bulk endpoint
- [[39816]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39816) Allow embedding `days_late` in baskets
- [[38931]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38931) Add endpoints for individual credits and debits
- [[40512]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40512) Add maxLength to the erm agreements definition
- [[40511]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40511) Add maxLength to the eHoldings title definition
- [[40434]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40434) Add maxLength to the vendor definition

## Searching

- [[36947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36947) Sort Elasticsearch/Zebra facets according to configurable locale instead of using Perl's stringwise/bytewise sort

## Searching - Elasticsearch

- [[40966]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40966) 'whole_record' and 'weighted_fields' not passed around
- [[38345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38345) Restore support for OpenSearch
- [[40980]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40980) Clicking a search facet without logging in may trigger a cud-login error
- [[40890]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40890) Make batch_size configurable for koha-es-indexer
- [[39636]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39636) Add options to compare_es_to_db script
- [[39526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39526) Unify system preference variable names for Elasticsearch

## Self checkout

- [[41646]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41646) Self-checkin displaying too much whitespace due to incorrect HTML

## Serials

- [[36466]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36466) Incorrect date value stored when "Published on" or "Expected on" are empty
- [[36136]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36136) Flatpickr allows selecting date from the past on copied serial subscriptions
- [[40070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40070) Make appending published date to serial enumeration optional on detail pages

## SIP2

- [[42053]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42053) Bug 37893 DBUpdate does not always add the new userflags/permissions
- [[41458]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41458) SIP passes UID instead of GID to Net::Server causing error
- [[41214]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41214) Cash register should only show if UseCashRegisters sys pref is enabled
- [[40455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40455) A patron information  request fails when no currency is set

## Staff interface

- [[42048]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42048) Reflected XSS in patron search saved link
- [[41594]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41594) Can access invoice-files.pl even when AcqEnableFiles is disabled
- [[41679]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41679) Stock rotation repatriation modal can conflict with holds modal
- [[41798]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41798) Cannot enable 'passive' mode in File Transports for FTP
- [[41422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41422) New FilterSearchResultsByLoggedInBranch doesn't fully translate
- [[41206]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41206) Add collection to transfers to receive
- [[40933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40933) Add SMS support under Add message feature
- [[41494]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41494) Rename "Koha administration" to "Administration" for consistency
- [[41484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41484) Wording of 'On hold', 'Booked', and 'Recalled' in issues table can be confusing
- [[41427]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41427) Terminology: branch should be library in FilterSearchResultsByLoggedInBranch
- [[30148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30148) Pipe separated contents are hard to customize (staff interface)
- [[40288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40288) patron details in patron sidebar overflow the sidebar
- [[40086]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40086) Table settings for Article Requests tables
- [[38438]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38438) Make Add persistent selections and batch operations to item search optional
- [[40615]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40615) Update mention of 'My virtual card' in OPACVirtualCard description
- [[40866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40866) Corrections to override logging
- [[40565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40565) Column filters on the item search do not work
- [[37883]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37883) Add a filter for staff search results to filter by library

## System Administration

- [[42263]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42263) Missing import of JSON::encode_json in Koha::File::Transport::SFTP [25.11.x]
- [[41261]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41261) XSS vulnerability in opac/unAPI
- [[41431]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41431) Circulation rule notes dropping when editing rule
- [[19690]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19690) Smart rules: Term "If any unavailable" is confusing
- [[28495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28495) Add hint about whitespace usage upon library creation
- [[38876]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38876) Typo in UpdateNotForLoanStatusOnCheckout description
- [[41332]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41332) Add new option for Greek (el) to the 'KohaManualLanguage' System Preference
- [[41190]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41190) "Default checkout, hold and return policy" needs a space in title
- [[39482]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39482) Link to edit OpacLibraryInfo from library edit page broken
- [[37893]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37893) Migrate some SIP configuration into the staff interface
- [[39825]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39825) Add a direct link to items tag in MARC bibliographic framework page
- [[38863]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38863) Show bookings options on itemtypes.pl
- [[40453]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40453) Allow newly-added item type translations to be edited
- [[40418]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40418) Update the item type translation process to avoid Greybox modal

## Task Scheduler

- [[37402]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37402) Task scheduling fails if you don't use the correct time format

## Templates

- [[41764]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41764) ISSN hidden input missing from Z39.50 search form navigation
- [[41340]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41340) Better translatability on 'batch_item_record_modification.inc'
- [[41350]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41350) Terminology: Biblio was already issued
- [[41677]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41677) Use template wrapper for tabs: OAI repositories
- [[40703]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40703) Replace data-toggle by data-bs-toggle
- [[32288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32288) Capitalization: RDA Carrier, etc.
- [[41586]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41586) Spacing problem in display of patron names
- [[41347]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41347) Terminology: Item had a reserve waiting
- [[32285]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32285) Punctuation: Completeness of the reproduction code␠:, ...
- [[39715]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39715) Do not quote DataTables options
- [[41398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41398) Typo: Tagret item is not in the local hold group
- [[41397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41397) Terminology: Target item is not reservable
- [[38739]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38739) Templates not ending with include intranet-bottom.inc in staff interface
- [[41339]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41339) Typo 'Too many checkout'
- [[41395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41395) Terminology: Target item cannot be reserved from other branches
- [[41396]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41396) Capitalization: 'Transport Settings' and other
- [[40567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40567) Correct eslint errors in recalls.js
- [[41348]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41348) Capitalization: "List Files" and others
- [[40422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40422) Remove Greybox assets from the staff interface
- [[32287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32287) Capitalization: Printing and/or Publishing Information Transcribed as Found in the Colophon:␠
- [[32296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32296) Capitalization: Specification of Dimensionality,...
- [[39947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39947) Use bg-*-subtle in preference to bg-* Bootstrap classes

## Test Suite

- [[41449]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41449) Reserves.t may fail when on shelf holds are restricted
- [[40946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40946) "Aborted connection 42 to db" from Koha/Z3950Responder/ZebraSession.t
- [[40947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40947) "Aborted connection 42 to db" from t/db_dependent/www/search_utf8.t
- [[39745]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39745) Wrong system preference 'language' in test suite
- [[41710]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41710) SearchEngine/Elasticsearch/Search.t does not rollback properly
- [[41682]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41682) Syspref discrepancies between new and upgraded installs
- [[41362]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41362) Allow Cypress tests to use KOHA_USER and KOHA_PASS as override
- [[40446]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40446) DB config used by Cypress (mysql2) is not configurable
- [[41274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41274) Incremental test runs not properly skipping Schema files
- [[41003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41003) Missing Cypress tests for patron display
- [[39877]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39877) CI - Incremental runs
- [[40950]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40950) Don't forbid 'falsy' in codespell
- [[40809]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40809) JS warning should make Cypress tests fail
- [[40872]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40872) opac/unapi type not detected by tidy.pl
- [[40380]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40380) Koha/Patrons/Import.t generates warnings
- [[39876]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39876) Centralize listing of files from our codebase

## Tools

- [[41883]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41883) Modifications using batch hold modification tool aren't logged
- [[40905]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40905) Past unique holidays not shown when enabling Show past checkbox
- [[41163]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41163) Circulation logs record issuing branch in database but show logged-in branch in log viewer
- [[40846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40846) Job Status should not be Failed if a record import result in a item update
- [[41334]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41334) Move modified_holds tables column settings under Tools section
- [[41438]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41438) Batch hold tool: Suspended holds are unsuspended when making other changes to holds
- [[34561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34561) Move IntranetReportsHomeHTML to HTML customizations

## Web services

- [[36561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36561) Inappropriate permission for "/api/v1/auth/password/validation"


