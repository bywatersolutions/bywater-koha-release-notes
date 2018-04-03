
# Release Notes for vokal-v17.05.10-02

## Acquisitions

- [[20148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20148) Don't allow adding same user multiple times to a basket or an order

## Architecture, internals, and plumbing

- [[20145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20145) borrowers.datexpiry eq '0000-00-00' means expired?

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Bug 20083: Follow up - use same logic in opac-showmarc

## Circulation

- [[19530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19530) Prevent multiple transfers from existing for one item

## Command-line Utilities

- [[19452]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19452) The -truncate option in borrowers-force-messaging-defaults.pl should not remove category preferences

## Course reserves

- [[20276]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20276) GetCourseItem is using the wrong call  to get itemnumber

## Hold requests

- [[20167]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20167) Item hold is set to bibliographic hold when changing pickup location

## OPAC

- [[20218]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20218) Tracklinks fails when URL has special characters

## Patrons

- [[20367]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20367) userid resets to firstname.surname when BorrowerUnwantedField contains userid

## Staff Client

- [[19806]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19806) Add class to items.itemnotes_nonpublic

## Test Suite

- [[20466]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20466) Incorrect fixtures for active currency in t/Prices.t
- [[19979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19979) Search.t fails on facet info with one branch
- [[20250]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20250) NoIssuesChargeGuarantees.t is still failing randomly
- [[19529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19529) NoIssuesChargeGuarantees.t is failing randomly

## Tools

- [[20098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20098) Inventory: CSV export: itemlost column is always empty



# Release Notes for vokal-v17.05.09-01

## Acquisitions

- [[19596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19596) Internal server error if open order with deleted biblio / null biblionumber
- [[19401]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19401) No confirm message when deleting an invoice from invoice detail page
- [[19429]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19429) No confirm message when deleting an invoice from invoice search

## Architecture, internals, and plumbing

- [[19847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19847) tracklinks.pl accepts any url from a parameter for proxying
- [[20126]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20126) Saving a biblio does no longer update MARC field lengths
- [[19985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19985) TestBuilder.t fails if default circ rule exists
- [[15770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15770) Number::Format issues with large numbers
- [[19839]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19839) invoice.pl warns about bad variable scope

## Bywater Only

- NOT IN BUGZILLA - Revert "BWS-PKG - Add bws auto-rebaser"
- NOT IN BUGZILLA - Add bws auto-rebaser
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[19968]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19968) Undefined subroutine &Date::Calc::Today
- [[18417]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18417) Advanced Editor - Rancor - add shortcuts for copyright symbols (C) (P)

## Circulation

- [[19825]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19825) List of pending offline operations does not links to biblio
- [[16603]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16603) Hide option to apply directly when processing uploaded offline circulation file

## Command-line Utilities

- [[19730]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19730) misc/export_records.pl should use biblio_metadata.timestamp

## Database

- [[19422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19422) kohastructure.sql missing DROP TABLES

## Installation and upgrade (web-based installer)

- [[19973]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19973) SQL syntax error in uk-UA/mandatory/sample_notices.sql

## Notices

- [[18477]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18477) AR_PENDING notice does not populate values from article_requests table

## OPAC

- [[19975]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19975) Tag cloud searching does not working
- [[17682]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17682) Change URL for Google Scholar in OPACSearchForTitleIn
- [[18915]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18915) Creating a checkout note (patron note) sends an incomplete email message
- [[19911]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19911) Passwords displayed to user during self-registration are not HTML-encoded

## Packaging

- [[20072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20072) Fix build-git-snapshot for Debian source format quilt
- [[18696]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18696) Change debian/source/format to quilt

## Patrons

- [[19443]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19443) Error while attempting to duplicate a patron
- [[19921]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19921) Error when updating child to adult patron on system with only one adult patron category

## Reports

- [[19669]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19669) Remove deprecated checkouts by patron category report

## Searching

- [[19971]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19971) typo in the comments of parseQuery routine

## Searching - Elasticsearch

- [[19580]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19580) Elasticsearch: QueryAutoTruncate exclude period as splitting character in autotruncation
- [[19559]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19559) Elasticsearch QueryAutoTruncate truncate field names with hyphens if data is quoted

## Staff Client

- [[19221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19221) Onboarding tool says user needs to be made superlibrarian

## System Administration

- [[19987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19987) If no z39.50/SRU servers, the z39.50/SRU buttons should not show
- [[19977]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19977) Local Use tab in systempreferences tries to open text editor's temporary files, and die
- [[19560]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19560) Unable to delete library when branchcode contains special characters

## Templates

- [[19677]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19677) Angle brackets in enumchron do not display in opac or staff side

## Test Suite

- [[19705]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19705) DecreaseLoanHighHolds.t is still failing randomly
- [[19455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19455) Circulation/SwitchOnSiteCheckouts.t is failing randomly
- [[19783]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19783) Move check_kohastructure.t to db_dependent
- [[20042]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20042) 00-load.t fails when Elasticsearch is not installed
- [[19937]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19937) Silence warnings t/db_dependent/www/batch.t
- [[19483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19483) t/db_dependent/www/* crashes test harness due to misconfigured test plan
- [[19914]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19914) Cannot locate the "Delete" in the library list table



# Release Notes for vokal-v17.05.08-01

## Acquisitions

- [[18183]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18183) jQuery append error related to script tags in cloneItemBlock
- [[19813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19813) MarcItemFieldsToOrder cannot handle a tag not existing
- [[19694]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19694) Edited shipping cost in invoice doesn't save

## Architecture, internals, and plumbing

- [[19760]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19760) Die instead of warn if koha-conf is not accessible
- [[19756]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19756) Encoding issues when update DB is run from the interface
- [[19599]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19599) anonymise_issue_history can be very slow on large systems
- [[19830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19830) Add the Koha::Patron->old_checkout method
- [[18923]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18923) Resolve a warn in Biblio::GetCOinSBiblio

## Bywater Only

- NOT IN BUGZILLA - Fully qualify call to ModZebra in Items.pm
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Bug 19738: Fix XSS on vendor name in serials module
- NOT IN BUGZILLA - Bug 19881: Remove authorities-list.pl
- NOT IN BUGZILLA - Bug 19847: Track links within the records and 404 for others

## Cataloging

- [[20063]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20063) $9 is lost when cataloguing authority records

## Circulation

- [[19444]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19444) Automatic renewal script should not auto-renew if a patron's record has expired
- [[11210]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11210) Allow partial writeoff

## Installation and upgrade (web-based installer)

- [[19514]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19514) No Password restrictions in onboarding tool patron creation

## MARC Authority data support

- [[18458]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18458) Merging authority record incorrectly orders subfields

## OPAC

- [[19913]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19913) Embedded HTML5 videos are broken
- [[19338]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19338) Dates sorting incorrectly in opac-account.tt
- [[19702]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19702) Basket not displaying correctly on home page
- [[19573]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19573) Link to make a new list in masthead in OPAC only appears / works if no other list already exists
- [[19450]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19450) OverDrive integration failing on missing method
- [[19496]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19496) Patron notes about item does not get emailed as indicated

## Patrons

- [[20008]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20008) Restrictions added from memberentry.pl have expiration date ignored if TimeFormat is 12hr
- [[19621]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19621) Routing lists tab not present when viewing 'Holds history' tab for a patron
- [[19510]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19510) edi_manage permission has no description

## Reports

- [[19669]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19669) Remove deprecated checkouts by patron category report

## Searching

- [[19807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19807) IntranetCatalogSearchPulldown doesn't honor IntranetNumbersPreferPhrase

## Staff Client

- [[19857]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19857) Optionally hide SMS provider field in patron modification screen

## System Administration

- [[19788]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19788) Case sensitivity is not preserved when creating local system preferences

## Templates

- [[19918]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19918) span tag not closed in opac-registration-confirmation.tt
- [[19602]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19602) Add usage statistics link to administration sidebar menu

## Test Suite

- [[19867]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19867) HouseboundRoles.t is failing randomly
- [[17770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17770) t/db_dependent/Sitemapper.t fails when date changes during test run

## Tools

- [[18201]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18201) Export data -Fix "Remove non-local items" option and add "Removes non-local records" option for existing functionality

## Web services

- [[19725]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19725) OAI-PMH ListRecords and ListIdentifiers should use biblio_metadata.timestamp



# Release Notes for vokal-v17.05.07-01

## Acquisitions

- [[19813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19813) MarcItemFieldsToOrder cannot handle a tag not existing

## Architecture, internals, and plumbing

- [[19655]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19655) To.json doesn't escape newlines which can create invalid JSON

## Bywater Only

- NOT IN BUGZILLA - Restore the storing of itemnumber for writeoffs
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Bug 19614: Fix XSS in members/pay.pl
- NOT IN BUGZILLA - Bug 19612: Fix XSS in members/memberentry.pl
- NOT IN BUGZILLA - Bug 19611: Fix XSS Flaws in supplier.pl
- NOT IN BUGZILLA - Bug 19319: Only fetch the record if it exists
- NOT IN BUGZILLA - Bug 19570: Add autocomplete to opac-main as well
- NOT IN BUGZILLA - Bug 19569: Set X-Frame-Options=SAMEORIGIN - opac-showmarc.ok
- NOT IN BUGZILLA - Bug 19568: Escape url params with url filter - opac-opensearch.tt

## Cataloging

- [[19595]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19595) Clicking plugin link does not fill item's date acquired field
- [[18833]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18833) plugin unimarc_field_210c pagination error
- [[19646]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19646) value_builder marc21_linking_section template is broken

## Command-line Utilities

- [[19190]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19190) Silly calculation of average time in touch_all scripts

## Database

- [[19724]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19724) Add timestamp to biblio_metadata and deletedbiblio_metadata

## Hold requests

- [[19533]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19533) Hold pulldown for itemtype is empty if hold placement needs override

## Label/patron card printing

- [[10222]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10222) Error when saving Demco label templates
- [[19681]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19681) label-item-search.pl result count formatting error when there is only one page

## Notices

- [[18990]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18990) Overdue Notices are not sending through SMS correctly

## OPAC

- [[12497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12497) Make OPAC search history feature accessible when it should
- [[19640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19640) IdRef webservice display is broken

## Packaging

- [[18907]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18907) Warning "dpkg-source: warning: relation < is deprecated: use << or <="

## Reports

- [[19638]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19638) False positives for 'Update SQL' button

## System Administration

- [[12768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12768) Replacement cost and processing fee management

## Templates

- [[19751]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19751) Holds awaiting pickup report should not be fixed-width
- [[19692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19692) Unclosed div in opac-shelves.tt

## Test Suite

- [[19775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19775) Search/History.t is failing randomly

## Tools

- [[19674]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19674) Broken indicators of changed fields in manage staged MARC records template
- [[19643]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19643) Pagination buttons on staged marc management are stacking instead of inline
- [[19683]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19683) Export.pl does not populate the Authority Types dropdown correctly


