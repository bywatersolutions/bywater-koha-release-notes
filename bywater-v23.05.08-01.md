
# Release Notes for bywater-v23.05.08-01

## Architecture, internals, and plumbing

- [[35629]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35629) Redundant code in includes/patron-search.inc
- [[35491]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35491) Reverting waiting status for holds is not logged
- [[35309]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35309) Remove DT's fnSetFilteringDelay
- [[35405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35405) MarcAuthorities: Use of uninitialized value $tag in hash element at MARC/Record.pm line 202.

## Bywater Only

- NOT IN BUGZILLA - Fix count of unit tests in Auth.t

## Circulation

- [[35587]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35587) Items lose their lost status when check-in triggers a transfer even though BlockReturnOfLostItems is enabled
- [[35600]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35600) Prevent checkouts table to flicker
- [[35310]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35310) Current renewals 'view' link doesnt work if renewals correspond to an item no longer checked out

## Hold requests

- [[35489]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35489) Holds on items with no barcode are missing an input for itemnumber

## I18N/L10N

- [[35567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35567) Host-item in "Show analytics" link can be translated
- [[34900]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34900) The translation of the string "The " should depend on context

## Installation and upgrade (command-line installer)

- [[35698]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35698) Wrong bug number in db_revs/220600084.pl

## Lists

- [[35547]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35547) When using "Add to a list" button with more than 10 lists, "staff only" does not show up

## Notices

- [[30287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30287) Notices using HTML render differently in notices.pl

## OPAC

- [[35496]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35496) Placing an article request on the OPAC takes the user to their account page, but does not activate the article request tab
- [[35495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35495) Cancelling a hold on the OPAC takes the user to their account page, but does not activate the holds tab
- [[35492]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35492) Suspending/unsuspending a hold on the OPAC takes the user to their account page, but does not activate the holds tab
- [[35488]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35488) Placing a hold on the OPAC takes the user to their account page, but does not activate the holds tab

## Packaging

- [[35713]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35713) Remove debian/docs/LEEME.Debian

## Patrons

- [[25835]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25835) Include overdue report (under circulation module) as a staff permission
- [[35493]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35493) Housebound roles show as a collapsed field option when checked in CollapseFieldsPatronAddForm, even if housebound is off

## Plugin architecture

- [[35070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35070) Koha plugins implementing "background_jobs" hook can't provide view template

## Reports

- [[35498]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35498) SQL auto-complete should not prevent use of tab for spacing

## REST API

- [[32551]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32551) API requests don't carry language related information
- [[35658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35658) Typo in /patrons/:patron_id/holds
- [[35204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35204) REST API: POST endpoint /auth/password/validation dies on patron with expired password

## Searching - Zebra

- [[35455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35455) ICU does not strip = when indexing/searching

## Serials

- [[28012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28012) Error on saving new numbering pattern
- [[31297]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31297) Cannot add new subscription patterns from edit subscription page

## Staff interface

- [[35619]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35619) Change password form in patron account has misaligned validation errors

## System Administration

- [[31694]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31694) MARC overlay rules presets don't change anything if presets are translated
- [[34644]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34644) Add clarifying text to sysprefs to indicate that MarcFieldsToOrder is a fallback to MarcItemFieldsToOrder

## Templates

- [[35557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35557) LoadResultsCovers is not used (staff)

## Test Suite

- [[35598]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35598) selenium/authentication_2fa.t is still failing randomly

## Tools

- [[35696]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35696) Transit status not properly updated for items advanced in Stock Rotation tool
- [[35588]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35588) marcrecord2csv retrieves authorised values incorrectly for fields
- [[35579]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35579) marcrecord2csv searches authorised values inefficiently

## translate.koha-community.org

- [[35428]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35428) gulp po tasks do not clean temporary files

## Web services

- [[34893]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34893) ILS-DI can return the wrong patron for AuthenticatePatron


