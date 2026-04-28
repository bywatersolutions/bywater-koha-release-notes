
# Release Notes for mainlib-v25.11.03-01

## Acquisitions

- [[41420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41420) Syntax error in referrer in parcel.tt

## Architecture, internals, and plumbing

- [[41747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41747) xt/js_tidy is failing on ill js files
- [[41701]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41701) Fix definition of OAI-PMH:DeletedRecord preference in sysprefs.sql
- [[41617]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41617) CSV export from item search results - incorrect spaces after comma separator causes issues
- [[41268]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41268) Circulation rules script has many  conditionals
- [[41076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41076) Perltidy config needs to be refined to not cause changes with perltidy 20250105
- [[41287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41287) Using locale sorting may have a negative impact on search speeds
- [[41561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41561) "tab" variable in admin/aqbudgetperiods.pl,tt is not used and should be removed
- [[41560]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41560) Useless (and confusing) id attribute on a couple of script tag
- [[41557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41557) LoginFirstname, LoginSurname and emailaddress sent to template but never used
- [[35423]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35423) AuthoritiesMarc: Warnings substr outside of string and Use of uninitialized value $type in string eq

## Authentication

- [[33782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33782) OAuth2/OIDC identity providers code is not covered by unit tests

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
- NOT IN BUGZILLA - GitHub Actions - 'Notify package importer' step should fail if apt api response code is a failure code
- NOT IN BUGZILLA - RMaint: Tidy files for xt/perltidy.t failures

## Cataloging

- [[40154]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40154) Deleting an item does not warn about an item level hold
- [[41588]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41588) Link from 856$u breaks with leading or trailing spaces
- [[41475]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41475) 500 error when placing a hold on records with multiple 773 entries
- [[34879]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34879) ./catalogue/getitem-ajax.pl appears to be unused
- [[40031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40031) Creation of a new MARC modification template should redirect to have the template ID in the URL

## Circulation

- [[41055]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41055) Missing accesskey attribute for print button (shortcut P)
- [[40134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40134) Fix and optimise 'Any item' functionality of bookings
- [[41457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41457) Hold history table does not deal with column visibility correctly
- [[41035]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41035) bundle_remove click handler in returns.tt has invalid path component "item"
- [[41539]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41539) Include item barcode in waiting hold message on patron record

## Command-line Utilities

- [[41315]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41315) Using patron-homelibrary option for overdue notices may not send notices to all branches

## Developer documentation

- [[42421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42421) Only run GitHub Actions for closing pull requests (close-pr.yml) on the community repo

## ERM

- [[41120]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41120) Click on New data provider breaks functionality

## Hold requests

- [[41781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41781) Holds queue builder ( build_holds_queue.pl ) fails if HoldsQueueParallelLoopsCount is greater than 1
- [[40769]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40769) Highlight hold fees when placing a hold from the staff interface

## I18N/L10N

- [[41689]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41689) "Staff note" and "OPAC" message types in patron files untranslatable

## ILL

- [[41204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41204) OpenURL ILL no longer defaults to Standard if FreeForm
- [[41281]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41281) ILL request metadata doesn't show if falsy
- [[41512]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41512) ILLCheckAvailability stage table doesn't render
- [[41478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41478) AutoILLBackendPriority - Unauthenticated request shows backend form if wrong captcha
- [[41465]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41465) Unauthenticated request does not display 'type' correctly

## Notices

- [[39781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39781) Cannot limit by library when creating custom patron email sent via patron details page
- [[42083]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42083) Email and SMS messages from patron record should have distinct permissions
- [[40960]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40960) Only generate a notice for patrons about holds filled if they have set messaging preferences
- [[28308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28308) Select 'Days in advance' = 0 for Advance notice effectively disables PREDUE notices

## OPAC

- [[41655]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41655) Local OPAC covers are not displayed in OPAC lists
- [[23308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23308) Contents of "OpacMaintenanceNotice" HTML escaped on display
- [[40822]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40822) Custom cover images not displayed in search results

## Patrons

- [[42423]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42423) Submit button in patron search from header never submits
- [[41040]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41040) Empty patron search from the header should not trigger a patron search
- [[41752]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41752) Guarantor first name and guarantor surname mislabeled in system preferences
- [[36360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36360) Link ILL requests to surviving patron record when patrons are merged
- [[29768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29768) hidepatronname hides guarantor name on borrower edit screen

## Plugin architecture

- [[41684]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41684) notices_content hook is not checking if individual plugins are enabled and is reloading plugins

## REST API

- [[41700]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41700) Checkouts note_date has incorrect format in swagger definitions

## Searching - Elasticsearch

- [[40966]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40966) 'whole_record' and 'weighted_fields' not passed around

## Serials

- [[36466]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36466) Incorrect date value stored when "Published on" or "Expected on" are empty
- [[36136]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36136) Flatpickr allows selecting date from the past on copied serial subscriptions

## SIP2

- [[41458]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41458) SIP passes UID instead of GID to Net::Server causing error
- [[41214]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41214) Cash register should only show if UseCashRegisters sys pref is enabled

## Staff interface

- [[42048]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42048) Reflected XSS in patron search saved link
- [[41594]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41594) Can access invoice-files.pl even when AcqEnableFiles is disabled
- [[41679]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41679) Stock rotation repatriation modal can conflict with holds modal
- [[41798]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41798) Cannot enable 'passive' mode in File Transports for FTP
- [[41422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41422) New FilterSearchResultsByLoggedInBranch doesn't fully translate
- [[41206]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41206) Add collection to transfers to receive
- [[40933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40933) Add SMS support under Add message feature

## System Administration

- [[41261]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41261) XSS vulnerability in opac/unAPI
- [[19690]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19690) Smart rules: Term "If any unavailable" is confusing

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

## Test Suite

- [[41449]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41449) Reserves.t may fail when on shelf holds are restricted
- [[40946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40946) "Aborted connection 42 to db" from Koha/Z3950Responder/ZebraSession.t
- [[40947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40947) "Aborted connection 42 to db" from t/db_dependent/www/search_utf8.t
- [[39745]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39745) Wrong system preference 'language' in test suite
- [[41710]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41710) SearchEngine/Elasticsearch/Search.t does not rollback properly
- [[41682]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41682) Syspref discrepancies between new and upgraded installs

## Tools

- [[40905]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40905) Past unique holidays not shown when enabling Show past checkbox
- [[41163]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41163) Circulation logs record issuing branch in database but show logged-in branch in log viewer


