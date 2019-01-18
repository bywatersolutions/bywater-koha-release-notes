
# Release Notes for vatech-v18.05.05-05

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

## Authentication

- [[20023]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20023) Password recovery should be case insensitive
- [[21323]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21323) Redirect page after login missing multiple params

## Bywater Only

- NOT IN BUGZILLA - remove extra line from rebase
- NOT IN BUGZILLA - This is an empty commit
- NOT IN BUGZILLA - Fix audio alerts so selectors can use both single and double quotes without breaking, fixed in master as of 5e3f428ade0a20062df1fd2852cb4cb99ae06f7b
- NOT IN BUGZILLA - Don't drop the branches_overdrive table on each upgrade
- NOT IN BUGZILLA - Remove t/Koha_ExternalContent_RecordedBooks.t, it doesn't pass without credentials and doesn't fail properly
- NOT IN BUGZILLA - Don't alter MarkLostItemsAsReturned if it has already been upgraded
- NOT IN BUGZILLA - Remove uses of raw TT plugin
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Translation updates RMaint followup for Koha 18.05.05

## Cataloging

- [[18655]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18655) Unimarc field 210c fails on importing fields with a simple quote
- [[21365]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21365) BiblioAddsAuthorities does not work with the Advanced MARC Editor - Rancor
- [[21448]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21448) Field 606 doesn't add multiple x subfields
- [[20785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20785) Advanced Editor does not honor MarcFieldDocURL
- [[21362]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21362) Advanced MARC Editor - Rancor - Tab navigation not working in fixed fields
- [[21407]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21407) Can't enter new macros in the advanced cataloging editor (rancor)

## Circulation

- [[10382]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10382) collection and location not returning to null when removed from course reserves
- [[21464]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21464) Overdues export is missing lot of fields
- [[16420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16420) Buttons inconsistent between "Hold found" and "Hold found (waiting)" dialogs in checkin
- [[21463]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21463) Library is no longer displayed in the overdue list
- [[21176]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21176) decreaseLoanHighHolds does not properly calculate date when  TimeFormat set to 12 hour

## Command-line Utilities

- [[21322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21322) process_message_queue.pl --type should take an argument

## Database

- [[5458]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=5458) length of items.ccode disagrees with authorised_values.authorised_value

## Fines and fees

- [[21673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21673) Koha::Account::Lines->total_outstanding must be used when needed
- [[21167]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21167) Price should be correctly formatted on printed fee receipt and invoice
- [[21196]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21196) C4::Overdues::CalcFine should consider default item type replacement cost

## Hold requests

- [[21495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21495) Regression in hold override functionality
- [[21320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21320) Holds to pull should honor syspref AllowHoldsOnDamagedItems
- [[21389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21389) Javascript error on article requests page

## I18N/L10N

- [[19500]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19500) Make module names on letters overview page translatable

## ILL

- [[20548]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20548) Remove copyright clearance workflow from staff created ILL requests
- [[21289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21289) Error when sending emails to partner libraries

## Installation and upgrade (command-line installer)

- [[21426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21426) setting USE_MEMCACHED to "no" in koha-sites.conf does not have any effect
- [[21440]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21440) koha-create expects the file passed by $DEFAULTSQL to be in gzip format
- [[16690]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16690) Improve security of remote database installations

## Label/patron card printing

- [[21281]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21281) Label Template - Creation not working

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

## Packaging

- [[17237]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17237) Stop koha-create from creating MySQL users without host restriction

## Patrons

- [[21353]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21353) Merge patrons option only available with manage_patron_lists
- [[20656]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20656) Print summary for patron shows paid fines and formats payments badly

## Searching

- [[20151]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20151) Search is broken when stemming has no language
- [[21455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21455) Authority search options get shuffled around when you click on 'Search'
- [[9968]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=9968) Incorrect index used for 'Standard number' in advanced search

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

## System Administration

- [[21279]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21279) Transport cost matrix shows html entity in all empty cells

## Templates

- [[21186]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21186) Incorrect Bootstrap modal event name in multiple templates
- [[21550]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21550) DataTables four button pagination uses the wrong icon for disabled buttons
- [[21506]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21506) DataTables four button pagination uses the wrong icon for First and Last buttons
- [[13272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13272) Many inputs lack a type attribute
- [[21350]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21350) Add Font Awesome icon for pending onsite checkouts link
- [[21397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21397) Routing list tab not marked as active
- [[20223]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20223) Merge members-menu and circ-menu inc files

## Test Suite

- [[20177]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20177) Remove GROUP BY clause in GetCourses

## Tools

- [[20131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20131) Inventory optional filters always shows "For loan" for value 0
- [[21113]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21113) Hint Messages are misleading at "Merge Selected Patrons" in Patron Lists

## translate.koha-community.org

- [[21480]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21480) misc/translator/translate does not work with perl 5.26

