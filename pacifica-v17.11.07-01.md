
# Release Notes for pacifica-v17.11.07-01

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



# Release Notes for pacifica-v17.11.06-06

## Architecture, internals, and plumbing

- [[20977]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20977) Javascript vars used in confirm_deletion in catalog.js do not match strings in catalog-strings.inc


