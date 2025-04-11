
# Release Notes for montgomery-v24.11.03-06

## About

- [[38617]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38617) Fix warning about auto increment and biblioitems
- [[36039]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36039) The output of audit_database.pl should be accessible through the UI

## Acquisitions

- [[39518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39518) Add the option to define the basket name in a MARC file when adding to a basket
- [[39530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39530) The MARC ordering cronjob needs to respect the AcqCreateItems syspref
- [[38957]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38957) EDIFACT messages table should sort by 'Transferred date' descending by default
- [[38766]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38766) Opening, closing, or deleting and invoice from the Action drop-down can cause internal server error

## Architecture, internals, and plumbing

- [[38483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38483) C4::Heading::preferred_authorities is not used
- [[36662]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36662) ILL - t/db_dependent/Illrequest should not exist
- [[38838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38838) optgroup construct needs cleaning in the reports module

## Authentication

- [[38826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38826) C4::Auth::check_api_auth sometimes returns $session and sometimes returns $sessionID

## Bywater Only

- NOT IN BUGZILLA - Add Test::NoWarnings to cpanfile
- NOT IN BUGZILLA - Enable INSTALL_MISSING_FROM_CPANFILE for Koha docker
- NOT IN BUGZILLA - Remove duplicate hide_marc from sysprefs.sql
- NOT IN BUGZILLA - 24.11.03: Update contributors.yaml
- NOT IN BUGZILLA - Bug 37784: (QA follow-up) Add few tables to Koha::Database::Columns
- NOT IN BUGZILLA - Bug 31165: Scrub "Public note" field for Course Reserves

## Cataloging

- [[37398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37398) Initialize a datepicker on all date/datetime fields when adding/editing items

## Circulation

- [[39361]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39361) Hold found modal does not display from circulation / transfer
- [[39183]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39183) If using automatic return claim resolution on checkout, each checkout will overwrite the previous resolution (again)
- [[38793]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38793) When setting up automatic confirmation of transfers when dismissing the modal. It prevents manual cancellation

## Command-line Utilities

- [[37920]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37920) writeoff_debts.pl should be logged
- [[39236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39236) writeoff_debts.pl does not run

## ERM

- [[38782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38782) ERM eUsage related tests are failing
- [[36627]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36627) Display importer for manually harvested SUSHI data

## I18N/L10N

- [[38684]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38684) Improve translatability in cat-toolbar.inc

## ILL

- [[39175]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39175) Send request to partners explodes

## Installation and upgrade (command-line installer)

- [[39460]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39460) Debian package install broken in 24.11 if no database change included in package (e.g. 24.11.03-2)

## Lists

- [[38302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38302) Inconsistent delete confirmation dialog for "Delete list" buttons

## OPAC

- [[35808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35808) Remove obsolete responsive table markup from several pages in the OPAC
- [[35975]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35975) Downloaded cart with BibTeX contains hash value instead of the record number
- [[38753]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38753) Missing table cells breaks OPAC charges table
- [[38077]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38077) Minor spacing issue in self checkout login page
- [[38462]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38462) Remove unused code for pagination in OPAC authority search

## Patrons

- [[36025]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36025) Extended attributes clause added to patron search query even when there are no searchable attributes
- [[38459]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38459) Cities dropdown should work for quick add form as well
- [[33454]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33454) Improve breadcrumbs for patron lists
- [[38735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38735) New installations should include preferred_name in DefaultPatronSearchFields by default
- [[38772]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38772) Typo 'minPasswordPreference' system preference

## Point of Sale

- [[38667]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38667) Point of sale transaction history should not appear to be sortable

## Searching - Elasticsearch

- [[38912]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38912) Elasticsearch record show is a 404 from staff catalog details

## SIP2

- [[38615]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38615) Cancelling a waiting hold via SIP should include an option to move it to holds with cancellation requests
- [[38375]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38375) SIP2 syspref SIP2SortBinMapping is not working

## Staff interface

- [[38436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38436) Adjust code for column visibility (after DataTables upgrade)
- [[38108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38108) Make display of table filters in staff interface holdings table configurable
- [[38632]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38632) All columns shown in holdings table when displaying the filters
- [[37761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37761) Tabs on curbside_pickups.tt page not styled right after Bootstrap 5 update
- [[38711]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38711) Wrong font-weight in tables during printing from staff interface
- [[38662]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38662) Additional fields admin page hard to read

## Templates

- [[38221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38221) Add Bootstrap styling to pagination in authority plugin search results
- [[37826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37826) Remove the use of the script_name variable where it is unnecessary
- [[38349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38349) Fix style of sidebar form submit button on tags review page
- [[38285]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38285) Replace instances of obsolete Bootstrap class "pull-right"
- [[36609]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36609) Update index type labels in Elasticsearch config page: Std. Number, Call Number, <empty>
- [[38665]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38665) Markup error in additional fields template title

## Test Suite

- [[39007]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39007) Add last_audit to the sushi_service API spec

## Tools

- [[38771]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38771) Typo 'AuthScuccessLog' system preference


