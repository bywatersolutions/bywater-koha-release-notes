
# Release Notes for bywater-v19.05.05-01

## Acquisitions

- [[23854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23854) Cannot edit a suggestion
- [[18743]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18743) Filter suggestion lists correctly for IndependentBranches
- [[23863]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23863) Editing a basket clears create_items value
- [[23855]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23855) Cannot mark the selected suggestion as "pending"
- [[23101]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23101) Contracts permissions for staff patron

## Architecture, internals, and plumbing

- [[22857]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22857) Entries missing in koha-conf.xml
- [[21987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21987) Local cover 'thumbnail' size is bigger than 'imagefile' size in biblioimages table
- [[23867]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23867) 18.12.00.051 fails with "Truncated incorrect DOUBLE value"
- [[23723]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23723) Using exit inside eval to stop sending output to the browser doesn't work under Plack
- [[23627]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23627) Koha::Biblio->get_coins too noisy if no 245$b

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Maintanence team template corrections
- NOT IN BUGZILLA - Update teams for 20.05 cycle
- NOT IN BUGZILLA - Bug 23042: Correct shib param escaping
- NOT IN BUGZILLA - Bug 23836: exit after output_error
- NOT IN BUGZILLA - Bug 23329: (RM follow-up) Restore DB after test
- NOT IN BUGZILLA - Bug 23451: Fix other similar wrong filterings
- NOT IN BUGZILLA - Bug 22543: Prevent "back and refresh attack"

## Cataloging

- [[23851]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23851) Auto generate accession number format <branchcode>yymm0001 fails to add branchcode prefix(branchcode) for multiple item addition
- [[23252]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23252) Pressing enter should not submit form in item editor

## Circulation

- [[24075]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24075) Backdating a return to the exact due date and time results in the fine not being refunded
- [[23985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23985) The method Koha::Item-> is not covered by tests!
- [[23774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23774) When placing a hold editing using Inspect Element allows addition to the code of non listed library
- [[23938]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23938) Title missing from Checked out box
- [[23679]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23679) Software error when trying to transfer an unknown barcode

## Database

- [[23579]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23579) error during web install: 'changed_fields' can't have a default value
- [[23809]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23809) Update to DB revision 16.12.00.032 fails

## Fines and fees

- [[23826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23826) Manual Invoice does not use new accounttype and status for fines

## Hold requests

- [[23484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23484) Holds to pull (pendingreserves.pl) uses removed default_branch_item_rules table

## I18N/L10N

- [[23713]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23713) Subscription add form broken for translations
- [[23631]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23631) fr-CA translation of NEW_SUGGESTION notice

## ILL

- [[23529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23529) Interlibrary loan javascript is broken
- [[22280]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22280) The ILL module assumes every status needs a next/previous status

## MARC Bibliographic record staging/import

- [[23846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23846) Handle records with broken MARCXML on the bibliographic detail view

## Notices

- [[23765]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23765) After TranslateNotices is set to 'Don't allow', email settings still show multiple languages
- [[23181]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23181) Unable to use payment library in ACCOUNT_PAYMENT or ACCOUNT_WRITEOFF notices

## OPAC

- [[23467]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23467) Duplicated screen if error in opac-reserve.pl
- [[22804]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22804) OPAC Overdrive JavaScript contains untranslatable strings
- [[23683]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23683) Course reserves public notes on specific items should allow for HTML
- [[23625]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23625) ArticleRequestsMandatoryFields* only affects field labels, does not make inputs required
- [[22602]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22602) OverDrive circulation integration is broken when user is referred to Koha from another site

## Patrons

- [[23822]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23822) Regression: As of 19.05.04 deletion of patrons with outstanding credits is silently blocked
- [[23589]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23589) Discharge notice does not show non-latin characters
- [[17140]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17140) Incorrect rounding in total fines calculations, part 2
- [[23688]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23688) System preference uppercasesurnames broken by typo

## Reports

- [[23827]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23827) [19.05] Cash register statistics uses old accounttype values
- [[23626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23626) Add a system preference to limit the number of rows of data used when charting or exporting report results
- [[23624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23624) Count rows in report without (potentially) consuming all memory

## REST API

- [[23607]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23607) Make /patrons/:patron_id/account privileged user only

## Searching - Elasticsearch

- [[23630]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23630) Elasticsearch indexing is removing field 999
- [[22997]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22997) Searching gives no results in auth_finder.pl

## Staff Client

- [[24060]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24060) [19.05] Can't load patron clubs tab on patron details page
- [[23689]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23689) Terminology: Branches limitations should be libraries limitations - Authorised Values
- [[23651]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23651) RestrictedPage system preferences should include the address of the page in the description

## System Administration

- [[24026]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24026) Wrong parameters in Koha/Templates/Plugin/CirculationRules.pm and smart-rules.tt
- [[23398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23398) Exporting/Reimporting frameworks in XML format will give incomplete results

## Templates

- [[23605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23605) Terminology: Branches limitations should be libraries limitations

## Test Suite

- [[24144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24144) regressions.t tests have not been updated after bug 23836
- [[24145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24145) Auth.t is failing because of wrong mocked ->param
- [[23234]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23234) Circulation.t failing when comparing dates that seem identical
- [[21985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21985) Test t/db_dependent/Circulation.t fails if SearchEngine is set to elasticsearch

## Tools

- [[23963]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23963) Visible reduction in image quality
- [[17359]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17359) Patron import results use wrong encoding
- [[18710]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18710) Wrong subfield modified in batch item modification



# Release Notes for bywater-v19.05.04-10

## Bywater Only

- NOT IN BUGZILLA - Update filter and add page id for 'Koha as a CMS' feature



# Release Notes for bywater-v19.05.04-09

## Hold requests

- [[23964]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23964) An item level hold when placed is set to Waiting, if ReservesNeedReturn is set to Automatic



# Release Notes for bywater-v19.05.04-08

## Bywater Only

- NOT IN BUGZILLA - Test commit 3
- NOT IN BUGZILLA - Test commit 2
- NOT IN BUGZILLA - Test commit 1
- NOT IN BUGZILLA - GitHub Actions - Testing Auto-Rebaser
- NOT IN BUGZILLA - GitHub Actions

## Circulation

- [[24075]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24075) Backdating a return to the exact due date and time results in the fine not being refunded



# Release Notes for bywater-v19.05.04-07

## Bywater Only

- NOT IN BUGZILLA - GITHUB ACTIONS - Initial commit

## Command-line Utilities

- [[23933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23933) commit_file.pl Can't call method "get_effective_marcorgcode" on an undefined value at /usr/share/koha/lib/C4/AuthoritiesMarc.pm line 578.



# Release Notes for bywater-v19.05.04-06

## Searching - Elasticsearch

- [[23986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23986) Batch Record Deletion does not remove records from Elasticsearch search index

## Staff Client

- [[23680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23680) Can't open 'Edit items' or 'Add item' links in new tab - tab is closed immediately



# Release Notes for bywater-v19.05.04-05

## Circulation

- [[23551]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23551) Problem with renewal period when using the renewal tab



# Release Notes for bywater-v19.05.04-04

## Installation and upgrade (command-line installer)

- [[23813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23813) DB error on 18.12.00.020



# Release Notes for bywater-v19.05.04-03



# Release Notes for bywater-v19.05.04-02

## Authentication

- [[23526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23526) Shibboleth login url with query has double encoded '?' %3F


