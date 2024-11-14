
# Release Notes for montgomery-v24.05.05-01

## Acquisitions

- [[38183]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38183) Can't set suggestion manager when there are multiple tabs

## Architecture, internals, and plumbing

- [[37861]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37861) Fix XSS vulnerability in barcode append function

## Authentication

- [[36822]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36822) When creating a new patron via LDAP or Shibboleth 0000-00-00 is inserted for invalid updated_on

## Cataloging

- [[35125]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35125) AutoCreateAuthorities creates separate authorities when thesaurus differs, even with LinkerConsiderThesaurus set to Don't
- [[38211]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38211) New bibliographic record in non-default framework opens in default on first edit

## Circulation

- [[38199]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38199) Printing transfer slips from circ/returns.pl doesn't set focus properly ( 24.05.x and below )

## Fines and fees

- [[34585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34585) "When to charge" columns value not copied when editing circulation rule

## Hold requests

- [[38148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38148) Check value of holdallowed circ rule properly (Bug 29087 follow-up)

## I18N/L10N

- [[38164]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38164) Translation process is broken

## MARC Authority data support

- [[38056]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38056) Search term after deleting an authority shouldn't be URI encoded

## Notices

- [[37891]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37891) Editing a notice's name having SMSSendDriver disabled causes notice to be listed twice

## OPAC

- [[37724]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37724) Remove Koha version number from public generator metadata
- [[37339]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37339) Default messaging preferences are not applied when self registering in OPAC

## Patrons

- [[32530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32530) When duplicating child card, guarantor is not saved
- [[37786]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37786) members/cancel-charge.pl needs CSRF protection

## Reports

- [[37270]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37270) Deleting a report from the actions menu on a list of saved reports does not work

## Searching

- [[37979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37979) typo in PQF index : index.koha.classification-soruce

## Searching - Elasticsearch

- [[37953]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37953) Incorrect handling of DisplayLibraryFacets in previous database update 23.12.000.36

## Staff interface

- [[35191]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35191) Make entries per page configurable for items table on staff detail page

## Tools

- [[33339]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33339) Formula injection (CSV Injection) in export functionality
- [[37961]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37961) Inventory followup fails by POSTing without an op or csrf_token


