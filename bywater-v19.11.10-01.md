
# Release Notes for bywater-v19.11.10-01

## Acquisitions

- [[25751]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25751) When an ORDERED suggestion is edited, the status resets to "No status"

## Architecture, internals, and plumbing

- [[26322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26322) REST API plugin authorization is not checked anymore
- [[26253]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26253) duplicated mana_config in etc/koha-conf.xml
- [[26331]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26331) svc/letters/preview is not executable which prevents CGI functioning
- [[21539]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21539) addorderiso2709.pl forces librarian to select a ccode and notforloan code when using MarcItemFieldsToOrder
- [[26228]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26228) Update gulpfile to work with Node.js v12
- [[26270]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26270) XISBN.t is failing since today

## Bywater Only

- NOT IN BUGZILLA - Fixing po files for 19.11.10
- NOT IN BUGZILLA - Merge branch 'new/security-release-19.11.10' into 19.11.x

## Cataloging

- [[26233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26233) Edit item date sort still does not sort correctly

## Circulation

- [[26362]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26362) Overdue report shows incorrect branches for patron, holdingbranch, and homebranch
- [[25584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25584) When a 'return claim' is added, the button disappears, but the claim date doesn't show up
- [[25958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25958) Allow LongOverdue cron to exclude specified lost values
- [[26076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26076) Paying selected accountlines in full may result in the error "You must pay a value less than or equal to $x"
- [[26078]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26078) "Item returns to issuing library" creates infinite transfer loop
- [[25783]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25783) Holds Queue treating item-level holds as bib-level

## Installation and upgrade (web-based installer)

- [[25448]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25448) Update German (de-DE) framework files

## OPAC

- [[26388]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26388) Renew all and Renew selected buttons should account for items that can't be renewed
- [[26041]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26041) Accessibility: The date picker calendar is not keyboard accessible
- [[26069]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26069) Twitter share button leaks information to Twitter
- [[26119]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26119) Patron attribute option to display in OPAC is not compatible with PatronSelfRegistrationVerifyByEmail

## Packaging

- [[25792]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25792) Rename 'ttf-dejavu' package to 'fonts-dejavu' for Debian 11
- [[25778]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25778) koha-plack puts duplicate entries into PERL5LIB when multiple instances named

## Reports

- [[17801]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17801) 'Top Most-circulated items' gives wrong results when filtering by checkout date
- [[26090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26090) Catalog by itemtype report fails if SQL strict mode is on

## REST API

- [[26271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26271) Call to /api/v1/patrons/<patron_id>/account returns 500 error if manager_id is NULL

## Searching

- [[17661]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17661) Differences in field ending (whitespace, punctuation) cause duplicate facets

## Searching - Elasticsearch

- [[26313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26313) "Show analytics" and "Show volumes" links don't work with Elasticsearch and UseControlNumber

## Self checkout

- [[25791]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25791) SCO print dialog pops up twice

## SIP2

- [[25903]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25903) Sending a SIP patron information request with a summary field flag in indexes 6-9 will crash server

## System Administration

- [[25005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25005) Admin Rights issue for Suggestion to Purchase

## Templates

- [[26324]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26324) Spelling error resizeable vs resizable
- [[26213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26213) Remove the use of jquery.checkboxes plugin when adding orders from MARC file

## Test Suite

- [[24147]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24147) Objects.t is failing randomly

## Tools

- [[26236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26236) log viewer does not translate the interface properly


