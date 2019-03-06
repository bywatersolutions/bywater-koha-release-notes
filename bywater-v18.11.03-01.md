
# Release Notes for bywater-v18.11.03-01

## Architecture, internals, and plumbing

- [[22144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22144) Add method metadata() to Koha::Biblio

## Bywater Only

- NOT IN BUGZILLA - Remove failing tests from Cache.t
- NOT IN BUGZILLA - Don't alter MarkLostItemsAsReturned if it has already been upgraded
- NOT IN BUGZILLA - Add transliteration for Ž in ICU chains
- NOT IN BUGZILLA - Restore the storing of itemnumber for writeoffs
- NOT IN BUGZILLA - Bug XXX - Add option to SIP2 config to send shelving location in CR instead of collection code
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Bux XXX - Adding f17I and f18K options to marc21_leader.tt for Albright
- NOT IN BUGZILLA - Bug XXX - Add ability to disable demagnitizing items via SIP2 for arbitrary patron categories
- NOT IN BUGZILLA - Reduce ambiguity for selecting opac_news.timestamp, affects only a few partners
- NOT IN BUGZILLA - Removing koha-upgrade-schema from post-install tasks
- NOT IN BUGZILLA - Adding custom ProxyPass and allow SetEnv options to plack configs
- NOT IN BUGZILLA - Add pages.pl and pages.tt for Koha as a CMS
- NOT IN BUGZILLA - Setting use_zebra_facets to 0 in koha-conf template files
- NOT IN BUGZILLA - BWS Patch: All custom zebra indexes

## Cataloging

- [[585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=585) Using 'document.forms[0]' notation prevents use of other forms on page

## SIP2

- [[22076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22076) SIP checkin for withdrawn item returns ok in checkin response
- [[22043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22043) SIP Checkin Response alert flag set to often set to Y incorrectly
- [[22016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22016) Always send CT field for SIP checkin, even if empty
- [[22014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22014) Add ability to send "00" in SIP CV field on checkin success

## Web services

- [[19945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19945) ILSDI - Return the reason a reserve is impossible


