
# Release Notes for bywater-v24.11.02-03

## Accessibility

- [[38644]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38644) Breadcrumbs disappear when zoomed in

## Acquisitions

- [[39044]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39044) Fund dropdown not populated for order search on acqui-home
- [[38155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38155) Can't close invoices using checkboxes from invoices.pl
- [[38659]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38659) Cannot set a new suggestion manager when editing a suggestion
- [[37993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37993) Having a single EDI EAN account produces a bad redirect

## Architecture, internals, and plumbing

- [[39214]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39214) Mock preferences in t/db_dependent/Koha/Session.t for subtest 'test session driver'
- [[38653]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38653) Obsolete call on system preference 'OPACLocalCoverImagesPriority'
- [[38624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38624) browserid_include.js no longer used

## Bywater Only

- NOT IN BUGZILLA - GHA - Bypass check if using security repo
- NOT IN BUGZILLA - Bug 36081: (QA follow-up) Resolve IsNotDebit exception in ArticleRequests.t
- NOT IN BUGZILLA - Bug 39170: Improve validation of report ID
- NOT IN BUGZILLA - Bug 37266: [24.11.x] patron_lists/delete.pl should have CSRF protection
- NOT IN BUGZILLA - Bug 38469: Replace single quotes with double quotes to prevent XSS
- NOT IN BUGZILLA - Bug 38488: Add Template::Toolkit filter for C4::Scrubber
- NOT IN BUGZILLA - Bug 38961: XSS in vendor search
- NOT IN BUGZILLA - Bug 28478: Make opac-*detail.pl scripts use Koha::Biblio->opac_suppressed()
- NOT IN BUGZILLA - Bug 37816: (QA follow-up) Avoid repetition, typo and pipe test
- NOT IN BUGZILLA - Bug 38454: Flush memory cache before every API request
- NOT IN BUGZILLA - Bug 38467: (follow-up) Update cpanfile
- NOT IN BUGZILLA - Bug 28907: REST - Drop support for allow-owner functionality
- NOT IN BUGZILLA - Bug 38829: Sanitize GetLateOrMissingIssues inputs

## Circulation

- [[38853]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38853) 'Cancel selected' on holds table does not work
- [[38649]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38649) Searching for a patron from additem.pl triggers an issue slip to print
- [[38512]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38512) Item table status column display is wrong when record has recalls
- [[38588]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38588) Checkin that triggers a transfer => print slip => Internal server error
- [[38985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38985) Syndetics covers don't show on OPAC result pages

## Command-line Utilities

- [[38386]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38386) compare_es_to_db.pl shouldn't retrieve the records from ES
- [[38382]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38382) Need a fresh connection when CSRF has expired for connexion daemon

## Fines and fees

- [[28097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28097) t/db_dependent/Koha/Account/Line.t test fails with FinesMode set to calculate

## Hold requests

- [[37427]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37427) Searching for an empty string for clubs in an item's hold tab is not allowed

## I18N/L10N

- [[38726]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38726) marc vs. MARC in admin-home.tt
- [[38707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38707) Patron restriction types from installer files not translatable
- [[38450]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38450) Missing translation string in catalogue_detail.inc

## ILL

- [[38675]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38675) 'Switch provider' dropdown options not styled properly
- [[38530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38530) ILL request table won't load if libraries are in groups and staff doesn't have view_borrower_infos_from_any_libraries

## Installation and upgrade (command-line installer)

- [[38779]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38779) Record sources not working on packages install
- [[38750]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38750) Installer process not terminating when nothing to do

## MARC Bibliographic data support

- [[32722]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32722) UNIMARC: Remove mandatory flag from some subfields and field in default bibliographic framework

## OPAC

- [[38422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38422) Add data-isbn and data-title to lists for plugin cover images
- [[38657]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38657) Image obscured by the search results toolbar when previewing cover images from OPAC search results
- [[39003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39003) Cannot see suspend column in user's hold table on OPAC
- [[38596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38596) DataTable - previous order sequence behaviour not restored at the OPAC
- [[38544]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38544) OPAC modal login should not exist when OPAC login is disabled
- [[38683]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38683) OPAC cover images are only shown on first result page

## Packaging

- [[33018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33018) Debian package tidy-up

## Patrons

- [[37992]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37992) Patron search results: table header with column filters isn't sticky anymore
- [[38429]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38429) Ambiguous patron category when adding a new guarantee

## REST API

- [[38678]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38678) GET /deleted/biblios cannot be filtered on `deleted_on`

## Searching

- [[39020]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39020) Search filters can't parse query in some instances
- [[38935]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38935) "Actions" column not translatable for the item search results table (itemsearch.tt)

## Searching - Elasticsearch

- [[38101]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38101) ES skips records with huge fields

## SIP2

- [[38486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38486) No block checkouts are still blocked by fines, checkouts, and blocked item types

## Staff interface

- [[39080]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39080) Table headers of holds to pull table are incorrect size on scroll
- [[39000]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39000) "Encoding errors" block on detail page hurt the eyes
- [[38521]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38521) Add classes to reports homepage
- [[38367]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38367) offset is wrong on plugins-disabled.tt page
- [[38465]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38465) Cannot schedule a curbside pickup
- [[38070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38070) Regression in print notices

## System Administration

- [[37311]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37311) Tone down the SMTP servers administration page

## Templates

- [[38611]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38611) Change 'Staff' to 'Staff interface' in HTML customization locations
- [[38701]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38701) Fix HTML validity errors in invoice template
- [[37634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37634) Missing "USE Koha" causes JS errors and missing "Last patron" menu
- [[38350]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38350) Fix style of sidebar form clear buttons
- [[38347]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38347) Fix style of sidebar form submit button on bookings to collect page
- [[38519]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38519) Improve contrast of Bootstrap alerts and text background classes
- [[38813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38813) Curbside pickups tab not selected in OPAC
- [[38268]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38268) Callers of confirmModal need to remove the modal as the first step in their callback function

## Tools

- [[37360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37360) Add 'protected status' as one of the things that can be updated via batch patron modification
- [[38531]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38531) Include action_logs.diff when reverting hold
- [[31450]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31450) HTML customizations and news will not display on OPAC without a publication date
- [[38452]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38452) Inventory tool barcodes should not be case sensitive


