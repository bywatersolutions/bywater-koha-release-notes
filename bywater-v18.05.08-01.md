
# Release Notes for bywater-v18.05.08-01

## Acquisitions

- [[21605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21605) Cannot create EDI account
- [[21929]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21929) Typo in orderreceive.tt

## Architecture, internals, and plumbing

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



# Release Notes for bywater-v18.05.07-04

## Architecture, internals, and plumbing

- [[22144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22144) Add method metadata() to Koha::Biblio



# Release Notes for bywater-v18.05.07-03



# Release Notes for bywater-v18.05.07-02

## Bywater Only

- NOT IN BUGZILLA - Remove failing tests from Cache.t



# Release Notes for bywater-v18.05.07-01

## Acquisitions

- [[21853]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21853) Internal software error when exporting basket group as PDF with Perl > 5.24.1

## Architecture, internals, and plumbing

- [[21969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21969) Koha::Account->outstanding_* should look for debits/credits by checking 'amount'
- [[21905]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21905) Plugin hook intranet_catalog_biblio_enhancements_toolbar_button incorrectly filtered
- [[21910]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21910) Koha::Library::Groups->get_search_groups should return the groups, not the children
- [[21955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21955) Cache::Memory should not be used as L2 cache
- [[21869]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21869) Bad update statement loses values for MarkLostItemsAsReturned
- [[21867]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21867) Replace remaining document.element.onchange calls in marc_modification_templates.js

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[21774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21774) Cloned item subfields disappear when editing an item

## Circulation

- [[20598]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20598) Accruing fines not closed out by longoverdue.pl if WhenLostForgiveFine is not enabled
- [[18677]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18677) issue_id is not added to accountlines for lost item fees
- [[21796]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21796) Patron Restriction do not restrict checkouts if patron also has a fee/fine on their account

## Fines and fees

- [[21849]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21849) Offsets not stored correctly in _FixOverduesOnReturn

## Lists

- [[21874]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21874) Encoding broken in list and cart email subjects

## MARC Authority data support

- [[21962]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21962) The `searching entire record` option in authority searches is currently failing
- [[21644]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21644) UNIMARC XSLT display of 210 in intranet

## Notices

- [[21529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21529) Fix display of HTML tags in print notices

## OPAC

- [[21911]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21911) Scoping OPACs by branch does not work with new library groups

## Packaging

- [[17111]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17111) Automatic debian/control updates (oldstable/18.05.x)

## Patrons

- [[21778]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21778) Sorting is inconsistent on patron search based on permissions
- [[21649]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21649) Add child button in the staff client is no longer automatically populating the parent address

## Reports

- [[21837]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21837) Overdues report shoudln't set homebranchfilter as holdingbranchfilter

## Staff Client

- [[21405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21405) Pagination in authorities search broken for Zebra and broken for 10000+ results in ES

## System Administration

- [[21730]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21730) PA_CLASS missing from list of authorized values categories
- [[21815]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21815) Rephrase HidePersonalPatronDetailOnCirculation a little bit

## Test Suite

- [[21567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21567) WebService:ILS related tests fail during package build

## Tools

- [[21861]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21861) The MARC modification template actions editor does not always validate user input
- [[21819]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21819) Marc modification templates action always checks Regexp checkbox
- [[21854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21854) Patron category is not showing during batch modification



# Release Notes for bywater-v18.05.06-07

## SIP2

- [[22076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22076) SIP checkin for withdrawn item returns ok in checkin response

## Web services

- [[19945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19945) ILSDI - Return the reason a reserve is impossible



# Release Notes for bywater-v18.05.06-06

## Bywater Only

- NOT IN BUGZILLA - Fix for failing t/db_dependent/TestBuilder.t

## Circulation

- [[15524]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15524) Set limit on maximum possible holds per patron by category

## SIP2

- [[22043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22043) SIP Checkin Response alert flag set to often set to Y incorrectly



# Release Notes for bywater-v18.05.06-05

## SIP2

- [[22043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22043) SIP Checkin Response alert flag set to often set to Y incorrectly



# Release Notes for bywater-v18.05.06-04

## SIP2

- [[22016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22016) Always send CT field for SIP checkin, even if empty



# Release Notes for bywater-v18.05.06-03

## SIP2

- [[22014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22014) Add ability to send "00" in SIP CV field on checkin success



# Release Notes for bywater-v18.05.06-02

## Architecture, internals, and plumbing

- [[21969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21969) Koha::Account->outstanding_* should look for debits/credits by checking 'amount'

## Bywater Only

- NOT IN BUGZILLA - BUG FIX for: Bug XXX - Add option to SIP2 config to send shelving location in CR instead of collection code



# Release Notes for bywater-v18.05.06-01

## About

- [[7143]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7143) Bug for tracking changes to the about page
- [[17597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17597) Outdated translation credits
- [[20720]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20720) Add libraries (sponsors) to the about page

## Acquisitions

- [[21282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21282) Ordered/spent lists should use prices including tax for calculations
- [[21619]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21619) Tax hints should not be abbreviated
- [[21387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21387) Receive items from - form should include tax hints the same as the ordering form
- [[21725]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21725) Incorrect HAVING in group by in Acquisitions.pm
- [[21587]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21587) Patrons to notify on receiving doesn't work on new order creation, only on modification
- [[16754]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16754) Use validation plugin in budgets, planning, and contracts

## Architecture, internals, and plumbing

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

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[21666]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21666) Advanced editor search- error is given for 'Unsupported Use attribute' when searching on title + author
- [[21556]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21556) Deleting same record twice leads to fatal software error
- [[21742]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21742) Incorrect count of youtube videos
- [[20592]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20592) updateitem.pl causes database errors when empty non-public item notes updated

## Circulation

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

- [[21629]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21629) List sort on call number does not use cn_sort

## MARC Authority data support

- [[21581]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21581) Matching rules for authorities do not respect 'Search index' setting

## MARC Bibliographic data support

- [[21749]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21749) Importing MARC frameworks from pre-9701 fails

## Notices

- [[21277]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21277) fr-CA translation for notices in sample_notices.sql

## OPAC

- [[21771]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21771) Password recovery is broken (see 20023)
- [[21476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21476) Incorrect filter prevents HTML5 media from playing in the OPAC
- [[21590]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21590) "send list" email uses the term "virtual shelf", this should be "list".

## Patrons

- [[12258]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12258) Datatable in Patrons Account Fines
- [[21080]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21080) patron attribute classes break patron's edit view
- [[21634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21634) "Circulation" option is lost when viewing patron's logs

## Reports

- [[21005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21005) Missing row/column defaults cause unexpected results in report wizards

## Searching

- [[14716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14716) Correctly URI-encode URLs in XSLT result lists and detail pages
- [[20758]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20758) Typo in BrowseResultSelection syspref description

## Serials

- [[21505]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21505) Box around 'Additional fields' does not contain the fields
- [[21554]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21554) Using Subscription Batch Edit produces Software Error
- [[20351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20351) Implement blocking errors for serials scripts

## SIP2

- [[21486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21486) SIP does not return  checked out (charged) items on patron_information request

## Staff Client

- [[21158]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21158) Add cronjob references to the system preference descriptions if a cronjob is required
- [[21606]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21606) Issues with matching rules
- [[21456]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21456) The 'New authority' button lists authority types inconsistently

## System Administration

- [[21625]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21625) Fix wording and typo in SMSSendDriver system preference description

## Templates

- [[21740]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21740) Fixed-length fields show _ instead of @ when editing subfields
- [[10442]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10442) Remove references to non-standard "error" class
- [[21186]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21186) Incorrect Bootstrap modal event name in multiple templates
- [[21531]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21531) Subscription "New fields" button should read "New field"
- [[21513]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21513) Add a 'Cancel' button to the authority editor and remove duplicate 'Save' button
- [[14786]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14786) Use text "MARC file" instead of "ISO2709" everywhere

## Test Suite

- [[21787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21787) GetHardDueDate.t has a silly test
- [[21775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21775) Lack of tests for audio alerts
- [[21717]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21717) TestBuilder.t is failing randomly
- [[18959]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18959) Text_CSV_Various.t must skip if Text::CSV::Unicode is not installed
- [[21600]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21600) t/db_dependent/api/v1/patrons.t is failing with new SQL modes
- [[21597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21597) Test suite is still failing with new default SQL modes
- [[21155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21155) SwitchOnSiteCheckouts.t is failing randomly

## Tools

- [[21242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21242) Modification log redirects you to circulation with no borrower if 'Object' field is not populated with borrowernumber
- [[21579]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21579) showdiffmarc tool during manage staged batches always looks for biblios even when matching authorities

## Web services

- [[21542]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21542) OverDrive password submission should use a password field to mask input



# Release Notes for bywater-v18.05.05-05

## Architecture, internals, and plumbing

- [[21896]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21896) Add Koha::Account::reconcile_balance
- [[20997]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20997) Add Koha::Account::Line::apply

## Bywater Only

- NOT IN BUGZILLA - remove extra line from rebase

## Circulation

- [[21915]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21915) Add a way to automatically reconcile balance for patrons
- [[18805]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18805) Add ability to use up account credits

## Fines and fees

- [[21673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21673) Koha::Account::Lines->total_outstanding must be used when needed

## Hold requests

- [[21495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21495) Regression in hold override functionality



# Release Notes for bywater-v18.05.05-04

## Bywater Only

- NOT IN BUGZILLA - This is an empty commit
- NOT IN BUGZILLA - Fix audio alerts so selectors can use both single and double quotes without breaking, fixed in master as of 5e3f428ade0a20062df1fd2852cb4cb99ae06f7b

## Templates

- [[21186]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21186) Incorrect Bootstrap modal event name in multiple templates


