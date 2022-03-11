
# Release Notes for bywater-v21.05.12-01

## Acquisitions

- [[29895]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29895) Button [Add multiple items] stops responding when it's pressed and some multiple items added to basket
- [[29570]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29570) Unable to sort summary column of pending_orders table on parcel.pl by summary column
- [[29670]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29670) Restore functionality broken by bug 27708 for AcqCreateItem set to "placing an order"

## Architecture, internals, and plumbing

- [[29420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29420) HTTP status code incorrect when calling error pages directly under Plack/PSGI
- [[29966]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29966) SCO Help page passes flags while not needing authentication
- [[29785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29785) Koha::Object->messages must be renamed
- [[29809]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29809) StockRotationItems->itemnumber is poorly named
- [[29646]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29646) Bad or repeated opac-password-recovery attempt crashes on wrong borrowernumber
- [[29764]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29764) EmbedItems RecordProcessor filter POD incorrect
- [[29806]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29806) ->pickup_locations should always be called in scalar context
- [[18320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18320) patroncards/edit-layout.pl raises warnings
- [[29336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29336) Some authorised_value FKs are too short
- [[29758]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29758) CGI::param in list context in boraccount.pl warning
- [[18540]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18540) koha-indexdefs-to-zebra.xsl introduces MARC21 stuff into UNIMARC xslts
- [[29812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29812) C4::Context not included, but used in Koha::Token
- [[29804]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29804) Koha::Hold->is_pickup_location_valid explodes if empty list of pickup locations

## Bywater Only

- NOT IN BUGZILLA - Removing unit tests that are failing do to Koha::Logger issues
- NOT IN BUGZILLA - GitHub Actions - Switch koah-dpkg from 21.05 to 21.11
- NOT IN BUGZILLA - Remove failing Selenium tests, they pass locally
- NOT IN BUGZILLA - Bug 29931: [21.05.x] Check cookie status before continuing
- NOT IN BUGZILLA - Bug 29956: Prevent login form to be serialized into cookie
- NOT IN BUGZILLA - Fix translations for Koha 21.05.11
- NOT IN BUGZILLA - Increment version number for 21.05.10 release

## Cataloging

- [[29511]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29511) While editing MARC records, blank subfields appear in varying order

## Circulation

- [[28271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28271) Add the ability to set a new lost status when a claim is resolved
- [[27296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27296) Return claims should be filtered by default to show unresolved claims
- [[29495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29495) Issue link is lost in return claims when using 'MarkLostItemsAsReturned'
- [[11750]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11750) Overdue report does not limit patron attributes

## Command-line Utilities

- [[29054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29054) Stop warns from advance_notices.pl if not running in verbose mode

## Database

- [[30065]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30065) Correct errors in backporting of database updates

## Fines and fees

- [[29952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29952) Filter Paid Transactions Broken on Transactions tab in Staff
- [[29385]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29385) Add missing cash register support to SIP2

## Hold requests

- [[29043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29043) Items are processed but not displayed on request.pl before a patron is selected
- [[21652]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21652) reserves.waitingdate is set to current date by printing new hold slip
- [[3142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=3142) Standardize how OPAC and staff determine requestability

## ILL

- [[28932]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28932) Backend overriding status_graph element causes duplicate actions

## Notices

- [[29943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29943) Fix typo in notices yaml file

## OPAC

- [[29320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29320) Use OverDrive availability API V2
- [[29840]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29840) opac-reserve explodes if invalid biblionumber is passed

## Packaging

- [[29881]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29881) Remove SQLite2 dependency

## Patrons

- [[30090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30090) Don't export action buttons from patron results

## Reports

- [[28977]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28977) Most-circulated items (cat_issues_top.pl) is failing with SQL Mode ONLY_FULL_GROUP_BY

## SIP2

- [[29754]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29754) Patron fines counted twice for SIP when NoIssuesChargeGuarantorsWithGuarantees is enabled

## Templates

- [[30082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30082) Bibliographic details tab missing when user can't add local cover image
- [[29932]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29932) Phase out jquery.cookie.js: bibs_selected (Browse selected records)
- [[29933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29933) Fix stray usage of jquery.cookie.js plugin
- [[29967]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29967) Increase size of description fields for authorized values in templates
- [[29807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29807) Branches template plugin doesn't handle empty lists correctly

## Test Suite

- [[29862]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29862) TestBuilder.t fails with ES enabled
- [[29838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29838) No string interpolation when expected in t/db_dependent/ImportBatch.t
- [[29884]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29884) Missing test in api/v1/patrons.t

## Tools

- [[29722]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29722) Add some diversity to sample quotes
- [[29156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29156) File missing warning in Koha::UploadedFile should be for permanent files only
- [[28832]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28832) [21.05] Batch modification always clears permanent_location if it is mapped in frameworks
- [[29808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29808) Stock rotation fails to advance when an item is checked out from the branch that is the next stage

## Z39.50 / SRU / OpenSearch Servers

- [[19865]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19865) Side scroll bar in z39.50 MARC view


