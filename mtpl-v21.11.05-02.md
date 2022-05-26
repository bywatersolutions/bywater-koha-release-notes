
# Release Notes for mtpl-v21.11.05-02

## About

- [[29209]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29209) Credits for Saxion in Dutch (NL) translation

## Acquisitions

- [[24866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24866) Display budget hierarchy in the budget dropdown menu used when placing a new order
- [[29496]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29496) Can't save an order with mandatory items subfields
- [[29429]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29429) Cannot close budgets
- [[24370]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24370) Editing purchase suggestion changes the acquisition library to logged-in user's
- [[27287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27287) Make note fields from orders searchable
- [[28079]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28079) Set focus to search box field when adding an order to basket
- [[24190]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24190) Add additional Acquisition logging
- [[28640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28640) Add EDI order status to basket details display
- [[28508]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28508) Use "Invoice number" instead of "Invoice no" on the invoice search filter

## Architecture, internals, and plumbing

- [[30172]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30172) Background jobs failing due to race condition
- [[30406]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30406) Our DT tables not filtering on the correct column if hidden by default
- [[29957]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29957) Cookies not removed after logout
- [[30377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30377) Fix two CGI::param called in list context-warnings
- [[30393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30393) datatables wrapper should handle searching for %, _ and \
- [[30110]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30110) Potential bug source: plenty of "my" declarations with conditional assignments
- [[30161]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30161) Remove duplicate z3950_search include lines
- [[30253]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30253) Double mana_success line is no success
- [[30008]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30008) Software error in details.pl when invalid MARCXML and showing component records
- [[30004]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30004) Prevent TooMany from executing too many SQL queries
- [[29684]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29684) Warning File not found: js/locale_data.js
- [[29771]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29771) Get rid of CGI::param in list context warnings
- [[30185]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30185) Missing return in db rev 210600003.pl
- [[29397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29397) Add a select2 wrapper for the API
- [[29865]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29865) Wrong includes in circ/returns.pl
- [[29336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29336) Some authorised_value FKs are too short
- [[29498]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29498) Remove usage of deprecated Mojolicious::Routes::Route::detour
- [[29717]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29717) Too many DateTime manipulation in tools/additional-contents.pl
- [[29789]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29789) Unused $error in cataloguing/additem.pl
- [[29741]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29741) Add Koha::Patron->safe_to_delete
- [[29631]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29631) 21.06.000.12 may fail
- [[28959]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28959) virtualshelves.category is really a boolean
- [[28445]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28445) Use the task queue for the batch delete and update items tool
- [[17600]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17600) Standardize the EXPORT
- [[28374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28374) Convert pos/printreceipt.pl to use GetPreparedLetter
- [[28413]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28413) background job worker is running with all the modules in RAM
- [[29386]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29386) background jobs table data field is a TEXT which is too small
- [[26326]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26326) Add Koha Objects for Import Records and Import Record Matches
- [[28417]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28417) Authen::CAS::Client always loaded even if CAS is not used
- [[24850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24850) Koha::DateUtils ignores offsets in RFC3339 datetimes
- [[29395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29395) Use EXPORT_OK in Koha::Patron::Debarments
- [[29288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29288) Add current_checkouts and old_checkouts methods to Koha::Biblio
- [[27526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27526) Remove Mod/AddItemFromMarc from additem.pl
- [[29207]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29207) Restore Getopt::Long config to not ignore cases
- [[28785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28785) Code in C4::Auth::checkauth is copy pasted
- [[28769]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28769) tabloop not used in cataloguing plugins
- [[29111]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29111) Remove dead code from intranet
- [[29177]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29177) Remove TODO in acqui/finishreceive.pl
- [[29197]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29197) commit_file.pl missing import
- [[28734]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28734) Koha::Biblio->get_marc_notes should parse authorised values
- [[29182]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29182) ArticleRequest status changing methods calling SUPER::store
- [[28931]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28931) use EXPORT_OK in Koha::DateUtils
- [[29179]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29179) Useless include in moveitem.pl
- [[29083]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29083) Update article requests-related Koha::Patron methods to use relationships
- [[29086]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29086) Reuse article request filtering methods in Biblio template plugin
- [[29084]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29084) Update article requests-related Koha::Biblio methods to use relationships
- [[29082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29082) Add filtering methods to Koha::ArticleRequests
- [[27032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27032) CanBookBeRenewed is not understandable and needs refactoring
- [[29139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29139) Paying gives ISE if UseEmailReceipts is enabled
- [[28772]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28772) Any user that can work with reports can see API keys of any other user
- [[28306]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28306) Allow to query database with minimal memory footprint
- [[28373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28373) Items fields not used in default XSLT
- [[28893]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28893) Unused opac/rss directory can be removed
- [[28765]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28765) sub find_value not used in tools/batchMod.pl
- [[28763]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28763) Undefined subroutine XSLTParse4Display (bug 17600)
- [[28565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28565) Adding a new syspref for sharing through HEA should be simpler
- [[28624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28624) Smart::Comments not used and not installed
- [[28606]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28606) Replace $ENV{DEBUG} and $DEBUG with Koha::Logger->debug
- [[28561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28561) Order_by triggers a DBIx warning Unable to properly collapse has_many results
- [[28588]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28588) Add Koha::Checkouts::ReturnClaim->resolve
- [[28572]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28572) Replace C4::Debug with Koha::Logger->debug
- [[28591]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28591) debug passed to get_template_and_user but not used
- [[28590]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28590) get_shelves_userenv and set_shelves_userenv not used
- [[28514]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28514) Replace C4::Letters::getletter with Koha::Notice::Templates->find_effective_template
- [[24434]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24434) C4::Circulation::updateWrongTransfer is never called but should be

## Authentication

- [[29915]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29915) Anonymous session generates 1 new session ID per hit
- [[28489]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28489) CGI::Session is incorrectly serialized to DB in production env / when strict_sql_modes = 0

## Bywater Only

- NOT IN BUGZILLA - Remove t/db_dependent/Koha/SearchEngine/Elasticsearch/Search.t until the correction version of Search::Elasticsearch is in Koha's apt repo
- NOT IN BUGZILLA - Fix translations for Koha 21.11.05
- NOT IN BUGZILLA - Bug 34874: Add streettype and B_streettype to PrefillGuaranteeField
- NOT IN BUGZILLA - Fix translations for Koha 21.11.04
- NOT IN BUGZILLA - Fix translations for Koha 21.11.03
- NOT IN BUGZILLA - Fix translations for Koha 21.11.02
- NOT IN BUGZILLA - Fix translations for Koha 21.11.01
- NOT IN BUGZILLA - Koha 21.11.00 is here!
- NOT IN BUGZILLA - 21.11.00 - Fix translation issues
- NOT IN BUGZILLA - 21.11.00 - Update .mailmap
- NOT IN BUGZILLA - 21.11.00 - Update kohastructure.sql
- NOT IN BUGZILLA - 21.11.00 - Update history.txt
- NOT IN BUGZILLA - 21.11.00 - Update contributors.yaml
- NOT IN BUGZILLA - Koha 21.06 - start of a new dev cycle

## Cataloging

- [[30376]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30376) Unable to save item if field date acquired is set mandatory
- [[25251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25251) When a record has no items click delete all does not need an alert
- [[26328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26328) incremental barcode generation fails when incorrectly converting strings to numbers
- [[30159]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30159) Fix display of validation of important fields when biblio cataloguing
- [[30178]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30178) Every librarian can edit every item with IndependentBranches on
- [[29962]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29962) Table of items on item edit page missing columns button
- [[29690]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29690) Software error in details.pl when invalid MARCXML
- [[29689]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29689) Update to 21.11 broken auto-generated barcode in <branchcode>0001 option
- [[26587]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26587) Cache libraries in Branches TT plugin to improve performance
- [[29146]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29146) Default values from the framework should only be applied at biblio/item creation
- [[24674]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24674) Uncertain years for publicationyear/copyrightdate -- corrected
- [[28694]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28694) Check alert in cataloguing should be a static message
- [[14957]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14957) Write protecting MARC fields based on source of import
- [[11175]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11175) Show the parent record's component parts in the detailed views
- [[29137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29137) Unwanted authorised values are too easily created via the cataloging module
- [[29030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29030) Problems introduced by bug 25728
- [[28022]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28022) MARC subfield 9 not honoring visibility
- [[27523]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27523) Adding new itemtype lock image to carredart
- [[27522]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27522) Add a new itemtype info image to carredart
- [[27520]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27520) Adding new itemtype images boardgame, zoom-in, and zoom-out to carredart
- [[28750]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28750) Undefined subroutines in svc/cataloguing/framework (caused by bug 17600)
- [[28543]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28543) Clicking on 'New record' will use default framework
- [[27985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27985) Add option for using a MARC modification template on a single record from the details page

## Circulation

- [[30222]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30222) Auto_renew_digest still sends every day when renewals are not allowed
- [[30114]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30114) Koha offline circulation will always cancel the next hold when issuing item to a patron
- [[30251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30251) With IndependentBranches non-superlibrarians do not get autocomplete list in circulation module
- [[30099]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30099) Error when accessing circulation.pl without patron parameter
- [[29519]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29519) Add option to resolve a return claim at checkin
- [[29889]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29889) Incorrect library check in patron message deletion logic
- [[29820]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29820) Print summary just show 20 items
- [[29495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29495) Issue link is lost in return claims when using 'MarkLostItemsAsReturned'
- [[29637]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29637) AutoSwitchPatron is broken since Bug 26352
- [[29463]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29463) Umlauts in search field get changed into replacement character
- [[29411]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29411) Single result for checkout search by name should redirect to check out tab
- [[25883]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25883) Highlight transfers on checkin screen table
- [[29380]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29380) Auto renewing, batch due date extension tool and checkout note previews are broken
- [[29221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29221) On returns.tt modal displays wrong message when lost items are returned
- [[27949]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27949) Batch printing of article request slips
- [[29093]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29093) Article requests: Checkbox for table of contents
- [[15812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15812) Checkout search with too many results (single character search)  causes poor performance or timeout
- [[27944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27944) Add new stages to the article request process
- [[27945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27945) Limit the number of active article requests per patron category
- [[27947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27947) Add default cancellation reasons to article requests
- [[27279]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27279) "Checked out by" not populated on issuehistory.pl
- [[28774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28774) Warnings from GetIssuingCharge when rental discount is not set
- [[20688]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20688) Add accesskeys for hold confirmation boxes
- [[28810]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28810) Housebound details should be textarea not text inputs
- [[28695]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28695) Add shelving location column to overdue report (overdue.tt)
- [[28850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28850) Clarify wording on AllFinesNeedOverride system preference
- [[10902]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10902) Highlight patrons from logged-in library in patron searches
- [[27948]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27948) Add disclaimer text to article requests feature
- [[20472]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20472) Add digital scan as optional format to Article Requests

## Command-line Utilities

- [[29501]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29501) gather_print_notices.pl does not use SMTP servers
- [[29794]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29794) delete_items.pl missing include
- [[18631]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18631) `cleanup_database.pl` should take an option for modules in action_logs
- [[25429]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25429) `cleanup_database.pl` should remove resolved claims returned after X days
- [[28456]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28456) Add option to use a WHERE statement in membership_expiry.pl cronjob

## Course reserves

- [[14237]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14237) Allow bibs to be added to course without items

## Database

- [[30498]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30498) Enum search_field.type should contain year in kohastructure
- [[30481]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30481) Drop unique constraint deleteditemsstocknumberidx for deleteditems
- [[30128]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30128) language_subtag_registry.description is too short
- [[29605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29605) DB structure may not be synced with kohastructure.sql
- [[28692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28692) Reduce DB action_log table size
- [[28534]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28534) pending_offline_circulations table uses MyISAM engine

## Developer documentation

- [[27375]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27375) Set YAML file settings in .editorconfig

## Documentation

- [[28636]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28636) t:lib::Mocks is missing POD

## Fines and fees

- [[30003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30003) Register entries doubled up if form fails validation on first submission
- [[29457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29457) Fee Cancellation records the wrong manager_id
- [[28389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28389) One should be able to see details for refunds on the register summary page
- [[28346]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28346) Action buttons should have a class per action type
- [[28421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28421) Add tests for Voided Payment and Voided Writeoff.
- [[22435]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22435) Clarify account_offset types by converting them to clear codes
- [[27583]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27583) Clarify how cash management fits together

## Hold requests

- [[30583]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30583) Hold system broken for translated template
- [[30432]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30432) get_items_that_can_fill needs to specify table for biblionumbers
- [[29517]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29517) CanItemBeReserved fetches biblio for agerestriction check if feature not enabled
- [[29103]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29103) reserves.desk_id for desk of waiting hold only updates when printing new hold slip
- [[29338]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29338) Reprinting holds slip with updated expiration date
- [[29969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29969) Cannot update hold list after holds cancelled in bulk
- [[29906]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29906) When changing hold parameters over API (PUT) it forcibly gets to "suspended" state
- [[29704]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29704) Holds reminder emails should allow configuration for a specific number of days
- [[29474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29474) Automatic renewals cronjob is slow on systems with large numbers of reserves
- [[29737]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29737) Cannot suspend holds
- [[28816]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28816) Improve the display of multiple holds during hold process
- [[29407]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29407) Make the pickup locations dropdown JS reusable
- [[29404]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29404) Add infinite scrolling to pickup location dropdowns
- [[29015]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29015) Add option to limit Holds Queue report by shelving location / collection
- [[29356]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29356) Search for pickup library when placing a hold should be truncated in both directions
- [[29355]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29355) Pickup location list limited by RESTdefaultPageSize syspref
- [[29116]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29116) request.pl re-invents Koha::Patron::is_expired accessor
- [[28510]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28510) Skip processing holds queue items from closed libraries when HoldsQueueSkipClosed is enabled
- [[23678]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23678) Cancel holds in bulk
- [[29073]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29073) Hold expiration added to new holds when DefaultHoldExpirationdate turned off
- [[28972]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28972) Add missing foreign key constraints to holds queue table
- [[28261]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28261) Add visual feedback on overridden pickup locations on patron's page
- [[20985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20985) CanBookBeReserved and CanItemBeReserved should check 'On shelf holds allowed' policy

## I18N/L10N

- [[22038]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22038) When exporting account table to excel, decimal is lost
- [[29596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29596) Add Yiddish language
- [[29589]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29589) Translation issue with formatting in MARC overlay rules page
- [[29585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29585) "Go to field" in cataloguing alerts is not translatable
- [[29588]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29588) Yesterday and tomorrow in datepicker don't translate
- [[28898]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28898) Context for translation: term (word) vs. term (semester)

## ILL

- [[30183]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30183) ILL table search filtering broken
- [[28879]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28879) Display of metadata with long label names looks terrible
- [[28340]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28340) Provide improved display of ILL request metadata in notices
- [[27170]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27170) ILL availability should be able to display arbitrary links to related resources
- [[22614]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22614) Request migration from one backend to another should not create new request

## Installation and upgrade (command-line installer)

- [[29813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29813) skeleton.pl missing semicolon

## Installation and upgrade (web-based installer)

- [[29837]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29837) JS error during installer
- [[27823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27823) List upcoming steps during installation process
- [[29158]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29158) Web installer fails to load account_offset_types.sql
- [[28978]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28978) Convert installer CSS to SCSS
- [[27622]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27622) Remove nb-NO installer data
- [[27101]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27101) Remove fr-CA installer data
- [[25078]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25078) Update DB process - wrap each DBRev inside a transaction and better error handling

## Label/patron card printing

- [[26340]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26340) When printing labels from a barcode range, keep zero padding

## Lists

- [[29669]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29669) Uninitialized value warnings when XSLTParse4Display is called
- [[28673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28673) An encoded ampersand missing the ampersand

## MARC Authority data support

- [[29334]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29334) Do not apply framework defaultvalue to existing authority records
- [[29435]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29435) OPAC authority details page broken when AuthDisplayHierarchy is enabled

## MARC Bibliographic data support

- [[18984]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18984) Remove support for NORMARC
- [[26852]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26852) Add missing X11$e and remove relator term subfields from MARC21 headings
- [[27850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27850) Search link for 260 a and c in MARC21 XSLT display

## MARC Bibliographic record staging/import

- [[26402]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26402) Add --framework parameter to commit_file.pl

## Notices

- [[17648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17648) ACCTDETAILS notice doesn't show in the notices tab in staff
- [[29230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29230) Patron's messages not accessible from template notices
- [[29943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29943) Fix typo in notices yaml file
- [[29557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29557) Auto renew notices should handle failed renewal due to patron expiration
- [[29586]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29586) "Hold reminder" notice doesn't show in messaging preferences in new installation
- [[28263]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28263) AUTO_RENEWALS message for 'too_many' is wrong
- [[28153]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28153) Add 'Hold reminder' messaging preference
- [[28813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28813) Fix recording and display of delivery errors for patron notices

## OPAC

- [[30426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30426) suggestion service missing Auth and Output imports
- [[30244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30244) Hide lost items not respected in OPAC results XSLT
- [[29802]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29802) biblionumber in OPACHiddenItems breaks opac lists
- [[30220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30220) Purchase suggestion defaults to first library
- [[30147]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30147) OpacBrowseResults causing error on detail page
- [[29803]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29803) Local cover images don't show in detail page, but only in results
- [[29482]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29482) Terminology: This item belongs to another branch.
- [[29481]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29481) Terminology: Collection code
- [[29778]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29778) Deleting additional_contents leaves entries for additional languages
- [[29604]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29604) Term highlighting adds unwanted pseudo element in the contentblock of OPAC details page
- [[5229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=5229) OPACItemsResultsDisplay preference must be removed
- [[27360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27360) Libraries should be able to pick which branches display on the public 'Libraries' page
- [[24224]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24224) Convert OpacNavBottom system preference to news block
- [[24223]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24223) Convert OpacNav system preference to news block
- [[28537]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28537) Improve HTML generated by OverDrive integration
- [[28901]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28901) showCart incorrectly calculates position if content above navbar
- [[29332]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29332) AdditionalContents displays blocks for every library prior to login
- [[29318]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29318) OverDrive search page should not require edit_borrowers permission
- [[29126]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29126) Accessibility: More corrections to contrast in the OPAC
- [[28101]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28101) Accessibility: OPAC - Breadcrumbs should be more accessible
- [[28180]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28180) Use a lightbox gallery to display the images on the detail pages in OPAC
- [[20277]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20277) Link to host item doesn't work in analytical records if 773$a is present
- [[28831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28831) OPAC XSLT Results: Allow unavailable item grouping on status only for large consortia
- [[29199]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29199) Classes in item availability on OPAC results no longer set correctly
- [[29162]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29162) Change template structure on OPAC library page so that a single library can easily be hidden
- [[29169]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29169) Wrong "daily limit" warning when article request is not available
- [[28821]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28821) OPAC Advanced search: Improve operation of button plus/less
- [[29006]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29006) Make GoogleOpenIDConnect options consistent in the OPAC
- [[28720]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28720) Update the process of adding a checkout note in the OPAC
- [[28933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28933) Hard to parse OPAC-detail subscription information
- [[28536]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28536) Move translatable strings into overdrive.js
- [[28921]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28921) Many [WARN] Argument "" isn't numeric in numeric gt (>) at /home/koha/src/koha-tmpl/opac-tmpl/bootstrap/en/includes/html_helpers.inc line 23.
- [[26302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26302) OPAC XSLT Results: List variable number of itemcallnumbers
- [[28838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28838) SCO impossible errors are hard to target with CSS/JS
- [[26761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26761) Use aria-disabled attribute in OPAC cart for disabled links
- [[28142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28142) Accessibility: OPAC Cart/basket checkboxes are not labelled
- [[15067]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15067) Add additional languages to advanced search language search
- [[27445]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27445) OPAC header tweaks for non-JavaScript users
- [[20310]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20310) Article requests: Use details from the host record when submitting an article request on an analytic record without attached items
- [[28600]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28600) Variable "$patron" is not available
- [[27882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27882) Move external search results links out of page heading

## Packaging

- [[26685]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26685) Move Starman out of debian/control.in and into cpanfile
- [[30252]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30252) lower version of 'Locale::XGettext::TT2' to 0.6

## Patrons

- [[29576]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29576) Add street type to fields which can be copied from guarantor to guarantee
- [[30175]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30175) Digest options not enabled when populating messaging preferences for a selected category during patron entry
- [[30325]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30325) (Bug 30098 follow-up) Broken patron search redirect when one result
- [[30214]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30214) Send WELCOME notice for new patrons added via self registration
- [[27812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27812) Remove the ability to transmit a patron's plain text password over email
- [[30177]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30177) When changing patron categories of existing accounts it should not reset message prefs without warning
- [[28943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28943) Lower the risk of accidental patron deletion by cleanup_database.pl
- [[29341]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29341) If OpacRenewalBranch = opacrenew, pseudonymization process leads to "internal server error" when patrons renew the loans at OPAC
- [[29430]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29430) Table cell click doesn't activate buttons in patron search
- [[28450]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28450) Make Account summary print tables configurable
- [[24406]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24406) Add a span to patron category category type codes in patron search result lists
- [[28867]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28867) Use Bootstrap button menu and modal for adding patrons to lists
- [[27725]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27725) Use JavaScript to set history state during patron search
- [[26544]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26544) Make housebound module show delivery preferences when scheduling
- [[28073]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28073) Make patron modifications auto-open panel for referring patron record
- [[27873]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27873) Make display of patron restrictions, charges, notes, etc. consistent for check out and patron details screens
- [[11879]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11879) Add a new field to patron record: main contact method
- [[15788]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15788) Split borrowers permission into create/edit and delete
- [[28490]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28490) Cannot modify patrons in some categories (e.g. Child category)

## Plugin architecture

- [[29787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29787) Add plugin version to plugin search results
- [[25285]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25285) Wrong message when plugin required Koha version isn't met
- [[29931]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29931) Script plugins-enable.pl should check the cookie status before running plugins
- [[28211]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28211) Replace use of call_recursive() with call()
- [[26352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26352) Add plugin hooks to transform patron barcodes
- [[26351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26351) Add plugin hooks to transform item barcodes
- [[28026]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28026) Add a 'call_recursive' method to Koha::Plugins
- [[29121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29121) Plugins with broken ->install prevent access to the plugins list

## Reports

- [[30532]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30532) guided_reports.pl has a problem
- [[26669]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26669) Last Run column not updated when report is run publicly (via CoverFlow or elsewhere)
- [[30282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30282) Overdues report does not display subtitle and other information
- [[29679]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29679) Reports result menu shows too many dividers
- [[29201]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29201) biblio_framework missing form list of runtime parameters when editing SQL reports
- [[29351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29351) Add missing cn_source parameter to reports parameter menu
- [[28349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28349) Date sorting incorrect in some tables
- [[29186]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29186) Move reports result limit menu into toolbar
- [[28454]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28454) Add Koha version number to database schema link in reports
- [[27747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27747) Add CodeMirror custom syntax highlighting for column placeholders
- [[28731]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28731) Subroutines not explicitly imported in reports svc (opac and staff)

## REST API

- [[30165]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30165) Several q parameters break the filters
- [[29620]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29620) Move the OpenAPI spec to YAML format
- [[29593]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29593) Wrong tag in GET /public/libraries spec
- [[29183]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29183) Add query options documentation
- [[29290]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29290) Add routes to fetch checkouts for a given biblio
- [[29108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29108) Add q parameters to items routes
- [[29107]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29107) item_type should be item_type_id on item response object
- [[27358]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27358) Add GET /public/biblios/:biblio_id/items
- [[28948]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28948) Add a /public counterpart for the libraries REST endpoints
- [[28412]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28412) Add supported authentication methods documentation
- [[28842]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28842) Missing summary for /items/:item_id/pickup_locations
- [[28848]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28848) OpenAPI version should be a string
- [[28585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28585) Cannot search on date fields

## Searching

- [[29374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29374) searchResults explodes if biblio record has been deleted
- [[29138]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29138) LoadSearchHistoryToTheFirstLoggedUser should save 0 instead of "no"
- [[28826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28826) Facet sort order differs between search engines
- [[28830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28830) Add CNI (Control Number Identifier) search index (MARC21)
- [[26860]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26860) Add search limit for records without items
- [[27848]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27848) Elasticsearch - include 245b subtitle and 245p part subfields in the default title index mappings
- [[28526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28526) Impossible to search only zero

## Searching - Elasticsearch

- [[30584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30584) Cannot add field mappings to Elasticsearch configuration
- [[30142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30142) ElasticSearch MARC mappings should not accept whitespaces
- [[28610]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28610) Elasticsearch 7 - hits.total is now an object
- [[29893]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29893) ElasticSearch Config UI deletes mappings
- [[25616]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25616) Uppercase hard coded lower case boolean operators for Elasticsearch
- [[27770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27770) ES: Deprecated aggregation order key [_term] used, replaced by [_key]
- [[29010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29010) Weight input pattern wrong
- [[22690]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22690) Merging records with many items too slow (Elasticsearch)
- [[28736]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28736) Better error message when ES fails to understand the syntax of the search query
- [[28393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28393) Elasticsearch - Add 050a to lc-call-number index mapping (MARC21)
- [[28381]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28381) Elasticsearch - Add 710 and 711 to default mappings for author index (MARC21)
- [[28380]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28380) Elasticsearch - Correct 024aa in mappings (MARC21)
- [[28379]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28379) Elasticsearch - Add 710 to author-name-corporate index (MARC21)
- [[28378]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28378) Elasticsearch - Add 264c to default copydate mappings (MARC21)
- [[28339]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28339) Elasticsearch - Add 8XX to default title-series index mappings (MARC21)
- [[28391]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28391) Elasticsearch - Add 264b to publisher index mapping (MARC21)

## Searching - Zebra

- [[20463]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20463) Create an index for LDR, pos 19 - Multipart resource record level
- [[28337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28337) Add System-control-number index for authorities to MARC21 indexes

## Self checkout

- [[30199]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30199) self checkout login by cardnumber is broken if you input a non-existent cardnumber

## Serials

- [[30035]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30035) Wrong month name in numbering pattern
- [[29790]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29790) Deleting serial items fail without warning
- [[28719]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28719) Cannot edit serials when deleted the selected issues

## SIP2

- [[29936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29936) Add ability to disable hold capture via SIP checkin
- [[30118]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30118) holds_block_checkin behavior is different in Koha and in SIP
- [[28730]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28730) Add option to format AH field (due date)  in SIP checkout response
- [[25464]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25464) Add ability to specify client IP and SIP account used in SIP2 logging
- [[12169]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12169) Improve reliability of sip_shutdown script

## Staff Client

- [[29541]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29541) Patron images can be accessed with just 'catalogue' permission
- [[29500]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29500) Flatpickr accepting original date in the past for futuredate but also other dates in the past
- [[29459]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29459) Replace some missed datetimepickers in circulation templates with Flatpickr
- [[29369]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29369) Use Flatpickr in dateaccessioned cataloging plugin
- [[28236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28236) Selecting database columns for system preferences in standard and dev installs is broken
- [[29242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29242) Flatpickr - Turn autocomplete off
- [[29241]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29241) Flatpickr not displaying date in the past for futuredate
- [[29240]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29240) Flatpickr - error in the console when a date is selected
- [[28356]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28356) Consolidate header catalogue search box code
- [[28872]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28872) AcquisitionLog, NewsLog, NoticesLog should use 1/0 for their values
- [[28819]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28819) Add link to item search from mainpage.pl
- [[28390]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28390) Transaction timestamps should be part of the transaction grouping row instead of repeated for each breakdown row
- [[28677]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28677) Add the word "calendar" to the description for ExpireReservesOnHolidays

## System Administration

- [[30107]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30107) When editing a desk, the currently logged in library is selected
- [[29875]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29875) Update text on MaxReserves system preference to describe functionality.
- [[29180]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29180) System preference RequestOnOpac should be renamed
- [[28859]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28859) Table Settings should control Checked out by field in Checkout history
- [[29200]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29200) Remove Adlibris cover service
- [[29020]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29020) Missing Background jobs link in admin-home
- [[29149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29149) Background job detail view needs more flexibility
- [[27521]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27521) Adding new itemtype headset image for carredart
- [[27505]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27505) Add new itemtype controller image for carredart
- [[28347]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28347) Add DataTables, additional information to patron attribute types management
- [[28563]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28563) Add AllowHoldItemTypeSelection to Hea

## Templates

- [[30525]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30525) Items batch modification broken
- [[29940]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29940) Phase out jquery.cookie.js in the OPAC
- [[30212]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30212) Make Select2 available for ILL backend developers
- [[29989]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29989) Improve headings in MARC staging template
- [[29735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29735) Remove flatpickr instantiations from .js files
- [[29552]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29552) flatpickr quick shortcuts should be 'Disabled' for invalid dates
- [[29688]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29688) Incorrect use of _() in holds.js
- [[29528]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29528) Breadcrumbs on HTML customizations take you to news
- [[29529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29529) Fix \n in hint on Koha to MARC mappings
- [[29478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29478) flatpickr misses quick shortcut to "Today" date
- [[29394]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29394) Remove flatpickr instantiations from .tt files
- [[29270]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29270) Use flatpickr and futuredate on reserve/request.tt
- [[29477]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29477) flatpickr default time should be 23:59 (11:59 pm as well, probably), not 12:00
- [[28376]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28376) Flatpickr introduction for datetime picker
- [[28982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28982) Use Flatpickr on onboarding pages
- [[29229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29229) Use Flatpickr in suggestion search sidebar filter
- [[29301]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29301) Display error with serials search flatpickr when searching Mana
- [[29299]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29299) Reindent serials search template
- [[29278]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29278) write_age function broken by Flatpickr conversion
- [[29231]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29231) Add missing Flatpickr to inventory page
- [[29052]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29052) Make consistent use of spans and div with hint class
- [[28084]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28084) Standardize: Cardnumber, Card number, Card
- [[29233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29233) Correct missed jQueryUI datepicker in serials search sidebar
- [[29232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29232) Clean up obsolete jQueryUI datepicker code from cash register stats template
- [[28963]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28963) Use Flatpickr on calendar page
- [[28988]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28988) Reindent calendar template
- [[29112]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29112) Module navigation sidebars in staff now show bullet points
- [[28441]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28441) Terminology: Reserve notes should be Hold notes
- [[29042]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29042) Improve formatting of entry form in Additional Contents
- [[29041]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29041) Improve specificity of breadcrumbs in Additional Contents
- [[28983]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28983) Use Flatpickr on various pages
- [[28961]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28961) Use Flatpickr on tools pages
- [[28958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28958) Use Flatpickr on serials pages
- [[28949]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28949) Use Flatpickr on reports pages
- [[28945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28945) Use Flatpickr on administration pages
- [[28942]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28942) Use Flatpickr on acquisitions pages
- [[28321]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28321) Use template block for display of items in search results
- [[26949]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26949) Upgrade TinyMCE in the staff interface from 5.0.16 to 5.9.2
- [[28937]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28937) Use Flatpickr on circulation and patron pages
- [[28938]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28938) Correct Flatpickr's default 12hr time formatting
- [[28928]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28928) Minor follow-ups to Bug 28376 - Flatpickr introduction
- [[28843]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28843) Add view and edit buttons to result of MARC record import
- [[28902]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28902) Grey color should be on label for record metadata
- [[12561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12561) Remove non-XSLT views
- [[28394]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28394) Improve style of patron category entry form
- [[26838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26838) Improve styling of checkin message

## Test Suite

- [[19169]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19169) Add a test to detect unneeded 'atomicupdate' files
- [[30203]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30203) Prevent data loss when running Circulation.t without prove
- [[29826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29826) Manage call of Template Plugin Branches GetName() with null or empty branchcode
- [[29779]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29779) selenium/regressions.t fails if Selenium lib is not installed
- [[29565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29565) selenium/regressions.t can fail on slow boxes
- [[29485]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29485) selenium/administration_tasks.t is failing randomly
- [[29273]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29273) Warning not caught in tests for plugins
- [[29368]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29368) Zebra index not correctly mocked from tests
- [[19185]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19185) Web installer and onboarding tool selenium test
- [[29306]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29306) Holds.t: Fix Use of uninitialized value $_ in concatenation (.) or string
- [[19821]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19821) Run tests on a separate database
- [[21670]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21670) t/db_dependent/Plugins.t is failing randomly on Jenkins
- [[28615]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28615) Add a simple way to mock Koha::Logger

## Tools

- [[30402]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30402) Authority import hanging when replacing matched record
- [[29761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29761) Patron batch modification tool - duplicated information on the listing page
- [[29797]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29797) Background job detail for batch delete items not listing the itemnumbers
- [[20076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20076) Overdues email to library for patrons without email should be optional
- [[29747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29747) Cataloguing upload plugin broken
- [[29693]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29693) CodeMirror broken on additional_contents.tt
- [[29113]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29113) New "code" field for additional contents is not useful for the end users
- [[29567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29567) Cataloguing plugins are broken on the batch item mod tool
- [[29387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29387) BatchUpdateBiblio does not handle exception correctly
- [[29469]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29469) Error when approving and rejecting tags
- [[29265]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29265) Can't pick editor to use when adding new news or HTML customization entries
- [[16446]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16446) Allow librarians to add borrowers to patron lists by borrowernumber
- [[29263]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29263) Return to Additional Contents listview after editing such an item
- [[29153]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29153) CodeMirror broken for news and HTML customizations
- [[29254]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29254) Setting wrong dates on additional-contents.pl
- [[28717]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28717) NewsLog doesn't work
- [[24387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24387) Rename News tool
- [[26080]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26080) Use the task queue for the batch delete records tool
- [[29019]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29019) Unable to delete HTML customization
- [[24019]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24019) Patron batch modification based on borrowernumber
- [[28839]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28839) Better texts in stage MARC for import
- [[28758]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28758) Undefined subroutines in C4/ImportBatch.pm (bug 17600)
- [[28718]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28718) Can't delete multiple news items at once
- [[28177]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28177) Add date column and column configuration to uploads
- [[28175]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28175) Usability improvements to uploads page
- [[27883]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27883) Add ability to preserve patron field from being overwritten by import
- [[22544]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22544) Move C4:NewsChannels to Koha namespace
- [[26205]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26205) News changes aren't logged

## translate.koha-community.org

- [[29261]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29261) Translation script breaks members/tables/members_results.tt

## Web services

- [[28238]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28238) Add itemcallnumber to ILS-DI GetAvailability output

## Z39.50 / SRU / OpenSearch Servers

- [[8280]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8280) SRU should be filterable by Koha Item Type


