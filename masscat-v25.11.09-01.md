
# Release Notes for masscat-v25.11.09-01

## About

- [[42453]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42453) "About Koha" breaks if Elasticsearch is used but unavailable

## Accessibility

- [[42231]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42231) Fix accessibility issues in OPAC summary table
- [[42234]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42234) OPAC checkout history page table header contains no text
- [[42229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42229) Form label used on non-form elements on opac-memberentry.tt pages
- [[42232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42232) Fieldset with missing legend on OPAC account messaging settings page (opac-messaging.tt)
- [[42233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42233) OPAC suggestions table header contains no text
- [[42299]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42299) OPAC detail page: star ratings has no associated label

## Acquisitions

- [[42225]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42225) On sites with many vendors spent.pl cannot load
- [[42571]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42571) Sending EDI order results in variable not available warnings
- [[41070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41070) No warning when filling no fund while importing in a basket from a file

## Architecture, internals, and plumbing

- [[42551]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42551) C3 merge error when syntax checking some installed plugins
- [[42736]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42736) SQL Injection in reports/cat_issues_top.pl via Criteria / Filter request parameters (unvalidated string context, no placeholders)
- [[42904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42904) Prevent XSS in patron restriction comments
- [[42800]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42800) Potential XSS in shelf list in the erm module
- [[42847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42847) SIP authentication ignored after initial successful connection
- [[42471]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42471) [CVE-2026-41921] /cgi-bin/koha/suggestion/suggestion.pl Multiple Parameters Stored Cross-Site Scripting
- [[30233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30233) [CVE-2026-19780][ZDI-CAN-29165] Remote code execution in user-supplied regex
- [[42746]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42746) Stored SQL injection via unvalidated 'agefield' in automatic_item_modification_by_age (C4::Items::ToggleNewStatus)
- [[42747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42747) Stored SQL injection via patroncard layout image_name (patroncards/edit-layout.pl -> create-pdf.pl)
- [[42866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42866) SQL Injection in Koha/AdditionalContents.pm search_for_display via the patron lang value (stored / second-order, executed on issue-slip print, unvalidated string context, no placeholder)
- [[42749]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42749) SQL injection in acqui/parcels.pl via the orderby parameter (ORDER BY direction) reaching C4::Acquisition::GetInvoices
- [[43019]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43019) OPAC pages limited to library are readable by unauthenticated users

## Bywater Only

- NOT IN BUGZILLA - [RMaint] Remove calls to CSPNonce (not implemented)
- NOT IN BUGZILLA - Bug 43470: (follow-up) DRY up the two-factor setup route checks
- NOT IN BUGZILLA - Bug 43426: Use check_cookie_auth to return 403
- NOT IN BUGZILLA - Bug 43424: Make REST API respect account lockout
- NOT IN BUGZILLA - Bug 42674: Validate job_id when deleting a job
- NOT IN BUGZILLA - Bug 37441: [25.11] ShowAlerts msg not sanitized in tools uploads

## Cataloging

- [[42874]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42874) z3950_auth_search is losing index parameter
- [[42846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42846) Koha::Database::DataInconsistency typo for biblioitemnumber in MARC
- [[42531]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42531) Repeatable field values with long text do not wrap on staff record detail page
- [[40225]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40225) The --send-all option in the stockrotation job fails if there are no items to rotate at all
- [[41829]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41829) Tag editor button has wrong id on copied MARC field when value builder plugin is used
- [[42178]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42178) The Close button submits the remove from bundle form

## Circulation

- [[41889]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41889) /checkouts?checked_in=1 errors when patron_id is null
- [[41358]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41358) action logs info column should always store JSON
- [[42930]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42930) Overdues (circ/overdue.pl) incorrectly shows bibliographic record title in patron column instead of the patron's title (salutation)
- [[42659]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42659) Multiple numbers and parts shown incorrectly on checkin screen
- [[41992]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41992) Checkout History remembering Last Page

## Command-line Utilities

- [[42640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42640) Script search_for_data_inconsistencies.pl should use binmode UTF-8

## ERM

- [[42933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42933) ERM - Error adding a license to an agreement when leaving non-mandatory fields empty
- [[42825]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42825) ERM Local Title - Start date (started_on) not saved for package resources

## Hold requests

- [[42999]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42999) $valid_items flag contamination in reserve/request.pl causes non-holdable items to appear as available after the first holdable item in the loop
- [[43033]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43033) Holds queue allocate with transport cost matrix can choose impossible holds
- [[42909]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42909) Suspend class missing from suspended holds on request.pl
- [[42395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42395) Missing translations for the existing holds table (load_patron_holds_table) for a record in the staff interface

## ILL

- [[42617]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42617) ILL availability pagination not working
- [[42582]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42582) Uncaught TypeError on Place request with partner libraries when no z39.50 service is set

## Installation and upgrade (command-line installer)

- [[42886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42886) CSS files not installed
- [[42850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42850) ILL requests stylesheet is not installed
- [[42795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42795) Bug 40658 breaks CLI for 25.11

## MARC Authority data support

- [[42920]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42920) Looking up authority records in Advanced editor appends 20 extra spaces

## OPAC

- [[42066]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42066) CSRF-token sometimes missing from pages
- [[41796]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41796) "Forgot your password" link is not visible if OpacResetPassword is enabled but OpacPasswordChange is disabled
- [[42912]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42912) Javascript error on opac-readingrecord when no Circulation history
- [[42654]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42654) Regression: Section missing from OPAC course reserve detail page
- [[42159]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42159) With OPACAuthorIdentifiersAndInformation information lacking from field 110/111
- [[42202]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42202) IndependentBranches shouldn't filter public libaries in OPAC search, news, and most popular

## Patrons

- [[41946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41946) Superlibrarian should be able to set protected status on patron creation
- [[42245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42245) Patron search for guarantors is preselecting borrower sort values from the borrower record
- [[42781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42781) Declare 'name' before using it in patron-format.js

## Plugin architecture

- [[42430]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42430) Fix issue with stale plugin methods after plugin upgrade

## Point of Sale

- [[41819]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41819) Refunds via the Cash registers page should not result in PAYOUTS if the transaction type is 'Account Credit'

## Reports

- [[8127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8127) Most-circulated items report doesn't work when limited by library
- [[42803]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42803) Regression in Reports > Items with no checkouts (reports/catalogue_out.pl)
- [[12757]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12757) Integers in saved SQL report ODT export prepended with single quote

## REST API

- [[42739]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42739) OPAC ratings.js: Add CSRF-TOKEN header to fetch call

## Searching - Elasticsearch

- [[42485]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42485) Elasticsearch dynamic mapping date detection causes indexing failures with ARRAY MARC format

## Serials

- [[42844]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42844) Subscription search breaks when using additional field and no search result is returned

## SIP2

- [[42664]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42664) Changes to SIP2 accounts may not applied immediately
- [[42002]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42002) SIP screen msg regexp can't be empty

## Staff interface

- [[42349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42349) Incorrect filter by recalls
- [[41604]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41604) Impossible to hide Checkin column in issues-table in circ/circulation.pl
- [[42339]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42339) Canceling a Record display customization directs to the HTML customizations
- [[42666]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42666) Next button in Item types and Patron categories does not work
- [[42116]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42116) e.preventDefault is a function, needs parentheses
- [[42535]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42535) Remove useless "news_delete" javascript in staff interface

## System Administration

- [[42568]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42568) Match maxlength attributes to marc_order_accounts column sizes
- [[42618]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42618) Incorrect sidebar menu link to MARC order accounts
- [[42141]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42141) Design pattern introduced in 40191 does not work in staff SIP configuration
- [[42641]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42641) JavaScript errors on patron attribute types admin page

## Templates

- [[42707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42707) Malformed Bootstrap dropdown in reports output
- [[42518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42518) Capitalization: Refund Payout Receipt
- [[42695]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42695) Minor language and markup corrections to reports error messages

## Test Suite

- [[42937]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42937) `$Test::Strict::TEST_STRICT = 0;` no longer needed in t/db_dependent/00-strict.t
- [[42783]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42783) Tools/ManageMarcImport_spec.ts is still flaky
- [[42705]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42705) OPAC/SCO_spec.ts  is failing

## Z39.50 / SRU / OpenSearch Servers

- [[42321]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42321) Z3950/SRU Search should handle empty results from search targets better


