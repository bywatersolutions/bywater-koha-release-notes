
# Release Notes for clic-v18.05.08-01

## Acquisitions

- [[21605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21605) Cannot create EDI account
- [[21929]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21929) Typo in orderreceive.tt

## Architecture, internals, and plumbing

- [[22144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22144) Add method metadata() to Koha::Biblio
- [[21969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21969) Koha::Account->outstanding_* should look for debits/credits by checking 'amount'
- [[22052]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22052) DeleteExpiredOpacRegistrations should skip bad borrowers
- [[21848]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21848) Resolve unac_string warning from Circulation.t

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[21986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21986) Quotation marks are wrongly escaped in several places

## Circulation

- [[22020]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22020) Configure Columns for Patron Issues checkin hides renewal
- [[21928]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21928) CircAutoPrintQuickSlip 'clear' is not working
- [[21065]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21065) Data in account_offsets and accountlines is deleted with the patron leaving gaps in financial reports

## Command-line Utilities

- [[21908]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21908) biblio_metadata is missing from the rebuild_zebra.pl tables list

## Database

- [[21931]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21931) Upgrade from 3.22 fails when running updatedatabase.pl script

## MARC Bibliographic data support

- [[22034]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22034) Viewing record with Default framework doesn't work on MARC tab

## Notices

- [[21571]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21571) Translate notices fail on ACCTDETAILS

## OPAC

- [[22030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22030) OverDrive requires configuration for field passed as username

## Packaging

- [[17111]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17111) Automatic debian/control updates (oldstable/18.05.x)
- [[17108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17108) Automatic debian/control updates (stable/18.11.x)

## Reports

- [[21984]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21984) Unable to load second page of results for reports with reused parameters
- [[21991]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21991) Displaying more rows on report results does not work for reports with parameters

## REST api

- [[22071]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22071) authenticate_api_request does not stash koha.user in the OAuth use case

## Searching - Zebra

- [[22073]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22073) Diacritics Ž and ž not being mapped for searching (Non-ICU)

## Templates

- [[21990]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21990) No background color for div.error, must be .alert

## Test Suite

- [[14334]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14334) DBI fighting DBIx over Autocommit in tests

## Tools

- [[22022]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22022) Authorised values on the batch item modification page are not displayed in order (order by code, not lib)
- [[21465]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21465) Cannot overlay patrons when matching by cardnumber if userid exists in file and in Koha



# Release Notes for clic-v18.05.07-03



# Release Notes for clic-v18.05.07-02

## Bywater Only

- NOT IN BUGZILLA - Remove failing tests from Cache.t



# Release Notes for clic-v18.05.07-01

## About

- [[7143]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7143) Bug for tracking changes to the about page
- [[17597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17597) Outdated translation credits
- [[20720]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20720) Add libraries (sponsors) to the about page

## Acquisitions

- [[21853]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21853) Internal software error when exporting basket group as PDF with Perl > 5.24.1
- [[21282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21282) Ordered/spent lists should use prices including tax for calculations
- [[21619]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21619) Tax hints should not be abbreviated
- [[21387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21387) Receive items from - form should include tax hints the same as the ordering form
- [[21725]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21725) Incorrect HAVING in group by in Acquisitions.pm
- [[21587]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21587) Patrons to notify on receiving doesn't work on new order creation, only on modification
- [[16754]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16754) Use validation plugin in budgets, planning, and contracts

## Architecture, internals, and plumbing

- [[21969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21969) Koha::Account->outstanding_* should look for debits/credits by checking 'amount'
- [[21896]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21896) Add Koha::Account::reconcile_balance
- [[20997]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20997) Add Koha::Account::Line::apply
- [[21905]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21905) Plugin hook intranet_catalog_biblio_enhancements_toolbar_button incorrectly filtered
- [[21910]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21910) Koha::Library::Groups->get_search_groups should return the groups, not the children
- [[21955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21955) Cache::Memory should not be used as L2 cache
- [[21869]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21869) Bad update statement loses values for MarkLostItemsAsReturned
- [[21867]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21867) Replace remaining document.element.onchange calls in marc_modification_templates.js
- [[18584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18584) Our legacy code contains trailing-spaces
- [[21719]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21719) Fix typos in codebase
- [[20968]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20968) Plugins: Add hooks to enable plugin integration into catalogue
- [[21604]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21604) Cannot add/edit funds, cannot add budgets
- [[18720]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18720) Get rid of "die" in favor of exceptions in C4::Acquisition::GetBasketAsCsv
- [[21621]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21621) Incorrect GROUP BY in tools/letter.pl
- [[21680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21680) Remove dead code C4::Accounts::fixaccounts
- [[21639]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21639) Phone notice transports do not exist for new installs
- [[21612]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21612) Incorrect GROUP BY in Koha::Virtualshelves
- [[21635]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21635) Incorrect GROUP BY clause in batchMod.pl
- [[20521]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20521) dev installations should run with problematic SQL modes
- [[21599]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21599) Incorrect decimal value: '' for column 'defaultreplacecost' - Cannot create item type
- [[21598]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21598) budget_parent_id isn't in GROUP BY - GetBudgetHierarchy
- [[21593]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21593) Remove Group by clause in GetAuthValueDropbox
- [[21082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21082) OverDrive authentication method no longer supported

## Authentication

- [[21311]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21311) Remove locked message from opac-auth.tt

## Bywater Only

- NOT IN BUGZILLA - Fix for failing t/db_dependent/TestBuilder.t
- NOT IN BUGZILLA - BUG FIX for: Bug XXX - Add option to SIP2 config to send shelving location in CR instead of collection code
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[21774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21774) Cloned item subfields disappear when editing an item
- [[21666]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21666) Advanced editor search- error is given for 'Unsupported Use attribute' when searching on title + author
- [[21556]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21556) Deleting same record twice leads to fatal software error
- [[21742]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21742) Incorrect count of youtube videos
- [[20592]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20592) updateitem.pl causes database errors when empty non-public item notes updated

## Circulation

- [[15524]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15524) Set limit on maximum possible holds per patron by category
- [[21915]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21915) Add a way to automatically reconcile balance for patrons
- [[18805]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18805) Currently it is impossible to apply credits against debits in patron accounts
- [[20598]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20598) Accruing fines not closed out by longoverdue.pl if WhenLostForgiveFine is not enabled
- [[18677]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18677) issue_id is not added to accountlines for lost item fees
- [[21796]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21796) Patron Restriction do not restrict checkouts if patron also has a fee/fine on their account
- [[21777]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21777) Checkouts table in circulation is out of alignment
- [[21641]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21641) Software error when checking out an item with a charge associated with it
- [[21562]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21562) Sorting on checkout date is broken

## Command-line Utilities

- [[21640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21640) Itivia outbound script doesn't print to STDOUT
- [[21698]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21698) FIX POD of cancel_unfilled_holds.pl

## Course reserves

- [[21349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21349) Instructors with special characters (e.g. $, ., :) in their cardnumber cannot be removed from course reserves
- [[21603]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21603) Incorrect GROUP BY clause in SearchCourses

## Database

- [[21015]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21015) Members.pm slow because it loads twice Koha::Schema
- [[21617]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21617) statistics.ccode is not long enough (see also dbrev 18.06.00.032)

## Fines and fees

- [[21673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21673) Koha::Account::Lines->total_outstanding must be used when needed
- [[21849]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21849) Offsets not stored correctly in _FixOverduesOnReturn
- [[21702]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21702) mancredit.pl incorrectly passes user_id instead of the patron id

## I18N/L10N

- [[21490]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21490) Disambiguation of "Order"
- [[21351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21351) Traditional Chinese Language pack should have file name "zh-Hant-TW" not "zh-Hans-TW"

## ILL

- [[21585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21585) Missing firstnames should be gracefully ignored in ILL requests table
- [[21497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21497) Dates should be correctly formatted for ILL requests in OPAC

## Installation and upgrade (command-line installer)

- [[21654]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21654) Installer is loading a non-existent file

## Lists

- [[21874]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21874) Encoding broken in list and cart email subjects
- [[21629]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21629) List sort on call number does not use cn_sort

## MARC Authority data support

- [[21962]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21962) The `searching entire record` option in authority searches is currently failing
- [[21644]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21644) UNIMARC XSLT display of 210 in intranet
- [[21581]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21581) Matching rules for authorities do not respect 'Search index' setting

## MARC Bibliographic data support

- [[21749]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21749) Importing MARC frameworks from pre-9701 fails

## Notices

- [[21529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21529) Fix display of HTML tags in print notices
- [[21277]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21277) fr-CA translation for notices in sample_notices.sql

## OPAC

- [[21911]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21911) Scoping OPACs by branch does not work with new library groups
- [[21771]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21771) Password recovery is broken (see 20023)
- [[21476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21476) Incorrect filter prevents HTML5 media from playing in the OPAC
- [[21590]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21590) "send list" email uses the term "virtual shelf", this should be "list".

## Packaging

- [[17111]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17111) Automatic debian/control updates (oldstable/18.05.x)

## Patrons

- [[21778]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21778) Sorting is inconsistent on patron search based on permissions
- [[21649]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21649) Add child button in the staff client is no longer automatically populating the parent address
- [[12258]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12258) Datatable in Patrons Account Fines
- [[21080]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21080) patron attribute classes break patron's edit view
- [[21634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21634) "Circulation" option is lost when viewing patron's logs

## Reports

- [[21837]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21837) Overdues report shoudln't set homebranchfilter as holdingbranchfilter
- [[21005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21005) Missing row/column defaults cause unexpected results in report wizards

## Searching

- [[14716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14716) Correctly URI-encode URLs in XSLT result lists and detail pages
- [[20758]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20758) Typo in BrowseResultSelection syspref description

## Serials

- [[21505]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21505) Box around 'Additional fields' does not contain the fields
- [[21554]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21554) Using Subscription Batch Edit produces Software Error
- [[20351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20351) Implement blocking errors for serials scripts

## SIP2

- [[22076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22076) SIP checkin for withdrawn item returns ok in checkin response
- [[22043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22043) SIP Checkin Response alert flag set to often set to Y incorrectly
- [[22016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22016) Always send CT field for SIP checkin, even if empty
- [[22014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22014) Add ability to send "00" in SIP CV field on checkin success
- [[21486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21486) SIP does not return  checked out (charged) items on patron_information request

## Staff Client

- [[21405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21405) Pagination in authorities search broken for Zebra and broken for 10000+ results in ES
- [[21158]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21158) Add cronjob references to the system preference descriptions if a cronjob is required
- [[21606]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21606) Issues with matching rules
- [[21456]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21456) The 'New authority' button lists authority types inconsistently

## System Administration

- [[21730]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21730) PA_CLASS missing from list of authorized values categories
- [[21815]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21815) Rephrase HidePersonalPatronDetailOnCirculation a little bit
- [[21625]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21625) Fix wording and typo in SMSSendDriver system preference description

## Templates

- [[21740]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21740) Fixed-length fields show _ instead of @ when editing subfields
- [[10442]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10442) Remove references to non-standard "error" class
- [[21186]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21186) Incorrect Bootstrap modal event name in multiple templates
- [[21531]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21531) Subscription "New fields" button should read "New field"
- [[21513]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21513) Add a 'Cancel' button to the authority editor and remove duplicate 'Save' button
- [[14786]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14786) Use text "MARC file" instead of "ISO2709" everywhere

## Test Suite

- [[21567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21567) WebService:ILS related tests fail during package build
- [[21787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21787) GetHardDueDate.t has a silly test
- [[21775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21775) Lack of tests for audio alerts
- [[21717]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21717) TestBuilder.t is failing randomly
- [[18959]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18959) Text_CSV_Various.t must skip if Text::CSV::Unicode is not installed
- [[21600]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21600) t/db_dependent/api/v1/patrons.t is failing with new SQL modes
- [[21597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21597) Test suite is still failing with new default SQL modes
- [[21155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21155) SwitchOnSiteCheckouts.t is failing randomly

## Tools

- [[21861]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21861) The MARC modification template actions editor does not always validate user input
- [[21819]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21819) Marc modification templates action always checks Regexp checkbox
- [[21854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21854) Patron category is not showing during batch modification
- [[21242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21242) Modification log redirects you to circulation with no borrower if 'Object' field is not populated with borrowernumber
- [[21579]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21579) showdiffmarc tool during manage staged batches always looks for biblios even when matching authorities

## Web services

- [[19945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19945) ILSDI - Return the reason a reserve is impossible
- [[21542]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21542) OverDrive password submission should use a password field to mask input



# Release Notes for clic-v18.05.05-05

## About

- [[7143]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7143) Bug for tracking changes to the about page

## Acquisitions

- [[21537]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21537) Template error when creating a new order from a suggestion
- [[21417]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21417) EDI ordering fails when basket and EAN libraries do not match
- [[21385]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21385) Vendor search: Item count is incorrectly updated on partial receive
- [[19271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19271) Ordered/Spent lists should display vendor name, not vendor code
- [[21425]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21425) basketno not being interpolated into error message
- [[16739]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16739) Generate EDIFACT on basket groups falsely showing when configuration is incomplete
- [[21398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21398) Search term when adding an order from an existing record should be required
- [[21356]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21356) Missing space in parcel.tt
- [[21288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21288) Slowness in acquisition caused by GetInvoices
- [[15408]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15408) Timestamp on funds not updated when you duplicate a budget
- [[20014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20014) When adding to basket from a staged file item budgets are selected by matching on code, not id
- [[21033]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21033) Remove few warns in acqui/basket.pl
- [[21048]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21048) suggest_status not behaving properly
- [[21097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21097) Missing optgroup closing tag in orderreceive.tt

## Architecture, internals, and plumbing

- [[21082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21082) OverDrive authentication method no longer supported
- [[21352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21352) Allow plugins to add CSS and Javascript to Staff interface
- [[21115]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21115) Add multi_param call and add divider in cache key in svc/report and opac counterpart
- [[19687]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19687) Recent upgrade to 17.05.04.000 bulkmarcimport started to fail
- [[15734]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15734) Audio Alerts broken
- [[21500]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21500) Warnings in rotating collections
- [[20287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20287) Move AddMember and ModMember to Koha::Patron
- [[21432]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21432) Internal Server Error in Checkout History
- [[21133]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21133) Missing use C4::Accounts statement in Koha/Patron.pm
- [[21396]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21396) Missing use statements in Koha::Account
- [[20669]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20669) Add upgrade method to plugins
- [[21202]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21202) C4::Items - Remove GetItemsByBiblioitemnumber
- [[21207]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21207) C4::Overdues::GetItems is not used
- [[19991]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19991) use Modern::Perl in OPAC perl scripts
- [[21182]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21182) acqui/check_duplicate_barcode_ajax.pl is not longer in use
- [[20509]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20509) Data consistency - authority types
- [[20631]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20631) C4::Acounts claims to use ReturnLostItem but doesn't
- [[21238]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21238) TemplateToolkit.t is failing on slow server
- [[21221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21221) Implement blocking errors for members/memberentry.pl
- [[20661]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20661) Implement blocking errors for circulation scripts
- [[21056]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21056) Changing the logged in library can fail sporadically
- [[21154]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21154) Remove unused subs from C4::Serials
- [[20980]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20980) Manual credit offsets are stored as debits
- [[20990]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20990) Add Koha::Account::outstanding_credits
- [[20079]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20079) Display stack trace for development installations

## Authentication

- [[20023]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20023) Password recovery should be case insensitive
- [[21323]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21323) Redirect page after login missing multiple params
- [[13779]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13779) sessionID declared twice in C4::Auth::checkauth()
- [[18947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18947) Unexpected Active Directory LDAP authentication failure mode

## Bywater Only

- NOT IN BUGZILLA - This is an empty commit
- NOT IN BUGZILLA - Fix audio alerts so selectors can use both single and double quotes without breaking, fixed in master as of 5e3f428ade0a20062df1fd2852cb4cb99ae06f7b
- NOT IN BUGZILLA - Don't drop the branches_overdrive table on each upgrade
- NOT IN BUGZILLA - Remove t/Koha_ExternalContent_RecordedBooks.t, it doesn't pass without credentials and doesn't fail properly
- NOT IN BUGZILLA - Don't alter MarkLostItemsAsReturned if it has already been upgraded
- NOT IN BUGZILLA - Remove uses of raw TT plugin
- NOT IN BUGZILLA - Add transliteration for Ž in ICU chains
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Translation updates RMaint followup for Koha 18.05.05
- NOT IN BUGZILLA - Translations: (rmaint followup) - Mark failing strings as fuzzy
- NOT IN BUGZILLA - Bug 20770: ILL loans OPAC form notes field allow arbitrary input

## Cataloging

- [[18655]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18655) Unimarc field 210c fails on importing fields with a simple quote
- [[21365]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21365) BiblioAddsAuthorities does not work with the Advanced MARC Editor - Rancor
- [[21448]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21448) Field 606 doesn't add multiple x subfields
- [[20785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20785) Advanced Editor does not honor MarcFieldDocURL
- [[21362]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21362) Advanced MARC Editor - Rancor - Tab navigation not working in fixed fields
- [[21407]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21407) Can't enter new macros in the advanced cataloging editor (rancor)
- [[14662]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14662) Allow blank values in pull downs in cataloguing forms when subfield is mandatory
- [[21064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21064) Advanced cataloging editor - rancor - check for changes should return 'undefined' instead of 'undef'
- [[21053]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21053) Editing 008 field with a hash overwrites data

## Circulation

- [[10382]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10382) collection and location not returning to null when removed from course reserves
- [[21464]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21464) Overdues export is missing lot of fields
- [[16420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16420) Buttons inconsistent between "Hold found" and "Hold found (waiting)" dialogs in checkin
- [[21463]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21463) Library is no longer displayed in the overdue list
- [[21176]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21176) decreaseLoanHighHolds does not properly calculate date when  TimeFormat set to 12 hour
- [[21168]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21168) Error on circ/returns.pl after deleting checked-in item
- [[21231]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21231) BlockReturnofLostItems does not prevent lost items being found
- [[20487]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20487) AddReturn should clear items.onloan for unissued items
- [[20660]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20660) AddReturn should use return date override for debarments

## Command-line Utilities

- [[21322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21322) process_message_queue.pl --type should take an argument
- [[21150]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21150) Data inconsistencies - item types
- [[21011]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21011) Data inconsistencies - items.holdingbranch | items.homebranch
- [[20795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20795) koha-rebuild-zebra should pass through increased verbosity
- [[21035]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21035) runreport.pl prints only a newline when printing a row that has a field that contains an embedded newline
- [[21122]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21122) Make check-url-quick.pl handle utf8 characters in urls gracefuly
- [[20811]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20811) Fix wrong usage of ModBiblio in bulkmarcimport.pl

## Custom For Instance

- NOT IN BUGZILLA - Bug fix and DBIC update
- NOT IN BUGZILLA - Fix bug introduced by rebase

## Database

- [[5458]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=5458) length of items.ccode disagrees with authorised_values.authorised_value
- [[20777]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20777) Remove unused field accountlines.dispute
- [[20773]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20773) bug 20724 follow-up - Database cleanup

## Developer documentation

- [[21077]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21077) Fix comment for statistics.type in installer/data/mysql/kohastructure.sql

## Fines and fees

- [[21673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21673) Koha::Account::Lines->total_outstanding must be used when needed
- [[21167]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21167) Price should be correctly formatted on printed fee receipt and invoice
- [[21196]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21196) C4::Overdues::CalcFine should consider default item type replacement cost

## Hold requests

- [[21495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21495) Regression in hold override functionality
- [[21320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21320) Holds to pull should honor syspref AllowHoldsOnDamagedItems
- [[21389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21389) Javascript error on article requests page
- [[21075]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21075) AutoUnsuspendHolds should unsuspend holds <= today
- [[21076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21076) Javascript error on article requests page

## I18N/L10N

- [[19500]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19500) Make module names on letters overview page translatable

## ILL

- [[20548]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20548) Remove copyright clearance workflow from staff created ILL requests
- [[21289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21289) Error when sending emails to partner libraries

## Installation and upgrade (command-line installer)

- [[21426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21426) setting USE_MEMCACHED to "no" in koha-sites.conf does not have any effect
- [[21440]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21440) koha-create expects the file passed by $DEFAULTSQL to be in gzip format
- [[16690]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16690) Improve security of remote database installations

## Installation and upgrade (web-based installer)

- [[20683]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20683) Update German web installer for 18.05

## Label/patron card printing

- [[21281]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21281) Label Template - Creation not working
- [[20765]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20765) Search for items by acqdate does not work in label batch
- [[8604]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8604) Patron cards made for patrons which don't have patron images use preceding card's image
- [[6647]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=6647) Label item search should use standard pagination routine

## Lists

- [[21297]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21297) "More lists" screen missing "Select an Existing list" fieldset when all lists are public

## MARC Bibliographic data support

- [[20910]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20910) 773$g not displayed if $0 is present

## Notices

- [[15971]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15971) Serial claim letters should allow the use of all biblio and biblioitems fields (like issn)

## OPAC

- [[17602]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17602) Integrate support for RecordedBooks (formerly OneClickDigital) API
- [[21479]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21479) Removing from cart removes 2 items
- [[21493]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21493) Remove incomplete icon style from serial issues tabs
- [[21078]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21078) Overdrive JS breaks when window opened from another site
- [[21127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21127) Remove jqTransform jQuery plugin from the OPAC
- [[20994]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20994) Fix capitalization on OPAC result list "Save to Lists"
- [[19291]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19291) Make breadcrumbs for OPAC search history consistent with other patron account pages
- [[21018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21018) OPAC Resource URL Broken if Tracklinks is enabled
- [[21094]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21094) Syndetics: always use https instead of http
- [[16575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16575) Irregular behaviour using window.print() followed by window.location.href=

## Packaging

- [[17237]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17237) Stop koha-create from creating MySQL users without host restriction
- [[21267]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21267) X_FORWARDED_PROTO header should be set in apache

## Patrons

- [[21353]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21353) Merge patrons option only available with manage_patron_lists
- [[20656]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20656) Print summary for patron shows paid fines and formats payments badly
- [[21096]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21096) Garbled username on intranet login page
- [[21068]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21068) Remove NorwegianPatronDB related code
- [[7996]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7996) Patron modification log requires parameters permission
- [[21208]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21208) Housebound deliverer/chooser have wrong name when creating a visit
- [[18635]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18635) Koha::Patron->guarantees() should return results alphabetically
- [[21041]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21041) "Merge patrons" button remains disabled with "Select all" option
- [[20806]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20806) Item type in holds history table should be written as description, not code

## REST api

- [[21334]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21334) Add bibliographic content type definitions
- [[21116]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21116) Add API routes through plugins
- [[21031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21031) Apache Rewrite rules don't work for API when using anything but Debian package Plack configuration
- [[20942]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20942) Add route to get patron's account balance

## Searching

- [[20151]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20151) Search is broken when stemming has no language
- [[21455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21455) Authority search options get shuffled around when you click on 'Search'
- [[9968]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=9968) Incorrect index used for 'Standard number' in advanced search
- [[19390]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19390) OPAC view link in staff results should open in a new tab

## Searching - Elasticsearch

- [[20273]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20273) Elasticsearch: Auth-finder.pl autocomplete must use search_auth_compat
- [[19604]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19604) Elasticsearch Fixes for build_authorities_query for auth searching
- [[21032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21032) Refining a search made on a specific index fail

## Searching - Zebra

- [[21416]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21416) 'gr' option missing from ZEBRA_LANGUAGE options in koha-sites.conf

## Serials

- [[21552]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21552) RoutingListNote should use raw filter and display HTML unescaped
- [[20241]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20241) Fix display of publication year in subscription record search for MARC21

## SIP2

- [[21486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21486) SIP does not return  checked out (charged) items on patron_information request

## Staff Client

- [[21766]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21766) Default sounds broken in 18.05 - wrong filter/link
- [[21583]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21583) Novelist Select staff client not working in staff client - ns2init.js not loading
- [[21291]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21291) Article requests page doesn't show MARC, LabeledMARC and ISBD in sidebar
- [[13406]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13406) Add classes to MARC Authority display to enable CSS styling
- [[21248]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21248) Fix COinS carp in MARC details page on unknown record
- [[17625]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17625) 245f and 245g are not displayed in XSLT
- [[20504]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20504) Language attribute in html tag is empty in system preference editor
- [[20647]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20647) When ILL is enabled the hover effect on the ILL requests button is wrong.

## System Administration

- [[21279]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21279) Transport cost matrix shows html entity in all empty cells
- [[19179]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19179) Email option for SMSSendDriver is not documented as a valid setting
- [[21144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21144) ROADTYPE missing from authorised value categories list
- [[21131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21131) Changing and restoring a WYSIWYG preference can result in unexpected behaviour
- [[21151]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21151) SRU search fields mapping pop-up comes up empty

## Templates

- [[21186]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21186) Incorrect Bootstrap modal event name in multiple templates
- [[21550]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21550) DataTables four button pagination uses the wrong icon for disabled buttons
- [[21506]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21506) DataTables four button pagination uses the wrong icon for First and Last buttons
- [[13272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13272) Many inputs lack a type attribute
- [[21350]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21350) Add Font Awesome icon for pending onsite checkouts link
- [[21397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21397) Routing list tab not marked as active
- [[20223]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20223) Merge members-menu and circ-menu inc files
- [[13692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13692) Series link is only using 800a instead of 800t
- [[21285]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21285) Select2 broken on high dpi screens
- [[21139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21139) The floating toolbars have some issues
- [[20984]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20984) MARC21 subfield 300f - Type of Unit  does not display
- [[21243]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21243) Regression: SRU mapping popup for bibliographic records is unstyled
- [[19511]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19511) Local cover images not centered in table column in staff client search results
- [[21112]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21112) Re-indent staff client cart template
- [[21164]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21164) Fix alignment on new basket form in acquisitions
- [[21185]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21185) Incorrect title tag on tags review page
- [[21125]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21125) Shortcut moredetail.pl on nonexistent biblionumber
- [[20828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20828) Step 4 of moremember is used for Housebound and additional attributes
- [[21148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21148) Dropdowns styled by the Select2 plugin do not highlight missing required fields
- [[21145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21145) The "Column visibility" button should not be displayed at the OPAC
- [[21099]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21099) Floating toolbars reposition too late
- [[20974]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20974) Remove files left behind after removing Solr
- [[21038]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21038) Reserves should be holds

## Test Suite

- [[20177]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20177) Remove GROUP BY clause in GetCourses
- [[21262]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21262) Do not format numbers for editing if too big
- [[21360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21360) IssueSlip.t is failing if run at 23:59
- [[21355]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21355) GetDailyQuotes.t is fragile
- [[20776]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20776) Add Selenium::Remote::Driver to dependencies
- [[21230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21230) Reserves.t is failing randomly
- [[21213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21213) Circulation.t needs diagnostics
- [[21188]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21188) t/db_dependent/Circulation/issue.t is failing
- [[21134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21134) Wrong error handling in Koha/Patron/Modification.pm hides a bug
- [[20757]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20757) Capture a screenshot on selenium errors

## Tools

- [[20131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20131) Inventory optional filters always shows "For loan" for value 0
- [[21113]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21113) Hint Messages are misleading at "Merge Selected Patrons" in Patron Lists
- [[20564]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20564) Error 500 displays when uploading patron images with a zipped file
- [[21142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21142) Batch item/record modification/deletion tools does not open uploaded files in utf-8
- [[21141]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21141) Batch item modification tool throws error 500 when an itemnumber is invalid

## translate.koha-community.org

- [[21480]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21480) misc/translator/translate does not work with perl 5.26

## Web services

- [[21235]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21235) Remove services_throttle if not required for ThingISBN
- [[21199]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21199) Patron's attributes are displayed on GetPatronInfo's ILSDI output regardless opac_display
- [[21203]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21203) ILS-DI - GetRecords crashes on non-existent records
- [[21226]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21226) Remove use of retired OCLC xISBN service


