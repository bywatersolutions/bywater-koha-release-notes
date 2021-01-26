
# Release Notes for masscat-v20.05.08-01

## Acquisitions

- [[24470]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24470) Set import_status when file used to populate basket in acquisitions

## Architecture, internals, and plumbing

- [[26848]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26848) Fix Readonly dependency in cpanfile
- [[25292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25292) L1 cache too long in Z3950 server (z3950-responder)
- [[27345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27345) C4::Auth::get_template_and_user is missing some permissions for superlibrarian
- [[27252]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27252) ES5 no longer supported (since 20.11.00)

## Cataloging

- [[27509]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27509) cn_sort value is lost when editing an item without changing cn_source or itemcallnumber
- [[27164]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27164) Fix item search CSV export
- [[26330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26330) jQueryUI tabs don't work with non-Latin-1 characters
- [[27137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27137) Move item doesn't show the title of the target record

## Command-line Utilities

- [[26851]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26851) Overdue notices should not send a report to the library if there is no content
- [[27245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27245) bulkmarcimport.pl error 'Already in a transaction'
- [[27085]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27085) Corrections in overdue_notices.pl help text

## Database

- [[27003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27003) action_logs table error when adding an item
- [[25826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25826) Hiding biblionumber in the frameworks breaks links in result list

## Fines and fees

- [[27180]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27180) Fines cronjob does not update fines on holidays when finesCalendar is set to ignore
- [[26593]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26593) Rental discounts are applied in wrong precedence order

## Hold requests

- [[26698]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26698) Hold can show as waiting and in transit at the same time

## Label/patron card printing

- [[26875]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26875) Allow printing of just one barcode

## MARC Bibliographic record staging/import

- [[26171]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26171) Show biblionumber in Koha::Exceptions::Metadata::Invalid

## OPAC

- [[27090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27090) In the location column of an OPAC cart the 'In transit from' and 'to' fields are empty
- [[26397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26397) opac.scss calls non-existent image
- [[27178]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27178) OPAC results and lists pages contain invalid attributes (xmlns:str="http://exslt.org/strings")

## Patrons

- [[27420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27420) A mistake in bug 5161 leads to some patron attributes appearing without a fieldset
- [[26417]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26417) Remove warn in Koha::Patron is_valid_age

## Searching - Elasticsearch

- [[24863]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24863) QueryFuzzy syspref says it requires Zebra but Elasticsearch has some support
- [[26996]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26996) Elasticsearch: Multiprocess reindexing sometimes doesn't reindex all records
- [[27043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27043) Add to number_of_replicas and number_of_shards  to index config

## SIP2

- [[27196]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27196) Waiting title level hold checked in at wrong location via SIP leaves hold in a broken state and drops connection

## Staff Client

- [[25462]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25462) Shelving location should be on a new line in holdings table

## System Administration

- [[27280]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27280) Explanation for "Days mode" is not consistent
- [[27349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27349) Mana system preference wrong type YesNo
- [[27351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27351) UsageStatsCountry system preference wrong type YesNo

## Templates

- [[25954]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25954) Header search forms should be labeled

## Test Suite

- [[26364]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26364) XISBN.t makes a bad assumption about return values

## Tools

- [[27413]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27413) Cannot add debarment with batch patron modification tool
- [[26894]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26894) Marc Modification Templates treat subfield 0 as no subfield set when moving fields
- [[26983]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26983) Selecting ALL Items in Inventory- only selects 20

## Web services

- [[21301]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21301) Restriction of the informations given by GetRecords ILS-DI service

## Z39.50 / SRU / OpenSearch Servers

- [[27149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27149) Z3950Responder removes itemnumber when adding item statuses


