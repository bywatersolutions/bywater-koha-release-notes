
# Release Notes for mtpl-v20.05.05-01

## Acquisitions

- [[26497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26497) "Hide all columns" throws Javascript error on aqplan.pl
- [[26438]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26438) Follow up to bug 23463 - return from Koha::Item overwrites existing variable
- [[10921]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10921) You can edit an order even when it is in a closed basket

## Architecture, internals, and plumbing

- [[26260]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26260) elasticsearch>cnx_pool missing in koha-conf-site.xml.in
- [[16357]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16357) Plack error logs are not time stamped
- [[26434]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26434) Plugin dirs duplicates in @INC with plack
- [[26464]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26464) Code correction in opac-main when news_id passed

## Bywater Only

- NOT IN BUGZILLA - Bug 26562: [20.05.x] Removes 'searches' from localStorage on logout

## Cataloging

- [[19322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19322) Typo in UNIMARC field 140 plugin
- [[19327]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19327) Typo in UNIMARC field 128a plugin
- [[24780]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24780) 952$i stocknumber does not display in batch item modification
- [[15933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15933) Add cataloguing plugin to search for existing publishers in other records

## Circulation

- [[26224]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26224) Prevent double submit of header checkin form
- [[26424]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26424) Better performance of svc/checkouts

## Command-line Utilities

- [[25624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25624) Update patrons category script should allow finding null and not null and wildcards
- [[26448]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26448) koha-elasticsearch --commit parameter is not used
- [[26451]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26451) Small typo in bulkmarcimport.pl
- [[26407]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26407) fix query in 'title exists' in `search_for_data_inconsistencies.pl`

## Fines and fees

- [[26785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26785) JS errors in pos/pay.tt in 20.05.x
- [[26541]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26541) Apply discount button misleading

## Hold requests

- [[23485]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23485) Holds to pull (pendingreserves.pl) should list barcodes
- [[18958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18958) If patron has multiple record level holds on one record transferring first hold causes next hold to become item level
- [[26460]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26460) Wrong line ending (semicolon vs comma) in request.tt

## I18N/L10N

- [[26217]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26217) Move translatable strings out of templates into acq.js
- [[26256]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26256) Move translatable strings out of templates and into serials-toolbar.js
- [[26243]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26243) Move translatable strings out of templates and into circulation.js
- [[26118]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26118) Move translatable strings out of tags/review.tt and into tags-review.js
- [[26242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26242) Move translatable strings out of results.tt and into results.js
- [[26240]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26240) Move translatable strings out of sms_providers.tt and into sms_providers.js
- [[26230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26230) Move translatable strings out of item_search_fields.tt and into item_search_fields.js
- [[26225]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26225) Move translatable strings out of audio_alerts.tt and into audio_alerts.js

## Installation and upgrade (web-based installer)

- [[26548]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26548) [20.05] Update for 20.05.03.001 has wrong SQL

## Lists

- [[25913]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25913) Internal server error when calling get_coins on record with no title (245) but with 880 linked to 245

## MARC Authority data support

- [[25273]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25273) Elasticsearch Authority matching is returning too many results

## MARC Bibliographic record staging/import

- [[26231]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26231) bulkmarcimport.pl does not import authority if it already has a 001 field

## Notices

- [[26420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26420) Overdue notices script does not care about borrower's language, always takes default template

## OPAC

- [[25242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25242) Accessibility: The 'Holdings' table partially obscures navigation links at 200% zoom
- [[26512]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26512) Display issue with buttons for OPAC checkout note

## Patrons

- [[26556]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26556) Cities autocomplete broken in patron edition

## Searching - Elasticsearch

- [[25957]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25957) Elasticsearch 5.X - empty subfields cause error on suggestible fields
- [[24807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24807) Add "year" type to improve sorting by publication date
- [[25265]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25265) Elasticsearch - Batch editing items on a biblio can lead to incorrect index
- [[26507]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26507) New items not indexed

## Staff Client

- [[26249]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26249) keep_text class not set inconsistently in cat-search.inc
- [[26435]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26435) AutoSelfCheckID syspref description should warn it blocks OPAC access

## Templates

- [[25320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25320) Move translatable strings out of merge-record-strings.inc into merge-record.js
- [[26291]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26291) Move translatable strings out of z3950_search.inc into z3950_search.js
- [[26261]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26261) Split calendar.inc into include file and JavaScript file
- [[26245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26245) Remove unused functions from members.js
- [[26120]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26120) Remove the use of jquery.checkboxes plugin from tags review template
- [[26151]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26151) Remove the use of jquery.checkboxes plugin from suggestions management page
- [[26504]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26504) Remove the use of jquery.checkboxes plugin from checkout notes page
- [[25321]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25321) Move translatable strings out of strings.inc into the corresponding JavaScript
- [[26334]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26334) Move translatable strings out of members-menu.inc into members-menu.js
- [[26339]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26339) Move translatable strings out of addorderiso2709.tt into addorderiso2709.js
- [[25317]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25317) Move translatable strings out of additem.js.inc
- [[26049]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26049) Replace li with span class results_summary in UNIMARC intranet XSLT

## Test Suite

- [[26157]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26157) Redirect expected DBI warnings

## Tools

- [[26592]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26592) XSS vulnerability when ysearch is used
- [[26431]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26431) Use split button to offer choice of WYSIWYG or code editor for news
- [[26414]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26414) Unable to export Withdrawn status using CSV profile


