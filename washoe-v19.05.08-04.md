
# Release Notes for washoe-v19.05.08-04

## SIP2

- [[24966]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24966) Fix calls to maybe_add where method call does not return a value
- [[21979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21979) Add option to SIP2 config to send arbitrary item field in CR instead of collection code



# Release Notes for washoe-v19.05.08-02

## Circulation

- [[24802]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24802) Updating holds can cause suspensions to apply to wrong hold



# Release Notes for washoe-v19.05.08-01

## Acquisitions

- [[9993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=9993) On editing basket group delivery place resets to logged in library
- [[22868]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22868) Circulation staff with suggestions_manage can have access to acquisition data
- [[17667]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17667) Standing orders - cancelling a receipt increase the original quantity
- [[24404]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24404) Add missing space on invoices page
- [[24277]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24277) Date Received in acquisitions cannot be changed

## Architecture, internals, and plumbing

- [[23290]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23290) XSLT system preferences allow administrators to exploit XML and XSLT vulnerabilities
- [[24213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24213) Koha::Object->get_from_storage should return undef if the object has been deleted
- [[23896]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23896) logaction should pass the correct interface to Koha::Logger
- [[23407]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23407) XSLT Details pages don't use items, we shouldn't pass them
- [[22220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22220) Error in ReWriteRule for 'bib' in apache-shared-intranet.conf
- [[24313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24313) XSLT errors should show in the logs
- [[24016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24016) manager_id in Koha::Patron::Message->store should not depend on userenv alone

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Prune Docker images
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Bug 24333: Add password class to AutoSelfCheck syspref

## Cataloging

- [[16683]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16683) Help links to fields 59X in cataloguing form are broken
- [[24452]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24452) Advanced editor - show multiple spaces visually
- [[24236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24236) Using quotes in a cataloging search, resulting in multiple pages, will not allow you to advance page
- [[24423]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24423) Broken link to return to record after batch item modification or deletion
- [[24323]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24323) Advanced editor - Invalid 008 with helper silently fails to save

## Circulation

- [[24214]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24214) Due date displayed in ISO format (when sticky)
- [[23233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23233) AllowItemsOnHoldCheckout is misnamed and should only work for for SIP-based checkouts

## Command-line Utilities

- [[24511]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24511) Patron emailer report not using specified email column
- [[24105]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24105) Longoverdue gives error message when --itemtypes are specified

## Database

- [[24289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24289) Deleting branch will not delete entry in special or repeatable holidays
- [[24377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24377) Record branch in statistics for auto-renewal

## Fines and fees

- [[24637]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24637) Pay selected & Pay amount does not log branchcode in 19.05
- [[23443]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23443) Paying off a lost fee will return the item, even if it is checked out to a different patron

## Hold requests

- [[21296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21296) Suspend hold ignores system preference on intranet
- [[20567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20567) "Holds per record (count)" limit is not enforced after item is captured for hold

## I18N/L10N

- [[23790]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23790) fr-CA translation of ACCOUNT_DEBIT and ACCOUNT_CREDIT notices

## MARC Authority data support

- [[24421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24421) Generated authorities are missing subfields

## MARC Bibliographic record staging/import

- [[24348]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24348) Record matching rules: required match checks does not work

## OPAC

- [[22302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22302) ITEMTYPECAT description doesn't fall back to description if OPAC description is empty
- [[24523]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24523) Fix opac-password-recovery markup mistake
- [[17697]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17697) Improve NotesBlacklist system preference description to make clear where it will apply
- [[24486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24486) Account Wording Information is duplicated in Patron's Fines Tab on OPAC
- [[24061]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24061) Print List (opac-shelves.pl) broken in Chrome
- [[24206]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24206) Change URLs for default options in OPACSearchForTitleIn
- [[23528]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23528) Show 'log in to add tags' link on all search result entries
- [[24371]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24371) OPAC 'Showing only available items/Show all items' is double encoded

## Patrons

- [[14759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14759) Replacement for Text::Unaccent

## Plugin architecture

- [[22835]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22835) Serve static files from plugins through the API
- [[22834]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22834) Add a method for plugins to return the absolute path for bundled files

## Searching

- [[10879]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10879) OverDrive should check for OverDriveLibraryID before performing search
- [[24443]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24443) Consider NULL as 0 for issues in items search
- [[15142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15142) Titles facet does not work in UNIMARC

## Searching - Elasticsearch

- [[23676]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23676) Elasticsearch - 0 is not a valid boolean for suppress
- [[22426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22426) Elasticsearch - Index location is missing in advanced search
- [[17885]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17885) Koha::SearchEngine::Elasticsearch->reset_elasticsearch_mappings throws DBD::mysql Duplicate entry exceptions
- [[24123]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24123) bulkmarcimport.pl doesn't support UTF-8 encoded MARCXML records

## Serials

- [[23064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23064) Cannot edit subscription with strict SQL modes turned on

## SIP2

- [[20292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20292) Filter/censor info sent via SIP

## Staff Client

- [[24515]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24515) Column Configuration for pay-fines-table does not hide Account Type properly

## System Administration

- [[24025]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24025) Make CodeMirror content searchable
- [[24329]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24329) Patron cardnumber change times are lost during upgrade for bug 3820

## Templates

- [[24054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24054) Typo in ClaimReturnedWarningThreshold system preference
- [[23947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23947) Phase out jquery.cookie.js: Authority merge
- [[23944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23944) Phase out use of jquery.cookie.js in favor of js.cookie.js
- [[23113]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23113) members/pay.tt account_grp is not longer used
- [[24391]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24391) Remove event attributes from patron clubs edit template

## Test Suite

- [[24543]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24543) Wrong test in api/v1/checkouts.t
- [[23274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23274) t/db_dependent/XISBN.t fails with Elasticsearch

## Tools

- [[24497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24497) CodeMirror indentation problems
- [[24275]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24275) Inventory table should be sortable by title without leading articles (allow for title sort with anti-the)
- [[24484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24484) Add explanatory text to batch patron deletion
- [[23377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23377) bulkmarcimport.pl disables syspref caching
- [[10352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10352) Cataloguing log search mixing itemnumber/bibnumber



# Release Notes for washoe-v19.05.07-04

## Searching - Elasticsearch

- [[23719]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23719) Record matching for authorities using defined fields is broken under ES



# Release Notes for washoe-v19.05.07-03

## SIP2

- [[24705]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24705) Holds placed via SIP will be given first priority



# Release Notes for washoe-v19.05.07-02

## SIP2

- [[24566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24566) UpdateItemLocationOnCheckin triggers SIP2 alert flag, even with checked_in_ok enabled


