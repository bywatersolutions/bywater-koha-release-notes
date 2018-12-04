
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


