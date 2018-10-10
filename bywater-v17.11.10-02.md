
# Release Notes for bywater-v17.11.10-02

## OPAC

- [[21340]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21340) Add spans with classes around callnumbers in OPAC for additional styling



# Release Notes for bywater-v17.11.10-01

## Acquisitions

- [[21288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21288) Slowness in acquisition caused by GetInvoices
- [[21033]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21033) Remove few warns in acqui/basket.pl
- [[21048]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21048) suggest_status not behaving properly
- [[21097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21097) Missing optgroup closing tag in orderreceive.tt
- [[20623]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20623) PDF export of a basket group fails when an item has an itemtype that is not in the itemtype table

## Architecture, internals, and plumbing

- [[12001]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12001) GetMemberAccountRecords slows down display of patron details and checkout pages
- [[21150]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21150) Data inconsistencies - item types
- [[20509]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20509) Data consistency - authority types
- [[20631]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20631) C4::Acounts claims to use ReturnLostItem but doesn't
- [[21238]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21238) TemplateToolkit.t is failing on slow server
- [[21056]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21056) Changing the logged in library can fail sporadically

## Authentication

- [[13779]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13779) sessionID declared twice in C4::Auth::checkauth()
- [[18947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18947) Unexpected Active Directory LDAP authentication failure mode

## Bywater Only

- NOT IN BUGZILLA - Backport Koha::Account::Lines::item to ensure unit tests pass
- NOT IN BUGZILLA - Fix unit tests for 17.11
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Bug 20770: ILL loans OPAC form notes field allow arbitrary input

## Cataloging

- [[21064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21064) Advanced cataloging editor - rancor - check for changes should return 'undefined' instead of 'undef'
- [[21053]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21053) Editing 008 field with a hash overwrites data
- [[14662]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14662) Allow blank values in pull downs in cataloguing forms when subfield is mandatory
- [[18822]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18822) Advanced editor - Rancor - searching broken under Elasticsearch
- [[21009]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21009) Max length of inputs on editing/adding items is broken

## Circulation

- [[21168]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21168) Error on circ/returns.pl after deleting checked-in item
- [[21231]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21231) BlockReturnofLostItems does not prevent lost items being found

## Command-line Utilities

- [[21011]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21011) Data inconsistencies - items.holdingbranch | items.homebranch
- [[20795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20795) koha-rebuild-zebra should pass through increased verbosity
- [[21035]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21035) runreport.pl prints only a newline when printing a row that has a field that contains an embedded newline
- [[21122]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21122) Make check-url-quick.pl handle utf8 characters in urls gracefuly
- [[20811]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20811) Fix wrong usage of ModBiblio in bulkmarcimport.pl

## Database

- [[20773]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20773) bug 20724 follow-up - Database cleanup

## Developer documentation

- [[21077]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21077) Fix comment for statistics.type in installer/data/mysql/kohastructure.sql

## Hold requests

- [[21076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21076) Javascript error on article requests page
- [[20724]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20724) ReservesNeedReturns syspref breaks "Holds awaiting pickup"

## I18N/L10N

- [[20332]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20332) Untranslatable strings in grouped OPAC results

## Label/patron card printing

- [[20765]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20765) Search for items by acqdate does not work in label batch
- [[8604]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8604) Patron cards made for patrons which don't have patron images use preceding card's image

## MARC Bibliographic data support

- [[20710]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20710) Update MARC21 frameworks to Update 26 (April 2018)

## OPAC

- [[21127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21127) Remove jqTransform jQuery plugin from the OPAC
- [[19291]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19291) Make breadcrumbs for OPAC search history consistent with other patron account pages
- [[21094]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21094) Syndetics: always use https instead of http
- [[21018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21018) OPAC Resource URL Broken if Tracklinks is enabled
- [[20090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20090) Missing Script Statement for Novelist Select on Some Record Displays in OPAC
- [[20953]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20953) Discharge can be requested several times on OPAC

## Packaging

- [[21267]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21267) X_FORWARDED_PROTO header should be set in apache
- [[20800]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20800) Keep Koha on Stretch from using broken libhttp-oai-perl
- [[20437]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20437) Force requirement for HTTP::OAI 3.27
- [[20949]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20949) Koha depends on Clone

## Patrons

- [[7996]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7996) Patron modification log requires parameters permission
- [[18635]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18635) Koha::Patron->guarantees() should return results alphabetically
- [[21025]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21025) Koha::Patron::Discharge is missing use C4::Letters

## REST api

- [[21031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21031) Apache Rewrite rules don't work for API when using anything but Debian package Plack configuration

## Searching

- [[19390]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19390) OPAC view link in staff results should open in a new tab

## Searching - Elasticsearch

- [[21032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21032) Refining a search made on a specific index fail
- [[19502]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19502) Result sets limited to 10000

## Staff Client

- [[21248]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21248) Fix COinS carp in MARC details page on unknown record
- [[17625]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17625) 245f and 245g are not displayed in XSLT
- [[20504]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20504) Language attribute in html tag is empty in system preference editor
- [[20919]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20919) A Zebra query is done for each item when opening a record detail page

## System Administration

- [[19179]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19179) Email option for SMSSendDriver is not documented as a valid setting
- [[21144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21144) ROADTYPE missing from authorised value categories list
- [[21131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21131) Changing and restoring a WYSIWYG preference can result in unexpected behaviour
- [[14446]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14446) Resolve "Use of uninitialized value in goto" in admin/preferences.pl

## Templates

- [[13692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13692) Series link is only using 800a instead of 800t
- [[20984]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20984) MARC21 subfield 300f - Type of Unit  does not display
- [[19511]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19511) Local cover images not centered in table column in staff client search results
- [[21164]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21164) Fix alignment on new basket form in acquisitions
- [[21185]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21185) Incorrect title tag on tags review page
- [[21148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21148) Dropdowns styled by the Select2 plugin do not highlight missing required fields
- [[21139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21139) The floating toolbars have some issues
- [[21099]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21099) Floating toolbars reposition too late
- [[20974]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20974) Remove files left behind after removing Solr
- [[21285]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21285) Select2 broken on high dpi screens
- [[20698]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20698) Remove obsolete template: transfer-slip.tt

## Test Suite

- [[21262]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21262) Do not format numbers for editing if too big
- [[21360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21360) IssueSlip.t is failing if run at 23:59
- [[20776]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20776) Add Selenium::Remote::Driver to dependencies
- [[21230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21230) Reserves.t is failing randomly
- [[21134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21134) Wrong error handling in Koha/Patron/Modification.pm hides a bug
- [[20900]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20900) Yet another test assumes that CPL is present
- [[21023]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21023) Remove warning in t/db_dependent/Circulation/Chargelostitem.t

## Tools

- [[21142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21142) Batch item/record modification/deletion tools does not open uploaded files in utf-8
- [[20564]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20564) Error 500 displays when uploading patron images with a zipped file

## Web services

- [[21226]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21226) Remove use of retired OCLC xISBN service
- [[21199]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21199) Patron's attributes are displayed on GetPatronInfo's ILSDI output regardless opac_display


