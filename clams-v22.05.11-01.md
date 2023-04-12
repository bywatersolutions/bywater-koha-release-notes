
# Release Notes for clams-v22.05.11-01

## Architecture, internals, and plumbing

- [[32580]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32580) Background job cancel button broken, leads to background_jobs.pl with a kc
- [[32558]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32558) Allow background_jobs_worker.pl to process multiple jobs simultaneously up to a limit
- [[32678]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32678) Add new line in authorized values tests in search_for_data_inconsistencies.pl
- [[32811]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32811) Remove unused indexer.log
- [[33044]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33044) BackgroundJob enqueue does not return the job id if rabbit is unreachable
- [[32460]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32460) Columns missing from table configuration for patron categories

## Bywater Only

- NOT IN BUGZILLA - Remove t/db_dependent/selenium/patrons_search.t for now

## Cataloging

- [[33173]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33173) Save and continue button in standard cataloging module broken
- [[32819]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32819) Fix cataloguing/value_builder/stocknumberam123.pl
- [[32815]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32815) Fix cataloguing/value_builder/callnumber.pl
- [[32824]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32824) Fix cataloguing/value_builder/unimarc_field_100.pl
- [[32835]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32835) Fix cataloguing/value_builder/unimarc_field_122.pl
- [[32829]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32829) Fix cataloguing/value_builder/unimarc_field_115b.pl
- [[32828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32828) Fix cataloguing/value_builder/unimarc_field_115a.pl
- [[32827]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32827) Fix cataloguing/value_builder/unimarc_field_110.pl
- [[32825]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32825) Fix cataloguing/value_builder/unimarc_field_105.pl
- [[32826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32826) Fix cataloguing/value_builder/unimarc_field_106.pl
- [[32823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32823) Fix cataloguing/value_builder/unimarc_field_100_authorities.pl
- [[32822]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32822) Fix cataloguing/value_builder/unimarc_field_010.pl
- [[32820]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32820) Fix cataloguing/value_builder/stocknumberAV.pl
- [[32816]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32816) Fix cataloguing/value_builder/cn_browser.pl
- [[32821]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32821) Fix cataloguing/value_builder/stocknumber.pl
- [[32814]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32814) Fix cataloguing/value_builder/callnumber-KU.pl
- [[32812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32812) Fix cataloguing/value_builder/barcode_manual.pl
- [[32813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32813) Fix cataloguing/value_builder/barcode.pl

## Circulation

- [[32878]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32878) Make it impossible to renew the item if it has active item level hold
- [[31209]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31209) Add a span with class around serial enumeration/chronology data in list of checkouts for better styling

## I18N/L10N

- [[30993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30993) Translation: Unbreak sentence in upload.tt
- [[31957]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31957) Translation: Ability to change the sentence structure on library administration page

## ILL

- [[32525]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32525) Standardize labels between ILL request list and detail page
- [[32566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32566) Don't show 'ILL request logs' button, when IllLog is turned off
- [[22693]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22693) ILL "Price paid" column does not appear in column configuration

## OPAC

- [[32492]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32492) Improve mark-up of OPAC messaging table to ease customization
- [[32679]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32679) CSS class article-request-title is doubled up in article requests list in staff patron account
- [[32663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32663) Street number should not allow for entering more than 10 characters in OPAC
- [[31248]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31248) Fix responsive table style in the OPAC after switch to Bootstrap tabs
- [[32999]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32999) Click handler to show QR code in OPAC lacks preventDefault

## Patrons

- [[32675]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32675) Cannot add a guarantor when there is a single quote in the guarantor attributes
- [[33155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33155) Category and library filters from header patron search not taken into account
- [[32770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32770) Patron search field groups no longer exist

## Plugin architecture

- [[33189]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33189) Plugin upload should prompt for .kpz files

## Searching

- [[32639]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32639) OpenSearch description format document generates search errors

## Searching - Elasticsearch

- [[31471]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31471) Duplicate check in cataloguing fails with Elasticsearch for records with multiple ISBN

## SIP2

- [[33055]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33055) SIP2 adding incorrect fines blocked message

## Staff interface

- [[33032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33032) Alternate holdings broken in staff interface search results
- [[32982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32982) 'Add/Edit group' modals in library groups is missing it's primary button
- [[32909]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32909) Item type icons broken when placing an item-level hold

## Templates

- [[32205]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32205) Unnecessary sysprefs used in template params for masthead during failed OPAC auth
- [[33048]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33048) Empty email link on error page when opac login not allowed
- [[32926]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32926) Cannot expand or collapse some System preference sections after a search
- [[31413]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31413) Set focus for cursor to Selector when adding a new audio alert
- [[32933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32933) Use val() instead of attr("value") when getting field values with jQuery
- [[32307]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32307) Chocolat image viewer broken in the staff interface when Coce is enabled

## Test Suite

- [[32375]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32375) 22.05.07 failing t/AuthoritiesMarc_MARC21.t
- [[32979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32979) Add Test::Exception to Logger.t

## Tools

- [[32804]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32804) Importing and replacing items causes inconsistency when itemnumber match and biblio match disagree
- [[32685]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32685) Display incorrect when matching authority records during import


