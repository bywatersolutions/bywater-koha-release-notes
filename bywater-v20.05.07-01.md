
# Release Notes for bywater-v20.05.07-01

## About

- [[27108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27108) Update team for 21.05 cycle

## Acquisitions

- [[26905]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26905) Purchase suggestion button hidden for users with suggestion permission but not acq permission
- [[27082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27082) Problem when a basket has more of 20 orders with uncertain price
- [[18267]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18267) Update price and tax fields in EDI to reflect DB changes

## Architecture, internals, and plumbing

- [[26849]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26849) Fix Array::Utils dependency in cpanfile
- [[27209]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27209) Add Koha::Hold->set_pickup_location
- [[16067]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16067) Koha::Cache, fastmmap caching system is broken
- [[27092]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27092) Remove note about "synced mirror" from the README.md
- [[27002]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27002) Make Koha::Biblio->pickup_locations return a Koha::Libraries resultset
- [[27021]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27021) Chaining on Koha::Objects->empty should always return an empty resultset

## Cataloging

- [[22243]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22243) Advanced Cataloguer editor fails if the target contains an apostrophe in the name
- [[26518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26518) Adding a record can succeed even if adding the biblioitem fails

## Circulation

- [[25583]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25583) When ClaimReturnedLostValue is not set, the claim returned tab doesn't appear

## Command-line Utilities

- [[27276]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27276) borrowers-force-messaging-defaults throws Incorrect DATE value: '0000-00-00' even though sql strict mode is dissabled
- [[14564]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14564) Incorrect permissions prevent web download of configuration backups
- [[26337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26337) Remove unused authorities script should skip merge

## Fines and fees

- [[24519]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24519) Change calculation and validation in Point of Sale should match Paycollect
- [[26536]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26536) "Writeoff/Pay selected" deducts from old unpaid debts first
- [[27079]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27079) UpdateFine adds refunds for fines paid off before return

## Hold requests

- [[22284]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22284) Add ability to define groups of locations for hold pickup
- [[27117]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27117) Staff without modify_holds_priority permission can't update hold pick-up from biblio
- [[27205]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27205) Hold routes are not dealing with invalid pickup locations
- [[26976]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26976) When renewalsallowed is empty the UI is not correct
- [[26988]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26988) Defer loading the hold pickup locations until the dropdown is selected

## MARC Authority data support

- [[25313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25313) Add optional skip_merge parameter to ModAuthority

## MARC Bibliographic record staging/import

- [[27099]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27099) Stage for import button not showing up
- [[26854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26854) stage-marc-import.pl does not properly fork

## OPAC

- [[27230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27230) purchase suggestion authorized value opac_sug doesn't show opac description

## Packaging

- [[25548]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25548) Package install Apache performs unnecessary redirects

## Patrons

- [[27004]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27004) Deleting a staff account who have created claims returned causes problem in the return_claims table because of a NULL value in return_claims.created_by.
- [[26956]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26956) Allow "Show checkouts/fines to guarantor" to be set without a guarantor saved
- [[27144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27144) Cannot delete any patrons
- [[14708]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14708) The patron set as the anonymous patron should not be deletable

## Reports

- [[27142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27142) Patron batch update from report module - no patrons loaded into view

## Searching

- [[7607]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7607) Advanced search: Index and search term don't match when leaving fields empty

## Searching - Elasticsearch

- [[26903]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26903) Authority records not being indexed in Elasticsearch

## Searching - Zebra

- [[12430]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12430) Relevance ranking should also be used without QueryWeightFields system preference

## Serials

- [[26992]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26992) On serial collection page, impossible to delete issues and related items
- [[26846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26846) serial-collections page should select the expected and late serials automatically

## SIP2

- [[27166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27166) SIP2 Connection is killed when an item that was not issued is checked in and generates a transfer

## Staff Client

- [[27256]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27256) "Add" button on point of sale page fails on table paging
- [[26946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26946) Limit size of cash register's name on the UI
- [[26938]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26938) Prevent flash of unstyled content on sales table
- [[23475]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23475) Search context is lost when simple search leads to a single record
- [[26944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26944) Help link from automatic item modification by age should go to the relevant part of the manual

## Test Suite

- [[27055]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27055) Update Firefox version used in Selenium GUI tests
- [[25514]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25514) REST/Plugin/Objects.t is failing randomly
- [[27007]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27007) GetMarcSubfieldStructure called with "unsafe" in tests
- [[26984]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26984) Tests are failing if AnonymousPatron is configured
- [[26986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26986) Second try to prevent Selenium's StaleElementReferenceException

## Tools

- [[27247]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27247) Missing highlighting in Quote of the day
- [[26336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26336) Cannot import items if items ignored when staging
- [[26516]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26516) Importing records with unexpected format of copyrightdate fails


