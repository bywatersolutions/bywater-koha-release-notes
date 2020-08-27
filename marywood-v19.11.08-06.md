
# Release Notes for marywood-v19.11.08-06

## Acquisitions

- [[25750]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25750) Fallback to ecost_tax_included, ecost_tax_excluded not happening when no 'Actual cost' entered
- [[25611]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25611) Changing the vendor when creating the basket does not keep that new vendor

## Architecture, internals, and plumbing

- [[26163]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26163) Add plugin directories to PERL5LIB
- [[26000]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26000) Holiday exceptions are incorrectly cached for an individual branch
- [[25875]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25875) Patron displayed multiple times in add user search if they have multiple sub permissions
- [[24986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24986) Maximum row size reached soon for borrowers and deletedborrowers

## Bywater Only

- NOT IN BUGZILLA - Fix unit test for t/db_dependent/XISBN.t, it is making a bad assumption
- NOT IN BUGZILLA - GitHub Actions - Add Slack notifications including failures
- NOT IN BUGZILLA - Add missing accountlines relationship to Borrower
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Fixing po files for 19.11.08

## Cataloging

- [[25553]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25553) Edit item date sort does not sort correctly

## Circulation

- [[26136]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26136) Prevent double submit of checkin form
- [[25940]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25940) Two separate print dialogs when checking in/transferring an item
- [[25969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25969) Checking in a found hold at a different branch then confirming the hold causes internal server error

## Custom For Instance

- NOT IN BUGZILLA - Update Dematic module

## Hold requests

- [[23820]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23820) Club hold pickup locations should be able to default to patron's home library
- [[25789]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25789) New expiration date on placing a hold in staff interface can be set to a date in the past

## Installation and upgrade (web-based installer)

- [[25491]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25491) Perl warning at the login page of installer

## MARC Bibliographic record staging/import

- [[25861]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25861) [19.11] Cannot copy MARC frameworks

## OPAC

- [[25434]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25434) When viewing cart on small screen sizes selections-toolbar is hidden
- [[22672]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22672) Replace <i> tags with <em> AND <b> tags with <strong> in the OPAC
- [[22807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22807) Accessibility: Add 'Skip to main content' link
- [[25151]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25151) Accessibility: The 'Your cart' page does not contain a level-one header
- [[25239]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25239) Accessibility: The 'Confirm hold page' contains semantically incorrect headings
- [[25154]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25154) Accessibility: The 'Search results' page does not use heading markup where content is introduced
- [[25236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25236) Accessibility: The 'Refine your search' box contains semantically incorrect headings
- [[25238]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25238) Accessibility: Multiple 'H1' headings exist in the full record display
- [[11994]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11994) Fix OpenSearch discovery in the OPAC
- [[24352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24352) Wrong labels displaying in result list with OpacItemLocation

## Packaging

- [[25509]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25509) Remove useless libjs-jquery dependency

## Patrons

- [[25858]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25858) Borrower permissions are broken by update from bug 22868

## REST API

- [[25570]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25570) Listing requests should be paginated by default

## Searching - Elasticsearch

- [[25864]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25864) Case sensitivity breaks searching of some fields in ES5

## Searching - Zebra

- [[23086]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23086) Search for collection is broken

## SIP2

- [[25805]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25805) SIP will show hold patron name (DA) as something like C4::SIP::SIPServer=HASH(0x88175c8) if there is no patron

## Staff Client

- [[25756]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25756) Empty HTML table row after OPAC "Appearance" preferences

## Templates

- [[25447]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25447) Terminology: Fix button text "Edit biblio"

## Tools

- [[25845]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25845) Cannot limit system logs to 'api' interface
- [[4985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=4985) Copy a change on the calendar to all libraries

## Web services

- [[25793]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25793) OAI 'Set' and 'Metadata' dropdowns broken by OPAC jQuery upgrade


