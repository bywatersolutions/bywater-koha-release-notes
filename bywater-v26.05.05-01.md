
# Release Notes for bywater-v26.05.05-01

## Accessibility

- [[42235]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42235) On OPAC messaging preferences page table header contains no text

## Acquisitions

- [[43787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43787) Adding orders from a staged file ( addorderiso2709.pl ) can use gigabytes of memory if there are many funds
- [[39959]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39959) Add total amount column to invoice search results
- [[34166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34166) Show total price in table of suggestions
- [[42789]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42789) EDI ORDRSP: Item and suggestion status not updated when order line cancelled by supplier
- [[43793]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43793) 26.05.04 backport of bug 42605 is incomplete

## Architecture, internals, and plumbing

- [[43330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43330) C4::Tags fails to compile when TagsExternalDictionary is configured
- [[42924]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42924) Restore default MaxAge for CSRF token
- [[43092]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43092) Koha::File::Transport::change_directory(undef) means three different things across FTP, SFTP and Local

## Authentication

- [[43375]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43375) OAuth userinfo_url silently fails to parse JSON when Content-Type has extra parameters (e.g. Microsoft Graph)

## Cataloging

- [[32748]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32748) Library limitations will cause data loss when editing items
- [[35104]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35104) We should warn when attempting to save MARC records that contain characters invalid in XML
- [[43239]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43239) Serial items item type can be set incorrectly when receiving multiple items

## Circulation

- [[42697]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42697) Home library and current library filters can filter incorrectly

## Command-line Utilities

- [[35061]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35061) Fix documentation for --preserve-field in import_patrons.pl

## Hold requests

- [[43634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43634) cancelBulk in waitingreserves.pl is not protected against CSRF attacks
- [[43378]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43378) Wrong hold can be selected when LocalHoldsPriority set to GiveLibraryAndGroup
- [[43072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43072) fill_other_biblio_holds_policy values display incorrectly in circ rules page

## I18N/L10N

- [[43260]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43260) Debug options in navigation bar untranslatable
- [[41842]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41842) Improve translation of course reserves headings

## ILL

- [[43354]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43354) ILL request table search returns a 500 error
- [[43204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43204) ILL availability search: Source column links to plain OPAC URL instead of the deep link

## Notices

- [[40294]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40294) Mandatory patron expiration notice is not sent if patron does not have a primary contact method defined
- [[43342]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43342) Default OVERDUES_SLIP contains empty lines

## OPAC

- [[30319]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30319) Patron self-modification values not retained if field blocked in PatronSelfRegistrationBorrowerUnwantedField
- [[39589]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39589) Search returns 'No results found' despite existing matching records
- [[42634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42634) Self-checkout Finish/logout does not reliably clear the JWT cookie
- [[41706]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41706) "Use of uninitialized value..." warning in C4/Record.pm
- [[20846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20846) Suppressed records still appear in public lists
- [[41197]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41197) opac/opac-account-pay-return.pl should not require CSRF
- [[40799]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40799) Loading spinner not removed because .cover-slider is now used instead of .cover-slides

## Patrons

- [[43672]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43672) When a patron has no advance notices value and their category is changed to one with a value the checkboxes are not enabled
- [[43245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43245) There should be a message in the staff interface if a patron has no email address and you reset their password (More > Send password reset)
- [[42112]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42112) Add option when changing a patron's category: allow choosing what to do for the expiry date and messaging preferences
- [[42018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42018) Inconsistent behavior for null values for fields selected in PatronDuplicateMatchingAddFields

## Plugin architecture

- [[41648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41648) Incorrect 'update_date' breaks the plugins home page

## Reports

- [[43249]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43249) A duplicate report limit of 1 prevents users from running reports at all
- [[42451]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42451) "convert" op in guided_reports.pl is broken due to JS error

## REST API

- [[43196]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43196) PUT requests with a bad request body to biblios endpoint blanks a record

## Searching

- [[42946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42946) [CVE-2026-16031] Time-based Blind SQL Injection in itemsearch.pl functionality

## Searching - Elasticsearch

- [[39769]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39769) es_indexer_daemon.pl uses stale L1 cache

## SIP2

- [[40800]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40800) TransferArrived needlessly triggers alerts in SIP
- [[42700]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42700) In C4/SIP/ILS/Patron.pm, hold_items only counts waiting holds

## Staff interface

- [[43373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43373) Holdings table always displays the shelving location column
- [[42727]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42727) Languages displayed in random order in language menu
- [[42661]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42661) Redudant repetition in "Patron: %s Patron's home library: (%s /%s )" when HidePatronName is activated
- [[43331]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43331) No class on collection code in holdings table on bib detail
- [[43313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43313) Item's permanent location not shown when item's location is set to CART
- [[42656]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42656) File transport test responses can be unclear

## System Administration

- [[43336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43336) Remove support for LibrisSpellcheck

## Templates

- [[43707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43707) Fix stored XSS in DT's column filters in staff interface
- [[43429]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43429) Stored XSS via OPAC Report a Problem executes in staff/intranet security context (8.7 HIGH)
- [[43570]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43570) Memory leak in SafeURL and HtmlScrubber Template::Toolkit filters

## Test Suite

- [[43339]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43339) automatic_item_modification_by_age_configuration is not a real system preference
- [[43203]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=43203) Item.t doesn't clean up after itself correctly


