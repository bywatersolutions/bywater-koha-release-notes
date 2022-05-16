
# Release Notes for bywater-v21.05.14-01

## Architecture, internals, and plumbing

- [[30406]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30406) Our DT tables not filtering on the correct column if hidden by default
- [[29771]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29771) Get rid of CGI::param in list context warnings
- [[30172]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30172) Background jobs failing due to race condition

## Bywater Only

- NOT IN BUGZILLA - Translation fixes for 21.05.14

## Cataloging

- [[26328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26328) incremental barcode generation fails when incorrectly converting strings to numbers

## Circulation

- [[30222]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30222) Auto_renew_digest still sends every day when renewals are not allowed

## Hold requests

- [[30583]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30583) Hold system broken for translated template
- [[29704]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29704) Holds reminder emails should allow configuration for a specific number of days
- [[29338]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29338) Reprinting holds slip with updated expiration date

## OPAC

- [[30220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30220) Purchase suggestion defaults to first library
- [[29482]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29482) Terminology: This item belongs to another branch.

## Patrons

- [[28943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28943) Lower the risk of accidental patron deletion by cleanup_database.pl

## Searching - Elasticsearch

- [[30142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30142) ElasticSearch MARC mappings should not accept whitespaces

## Serials

- [[30035]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30035) Wrong month name in numbering pattern

## SIP2

- [[30118]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30118) holds_block_checkin behavior is different in Koha and in SIP

## System Administration

- [[29020]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29020) Missing Background jobs link in admin-home
- [[29875]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29875) Update text on MaxReserves system preference to describe functionality.

## Test Suite

- [[19169]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19169) Add a test to detect unneeded 'atomicupdate' files


