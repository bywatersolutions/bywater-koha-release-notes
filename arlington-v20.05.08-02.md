
# Release Notes for arlington-v20.05.08-02

## About

- [[27108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27108) Update team for 21.05 cycle

## Acquisitions

- [[24470]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24470) Set import_status when file used to populate basket in acquisitions
- [[26905]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26905) Purchase suggestion button hidden for users with suggestion permission but not acq permission
- [[27082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27082) Problem when a basket has more of 20 orders with uncertain price
- [[18267]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18267) Update price and tax fields in EDI to reflect DB changes

## Architecture, internals, and plumbing

- [[27562]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27562) itiva notices break if record title contains quotes
- [[26470]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26470) itemnumber not available for plugin hook
- [[26848]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26848) Fix Readonly dependency in cpanfile
- [[25292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25292) L1 cache too long in Z3950 server (z3950-responder)
- [[27345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27345) C4::Auth::get_template_and_user is missing some permissions for superlibrarian
- [[27252]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27252) ES5 no longer supported (since 20.11.00)
- [[26849]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26849) Fix Array::Utils dependency in cpanfile
- [[27209]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27209) Add Koha::Hold->set_pickup_location
- [[16067]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16067) Koha::Cache, fastmmap caching system is broken
- [[27092]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27092) Remove note about "synced mirror" from the README.md
- [[27002]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27002) Make Koha::Biblio->pickup_locations return a Koha::Libraries resultset
- [[27021]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27021) Chaining on Koha::Objects->empty should always return an empty resultset

## Cataloging

- [[27509]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27509) cn_sort value is lost when editing an item without changing cn_source or itemcallnumber
- [[27164]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27164) Fix item search CSV export
- [[26330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26330) jQueryUI tabs don't work with non-Latin-1 characters
- [[27137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27137) Move item doesn't show the title of the target record
- [[22243]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22243) Advanced Cataloguer editor fails if the target contains an apostrophe in the name
- [[26518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26518) Adding a record can succeed even if adding the biblioitem fails

## Circulation

- [[25583]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25583) When ClaimReturnedLostValue is not set, the claim returned tab doesn't appear

## Command-line Utilities

- [[26851]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26851) Overdue notices should not send a report to the library if there is no content
- [[27245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27245) bulkmarcimport.pl error 'Already in a transaction'
- [[27085]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27085) Corrections in overdue_notices.pl help text
- [[27276]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27276) borrowers-force-messaging-defaults throws Incorrect DATE value: '0000-00-00' even though sql strict mode is dissabled
- [[14564]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14564) Incorrect permissions prevent web download of configuration backups
- [[26337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26337) Remove unused authorities script should skip merge

## Custom For Instance

- NOT IN BUGZILLA - Fix bug causing javascript error, again, again

## Database

- [[27003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27003) action_logs table error when adding an item
- [[25826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25826) Hiding biblionumber in the frameworks breaks links in result list

## Fines and fees

- [[27180]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27180) Fines cronjob does not update fines on holidays when finesCalendar is set to ignore
- [[26593]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26593) Rental discounts are applied in wrong precedence order
- [[24519]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24519) Change calculation and validation in Point of Sale should match Paycollect
- [[26536]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26536) "Writeoff/Pay selected" deducts from old unpaid debts first
- [[27079]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27079) UpdateFine adds refunds for fines paid off before return

## Hold requests

- [[22284]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22284) Add ability to define groups of locations for hold pickup
- [[26698]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26698) Hold can show as waiting and in transit at the same time
- [[27117]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27117) Staff without modify_holds_priority permission can't update hold pick-up from biblio
- [[27205]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27205) Hold routes are not dealing with invalid pickup locations
- [[26976]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26976) When renewalsallowed is empty the UI is not correct
- [[26988]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26988) Defer loading the hold pickup locations until the dropdown is selected

## Label/patron card printing

- [[26875]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26875) Allow printing of just one barcode

## MARC Authority data support

- [[25313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25313) Add optional skip_merge parameter to ModAuthority

## MARC Bibliographic record staging/import

- [[26171]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26171) Show biblionumber in Koha::Exceptions::Metadata::Invalid
- [[27099]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27099) Stage for import button not showing up
- [[26854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26854) stage-marc-import.pl does not properly fork

## OPAC

- [[27090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27090) In the location column of an OPAC cart the 'In transit from' and 'to' fields are empty
- [[26397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26397) opac.scss calls non-existent image
- [[27178]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27178) OPAC results and lists pages contain invalid attributes (xmlns:str="http://exslt.org/strings")
- [[27230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27230) purchase suggestion authorized value opac_sug doesn't show opac description

## Packaging

- [[25548]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25548) Package install Apache performs unnecessary redirects

## Patrons

- [[27420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27420) A mistake in bug 5161 leads to some patron attributes appearing without a fieldset
- [[26417]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26417) Remove warn in Koha::Patron is_valid_age
- [[27004]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27004) Deleting a staff account who have created claims returned causes problem in the return_claims table because of a NULL value in return_claims.created_by.
- [[26956]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26956) Allow "Show checkouts/fines to guarantor" to be set without a guarantor saved
- [[27144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27144) Cannot delete any patrons
- [[14708]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14708) The patron set as the anonymous patron should not be deletable

## Plugin architecture

- [[21468]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21468) Plugins need hooks for checkin and checkout actions
- [[25855]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25855) Add hook to AddRenewal using a new _after_circ_actions method in circulation

## Reports

- [[27142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27142) Patron batch update from report module - no patrons loaded into view

## Searching

- [[7607]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7607) Advanced search: Index and search term don't match when leaving fields empty

## Searching - Elasticsearch

- [[24863]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24863) QueryFuzzy syspref says it requires Zebra but Elasticsearch has some support
- [[26996]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26996) Elasticsearch: Multiprocess reindexing sometimes doesn't reindex all records
- [[27043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27043) Add to number_of_replicas and number_of_shards  to index config
- [[26903]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26903) Authority records not being indexed in Elasticsearch

## Searching - Zebra

- [[12430]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12430) Relevance ranking should also be used without QueryWeightFields system preference

## Serials

- [[26992]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26992) On serial collection page, impossible to delete issues and related items
- [[26846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26846) serial-collections page should select the expected and late serials automatically

## SIP2

- [[27196]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27196) Waiting title level hold checked in at wrong location via SIP leaves hold in a broken state and drops connection
- [[27166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27166) SIP2 Connection is killed when an item that was not issued is checked in and generates a transfer

## Staff Client

- [[25462]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25462) Shelving location should be on a new line in holdings table
- [[27256]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27256) "Add" button on point of sale page fails on table paging
- [[26946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26946) Limit size of cash register's name on the UI
- [[26938]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26938) Prevent flash of unstyled content on sales table
- [[23475]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23475) Search context is lost when simple search leads to a single record
- [[26944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26944) Help link from automatic item modification by age should go to the relevant part of the manual

## System Administration

- [[27280]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27280) Explanation for "Days mode" is not consistent
- [[27349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27349) Mana system preference wrong type YesNo
- [[27351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27351) UsageStatsCountry system preference wrong type YesNo

## Templates

- [[25954]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25954) Header search forms should be labeled

## Test Suite

- [[26364]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26364) XISBN.t makes a bad assumption about return values
- [[27055]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27055) Update Firefox version used in Selenium GUI tests
- [[25514]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25514) REST/Plugin/Objects.t is failing randomly
- [[27007]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27007) GetMarcSubfieldStructure called with "unsafe" in tests
- [[26984]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26984) Tests are failing if AnonymousPatron is configured
- [[26986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26986) Second try to prevent Selenium's StaleElementReferenceException

## Tools

- [[27413]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27413) Cannot add debarment with batch patron modification tool
- [[26894]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26894) Marc Modification Templates treat subfield 0 as no subfield set when moving fields
- [[26983]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26983) Selecting ALL Items in Inventory- only selects 20
- [[27247]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27247) Missing highlighting in Quote of the day
- [[26336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26336) Cannot import items if items ignored when staging
- [[26516]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26516) Importing records with unexpected format of copyrightdate fails

## Web services

- [[21301]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21301) Restriction of the informations given by GetRecords ILS-DI service

## Z39.50 / SRU / OpenSearch Servers

- [[27149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27149) Z3950Responder removes itemnumber when adding item statuses


