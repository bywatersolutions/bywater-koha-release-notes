
# Release Notes for montgomery-v23.05.09-01

## About

- [[35504]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35504) Release team 24.05

## Accessibility

- [[34647]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34647) name attribute is obsolete in anchor tag
- [[35894]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35894) Duplicate link in booksellers.tt

## Acquisitions

- [[33457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33457) Improve display of fund users when the patron has no firstname

## Architecture, internals, and plumbing

- [[35918]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35918) Incorrect library used when AutoLocation configured using the same IP
- [[36092]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36092) sessionID not passed to the template on auth.tt
- [[35890]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35890) AutoLocation system preference + setting the library IP field - can still login and unexpected results
- [[35701]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35701) Cannot use i18n.inc from memberentrygen
- [[35835]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35835) Fix shebang for cataloguing/ysearch.pl
- [[35843]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35843) No such thing as Koha::Exceptions::Exception
- [[35702]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35702) Reduce DB calls when performing authorities merge
- [[34999]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34999) REST API: Public routes should respect OPACMaintenance

## Authentication

- [[29930]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29930) 'cardnumber' overwritten with userid when not mapped (LDAP auth)

## Bywater Only

- NOT IN BUGZILLA - Bug 35942: OPAC user can enroll several times to the same club [23.05.x]
- NOT IN BUGZILLA - Bug 29510: (Rmaint follow-up) fix number of tests
- NOT IN BUGZILLA - Bug 34623: Update jQuery-validate plugin to 1.20.0
- NOT IN BUGZILLA - Bug 36072: opac-request-article should check syspref

## Cataloging

- [[35695]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35695) Remove useless item group code from cataloging_additem.js
- [[35774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35774) add_item_to_item_group additem.pl should be $item->itemnumber instead of biblioitemnumber
- [[33639]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33639) Adding item to item group from 'Add item' screen doesn't work

## Circulation

- [[35518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35518) Call to C4::Context->userenv happens before it's gets populated breaks code logic in circulation
- [[35360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35360) Inconsistent use/look of 'Cancel hold(s)' button on circ/waitingreserves.pl
- [[35341]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35341) Circulation rule dates are being overwritten

## Command-line Utilities

- [[35596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35596) Error in writeoff_debts documentation
- [[35373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35373) Remove comment about bug 8000 in gather_print_notices.pl
- [[30627]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30627) koha-run-backups delete the backup files after finished its job without caring days option

## Documentation

- [[35354]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35354) Update emailLibrarianWhenHoldisPlaced system preference description

## Hold requests

- [[35322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35322) AllowItemsOnHoldCheckoutSCO and AllowItemsOnHoldCheckoutSIP do not work

## Installation and upgrade (command-line installer)

- [[34979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34979) System preferences missing from sysprefs.sql

## OPAC

- [[35663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35663) Wording on OPAC privacy page is misleading

## Packaging

- [[25691]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25691) Debian packages point to /usr/share/doc/koha/README.Debian which does not exist

## Patrons

- [[34479]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34479) Clear saved patron search selections after certain actions
- [[35756]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35756) Wrong use of encodeURIComponent in patron-search.inc

## Searching - Elasticsearch

- [[35086]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35086) Koha::SearchEngine::Elasticsearch::Indexer->update_index needs to commit in batches

## SIP2

- [[35461]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35461) Renew All 66 SIP server response messages produce HASH content in replies

## Staff interface

- [[35865]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35865) Missing hint about permissions when adding managers to a basket
- [[32477]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32477) Hiding batch item modification columns isn't remembered correctly

## System Administration

- [[35510]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35510) Non-patron guarantor missing from CollapseFieldsPatronAddForm  options

## Templates

- [[35474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35474) Add icon for protected patrons

## Test Suite

- [[35904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35904) C4::Auth::checkauth cannot be tested easily
- [[35507]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35507) Fix handling plugins in unit tests causing random failures on Jenkins
- [[35962]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35962) t/db_dependent/Koha/BackgroundJob.t failing on D10

## Tools

- [[35817]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35817) Wrong hint on patron's category when batch update patron
- [[35641]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35641) Reduce DB calls when performing inventory on a list of barcodes
- [[35438]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35438) Importing records can create too large transactions

## Web services

- [[34893]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34893) ILS-DI can return the wrong patron for AuthenticatePatron
- [[34950]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34950) ILS DI Availability is not accurate for items on holds shelf or in transit


