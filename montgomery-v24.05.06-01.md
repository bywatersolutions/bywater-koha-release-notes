
# Release Notes for montgomery-v24.05.06-01

## About

- [[38517]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38517) Release team 25.05

## Acquisitions

- [[38680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38680) [24.05.x] copyno not copied over when set in MarcItemFieldsToOrder system preference
- [[38437]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38437) Modal does not appear on single order receive
- [[37854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37854) Barcode fails when adding item during order receive (again)
- [[38329]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38329) Remove orphan confirm_deletion() in supplier.tt
- [[38325]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38325) Cannot delete invoice while viewing it
- [[38303]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38303) Item's replacement price not set to defaultreplacecost if 0.00
- [[38297]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38297) The "New vendor" button needs a permissions guard
- [[37184]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37184) Special character encoding problem when importing MARC file from the acquisitions module
- [[38271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38271) Missing 008 field in bibliographic records created via EDIFACT
- [[37304]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37304) Created by filter in acquisitions advanced orders search always shows zero results
- [[37070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37070) Incorrect barcode generation when adding orders to basket
- [[37265]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37265) Consideration of UniqueItemFields setting when receiving items in an order
- [[35087]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35087) Discount rate should only allow valid input formats
- [[36049]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36049) Rounding prices sometimes leads to incorrect results
- [[37914]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37914) Forms for budget planning filters and export should GET rather than POST
- [[34159]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34159) Remove plan by AR_CANCELLATION choice in aqplan
- [[37246]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37246) Suggestions filter by fund displays inactive budgets
- [[35823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35823) When uploading a MARC file to a basket it is showing inactive funds without them being selected
- [[37913]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37913) Remove more unreachable code in aqcontract.tt

## Architecture, internals, and plumbing

- [[38543]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38543) dataTables assets included but no longer exist
- [[37292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37292) Add an index on expires column for oauth_access_tokens
- [[38495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38495) Cannot cancel background job (CSRF)
- [[37865]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37865) Use of uninitialized value $op in string at circulation.pl
- [[38257]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38257) Several functionalities broken in cart pop up
- [[33188]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33188) Warning in Koha::Items->hidden_in_opac
- [[38286]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38286) Koha::Biblio:hidden_in_opac does not need to fetch the items if OpacHiddenItemsHidesRecord is set
- [[37824]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37824) Replace webpack with rspack for fun and profit
- [[38234]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38234) Remove unused vulnerable jszip library file
- [[38274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38274) Typo in Arabic language description
- [[36317]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36317) Koha::Biblio->host_items fails with search_ordered()
- [[38200]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38200) Remove dead code to delete authorities in authorities/authorities.pl
- [[31581]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31581) Remove Zebra files for NORMARC
- [[38027]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38027) Clearing a flatpickr datetime causes errors
- [[38035]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38035) "sound" listed as an installed language
- [[38000]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38000) Redundant code import in search.pl
- [[37982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37982) Serial collection edit form can be GET
- [[37981]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37981) Switch installer/step3.tt form from POST to GET
- [[37757]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37757) notice_email_address explodes if EmailFieldPrimary is not valid
- [[37628]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37628) Remove get_opac_news_by_id
- [[35959]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35959) Inconsistent hierarchy during C3 merge of class 'Koha::AuthorisedValue' (and a few other modules)
- [[37155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37155) Remove unnecessary unblessing of patron in CanItemBeReserved
- [[36901]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36901) Add logging for uncaught exceptions in background job classes
- [[36873]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36873) Koha::Objects->delete should accept parameters and pass them through
- [[37823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37823) Remove unreachable code in aqcontract.tt
- [[37741]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37741) Koha errors on page (e.g. 404) cause incorrect CSRF errors
- [[37672]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37672) V1/RecordSources.pm should use more helpers

## Authentication

- [[37104]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37104) Block AnonymousPatron from logging into anything
- [[36822]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36822) When creating a new patron via LDAP or Shibboleth 0000-00-00 is inserted for invalid updated_on

## Bywater Only

- NOT IN BUGZILLA - Remove failing test t/cypress/integration/ERM/UserRoles_spec.ts

## Cataloging

- [[37293]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37293) MARC bibliographic framework text for librarians and OPAC limited to 100 characters
- [[38158]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38158) Typo in inventory 'Items has no "not for loan" status'
- [[38030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38030) stocknumberAV.pl fails with CSRF protection
- [[38082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38082) Advanced editor does not save the selected framework with new record
- [[38065]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38065) Auto control number (001) widget in advanced editor does not work under CSRF protection
- [[36320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36320) Clicking 'Edit items' from detail page in staff interface leads to 'Add item' screen
- [[38413]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38413) Batch operations from item search results fail when "select visible rows" and many items are selected
- [[37403]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37403) Wrong progress quantity in job details when staging records with match check
- [[38162]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38162) Can't delete a stock rotation
- [[36375]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36375) Inconsistencies in ContentWarningField display
- [[37964]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37964) Only show host items when system preference EasyAnalyticalRecords is enabled
- [[37871]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37871) Remove extraneous 246 subfields from the title mappings (Elasticsearch, MARC21)
- [[26929]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26929) Koha will only display the first 20 macros Advanced Editor
- [[37840]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37840) Wrong status in the Intranet detail page when the item type is not for loan
- [[36821]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36821) Authority type text for librarians and OPAC limited to 100 characters
- [[36976]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36976) Warning 'Argument "" isn't numeric in numeric' in log when merging bibliographic records
- [[27769]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27769) Advanced editor shouldn't break copying selected text with Ctrl+C

## Circulation

- [[37424]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37424) Batch checkout silently fails if item contains materials specified (952$3)
- [[38117]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38117) "Item was not checked in" should not always show
- [[37505]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37505) Statistical patrons don't display information about item status if item wasn't checked out
- [[38012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38012) Remove ispermanent from returns.tt and branchtransfers.tt
- [[37836]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37836) Prevent submitting empty barcodes in self check-in
- [[38097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38097) Add class to "Item was not checked out" message in checkin table
- [[13945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13945) Multiple dialogs for item that needs transferred and hold captured at checkin
- [[37983]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37983) "Search a patron" box no longer has auto focus
- [[37396]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37396) Batch checkout does not checkout items if OverduesBlockCirc set to ask for confirmation
- [[37444]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37444) Can't filter holds to pull by pickup location
- [[37271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37271) Recall status should be 'requested' in overdue_recalls.pl
- [[37524]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37524) Pressing "Renew all" redirects user to "Export data" tool if one of the items is not renewable
- [[37794]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37794) Fix form that POSTs without an op in Holds to pull
- [[37076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37076) Incorrect needsconfirmation code RESERVED_WAITING

## Command-line Utilities

- [[37478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37478) bulkmarcimport.pl can die on bad records
- [[37550]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37550) bulkmarcimport.pl dies when adding items throws an exception
- [[38249]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38249) `koha-list` help typo about elastic
- [[38237]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38237) Add logging to erm_run_harvester cronjob
- [[38173]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38173) Fix description of koha-dump --exclude-indexes
- [[37787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37787) Undocument koha-worker --queue elastic_index
- [[18273]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18273) bulkmarcimport.pl inserts authority duplicates
- [[35466]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35466) bulkmarcimport needs a parameter to skip indexing
- [[36435]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36435) Prevent warnings from interrupting koha-run-backups when deleting old backup files
- [[37709]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37709) bulkmarcimport.pl should die when the file cannot be opened
- [[37038]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37038) koha-elasticsearch creates a file named 0
- [[14565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14565) koha-run-backups does not backup an instance called demo

## Course reserves

- [[37838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37838) Remove button broken on second page of course reserves item results

## Database

- [[38522]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38522) Increase length of erm_argreements.license_info
- [[37593]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37593) Fix typo in schema description for items.bookable
- [[31143]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31143) We should attempt to fix/identify all cases where '0000-00-00' may still remain in the database

## ERM

- [[38272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38272) Add permission check for erm permission to additional-fields.tt
- [[37526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37526) Handle redirects in SUSHI requests
- [[37856]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37856) Some SUSHI providers require the platform parameter
- [[38128]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38128) Agreement/license user selection not limited to users with ERM module permissions
- [[38177]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38177) ERM - HoldingsIQ pagination does not work
- [[37395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37395) Cannot hide columns in ERM tables
- [[37275]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37275) Remove parenthesis from Select user button in ERM
- [[37277]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37277) Identifiers need a space between the ISBN (Print) and ISBN (Online) in ERM
- [[37008]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37008) "Help" link on ERM pages is not translatable
- [[34920]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34920) ERM breaks if an ERM authorized value is missing a description
- [[37491]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37491) Remove duplicate asset import from KBART template

## Fines and fees

- [[37263]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37263) Creating default article request fees is not working

## Hold requests

- [[38239]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38239) Incorrect number of items to pull in holds to pull report with partially filled holds
- [[38186]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38186) Cancelling a hold from the holds over tab shouldn't trigger "return to home" transfer on a lost item
- [[36970]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36970) (Bug 34160 follow-up) Barcode should be html filtered, not uri filtered in holds queue view
- [[35771]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35771) Unselecting titles when making multi-hold does not have any effect

## Holidays

- [[38357]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38357) When adding new holidays Koha sometimes copies same holidays to other librarys

## I18N/L10N

- [[38138]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38138) Main contact method in hold pop-up untranslatable
- [[38085]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38085) Untranslatable options in OPACAuthorIdentifiersAndInformation
- [[36171]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36171) Extraction of Template Toolkit directive as translatable string causes patron view error in several languages
- [[35769]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35769) Untranslatable strings when placing holds in staff
- [[37257]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37257) Copy in OPAC datatable untranslatable
- [[37814]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37814) Wrong use of '__()' in .tt files

## ILL

- [[37178]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37178) Column "comments" in ILL requests table gives error on sorting, paging cannot be changed
- [[37194]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37194) Improve link from unconfigured ILL module

## Installation and upgrade (command-line installer)

- [[38385]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38385) DB updates not displayed properly on the UI

## Label/patron card printing

- [[37863]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37863) Patron card batches don't detect when the patron is already in the list
- [[37206]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37206) Removing an item from a label batch should be a CSRF-protected POST operation

## Lists

- [[38020]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38020) Fix 'delete list' button to have same formatting as 'edit list'
- [[38251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38251) "Remove selected items" button not removing single item in OPAC lists

## MARC Authority data support

- [[37252]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37252) Saving an authority record as MADS (XML) fails
- [[37235]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37235) Download single authority results in 500 error

## MARC Bibliographic data support

- [[28075]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28075) Add missing UNIMARC value for coded data 135a
- [[34346]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34346) Adding duplicate tag to a framework should give user readable message
- [[37357]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37357) Authorised values in control fields cause Javascript errors
- [[37114]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37114) Update MARC21 default framework to Update 38 (June 2024)

## Notices

- [[38089]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38089) Fix incorrect regular expression from bug 33478 and move styles to head
- [[32575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32575) gather_print_notices.pl sends attachment as body of email or poorly named txt file
- [[37642]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37642) Generated letter should use https in header

## OPAC

- [[38362]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38362) Printing lists only prints the ten first results in the OPAC
- [[24690]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24690) Make OPACPopupAuthorsSearch work with search terms containing parenthesis
- [[38463]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38463) Unnecessary CSRF token in OPAC authority search
- [[38100]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38100) Items with damaged status are shown in OPAC results as "Not available" even with AllowHoldsOnDamagedItems
- [[35126]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35126) Remove the use of event attributes from when adding records to lists in the OPAC
- [[37684]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37684) Direct links to expired news are broken
- [[22223]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22223) Item url double-encode when parameter is an encoded URL
- [[38132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38132) Add data-isbn to shelfbrowser images
- [[38231]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38231) Adjust CSS for search result controls in the OPAC
- [[37931]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37931) Wrong OPAC facet item types label
- [[37887]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37887) OPAC password recovery needs to use a cud- op while POSTing new password
- [[37629]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37629) Link to news are broken
- [[37679]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37679) Dublin Core export option broken
- [[37158]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37158) OPAC recalls history table not responsive
- [[37057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37057) OPACShowUnusedAuthorities displays unused authorities regardless
- [[36950]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36950) Improve placement of catalog concern banner in the OPAC
- [[36557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36557) Improve logic and display of OPAC cart, tag, and lists controls
- [[37827]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37827) Switch OPAC download list form from POST to GET
- [[37853]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37853) Returning to your account at the end of changing your password in the OPAC doesn't need to POST a form

## Patrons

- [[37365]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37365) Bad redirect when adding a patron message from members/files.pl
- [[30397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30397) Duplicate '20' option in dropdown 'Show entries' menu
- [[35987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35987) See highlighted items below link broken
- [[30648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30648) Title is lost in holds history when bibliographic record is deleted
- [[38188]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38188) Fix populating borrowernumberslist from patron_search_selections
- [[35508]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35508) Update borrowers.updated_on when modifying a patron's attribute
- [[37528]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37528) Using borrowerRelationship while guarantor relationship is unchecked from BorrowerMandatoryField results in error
- [[38112]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38112) Description of patrons search no longer displayed
- [[38005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38005) 500 error on self registration when patron attribute is set as mandatory
- [[38109]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38109) Patron category types are not sorted when entering/editing patrons
- [[34610]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34610) ProtectSuperlibrarianPrivileges, not ProtectSuperlibrarian
- [[37562]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37562) Duplicate patron check when user cannot see patron leads to a blank popup

## Plugin architecture

- [[37872]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37872) ILL module has issues when plugins are disabled (enable_plugins = 0)

## Reports

- [[37108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37108) Cash register statistics wizard is wrongly sorting payment by home library of the manager
- [[37987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37987) Downloading SQL report in .tab format is slow

## REST API

- [[38390]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38390) Add 'subscriptions+count' embed to vendors endpoint
- [[37032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37032) REST API: Unable to call item info via holds endpoint
- [[37535]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37535) Adding a debit via API will show the patron as the librarian that caused the debit
- [[37687]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37687) API query operators list doesn't match documentation

## Searching

- [[37998]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37998) Tabs and backslashes in the data break item search display
- [[37369]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37369) Item search column filtering can't use descriptions
- [[37333]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37333) Search filters using OR are not correctly grouped
- [[37249]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37249) Item search column filtering broken
- [[37244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37244) Selecting home library or holding library facet changes library dropdown
- [[37167]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37167) Fix mapping call number searches to Z39.50

## Searching - Elasticsearch

- [[38416]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38416) Failover to MARCXML if cannot roundtrip USMARC when indexing
- [[33348]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33348) Show authority heading use with Elasticsearch
- [[37446]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37446) Home/holding library facets missing user friendly label
- [[37857]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37857) Unable to select type "Geo point" or "Call number" when adding a search field
- [[37319]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37319) Move mappings for 752ad (MARC21) and 210a/214a (UNIMARC) to pl index

## Self checkout

- [[38041]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38041) Not all self checkout errors behave the same
- [[37525]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37525) Self checkout: "Return this item" doesn't show up in scan confirmation screen despite SCOAllowCheckin being allowed
- [[37027]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37027) Some dataTable controls in SCO seem unnecessary

## Serials

- [[38470]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38470) Subscription detail page vulnerable to reflected XSS
- [[29818]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29818) Cannot save subscription frequency without display order
- [[38378]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38378) Serial frequency deletion is broken

## SIP2

- [[37087]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37087) Add support for TCP keepalive to SIP server
- [[23426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23426) Empty AV field returned in 'patron info' in addition to those requested
- [[38344]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38344) Don't send "Thank you !" as screen message
- [[38284]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38284) handle_patron_status dies if patron not found
- [[37582]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37582) SIP2 responses can contain newlines when a patron has multiple debarments

## Staff interface

- [[38468]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38468) Staff interface detail page vulnerable to reflected XSS
- [[37727]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37727) CVE-2024-24337 - Fix CSV formula injection - client side (DataTables)
- [[37393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37393) Bundle items don't show their host in the staff interface
- [[38130]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38130) Cannot filter items on library name
- [[38146]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38146) Last seen date is missing the time in the item holdings table
- [[38240]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38240) Filtering resulting in no result will hide filters
- [[38118]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38118) Removed empty columns on holdings table on details page are not restored when new items loaded
- [[37954]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37954) Unable to hide barcode column in holdings table
- [[37928]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37928) "Upload image" item not correctly styled
- [[37233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37233) Library URL broken in the libraries table
- [[37065]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37065) Bookings tab should filter out expired bookings by default
- [[37916]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37916) Plugin search and install regression
- [[37213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37213) Improve breadcrumbs in rotating collections
- [[38071]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38071) "Clear filter" on catalogue details page always disabled

## System Administration

- [[38328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38328) Cannot delete ILL batch statuses
- [[38309]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38309) Cannot delete additional fields
- [[37209]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37209) Improve record overlay rules validation and styling
- [[37905]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37905) Correctly fix the "last hour" filter on the job list
- [[37606]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37606) Framework export module should escape double quotes
- [[37404]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37404) Typo in intranetreadinghistory description
- [[37329]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37329) Typo: authorised value in patron attribute types
- [[37229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37229) Table configuration listings for course reserves incorrect
- [[35257]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35257) Only admin start page uses "circulation desks"
- [[37766]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37766) Fix forms that POST without an op in MARC bibliographic frameworks

## Templates

- [[38536]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38536) Patrons requesting modifications: Expand correct panel
- [[37912]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37912) Catalog concerns - Broken link under concern title
- [[38476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38476) Use anchor tag for DataTables configure button
- [[38066]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38066) Pop-up window footers can block page content
- [[37977]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37977) Fix some issues with labels in inventory form
- [[37848]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37848) "Run with template" options need formatting
- [[37595]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37595) Double HTML escaped ampersand in pagination bar
- [[37231]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37231) (Bug 34940 follow-up) Highlight logged-in library in facets does not work with ES
- [[37242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37242) Don't use the term branch in cash register administration
- [[37264]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37264) Fix delete button on staff interface's suggestion detail page
- [[36905]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36905) Terminology: home locations / home collections
- [[35232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35232) Misspelled ID breaks label on patron lists form
- [[35238]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35238) Incorrect label markup in patron card creator printer profile edit form
- [[33925]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33925) Improve translation of title tags: Serials
- [[35239]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35239) Missing form field ids in batch patron modification template

## Test Suite

- [[38513]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38513) Fix Biblio.t for Koha_Main_My8 test configuration
- [[38526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38526) Auth_with_* tests fail randomly
- [[38322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38322) Wrong comment in t/db_dependent/api/v1/erm_users.t
- [[37963]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37963) Improve error handling and testing of ERM eUsage SUSHI
- [[37870]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37870) UI/Form/Builder/Item.t and Biblio.t are still failing randomly (cn_source sort)
- [[37289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37289) t/db_dependent/api/v1/authorised_values.t is failing under specific circumstances
- [[37283]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37283) t/db_dependent/selenium/authentication.t is failing
- [[36935]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36935) BackgroundJob/ImportKBARTFile.t generates warnings
- [[36944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36944) Auth.t should not fail when AutoLocation is enabled
- [[36936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36936) api/v1/bookings.t generates warnings
- [[37490]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37490) Add test to detect when yarn.lock is not updated
- [[36919]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36919) t/db_dependent/Koha/Object.t produces warnings
- [[37620]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37620) Fix randomly failing tests for cypress/integration/InfiniteScrollSelect_spec.ts

## Tools

- [[37326]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37326) Batch modification should decode barcodes when using a barcode file
- [[36132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36132) Allow users to delete multiple patron lists at once on any page
- [[38266]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38266) Incorrect attribute disabled in patron batch modification
- [[37965]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37965) Fix regression of convert_urls setting in TinyMCE which causes unexpected URL rewriting
- [[38275]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38275) Unable to delete patron card creator images
- [[37730]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37730) Batch patron modification table horizontal scroll causes headers to mismatch
- [[37580]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37580) Unique holiday descriptions are not editable
- [[37243]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37243) Tag moderation actions should be in the last column

## Web services

- [[38131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38131) ILS-DI documentation still shows renewals instead of renewals_count
- [[38233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38233) ILS-DI GetRecords should filter out items hidden in OPAC and use OPAC MARCXML
- [[36560]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36560) ILS-DI API POSTS cause CSRF errors
- [[35442]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35442) Script migration_tools/build_oai_sets.pl is missing ORDER BY


