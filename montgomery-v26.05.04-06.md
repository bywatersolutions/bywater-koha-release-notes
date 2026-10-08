
# Release Notes for montgomery-v26.05.04-06

## About

- [[43177]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43177) Use archived link for Bridge Material Type Icon Set

## Acquisitions

- [[43211]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43211) Koha hangs when receiving order with AcqCreateItem set to 'receiving an order'
- [[42605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42605) Acquisition Items not listed during receipt
- [[43053]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43053) Vendor payment methods are not displaying correctly
- [[42827]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42827) Items expected column in parcels.pl always displays 0

## Architecture, internals, and plumbing

- [[40901]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40901) koha-common.service bundles all sub-daemons under one systemd service instead of per-instance services
- [[43470]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43470) REST Basic Auth allows silent 2FA secret takeover
- [[43426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43426) admin/item_circulation_alerts.pl cud-toggle performs no authentication check at all (7.5 HIGH)
- [[43424]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43424) REST Basic Auth bypasses account lockout (8.1 HIGH)
- [[43326]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43326) Stored XSS in patron account note (accountlines.note)
- [[42674]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42674) OS command injection via `jobid` in Task Scheduler (`tools/scheduler.pl`)
- [[43091]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43091) Staff-only Vue island chunks are emitted into the OPAC dist directory
- [[43088]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43088) Koha::File::Transport lacks a consistent current_directory() accessor across FTP/SFTP/Local
- [[43078]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43078) File transport SFTP backend returns inconsistent list() structure compared to FTP/Local backends
- [[43168]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43168) Incorrect error output when staging a file
- [[43159]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43159) Regression to @INC handling by bug 39740 undoing bug 25778
- [[43103]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43103) Batch item modification and patron deletion query IDs as OR query chains
- [[41717]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41717) Update PDF::Reuse and PDF::Reuse::Barcode to the latest version
- [[43401]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43401) Makefile.PL doesn't compile vue OPAC js to the right directory
- [[41681]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41681) bulkmarcimport.pl reports an incorrect number of MARC records processed
- [[42396]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42396) Replace C4::Stats::UpdateStats calls with Koha::Statistic->store

## Authentication

- [[42719]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42719) OAuth/OIDC login crashes with 500 when no CGISESSID cookie exists (IdP-initiated flow)

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Pin koha-dpkg to the last bookworm image until the trixie image can trust the Koha repo
- NOT IN BUGZILLA - GitHub Actions - Restore AcqCreateItem string value lost in 26.05.x backport
- NOT IN BUGZILLA - Point KTD at misc4dev main until the 25.11 images are rebuilt
- NOT IN BUGZILLA - Revert "BWS-PKG - Point KTD at the misc4dev branch that knows about koha-core"
- NOT IN BUGZILLA - GitHub Actions - Set the default branch on bywater-koha-future too
- NOT IN BUGZILLA - Add upgrade info to the Server information tab of the About page
- NOT IN BUGZILLA - Update about page for ByWater specifics

## Cataloging

- [[35729]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35729) Koha needs to handle ISBNs starting with 979 for cover images

## Circulation

- [[42565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42565) GetIssuingCharges returns undef when rentalcharge is NULL
- [[43119]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43119) Checkout and hold action logs are not displayed correctly

## Command-line Utilities

- [[42298]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42298) "No automatic renewal before" falls back to "No renewal before" if former is greater than the latter

## ILL

- [[42845]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42845) Access to ILL requires parameters => 'manage_sysprefs'
- [[43139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43139) ILL requests Widget should sort desc to display newest records

## Lists

- [[43192]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43192) Lists cannot be deleted from OPAC

## OPAC

- [[30759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30759) Add hint about the data that is sent via the Google Books API to OPACSuggestionAutoFill
- [[43134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43134) Standardize use of colon in OPAC advanced search page
- [[38361]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38361) Gender field does not include a Required if the field is set to required in  PatronSelfRegistrationBorrowerMandatoryField

## Patrons

- [[20573]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20573) Patron receives membership expiry notice but 'will expire soon' alert doesn't show for staff at checkout
- [[43110]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43110) When a patron has a value for advance notices the checkboxes are enabled on the details view
- [[43005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43005) Regression: Changing category from details page section doesn't trigger expiration update

## Reports

- [[41920]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41920) Limit number of concurrent reports that can be run simultaneously for an instance of Koha
- [[43267]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43267) Batch operations from datatables report view should only send visible results (same as standard view)

## Searching

- [[43320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43320) Don't repeat a quoted search with more quotes when no results

## Serials

- [[40201]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40201) Subscription search form on the start page is missing additional fields

## Staff interface

- [[40668]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40668) Library groups and seperateholdings with itemgroups prevents adding items to itemgroup
- [[41116]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41116) Selectors are inconsistently structured in hold found modals
- [[42632]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42632) Cannot manage bundles after filters are displayed

## Templates

- [[43570]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43570) Memory leak in SafeURL and HtmlScrubber Template::Toolkit filters
- [[37441]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37441) ShowAlerts msg not escaped in tools uploads

## Test Suite

- [[43669]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43669) Selenium tests can fail if server is still restarting
- [[43082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43082) Flaky action_logs.t object filter test due to default LIKE matching

## Tools

- [[43173]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43173) Terminology: Log viewer - "Modify cardnumber" should be " Modify card number"
- [[42973]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42973) Additional contents ordering ignores "Appear in position" when sorting news


