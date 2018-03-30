
# Release Notes for bywater-v17.05.10-01

## Acquisitions

- [[20148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20148) Don't allow adding same user multiple times to a basket or an order

## Architecture, internals, and plumbing

- [[20145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20145) borrowers.datexpiry eq '0000-00-00' means expired?

## Bywater Only

- NOT IN BUGZILLA - Switch to using Docker for the rebaser
- NOT IN BUGZILLA - Skip rebase step unless branch is begins with 'bywater-v'
- NOT IN BUGZILLA - Update travis.yml to make unit testing first stage
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


