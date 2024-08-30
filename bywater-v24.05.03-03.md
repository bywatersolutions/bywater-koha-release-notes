
# Release Notes for bywater-v24.05.03-03

## About

- [[37003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37003) Release team 24.11
- [[32693]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32693) The 'About Koha' page loads slowly

## Acquisitions

- [[37337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37337) Submitting a similar suggestion results in a blank page
- [[37343]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37343) Cannot search for vendors when transferring an item in acquisitions
- [[37533]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37533) Invalid query when receiving an order
- [[37377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37377) Orders search is not returning any results
- [[30493]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30493) Pending archived suggestions appear on staff interface home page
- [[37089]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37089) Cannot delete a fund or a currency
- [[37090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37090) Cannot delete an EDI account
- [[37316]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37316) Cannot add items to basket via file if barcodes not supplied
- [[37071]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37071) Purchase suggestions from the patron account are not redirecting to the suggestion form
- [[34718]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34718) Input field in fund list (Select2) on receive is inactive
- [[36995]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36995) Can't delete library EAN
- [[34444]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34444) Statistic 1/2 not saving when updating fund after receipt
- [[36856]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36856) New order from existing bibliographic record does not show MARC subfield name
- [[36739]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36739) Unable to delete a budget
- [[36620]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36620) Broken order management for suggestions with quantity
- [[35927]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35927) Selecting MARC framework again doesn't work when adding to basket from an external source
- [[36122]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36122) NEW_SUGGESTION is sent for every modification to the suggestion
- [[18360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18360) Allow deletion of cancelled order lines
- [[36002]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36002) Get rid of aqorders.purchaseordernumber
- [[30598]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30598) Replacement cost is not copied from retail price when ordering from file
- [[10758]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10758) Show bibliographic information of deleted records in acquisition baskets
- [[32132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32132) Missing budget_period_id in aqbudgets kills lateorders.pl
- [[33393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33393) Modify sentence above the order table in English 1-page order PDF
- [[35724]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35724) Define non-standard port numbers for SFTP upload/download in EDI accounts
- [[34963]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34963) Unable to delete fields in suggestions
- [[36635]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36635) Cannot display vendor's issue
- [[36173]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36173) Cancelling order confirmation view does not show basket's info
- [[36442]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36442) Fix typo in EDIFACT list
- [[36187]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36187) Cannot set suggestedby when adding/editing a suggestion from the staff interface
- [[36030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36030) Do not show "Place hold" for deleted biblio record on basket page
- [[33171]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33171) Add coded_location_qualifier, barcode, and enumchron to MarcItemFieldsToOrder
- [[30070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30070) Performance issues with edifactmsgs when you have a large number of messages

## Architecture, internals, and plumbing

- [[36736]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36736) Add ability to load DBIx::Class Schema files found in plugins
- [[37371]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37371) Direct input of dates not working when editing only part of a date
- [[37056]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37056) CSRF error on login when user js contains a fetch of svc/report
- [[37464]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37464) Remote Code Execution in barcode function leads to reverse shell
- [[36863]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36863) CSRF Plack middleware doesn't handle the CONNECT HTTP method
- [[37152]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37152) Delete-confirm should not start with 'cud-'
- [[35294]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35294) Typo in comment in C4 circulation: barocode
- [[36940]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36940) Resolve two Auth warnings when AutoLocation is enabled having a branch without branchip
- [[37037]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37037) touch_all_biblios.pl triggers rebuilding holds for all affected records when RealTimeHoldsQueue is enabled
- [[37040]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37040) ErrorDocument accidentally setting off CSRF
- [[36875]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36875) SQL injection in additional content pages
- [[36818]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36818) Remote-Code-Execution (RCE) in upload-cover-image.pl (CVE-2024-36057)
- [[36520]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36520) SQL Injection in opac-sendbasket.pl (CVE-2024-36058)
- [[26176]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26176) AutoLocation is badly named
- [[36943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36943) Update .mailmap for 24.05.x release
- [[36665]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36665) Auto location and IP recognition
- [[36858]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36858) Crash on wrong page number in opac-shelves
- [[36914]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36914) DBIx::Class warning from shelves.pl
- [[36793]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36793) Local preferences should not stay in the cache when they are deleted
- [[36378]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36378) Cannot stay logged in if AutoLocation is enabled but library's IP address is not set correctly
- [[36018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36018) Improve consistency in Acquisition/Order(s) regarding active/current orders
- [[35994]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35994) New acquisition status method to see if biblio record is still in acquisition
- [[35907]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35907) Add ability to log all custom report runs with or without query
- [[36774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36774) Flatpickr clear() adds unintentional clear button
- [[34360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34360) [WARN] DBIx::Class::ResultSetColumn::new(): Attempting to retrieve non-unique column 'biblionumber' on a resultset containing one-to-many joins will return duplicate results
- [[36151]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36151) Update leaflet.js to current version
- [[36792]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36792) Limit POSIX imports
- [[36790]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36790) 230600052.pl is failing
- [[36788]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36788) Debian control* updates for new dependencies
- [[36246]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36246) Have a centralized method for submitting a form via a link
- [[36526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36526) Remove circular dependency from Koha::Objects
- [[36546]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36546) Bundle API spec to speed up worker startup
- [[36374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36374) Some of our JS files should stay tidy
- [[19097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19097) Koha to MARC mappings (Part 3): Correct remaining GetMarcFromKohaField calls
- [[31335]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31335) Unnecessary holds fetch in serials/routing-preview.pl
- [[35979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35979) Possible RealTimeHoldsQueue check missing in modrequest.pl for BatchUpdateBiblioHoldsQueue background job
- [[36639]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36639) CSRF: Fix deleting authority from authority detail page
- [[36400]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36400) Centralize {js,ts,vue} formatting config in .prettierrc.js
- [[35581]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35581) ILL Koha classes are not consistent
- [[35616]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35616) Add a 'source' field to Koha::Tickets to denote the path taken to report the ticket
- [[36634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36634) tools/automatic_item_modification_by_age.pl use cud-show instead of show
- [[36473]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36473) updatetotalissues.pl should not die on a bad record
- [[36386]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36386) Prevent Net::Server warn about User Not Defined from SIPServer
- [[30068]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30068) Wrong reference to table_borrowers in circulation.tt
- [[36051]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36051) Add option to specify SMS::Send driver parameters in a system preference instead of a file
- [[36438]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36438) MARCdetail: Can't call method "metadata" on an undefined value
- [[36531]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36531) Koha should serve text/javascript compressed, like application/javascript is
- [[36463]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36463) We should compress our JSON responses (gzip deflate mod_deflate application/json)
- [[36379]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36379) Authorities search is broken
- [[36307]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36307) SMS::Send driver errors are not captured and stored
- [[36031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36031) Get rid of (outdated) misc/bin/set-selinux-labels.sh
- [[36395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36395) Useless fetch of AV categories in admin/marc_subfields_structure.pl
- [[36521]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36521) Checkbox preferences should be allowed to be submitted empty
- [[35610]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35610) Missing FK on old_reserves.branchcode
- [[36432]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36432) Remove circular dependency from Koha::Object
- [[36244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36244) Template toolkit syntax not escaped in letter templates
- [[35536]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35536) Improve removal of Koha plugins in unit tests
- [[35133]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35133) Accessors defined in AUTOLOAD does not work if called with SUPER
- [[35793]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35793) Remove Koha::Template::Plugin::Cache
- [[35790]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35790) Remove Koha::Template::Plugin::Biblio::CanArticleRequest
- [[35789]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35789) Remove Koha::Template::Plugin::Biblio::ArticleRequestsActiveCount
- [[35783]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35783) Remove Koha::Template::Plugin::Biblio::RecallsCount
- [[35638]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35638) Upgrade Enquire JS library from v2.0.1 to v2.1.6
- [[35640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35640) Upgrade FileSaver JS library to v2.0.4
- [[35642]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35642) Upgrade Font Face Observer library from v2.0.3 to v2.3.0
- [[35633]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35633) Upgrade Chocolat JS library from v1.1.0 to v1.1.2
- [[35539]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35539) Remove unused columns from categories table
- [[25539]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25539) Remove AddBiblio "defer_marc_save" option
- [[35643]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35643) Upgrade HC Sticky library from v2.2.3 to v2.2.7
- [[33431]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33431) Make code use C4::Context->yaml_preference
- [[36190]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36190) op param for stateful requests must start with 'cud-'
- [[35788]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35788) Remove Koha::Template::Plugin::Biblio::BookingsCount
- [[35787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35787) Remove Koha::Template::Plugin::Biblio::CanBook
- [[35782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35782) Remove Koha::Template::Plugin::Biblio::HoldsCount
- [[36177]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36177) We need integration tests to cover CSRF checks
- [[36193]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36193) CSRF - Code review missed
- [[36195]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36195) CSRF - testing reports
- [[36084]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36084) Pass CSRF token to SVC scripts (1/2)
- [[36148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36148) Move CSRF check code outside of CGI->new
- [[36102]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36102) Protect login forms from CSRF attacks
- [[34478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34478) Full CSRF protection
- [[36019]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36019) Dead code in tags/review
- [[36017]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36017) Dead code in admin/clone-rules
- [[34426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34426) Add tests for CSRF checks missing
- [[32474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32474) Implement infinite scroll in vue-select
- [[35687]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35687) Upgrade to 23.06.00.013 may fail

## Authentication

- [[36908]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36908) Clarify and standardize the behavior of AutoLocation/ StaffLoginBranchBasedOnIP system preferences
- [[36503]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36503) Add a plugin hook to modify patrons after authentication
- [[36219]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36219) State parameter broken for OIDC/Oauth

## Bywater Only

- NOT IN BUGZILLA - GitHub Action - Update actions for changes in koha-testing-docker
- NOT IN BUGZILLA - Remove InfiniteScrollSelect_spec.ts, it is failing for no apparent reason
- NOT IN BUGZILLA - TEMP - Remove failing SC test, setup is bad
- NOT IN BUGZILLA - GitHub Actions - Remove  t/db_dependent/selenium/authentication.t
- NOT IN BUGZILLA - Fix missing CSRF token
- NOT IN BUGZILLA - GitHub Actions - Update image from 23.11 to 24.05
- NOT IN BUGZILLA - Revert "BWS-PKG - GitHub Actions - Install Struct::Diff manually for unit tests"
- NOT IN BUGZILLA - GitHub Actions - Install Struct::Diff manually for unit tests
- NOT IN BUGZILLA - 24.05.00: Update kohastructure.sql
- NOT IN BUGZILLA - 24.05.00: Update history.txt
- NOT IN BUGZILLA - 24.05.00: Update contributors.yaml
- NOT IN BUGZILLA - DBRev 23.12.00.000: Start of a new release cycle

## Cataloging

- [[37383]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37383) No edit item button on catalog detail page for items where holding library is not logged in library
- [[36498]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36498) Allow ability to set display order when adding an item group from item editor
- [[36891]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36891) Restore returning 404 from svc/bib when the bib number doesn't exist
- [[25387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25387) Merging different authority types creates no warning
- [[36984]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36984) Transit pending status breaks holdings info
- [[37127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37127) Authorized values select not working on authority forms
- [[37080]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37080) Cannot delete a MARC bibliographic framework or authority type
- [[36589]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36589) Advanced cataloging - restore the correct height of the clipboard
- [[24424]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24424) Advanced editor - interface hangs as "Loading" when given an invalid bib number
- [[36370]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36370) Add ContentWarningField to UNIMARC XSLT
- [[36794]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36794) Illegitimate modification of biblionumber subfield content (999 $c)
- [[36757]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36757) Add assignee to catalog concern/ticket detail view when opened from catalog detail page
- [[27363]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27363) Restore temporary selection of Z39.50 targets throughout multiple searches
- [[36786]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36786) (Bug 31791 follow-up) Koha explodes when trying to edit a bibliographic record with an invalid biblionumber
- [[36756]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36756) Fix default action on split update button when editing tickets/catalog concerns
- [[35657]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35657) Add ability to assign tickets to librarians for catalog concerns
- [[32435]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32435) Add resolution types to catalog concerns
- [[35628]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35628) Add optional statuses to catalog concerns
- [[33494]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33494) Catalog concerns - Toggle 'Hide resolved' and 'Show all'
- [[31791]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31791) Add the ability to lock records to prevent modification through the Koha staff interface
- [[27893]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27893) Deleting a bibliographic record should warn about attached acquisition orders and cancel them
- [[36630]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36630) Item search batch operations buttons broken by CSRF
- [[36552]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36552) Update record 'date entered on file' when duplicating a record
- [[36461]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36461) Advanced editor should disable RequireJS timeout with waitSeconds: 0
- [[30554]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30554) Use XSLT in authority search cataloguing plugin
- [[35034]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35034) Add link to the bibliographic records when they are selected for merging
- [[35768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35768) Show 'Used in' records link for results in cataloguing authority plugin
- [[36326]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36326) Batch deletion of selected items from detail page is broken
- [[35062]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35062) Allow a framework plugin to add class to prevent submit during ajax call
- [[36336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36336) Exporting records from detail page is broken
- [[36327]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36327) Items view -  Deletion of items is broken
- [[36351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36351) CSRF Adjustments for Cataloguing editor

## Circulation

- [[37540]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37540) Pseudonymization is preventing renewals from the patrons account page
- [[37210]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37210) SQL injection in overdue.pl
- [[37385]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37385) Transfer/next hold modals not triggered automatically when cancelling a hold by checking item in
- [[37332]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37332) Renewal due date and renew as unseen fields not respected when renewing an item from the patron account
- [[37345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37345) Remember for session checkbox on checkout page not sticking
- [[37047]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37047) Patron bookings are not visible from patrons checkout page
- [[36428]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36428) Current bookings are not counted in record side bar
- [[37031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37031) Club enrollment doesn't complete in staff interface
- [[37014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37014) "Item was not checked in" printed on next POST because of missing supplementary form
- [[36459]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36459) Backdating checkouts on circ/circulation.pl not working properly
- [[36946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36946) Can't process pending offline circulations
- [[36060]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36060) If issues table includes overdues 'Renew selected items' button is disabled
- [[36096]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36096) Add ability to select default sort and display length for tables on 'Holds awaiting pickup' page
- [[36619]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36619) Cannot show/hide columns on the patron search table when placing a hold
- [[36859]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36859) Batch checkout not working due to mismatch in CSRF parameter names
- [[36708]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36708) Problems editing circ rules when 'Holds allowed (total)' value is greater than or equal to 0
- [[36373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36373) Show existing bookings in datepicker
- [[35813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35813) When placing a booking, we should feedback successful placements
- [[35149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35149) Add "do nothing" option to CircAutoPrintQuickSlip system preference
- [[33737]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33737) Add bookings to patron details
- [[34263]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34263) Suspending holds consecutively populates previously used date falsely
- [[36074]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36074) Make materials specified note easier to customize, part 2
- [[27753]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27753) Automate resolution of return claim when checking in an item
- [[36393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36393) Renewal with a specific date does not take the new date due that we pick
- [[36120]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36120) Add pickup locations to bookings
- [[36614]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36614) Reinstate phone column in patron search
- [[31671]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31671) Add button to print transfer slips to the 'Transfer items' page
- [[30324]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30324) Parent and child itemtype checkout limits not enforced as expected
- [[16122]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16122) Item record needs to keep local use count
- [[36313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36313) Check out/check in leads to error 500 in staff interface
- [[33174]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33174) Have better indication when one is cancelling multiple holds on a record
- [[8461]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8461) Block returns of withdrawn items show as 'not checked out'
- [[36494]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36494) Flatpickr error on checkout page if the patron is blocked from checking out
- [[6796]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=6796) Overnight checkouts taking into account opening and closing hours
- [[36581]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36581) Checkouts table on patron account won't load if any of the items have item notes
- [[36418]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36418) Set response's content-type to application/json when needed - svc scripts
- [[36347]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36347) Return claims table is loaded twice
- [[36426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36426) Cannot set article request as pending
- [[18885]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18885) When 'on-site checkout' was used, the 'Specify due date' should be emptied for next checkout unless OnSiteCheckoutAutoCheck
- [[34668]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34668) Notify staff with a pop-up about waiting holds for a patron when checking out
- [[27595]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27595) Place holds for patrons on accepted purchase suggestions
- [[29002]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29002) Add ability to book items ahead of time
- [[30230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30230) Search for patrons in checkout should not require edit_borrowers permission

## Command-line Utilities

- [[29507]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29507) Speed up auto renew cronjob via parallel processing
- [[37075]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37075) Message queue processor will fail to send any message unless letter_code is passed
- [[34077]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34077) writeoff_debts without --confirm doesn't show which accountline records it would have been written off
- [[35836]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35836) search_for_data_inconsistencies.pl - Search for loops in dependencies
- [[36325]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36325) Add option to koha-run-backups/koha-dump, to exclude logs
- [[36787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36787) staticfines.pl missing use Koha::DateUtils::output_pref
- [[35169]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35169) Make long overdue patron category options configurable in interface
- [[36709]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36709) Add --confirm flag to update_localuse_from_statistics.pl script
- [[35954]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35954) Add --status to koha-plack
- [[36508]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36508) Patron userid field can be overwritten by update_patron_categories when limiting by fines
- [[35996]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35996) Add clarification to POD in writeoff_debts.pl
- [[36309]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36309) create_superlibrarian.pl output could be more helpful
- [[36068]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36068) Add maintenance script acq_cancel_obsolete_orders.pl
- [[36517]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36517) Fix output from install_plugins.pl
- [[31286]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31286) Embed see-from headings into bibliographic records export
- [[35653]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35653) Allow the patron import script to log it's output to the action_logs cron logging
- [[34611]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34611) Add a script for pseudonymizing existing data
- [[29440]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29440) Refactor/clean up bulkmarcimport.pl
- [[26831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26831) Enable librarians to control when unaccepted private list share invites are removed by the cleanup_database.pl cronjob

## Database

- [[36755]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36755) Increase length of 'code' column in borrower_attribute_types
- [[36687]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36687) itemtypes.notforloan should be tinyint and NOT NULL
- [[36033]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36033) Table pseudonymized_transactions needs more indexes

## Developer documentation

- [[37198]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37198) POD for GetPreparedLetter doesn't include 'objects'

## ERM

- [[36895]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36895) Background job links for KBART import are not working
- [[36956]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36956) ERM eUsage reports: only the first 20 data providers are listed when creating a new report
- [[37043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37043) Counter registry has a new API base URL
- [[36618]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36618) Make creation of bibliographic records optional for ERM local titles
- [[36623]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36623) Remove localhost reference from counter logs page
- [[34788]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34788) Add the ability to import KBART files to ERM
- [[36827]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36827) Tabs in the ERM module have a gap above the tab content
- [[36828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36828) Remove unnecessary code from UsageStatisticsReportsHome.vue
- [[36093]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36093) Fix missing array reference in provider rollup reports
- [[35392]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35392) HTML in translatable string
- [[36392]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36392) Only 20 vendors in ERM dropdown

## Fines and fees

- [[37255]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37255) Creating default waiting hold cancellation policy for all patron categories and itemtypes breaks Koha
- [[28664]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28664) One should not be able to issue a refund against a VOID accountline
- [[22740]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22740) Automatically change lost status when item is paid for

## Hold requests

- [[37374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37374) Place hold button non-responsive for club holds
- [[31981]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31981) Add classes to each NEEDSCONFIRM message for easier styling in circ/circulation.tt
- [[36899]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36899) Further improvements to holds request page, part 2
- [[36864]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36864) Further improvements to holds request page
- [[34823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34823) Do not show item group drop-down if there are no item groups
- [[36797]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36797) Record with 1000+ holds and unique priorities causes a 500 error
- [[36735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36735) Cannot revert the waiting status of a hold
- [[36775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36775) Option to place multiple holds on single bib should not be hidden when holds per record is unlimited
- [[30579]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30579) When placing item level hold, some options that are not used are not disabled
- [[34972]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34972) Canceling a waiting hold from the holds over tab can make the next hold unfillable
- [[36137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36137) update_totalissues.pl should always skip_holds_queue
- [[35559]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35559) Can't change the pickup date of holds on the last day of expiration
- [[15565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15565) Place multiple item-level holds at once for the same record
- [[35977]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35977) Display current date in hold starts on when placing a hold in the OPAC
- [[32565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32565) Holds placed when all libraries are closed do not get added to holds queue if HoldsQueueSkipClosed and RealTimeHoldsQueue are enabled
- [[36559]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36559) Transport cost matrix update helpers
- [[35727]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35727) Unused code in HoldsQueue::MapItemsToHoldRequests
- [[34032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34032) Holds expirationdate left blank if waiting status is reverted
- [[35826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35826) Optimize building of holds queue based on transport cost matrix
- [[35394]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35394) Correct the message displayed when attempting to checkout an item during it's booking period
- [[35432]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35432) Clarify and simplify the workings of MapItemsToHoldRequests
- [[36439]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36439) Column settings are missing on holds-to-pull table
- [[35573]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35573) Koha is not correctly warning of overridden items when placing a hold if AllowHoldPolicyOverride
- [[36227]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36227) No warning if placing hold on item group with no items
- [[23208]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23208) Ability to set default ratio in holds ratio report
- [[35576]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35576) Make the callnumber column easier to customize when viewing the holds queue report
- [[35564]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35564) Add home library (homebranch) column to holds queue report

## I18N/L10N

- [[32313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32313) Complete database column descriptions for cataloguing module in guided reports
- [[36845]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36845) Exclude meta tag from the translations
- [[36872]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36872) Untranslatable "Please make sure all selected titles have a pickup location set"
- [[36876]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36876) In table settings words are split in two and some of them cannot be translated properly
- [[33237]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33237) If TranslateNotices is off, use the default language includes in slips
- [[36837]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36837) XSLT CSS classes offered for translations
- [[36516]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36516) translation script could output useless warning
- [[35531]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35531) Add context for translation of gender option "Other"

## ILL

- [[36894]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36894) Journal article request authors do not show in the ILL requests table
- [[36904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36904) ILL error when searching from table search input
- [[36414]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36414) Consequent workflow stages form submit fail due to CSRF token conflict
- [[35106]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35106) ILL - Add patron autocomplete to 'Edit request' Patron ID input
- [[36416]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36416) Check out using CirculateILL is broken
- [[35151]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35151) Convert ILLModuleCopyrightClearance system preference to additional contents
- [[19605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19605) ILL backends should be pluggable through regular Koha plugins
- [[36105]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36105) Add option to filter for "No status alias"
- [[35108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35108) ILL - "Manage request" page is too loaded
- [[35685]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35685) ILL - OPAC request creation error if submitted empty while ILLModuleDisclaimerByType is in use
- [[35107]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35107) ILL - Type disclaimer value and date should be visible under "Request details" in the manage request page
- [[34431]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34431) Distinguish between status and status alias in ILL UI
- [[36245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36245) ILL - Custom backend form action is broken
- [[36249]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36249) ILL - "Request from partners" action is broken
- [[36243]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36243) ILL "Edit request" action is broken
- [[36241]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36241) ILL Batches are broken

## Installation and upgrade (command-line installer)

- [[36424]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36424) Database update 23.06.00.061 breaks due to syntax error
- [[37000]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37000) Upgrade fails at 23.12.00.044 [Bug 36120]
- [[36993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36993) Upgrade fails at 23.12.00.023 [Bug 32132]
- [[36986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36986) (Bug 26176 follow-up) Fix rename StaffLoginBranchBasedOnIP in DBRev
- [[34979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34979) System preferences missing from sysprefs.sql

## Installation and upgrade (web-based installer)

- [[35681]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35681) Add support for colored messages in the output of updatedatabase

## Label/patron card printing

- [[37192]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37192) Can't print label from the item editor
- [[37187]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37187) Label batches and label templates cannot be deleted
- [[36931]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36931) label-item-search.pl paging doesn't work (due to CSRF changes)
- [[36819]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36819) Default layout data prints squished barcodes

## Lists

- [[36003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36003) Printing list from OPAC shows "Cookies" when CookieConsent enabled

## MARC Authority data support

- [[30047]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30047) Add a field to auth_header to record main heading as text string
- [[36799]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36799) Illegitimate modification of MARC authid field content (001)
- [[36832]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36832) Adding authority records is broken
- [[36388]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36388) Mouse operation does not work in draggable fields in authority editor (with Firefox)
- [[36791]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36791) Koha explodes when trying to edit an authority record with an invalid authid
- [[35903]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35903) In cataloguing authority plugin using autocomplete should set operator exact after selecting an entry
- [[13706]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13706) Deduping authorities script (dedup_authorities.pl)
- [[29825]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29825) Preview of authority record on edit mode as MARC formatted view
- [[35328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35328) Add a notes pop-up for authority records to authority search results

## MARC Bibliographic data support

- [[36108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36108) Update MARC21 default framework to Update 37 (December 2023)
- [[35993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35993) AddBiblio should add 005 just like ModBiblio updates it
- [[36111]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36111) Online resource link should be based on the presence of 856$u (MARC21)
- [[34663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34663) Errors in UNIMARC default framework

## MARC Bibliographic record staging/import

- [[33418]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33418) Allow setting overlay_framework for connexion imports
- [[36247]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36247) MARC21 Addition to relator terms in technical notice 2024-02-27
- [[30349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30349) Cleanup bulkmarcimport.pl

## Notices

- [[36741]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36741) AUTO_RENEWALS_DGST should skip auto_too_soon
- [[37036]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37036) Cannot access template toolkit branch variable in auto renewal notices
- [[37059]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37059) 'Insert' button is not working in notices and slips tool
- [[35285]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35285) Centralise notice content wrapping for HTML output
- [[35925]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35925) Port default NEW_SUGGESTION, REJECTED, ACCEPTED, and ORDERED notices to Template Toolkit
- [[36106]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36106) Port default PREDUE and DUE notices to Template Toolkit
- [[36126]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36126) Port default HOLD notice to Template Toolkit syntax
- [[36113]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36113) Port default RENEWAL notice to Template Toolkit syntax
- [[36125]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36125) Port default HOLD_SLIP notice to Template Toolkit syntax
- [[36608]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36608) Port default TO_PROCESS and AVAILABLE notices to Template Toolkit syntax
- [[31627]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31627) Add ability to embed the letter ID in outgoing email notices
- [[29393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29393) Ability to send emails from patron details page
- [[12802]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12802) Send notices using several email addresses
- [[33478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33478) Customise the format of notices when they are printed
- [[36652]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36652) Cannot copy notice from one library to another
- [[23296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23296) Auto Renewal Notice does not use Library specific notices
- [[35279]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35279) Add fallback for WELCOME notice to allow 'print' when patrons are missing email address

## OPAC

- [[37111]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37111) OPAC renewal - CSRF "op must be set"
- [[37150]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37150) Can't delete single title from a list using the "Remove from list" link
- [[37370]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37370) opac-export.pl can be used even if exporting disabled
- [[37074]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37074) Comment approval and un-approval should be CSRF-protected
- [[36141]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36141) Add classes to CAS text on OPAC login page
- [[30372]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30372) Patron self registration: Extended patron attributes are emptied on submit when mandatory field isn't filled in
- [[37069]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37069) Authorities pagination on OPAC broken by CSRF
- [[36166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36166) Disable select to add to list if opacuserlogin is disabled
- [[36207]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36207) Update browser alerts to modals: OPAC tags
- [[36983]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36983) B_address_2 field is required even when not set to be required
- [[29539]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29539) UNIMARC: authority number in $9 displays for thesaurus controlled fields instead of content of $a
- [[37039]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37039) Cannot request a discharge in the OPAC
- [[35929]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35929) Don't submit 'empty' changes to personal details in OPAC
- [[36883]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36883) Can't finish club enrollment in the OPAC
- [[36785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36785) Tagging: Resolve warning about unrecognized biblionumber
- [[36772]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36772) OPAC self checkout accepts wrong or partial barcodes
- [[29948]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29948) Display author information for researchers
- [[35812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35812) Should specify canonical URLs to help search indexers
- [[19768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19768) Possibility to choose "Note" tab in OpacSerialDefaultTab
- [[36390]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36390) Two minor OPAC CSS fixes
- [[36341]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36341) "Hold starts on date" should be limited to future dates
- [[34792]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34792) CookieConsentBar content feels mis-aligned
- [[36615]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36615) Terminology: use 'on hold' instead of 'reserved' in OPAC self checkout
- [[35586]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35586) Add the collection to the location column in the OPAC cart
- [[35689]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35689) Add id and classes to each MARC note in OPAC bibliographic details
- [[35348]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35348) Cookie information should be available regardless of whether you are logged in or not
- [[16567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16567) RSS feeds show issues in W3C validator and can't be read by some aggregators (Chimpfeedr, feedbucket)
- [[36138]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36138) Add cancellation reason to the status column on the OPAC hold history page
- [[35969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35969) Improve error message, remove some logging when sending a cart from the OPAC
- [[36142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36142) Usermenu "Recalls history" not active when confirming recall
- [[35346]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35346) 'Accept essential cookies' should always appear if CookieConsent is enabled
- [[35347]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35347) 'More information' should always display in cookie consent bar
- [[34793]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34793) We should ship default 'CookieConsentPopup' data that describes our required cookies
- [[36274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36274) OPAC suggestions form doesn't display

## Packaging

- [[35614]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35614) Update cpanfile for Mojolicious::Plugin::OpenAPI v5.09

## Patrons

- [[37435]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37435) Cannot renew patron from details page in patron account without circulate permissions
- [[34147]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34147) Patron search displays "processing" when category has library limitations that exclude the logged in library name
- [[37378]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37378) Patron searches can fail when library groups are set to 'Limit patron data access by group'
- [[37366]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37366) Patron category "Password change in OPAC" setting only follows system preference
- [[37368]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37368) Patron searches break when surname and firstname are set to NULL
- [[37488]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37488) Filepaths not validated in ZIP upload to picture-upload.pl
- [[37323]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37323) Remote-Code-Execution (RCE) in picture-upload.pl
- [[25520]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25520) Change wording on SMS phone number set up
- [[36816]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36816) OPAC - Patron 'submit update request' does not work for clearing patron attribute types
- [[36529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36529) manage_additional_fields permission for more than acquisitions and serials
- [[36825]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36825) Cannot hide "Protected" field via BorrowerUnwantedField system preference
- [[33849]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33849) Duplicate patron warning resets patron's library if different than logged in user's library
- [[31097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31097) Patron restriction types should display in staff interface and OPAC
- [[25996]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25996) Changes to restrictions should be logged
- [[36738]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36738) Date attributes follow-ups
- [[32610]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32610) Add ability to specify patron attribute as a date
- [[33703]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33703) Entering dates should be more flexible accepting different entry formats
- [[30318]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30318) Cannot override default patron messaging preferences when creating a patron in staff interface
- [[30645]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30645) Generated DBIC query incorrect for API searches across joined extended attributes when several terms are passed
- [[36204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36204) Add othernames to the PatronAutoComplete  display
- [[34575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34575) Patron search results: Add a CSS class to patron email to ease customization
- [[34574]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34574) Datatables column dropdown select filter does not have a CSS class
- [[30987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30987) Adding relationship to PatronQuickAddFields causes it to be added 2x
- [[33832]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33832) Can't change a patron's username without entering passwords
- [[36353]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36353) Ensure consistent empty selection style for guarantor relationship drop-downs
- [[36452]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36452) Patron message does not respect multiple line display
- [[35599]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35599) Pronouns and HidePersonalPatronDetailOnCirculation
- [[36376]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36376) Display library limitations alert in patron's messages
- [[36368]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36368) Cannot save new patron after error
- [[36371]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36371) Patron attributes will not show in brief info if value is 0
- [[35316]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35316) Add call number to holds history page
- [[36321]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36321) Problem when dateexpiry in BorrowerUnwantedField
- [[26597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26597) Transfer information from guarantor when adding a guarantor to an existing patron
- [[36251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36251) Patron search by letter broken in holds

## Plugin architecture

- [[37146]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37146) plugin_launcher.pl allows running of any Perl file on file system
- [[36206]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36206) Administrative plugins
- [[35568]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35568) Add a plugin hook to allow modification of notices created via GetPreparedLetter
- [[36343]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36343) The 'after_biblio_action' hooks have an inconsistent signature compared to before_biblio_action, and actions in reserves and items
- [[30897]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30897) Gracefully reload Koha after plugin install/upgrade
- [[34943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34943) Add a pre-save plugin hook for biblios
- [[35331]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35331) Add an ILL table actions plugin hook

## Preservation

- [[36649]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36649) Adding recently added items to processing from waiting list does not work if processing includes information from database columns
- [[35714]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35714) Clicking Print slips when no letter template selected causes error

## Reports

- [[37508]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37508) SQL reports should not show patron password hash if queried
- [[36380]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36380) Filter matches not included in borrowers statistics reports
- [[36823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36823) Reports links to database schema 404 looking for master rather than main
- [[36534]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36534) Batch operations when using limit in report
- [[36796]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36796) Fix mistake in database column descriptions for statistics table
- [[36555]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36555) Add report_id to file name when exporting report results
- [[5920]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=5920) Remove HTML from downloaded reports in CSV format
- [[35856]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35856) Runtime parameter modal should provide option of ":all"
- [[35746]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35746) Multiple selections for parameters used in the IN function
- [[36568]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36568) Changing rows per page on a custom report is broken
- [[35943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35943) SQL reports groups/subgroups whose name contains regexp special characters break table filtering

## REST API

- [[36481]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36481) Add GET /libraries/:library_id/cash_registers
- [[36480]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36480) Add GET /libraries/:library_id/desks
- [[37018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37018) SQL injection using q under api/
- [[37021]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37021) REST API: Holds endpoint handles item_id as string in GET call
- [[36575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36575) Wrong patron can be returned for API validation route
- [[36612]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36612) The public tickets endpoint needs public fields list
- [[26297]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26297) Add a route to list patron categories
- [[36565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36565) Fix API docs inconsistencies
- [[36495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36495) Add render_resource_not_found() and render_resource_deleted() helpers
- [[22613]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22613) Add /patrons/patron_id/checkouts endpoints
- [[36505]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36505) Allow updating patron attributes via PUT
- [[36482]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36482) Make it possible to embed desks and cash_registers on /libraries
- [[35353]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35353) Add API endpoint to fetch patron's previous holds
- [[33960]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33960) Add ability to retrieve deleted bibliographic records
- [[35967]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35967) Add /api/v1/patrons/{patron_id}/recalls endpoint to list a patron's recalls
- [[36420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36420) REST API Basic Auth does not support cardnumbers, only userid
- [[36483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36483) Calling $object->to_api directly should be avoided
- [[36493]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36493) Test for GET /api/v1/cash_registers/:cash_register_id/cashups is fragile
- [[35129]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35129) REST API: _per_page=0 crashes on Illegal division by zero
- [[36421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36421) Better logging of 500 errors in V1/Auth.pm
- [[35386]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35386) Add ability to configure renewal library when not specified in API request

## Searching

- [[33563]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33563) Document Elasticsearch secure mode
- [[35989]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35989) Searching Geographic authorities generates error
- [[26654]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26654) Add item number column to item search results and CSV export
- [[33134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33134) Add some missing languages
- [[36545]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36545) Use select2 to improve multi-select in item search
- [[36499]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36499) Add last checkout date column to the item search results
- [[35728]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35728) Add option to NOT redirect to result when search returns only one record
- [[36659]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36659) Authorities search tab keeps defaulting to main heading ($a only)
- [[32695]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32695) Search string for various 7xx linking fields is incorrectly formed
- [[36563]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36563) Item search does not search for multiple values

## Searching - Elasticsearch

- [[36982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36982) Collections facet does not get alphabetized based on collection descriptions
- [[33099]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33099) Add missing MARC21 match authority mappings so "Search all headings" search works
- [[36723]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36723) Add musical presentation to Elasticsearch index mappings
- [[35138]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35138) Enable configuration of facets with Elasticsearch
- [[36750]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36750) OPAC - some facet heading labels are not displayed in search results when using Elasticsearch
- [[36396]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36396) Link facet with authorised value category
- [[36554]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36554) Document languages from field 041 should be present in 'ln' search field and Languages facet (MARC 21)
- [[36584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36584) Add fields 520, 561, and 563 (MARC 21) to ES note search field
- [[36578]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36578) Elasticsearch: publisher-location (pl) index should include field 752 (for old prints) and also support UNIMARC
- [[34693]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34693) Add 035$a as Other-control-number index in authorities search indexes (MARC21, Elasticsearch)
- [[36574]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36574) Canceled/invalid ISBN not indexed for MARC21
- [[36678]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36678) Include fields with non-filing characters removed when indexing
- [[31652]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31652) Add geo-search
- [[35345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35345) Pass custom SQL to rebuild_elasticsearch.pl to determine which records to index
- [[20388]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20388) Ability to add search fields from UI
- [[33205]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33205) (Bug 28268 follow-up) Method call $row->authid inside quotes - produces meaningless warning
- [[32707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32707) Elasticsearch should not auto truncate (even if  QueryAutoTruncate = 1) for identifiers (and some other fields)
- [[36269]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36269) Elasticsearch: publisher-location (pl) index should include 260a/264a (MARC21)
- [[36394]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36394) Inconsistent behaviour in footers (mappings admin page)

## Searching - Zebra

- [[27198]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27198) Sync marc21-retrieval-info-auth-dom.xml with retrieval-info-auth-dom.xml
- [[35621]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35621) Map ÿ to y for searching (Non-ICU)

## Self checkout

- [[37044]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37044) OPAC message from SCO missing library branch
- [[35869]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35869) Dismissing an OPAC message from SCO logs the user out
- [[37026]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37026) Switching tabs in the sco_main page ( Checkouts, Holds, Charges ) creates a JS error
- [[36679]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36679) Anonymous patron is not blocked from checkout via self check
- [[32256]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32256) Self checkout batch mode
- [[23102]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23102) 404 errors on page causes SCI user to be logged out
- [[36349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36349) Login for SCO/SCI broken  by CSRF

## Serials

- [[37294]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37294) Generate next button in serials not working
- [[37247]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37247) On subscriptions operation allowed without authentication
- [[37183]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37183) Serials batch edit changes the expiration date to TODAY
- [[37165]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37165) Can't edit frequencies due to stray cud- in modify op
- [[26567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26567) Allow to limit subscription search to subscriptions with routing lists
- [[36804]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36804) Serials claims 'Clear filter' doesn't work
- [[32392]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32392) Ability to skip forward serial issues when receiving double (or more) issue
- [[35646]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35646) Allow using the publication date parts for serial numbering
- [[31297]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31297) Cannot add new subscription patterns from edit subscription page

## SIP2

- [[37016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37016) SIP2 renew shows old/wrong date due
- [[36948]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36948) Adjust SIPconfig for log_file and IP version
- [[36676]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36676) SIP2 drops connection when using unknown patron id in fee paid message
- [[25813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25813) Enhance patron expiration in SIP display
- [[36308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36308) SIP2 login broken by CSRF changes

## Staff interface

- [[37425]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37425) Deletion of bibliographic record can cause search errors
- [[37466]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37466) Reflected Cross Site Scripting
- [[36966]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36966) Fix links for local cover images for items on staff detail page
- [[30623]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30623) Copy permissions from one user to another
- [[36930]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36930) Item search gives irrelevant results when using 2+ added filter criteria
- [[37005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37005) Holdings table will not load when noItemTypeImages is set to 'Don't show'
- [[37078]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37078) Damaged status not showing in record detail page
- [[36834]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36834) (Bug 29697 follow-up) Koha explodes when trying to open in Labeled MARC view a bibliographic record with an invalid biblionumber
- [[28869]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28869) Optionally restrict authorised values to tinyint
- [[35961]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35961) Modal include missing for catalog concerns
- [[35862]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35862) Display patron search result on the right of the form (modal)
- [[36440]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36440) Add edit buttons for patron flags in attention box
- [[36830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36830) Unable to delete a holiday
- [[36582]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36582) Add option to set library, desk, and register from user menu
- [[36760]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36760) Make 'Current assignee' stand out more in ticket details view
- [[36673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36673) Limit search for used categories and item types to current library
- [[36700]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36700) CSRF: Cannot save a systempreference (when nginx drops the CSRF header with an underscore)
- [[35582]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35582) Advanced search languages should be listed with selected UI language descriptions shown first if available
- [[36663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36663) Table configuration options on items table don't show in staff interface
- [[30123]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30123) On set library page, desk always defaults to last in list instead of desk user is signed in at
- [[22567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22567) Stock rotation manage rotas should show items current and desired locations
- [[36265]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36265) Bigger font-size for headers in staff interface
- [[36577]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36577) (bug 34478 follow-up) marc21_linking_section.pl not working
- [[35810]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35810) Add back to top button to the staff interface
- [[36572]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36572) Cleanup the set library page and avoid extra confirmation step
- [[33568]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33568) Use the REST API to display items on the staff biblio detail view
- [[36462]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36462) Home button breadcrumb appears twice when viewing/editing the authority MARC subfield structure
- [[36469]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36469) Conflict between _header.scss and addbiblio.css tab style
- [[35868]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35868) Warning sign for using a patron category that is limited to another library has moved to other side of page
- [[36507]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36507) Cannot set desk or register as non superlibrarian
- [[36302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36302) Patron search from search bar broken
- [[35444]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35444) Add easy way to retrieve a logged in user's categorycode
- [[35540]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35540) Separate StaffListsHome block from the table block
- [[36234]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36234) Language prefs cannot be modified
- [[35329]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35329) Move patron searches to a modal
- [[35752]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35752) Can't delete additional contents with 'Delete selected' button
- [[35707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35707) Item statuses in the holdings table on biblio details should appear one per line

## System Administration

- [[36880]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36880) Record overlay rules are not validated on add or edit
- [[37157]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37157) Error 500 when loading identity provider list
- [[36527]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36527) Patron category or item type not changing when editing another circulation rule
- [[37163]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37163) Fix the redirect after deleting a tag from an authority framework to load the right page
- [[37091]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37091) Cannot delete a local system preference
- [[36922]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36922) Correct hint on date patron attributes not being repeatable
- [[36672]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36672) Circulation rules are performing too many lookups
- [[36824]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36824) Fix conversion of __VERSION__ in system preferences to use main rather than master
- [[36510]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36510) Add CircControl information to circulation and fine rules page
- [[35919]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35919) Add record sources CRUD
- [[36592]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36592) Cannot save default display length or default sort order in table settings
- [[35973]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35973) System preference RedirectGuaranteeEmail has incorrect values
- [[36597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36597) Cannot delete circulation desk
- [[36409]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36409) System preference name consistency - change EMail to Email for SerialsDefaultEMailAddress and AcquisitionsDefaultEMailAddress
- [[35708]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35708) System parameter AutoRenewalNotices defaults to deprecated option
- [[36294]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36294) Replace inaccurate use of "book" in system preferences
- [[35457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35457) Move SerialsDefaultEMailAddress and SerialsDefaultReplyTo to serials preferences
- [[35097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35097) Use country-list.inc to display choices for UsageStatsCountry preference
- [[36235]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36235) System preferences chopping everything after a semicolon.

## Templates

- [[37002]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37002) Correct several HTML markup errors
- [[36909]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36909) Eliminate duplicate ID in cookie consent markup
- [[36911]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36911) Reindent circ-menu.inc
- [[35240]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35240) Missing form field ids in rotating collection edit form
- [[37162]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37162) Remove dead confirmation code when deleting tags from authority frameworks
- [[37161]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37161) After deleting a tag in a MARC framework, confirmation page is blank
- [[34706]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34706) Capitalization: Cas login
- [[36338]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36338) Capitalization: Card number or Userid may already exist.
- [[36961]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36961) Typo: itms
- [[34573]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34573) Inconsistencies in acquisitions modify vendor title tag
- [[36892]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36892) Wrong label on filter-orders include
- [[36528]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36528) Incorrect path to enquire.js on self checkout slip print page
- [[36610]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36610) Some improvements to OPAC print CSS
- [[36844]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36844) Set library, desk, and cash register menu follow-ups
- [[35362]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35362) Update patron module pop-up windows with consistent footer markup
- [[36472]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36472) Add search box at the top of the authorities editor page
- [[36701]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36701) Adjust hold confirmation to avoid showing empty div
- [[35895]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35895) Reindent tags review template
- [[25682]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25682) Style transfers interface to match checkin page
- [[36671]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36671) Reindent item transfer template (branchtransfers.tt)
- [[35511]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35511) Add visual indicators of patron edit form collapsible sections
- [[34082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34082) Cut some redundancy in OPAC JavaScript string translations
- [[35249]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35249) Use DataTables RowReorder extension instead of tableDND jQuery plugin
- [[35558]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35558) Do not fetch local image if none exists
- [[36295]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36295) Space out content blocks in batch record deletion
- [[36282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36282) OPAC - Remove trailing and leading blank space from translated strings
- [[35364]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35364) Update serials pop-up windows with consistent footer markup
- [[35363]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35363) Update transfer order pop-up window with consistent footer markup
- [[36490]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36490) Correct tab-switching keyboard shortcut for header search forms
- [[36384]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36384) 'Used saved' typo in guided reports
- [[35882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35882) Use template wrapper for accordions: Notices
- [[35883]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35883) Use template wrapper for accordions: Table settings administration
- [[35880]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35880) Use template wrapper for accordions: Patrons requesting modifications
- [[35877]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35877) Use template wrapper to build Bootstrap accordion components
- [[35850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35850) Use template wrapper for tabs: Header search forms
- [[35857]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35857) Update display of Clear and Cancel links in the authority search pop-up window
- [[36358]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36358) Typo in errorpage.tt: requets
- [[36334]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36334) Unnecessary JS code in member.tt
- [[35413]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35413) Terminology: differentiate issues for vendor issues and serials

## Test Suite

- [[36937]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36937) api/v1/password_validation.t generates warnings
- [[36999]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36999) 00-strict.t fails to find koha_perl_deps.pl
- [[36938]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36938) Biblio.t generates warnings
- [[34838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34838) The ILL module and tests generate warnings
- [[36939]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36939) Serials.t generates a warning
- [[36923]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36923) Holds/LocalHoldsPriority.t generates warnings
- [[36916]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36916) TestBuilder generates incorrect JS and CSS for libraries
- [[36917]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36917) Many warnings from t/db_dependent/Authority/Merge.t
- [[36924]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36924) t/db_dependent/Search.t generates warnings
- [[36486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36486) Add tests for Koha::DateTime::Format::SQL
- [[34655]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34655) system_preferences_search.t is failing randomly
- [[36567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36567) Datetime warning in t/db_dependent/Circulation.t and t/db_dependent/Circulation/dateexpiry.t
- [[36160]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36160) Use $builder->build_object when creating patrons in Circulation.t
- [[36535]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36535) 33568 introduced too many changes in modules without tests
- [[36593]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36593) Add support for the `time` column type on TestBuilder
- [[36268]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36268) Letters.t assumes an empty ReplyToDefault
- [[35548]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35548) Move KitchenSink test on its own and control table creation
- [[36012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36012) ERM/Agreements_spec.ts might be failing if run too slow
- [[36397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36397) t/db_dependent/Koha/Plugins/authority_hooks.t fails with Elasticsearch
- [[36355]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36355) Auth/csrf.ts is failing if library with long info in the DB
- [[35904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35904) C4::Auth::checkauth cannot be tested easily
- [[35506]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35506) selenium/regressions.t is failing randomly

## Tools

- [[36128]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36128) Use of uninitialized value in string eq at /usr/share/koha/lib/C4/Overdues.pm
- [[37129]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37129) Patron attributes linked to an authorized value don't show a select menu in batch modification
- [[36877]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36877) Patron card creator does not work when editing layout, profile or template
- [[36838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36838) Can't approve or reject tags in the staff interface
- [[35648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35648) Allow sorting of patron categories in overdue notice/status triggers
- [[25159]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25159) Action logs should be stored in JSON (and as a diff of the change)
- [[36443]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36443) Add 'fax' to batch patron modification tool
- [[34621]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34621) Patron import option to 'Renew existing patrons' 'from the current membership expiry date' not implemented
- [[36082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36082) OPACResultsSideBar not working with library specific message
- [[36305]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36305) Inventory tools need adjustments for CSRF

## Transaction logs

- [[37182]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37182) 'datetime' field lost on pseudonymization
- [[30715]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30715) Terminology: Logs should use staff interface and not intranet for the interface
- [[27291]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27291) Change datetime format in Zebra logs

## translate.koha-community.org

- [[36730]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36730) (Bug 35428 follow-up) po files (sometimes) fail to update

## Web services

- [[36335]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36335) ILS-DI GetRecords bad encoding for UNIMARC

## Z39.50 / SRU / OpenSearch Servers

- [[34041]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34041) z3950 responder additional options not coming through properly


