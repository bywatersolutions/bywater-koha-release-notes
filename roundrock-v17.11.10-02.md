
# Release Notes for roundrock-v17.11.10-02

## OPAC

- [[21340]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21340) Add spans with classes around callnumbers in OPAC for additional styling



# Release Notes for roundrock-v17.11.10-01

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
- NOT IN BUGZILLA - BWS PATCH add 773t to zebra index for Title.
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



# Release Notes for roundrock-v17.11.08-01

## Acquisitions

- [[20014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20014) When adding to basket from a staged file item budgets are selected my matching on code, not id
- [[20979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20979) Error message when deleting bib attached to order
- [[20972]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20972) If ISBN has 10 numbers only the first 9 numbers are used

## Architecture, internals, and plumbing

- [[12001]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12001) GetMemberAccountRecords slows down display of patron details and checkout pages
- [[20702]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20702) Bind results of GetHostItemsInfo to the EasyAnalyticalRecords pref

## Authentication

- [[20879]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20879) Shibboleth in combination with LDAP as an alternative no longer works

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Circulation

- [[20793]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20793) Don't show holds link in result list when staff user doesn't have place_holds permission
- [[21019]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21019) [17.11] Borrower address not shown on reserve pop-up on returns.pl
- [[20794]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20794) Don't show holds tab when user doesn't have circulate_remaining_permissions

## Command-line Utilities

- [[20893]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20893) batchRebuildItemsTables.pl has incorrect parameter

## Hold requests

- [[21075]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21075) AutoUnsuspendHolds should unsuspend holds <= today

## I18N/L10N

- [[21029]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21029) "Suspend until" in modal in staff patron account is not translatable
- [[20709]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20709) Update GERMAN MARC frameworks to Updates 23-26 (Nov 2016, May and Apr 2018)

## Installation and upgrade (web-based installer)

- [[20745]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20745) indexing/searching not active at end of installation

## Lists

- [[17886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17886) Don't show option to add to existing list if there are no lists in staff

## MARC Bibliographic data support

- [[20700]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20700) Update MARC21 leader/007/008 codes
- [[19835]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19835) Update MARC frameworks to Updates 23+24+25 (Nov 2016, May and Dec 2017)

## OPAC

- [[20832]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20832) Opac user page crash when there is an overdue fine and not any rental charge for a patron
- [[18856]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18856) Cancel Waiting Hold in OPAC does not give useful message
- [[19849]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19849) Rebase of bug 16621 partially reverted bug 12509
- [[20507]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20507) Shelf browser does not update image sources when paging
- [[17869]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17869) Don't show pick-up library for list of holds in OPAC account when there is only one branch
- [[20876]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20876) The form_serialized_itype cookie is not used and should be removed

## Packaging

- [[20920]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20920) Plack timeout because of missing CGI::Compile Perl dependency
- [[20693]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20693) Plack fails, because 'libcgi-emulate-psgi-perl' package is not installed

## Patrons

- [[20008]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20008) Restrictions added from memberentry.pl have expiration date ignored if TimeFormat is 12hr
- [[20991]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20991) Error will reset category when editing a patron
- [[20903]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20903) Print payment receipt on child patron could end with server error
- [[20951]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20951) Koha::Patron::Discharge is missing use Koha::Patron::Debarments

## Reports

- [[20945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20945) Report params not escaped when downloading
- [[16653]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16653) reports/cat_issues_top.pl does not export "Count of checkouts" column as CSV

## Searching

- [[19873]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19873) Make it possible to search on value 0

## Searching - Elasticsearch

- [[17373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17373) Elasticsearch - Authority mappings for UNIMARC

## Searching - Zebra

- [[20697]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20697) Remove some Host-Item-Number noise from zebra-output.log when EasyAnalyticalRecords is not used

## Self checkout

- [[21054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21054) Extra closing body tag in sco-main.tt prevents slip printing

## Serials

- [[7136]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7136) Correct description of Grace period for subscriptions

## SIP2

- [[21020]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21020) Return branch not set for transfer when using SIP

## Staff Client

- [[20998]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20998) Non superlibrarians cannot search for patrons using the quicksearch at the top
- [[18521]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18521) Renew and search hotkeys are swapped on returns page.

## Templates

- [[20999]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20999) Remove invalid 'style="block"' from OPAC templates
- [[20559]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20559) Occurrences of loading-small.gif still exist
- [[20881]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20881) Order receiving: Price filter missing on_editing

## Test Suite

- [[20175]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20175) Set a correct default value for club_enrollments.date_created
- [[20906]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20906) Fix Debian 9 Test Failures

## Tools

- [[20084]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20084) Patron card creator: layouts Industrial2of5 and COOP2of5 broken with error "Invalid Characters"

## Web services

- [[21046]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21046) ILSDI - AuthenticatePatron returns a wrong borrowernumber if cardnumber is empty



# Release Notes for roundrock-v17.11.07-03

## System Administration

- [[20216]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20216) Editing itemtypes does not pull existing values correctly



# Release Notes for roundrock-v17.11.07-02

## Staff Client

- [[20998]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20998) Non superlibrarians cannot search for patrons using the quicksearch at the top



# Release Notes for roundrock-v17.11.07-01

## Acquisitions

- [[20892]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20892) Wrong basketgroup link in histsearch.pl
- [[20861]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20861) Correct EDI permissions on some pages
- [[20827]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20827) Can't add owner to a fund

## Architecture, internals, and plumbing

- [[20911]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20911) Search history page forms use 'GET' and this limits the number of entries that can be submitted
- [[20922]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20922) Koha::Number::Price must not be used in updatedatabase.pl
- [[20851]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20851) Missing module in circ/article-request-slip.pl
- [[18821]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18821) TrackLastPatronActivity is a performance killer
- [[20696]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20696) Remove a few ugly "eq undef" comparisons
- [[20767]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20767) "The method is not covered by tests!" should give more information

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[19970]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19970) Revise change of bug 19413 to work better for translations
- [[20760]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20760) Advanced Cataloging Editor - Rancor - AuthorisedValues are incorrectly fetched
- [[20829]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20829) 'Link to host item' gives internal server error

## Circulation

- [[20546]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20546) Shelving location not displayed on checkin
- [[17561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17561) ReserveSlip needs itemnumber for item level holds on same biblio
- [[20343]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20343) Show number of checkouts by itemtype in circulation.pl

## Fines and fees

- [[20285]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20285) Lost item refund won't always pay down lost item fee first

## Hold requests

- [[19972]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19972) Holds to pull should honor syspref "item-level_itypes"

## OPAC

- [[20763]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20763) AllowPurchaseSuggestionBranchChoice triggers error opac-suggestions.pl is visited without logging in

## Packaging

- [[17111]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17111) Automatic debian/control updates (oldstable/17.11.x)

## Patrons

- [[3886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=3886) Can't print receipt w/out allowing "Add or modify borrowers" permission

## Searching

- [[18799]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18799) XSLTresultsdisplay hides the icons
- [[20722]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20722) Searching only for an ITEMTYPECAT itemtype is impossible

## Staff Client

- [[20781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20781) 0 months is not a valid enrollment period and causes errors
- [[20652]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20652) Sort after item type search fails

## Templates

- [[20752]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20752) Files tab in patron account is not properly capitalized
- [[20791]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20791) Correct capitalization on 'Notices and slips' page

## Test Suite

- [[20191]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20191) OAI/Server.t still fails on slow servers


