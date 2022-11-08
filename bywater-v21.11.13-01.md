
# Release Notes for bywater-v21.11.13-01

## Acquisitions

- [[23202]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23202) Problems when adding multiple items to an order in acquisitions
- [[30658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30658) (Bug 29496 follow-up) CheckMandatorySubfields don't  work properly with select field in serials-edit.tt for Supplemental issue
- [[30268]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30268) When creating an order from a staged file, mandatory item subfields that are empty do not block form submission
- [[31144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31144) When modifying an order we should not load the vendor default discount
- [[14680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14680) When creating orders from a staged file discounts supplied in the form are added

## Architecture, internals, and plumbing

- [[31390]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31390) Remove noisy warns in C4::Templates
- [[31222]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31222) DBIC queries for batch mod can be very large
- [[31245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31245) Job detail view for batch mod explode if job not started
- [[27849]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27849) Koha::Token may access undefined C4::Context->userenv
- [[30984]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30984) Action logs should log the cronjob script name that generated the given log
- [[30468]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30468) koha-mysql does not honor Koha's timezone setting
- [[31145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31145) Add some defaults for acquisitions in TestBuilder

## Bywater Only

- NOT IN BUGZILLA - Remove invalid unit tests, fix executables
- NOT IN BUGZILLA - Fix translations for Koha 21.11.13
- NOT IN BUGZILLA - Fix translations for Koha 21.11.12

## Cataloging

- [[30797]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30797) Subfields linked to the dateaccessioned.pl value builder on addbiblio.pl throw a JS error
- [[30909]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30909) Regression, Permanent shelving location is always updated when editing location VIA ADDITEM.PL if both are mapped to MARC fields
- [[27683]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27683) Bind results of GetAnalyticsCount to the EasyAnalyticalRecords pref

## Circulation

- [[29012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29012) Some rules are not saved when left blank while editing a 'rule' line in smart-rules.pl
- [[31120]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31120) Items will renew for zero ( 0 ) days if renewalperiod is blank/empty value
- [[30447]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30447) pendingreserves.pl is checking too many transfers
- [[31129]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31129) Number of restrictions is always "0" on the "Check out" tab
- [[29051]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29051) Seen renewal methods incorrectly blocked

## Command-line Utilities

- [[31282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31282) Broken characters in patron_emailer.pl verbose mode
- [[29325]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29325) commit_file.pl error 'Already in a transaction'
- [[31325]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31325) Fix koha-preferences get
- [[31155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31155) Document --since option in help of borrowers-force-messaging-defaults.pl
- [[30308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30308) bulkmarcimport.pl broken by OAI-PMH:AutoUpdateSets(EmbedItemData)

## Fines and fees

- [[31121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31121) Format date range on top of cashup summary page
- [[30458]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30458) Librarian ( manager_id ) not included in accountline when using "Payout amount" button
- [[31163]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31163) Sort cashup history so that newest entries are first
- [[31036]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31036) Cash management doesn't take SIP00 (Cash via SIP2) transactions into account

## Hold requests

- [[19540]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19540) opac-reserve does not correctly warn of too_much reserves
- [[30878]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30878) Canceling holds from 'Holds awaiting pickup' should not reset the selected tab
- [[31086]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31086) Do not allow hold requests with no branchcode
- [[30935]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30935) Holds to pull shows wrong first patron

## I18N/L10N

- [[31292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31292) Untranslatable string in sample_notices.yaml
- [[30028]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30028) Patron message delete confirmation untranslatable
- [[28707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28707) Missing strings in translation of sample data

## Installation and upgrade (command-line installer)

- [[31673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31673) DB update of bug 31086 fails: Cannot change column 'branchcode': used in a foreign key constraint

## Label/patron card printing

- [[31352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31352) Terminology: Borrower name
- [[31137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31137) Error editing label template

## Lists

- [[29114]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29114) Can not add barcodes with whitespaces at the beginning to the list

## MARC Authority data support

- [[29434]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29434) In UNIMARC instances, the authority finder uses MARC21 relationship codes
- [[29333]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29333) Importing UNIMARC authorities in MARCXML UTF-8 breaks the encoding

## MARC Bibliographic record staging/import

- [[26632]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26632) BatchStageMarcRecords passes a random number to AddBiblioToBatch / AddAuthToBatch

## Notices

- [[31281]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31281) Overdue notices reply-to email address of a branch not respected
- [[26689]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26689) Monetary accounts notices should be definable at the credit_type/debit_type level
- [[30838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30838) to_address is misleading for SMS transports

## OPAC

- [[31387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31387) Marking othernames as required via PatronSelfRegistrationBorrowerMandatoryField does not display required label
- [[31217]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31217) Fix Coce JavaScript to hide single-pixel cover images in the OPAC lightbox gallery
- [[29782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29782) Additional contents: Fix handling records without title or content
- [[31294]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31294) Article requests: Mandatory subfields in OPAC don't show they are required
- [[31346]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31346) On the OPAC detail page some Syndetics links are wrong
- [[31272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31272) Show library name not code when placing item level holds in OPAC
- [[31186]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31186) Search result numbering in OPAC got suppressed
- [[29922]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29922) Group of libraries are now displayed in alphabetical order

## Packaging

- [[31348]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31348) Plack stop should be graceful
- [[31499]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31499) Add libhttp-tiny-perl 0.076 dependency for ES7

## Patrons

- [[7660]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7660) Enhanced messaging preferences are not set when creating a child patron from the adult
- [[20439]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20439) SMS provider sorting

## Reports

- [[31276]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31276) Report results are limited to 999,999 no matter the actual number of results
- [[21982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21982) Circulation statistics wizard does not count deleted items
- [[27045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27045) Exports using CSV profiles with tab as separator don't work correctly

## REST API

- [[29105]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29105) Add effective_item_type_id to the API items responses

## Searching

- [[22605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22605) Adding the option to modify/edit searches on the staff interface
- [[31213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31213) When performing a basic search with no results, repeat the search with term quoted

## Searching - Elasticsearch

- [[31076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31076) Bug 22605 breaks date of publication range search
- [[27667]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27667) Display the number of non-indexed records
- [[30882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30882) Add max_result_window to index config
- [[25669]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25669) ElasticSearch 6: [types removal] Specifying types in put mapping requests is deprecated (incompatible with 7)

## SIP2

- [[31033]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31033) SIP2 configuration does not correctly handle multiple simultaneous connections by default
- [[31202]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31202) Koha removes optional SIP fields with a value of "0"

## Staff Client

- [[28864]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28864) The patron search results in the patron card creator doesn't seem to use PatronsPerPage syspref
- [[31251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31251) "Clear" patron attribute link does not work
- [[31138]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31138) DataTables is not raising error to the end user
- [[30471]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30471) Typo in circulation rules - lost item fee refund policy
- [[31039]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31039) Rebase issues lead to duplicate JS for cash summary modal printing

## System Administration

- [[31289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31289) Hide Article requests column in circulation rules when ArticleRequests syspref is disabled
- [[31249]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31249) update_patrons_category.pl cron does not log to action_logs
- [[31020]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31020) PassItemMarcToXSLT only applies on results pages

## Templates

- [[31425]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31425) Minor correction to patron categories admin title
- [[31228]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31228) Fix Coce JavaScript to hide single-pixel cover images in both the staff client detail and results pages
- [[31302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31302) Spelling: You can download the scanned materials via the following url(s):
- [[31141]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31141) We can remove 'select_column' from waiting_holds.inc

## Test Suite

- [[31201]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31201) Pseudonymization.t failing if selenium/patrons_search.t failed before
- [[31139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31139) basic_workflow.t is failing

## Tools

- [[28327]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28327) System preference CSVdelimiter special case for tabulation
- [[30779]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30779) Do not need to remove items from import biblios marc
- [[31455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31455) Batch modification tool orders found items by itemnumber
- [[31204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31204) Edit dropdown on results.tt should indicate it is record modification


