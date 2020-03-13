
# Release Notes for marywood-v19.05.08-02

## About

- [[24136]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24136) Add libraries (sponsors) to the about page
- [[22862]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22862) It should be possible to paste formatted phone numbers into the SMS messaging number field
- [[21662]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21662) Missing developers from history
- [[23037]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23037) Henry Bolshaw is missing from the contributors list
- [[21626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21626) Add 'current maintenance team' to the 'Koha team' page
- [[21502]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21502) Add checks for YAML formatted system preferences to about page

## Acquisitions

- [[9993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=9993) On editing basket group delivery place resets to logged in library
- [[22868]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22868) Circulation staff with suggestions_manage can have access to acquisition data
- [[17667]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17667) Standing orders - cancelling a receipt increase the original quantity
- [[24404]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24404) Add missing space on invoices page
- [[24277]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24277) Date Received in acquisitions cannot be changed
- [[24244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24244) Cannot create suggestion with branch set to 'Any'
- [[24242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24242) Funds with no library assigned do not appear on edit suggestions page
- [[5365]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=5365) It should be more clear how to reopen a basket in a basket group
- [[23854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23854) Cannot edit a suggestion
- [[18743]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18743) Filter suggestion lists correctly for IndependentBranches
- [[23863]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23863) Editing a basket clears create_items value
- [[23855]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23855) Cannot mark the selected suggestion as "pending"
- [[23101]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23101) Contracts permissions for staff patron
- [[22786]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22786) Can create new funds for locked budgets
- [[23397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23397) Order lines can be duplicated in acqui scripts spent.pl and ordered.pl
- [[23319]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23319) Reloading page when adding to basket from existing order can cause internal server error
- [[23294]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23294) Restore actual cost input field on order page
- [[23338]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23338) Cannot specify replacement price when ordering from file if not using fields to order
- [[23251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23251) EDI Order line incorrectly terminated when it ends with a quoted apostrophe
- [[23363]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23363) Clicking on shipping cost invoice link from spent.pl causes internal server error
- [[21316]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21316) Adding controlfields to the ACQ framework causes issues when adding to basket
- [[22905]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22905) Cannot update the status of suggestions if the branchcode filter is set to all
- [[4833]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=4833) Show acquisition information when ordering from a suggestion
- [[22713]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22713) Replacement price removed when receiving if using MarcItemFieldstoOrder
- [[5770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=5770) Email librarian when purchase suggestion made
- [[21364]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21364) Allow closing basket from vendor search/view
- [[22669]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22669) Cannot edit received item in acquisitions with acqcreateitem set to "when placing an order"
- [[22556]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22556) Add ability to quickly filter funds/budgets by library on the Acquisitions home page
- [[22664]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22664) Link basket name and basket group name instead of the, often short, basket numbers
- [[21308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21308) Show the search filters used on the search results page for acquisitions history searches
- [[6730]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=6730) Rename 'basket' filter to 'basket name' on receive page
- [[18736]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18736) Problems in order calculations (rounding errors)
- [[18952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18952) Show internal note in acquisitions details tab
- [[15774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15774) Additional fields for baskets
- [[22293]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22293) Sticky toolbar making vendor form uneditable
- [[16939]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16939) Making all 'add to basket' actions buttons
- [[19850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19850) Enhance invoicing functionality for each line item

## Architecture, internals, and plumbing

- [[23290]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23290) XSLT system preferences allow administrators to exploit XML and XSLT vulnerabilities
- [[24213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24213) Koha::Object->get_from_storage should return undef if the object has been deleted
- [[23896]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23896) logaction should pass the correct interface to Koha::Logger
- [[23407]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23407) XSLT Details pages don't use items, we shouldn't pass them
- [[22220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22220) Error in ReWriteRule for 'bib' in apache-shared-intranet.conf
- [[24313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24313) XSLT errors should show in the logs
- [[24016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24016) manager_id in Koha::Patron::Message->store should not depend on userenv alone
- [[23997]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23997) sample_z3950_servers.sql is failing on MySQL 8
- [[24243]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24243) Bad characters in MARC cause internal server error when searching catalog
- [[24106]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24106) In returns.pl, don't search for item if no barcode is provided
- [[22857]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22857) Entries missing in koha-conf.xml
- [[21987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21987) Local cover 'thumbnail' size is bigger than 'imagefile' size in biblioimages table
- [[23867]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23867) 18.12.00.051 fails with "Truncated incorrect DOUBLE value"
- [[23723]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23723) Using exit inside eval to stop sending output to the browser doesn't work under Plack
- [[23627]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23627) Koha::Biblio->get_coins too noisy if no 245$b
- [[23539]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23539) accountlines.accounttype should match authorised_values.authorised_value in size
- [[23316]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23316) GetFine needs updating for bug 22521
- [[23230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23230) Make Koha::Plugins::Base::_version_compare OO
- [[23144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23144) Bad POD breaks svc/barcode
- [[23117]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23117) additem.pl crashes on nonexistent biblionumber
- [[23095]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23095) Circulation rules not displayed (empty vs null)
- [[22046]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22046) Simplify C4::Matcher->get_matches
- [[22893]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22893) contributors.yaml not correctly copied
- [[19302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19302) Pass objects to IsAvailableForItemLevelRequest
- [[22757]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22757) Use YAML CodeMirror higlighting on YAML preferences
- [[21757]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21757) Patron detail script (moremember.pl) cleanup
- [[22765]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22765) Add class beside loggedinusername to indicate if logged in user is a superlibrarian
- [[22056]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22056) Remove test/search.pl
- [[22511]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22511) Koha::Account::Line->void loses the original type of the credit
- [[22729]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22729) flgAnonymized shouldn't be NULL and should be renamed anonymized
- [[22696]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22696) Simplify visibility logic in opac-ISBDdetail.pl
- [[22701]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22701) Make items prefetchable from Koha::Biblio
- [[22694]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22694) Add a method for checking OpacHiddenItems exceptions in Koha::Patron::Category
- [[22700]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22700) Make biblio_metadata prefetchable from Koha::Biblio
- [[22748]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22748) Wrong permission check in addbiblio.pl
- [[22755]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22755) Import Koha::Script to patron_emailer cronjob
- [[22749]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22749) Koha::Item->hidden_in_opac should consider hidelostitems syspref
- [[22564]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22564) accounttype 'Rep' is still referred to but is never set
- [[22532]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22532) Remove "random" from Z39.50
- [[22521]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22521) Convert fines handling to use 'status' instead of two accounttypes
- [[13795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13795) Delete unused columns from statistics table
- [[22311]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22311) Add a SysPref to allow adding content to the #moresearches div in the opac
- [[22044]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22044) NoRenewalBeforePrecision should be set by default for new installations
- [[21890]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21890) Allow forgotten password functionality to be limited by patron category
- [[22600]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22600) We should add an 'interface' field to accountlines
- [[22512]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22512) accountlines.accountype mixes 'state' and 'type'
- [[22607]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22607) Default value in issues.renewals should be '0' not null
- [[22518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22518) accounttype 'O' is still referred to but is never set
- [[22127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22127) Update dateaccessioned value builder
- [[22516]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22516) accountlines.lastincrement can be removed
- [[12159]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12159) Duplicate borrower_add_additional_fields function
- [[10577]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10577) C4::Budgets::GetBudgetPeriod has inappropriate overloading of its behavior
- [[22454]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22454) Add Koha::Item::hidden_in_opac method
- [[22455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22455) Add Koha::Biblio::hidden_in_opac method
- [[21756]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21756) Deprecate C4::Accounts::manualinvoice (use Koha::Account->add_debit instead)
- [[22363]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22363) Move C4::Logs::GetLogs to Koha namespace
- [[22483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22483) haspermissions previously supported passing 'undef' for $flagsrequired
- [[22031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22031) C4::Auth->haspermission should allow checking for more than one subpermission
- [[21721]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21721) Update C4::Circulation::AddRenewal to use Koha::Account->add_debit
- [[18925]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18925) Move maxissueqty and maxonsiteissueqty to circulation_rules
- [[21728]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21728) Update C4::Reserves::ChargeReserveFee to use Koha::Account->add_debit
- [[21720]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21720) Update C4::Circulation::AddIssuingCharge to use Koha::Account->add_debit
- [[21722]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21722) Update C4::Accounts::chargelostitem to use Koha::Account->add_debit
- [[21747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21747) Update C4::Overdues::UpdateFine to use Koha::Account->add_debit and Koha::Account::Line->adjust
- [[21875]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21875) Handling subject line in Letters.pm
- [[22026]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22026) Remove `use  Modern::Perl` from Koha::REST::classes
- [[21206]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21206) C4::Items - Remove GetItem
- [[22049]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22049) MarkIssueReturned should rely on returndate only
- [[22144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22144) Add method metadata() to Koha::Biblio
- [[22194]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22194) Add Koha::Exceptions::Metadata
- [[21002]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21002) Add Koha::Account::add_debit
- [[21992]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21992) Remove Koha::Patron::update_password
- [[22048]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22048) Use set_password instead of update_password in the codebase
- [[21727]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21727) Add Koha::Account::Line->adjust
- [[21999]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21999) C4::Circulation::AddIssue uses DBIx::Class directly
- [[22003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22003) Remove unused subroutines displaylog and GetLogStatus from in C4::Log
- [[21980]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21980) Add some new Exceptions for Koha::Account methods
- [[21788]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21788) C4::Circulation::ProcessOfflinePayment should pass library_id to ->pay
- [[21909]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21909) Koha::Account::outstanding_* methods should preserve call context
- [[21969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21969) Koha::Account->outstanding_* should look for debits/credits by checking 'amount'

## Authentication

- [[23042]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23042) Local login attempt populates shibboleth url with userid and password in plain text
- [[23771]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23771) CAS/Shib Authentication can fail when multiple users with no userid/cardnumber defined and one of them is locked
- [[23526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23526) Shibboleth login url with query has double encoded '?' %3F
- [[22585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22585) Fix remaining double-escaped CAS links
- [[22692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22692) Logging in via cardnumber circumvents account logout
- [[22461]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22461) Regression in #20287: LDAP user replication broken with mapped extended patron attributes

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Prune Docker images
- NOT IN BUGZILLA - GitHub Actions - Add Auto-rebasing of XSLT branches, leave disabled
- NOT IN BUGZILLA - GitHub Actions - Prevent workflow from running on tags, associate release with correct branch
- NOT IN BUGZILLA - GitHub Actions - Build Debian packaage
- NOT IN BUGZILLA - Update filter and add page id for 'Koha as a CMS' feature
- NOT IN BUGZILLA - GitHub Actions
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Bug 24333: Add password class to AutoSelfCheck syspref
- NOT IN BUGZILLA - Update teams for 20.05 cycle
- NOT IN BUGZILLA - Koha 18.12 - ...and Steven!

## Cataloging

- [[16683]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16683) Help links to fields 59X in cataloguing form are broken
- [[24452]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24452) Advanced editor - show multiple spaces visually
- [[24236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24236) Using quotes in a cataloging search, resulting in multiple pages, will not allow you to advance page
- [[24423]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24423) Broken link to return to record after batch item modification or deletion
- [[24323]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24323) Advanced editor - Invalid 008 with helper silently fails to save
- [[24173]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24173) Advanced Editor: Show subtitle & published date on the search page
- [[24232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24232) Fix permissions for deleting a bib record after attaching the last item to another bib
- [[11500]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11500) Use dateformat syspref and datepicker on additems.pl (and other item cataloguing pages)
- [[24090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24090) Subfield text in red when mandatory in record edition
- [[23851]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23851) Auto generate accession number format <branchcode>yymm0001 fails to add branchcode prefix(branchcode) for multiple item addition
- [[23252]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23252) Pressing enter should not submit form in item editor
- [[22830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22830) correct for loop in value_builder/unimarc_field_4XX.pl value_builder
- [[23436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23436) Save to 'undefined' showing in Advanced cataloging editor
- [[21518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21518) Material type "three-dimensional artifact" displays as "visual material"
- [[23045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23045) Advanced cataloging editor (rancor) throws a JS error on incomplete/blank lines
- [[21411]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21411) Advanced cataloging editor - rancor - Allow configuration of Keyboard shortcuts
- [[15496]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15496) Delete bibliographic record after moving last item to another record(s)
- [[20128]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20128) Permission for advanced editor
- [[22525]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22525) Navigation arrows on the bottom of Cataloging search pages
- [[22399]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22399) Improve responsive behavior of the basic marc editor
- [[22045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22045) Cataloging UX enhancement - Improve access to tabs
- [[21826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21826) Automatic authority record generation improvements

## Circulation

- [[24802]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24802) Updating holds can cause suspensions to apply to wrong hold
- [[24547]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24547) Add more action logs for holds
- [[24441]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24441) Error when checking in an item with BranchTansferLimitsType set to itemtype
- [[24085]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24085) Double submission of forms on returns.pl
- [[23658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23658) [18.11] WrongTransfer modal drops off specified checkin date on returns.pl
- [[24214]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24214) Due date displayed in ISO format (when sticky)
- [[23233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23233) AllowItemsOnHoldCheckout is misnamed and should only work for for SIP-based checkouts
- [[23382]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23382) Issuing rules failing after bug 20912
- [[24166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24166) Barcode removal breaks circulation.pl/moremember.pl
- [[24337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24337) Checkout note cannot be marked seen if more than 20 exist
- [[24335]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24335) Cannot mark checkout notes seen/not seen in bulk
- [[24308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24308) Suggestions table on suggestions.pl should have separate columns for dates
- [[24259]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24259) Circulation fails if no circ rule defined but checkout override confirmed
- [[24138]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24138) suspension miscalculated when Suspension charging interval bigger than 1 and Max. suspension duration  is defined
- [[23427]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23427) Better sorting of previous checkouts
- [[13958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13958) Add a suspensionsCalendar syspref
- [[24024]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24024) Holds Awaiting Pickup (Both Active and Expired) Sorts by Firstname
- [[24075]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24075) Backdating a return to the exact due date and time results in the fine not being refunded
- [[23985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23985) The method Koha::Item-> is not covered by tests!
- [[23774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23774) When placing a hold editing using Inspect Element allows addition to the code of non listed library
- [[23938]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23938) Title missing from Checked out box
- [[23551]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23551) Problem with renewal period when using the renewal tab
- [[23679]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23679) Software error when trying to transfer an unknown barcode
- [[23404]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23404) Circulation::TooMany error on itemtype when at biblio level
- [[23079]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23079) Checkouts page broken because of problems with date calculation (TZAmerica/Sao_Paulo)
- [[23518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23518) Problem with borrower search  autocomplete
- [[23273]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23273) Downloading from overdues.pl doesn't use set filters
- [[23408]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23408) Relatives' checkout table columns are not configured properly
- [[23405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23405) Circulation autocomplete for patron lookup broken if cardnumber is empty
- [[23145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23145) Confirming transfer during checkin clears the table of previously checked-in items
- [[21027]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21027) Totals in statistics tab change when StatisticsFields is changed
- [[23192]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23192) Cancelling holds over returning to wrong tab on waitingreserves.pl
- [[23255]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23255) HomeOrHoldingbranch system preference options are described wrong
- [[23220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23220) Cancelling transfer on returns.pl is subject to a race condition
- [[23158]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23158) on-site checkout missing when using itemBarcodeFallbackSearch
- [[23098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23098) KOC upload process has misleading wording
- [[22617]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22617) Checkout notes pending dashboard link - error received even though manage_checkout_notes permission set
- [[23097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23097) Circulation Overdues report patron link  goes to patron's holds tab
- [[23103]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23103) Cannot checkin items lost by deleted patrons with fines attached
- [[23061]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23061) The column/print/export buttons are missing on the checkout history page
- [[13094]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13094) It should be easy to hide the 'Cancel all' button on the holds over report
- [[22982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22982) Paying lost fee does not always remove lost item from checkouts
- [[22877]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22877) Returning a lost item not marked as returned can generate additional overdue fines
- [[22809]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22809) Move "INVOICE" from template to a slip
- [[22761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22761) Move "Fee receipt" from template to a slip
- [[7088]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7088) Cannot renew items on hold even with override
- [[10300]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10300) Allow transferring of items to be have separate IndependentBranches syspref
- [[22200]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22200) Forgiving a fine (FOR) does not create a FORGIVEN credit line
- [[14576]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14576) Allow automatic update of location on checkin
- [[22679]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22679) circulation_rules are not deleted when accompanying issuingrules are deleted
- [[22759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22759) Circulation rules for maxissueqty are applied per branch even for defaults
- [[17171]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17171) Add a syspref to allow currently issued items to be issued to a new patron without staff confirmation
- [[20912]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20912) Rental fees based on time period
- [[14591]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14591) book drop / drop box mode incorrectly decrements accrued overdue fines
- [[17353]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17353) Add phone number column to checkout search
- [[21915]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21915) Add a way to automatically reconcile balance for patrons
- [[19066]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19066) Add branchcode to accountlines
- [[21754]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21754) If an item is marked as lost, any outstanding transfers upon it should be automatically cancelled
- [[21065]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21065) Data in account_offsets and accountlines is deleted with the patron leaving gaps in financial reports

## Command-line Utilities

- [[24511]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24511) Patron emailer report not using specified email column
- [[24105]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24105) Longoverdue gives error message when --itemtypes are specified
- [[19465]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19465) Allow choosing Elasticsearch server on instance creation
- [[24164]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24164) Patron emailer cronjob is not generating unique content for notices
- [[23933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23933) commit_file.pl Can't call method "get_effective_marcorgcode" on an undefined value at /usr/share/koha/lib/C4/AuthoritiesMarc.pm line 578.
- [[16219]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16219) Runreport.pl should allow SQL parameters to be passed on the command line
- [[23345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23345) Wrong parameter name in koha-dump usage statement
- [[23193]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23193) Make set_password.pl use Koha::Script
- [[22128]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22128) koha-remove fails mysql ERROR 1133 (42000) at line 2: Can't find any matching row in the user table
- [[22566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22566) Stock rotation cronjob reporting has issues
- [[20436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20436) Add ability to specify itemtypes for longoverdue.pl
- [[20485]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20485) Don't account for items timestamps when combining "dont_export_items=1" and "date" in misc/export_records.pl
- [[22580]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22580) Remove deprecated delete_expired_opac_registrations.pl cronjob
- [[21975]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21975) Unnecessary substitutions in automatic item modification by age
- [[22593]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22593) Cronjobs/Scripts dealing with accountlines need updating for bug 22008
- [[22299]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22299) Typo in parameter of import_patrons.pl: preserve_extended_atributes
- [[22238]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22238) Remove koha-*-sip scripts in favor of koha-sip
- [[22235]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22235) Make maintenance scripts use koha-sip instead of koha-*-sip

## Course reserves

- [[24283]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24283) Missing close parens and closing strong tag in course reserves
- [[23952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23952) Fix body id on OPAC course details page
- [[22142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22142) An item's current location changes to blank when it is removed from Course Reserves
- [[23083]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23083) Course reserve item edit fails if one does not set all values
- [[22899]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22899) Cannot view course details
- [[21446]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21446) Improve display of changed values on course reserves and show permanent location instead of cart

## Custom For Instance

- NOT IN BUGZILLA - Github Actions - Run all in parallel

## Database

- [[24289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24289) Deleting branch will not delete entry in special or repeatable holidays
- [[24377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24377) Record branch in statistics for auto-renewal
- [[23995]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23995) Check constraints are supported differently by MySQL and MariaDB so we should remove them for now.
- [[23579]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23579) error during web install: 'changed_fields' can't have a default value
- [[23809]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23809) Update to DB revision 16.12.00.032 fails
- [[23265]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23265) Update to DB revision 16.12.00.032 fails: Unknown column 'me.item_level_hold'
- [[22634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22634) Standardize table creation for stockrotation* tables in kohacstructure.sql
- [[22008]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22008) accountlines.manager_id is missing a foreign key constraint
- [[22368]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22368) Table suggestions lacks foreign key constraints
- [[13515]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13515) Table messages is missing FK constraints and is never cleaned up
- [[22155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22155) biblio_metadata.marcflavour should be renamed 'schema'
- [[21753]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21753) issuingrules.chargename is unused and should be removed

## Developer documentation

- [[22358]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22358) Add POD to Koha::SharedContent

## Documentation

- [[8701]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8701) Help for OpacHiddenItems pref should not point to text in install directory

## Fines and fees

- [[24146]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24146) Paying Accruing Fines prior to return causes another accruing fine when returned
- [[24637]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24637) Pay selected & Pay amount does not log branchcode in 19.05
- [[23443]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23443) Paying off a lost fee will return the item, even if it is checked out to a different patron
- [[23483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23483) When writing off a fine, the title of the patron is shown as description
- [[23826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23826) Manual Invoice does not use new accounttype and status for fines
- [[23115]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23115) Totals are unclear when a credit is involved on the OPAC 'Fines and charges' screen
- [[23106]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23106) Totals are unclear when a credit is involved on the 'Pay fines' screen
- [[22674]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22674) Change wording of payments in the GUI
- [[22628]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22628) FFOR and VOID show up as codes to end users in OPAC, SCO and staff
- [[22626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22626) 'Filter paid transactions' broken on Transactions tab in staff
- [[12166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12166) Improve display of hold charges in patron account
- [[22533]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22533) Cannot create manual invoices
- [[21683]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21683) Remove accountlines.accountno
- [[19489]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19489) Detailed description of charges on Accounting tab
- [[22301]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22301) Paying fines is broken when using CurrencyFormat = FR
- [[11373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11373) Add "change calculation" feature to the fine payment forms
- [[22148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22148) Cancelling some payments/writeoffs redirects to unexpected page
- [[21918]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21918) Clean up pay fines template
- [[21578]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21578) 'Pay fines' tab incorrectly describes the purpose
- [[21844]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21844) Add callnumber to fines descriptions

## Hold requests

- [[23964]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23964) An item level hold when placed is set to Waiting, if ReservesNeedReturn is set to Automatic
- [[21296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21296) Suspend hold ignores system preference on intranet
- [[20567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20567) "Holds per record (count)" limit is not enforced after item is captured for hold
- [[24485]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24485) AllowHoldPolicyOverride should allow Staff to override the Holds Per Record Rule
- [[20948]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20948) Item-level hold info displayed regardless its priority (detail.pl)
- [[24168]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24168) Errors with use of CanItemBeReserved return value
- [[23484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23484) Holds to pull (pendingreserves.pl) uses removed default_branch_item_rules table
- [[23502]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23502) Staff client "revert status" buttons should not depend on SuspendHoldsIntranet preference
- [[14549]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14549) Hold not removed when item is checked out to patron who is not next in priority list
- [[22021]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22021) Item status not shown accurately on request.pl
- [[23048]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23048) Hide non-pickup branches from hold modification select
- [[13640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13640) Holds To Pull List includes items unreserveable items
- [[22633]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22633) Barcodes in the patrons 'holds' summary should link to the moredetail page
- [[20421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20421) Apply CheckPrevCheckout logic when placing a hold on the staff client
- [[20837]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20837) CanItemBeReserved should follow ReservesControlBranch and not CircControl
- [[22372]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22372) Add shelving location to Holds awaiting pickup report
- [[19630]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19630) "Hold is suspended" message appears in barcode field in holds table
- [[22631]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22631) Make links on barcode on hold summary page consistent (bug 21070)
- [[22330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22330) Transfer limits should be respected for placing holds in staff interface and APIs
- [[19469]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19469) Add ability to split view of holds view on record by pickup library and/or itemtype
- [[21070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21070) request.pl details links to biblio instead of moredetail.pl for that item
- [[19770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19770) Add cardnumber to holds awaiting pickup screen and add classes to borrower info

## I18N/L10N

- [[23790]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23790) fr-CA translation of ACCOUNT_DEBIT and ACCOUNT_CREDIT notices
- [[24063]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24063) Add Sami language characters to Zebra
- [[24358]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24358) "Bibliographic record does not exist!" is not translatable
- [[18688]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18688) Warnings about UTF-8 charset when creating a new language
- [[24046]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24046) 'Activate filters' untranslatable
- [[13749]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13749) On loading holds in patron account 'processing' is not translatable
- [[23713]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23713) Subscription add form broken for translations
- [[23631]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23631) fr-CA translation of NEW_SUGGESTION notice
- [[10492]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10492) Translation problems with TT directives in po files
- [[22783]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22783) 'Location' not picked up by translation toolchain
- [[11375]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11375) Improve patrons permissions display

## ILL

- [[21270]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21270) "Not finding what you're looking" display needs to be fixed
- [[23529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23529) Interlibrary loan javascript is broken
- [[22280]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22280) The ILL module assumes every status needs a next/previous status
- [[23229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23229) "Get all requests" API call fired when loading any ILL page
- [[21460]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21460) Filtering ILL requests on borrowernumber does not work
- [[18589]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18589) Show ILLs as part of patron profile
- [[20563]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20563) ILL request list gives no indication of source and/or target
- [[18837]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18837) Add an unmediated Interlibrary Loans workflow
- [[21063]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21063) Allow columns in intranet ILL request datatable to be customisable
- [[20750]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20750) Allow timestamped auditing of ILL request events
- [[20639]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20639) Allow setting a default/single backend for OPAC driven requests
- [[20581]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20581) Allow manual selection of custom ILL request statuses
- [[20600]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20600) Provide the ability for users to filter ILL requests
- [[22121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22121) Display 'Price paid' on ILL requests according to CurrencyFormat pref
- [[20640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20640) Allow migrating a request between backends

## importedbugs

- [[18939]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18939) Record matching rules didnot work by matching with callnumber

## Installation and upgrade (command-line installer)

- [[24328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24328) Bibliographic frameworks fail to install
- [[23813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23813) DB error on 18.12.00.020
- [[23250]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23250) koha-create generates broken mysql password
- [[23090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23090) MySQL validate_password plugin breaks koha-create

## Installation and upgrade (web-based installer)

- [[24314]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24314) Update de-DE MARC21 frameworks for updates 28+29 (May and November 2019)
- [[24137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24137) Marc21 bibliographic fails to install for ru-Ru and uk-UA
- [[23353]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23353) ACQ framework makes fr-CA web installer explode
- [[23396]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23396) Rancor fails to load: insert_copyright is not defined
- [[22966]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22966) Add Norwegian library and patron names for the web-based installer
- [[22770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22770) Typo in German translation for Greek in language pull down
- [[22489]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22489) Onboarding tool fails due to inserting maxissueqty into IssuingRule
- [[22024]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22024) Update translated web installer files with new class splitting rules

## Label/patron card printing

- [[23289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23289) Label Template - Creation not working (MariaDB >= 10.2.4)
- [[23455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23455) Patron card printing from Patron lists is broken

## Lists

- [[23266]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23266) Add to cart fires twice on shelf page
- [[17526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17526) OPAC lists sortfield breaks with a `(`
- [[12759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12759) Add ability to pass list contents to batch record modification/deletion tools
- [[21751]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21751) fixFloat toolbar not displaying properly in Chrome

## Mana-kb

- [[23034]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23034) Warning when in Mana KB settings Auto subscription sharing is unchecked
- [[23130]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23130) Incorrect alternative mana server URL in etc/koha-conf.xml
- [[22210]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22210) ManaKB should not require firstname and lastname for signup
- [[22915]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22915) Cannot subscribe to Mana-KB

## MARC Authority data support

- [[24421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24421) Generated authorities are missing subfields
- [[24267]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24267) C4::Breeding::ImportBreedingAuth is ineffective
- [[23437]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23437) When UseAuthoritiesForTracing is 'Use' we should use series authorities
- [[23053]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23053) Local-Number cannot be used for authority matching due to non-existence of 'phrase' index

## MARC Bibliographic data support

- [[24312]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24312) Update MARC21 frameworks to Updates 28+29 (May and November 2019)
- [[24274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24274) New installations should not contain field 01e Coded field error (RLIN)
- [[24281]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24281) Fix the list of types of visual materials
- [[23731]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23731) Display LC call number in OPAC and staff detail pages
- [[17831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17831) Remove non-existing bibliosubject.subject mapping from frameworks

## MARC Bibliographic record staging/import

- [[24348]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24348) Record matching rules: required match checks does not work
- [[23846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23846) Handle records with broken MARCXML on the bibliographic detail view
- [[23324]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23324) Need an ISBN normalization routine
- [[19164]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19164) Allow MARC modification templates to be used in staged MARC imports

## Notices

- [[24235]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24235) /misc/cronjobs/advance_notices.pl DUEDGST does NOT send sms, just e-mail
- [[24268]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24268) advance_notices.pl dies on undefined letter
- [[24072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24072) Typos in advance_notices.pl causes DUEDGST not to be sent
- [[24064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24064) DUEDGST typoed as DUEGST
- [[23765]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23765) After TranslateNotices is set to 'Don't allow', email settings still show multiple languages
- [[23181]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23181) Unable to use payment library in ACCOUNT_PAYMENT or ACCOUNT_WRITEOFF notices
- [[22744]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22744) Remove confusing 'Do not notify' checkboxes from messaging preferences
- [[21180]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21180) Allow Talking Tech outbound script to limit based on patron home library branchcode
- [[23278]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23278) Reopen last panel upon "Save and continue" in notices
- [[8000]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8000) Test mode for notices
- [[16149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16149) Generate and send custom notices based on report output
- [[20478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20478) Advance notices: send separate digest messages per library
- [[21241]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21241) Set suggestion notices message_transport_type to sms if syspref is enabled and patron has an smsalertnumber but no email address

## OPAC

- [[21701]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21701) Have PayPal optionally return to originating OPAC url rather than OPACBaseURL
- [[22302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22302) ITEMTYPECAT description doesn't fall back to description if OPAC description is empty
- [[24523]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24523) Fix opac-password-recovery markup mistake
- [[17697]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17697) Improve NotesBlacklist system preference description to make clear where it will apply
- [[24486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24486) Account Wording Information is duplicated in Patron's Fines Tab on OPAC
- [[24061]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24061) Print List (opac-shelves.pl) broken in Chrome
- [[24206]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24206) Change URLs for default options in OPACSearchForTitleIn
- [[23528]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23528) Show 'log in to add tags' link on all search result entries
- [[24371]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24371) OPAC 'Showing only available items/Show all items' is double encoded
- [[24212]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24212) OPAC send list dialog opens too small in IE
- [[24245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24245) opac-registration-confirmation.tt has incorrect HTML body id
- [[24240]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24240) List on opac missing close form tag under some conditions
- [[23785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23785) Software error Can't call method "get_coins" on an undefined value at /usr/share/koha/opac/cgi-bin/opac/opac-search.pl line 692.
- [[23506]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23506) Sound material type displays wrong icon in OPAC/Staff details
- [[23836]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23836) tracklinks.pl should not forward if TrackClicks is disabled
- [[23329]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23329) tracklinks.pl accepts any url from a parameter for proxying if not tracking
- [[23451]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23451) Reflected XSS in opac-imageviewer.pl
- [[22543]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22543) Patron might be logged in again using browser back button
- [[23467]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23467) Duplicated screen if error in opac-reserve.pl
- [[22804]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22804) OPAC Overdrive JavaScript contains untranslatable strings
- [[23683]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23683) Course reserves public notes on specific items should allow for HTML
- [[23625]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23625) ArticleRequestsMandatoryFields* only affects field labels, does not make inputs required
- [[22602]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22602) OverDrive circulation integration is broken when user is referred to Koha from another site
- [[23537]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23537) Overdrive won't show complete results if the Overdrive object doesn't have a primaryCreator
- [[16111]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16111) RSS feed for OPAC search results has wrong content type
- [[23530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23530) Opac-basket.pl script accidentally displays 'hidden' items
- [[23210]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23210) login4tags should be a link
- [[23253]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23253) OpacNavRight does not display correctly for opacuserlogin disabled or self registration
- [[23428]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23428) Self registration with a verification by email is broken
- [[23099]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23099) OPAC Search result sorting "go" button flashes on page load
- [[23431]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23431) having Date of birth in PatronSelfModificationBorrowerUnwantedField causes DOB to be nullified
- [[23078]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23078) Use Koha.Preference in OPAC global header include
- [[23308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23308) Contents of "OpacMaintenanceNotice" HTML escaped on display
- [[12537]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12537) Editions tab showing on bibs with more than one ISBN
- [[23194]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23194) Public notes items in the OPAC should allow for HTML tags
- [[22951]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22951) Markup error in OPAC holds template
- [[23248]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23248) opac-ISBDdetail.pl dies on invalid biblionumber
- [[23225]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23225) OPAC ISBD view returns 404 when no item attached
- [[23126]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23126) Multiline entries in subscription history display with <br/> in OPAC
- [[22949]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22949) Markup error in OPAC course reserves template
- [[23151]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23151) Patron self modification sends null dateofbirth
- [[23150]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23150) GDPR feature breaks patron self modification on OPAC
- [[22946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22946) Markup error in OPAC search results around selection links
- [[23122]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23122) When searching callnumber in simple search, search option is not retained
- [[22657]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22657) Remove JavaScript from OPAC suggestion validation of required fields
- [[22803]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22803) Set dataTable width issue
- [[21533]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21533) Do not allow password recovery for administrative locked patrons (see 21336)
- [[8995]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8995) Show OpenURL links in OPAC search results
- [[22772]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22772) Menu link hover color incorrect in OPAC language choosers
- [[22537]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22537) Don't show Suspend all holds button when holds can no longer be susppended in OPAC
- [[22645]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22645) Add 'ISSN' option to OPAC's basic search
- [[11969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11969) Show patrons star rating on their reading history
- [[22576]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22576) OPAC password change text changes
- [[22638]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22638) Self checkin CSS update
- [[22588]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22588) Simplify getting account information in opac and self checkout module
- [[22501]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22501) OPAC course reserves notes should allow html links
- [[13782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13782) RSS for news needs a bit of styling
- [[22568]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22568) Replace RSS icon in the OPAC with Font Awesome
- [[22432]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22432) Star ratings plugin replacement missing from a couple pages
- [[22559]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22559) OPAC Forgotten password functionality not working
- [[21846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21846) Using emoji as tags doesn't discriminate between emoji when calculating weights or searching
- [[22370]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22370) OPAC users should not be allowed to view staff news items
- [[12318]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12318) Show subscription shelving location on subscription tabs
- [[14272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14272) Allow OPAC to show a single news entry
- [[21850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21850) Remove search request from page title of OPAC result list
- [[21871]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21871) Show authority 856 links in the OPAC
- [[22102]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22102) Markup fixes for OPAC article request page
- [[21399]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21399) Sort patron fines in OPAC by date descending as a default
- [[22030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22030) OverDrive requires configuration for field passed as username

## Packaging

- [[21000]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21000) debian/build-git-snapshot script ignores -D

## Patrons

- [[14759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14759) Replacement for Text::Unaccent
- [[21939]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21939) Permission for holds history tab is too strict
- [[23822]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23822) Regression: As of 19.05.04 deletion of patrons with outstanding credits is silently blocked
- [[23589]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23589) Discharge notice does not show non-latin characters
- [[17140]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17140) Incorrect rounding in total fines calculations, part 2
- [[23688]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23688) System preference uppercasesurnames broken by typo
- [[21390]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21390) Self registration verification emails should send immediately
- [[22741]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22741) Koha::Patron->store must not log updated_on changes (random failure of test BorrowerLogs and TrackLastPatronActivity)
- [[23217]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23217) Batch patron modification shows database errors when no Attribute provided
- [[23218]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23218) Batch patron modification empty attribute causes improper handling of values
- [[23199]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23199) Koha::Patron->store and uppercasesurname syspref
- [[23077]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23077) Can't import patrons without cardnumber
- [[22944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22944) avoid AnonymousPatron in search_patrons_to_anonymise
- [[22928]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22928) "Update child to adult patron" link no longer displayed
- [[21312]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21312) Show lockout on Patrons form
- [[21535]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21535) Anonymize function in Patron should not scramble email addresses
- [[21336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21336) GDPR: Handle unsubscribe requests automatically by optional (administrative) lock, anonymize and remove
- [[3766]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=3766) Cities/Towns only on one address
- [[21953]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21953) Term "Lost item" is untranslatable
- [[10796]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10796) Allow password changes for logged in OPAC users by patron category
- [[22594]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22594) Validate SMS messaging numbers using the E.164 format
- [[22505]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22505) Add column configuration to patron list table
- [[22198]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22198) Add granular permission setting for Mana KB
- [[22253]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22253) Koha throws an exception when updating a borrower with an insecure password
- [[17854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17854) New Print slip and close button next to Close button

## Plugin architecture

- [[22835]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22835) Serve static files from plugins through the API
- [[22834]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22834) Add a method for plugins to return the absolute path for bundled files
- [[23237]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23237) Add support for [% INCLUDE %] in plugin templates

## Reports

- [[23626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23626) Add a system preference to limit the number of rows of data used when charting or exporting report results
- [[13806]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13806) No input sanitization where creating Reports subgroup
- [[23389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23389) Add 'All' option to report value dropdowns
- [[23827]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23827) [19.05] Cash register statistics uses old accounttype values
- [[23624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23624) Count rows in report without (potentially) consuming all memory
- [[22856]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22856) Show SQL code button should trigger CodeMirror view
- [[8775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8775) Add collection column to built in  'Items lost' report

## REST API

- [[24191]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24191) Sorting doesn't use to_model
- [[23607]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23607) Make /patrons/:patron_id/account privileged user only
- [[23597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23597) Holds API is missing reserved parameters on the GET spec
- [[16825]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16825) Add API route for getting an item
- [[17003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17003) Add API route to get checkout's renewability
- [[22216]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22216) Make GET /patrons/{patron_id} staff only
- [[22227]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22227) Make GET /cities staff only
- [[22132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22132) Add Basic authentication to the REST API
- [[22061]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22061) Add route to change patron's password (public)
- [[21786]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21786) Routes for credits should include library_id

## Searching

- [[10879]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10879) OverDrive should check for OverDriveLibraryID before performing search
- [[24443]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24443) Consider NULL as 0 for issues in items search
- [[15142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15142) Titles facet does not work in UNIMARC
- [[24121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24121) Item types icons in intra search results are requesting icons from opac images path
- [[14419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14419) Expanding facets (Show more) performs a new search
- [[23970]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23970) itemsearch - publication date not taken into account if not used in the first field
- [[23768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23768) ISBN search in IntranetCatalogPulldown searches nothing if passed an invalid ISBN and using SearchWithISBNVariations
- [[24120]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24120) Search terms in search dropdown must be URI filtered
- [[23425]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23425) Search explodes with "invalid data, cannot decode object"
- [[11677]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11677) Limit to Only items currently available for loan or reference not working
- [[15704]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15704) The 264 index should be split by subfield to match how 260 is indexed
- [[23132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23132) Encoding issues in facets with show more link
- [[22424]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22424) Add search by all lost statuses to item search
- [[22418]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22418) Authority link magnifying glass icon doesn't appear for 655 subject tags
- [[22649]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22649) Add item type to item search results
- [[14457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14457) Integrate LIBRIS spellchecking

## Searching - Elasticsearch

- [[23719]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23719) Record matching for authorities using defined fields is broken under ES
- [[23676]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23676) Elasticsearch - 0 is not a valid boolean for suppress
- [[22426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22426) Elasticsearch - Index location is missing in advanced search
- [[17885]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17885) Koha::SearchEngine::Elasticsearch->reset_elasticsearch_mappings throws DBD::mysql Duplicate entry exceptions
- [[24123]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24123) bulkmarcimport.pl doesn't support UTF-8 encoded MARCXML records
- [[24264]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24264) Elasticsearch - Cannot search for genre/form authorities
- [[24128]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24128) Add alias for biblionumber => local-number
- [[23089]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23089) Elasticsearch - cannot sort on non-text fields
- [[23986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23986) Batch Record Deletion does not remove records from Elasticsearch search index
- [[23630]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23630) Elasticsearch indexing is removing field 999
- [[22997]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22997) Searching gives no results in auth_finder.pl
- [[23004]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23004) Missing authtype filter in auth_finder.pl
- [[23322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23322) Elasticsearch - Record matching fails when multiple keys exist
- [[22524]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22524) Elasticsearch - Date range in advanced search
- [[20607]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20607) Elasticsearch - ability to add a relevancy weight in mappings.yaml file
- [[21534]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21534) ElasticSearch - Wildcards not being analyzed
- [[22892]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22892) Warning when reindexing without parameters
- [[21872]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21872) Elasticsearch indexing faster by making it multi-threaded
- [[22339]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22339) Elasticsearch - fixed field mappings should match MARC ranges
- [[19670]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19670) search_marc_map.marc_field should have COLLATE= utf8mb4_bin
- [[18213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18213) Add language facets to Elasticsearch
- [[18235]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18235) Elastic search - Configurable facets
- [[20535]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20535) ModZebra called with $record with items stripped in ModBiblioMarc
- [[19575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19575) Use canonical field names and resolve aliased fields

## Self checkout

- [[22929]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22929) Enabling the GDPR_Policy will affect libraries using the SCO module in Koha
- [[14407]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14407) Limit web-based self-checkout to specific IP addresses
- [[22538]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22538) Add a noticeable alert about waiting holds
- [[22274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22274) Self-checkout pages not covered by OPAC CSS changes
- [[22675]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22675) SCO broken on invalid barcodes
- [[21772]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21772) Add holds and account information tab to the SCO module
- [[18251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18251) SCO alerts - need a trigger for successful checkouts
- [[19458]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19458) Self-check module highlighting

## Serials

- [[23064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23064) Cannot edit subscription with strict SQL modes turned on
- [[21232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21232) Problems when linking a subscription to a non-existing biblionumber
- [[23416]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23416) When a note to a specific issue upon receiving a serial, this note will appear in next issue received
- [[23065]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23065) 'New subscription' button in serials sometimes uses a blank form and sometimes defaults to current serial
- [[10215]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10215) Increase the size of opacnote and librariannote for table subscriptionhistory
- [[22934]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22934) Add missing use statement to Koha::AdditionalFieldValue
- [[22408]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22408) Subscription entry form cleanup

## SIP2

- [[24705]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24705) Holds placed via SIP will be given first priority
- [[24566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24566) UpdateItemLocationOnCheckin triggers SIP2 alert flag, even with checked_in_ok enabled
- [[24175]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24175) Cannot cancel holds - wrong parameter passed for itemnumber
- [[20292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20292) Filter/censor info sent via SIP
- [[22037]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22037) Regression: guarantor no longer blocked (debarred) if child is over limit, when checking out via SIP
- [[23057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23057) If checked_in_ok is set and item is not checked out, alert flag is supressed for *any* reason
- [[22790]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22790) The system preference itemBarcodeInputFilter is not applied for barcodes inputed via SIP2
- [[15253]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15253) Add Koha::Logger based logging for SIP2
- [[19619]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19619) Add support for SIP2 field CM ( Hold Pickup Date ) to Koha
- [[22076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22076) SIP checkin for withdrawn item returns ok in checkin response
- [[22043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22043) SIP Checkin Response alert flag set to often set to Y incorrectly
- [[22016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22016) Always send CT field for SIP checkin, even if empty
- [[22014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22014) Add ability to send "00" in SIP CV field on checkin success

## Staff Client

- [[24515]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24515) Column Configuration for pay-fines-table does not hide Account Type properly
- [[22381]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22381) Wording on Calendar-related system preferences not standardized
- [[23246]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23246) Record detail page jumps into the 'images' tab if no holdings
- [[23987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23987) batchMod.pl provides a link back to the record after the record is deleted
- [[24060]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24060) [19.05] Can't load patron clubs tab on patron details page
- [[23680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23680) Can't open 'Edit items' or 'Add item' links in new tab - tab is closed immediately
- [[23689]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23689) Terminology: Branches limitations should be libraries limitations - Authorised Values
- [[23651]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23651) RestrictedPage system preferences should include the address of the page in the description
- [[21716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21716) Item Search hangs when \ exists in MARC fields
- [[23315]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23315) Some system preferences are no longer editable
- [[22616]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22616) Update error text messages
- [[21582]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21582) Use CodeMirror for *UserJS & *UserCSS
- [[22553]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22553) Unchecking a subpermission does not uncheck the top level permission
- [[12283]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12283) Set autocomplete=off for patron search input

## System Administration

- [[24025]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24025) Make CodeMirror content searchable
- [[24329]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24329) Patron cardnumber change times are lost during upgrade for bug 3820
- [[24184]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24184) Reword FallbackToSMSIfNoEmail syspref text
- [[24170]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24170) sysprefs search result does not have a consistent order
- [[23751]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23751) Description of staffaccess permission should be improved
- [[24026]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24026) Wrong parameters in Koha/Templates/Plugin/CirculationRules.pm and smart-rules.tt
- [[23398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23398) Exporting/Reimporting frameworks in XML format will give incomplete results
- [[23445]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23445) Loan period unit in circulation rules is untranslatable causing problems when editing rules
- [[23309]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23309) Can't add new subfields to bibliographic frameworks in strict mode
- [[23179]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23179) Add 'Edit subfields' to framework management tag dropdown and clarify options
- [[23153]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23153) In framework management action subfields goes directly to edition
- [[23104]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23104) Regression (18925) in circ rules - unlimited vs 0
- [[22962]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22962) Wrong punctuation in RisExportAdditionalFields system preference
- [[22053]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22053) Ability to disable some plugins
- [[22847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22847) Specific circ rule by patron category is displaying the default (or not displaying)
- [[22619]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22619) Adding a new circ rule with unlimited checkouts is broken
- [[3820]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=3820) More detailed patron record changes log
- [[22191]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22191) Add column configuration to libraries administration
- [[22190]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22190) Add column configuration to patron category administration
- [[21961]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21961) Typo in permission keeps Did you mean? config from showing up

## Templates

- [[24054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24054) Typo in ClaimReturnedWarningThreshold system preference
- [[23947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23947) Phase out jquery.cookie.js: Authority merge
- [[23944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23944) Phase out use of jquery.cookie.js in favor of js.cookie.js
- [[23113]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23113) members/pay.tt account_grp is not longer used
- [[24391]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24391) Remove event attributes from patron clubs edit template
- [[24104]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24104) Item search - dropdown buttons overflow
- [[10469]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10469) Display more when editing subfields in frameworks
- [[23956]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23956) Replace famfamfam calendar icon in staff client with CSS data-url
- [[23889]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23889) Improve style of menu header in advanced cataloging editor
- [[24282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24282) SCSS conversion broke style in search results item status
- [[24230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24230) intranet_js plugin hook is after body end tag
- [[23954]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23954) Format notes in suggestion management
- [[23605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23605) Terminology: Branches limitations should be libraries limitations
- [[23575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23575) Template error causes item search to be submitted multiple times
- [[21058]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21058) Missing class for results_summary spans
- [[23446]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23446) Fix display issue with serials navigation
- [[23438]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23438) Use Font Awesome icons in intranet search results browser
- [[23226]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23226) Remove type attribute from script tags: Cataloging
- [[23304]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23304) Reindent cataloguing/z3950_search.tt
- [[22768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22768) Global search forms' keyboard navigation broken
- [[23159]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23159) Reindent addbiblio.tt
- [[23221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23221) Reindent tools/manage-marc-import.tt
- [[13597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13597) Amazon 'no image' element needs a 'no-image' class, in the staff client
- [[23227]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23227) Remove type attribute from script tags: Reports
- [[22957]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22957) Remove type attribute from script tags: Staff client includes 1/2
- [[23196]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23196) Reindent tools/batch_record_modification.tt
- [[23183]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23183) Reindent cataloging.js
- [[22935]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22935) Improve style of Bootstrap pagination
- [[22851]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22851) Navigation links in the serials module should be styled the same as other modules
- [[22960]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22960) Typo found in circulation.pref in UpdateItemLocationOnCheckin preference
- [[22906]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22906) Minor corrections to plugins home page
- [[22981]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22981) Remove type attribute from script tags: Catalog
- [[22979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22979) Remove type attribute from script tags: Authorities
- [[22975]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22975) Remove type attribute from script tags: Acquisitions
- [[22973]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22973) Remove type attribute from script tags: Staff client includes 2/2
- [[22974]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22974) Patron password update validation broken
- [[22746]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22746) Another typo found in mana-subscription-search-result.inc (Mana KB)
- [[22889]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22889) Fix typos librairies and libaries
- [[22716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22716) Use gender-neutral pronouns in system preference descriptions
- [[22811]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22811) Add button to clear DataTables filtering
- [[22035]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22035) Improve local cover image browser page
- [[22764]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22764) More YUI grid cleanup
- [[22751]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22751) Switch two-column templates to Bootstrap grid: Patron details
- [[21034]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21034) Re-indent circulation.tt
- [[21784]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21784) Clean up js_includes.inc
- [[21783]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21783) Reindent admin/columns_settings.tt
- [[21307]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21307) Switch two-column templates to Bootstrap grid: Cataloging
- [[22584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22584) Add YAML support for Codemirror
- [[22697]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22697) Reindent catalogue/result.tt
- [[21942]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21942) Clean up cataloging merge template
- [[22656]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22656) Report charts broken after bug 22023
- [[21943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21943) Clean up holds template
- [[22698]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22698) Fix incorrect button classes
- [[22695]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22695) Remove non-XSLT search results view from the staff client
- [[21891]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21891) Remove non-XSLT detail view in the staff client
- [[22250]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22250) Clean up Mana KB integration with serials and reports
- [[21646]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21646) Clean up Overdrive template
- [[22032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22032) Improve local cover image tab on detail page
- [[21304]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21304) Update two-column templates with Bootstrap grid: Catalog
- [[22023]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22023) Further improve responsive layout handling of staff client menu bar
- [[15911]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15911) Use noEnterSubmit CSS class instead of prevent_submit.js
- [[21091]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21091) Move add item template JavaScript to a separate file
- [[22452]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22452) Typos in add a comment to Mana modal
- [[22337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22337) Make it clearer that language preferences can be re-ordered
- [[21870]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21870) Convert browser alerts to modals: OPAC user summary
- [[22261]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22261) Revise style of DataTables menus
- [[22015]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22015) Move DataTables CSS to global include
- [[10659]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10659) Upgrade jQuery star ratings plugin
- [[22195]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22195) Change default DataTables configuration to consolidate buttons
- [[20809]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20809) Link patron image to patron image add/edit form
- [[22197]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22197) Add Mana KB link to administration sidebar menu
- [[22196]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22196) Clean up Mana KB administration template
- [[21449]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21449) Switch two-column templates to Bootstrap grid: Circulation part 2
- [[22134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22134) Add account expiration information to patron details
- [[21945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21945) Clean up stock rotation template
- [[22104]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22104) Clean up patron API keys template
- [[21964]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21964) Switch two-column templates to Bootstrap grid: Patrons part 2
- [[21573]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21573) Move lists barcode and biblionumber entry form to modal
- [[20729]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20729) Update style of datepickers
- [[21913]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21913) Clean up payment details page
- [[21965]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21965) Switch two-column templates to Bootstrap grid: Patrons part 3
- [[21438]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21438) Switch two-column templates to Bootstrap grid: Patron card creator
- [[21792]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21792) Switch two-column templates to Bootstrap grid: Serials part 3
- [[21672]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21672) Switch templates to Bootstrap grid: Various
- [[21785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21785) Add column configuration to hold ratios report
- [[21442]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21442) Switch two-column templates to Bootstrap grid: Circulation part 1
- [[21797]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21797) Update two-column templates with Bootstrap grid: Acquisitions part 5
- [[21803]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21803) Redesign authorized values interface
- [[21963]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21963) Switch two-column templates to Bootstrap grid: Patrons part 1
- [[21569]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21569) Switch two-column templates to Bootstrap grid: Circulation part 3
- [[21436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21436) Switch two-column templates to Bootstrap grid: Tools part 4
- [[21693]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21693) Clean up checkout notes template
- [[21695]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21695) Clean up access files template
- [[21795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21795) Switch two-column templates to Bootstrap grid: Notices and slips
- [[21790]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21790) Switch error page template to Bootstrap grid

## Test Suite

- [[24543]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24543) Wrong test in api/v1/checkouts.t
- [[23274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23274) t/db_dependent/XISBN.t fails with Elasticsearch
- [[24199]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24199) t/Auth_with_shibboleth.t is failing randomly
- [[24145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24145) Auth.t is failing because of wrong mocked ->param
- [[24144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24144) regressions.t tests have not been updated after bug 23836
- [[23234]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23234) Circulation.t failing when comparing dates that seem identical
- [[21985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21985) Test t/db_dependent/Circulation.t fails if SearchEngine is set to elasticsearch
- [[23280]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23280) Warning in t/db_dependent/selenium/patrons_search.t
- [[23211]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23211) SIP/Transaction.t is failing randomly
- [[23177]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23177) Rollback cleanup in Circulation.t
- [[23027]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23027) Suggestions.t is failing if no biblio in DB
- [[22850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22850) SharedContent.t wrongly use ->set_userenv
- [[22547]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22547) C4::Overdues - UpdateFine is barely tested
- [[22392]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22392) TestBuilder::build_sample_item should allow defining barcode
- [[22349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22349) Overzealous deletion of data in t/db_dependant/Koha/Acquisitions/Booksellers.t

## Tools

- [[24330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24330) When importing patrons from CSV, automatically strip BOM from file if it exists
- [[24497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24497) CodeMirror indentation problems
- [[24275]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24275) Inventory table should be sortable by title without leading articles (allow for title sort with anti-the)
- [[24484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24484) Add explanatory text to batch patron deletion
- [[23377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23377) bulkmarcimport.pl disables syspref caching
- [[10352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10352) Cataloguing log search mixing itemnumber/bibnumber
- [[24124]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24124) Cannot select authorities in batch deletion tool in Chrome
- [[23963]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23963) Visible reduction in image quality
- [[17359]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17359) Patron import results use wrong encoding
- [[18710]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18710) Wrong subfield modified in batch item modification
- [[22799]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22799) Batch item modification is case sensitive
- [[22272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22272) Calendar: When entering date ranges grey out dates in the past from the start date
- [[23385]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23385) Hide default value fields by default on patron import
- [[11642]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11642) Improve Batch patron deletion and anonymization GUI to make consequences clearer
- [[18707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18707) Background jobs post disabled inputs
- [[19012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19012) Note additional columns that are required during patron import
- [[22571]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22571) MARC modification templates do not handle control fields in conditional
- [[15814]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15814) Templates for MARC modification: Edit action does not work when Description contains '
- [[23093]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23093) Error during upgrade of OpacNavRight preference to Koha news
- [[22175]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22175) Make stock rotation table sortable
- [[22318]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22318) Extend Koha news feature to include other content areas
- [[22069]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22069) Log viewer not displaying item renewals
- [[19722]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19722) Add a MaxItemsToDisplayForBatchMod preference
- [[19417]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19417) Improve display of errors from background job during stage for import
- [[18661]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18661) Make "Replace only included patron attributes" default on patron import

## Web services

- [[22677]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22677) Include hint on OAI-PMH URL for Koha in system preference
- [[22249]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22249) Error when submitting Mana comment
- [[23156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23156) Add pagination to checkouts in ILS-DI GetPatronInfo service
- [[23154]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23154) Add pagination to /api/v1/checkouts
- [[22742]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22742) RenewLoan return wrong datetime format
- [[22891]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22891) ILS-DI: RenewLoan explodes in error
- [[22849]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22849) Data shared without agreement
- [[19380]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19380) Add transfer informations in ILS-DI GetRecords response
- [[22222]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22222) Mana subscription search always returns all results
- [[22237]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22237) Subscriptions are not linked to Mana upon edit
- [[17047]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17047) Mana Knowledge Base : Data sharing
- [[21738]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21738) [ILS-DI] Error placing a hold on a title without item
- [[19945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19945) ILSDI - Return the reason a reserve is impossible

## Z39.50 / SRU / OpenSearch Servers

- [[23242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23242) Error when adding new Z39.50/SRU server in DB strict mode



# Release Notes for marywood-v18.11.07-05


