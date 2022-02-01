
# Release Notes for roundrock-v21.05.09-01

## Acquisitions

- [[24866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24866) Display budget hierarchy in the budget dropdown menu used when placing a new order
- [[29419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29419) Suggest for purchase clears item type, quantity, library and reason if bib exists

## Architecture, internals, and plumbing

- [[29702]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29702) all_libraries routine in library groups make a DB call per member of group
- [[29789]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29789) Unused $error in cataloguing/additem.pl

## Bywater Only

- NOT IN BUGZILLA - Fix translations for Koha 21.05.09
- NOT IN BUGZILLA - Bug 29541: Restrict access to patron's image to borrowers => * and circulate => *
- NOT IN BUGZILLA - Bug 29903: Prevent messages to be deleted from unauthorised users
- NOT IN BUGZILLA - Bug 29542: Prevent access to private list to non authorized users
- NOT IN BUGZILLA - Bug 29914: Remove 'Use of uninitialized value ' warnings
- NOT IN BUGZILLA - Bug 29544: (QA follow-up) Simplify code
- NOT IN BUGZILLA - Bug 29540: Raise flagsrequired in modrequest
- NOT IN BUGZILLA - Bug 28735: Self-checkout users can access opac-user.pl for sco user when not using AutoSelfCheckID
- NOT IN BUGZILLA - Bug 29543: Set autocomplete off for SCO login fields
- NOT IN BUGZILLA - Bug 26102: Prevent XSS when To.json is used: unimarc_field_4XX.tt
- NOT IN BUGZILLA - DBRev 21.05.08.002

## Circulation

- [[29476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29476) Earliest renewal date is displayed wrong in circ/renew.pl for issues with auto renewing

## Fines and fees

- [[29457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29457) Fee Cancellation records the wrong manager_id

## Hold requests

- [[29736]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29736) Error when placing a hold for a club without members
- [[29553]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29553) Holds: Can't call method "notforloan" on an undefined value when placing a hold

## Notices

- [[29557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29557) Auto renew notices should handle failed renewal due to patron expiration
- [[29381]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29381) Auto-renewal digest messages are sent on every cron run

## OPAC

- [[17127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17127) Can't hide MARC21 500 and others with NotesToHide
- [[29604]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29604) Term highlighting adds unwanted pseudo element in the contentblock of OPAC details page
- [[29696]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29696) "Suggest for purchase" missing biblio link

## Packaging

- [[28926]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28926) Update cpanfile for Mojolicious::Plugin::OpenAPI v2.16

## Reports

- [[29530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29530) When NumSavedReports is set, show value in pull down of entries
- [[29680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29680) Reports menu 'Show SQL code' wrong border radius
- [[29729]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29729) If serials_stats.pl returns no results dataTables get angry

## REST API

- [[29508]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29508) GET /patrons/:patron_id should use Koha::Patrons->search_limited
- [[29506]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29506) objects.search should call search_limited if present
- [[29503]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29503) GET /patrons should use Koha::Patrons->search_limited
- [[29018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29018) Deleting patrons from REST API doesn't do any checks or move to deletedborrowers

## Searching - Elasticsearch

- [[29436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29436) Cannot reorder facets in staff interface elasticsearch configuration

## System Administration

- [[29591]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29591) Add autorenew_checkouts to BorrowerMandatory/Unwanted fields system preferences

## Templates

- [[29571]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29571) Mainpage : "All libraries" pending suggestions are visible only if the current library has suggestions


