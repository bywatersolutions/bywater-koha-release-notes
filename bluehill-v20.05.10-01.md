
# Release Notes for bluehill-v20.05.10-01

## Acquisitions

- [[27813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27813) Purchase suggestions should sort by suggesteddate rather than title
- [[23929]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23929) Invoice adjustments should filter inactive funds
- [[27828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27828) New order from staged file is broken
- [[27794]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27794) Add link to biblio in lateorders page
- [[23675]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23675) UseACQFrameworkForBiblioRecords default framework is missing LDR breaking encoding
- [[26997]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26997) Database Mysql Version 8.0.22 failed to Update During Upgrade

## Architecture, internals, and plumbing

- [[27680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27680) API DataTables Wrapper fails for ordering on multi-data-field columns
- [[27821]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27821) sanitize_zero_date does not handle datetime
- [[27714]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27714) Koha::NewsItem->author explodes if the author has been removed

## Bywater Only

- NOT IN BUGZILLA - Minor bug fix to get t/db_dependent/selenium/basic_workflow.t to pass
- NOT IN BUGZILLA - Translation fixes for 20.05.10
- NOT IN BUGZILLA - Revert "DBRev 20.05.09.001"

## Cataloging

- [[26964]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26964) Advanced editor no longer selects newly created macros
- [[27578]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27578) Searchid not initialized when adding a new record
- [[25777]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25777) Datatables on z3950_search.pl show incorrect number of entries

## Circulation

- [[27808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27808) Item's onloan column remains unset if a checked out item is issued to another patron without being returned first
- [[26457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26457) DB DeadLock when renewing checkout items
- [[26208]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26208) Overdues restrictions not consistently removed when renewing multiple items at once

## Database

- [[7806]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7806) Don't use 0000-00-00 to signal a non-existing date

## Hold requests

- [[27071]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27071) Hold pickup library match not enforced correctly on intranet when using hold groups
- [[27729]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27729) Code around SkipHoldTrapOnNotForLoanValue contains two perl bugs

## Holidays

- [[27835]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27835) Closed days offsets with one day

## I18N/L10N

- [[27815]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27815) "Remove" in point of sale untranslatable

## OPAC

- [[27650]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27650) Wrong variable passed to the template in opac-main
- [[24398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24398) Error when viewing single news item and NewsAuthorDisplay pref set to OPAC
- [[27626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27626) Patron self-registration breaks if categorycode and password are hidden

## Patrons

- [[27933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27933) Order patron search broken (dateofbirth, cardnumber, expirationdate)

## REST API

- [[27593]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27593) Inconsistent return status on club holds routes
- [[27330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27330) Wrong return status when no enrollments in club holds

## Searching

- [[27745]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27745) Use of uninitialized value in hash element error at C4/Search.pm

## Searching - Elasticsearch

- [[27597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27597) Searching "kw:term" does not work with Elasticsearch
- [[24567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24567) Elasticsearch: CCL syntax does not allow for multiple indexes to be searched at once
- [[27784]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27784) Unknown authority types break elasticsearch authorities indexing
- [[26051]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26051) Elasticsearch uses the wrong field for callnumber sorting

## Searching - Zebra

- [[8426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8426) Map  ︡a to a and t︠ to t for searching (Non-ICU)

## Serials

- [[27332]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27332) When renewing a serial subscription, show note and library only if RenewSerialAddsSuggestion is used

## SIP2

- [[27014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27014) SIP2 cannot find patrons at checkin

## Staff Client

- [[27776]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27776) Point of Sale 'This sale' table should not be sorted by default

## System Administration

- [[27703]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27703) Can't navigate in Authorized values
- [[27798]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27798) Independent branches should have a warning
- [[27713]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27713) Duplicate search field IDs in MARC framework administration template

## Templates

- [[27795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27795) Misalignment of TOTAL value in lateorders page
- [[27752]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27752) Correct ESLint errors in batchMod.js
- [[27754]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27754) Correct eslint errors in basket.js


