
# Release Notes for plano-v18.11.10-02

## Authentication

- [[23771]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23771) CAS/Shib Authentication can fail when multiple users with no userid/cardnumber defined and one of them is locked

## Reports

- [[23626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23626) Add a system preference to limit the number of rows of data used when charting or exporting report results



# Release Notes for plano-v18.11.10-01

## Acquisitions

- [[22786]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22786) Can create new funds for locked budgets
- [[23338]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23338) Cannot specify replacement price when ordering from file if not using fields to order
- [[23294]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23294) Restore actual cost input field on order page
- [[23251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23251) EDI Order line incorrectly terminated when it ends with a quoted apostrophe

## Architecture, internals, and plumbing

- [[23237]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23237) Plugin allow [% INCLUDE %] from template

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[22830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22830) correct for loop in value_builder/unimarc_field_4XX.pl value_builder
- [[23436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23436) Save to 'undefined' showing in Advanced cataloging editor
- [[21518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21518) Material type "three-dimensional artifact" displays as "visual material"

## Circulation

- [[23273]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23273) Downloading from overdues.pl doesn't use set filters
- [[23518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23518) Problem with borrower search  autocomplete
- [[23408]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23408) Relatives' checkout table columns are not configured properly

## Command-line Utilities

- [[23345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23345) Wrong parameter name in koha-dump usage statement

## Database

- [[23265]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23265) Update to DB revision 16.12.00.032 fails: Unknown column 'me.item_level_hold'

## Hold requests

- [[23502]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23502) Staff client "revert status" buttons should not depend on SuspendHoldsIntranet preference

## I18N/L10N

- [[10492]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10492) Translation problems with TT directives in po files

## MARC Authority data support

- [[23437]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23437) When UseAuthoritiesForTracing is 'Use' we should use series authorities

## MARC Bibliographic record staging/import

- [[23324]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23324) Need an ISBN normalization routine

## OPAC

- [[23530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23530) Opac-basket.pl script accidentally displays 'hidden' items
- [[23210]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23210) login4tags should be a link
- [[23151]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23151) Patron self modification sends null dateofbirth
- [[23099]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23099) OPAC Search result sorting "go" button flashes on page load

## Searching

- [[11677]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11677) Limit to Only items currently available for loan or reference not working

## Searching - Elasticsearch

- [[22524]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22524) Elasticsearch - Date range in advanced search

## SIP2

- [[23057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23057) If checked_in_ok is set and item is not checked out, alert flag is supressed for *any* reason

## Staff Client

- [[21716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21716) Item Search hangs when \ exists in MARC fields

## System Administration

- [[23309]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23309) Can't add new subfields to bibliographic frameworks in strict mode

## Templates

- [[23446]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23446) Fix display issue with serials navigation
- [[23226]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23226) Remove type attribute from script tags: Cataloging

## Tools

- [[22799]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22799) Batch item modification is case sensitive

## Z39.50 / SRU / OpenSearch Servers

- [[23242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23242) Error when adding new Z39.50/SRU server in DB strict mode



# Release Notes for plano-v18.11.09-05

## SIP2

- [[22037]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22037) regression: guarantor no longer blocked (debarred) if child is over limit, when checking out via SIP.



# Release Notes for plano-v18.11.09-04

## Reports

- [[23624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23624) Count rows in report without (potentially) consuming all memory


