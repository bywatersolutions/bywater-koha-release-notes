
# Release Notes for masscat-v21.05.04-07

## Architecture, internals, and plumbing

- [[29135]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29135) OAI should not include biblionumbers from deleteditems when determining deletedbiblios
- [[29134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29134) Patron search has poor performance when ExtendedAttributes enabled and many attributes match
- [[29243]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29243) PrepareItemrecordDisplay should not be called with empty string in defaultvalues

## Bywater Only

- NOT IN BUGZILLA - Revert "BWS-PKG - GitHub Actions - Use custom docker-compose file for koha-testing-docker"
- NOT IN BUGZILLA - GitHub Actions - Use custom docker-compose file for koha-testing-docker

## Circulation

- [[15812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15812) Checkout search with too many results (single character search)  causes poor performance or timeout
- [[29234]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29234) Transfers generated by stock rotation alert but do not initiate at checkin

## Hold requests

- [[29073]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29073) Hold expiration added to new holds when DefaultHoldExpirationdate turned off

## Plugin architecture

- [[29121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29121) Plugins with broken ->install prevent access to the plugins list

## Reports

- [[29225]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29225) Report subgroup does not appear consistently

## REST API

- [[29157]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29157) Cannot set date/date-time attributes to NULL

## Searching - Elasticsearch

- [[29284]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29284) Koha dies when an analytics search fails in Elasticsearch

## Staff Client

- [[29193]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29193) DataTables only showing 20 results on checkout search and patrons search on request.pl


