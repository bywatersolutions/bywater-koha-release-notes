
# Release Notes for arlington-v21.05.19-01

## About

- [[30808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30808) Release team 22.11

## Acquisitions

- [[14680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14680) When creating orders from a staged file discounts supplied in the form are added

## Architecture, internals, and plumbing

- [[31473]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31473) Test about bad OpacHiddenItems conf fragile
- [[30848]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30848) Introduce Koha::Filter::ExpandCodedFields
- [[30540]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30540) Double processing invalid dates can lead to ISE
- [[30406]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30406) Our DT tables not filtering on the correct column if hidden by default
- [[29771]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29771) Get rid of CGI::param in list context warnings
- [[30172]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30172) Background jobs failing due to race condition

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Skip building docker images for now, it always fails
- NOT IN BUGZILLA - Fix translations for Koha 21.05.19
- NOT IN BUGZILLA - Fix translations for Koha 21.05.18
- NOT IN BUGZILLA - Fix translations for Koha 21.05.17
- NOT IN BUGZILLA - Bug 30969: Cross site scripting (XSS) attack in OPAC authority search ( opac-authorities-home.pl )
- NOT IN BUGZILLA - Increment version number for 21.05.15 release
- NOT IN BUGZILLA - Fix translations for Koha 21.05.15
- NOT IN BUGZILLA - Translation fixes for 21.05.15
- NOT IN BUGZILLA - Translation fixes for 21.05.14

## Cataloging

- [[29958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29958) Missing dateaccessioned is set to today when storing an item
- [[30234]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30234) Serial local covers don't appear in the staff interface for other libraries with SeparateHoldings
- [[26328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26328) incremental barcode generation fails when incorrectly converting strings to numbers

## Circulation

- [[29051]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29051) Seen renewal methods incorrectly blocked
- [[29504]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29504) Confirm item parts requires force_checkout permission (checkouts tab)
- [[30222]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30222) Auto_renew_digest still sends every day when renewals are not allowed

## Command-line Utilities

- [[30308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30308) bulkmarcimport.pl broken by OAI-PMH:AutoUpdateSets(EmbedItemData)
- [[30914]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30914) cleanup_database.pl --transfers --old-reserves --confirm does not work
- [[30781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30781) Use of uninitialized value $val in substitution iterator at /usr/share/koha/lib/C4/Letters.pm line 665.

## Custom For Instance

- [[24857]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24857) Add ability to group items for records

## Fines and fees

- [[30567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30567) Create manual invoice with FR currency format show the incorrect format
- [[30346]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30346) Editing circ rule with Overdue fines cap (amount) results in data loss and extra fines

## Hold requests

- [[30630]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30630) Checking in a waiting hold at another branch when HoldsAutoFill is enabled causes errors
- [[30583]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30583) Hold system broken for translated template
- [[29704]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29704) Holds reminder emails should allow configuration for a specific number of days
- [[29338]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29338) Reprinting holds slip with updated expiration date

## I18N/L10N

- [[30958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30958) OPAC Overdrive search result page broken for translations

## Label/patron card printing

- [[24001]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24001) Cannot edit card template

## Notices

- [[30354]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30354) AUTO_RENEWALS_DGST notices are not generated if patron set to receive notice via SMS and no SMS notice defined

## OPAC

- [[30220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30220) Purchase suggestion defaults to first library
- [[29482]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29482) Terminology: This item belongs to another branch.

## Packaging

- [[30209]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30209) Upgrade 'libdbd-sqlite2-perl' package to 'libdbd-sqlite3-perl'

## Patrons

- [[31005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31005) Cannot edit patrons in other categories if an extended attribute is mandatory and limited to a category
- [[28943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28943) Lower the risk of accidental patron deletion by cleanup_database.pl

## Reports

- [[27045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27045) Exports using CSV profiles with tab as separator don't work correctly
- [[30551]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30551) Cash register report shows wrong library when paying fees in two different libraries

## REST API

- [[30663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30663) POST /api/v1/suggestions won't honor suggestions limits

## Searching

- [[29374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29374) searchResults explodes if biblio record has been deleted

## Searching - Elasticsearch

- [[28610]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28610) Elasticsearch 7 - hits.total is now an object
- [[25669]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25669) ElasticSearch 6: [types removal] Specifying types in put mapping requests is deprecated (incompatible with 7)
- [[30883]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30883) Authorities merge is limited to 100 biblio with Elasticsearch
- [[30142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30142) ElasticSearch MARC mappings should not accept whitespaces

## Searching - Zebra

- [[29418]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29418) Error searching for analytics in detail view

## Self checkout

- [[30199]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30199) self checkout login by cardnumber is broken if you input a non-existent cardnumber

## Serials

- [[30035]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30035) Wrong month name in numbering pattern

## SIP2

- [[30118]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30118) holds_block_checkin behavior is different in Koha and in SIP

## Staff Client

- [[31138]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31138) DataTables is not raising error to the end user
- [[30610]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30610) The 'Print receipt' button on cash management registers page fails on second datatables page

## System Administration

- [[29020]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29020) Missing Background jobs link in admin-home
- [[29875]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29875) Update text on MaxReserves system preference to describe functionality.

## Templates

- [[30212]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30212) Make Select2 available for ILL backend developers

## Test Suite

- [[31108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31108) rename ./t/00-check-atomic-updates.pl extension to *.t
- [[30595]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30595) update_child_to_adult.t is failing randomly
- [[19169]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19169) Add a test to detect unneeded 'atomicupdate' files

## Tools

- [[30628]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30628) Batch borrower modifications only affect the current page
- [[30518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30518) StockRotationItems crossing DST boundary throw invalid local time exception


