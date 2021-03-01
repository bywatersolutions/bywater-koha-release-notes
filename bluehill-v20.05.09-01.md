
# Release Notes for bluehill-v20.05.09-01

## Acquisitions

- [[24469]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24469) Record biblionumber in import_biblio when adding to basket via file
- [[27646]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27646) Allow export of acquisitions home and funds table
- [[23767]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23767) Spent and Ordered total values don't include child funds on acqui-home
- [[27608]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27608) Correct 'accepted by' inconsistency in suggestion.tt
- [[27547]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27547) Typo in parcel.tt

## Architecture, internals, and plumbing

- [[27676]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27676) finesMode=off not correctly handled
- [[27154]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27154) Koha/Util/SystemPreferences.pm must be removed
- [[27586]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27586) Import patrons script has a confirm switch that doesn't do anything
- [[25552]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25552) Add missing Claims Returned option to MarkLostItemsAsReturned
- [[27530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27530) Sample patron data should be updated and/or use relative dates
- [[27580]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27580) NULL values not correctly handled in Koha::Items->filter_by_visible_in_opac
- [[27333]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27333) Wrong exception thrown in Koha::Club::Hold::add
- [[27327]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27327) Indirect object notation in Koha::Club::Hold
- [[27179]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27179) Misspelling of Method in REST API files
- [[25381]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25381) XSLTs should not define entities
- [[24254]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24254) Add Koha::Items->filter_by_visible_in_opac

## Bywater Only

- NOT IN BUGZILLA - Traslation fixes for Koha 20.05.09

## Cataloging

- [[27422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27422) HTML5Media is http by default but Youtube is https only
- [[26943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26943) Show not for loan descriptions in cataloging search (addbooks.pl)
- [[27308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27308) Advanced editor should skip blank lines when inserting new fields

## Circulation

- [[27707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27707) Renewing doesn't work when renewal notices are enabled
- [[8287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8287) Improve filter on checked out from overdues
- [[27645]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27645) Duplicate message in batch checkout
- [[27655]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27655) Barcode column is missing from "Holds to pull" table preferences yaml file
- [[27549]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27549) Warning "use of uninitialized value" on renew.pl
- [[27548]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27548) Warnings "use of uninitialized value" on branchoverdues.pl
- [[27538]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27538) Cells in the bottom filtering row of the "Holds to pull" table shifted
- [[27011]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27011) Warnings in returns.pl
- [[27306]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27306) Add subtitle to return claims table

## Command-line Utilities

- [[11344]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11344) Perldoc issues in misc/cronjobs/advance_notices.pl
- [[24272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24272) Add a command line script to compare the syspref cache to the database
- [[17429]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17429) Document the --plack option for koha-list

## Fines and fees

- [[20527]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20527) <label> linked to the wrong <input> (wrong "for" attribute) in paycollect.tt

## Hold requests

- [[27068]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27068) HoldsQueue doesn't know how to use holds groups
- [[26634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26634) Hold rules applied incorrectly when All Libraries rules are more specific than branch rules

## I18N/L10N

- [[27398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27398) Serials: Values in subscription length pull down are not translatable when defining numbering patterns
- [[27416]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27416) String 'Modify tag' in breadcrumb is untranslatable

## ILL

- [[25614]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25614) "Clear filter" button permanently disabled on ILL request list

## Installation and upgrade (web-based installer)

- [[24811]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24811) French SQL files for "news" contain broken link to the wiki
- [[24810]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24810) French SQL files for "news" contain "Welcome into Koha 3!"
- [[11996]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11996) Default active currencies for ru-RU and uk-UA are wrong

## Lists

- [[27715]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27715) Possibly SQL injection in virtualshelves

## MARC Bibliographic data support

- [[25632]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25632) Update MARC21 frameworks to update Nr. 30 (May 2020)

## Notices

- [[24447]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24447) POD of C4::Members::Messaging::GetMessagingPreferences() is misleading

## OPAC

- [[27571]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27571) "Add to lists" on MARC and ISBD view of OPAC detail page doesn't open in new window
- [[27450]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27450) Making password required for patron registration breaks patron modification
- [[27029]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27029) Detail page missing Javascript accessible biblionumber value
- [[15448]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15448) Placing hold on specific items doesn't enforce OpacHiddenItems
- [[27297]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27297) When itemtype is marked as required in OpacSuggestion MandatoryFields the field is not required

## Patrons

- [[27604]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27604) PatronSelfRegistrationLibraryList can be bypassed
- [[26059]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26059) Create guarantor/guarantee links on patron import
- [[27454]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27454) Additional patron attributes change sequence on every reload of edit page

## Reports

- [[26713]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26713) Add pagination to bottom of saved SQL reports table

## REST API

- [[26181]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26181) Holds placed via the REST API should not be forced by default even if AllowHoldPolicyOverride is enabled

## Searching

- [[26957]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26957) Find duplicate removes operators from the middle of search terms

## Searching - Elasticsearch

- [[27307]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27307) "Keyword as phrase" option in search dropdown doesn't work with Elastic

## Searching - Zebra

- [[27299]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27299) Zebra phrase register is incorrectly tokenized when using ICU

## SIP2

- [[27204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27204) SIP patron information request with fee line items returns incorrect data
- [[25808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25808) Renewal via the SIP 'checkout' message gives incorrect message

## Staff Client

- [[27653]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27653) Do not include 'caption' row in print/copy export of datatables
- [[14004]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14004) Add ability to temporarily disable added CSS and Javascript in OPAC and interface

## System Administration

- [[27569]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27569) marc-framework import function doesn't accept LibreOffice csv/ods file formats
- [[27395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27395) Add warning to PatronSelfRegistrationDefaultCategory to avoid accidental patron deletion

## Templates

- [[26602]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26602) Datatables - Actions columns should not be exported
- [[26958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26958) Move Elasticsearch mapping template JS to the footer
- [[27654]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27654) "Table settings for Pages" need to be sorted on "Administration -> Table settings"
- [[27561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27561) Remove type attribute from script tags: Various templates
- [[26755]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26755) Make the guarantor search popup taller
- [[20238]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20238) Show description of ITEMTYPECAT instead of code in itemtypes summary table
- [[27525]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27525) 'wich' instead of a 'with' in a sentence
- [[27531]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27531) Remove type attribute from script tags: Cataloging plugins
- [[27210]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27210) Typo in patron-attr-types.tt
- [[24055]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24055) Description of PayPalReturnURL system preference is unclear
- [[27457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27457) Set focus for cursor to Debit type code field when creating new debit type
- [[27458]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27458) Set focus for cursor to Credit type code field when creating new credit type
- [[27192]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27192) Set focus for cursor to item type input box when creating new item types

## Test Suite

- [[27554]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27554) Clarify and add tests for Koha::Patrons->update_category_to child to adult

## Tools

- [[27576]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27576) Don't show import records table when cleaning a batch
- [[26298]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26298) If MaxItemsToProcessForBatchMod is set to 1000, the max is actually 999


