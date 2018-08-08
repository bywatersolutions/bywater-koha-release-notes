
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


