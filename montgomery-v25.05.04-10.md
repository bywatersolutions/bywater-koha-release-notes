
# Release Notes for montgomery-v25.05.04-10

## About

- [[40468]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40468) Terminology on the About > Licenses page - use US American spelling for license
- [[40692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40692) Wrong color background in Perl modules page

## Accessibility

- [[38642]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38642) DataTables expand button has no label
- [[40609]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40609) Invisible Button Styling in "hint" Container Until Hovered

## Acquisitions

- [[41100]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41100) EDI vendor account port numbers no longer editable
- [[40743]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40743) Unable to select the correct fund when paying invoices
- [[40918]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40918) Invoice Adjustment Reason always "No reason" even if report shows a saved reason
- [[40868]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40868) Vendor module permissions are ignored
- [[40861]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40861) "Odd number of elements in anonymous hash" warning in serials/acqui-search-result.pl
- [[39980]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39980) Vendors pages are broken when using Koha as a Mojolicious application
- [[36155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36155) Improve performance of suggestion.pl when there are many budgets
- [[38619]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38619) UNIMARC prices should also be extracted from 071d
- [[40146]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40146) Untranslatable actions on vendor

## Architecture, internals, and plumbing

- [[40766]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40766) Reflected XSS in set-library.pl
- [[40748]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40748) Remote-Code-Execution (RCE) in update_social_data.pl
- [[40838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40838) Bookings related built CSS not ignored by Git
- [[40585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40585) Prevent crash on biblionumber in addbybiblionumber.pl
- [[40773]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40773) Improve build of "vue/dist" files
- [[40636]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40636) C4::Reserves::CancelExpiredReserves behavior depends on date it is run
- [[40275]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40275) Add Koha::Patrons->find_by_identifier()
- [[40671]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40671) Expand Koha::Hold->revert_waiting to handle all found statuses
- [[40725]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40725) DBRev 23.12.00.053 should be made more resilient
- [[40058]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40058) Move RevertWaitingStatus to Koha::Hold->revert_waiting()
- [[40608]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40608) Password not changed if PASSWORD_CHANGE letter absent
- [[40150]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40150) Prevent uncaught error on multiple attempts to 'define' on 'CustomElementsRegistry' in islands.ts
- [[35467]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35467) NewsLog should be renamed
- [[40641]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40641) Patron.pm can create warnings
- [[40405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40405) systempreferences.value cannot be set to NULL

## Bywater Only

- NOT IN BUGZILLA - GHA - Don't run xt/tt_tidy.t for bywater builds

## Cataloging

- [[40997]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40997) Javascript error prevents saving when an instance of an 'important' or 'required' field is deleted
- [[40908]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40908) Issues with deleting items from additem page
- [[38967]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38967) Export to CSV or Barcode file from item search results fail when "select visible rows" and many items are selected
- [[40839]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40839) Advanced cataloging editor z39.50 search should include Keyword in Advanced Search options
- [[31460]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31460) Merging biblio records with attached item groups losing groups
- [[40497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40497) Item add form does not respect framework maxlength setting
- [[35654]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35654) Add option to delete_items.pl to delete record if existing item getting deleted is the only one attached to the bib

## Circulation

- [[40899]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40899) When placing multiple holds at once the individual "Pickup location:" dropdowns do not update when changing the top level "Pickup at:" dropdown"
- [[40679]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40679) Existing holds toolbar goes wonky if you select 'del' from priority dropdown
- [[40708]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40708) Increase accuracy and accessibility of checkin errors
- [[40689]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40689) "Lost status" and "Damaged status" don't appear on moredetail.pl if user can't update them
- [[36455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36455) Default the hold queue link to your logged in library
- [[40644]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40644) Bookings biblio checks erroneously if multiple check-outs and bookings exist
- [[36789]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36789) Transform a booking into checkout
- [[40656]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40656) bookings/list.tt needs to be refactored
- [[9762]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=9762) Log circulation overrides
- [[40643]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40643) circulation.tt attaches event listeners to keypress in a problematic way
- [[40690]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40690) Checkout status doesn't appear on moredetail.pl if item is not checked out
- [[40678]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40678) Choices are not remembered if a wrong transfer modal is generated
- [[23010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23010) If an item is checked out or in transit it should not be able to be marked withdrawn

## Command-line Utilities

- [[40953]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40953) marc_ordering_process.pl broken due to accidental newline

## Database

- [[38906]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38906) REGEXP_REPLACE not in MySQL < 5.7b DB update 24.06.00.064 fails

## Developer documentation

- [[38997]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38997) Remove reference to "members" in SendAlerts

## ERM

- [[40774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40774) EBSCO Packages search box is missing
- [[39345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39345) Koha must support COUNTER 5.1

## Hold requests

- [[40586]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40586) opac-user, holds-table.inc: Include on order status when item.notforloan < 0
- [[15516]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15516) Allow to place a hold on first available item from a group of titles
- [[36135]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36135) Add tool to batch modify holds
- [[40747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40747) Placeholder text in the filter row for Publication Details on the holds queue is incorrect
- [[40672]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40672) `desk_id` not cleared when `revert_found()` called
- [[40515]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40515) Mark as lost and notify patron is broken in pendingreserves.pl
- [[37651]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37651) biblio->current_holds and item->current_holds do not respect ConfirmFutureHolds
- [[40395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40395) Allow selecting multiple holds in patron detail page to perform actions on

## Holidays

- [[38633]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38633) Calendar - Weekly closures are ignored when setting a yearly repeating holiday

## I18N/L10N

- [[40510]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40510) Add context to the word "More" in several templates
- [[33856]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33856) Inventory tool CSV export contains untranslatable strings
- [[37926]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37926) Bookings - "to" untranslatable

## Installation and upgrade (command-line installer)

- [[40292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40292) SQL syntax error when upgrading to 25.05 on MariaDB 10.3, RENAME COLUMN unsupported

## Installation and upgrade (web-based installer)

- [[40557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40557) Onboarding enrollment period fields styled badly

## Lists

- [[40916]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40916) Cannot edit a list to have a sortfield value of anything other than publicationyear

## MARC Bibliographic data support

- [[40618]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40618) The display of the field 255 (Cartographic Mathematical Data) is missing (both in intranet and OPAC)
- [[40071]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40071) MARC21 Addition to relator terms in technical notice 2025-06-04
- [[40072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40072) MARC21 Addition to relator terms in technical notice 2025-04-03
- [[40073]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40073) MARC21 Addition to relator terms in technical notice 2025-02-06
- [[40482]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40482) bookcover/bookcoverimg class in search results show include more data-attributes for customization

## Notices

- [[39883]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39883) NEW_SUGGESTION email notices end up in the patrons notice tab (members/notices.pl) when they should not
- [[36114]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36114) Port default TRANSFERSLIP notice to Template Toolkit syntax
- [[40305]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40305) Collected and change variables are inconsistent in controllers and notice templates

## OPAC

- [[40614]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40614) Invalid markup in cookie consent modal
- [[40759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40759) Wrong date format in subscription brief history in OPAC
- [[40612]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40612) Eliminate duplicate element id in OPAC language menus
- [[40780]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40780) Removing rows on advanced search should not lose focus
- [[40782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40782) Selections toolbar buttons should not be focusable when they are inactive
- [[40602]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40602) Broken HTML showing in Alert 'subscriptions' tab
- [[40803]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40803) Users cannot renew overdue items from 'Overdue' tab in account
- [[40523]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40523) Remove unused export_buttons variable from koha-tmpl/opac-tmpl/bootstrap/js/datatables.js
- [[38455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38455) UNIMARC XSLT Music incipit (036) try to display field 031 (as in MARC21)

## Patrons

- [[40886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40886) Patron circ messages not sorted in chronological order
- [[40807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40807) Quick add form does not include 'username' when it is included in BorrowerMandatoryFields
- [[40566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40566) "Home library" empty on "Recalls history"
- [[36278]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36278) Relabel "Gone no address"
- [[40251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40251) Icon for self-check user permission
- [[22632]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22632) Add logging of merged patrons

## Plugin architecture

- [[40812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40812) Move Theke sample plugin repo to Github
- [[40653]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40653) plugins/run.pl controller drops authentication if logging in to that route
- [[34978]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34978) Add --include and --exclude options to install_plugins.pl to choose the plugins to install

## Reports

- [[40939]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40939) Cardnumber not found when performing batch actions from report results
- [[40819]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40819) Guided reports select column should not be initialized as select2
- [[40425]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40425) Guided report - "Next" button on last step is misleading

## REST API

- [[36536]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36536) Make REST API's validateUserAndPassword update borrowers.lastseen
- [[40543]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40543) pickup_library.branchname embed wrong
- [[39900]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39900) Add public REST endpoint for additional_contents

## Searching

- [[40888]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40888) and/or/not drop-downs are missing in the Advanced Search form
- [[33646]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33646) "Cataloging search" missing important data for not for loan items
- [[39072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39072) Item search shareable link adding selections for similar LOC auth values

## Self checkout

- [[40763]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40763) SCO alert box for for wrong password used alert-info when it should use alert-warning

## Serials

- [[37116]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37116) Add the option to edit linked serials when editing items

## SIP2

- [[40675]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40675) Carriage return in patron note message breaks SIP
- [[39820]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39820) Items with hold cancellation requests should have the hold cancelled when checked in via SIP

## Staff interface

- [[40866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40866) Corrections to override logging
- [[40880]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40880) Exporting Item search results to csv, columns after Damaged Status are misaligned
- [[40876]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40876) DT - Exact search not applied on second attribute for column filters
- [[40565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40565) Column filters on the item search do not work
- [[27934]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27934) Table sorting using title-string option is obsolete
- [[40734]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40734) Libraries additional fields don't appear when creating a new library
- [[40753]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40753) DT's SaveState not working on the orders table
- [[39930]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39930) Saved configuration states on tables are lost overnight
- [[40040]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40040) RTL CSS files not loaded in templates; legacy right-to-left.css causing UI issues
- [[40645]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40645) When adding to a list the 'list name' field is cut off
- [[37883]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37883) Add a filter for staff search results to filter by library

## System Administration

- [[40655]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40655) Transport cost matrix doesn't save changes
- [[39824]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39824) Add a direct link to default framework in MARC bibliographic frameworks page

## Templates

- [[36095]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36095) Improve translation of title tags: OPAC part 2
- [[38877]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38877) Improve translation of title tags: OPAC part 3
- [[40591]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40591) Typo in fastadd button class
- [[40606]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40606) Remove italics from shelving location in the staff interface
- [[40600]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40600) Typo in ILL requests template: "Complete request request"
- [[40592]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40592) Fix incorrect row highlighting on patron checkout history page

## Test Suite

- [[40858]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40858) t/00-merge-conflict-markers.t should only test files part of git repo
- [[40765]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40765) Acquisition tests will fail if order.quantity is set to 0
- [[40315]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40315) xt/tt_tidy.t generates warnings
- [[40444]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40444) Add a test to ensure all Perl test files use Test::NoWarnings

## Tools

- [[40702]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40702) Inventory CSV export missing "title" header
- [[40691]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40691) CCODE label not includes in case of 'wrong place' problem (and maybe others cases) into inventory.pl
- [[39423]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39423) Column checkboxes on item batch modification hide incorrect columns
- [[34561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34561) Move IntranetReportsHomeHTML to HTML customizations

## Web services

- [[36561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36561) Inappropriate permission for "/api/v1/auth/password/validation"


