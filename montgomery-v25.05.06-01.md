
# Release Notes for montgomery-v25.05.06-01

## Accessibility

- [[41198]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41198) Add visible “Sort results by” label above the sort dropdown for accessibility and clarity
- [[41201]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41201) Definite article in some labels confuses screen readers

## Acquisitions

- [[38516]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38516) Closed group basket not able to open pdf file with adobe  The root object is missing or invalid
- [[40988]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40988) Subfunds in acqui-home.pl and aqbudgets.pl are not collapsible beyond 20th line

## Architecture, internals, and plumbing

- [[40524]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40524) Stored XSS run by DataTables Print button in staff interface
- [[41032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41032) Open Fifth missing in plugin repos config
- [[41262]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41262) Duplicate import in Koha::Patron
- [[41104]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41104) Samesite HTTP response header being set in C4::Auth::checkauth()
- [[41044]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41044) Fix argument isn't numeric in addition in Koha::Item::find_booking
- [[40559]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40559) Fix a noisy warn in catalogue/MARCdetail
- [[41024]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41024) Inconsistent spelling of Borrower(s)Log
- [[41123]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41123) Remove useless dbh statement from Patron

## Authentication

- [[41038]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41038) Add more test coverage for bug 30724

## Cataloging

- [[41205]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41205) Error in Advanced Cataloging editor when z39 source returns undef / empty records

## Circulation

- [[40205]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40205) "Default checkout, hold and return policy" cannot be unset
- [[41298]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41298) Filtering holdings table with status In transit considers every item ever transferred to be "In transit"
- [[41314]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41314) Column visibility broken on the checkouts table
- [[41149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41149) Spinner/loader does not disappear when a renewal fails with AllowRenewalOnHoldOverride set to dont allow
- [[24533]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24533) Improved sorting in checkouts table

## Command-line Utilities

- [[41008]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41008) bulkmarcimport.pl -d broken for authorities
- [[39532]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39532) Script debar_patrons_with_fines.pl should not use MANUAL restriction type

## Database

- [[41421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41421) Bug 35830 DB update must be idempotent

## ERM

- [[38446]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38446) Permission error for additional fields

## ILL

- [[41257]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41257) ILL "List requests"/"Refresh" wording doesn't work

## Installation and upgrade (command-line installer)

- [[41167]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41167) Rewrite Rules missing in etc/koha-httpd.conf

## Notices

- [[39985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39985) items.onloan field is not updated when an item is recalled

## OPAC

- [[40873]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40873) AV dropdowns in OPAC don't use lib_opac values
- [[41177]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41177) Breadcrumbs should have aria-disabled attribute if its the current page
- [[41168]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41168) "Search the catalog by keyword" confuses some users
- [[40836]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40836) Credit and debit types are not shown in patron account on OPAC
- [[41078]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41078) Improve handling of multiple covers on shelves/lists results in the OPAC
- [[38080]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38080) Sorting options for holdings table are incorrect
- [[40903]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40903) OPAC advanced search applies a location limit of the logged-in library by default
- [[30633]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30633) Move OPACHoldingsDefaultSortField to table settings configuration

## Patrons

- [[41094]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41094) search_anonymize_candidates returns too many candidates when FailedLoginAttempts is empty
- [[41212]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41212) members/maninvoice.pl debit_types should sort by description not code
- [[41039]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41039) Patron search button can be spammed and trigger many API patron searches
- [[41053]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41053) Make notice contents searchable on notices tab of patron details
- [[29908]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29908) Warning when empty ClaimReturnedWarningThreshold in patron_messages.inc
- [[35830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35830) Add separate permission for Merging Patrons
- [[41067]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41067) 'OPAC mandatory' attribute setting requires 'Editable in OPAC' to work

## Plugin architecture

- [[25952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25952) Github search errors make it impossible to install plugins from other repos
- [[40983]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40983) Remove deprecated syntax for 'after_biblio_action' hooks

## Point of Sale

- [[40625]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40625) Prevent cashup re-submissions on page reload

## Reports

- [[40961]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40961) LocalUse Circulation Statistics offering empty results
- [[41082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41082) Renaming columns in reports doesn't work with batch tools
- [[41112]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41112) Space is missing in report preview

## REST API

- [[39336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39336) Public Biblio endpoint should honour OpacSuppression syspref

## Staff interface

- [[41229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41229) Cash registers are not fully reset on library change
- [[38072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38072) Regression with modalPrint

## System Administration

- [[41092]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41092) Some system preferences have target='blank' instead of target='_blank'

## Templates

- [[40760]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40760) 'Edit' link in item receive table is not formatted as link
- [[40664]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40664) Serial subscription input missing "Required" labels
- [[41207]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41207) Permission description string does match permission name
- [[40720]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40720) Misleading title attribute "Remove all items" in Select2 fields

## Test Suite

- [[38475]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38475) InfiniteScrollSelect_spec.ts is failing randomly again
- [[40845]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40845) t/Koha/Manual.t only passes for 25.05 and 25.06

## Tools

- [[40843]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40843) On modborrowers.pl patron attributes should sort by the description, not the code


