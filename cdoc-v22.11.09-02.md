
# Release Notes for cdoc-v22.11.09-02

## Acquisitions

- [[34305]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34305) If actual cost is negative, wrong price will display in the acq details tab
- [[34469]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34469) Modifying an order line of a standing order will delete linked invoice ID
- [[34452]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34452) Button 'Update adjustments' is hidden

## Architecture, internals, and plumbing

- [[34193]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34193) Default HTTPS template has outdated SSLProtocol value
- [[34354]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34354) Job progress typo
- [[34056]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34056) authorised-values API client file is missing -api-client suffix
- [[34470]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34470) Real Time Holds Queue - make random numbers play nice with forked processes
- [[34316]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34316) account->add_credit does not rethrow exception

## Authentication

- [[34028]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34028) Two factor authentication (2FA) shows the wrong values for manual entry

## Bywater Only

- NOT IN BUGZILLA - Fix translations for Koha 22.11.09
- NOT IN BUGZILLA - Bug 33881: Clear self-check JWT during auth kick out
- NOT IN BUGZILLA - Bug 30524: (QA follow-up) Fix tests

## Cataloging

- [[33755]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33755) Profile used is not saved when importing records

## Circulation

- [[34601]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34601) Cannot manage suggestions without CSRF error
- [[34289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34289) UI issue on checkin page when checking the forgive fines checkbox
- [[34279]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34279) overduefinescap of 0 is ignored, but overduefinescap of 0.00 is enforced
- [[33992]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33992) Only consider the date when labelling a waiting recall as problematic

## Command-line Utilities

- [[34213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34213) False POD for matchpoint option in import_patrons.pl

## ERM

- [[34447]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34447) "Actions" columns are exported

## Fines and fees

- [[34332]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34332) Syntax error in point of sale email template
- [[32271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32271) Overdue fines cap (amount) set to 0.00 when editing rule
- [[33028]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33028) Wrongly formatted monetary amounts in circulation rules break scripts and calculations

## Hold requests

- [[30846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30846) "If any unavailable" doesn't consider negative notforloan values as unavailable

## I18N/L10N

- [[34334]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34334) 'Item(s)' in MARC detail view untranslatable

## ILL

- [[34133]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34133) ILL table should be sorted by request id descending by default

## Installation and upgrade (web-based installer)

- [[34337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34337) Web installer doesn't install patrons when select all is used

## MARC Authority data support

- [[33978]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33978) Adding authority from automatic linker closes imported record

## Notices

- [[34059]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34059) advance_notices.pl -c --digest-per-branch does not work as intended

## OPAC

- [[33848]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33848) Enabling Coce in the OPAC breaks cover images on bibliographic detail page
- [[34155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34155) OPAC item level holds "force" option broken

## Packaging

- [[28493]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28493) Make koha-passwd display the username

## Patrons

- [[34435]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34435) get_password_expiry_date should not modify its parameter
- [[34117]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34117) Duplicate patron sets dateenrolled incorrectly
- [[33117]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33117) Patron checkout search not working if searching with second surname

## REST API

- [[34024]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34024) REST API should not allow changing the pickup location on found holds
- [[32739]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32739) REST API: Extend endpoint /auth/password/validation for cardnumber
- [[34365]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34365) Hold cancellation request workflow cannot be triggered on API
- [[34387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34387) API docs tags missing descriptions

## Searching

- [[33140]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33140) Use facet label value in mouseover title attribute of facet removal link

## Serials

- [[30451]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30451) Delete a subscription deletes the linked order

## System Administration

- [[34269]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34269) Regression in circulation rules for 'similar' patron categories

## Templates

- [[34343]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34343) Z39.50 search background not updated
- [[31667]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31667) Merge 'tip' and 'hint' classes
- [[34493]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34493) Bad indenting in search_indexes.inc

## Tools

- [[34181]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34181) Batch patron modification tool missing checkboxes to clear field values


