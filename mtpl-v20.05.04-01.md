
# Release Notes for mtpl-v20.05.04-01

## About

- [[25642]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25642) Technical notes are missing from the release
- [[25592]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25592) Add Devinim to about page

## Acquisitions

- [[26082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26082) Follow up to bug 23463 - need to call Koha::Item store to get itemnumber
- [[26134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26134) Error when adding to basket from new/staged file when using MARCItemFieldsToOrder
- [[21268]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21268) Can't add to basket from staged file if base-level allocated is zero
- [[25266]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25266) Not all vendors are listed in the filters on the late order claims page
- [[24347]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24347) Add a 'search to order' function
- [[25130]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25130) Reason for accepting/rejecting a suggestion is not visible when viewing (not editing)
- [[23593]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23593) Add a shortcut from suggestion details to the bibliographic record in the OPAC
- [[23592]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23592) Add a shortcut from suggestion details to the bibliographic details in the staff client
- [[24161]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24161) Add ability to track the claim dates of later orders
- [[24163]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24163) Add ability to define a CSV profile for late orders export
- [[24162]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24162) Add quantity column to the late orders table
- [[24819]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24819) Add ability for librarians to choose a patron when entering a purchase suggestion
- [[22784]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22784) Add the ability to archive purchase suggestions
- [[22774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22774) Add ability to limit the number of purchase suggestions a patron may submit in a specified time period
- [[23591]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23591) Add a new "Suggestions details" tab on bibliographic record
- [[23596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23596) Add ability to modify the suggestions 'reason' field when receiving the item
- [[25041]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25041) Links to 'pending' #ASKED tab in suggestions.pl is broken
- [[24158]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24158) Add ability to receive items in multiple currencies
- [[23590]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23590) Add the ability to change the manager of a suggestion and notify the new manager
- [[24276]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24276) Add functionality to apply defaults from the ACQ framework for mandatory fields when adding records from external sources
- [[24672]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24672) Error on receiving orders when there is an order with a deleted record
- [[23926]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23926) In EDI Order limit GIR segment to five pieces of information
- [[11161]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11161) Relabel 'child fund' to 'sub fund'
- [[17611]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17611) Searching for orders uses misleading column name "Pending order"
- [[24569]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24569) Cannot add to basket if it is the only action
- [[23031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23031) Restore 'Add to basket' as immediately accessible option on vendor search page
- [[23594]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23594) Add ability to batch modify itemtypes from the suggestions page
- [[22868]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22868) Circulation staff with suggestions_manage can have access to acquisition data
- [[12502]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12502) Add columns for note, order number and ISBN to late orders page
- [[16784]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16784) Add table configuration for the suggestions table
- [[14973]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14973) Add an alert during purchase suggestion submissions to warn the user when an existing biblio appears to satisfy the request
- [[14963]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14963) Add the ability to suggest purchase from existing titles

## Architecture, internals, and plumbing

- [[26322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26322) REST API plugin authorization is not checked anymore
- [[26251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26251) Remove unused routines from svc/split_callnumbers
- [[23632]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23632) Remove C4::Logs::GetLogs
- [[24663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24663) OPACPublic must be tested for all opac scripts
- [[26133]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26133) Unneeded calls in detail.pl can be removed
- [[26141]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26141) Duplicated code in search.pl
- [[25998]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25998) Add 'library' relation to Koha::Account::Line
- [[25723]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25723) Improve efficiency of holiday calculation
- [[25511]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25511) Add --force option to update_dbix_class_files.pl
- [[23070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23070) Use Koha::Hold in C4::Reserves::RevertWaitingStatus
- [[25964]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25964) Data loss possible when items are modified
- [[21395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21395) Make perlcritic happy
- [[24986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24986) Maximum row size reached soon for borrowers and deletedborrowers
- [[25070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25070) Include files to display address and contact must be refactored
- [[25608]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25608) (regression) Inventory is broken
- [[20116]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20116) Improve performance by caching the language list
- [[20370]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20370) Misleading comment for bcrypt - #encrypt it; Instead it should be #hash it
- [[24255]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24255) Add totals methods Koha::Account::Lines
- [[24252]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24252) Add credits, debits, credit_offsets and debit_offsets relationships to Koha::Account::Line
- [[24368]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24368) Koha::Libraries->pickup_locations needs refactoring/ratifying
- [[24561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24561) Add a datatables API wrapper
- [[25423]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25423) Methods update and empty from Koha::Objects are not class methods
- [[23185]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23185) Koha::Objects supports passing through 'update' which means we can side step 'set' + 'store'
- [[20443]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20443) Move C4::Members::Attributes to Koha namespace
- [[18308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18308) Default value of minPasswordLength should be increased
- [[25107]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25107) Remove double passing of $server variable to maybe_add in C4::SIP::Sip::MsgType
- [[25297]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25297) Consistent return value in K::A::Order->current_item_level_holds
- [[25303]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25303) Koha::Objects->delete should not skip overridden object class ->delete
- [[25131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25131) Web installer broken if enable_plugin is set
- [[25296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25296) Add a way to force an empty Koha::Objects resultset
- [[21294]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21294) Add identification of boolean fields in the database
- [[24815]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24815) Koha::Cash::Register relations should return sets not undef
- [[25045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25045) Add a way to restrict anonymous access to public routes (OpacPublic behaviour)
- [[25172]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25172) Koha::Logger init is failing silently
- [[23463]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23463) Move C4::Items CRUD subroutines to Koha::Item
- [[24715]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24715) Cache repeatable subfield in TransformKohaToMarc
- [[25109]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25109) Add execution locking to Koha::Script
- [[20728]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20728) Remove subroutines GetLastOrder*
- [[25044]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25044) No need to define koha_object[s]_class for standard object class names
- [[25018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25018) Jenkins is not running the test with $ENV{_} eq 'prove'
- [[22685]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22685) Koha::Acquisition::Bookseller methods should return Koha::Objects using the DBIx::Class relationships
- [[24455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24455) Add ability to apply Koha formatting to dates from Javascript
- [[24754]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24754) UserEnv not set for ISLDI requests
- [[21800]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21800) TransformKohaToMarc should respect non-repeatability of item subfields
- [[21503]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21503) Update AuthorisedValues.pm to fall back to code if description doesn't exist
- [[24837]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24837) selectbranchprinter needs to be renamed
- [[22589]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22589) Remove sub C4::Overdues::BorType
- [[24468]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24468) C4::Reserves::_get_itype is no longer used
- [[22098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22098) The stocknumberAV cataloguing plugin should be updated to use Koha::Objects
- [[24759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24759) OpacRenewalBranch code should be a Koha::Item method
- [[24052]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24052) Koha::XSLT housekeeping for bug 23290 (follow-up)
- [[24463]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24463) Consistent accessor-relationship naming for basket_group in Basket.pm
- [[24830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24830) dbic_merge_prefetch is not handling recursive cases correctly
- [[24726]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24726) overdue_notices.pl should use Koha::Library->inbound_email_address
- [[24723]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24723) EmailPurchaseSuggestions should use Koha::Library->inbound_email_address when set to 'BranchEmailAddress'
- [[24721]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24721) emailLibrarianWhenHoldIsPlaced should use Koha::Library->inbound_email_address
- [[22823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22823) Koha::Library needs a method for obtaining the inbound email address
- [[24722]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24722) reserves.priority must be NOT NULL
- [[17845]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17845) Printers related code should be removed
- [[24545]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24545) Replace Franklin Street by gnu.org/licenses in copyright
- [[24066]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24066) Koha::Patron->has_permission has no POD
- [[24573]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24573) Catmandu::Store::ElasticSearch and Catmandu::MARC are missing from cpanfile
- [[22529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22529) /svc/members/search relies on quirks of haspermission
- [[24741]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24741) Recent creation of unique index on library_groups erroneously removes rows
- [[24735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24735) Remove QueryParser-related code
- [[21746]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21746) Remove NO_LIBRARY_SET
- [[23290]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23290) XSLT system preferences allow administrators to exploit XML and XSLT vulnerabilities
- [[22522]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22522) API authentication breaks with updated Mojolicious version
- [[24356]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24356) objects.search prefetch
- [[24693]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24693) GD is declared as an optional dependency but Koha dies without it
- [[24103]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24103) Add option to dump built search query to templates
- [[24367]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24367) With strict enabled, Search.t is too verbose
- [[24647]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24647) PDF::API2::Simple is declared as a required dependency but it is not used
- [[23084]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23084) Replace grep {^$var$} with grep {$var eq $_}
- [[20882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20882) URI column in the items table is limited to 255 characters
- [[19735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19735) Move Perl deps definitions into a cpanfile
- [[14711]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14711) C4::Reserves::AddReserves should take a hashref in parameters
- [[24602]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24602) The fallback value for onshelfholds should be 0
- [[24595]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24595) Warnings displayed by Circulation.t
- [[24529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24529) Uninitialised value warnings in C4::Reserves
- [[18936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18936) Move issuingrules into circulation_rules
- [[24440]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24440) Add ->current_item_level_holds to Koha::Acquisition::Order
- [[21674]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21674) Data integrity not enforced for library groups
- [[24467]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24467) *_count methods should be avoided
- [[24448]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24448) Add Koha::Biblio->subscriptions_count
- [[24149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24149) Add new Koha::Statistic[s] classes
- [[24459]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24459) Overloaded ->to_api needs to pass $params through
- [[24457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24457) K::A::Basket->to_api is not passing the parameters to the parent class implementation
- [[24435]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24435) Add Koha::Biblio->items_count
- [[24430]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24430) Remove C4::Biblio::CountBiblioInOrders
- [[24419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24419) Add Koha::Suggestion->suggester accessor
- [[24418]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24418) Add Koha::Biblio->suggestions
- [[24018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24018) No need to die "Not logged in"
- [[24263]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24263) borrowers.relationship should not contain an empty string
- [[21684]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21684) Koha::Object[s]->delete methods must behave identically as the corresponding DBIx::Class ones
- [[24150]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24150) Add missing Koha::Old::*[s] classes
- [[24089]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24089) Upgrade jQuery Validate plugin in the staff client
- [[24217]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24217) use strict for all modules
- [[21761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21761) Koha::Object supports passing through 'update' which means we can side step 'set' + 'store'

## Authentication

- [[21190]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21190) Add logging of successful/unsuccessful login attempts

## Bywater Only

- NOT IN BUGZILLA - Update GitHub Actions
- NOT IN BUGZILLA - Add .github & .env to list of directories to skip for check_makefile.t
- NOT IN BUGZILLA - Fixing po files for 20.05.01
- NOT IN BUGZILLA - Translation fixes
- NOT IN BUGZILLA - Teams fixes
- NOT IN BUGZILLA - Clean up 'John Doe'
- NOT IN BUGZILLA - Add 20.11 release team
- NOT IN BUGZILLA - Update Contributors for 20.05
- NOT IN BUGZILLA - Koha 19.12 - Dobbie is a free elf...

## Cataloging

- [[16314]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16314) Show upload link for upload plugin in basic MARC editor
- [[26289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26289) Deleting biblio in labeled MARC view doesn't work
- [[25189]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25189) AutoCreateAuthorities can repeatedly generate authority records when using Default linker
- [[24185]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24185) 'If all unavailable' state for 'on shelf holds' makes holds page very slow if there's a lot of items
- [[24027]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24027) Adding multiple items is slow
- [[25248]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25248) Delete All Items should redirect to detail.pl, not additem.pl
- [[7947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7947) 440/490 Koha Mapping
- [[17268]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17268) Advanced cataloging editor - rancor - macros are lost when browser storage cleared
- [[19313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19313) Typo in UNIMARC field 130 plugin
- [[23349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23349) Add batch operations to staff interface catalog search results
- [[13775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13775) Set main headings to mandatory in authority frameworks
- [[23777]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23777) Text converted to html entity codes in cataloguing edit form
- [[8643]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8643) Add ability to mark some MARC tags and subfields as important and alert on saving the record if they are found to be empty
- [[15850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15850) Correct eslint errors in cataloging.js
- [[24305]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24305) Batch Item modification via item number in reports does not work with CONCAT in report
- [[3426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=3426) Add support for multiple tags to the itemcallnumber system preference

## Circulation

- [[25958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25958) Allow LongOverdue cron to exclude specified lost values
- [[25907]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25907) When cancelling a waiting hold on returns.pl, looks for new hold to fill without rescanning barcode
- [[25717]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25717) Improve messages for automatic renewal errors
- [[25851]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25851) 19.11 upgrade creates holdallowed rule with empty value
- [[25440]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25440) Remove undef and CGI warnings and fix template variables list in circulation rules
- [[25807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25807) Version 3.008 of Template breaks smart-rules display
- [[25232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25232) Add ability to skip trapping items with a given notforloan value
- [[25699]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25699) Add edition information to Holds to pull report
- [[25658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25658) Print icon sometimes obscures patron barcode
- [[24846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24846) Add a tool to enable bulk edit of due dates
- [[24413]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24413) MarkLostItemsAsReturned functionality does not lift restrictions caused by long overdues
- [[13881]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13881) Add ability to defined circulation desks
- [[25188]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25188) Make circulation notes more prominent on the patron details tab
- [[25184]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25184) Items with a negative notforloan status should not be captured for holds
- [[24298]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24298) Record if a transfer was triggered by 'return to homebranch'
- [[24620]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24620) Existing transfers not closed when hold is set to waiting
- [[24840]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24840) Datetime issues in automatic_renewals / CanBookBeReserved
- [[24474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24474) Lost items that are checked out are always returned, even when attempting to renew them
- [[21443]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21443) Add ability to exclude holidays when calculating rentals fees by time period
- [[24297]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24297) Record if a transfer was triggered 'manually'
- [[24436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24436) Record if a transfer was triggered by a 'hold'
- [[24299]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24299) Record if a transfer was triggered by 'rotating collections'
- [[23051]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23051) Add ability to optionally renew fine accruing items when all fines on item are paid off
- [[24669]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24669) Editing circulation rule breaks holds when total holds unlimited
- [[24585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24585) Add 'Managed on' and 'Suggested on' columns to suggestions tab in patron account in staff
- [[24296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24296) Move stock rotation transfer triggers from `comments` to `reason`
- [[24287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24287) Add ability to record what triggered a given transfer
- [[18355]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18355) Add 'permanent location' alongside 'shelving location' when located on cart
- [[23233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23233) AllowItemsOnHoldCheckout is misnamed and should only work for for SIP-based checkouts

## Command-line Utilities

- [[26175]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26175) Remove warn if undefined barcode in misc/export_records.pl
- [[23696]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23696) build_oai_sets.pl should take biblios from deletedbiblio_metadata too
- [[25955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25955) compare_es_to_db.pl broken by drop of Catmandu dependency
- [[25752]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25752) Current directory not kept when using koha-shell
- [[21591]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21591) Data inconsistencies - Item types and biblio level
- [[25538]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25538) koha-shell should pass --login to sudo if no command
- [[25482]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25482) Wrong permissions in spec break Plack on Debian 10
- [[23571]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23571) Add measures to prevent concurrent execution of fines.pl
- [[23871]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23871) Add check for 'title exists' to `search_for_data_inconsistencies.pl`
- [[24883]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24883) Add `misc/load_yaml.pl` utility script to allow manual loading of yaml data files
- [[15214]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15214) Add logging of authority updates to bulkmarcimport
- [[18414]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18414) Add ability to pass a file of borrowernumbers for deletion to delete_patrons.pl
- [[24651]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24651) Add --maxdays option to the `fines.pl` cronjob to reduce the chance of re-processing very old, already capped, fines.
- [[24340]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24340) Add ability to disable SIP using koha-sip
- [[24526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24526) Add verbose and test modes to the `automatic_renewals.pl` cronjob
- [[21177]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21177) Add ability to run misc/devel/update_dbic_class_files.pl without passing parameters by defaulting to koha-conf.xml
- [[21466]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21466) Data inconsistencies - koha fields linked to AV cat values must have a corresponding authorised value

## Course reserves

- [[25444]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25444) Course reserve settings are not saved on edit
- [[22630]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22630) Add ability to change the homebranch in course reserves
- [[22970]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22970) Add ability to change homebranch in batch add course reserves
- [[24772]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24772) Deactivating course reserves before deleting the same course empties/resets course reserve values in the items
- [[23727]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23727) Editing course reserve items is broken
- [[15377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15377) Add ability to remove 'checked out' items from course reserves
- [[24343]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24343) Show subtitle, number and parts in course reserves list of titles in staff client

## Database

- [[24379]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24379) Patron login attempts happen to be NULL instead of 0
- [[8132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8132) Batch delete tool deletes items with holds on them
- [[13518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13518) Table borrower_modifications is missing FK and not deleted with the patron
- [[22887]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22887) authorised_values is missing a unique constraint on category + authorised_value
- [[25152]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25152) subscription.closed is a boolean and must be tinyint(1)
- [[18177]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18177) Remove unused columns in aqbooksellers
- [[22987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22987) Add biblioimages.timestamp
- [[22273]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22273) Column article_requests.created_on should not be updated
- [[24640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24640) quotes.timestamp should default to NULL
- [[24289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24289) Deleting branch will not delete entry in special or repeatable holidays

## Developer documentation

- [[24774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24774) Specify 2 space indentation for JSON files in .editorconfig

## Documentation

- [[21633]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21633) Did finesMode = test ever send email?

## Fines and fees

- [[26189]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26189) Table options on points of sale misaligned
- [[26023]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26023) Incorrect permissions handling for cashup actions on the library level registers summary page
- [[26161]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26161) Confirm and cancel buttons should be underneath the right hand form on the POS page
- [[8338]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8338) Add ability to remove fines with dropbox mode
- [[24380]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24380) Add option to recalculate fines upon a backdated return distinctly from `CalculateFinesOnReturn`
- [[24080]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24080) Add a 'payout' process to accounts
- [[23442]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23442) Add a 'refund' process to accounts
- [[25389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25389) Inconsistent naming of account_credit_type for lost and returned items
- [[25119]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25119) When paying or writing off a single fee, the account type doesn't display correctly
- [[25138]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25138) Terminology: Point of sale should use library instead of branch
- [[24820]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24820) The cashup workflow should use the static 'date' field rather than the transient 'timestamp' field in accountlines
- [[25139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25139) POS explodes in error when trying to display older transactions
- [[23355]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23355) Add a 'cashup' process to accounts
- [[24492]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24492) Add a 'library cashup' workflow to the point of sale system
- [[24828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24828) Add cash register support to SIP2
- [[24951]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24951) Payout modal confirm button should have an ID
- [[24952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24952) Refund modal confirm button should have an ID
- [[24818]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24818) Accountline creation dates should be datetimes
- [[24495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24495) Reword change collection feature
- [[24812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24812) Add permission for 'discount' process
- [[23354]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23354) Add a 'Point of sale' screen to allow anonymous payments
- [[24790]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24790) POS missing from the 'More' dropdown
- [[24082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24082) Add a 'refund' option to anonymous payments
- [[24775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24775) Payment submit button on POS page should have an ID
- [[24479]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24479) POS doesn't follow CurrencyFormat
- [[24081]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24081) Add a 'discount' process to accounts
- [[17702]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17702) Create configuration for account credit types
- [[14898]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14898) Add 'Save and pay' button to use after adding a manual invoice
- [[24532]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24532) Some account types are converted to debits when they shouldn't be
- [[6508]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=6508) Show indication of existing 'Charges' on tab of the same name
- [[24592]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24592) Clarify LOST_RETURN process by using FOUND over RETURNED
- [[24525]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24525) Hide SIP payment types from the Point of Sale page
- [[24490]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24490) Clarify wording and function of Purchase Items link on POS
- [[24339]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24339) SIP codes are missing from the default payment_types on installation
- [[24478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24478) Make it possible to deactivate point of sale
- [[24477]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24477) No permissions check for POS feature
- [[24481]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24481) Incorrect permission in admin/cash_registers.pl

## Hold requests

- [[24683]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24683) Holds on biblios with different item types: rules for holds allowed are not applied correctly if any item type is available
- [[23820]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23820) Club hold pickup locations should be able to default to patron's home library
- [[25786]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25786) Holds Queue building may target the wrong item for item level requests that match holds queue priority
- [[25556]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25556) Holds blocked when empty holdallowed value present in circulation_rules
- [[25516]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25516) Item/pickup_locations wantarray removed, so dies on Perl >=5.24 where "autoderef" feature absent
- [[25421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25421) Make Koha::Item and Koha::Biblio ->pickup_locations return an arrayref
- [[16547]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16547) Can't place item level hold directly from search results screen
- [[24953]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24953) Minor corrections to hold ratios report sidebar
- [[24907]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24907) Optionally exclude suspended holds from holds ratio report
- [[19718]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19718) Create message for patrons with multiple holds on the same item
- [[24350]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24350) Can't place holds
- [[22284]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22284) Add ability to define groups of locations for hold pickup

## I18N/L10N

- [[25626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25626) Translation issues with OPAC problem reports (status and 'sent to')
- [[26158]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26158) Z3950 search button broken for translations
- [[25346]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25346) Only show warn about existing directory on installing translations when verbose is used
- [[25501]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25501) Encoding issues in the translation process
- [[25305]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25305) Double UTF-8 encoding on translation files
- [[24808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24808) Untranslatable strings in results.js
- [[24871]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24871) Add new *-installer-*.po translation files
- [[24662]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24662) Remove global variables MSG_* from datatables.inc
- [[24583]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24583) Rewrite mandatory installation files to YAML
- [[24594]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24594) Rewrite MARC21 mandatory data to YAML
- [[24593]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24593) Rewrite MARC21 optional data to YAML
- [[24584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24584) Rewrite optional installation files to YAML
- [[24262]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24262) Translate installer data in YAML format
- [[13897]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13897) Use YAML files for installer data
- [[24664]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24664) Add missing *-messages-js.po
- [[24661]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24661) Inclusion of locale-related javascript files is broken
- [[24211]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24211) Compress/uncompress translation files
- [[24648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24648) Contextualization of past tense "Created"
- [[24365]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24365) Using strict from TmplTokenizer.pm broke the translator script

## ILL

- [[26114]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26114) ILL should mark status=RET only if a return happened
- [[23173]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23173) ILL should be able to search third party sources prior to request creation
- [[23112]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23112) Add circulation process to inter-library loans

## Installation and upgrade (command-line installer)

- [[26265]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26265) Makefile.PL is missing pos directory
- [[25284]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25284) Can't open /var/log/koha/kohadev/opac-error.log (Permission denied)
- [[24696]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24696) We should output completion times in the updatedatabase output.
- [[24904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24904) New YAML files for installer are slow to insert

## Installation and upgrade (web-based installer)

- [[25129]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25129) Update German (de-DE) web installer files for 20.05
- [[25695]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25695) Missing logging of $@ in onboarding.pl after eval block
- [[24897]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24897) Remove es-ES installer data
- [[24131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24131) Improved formatting for output of updatedatabase
- [[24707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24707) Remove AMICUS from default fr-CA z39.50 servers
- [[24708]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24708) Update Z39.50 server attribute in fr-CA installation file
- [[22655]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22655) Add setup of a hold rule to the onboarding tool
- [[24137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24137) Marc21 bibliographic fails to install for ru-Ru and uk-UA

## Label/patron card printing

- [[7468]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7468) Add label to batch by barcode range

## Lists

- [[20754]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20754) Db revision to remove double accepted list shares

## MARC Bibliographic data support

- [[23119]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23119) MARC21 added title 246, 730 subfield i should display before subfield a
- [[25410]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25410) MARC21 out of sync intranet/opac subfield descriptions
- [[25011]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25011) Improve display of Production credits (MARC21 508) in OPAC and staff
- [[17831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17831) Remove non-existing bibliosubject.subject mapping from frameworks

## Notices

- [[25639]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25639) Add search queries to HTML so queries can be retrieved via JS
- [[24591]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24591) Add developer script to preview a letter
- [[25629]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25629) Fix capitalization in sample notices
- [[25097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25097) Add option to message_queue to allow for only specific sending notices
- [[24378]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24378) Change wording on AUTO_RENEWALS notice in updatedatabase
- [[23787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23787) Add AUTO_RENEWALS in sample_notices.sql
- [[10269]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10269) Add a way to utilise a specific replyto email address for some notices
- [[24588]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24588) Set `Mailer-X` and `MessageID` mail headers to reduce the likelihood of Koha mail being marked as spam
- [[19014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19014) Patrons should not get an 'on_reserve' notification if the due date is far into the future
- [[23673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23673) Separate time sent from time created in message_queue table

## OPAC

- [[26127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26127) When reporting an Error from the OPAC, the URL does not display
- [[26008]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26008) Remove the use of jquery.checkboxes plugin from OPAC cart
- [[26179]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26179) Remove redundant import of Google font
- [[26037]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26037) openlibrary.org is hit on every Koha requests
- [[26094]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26094) "Suggest for Purchase" button missing unique CSS class
- [[26070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26070) Google Transliterate API has been deprecated
- [[23797]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23797) Convert OpacLoginInstructions system preference to news block
- [[23796]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23796) Convert OpacCustomSearch system preference to news block
- [[23795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23795) Convert OpacCredits system preference to news block
- [[26005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26005) OPAC cart display fails with error
- [[24473]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24473) Syndetics content should be $raw filtered on opac-detail.tt
- [[18911]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18911) Option to set preferred language in OPAC
- [[22807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22807) Accessibility: Add 'Skip to main content' link
- [[25402]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25402) Put OPAC cart download options into dropdown menu
- [[24405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24405) Links in facets are styled differently than other links on the results page in OPAC
- [[20783]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20783) Cannot embed some YouTube videos due to 403 errors
- [[23794]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23794) Convert OpacMainUserBlock system preference to news block
- [[13547]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13547) Item field 'Materials specified' would be useful to see in OPAC
- [[25350]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25350) Load Emoji picker assets more efficiently
- [[13388]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13388) Add library pages to the OPAC
- [[24980]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24980) Date formatting from JS - use timezone only with dates with offset
- [[25271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25271) Add floating toolbar to OPAC cart
- [[25166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25166) Add aria-hidden = "true" to Font Awesome icons in the OPAC
- [[25294]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25294) Don't show deletion button if user can't delete suggestions
- [[25110]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25110) Allow patrons to add star ratings to titles on their summary/checkout page
- [[25281]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25281) Use modal confirmation when deleting a list in the OPAC
- [[25280]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25280) Use modal confirmation when removing share from a list in the OPAC
- [[25234]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25234) Update OPAC search results pagination with aria labels
- [[24913]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24913) Add option to require users to enter email address twice during self-registration.
- [[25086]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25086) OPAC Self Registration - Field 'changed_fields' doesn't have a default value
- [[25136]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25136) PatronSelfRegistrationLibraryList controls both self-reg and self-modification
- [[25137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25137) PatronSelfRegistrationLibraryList results in empty branch list on opac-memberentry.pl
- [[4461]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=4461) Add a context-sensitive report a problem process
- [[24699]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24699) Split items.uri on OPAC detail page
- [[25004]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25004) Search results place hold button not enabled when checking result checkboxes on opac-search.pl
- [[25024]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25024) OPAC incorrectly marks branch as invalid pickup location when similarly named branch is blocked
- [[24996]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24996) Unwanted CSS change unhides OPAC results sorting button
- [[14715]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14715) Results per page setting for catalog search in staff client and OPAC
- [[24745]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24745) OPAC news block plugin should evaluate as false if there are no items
- [[24854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24854) Remove IDreamBooks integration
- [[24701]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24701) Add column configuration to course reserves items table in the OPAC
- [[22821]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22821) Use reply-to address for item notes notifications if available to avoid being flagged as spam
- [[23547]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23547) Add column configuration to course reserves table in the OPAC
- [[24746]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24746) Duplicate id in opacheader markup
- [[13327]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13327) OPACPopupAuthorsSearch doesn't work with XSLT views
- [[22880]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22880) Convert opacheader system preference to news block
- [[24706]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24706) Toolbar not rendered correctly when a list is empty
- [[23482]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23482) BakerTaylor images broken on OPAC lists
- [[24249]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24249) OPAC lists page should require login for login-dependent operations
- [[7611]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7611) Show the NOT_LOAN authorised values for item status in XSLT OPAC search results
- [[24530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24530) Show the number of title notes in the tab label on the OPAC detail page
- [[23915]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23915) Replace OPAC list sort menu with Bootstrap menu button
- [[13121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13121) Move search results "action" links ("Place hold," "Add tag," etc) into include file
- [[24345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24345) Fix process of suggesting purchase of existing title for non-logged-in users
- [[24336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24336) Ask for confirmation before deleting a suggestion in the OPAC
- [[24344]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24344) Modify OPAC link to suggest existing record for purchase
- [[24206]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24206) Change URLs for default options in OPACSearchForTitleIn
- [[24371]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24371) OPAC 'Showing only available items/Show all items' is double encoded
- [[23913]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23913) Use a single menu to sort lists in the OPAC

## Packaging

- [[25889]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25889) Increase performance of debian/list-deps script
- [[25828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25828) Update cpanfile for 20.05 release cycle
- [[25591]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25591) Update list-deps for Debian 10 and Ubuntu 20.04
- [[25068]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25068) koha-common build error caused by missing /etc/searchengine
- [[25527]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25527) Package does not build because of missing log4perl.conf

## Patrons

- [[26125]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26125) In 'Patron search' tab link should lead to patron details instead of checkout screen
- [[25322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25322) Adding a guarantor with no relationship defaults to first available relationship name
- [[25858]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25858) Borrower permissions are broken by update from bug 22868
- [[10910]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10910) Add a warn when deleting a patron with pending suggestions
- [[20847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20847) Add main address, phone, and mobile fields to the Batch patron modification tool
- [[23495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23495) Show SMS provider on details tab in patron account in staff
- [[5161]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=5161) Patron attributes clearing if duplicate warning
- [[14229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14229) Link to accounting tab from fines column in patron search results
- [[22534]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22534) Add ability to choose which fields are copied from guarantor to guarantee
- [[24964]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24964) Do not filter patrons AFTER they have been fetched from the DB (when searching with permissions)
- [[24988]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24988) autorenew_checkouts should default to yes
- [[24962]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24962) Don't show floating toolbar when duplicate patron record was detected
- [[24476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24476) Allow patrons to opt-out of auto-renewal
- [[23808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23808) Creating Child Guarantee doesn't populate Guarantor Information
- [[3137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=3137) Allow to collapse areas of the patron add form by default
- [[24008]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24008) Attempting to delete a patron with outstanding credits will warn, but not block the deletion

## Plugin architecture

- [[25953]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25953) Add ID to installed plugins table to ease styling and DOM mods
- [[25961]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25961) Add hooks for plugins to inject variables to XSLT
- [[23975]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23975) Add ability to search and install plugins from GitHub
- [[24183]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24183) Introduce `before_send_messages` hook

## Reports

- [[25605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25605) Exporting report as a tab delimited file can produce a lot of warnings
- [[24976]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24976) Guided report - "Save" button on last step is misleading
- [[24959]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24959) Fix id/label pairs in saved reports table

## REST API

- [[25774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25774) REST API searches don't handle correctly utf8 characters
- [[25411]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25411) Plugin routes cannot have anonymous access
- [[25502]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25502) /advanced_editor/macros doesn't follow coding guidelines
- [[25493]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25493) Koha::Logger is not suitable for using as Mojo::Log
- [[25279]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25279) Make the cities list use the API
- [[25048]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25048) Successful resource deletion should return 204
- [[25032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25032) Generic unhandled exception handling
- [[24700]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24700) Improve Mojo startup speed for REST APIs
- [[24461]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24461) Add to_api_mapping to Koha::Acquisition::BasketGroup
- [[24918]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24918) Wrong attribute mappings in Koha::Acquisition::Basket
- [[24464]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24464) Add K::A::Basket->creator
- [[22615]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22615) Add routes for /ill_backends
- [[24615]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24615) Add support for ordering by related object columns in the REST API
- [[24502]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24502) Add a query language and param (q=) to the API
- [[24680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24680) Hold modification endpoints don't always work properly
- [[24611]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24611) Wrong budget_id query parameter in /acquisitions/orders
- [[24462]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24462) Adjust K::A::Invoice API mapping to voted RFC
- [[24554]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24554) Only embed relations from Koha::Biblio in to_api
- [[24528]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24528) Add a syntax for specifying counts on x-koha-embed
- [[24432]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24432) order_by broken for date columns
- [[24366]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24366) Merging biblioitems should happen in Koha::Biblio->to_api
- [[18731]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18731) Add routes for acquisition orders
- [[24302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24302) Add a way to specify nested objects to embed in OpenAPI
- [[24321]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24321) Make objects.search use mappings from Koha::Object(s)

## Searching

- [[23081]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23081) Make items.issues and deleteditems.issues default to 0 instead of null
- [[24219]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24219) Elasticsearch needs to remember sort preference when returning to result list
- [[18433]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18433) Allow to select results to export in item search

## Searching - Elasticsearch

- [[26309]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26309) Elasticsearch cxn_pool must be configurable (again)
- [[25872]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25872) Advanced search on OPAC with limiter but no search term fails when re-sorted
- [[24823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24823) Drop Catmandu dependency
- [[25325]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25325) ElasticSearch mapping export lacks staff_client/opac fields
- [[23204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23204) Add script for exporting Elasticsearch mappings to YAML
- [[14567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14567) Add an elasticsearch driven browse interface to the OPAC
- [[22831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22831) Add a maintenance script for checking DB vs index counts

## Searching - Zebra

- [[25149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25149) The Zebra language option for Greek should be 'el', not 'gr'

## Self checkout

- [[26131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26131) console errors when attempting to open SCO related system preferences
- [[25349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25349) Enter in the username field submits the login, instead of moving focus to the password field
- [[25147]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25147) AllowSelfCheckReturns is in the wrong system preference section
- [[21250]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21250) Auto-self-checkout not fully compatible with multi-branch library setup

## Serials

- [[16962]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16962) Remove the use of "onclick" from serial collection template
- [[21901]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21901) Foreign keys are missing on the serials and subscriptions tables
- [[7046]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7046) subscription renewal period should be a pull down
- [[23888]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23888) Incorrect vendor id in subscription creation causes internal server error
- [[17674]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17674) Allow UI to delete serials issues in batch
- [[7047]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7047) Renewing serials note not visible

## SIP2

- [[25348]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25348) Add support for circulation status 12 ( lost )
- [[25347]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25347) Add support for circulation status 11 ( claimed returned )
- [[25344]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25344) Add support for circulation status 10 ( item in transit )
- [[25992]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25992) SIP2 server doesn't start - Undefined subroutine set_logger
- [[15253]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15253) Add Koha::Logger based logging for SIP2
- [[20816]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20816) Add ability to send custom field(s) containing patron information in SIP patron responses
- [[24629]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24629) SIP2 logs garbage

## Staff Client

- [[26007]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26007) Warning/reminder for changes to Koha to MARC mapping
- [[26182]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26182) Clearly pair UpdateItemWhenLostFromHoldList and CanMarkHoldsToPullAsLost system preferences
- [[26084]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26084) ConsiderOnSiteCheckoutsAsNormalCheckouts description is unclear
- [[25804]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25804) Remove HTML from title tag of bibliographic detail page
- [[12093]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12093) Add CSS classes to item statuses in detail view
- [[24697]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24697) Split items.uri on staff detail view
- [[17374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17374) Make use of fields from syspref 'DefaultPatronSearchFields' in patron search fields dropdown
- [[24540]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24540) Unexpected behaviour on 'enter' in point of sale payment fields
- [[24617]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24617) Add title notes count in staff detail (following 24530)
- [[24646]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24646) RoundFinesAtPayment is not a self check in preference
- [[24482]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24482) Purchase Items broken by costs containing a comma

## System Administration

- [[25945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25945) Description of AuthoritySeparator is misleading
- [[25919]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25919) Desks link is available in left side menu even if UseCirculationDesks is disabled
- [[25709]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25709) Rename systempreference from NotesBlacklist to NotesToHide
- [[25651]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25651) Modifying an authorised value make it disappear
- [[25601]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25601) Error when unsetting default checkout, hold and return policy for a specific library
- [[17355]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17355) Authorised value categories cannot be deleted
- [[15668]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15668) Add column configuration to the items table in staff detail pages
- [[5614]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=5614) Add sections/headings to Patron system preferences tab
- [[4944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=4944) Create separate noItemTypeImages preferences for OPAC and staff client
- [[20648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20648) "Display in check-out" renamed to "Display in patron's brief information" on patron attributes configuration page
- [[24475]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24475) Reword FinesMode system preference
- [[20415]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20415) Remove UseKohaPlugins system preference
- [[20399]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20399) Remove "did you mean" for the staff interface
- [[24193]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24193) Add CodeMirror linting of JavaScript, CSS, HTML, and YAML system preferences
- [[17016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17016) Button to clear all fields in budget planning
- [[24291]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24291) Explanation next to limit item types by library is confusing
- [[24670]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24670) Circulation and fine rules page has performance issues since issuingrules change
- [[24576]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24576) StoreLastBorrower preference is in the wrong tab and is confusing
- [[15686]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15686) Rename "item level holds" circ rule column to "OPAC item level holds"
- [[21520]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21520) More complex OAI sets mappings
- [[24329]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24329) Patron cardnumber change times are lost during upgrade for bug 3820

## Templates

- [[26150]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26150) Remove the use of jquery.checkboxes plugin from inventory page
- [[26153]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26153) Remove the use of jquery.checkboxes plugin from items lost report
- [[26149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26149) Remove jquery.checkboxes plugin from problem reports page
- [[26159]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26159) Remove the use of jquery.checkboxes plugin from batch record delete page
- [[26201]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26201) Remove the use of jquery.checkboxes plugin from batch extend due dates page
- [[26202]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26202) Remove the use of jquery.checkboxes plugin from batch record modification page
- [[26204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26204) Remove the use of jquery.checkboxes plugin from staff interface lists
- [[26212]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26212) Remove the use of jquery.checkboxes plugin from pending offline circulations
- [[26214]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26214) Remove the use of jquery.checkboxes plugin on late orders page
- [[26215]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26215) Remove the use of jquery.checkboxes plugin from Z39.50 search pages
- [[26216]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26216) Remove the use of jquery.checkboxes plugin from catalog search results
- [[26010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26010) Remove the use of jquery.checkboxes plugin from staff interface cart
- [[26085]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26085) Add the copy, print and export DataTables buttons to lost items report
- [[26004]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26004) Remove unused jQuery plugin jquery.hoverIntent.minified.js from the OPAC
- [[26011]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26011) Remove unused jQuery plugin jquery.metadata.min.js from the OPAC
- [[25968]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25968) Make logs sort by date descending as a default and add column configuration options
- [[26016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26016) Capitalization: MARC Preview
- [[25765]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25765) Replace LoginBranchname and LoginBranchcode with use of Branches template plugin
- [[25718]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25718) Correct typo in additem.tt
- [[25427]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25427) Make authority subfield management interface consistent with bibliographic subfield management view
- [[24625]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24625) Phase out jquery.cookie.js:  showLastPatron
- [[23148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23148) Replace Bridge icons with transparent PNG files
- [[25987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25987) Radio buttons are misaligned in New label batches
- [[25471]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25471) Add DataTables to MARC subfield structure admin page for bibliographic frameworks
- [[25747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25747) Don't display a comma when patron has no firstname
- [[25842]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25842) Typo "streetype" in member-main-address-style.inc
- [[25839]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25839) Typo patron.streetype in member-main-address-style.inc
- [[25363]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25363) Merge common.js with staff-global.js
- [[25593]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25593) Terminology: Fix "There is no order for this biblio." on catalog detail page
- [[25627]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25627) Move OPAC problem reports from administration to tools
- [[25687]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25687) Switch Y/N in EDI accounts table for Yes and No for better translatability
- [[25582]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25582) Don't show OPAC problems entry on dashboard when there are no reports
- [[25416]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25416) Add information about anonymous session for XSLT use
- [[24963]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24963) Terminology: auto renewal, auto-renewal or autorenewal?
- [[24098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24098) Standardize Fines/Fees & Charges
- [[23433]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23433) Make consistent use of patron-title.inc in hold confirmation dialogs
- [[25002]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25002) JS Includes should be wrapped with template comments
- [[25282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25282) Menu for Action menubutton in dataTables like MARC frameworks page separated from the button
- [[25135]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25135) Improve clarity and navigation of columns settings administration
- [[24939]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24939) Labels in system preferences not following capitalization rules
- [[25010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25010) Fix typo in debit type description: rewewal
- [[16457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16457) Remove the use of "onclick" from the patron entry form
- [[24886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24886) Reports template should be reindented
- [[24776]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24776) Remove useless Borrowers Template Toolkit plugin
- [[24713]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24713) JavaScript error on staff client catalog search results page
- [[23534]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23534) Use patron-title.inc on patron entry page
- [[23536]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23536) Remove obsolete category markup from patron entry
- [[24363]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24363) Datepicker calendar is not always sexy
- [[15352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15352) Use URLLinkText instead of URL for item links
- [[23533]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23533) Reindent patron entry form (memberentrygen.tt)
- [[23493]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23493) jquery.dataTables.rowGrouping.js is no longer maintained, but there is an official DataTables version we could switch to
- [[23856]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23856) Split author and ISBN/ISSN out of citation in staged MARC record management
- [[23885]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23885) Move staff client search results JavaScript into separate file
- [[23884]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23884) Merge strings.inc and browser-strings.inc
- [[24393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24393) Remove event attributes from patron clubs list template
- [[24433]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24433) OPAC account page no longer asks for confirmation before deleting hold
- [[24341]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24341) Add support for more complex markup in OPAC confirmation dialogs
- [[24059]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24059) Remove unused Greybox assets from detail.tt

## Test Suite

- [[26115]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26115) Remove leftover Carp::Always
- [[25638]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25638) API related tests failing on comparing floats
- [[25641]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25641) Koha/XSLT/Base.t is failing on U20
- [[25513]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25513) Integer casting in Koha::Object->TO_JSON causes random test failures
- [[25540]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25540) Biblio.t is failing randomly
- [[22001]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22001) Add RaiseError and PrintError flags for all tests
- [[24881]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24881) Circulation.t still fails if tests are ran slowly
- [[24817]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24817) Fix timing issues in t/db_dependant/Koha/Cash/Register.t
- [[24756]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24756) Occasional failures for Koha/XSLT/Security.t
- [[24757]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24757) t/db_dependent/Koha/Patrons.t get_age fails on February 28 in a Leap Year
- [[24657]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24657) Fix tests of bug 22284 - Groups of pickup locations for holds
- [[24002]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24002) Test suite is failing on MySQL 8
- [[22898]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22898) Selenium tests for placing holds from the staff interface
- [[24361]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24361) Fix warnings (or failing tests) from bug 24217
- [[24509]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24509) API related tests failing on MySQL8

## Tools

- [[26013]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26013) Date on 'manage staged MARC records' is not formatted correctly
- [[26017]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26017) Cashup registers never shows on tools page
- [[26121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26121) When using CodeMirror in News Tool DatePicker is hard to see
- [[26124]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26124) Console errors on tools_koha-news when editing with TinyMCE
- [[22660]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22660) Allow use of CodeMirror for editing HTML in the news editor
- [[5087]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=5087) Option to not show CSV profiles in OPAC
- [[25845]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25845) Cannot limit system logs to 'api' interface
- [[24484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24484) Add explanatory text to batch patron deletion
- [[25249]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25249) When viewing a patron's modification log we should see both the MEMBERS and CIRCULATION modules
- [[25250]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25250) JS code for checkboxes also affects hidden modules inputs
- [[24900]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24900) Fix 'MARC modification templates' to not assume that 'from field' will match 'conditional field'
- [[23473]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23473) Add option to import/overwrite passwords when using the patron import tool
- [[24982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24982) Update the log viewer to use checkboxes instead of select lists
- [[18127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18127) Add ability to add batch modified records to an existing list
- [[24390]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24390) Add item total to rotating collections (addItems.tt)
- [[17510]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17510) MARC modification templates ignore subfield $0
- [[14647]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14647) When exporting records, the file name extension should match the selected export format
- [[19793]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19793) Add email to batch patron modification
- [[21959]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21959) Add ability to apply regular expressions to text fields in the batch item modification tool

## Web services

- [[24769]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24769) DataTable error on patron hold page when hold placed (ILS-DI and other bugs)
- [[24537]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24537) Add support for IP ranges in ILS-DI:AuthorizedIPs using Net::Netmask
- [[24384]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24384) Add Access-Control-Allow-Origin support to OPAC reports svc
- [[23531]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23531) ILS-DI doesn't implement needed_before_date and pickup_expiry_date parameters (renamed start_date and expiry_date)
- [[24369]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24369) Add ability to set CORS header in Koha
- [[24531]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24531) OAI-PMH set mappings only consider first field with a given tag

## Z39.50 / SRU / OpenSearch Servers

- [[25702]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25702) Actions button on Search results from Z39.50 is displayed incorrectly
- [[11297]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11297) Add support for custom PQF attributes for Z39.50 server searches
- [[21921]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21921) Add publication year to the Z39.50 search form for bibliographic records


