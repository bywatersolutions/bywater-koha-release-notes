
# Release Notes for bywater-v25.05.05-01

## Acquisitions

- [[40587]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40587) Prevent selection of different EAN's on EDI ORDER when the Basket is generated from a QUOTE message

## Architecture, internals, and plumbing

- [[40818]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40818) marc_lib is mostly used raw in templates
- [[40525]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40525) CSV formula injection - client side (DataTables) in OPAC
- [[40978]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40978) t/db_dependent/Budgets.t fails on Debian 13 due to warnings
- [[40041]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40041) Update mailmap for 25.11.x
- [[40820]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40820) STOMP errors even when JobsNotificationMethod='polling'
- [[40265]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40265) t/db_dependent/OAI/Server.t is failing randomly

## Cataloging

- [[40897]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40897) Uneven field lengths in additem.tt

## Circulation

- [[34596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34596) Items in transit should not show up in the holds queue

## Command-line Utilities

- [[40785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40785) Cronjob cleanup_database.pl usage is outdated
- [[35700]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35700) Holds reminder cronjob --triggered switch does not work as intended if the day to send notice hits concurrent holidays

## Developer documentation

- [[40027]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40027) Use GitHub workflow to automatically close PRs opened on the Koha repo there

## ERM

- [[37622]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37622) "location" header is set for non-POST routes

## Hold requests

- [[40985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40985) Clarify POD of Holds->filter_by_found
- [[40929]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40929) Can't call method "borrowernumber" on an undefined value at opac-modrequest.pl

## ILL

- [[41057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41057) OPAC ILL visiting a URL directly does not respect ILLOpacbackends
- [[40171]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40171) ILL Patron Has No Email Address on File message upon "Send Notice To Patron"

## Installation and upgrade (command-line installer)

- [[40292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40292) SQL syntax error when upgrading to 25.05 on MariaDB 10.3, RENAME COLUMN unsupported

## Label/patron card printing

- [[40473]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40473) X scale for Code39 barcodes is calculated incorrectly when generating barcode labels

## MARC Bibliographic data support

- [[40959]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40959) LOC classification display broken

## OPAC

- [[41010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41010) Incorrect show_priority condition in opac-detail

## Patrons

- [[40936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40936) Add index for default patron sort order
- [[39408]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39408) Cannot add patron via API if AutoEmailNewUser and WELCOME content blank
- [[40917]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40917) Required patron attributes show with extra whitespace in the textarea
- [[40605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40605) Synchronize two sentences about processing personal data

## Reports

- [[40470]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40470) REPORT_GROUP authorized value cannot be numeric
- [[40937]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40937) No option to show/hide data menu in report results when including borrowernumber

## SIP2

- [[40915]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40915) SIP message parsing with empty fields edge cases

## Staff interface

- [[41071]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41071) Registers not correctly populated / selected when changing branches
- [[41074]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41074) Last patron links are shuffled and wrong patrons removed
- [[41042]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41042) Table setting 'default sort order' not available for existing installations
- [[40907]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40907) parenthesis and bracket are breaking filter on item table
- [[40866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40866) Corrections to override logging
- [[40904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40904) Unable to search items by location

## Templates

- [[40931]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40931) Hold pickup location drop-down boxes not wide enough when placing multiple holds at the same time.

## Test Suite

- [[40969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40969) Circulation.t fails if  RenewalPeriodBase is set to now ( the current date )
- [[41012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41012) ILSDI_Services.t is failing randomly
- [[40981]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40981) KohaTable/Holdings_spec.ts is failing randomly
- [[40320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40320) Missing Cypress tests for patron address display
- [[40467]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40467) t/00-deprecated.t no longer needed

## Tools

- [[41079]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41079) Checkboxes visible on the batch patron modification results view
- [[41065]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41065) Batch patron modification results are no longer displayed
- [[32950]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32950) MARC modification template moving subfield can lose values for repeatable fields

## Web services

- [[40622]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40622) Bug 38233 not properly applied to 24.11.x, 25.05.x, and main


