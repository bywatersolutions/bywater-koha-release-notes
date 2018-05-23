
# Release Notes for huntsville-v17.11.04-05

## Acquisitions

- [[20446]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20446) QUOTES processing broken by run time error
- [[20303]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20303) Receive order fails if no "authorised_by" value
- [[20201]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20201) Silence warnings in admin/aqplan.pl
- [[20148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20148) Don't allow adding same user multiple times to a basket or an order
- [[19928]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19928) Acquisitions' CSV exports should honor syspref "delimiter"
- [[10032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10032) Uncertain prices hide 'close basket' without explanation
- [[20110]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20110) Don't allow adding same user multiple times to same budget fund

## Architecture, internals, and plumbing

- [[20145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20145) borrowers.datexpiry eq '0000-00-00' means expired?
- [[20060]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20060) Uninitialized warn from Koha::Template::Plugin::Branches
- [[20031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20031) CGI param in list context warn in guided_reports.pl
- [[20126]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20126) Saving a biblio does no longer update MARC field lengths
- [[20088]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20088) Use of uninitialized value in array element in svc/holds
- [[20056]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20056) Uninitialized warn in cmp_sysprefs.pl
- [[19827]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19827) checkuniquemember is exported from C4::Members but has been removed
- [[19985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19985) TestBuilder.t fails if default circ rule exists

## Authentication

- [[20083]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20083) Information disclosure when (mis)using the MARC Preview feature

## Bywater Only

- NOT IN BUGZILLA - Update .travis.yml to match the one we use for 17.05 - TODO - merge with origin travis patch
- NOT IN BUGZILLA - Fully qualify call to ModZebra in Items.pm
- NOT IN BUGZILLA - Restore the storing of itemnumber for writeoffs
- NOT IN BUGZILLA - Bug XXX - Add option to SIP2 config to send shelving location in CR instead of collection code
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Bux XXX - Adding f17I and f18K options to marc21_leader.tt for Albright
- NOT IN BUGZILLA - Bug XXX - Add ability to disable demagnitizing items via SIP2 for arbitrary patron categories
- NOT IN BUGZILLA - Fixing typo, missing OR symbol
- NOT IN BUGZILLA - Reduce ambiguity for selecting opac_news.timestamp, affects only a few partners
- NOT IN BUGZILLA - Removing koha-upgrade-schema from post-install tasks
- NOT IN BUGZILLA - Adding custom ProxyPass and allow SetEnv options to plack configs
- NOT IN BUGZILLA - Add pages.pl and pages.tt for Koha as a CMS
- NOT IN BUGZILLA - SHIB - Shibboleth: bugfix for logging into staff client
- NOT IN BUGZILLA - SHIB - Two minor bugfixes; log out from staff side, and don't create new session on each page load
- NOT IN BUGZILLA - SHIB - Adds Shibboleth authentication (Matthias + JPW)
- NOT IN BUGZILLA - Setting use_zebra_facets to 0 in koha-conf template files
- NOT IN BUGZILLA - BWS Patch: All custom zebra indexes
- NOT IN BUGZILLA - Update relase notes for 17.11.04 release

## Circulation

- [[18816]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18816) Make CataloguingLog work in production by preventing circulation from spamming the log
- [[19530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19530) Prevent multiple transfers from existing for one item
- [[4319]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=4319) waiting and in transit items cannot be reserved
- [[20003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20003) Result summary of remaining checkouts items not displaying.

## Command-line Utilities

- [[20795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20795) koha-rebuild-zebra should pass through increased verbosity
- [[19452]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19452) The -truncate option in borrowers-force-messaging-defaults.pl should not remove category preferences
- [[19730]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19730) misc/export_records.pl should use biblio_metadata.timestamp

## Course reserves

- [[19230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19230) Warn when deleting a course in course reserves

## Fines and fees

- [[20285]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20285) Lost item refund won't always pay down lost item fee first
- [[19750]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19750) Overdues without a fine rule add warnings to log

## Hold requests

- [[20167]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20167) Item hold is set to bibliographic hold when changing pickup location

## I18N/L10N

- [[20166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20166) Untranslatable course reserves delete prompt
- [[20124]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20124) Allow translating did you mean config save message
- [[20109]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20109) Allow translating "Remove" in Add Fund
- [[11827]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11827) Untranslatable "Cancel Rating" in jQuery rating plugin

## ILL

- [[20041]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20041) ILL module missing from more menu in staff when activated

## Installation and upgrade (web-based installer)

- [[12932]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12932) Web installer's Perl version check will not raise errors if all modules are installed

## Notices

- [[18477]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18477) AR_PENDING notice does not populate values from article_requests table

## OPAC

- [[20122]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20122) Empty and close link on cart page not working
- [[19978]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19978) Fix ITEMTYPECAT feature for grouping item types for search
- [[18975]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18975) Wrong CSRF token when emailing cart contents
- [[20054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20054) Remove attribute "text/css" for the style tags used in the OPAC templates
- [[19975]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19975) Tag cloud searching does not working
- [[20068]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20068) Warn on OPAC homepage if not logged in due to OPAC dashboard

## Packaging

- [[17108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17108) Automatic debian/control updates (stable)
- [[20072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20072) Fix build-git-snapshot for Debian source format quilt

## Patrons

- [[20008]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20008) Restrictions added from memberentry.pl have expiration date ignored if TimeFormat is 12hr
- [[20367]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20367) userid resets to firstname.surname when BorrowerUnwantedField contains userid

## Reports

- [[19671]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19671) Circulation wizard / issues_stats.pl does not populate itemtype descriptions correctly
- [[18497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18497) Downloading a report passes the constructed SQL as a parameter
- [[19669]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19669) Remove deprecated checkouts by patron category report

## REST api

- [[20134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20134) Remove /api/v1/app.pl from the generated URLs

## SIP2

- [[20348]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20348) SIP2 patron identification fails to use userid

## Staff Client

- [[20227]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20227) admin/smart-rules.pl should pass categorycode instead of branchcode

## System Administration

- [[20091]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20091) FailedLoginAttempts is not part of NorwegianPatronDatabase pref group

## Templates

- [[19882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19882) Add Novelist Select staff client profile
- [[20135]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20135) Staff client language choose pop-up can appear off-screen
- [[20156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20156) Staff client header language menu doesn't show check mark for current language
- [[20051]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20051) Invalid markup in staff client's header.inc

## Test Suite

- [[20466]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20466) Incorrect fixtures for active currency in t/Prices.t
- [[19979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19979) Search.t fails on facet info with one branch
- [[20250]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20250) NoIssuesChargeGuarantees.t is still failing randomly
- [[19705]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19705) DecreaseLoanHighHolds.t is still failing randomly

## Tools

- [[20098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20098) Inventory: CSV export: itemlost column is always empty

## Web services

- [[13990]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13990) ILS-DI LookupPatron Requries ID Type

## Z39.50 / SRU / OpenSearch Servers

- [[19986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19986) 'Server name' doesn't appear as required when creating new z39.50/sru server


