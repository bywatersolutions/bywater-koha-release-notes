
# Release Notes for barcodeprfx-v21.11.09-01

## About

- [[30808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30808) Release team 22.11

## Acquisitions

- [[31054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31054) Manual importing for EDIFACT invoices fails with a 500 error page
- [[29961]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29961) Horizontal scroll bar in acquisition z39.50 search should always show
- [[30599]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30599) Allow archiving multiple suggestions

## Architecture, internals, and plumbing

- [[30731]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30731) Noise from about script coming from Test::MockTime (or other CPAN modules)
- [[29883]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29883) Uninitialized value warning when GetAuthorisedValues gets called with no parameters
- [[30830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30830) Add Koha Objects  for Koha Import Items
- [[30143]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30143) OAI-PMH provider may end up in an eternal loop due to missing sort
- [[29483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29483) AllowRenewalIfOtherItemsAvailable has poor performance for records with many items
- [[27253]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27253) borrowers.updated_on cannot be null on fresh install, but can be null with upgrade
- [[30540]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30540) Double processing invalid dates can lead to ISE

## Bywater Only

- NOT IN BUGZILLA - Make installer/data/mysql/db_revs/211109000.pl executable
- NOT IN BUGZILLA - Fix translations for Koha 21.11.07
- NOT IN BUGZILLA - Fix translations for Koha 21.11.06

## Cataloging

- [[30717]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30717) Dates displayed in ISO format when editing items
- [[30224]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30224) Wrong important field shown in cataloguing validation
- [[30482]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30482) Potential for bad string concatenation in cataloging validation error message

## Circulation

- [[30337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30337) Holds to Pull ( pendingreserves.pl ) ignores holds if priority 1 hold is suspended
- [[29537]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29537) Simplify auto-renewal code in CanBookBeRenewed
- [[18392]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18392) Allow exporting circulation conditions as CSV or spreadsheet

## Command-line Utilities

- [[30893]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30893) Typo: update_patrons_category.pl fine(s)
- [[30781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30781) Use of uninitialized value $val in substitution iterator at /usr/share/koha/lib/C4/Letters.pm line 665.
- [[10517]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10517) koha-restore fails to create mysqluser@mysql_hostname so zebra update fails

## Course reserves

- [[30840]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30840) Add support for barcode filters to course reserves

## Database

- [[30572]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30572) Field search_marc_to_field.sort needs syncing too
- [[30620]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30620) Add a warning close to /*!VERSION lines in kohastructure.sql
- [[30449]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30449) Missing FK constraint on borrower_attribute_types
- [[30565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30565) Field stockrotationrotas.description should be NOT NULL, title UNIQUE

## Fines and fees

- [[30346]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30346) Editing circ rule with Overdue fines cap (amount) results in data loss and extra fines

## Hold requests

- [[30828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30828) Remove unused variable in placerequest.pl
- [[30742]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30742) Confusion when placing hold on record with no items available because of not for loan
- [[30630]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30630) Checking in a waiting hold at another branch when HoldsAutoFill is enabled causes errors

## Installation and upgrade (command-line installer)

- [[30366]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30366) Warn when running automatic_item_modification_by_age.pl

## Installation and upgrade (web-based installer)

- [[20449]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20449) Noise triggered by Archive::Extract during installation

## Label/patron card printing

- [[24001]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24001) Cannot edit card template

## Notices

- [[30354]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30354) AUTO_RENEWALS_DGST notices are not generated if patron set to receive notice via SMS and no SMS notice defined
- [[30509]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30509) Accordion on letter.tt is broken

## OPAC

- [[30844]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30844) The OPAC detail page's browser is limited to the current page of results when using Elasticsearch
- [[30746]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30746) JS error on 'your personal details' in OPAC
- [[28955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28955) Add option to set default branch from Apache
- [[30191]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30191) Authority search result list in the OPAC should use 'record' instead of 'biblios'

## Patrons

- [[30868]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30868) Modifying a patron - page not found error after fixing validation errors where the message is displayed at the top of the page
- [[29617]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29617) BorrowerUnwantedField should exclude the ability to hide categorycode
- [[30405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30405) Style of address in patron search result are 110%

## Plugin architecture

- [[30072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30072) Add more holds hooks

## Reports

- [[30551]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30551) Cash register report shows wrong library when paying fees in two different libraries

## REST API

- [[30663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30663) POST /api/v1/suggestions won't honor suggestions limits
- [[30534]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30534) borrowers.guarantorid not present on database

## Searching

- [[27697]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27697) Opening bibliographic record page prepopulates search bar text

## Searching - Elasticsearch

- [[29077]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29077) Warns when searching blank index

## Searching - Zebra

- [[30528]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30528) Limits are not correctly parsed when query contains CCL

## Serials

- [[30204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30204) Add subtitle to serial subscription search

## Staff Client

- [[28723]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28723) Holds table not displayed when it contains a biblio without title
- [[30610]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30610) The 'Print receipt' button on cash management registers page fails on second datatables page
- [[29092]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29092) Table settings for account_fines table is missing Updated on column and hides the wrong things

## System Administration

- [[30862]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30862) Typo: langues
- [[30597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30597) Update wording of RestrictionBlockRenewing to include auto-renew

## Templates

- [[30726]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30726) Flatpickr's "yesterday" shortcut doesn't work if entry is limited to past dates
- [[30523]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30523) Quiet console warning about missing shortcut-buttons map file
- [[30721]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30721) Markup error in detail page's component parts tab
- [[30587]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30587) Incorrect translations in some templates

## Test Suite

- [[30756]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30756) Get skip block out of Koha_Authority.t and add TestBuilder
- [[29860]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29860) Useless warnings in regressions.t
- [[30870]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30870) Don't skip tests if Test::Deep is not installed
- [[30595]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30595) update_child_to_adult.t is failing randomly
- [[30531]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30531) Search.t needs update for Recalls

## Tools

- [[30884]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30884) Incomplete replace of jQuery UI tabs in batch patron modification breaks the form sending
- [[30831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30831) Add unit test for BatchCommitItems
- [[28152]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28152) Hidden error when importing an item with an existing itemnumber
- [[29828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29828) If no content is added to default, but a translation, news/additional content entries don't show in list
- [[30628]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30628) Batch borrower modifications only affect the current page
- [[30461]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30461) Batch authority tool is broken
- [[30518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30518) StockRotationItems crossing DST boundary throw invalid local time exception

## Web services

- [[22379]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22379) ILS-DI Method "CancelHold" doesn't check CanReserveBeCanceledFromOpac


