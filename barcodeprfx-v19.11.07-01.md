
# Release Notes for barcodeprfx-v19.11.07-01

## About

- [[25506]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25506) Perl undef warning on the "About Koha" page

## Acquisitions

- [[25507]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25507) PDF order print for German 2-pages is broken
- [[25545]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25545) Invoice page - Adjustments are not included in the Total + adjustments + shipment cost (Column tax. inc.)
- [[14543]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14543) Order lines updated that have a tax rate not in gist will have tax rate set to 0!
- [[25677]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25677) Checkbox options for EDI accounts cannot be enabled
- [[25473]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25473) Can't add order from MARC file, save button does nothing
- [[25563]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25563) Cannot submit "add order from MARC file" form after alert

## Architecture, internals, and plumbing

- [[25045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25045) Add a way to restrict anonymous access to public routes (OpacPublic behaviour)
- [[25634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25634) koha-foreach exits too early if any command has non-zero status
- [[25707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25707) Mappings update in bug 11529 causes incorrect MARC to DB data flow
- [[25567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25567) borrower_attribute_types.category_code must be set to undef if not set
- [[22522]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22522) API authentication breaks with updated Mojolicious version

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Fixing po files for 19.11.07

## Circulation

- [[25587]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25587) JavaScript issue - "clear" button doesn't reset some dropdowns
- [[24413]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24413) MarkLostItemsAsReturned functionality does not lift restrictions caused by long overdues

## Command-line Utilities

- [[22470]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22470) Missing the table name on misc/migration_tools/switch_marc21_series_info.pl
- [[25538]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25538) koha-shell should pass --login to sudo if no command

## Documentation

- [[25576]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25576) ILL requests Help does not take you to the correct place in the manual

## Fines and fees

- [[25526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25526) Using Write Off Selected will not allow for a different amount to be written off

## I18N/L10N

- [[25517]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25517) Koha.mo not found on package installations / Translations not working

## MARC Authority data support

- [[25653]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25653) Authorities search does not retain selection
- [[25428]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25428) Escaped HTML shows in authority detail view when subfield is a link

## MARC Bibliographic data support

- [[25701]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25701) Facets display in random order

## Notices

- [[24612]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24612) expirationdate blank if patron has more than one item from bib on hold

## OPAC

- [[23276]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23276) Don't show tags on tag cloud when tagging is disabled
- [[25597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25597) Javascript errors in self-checkout printslip.pl preventing printing
- [[25492]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25492) Your Account Menu button does nothing on mobile devices
- [[17842]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17842) Broken diacritics on records exported as MARC from cart

## Packaging

- [[25633]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25633) Update debian/control.ini file for 20.05 release cycle
- [[25591]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25591) Update list-deps for Debian 10 and Ubuntu 20.04
- [[25693]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25693) Correct permissions must be set on logdir after an upgrade

## Patrons

- [[23808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23808) Creating Child Guarantee doesn't populate Guarantor Information
- [[25452]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25452) Alternate email contact not displayed

## REST API

- [[25327]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25327) Cannot access API spec
- [[24003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24003) REST API should set C4::Context->userenv
- [[25411]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25411) Plugin routes cannot have anonymous access
- [[24862]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24862) Wrong behaviour on anonymous sessions
- [[24909]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24909) Add unprivileged route to get a bibliographic record

## Serials

- [[25696]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25696) Test prediction pattern button is invalid HTML

## Staff Client

- [[25537]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25537) Page reload at branchtransfers.pl loses destination branch
- [[25521]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25521) NewItemsDefaultLocation description should not mention cart_to_shelf.pl

## System Administration

- [[25394]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25394) Cronjob path in the AuthorityMergeLimit syspref description is wrong
- [[25675]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25675) System preference PatronSelfRegistration incorrectly described
- [[25601]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25601) Error when unsetting default checkout, hold and return policy for a specific library

## Templates

- [[25615]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25615) Empty select in "Holds to pull" filters

## Test Suite

- [[25623]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25623) Some tests in oauth.t do not roll back
- [[24229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24229) /items API tests fail on Ubuntu 18.04

## Tools

- [[25557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25557) Column config table in acquisitions order does not match the acq table in baskets


