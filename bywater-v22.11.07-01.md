
# Release Notes for bywater-v22.11.07-01

## About

- [[33877]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33877) Fix teams.yaml

## Acquisitions

- [[34006]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34006) [22.11] Keep the current option for funds in receiving returns an error 500 or saves wrong fund
- [[33748]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33748) UI issue on addorderiso2709.pl page
- [[33663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33663) Don't hide Suggestions link in side navigation when suggestion preference is disabled
- [[33421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33421) Filtering purchase suggestions by status does not work if All Libraries is selected
- [[33340]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33340) Correct formatting of English 1-page order PDF when the basket group covers multiple pages

## Architecture, internals, and plumbing

- [[33934]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33934) 'No encryption_key in koha-conf.xml' needs more detail
- [[32060]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32060) Improve performance of Koha::Item->columns_to_str
- [[32464]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32464) Koha::Item->as_marc_field obsolete option mss
- [[33803]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33803) Some scripts contain info about tab width
- [[33854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33854) Typo in ImportBatchProfiles controller
- [[33718]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33718) _new_Zconn crashes on a bug in t::lib::Mocks::mock_config
- [[30649]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30649) Vendor EDI account passwords should be encrypted in the database
- [[33167]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33167) Cleanup staff interface catalog details page

## Authentication

- [[33815]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33815) Crash when librarian changes their own username in the staff interface
- [[33675]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33675) Add CSRF protection to OAuth/OIDC authentication
- [[33708]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33708) OAuth/OIDC authentication for the staff interface requires OPAC enabled

## Bywater Only

- NOT IN BUGZILLA - Fix translations for Koha 22.11.07
- NOT IN BUGZILLA - Bug 33595: (bug 26628 follow-up) Fix authorization for tools-home.pl

## Cataloging

- [[33247]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33247) Deleted authority still on results list
- [[32959]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32959) Item templates will apply the same barcode each time template is applied if autobarcode is enabled
- [[33686]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33686) Update plugin unimarc_field_100.pl 'Script of title' with 2022 values
- [[33624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33624) Using Browser "Back" button in Batch Record Modification causes biblio options to be displayed

## Circulation

- [[33838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33838) Offline circulation interface error on return
- [[33362]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33362) Return claims can be un-resolvable if issue_id is set but no issue is found in issues or old_issues
- [[33220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33220) Recalls to pull should not show in transit or allocated items
- [[32878]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32878) Make it impossible to renew the item if it has active item level hold

## Command-line Utilities

- [[33717]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33717) Typo in search_for_data_inconsistencies.pl

## ERM

- [[32932]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32932) Re-structure Vue router-links to use "name" instead of urls
- [[33823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33823) KohaTable vue component action buttons spacing differ from kohaTable

## Hold requests

- [[33761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33761) Holds queue is not selecting items with completed transfers
- [[33791]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33791) $hold->fill does not set itemnumber when checking out without confirming hold

## ILL

- [[21983]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21983) Better handling of deleted biblios on ILL requests
- [[33786]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33786) ILL requests table pagination in patron ILL history is transposing for different patrons
- [[22440]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22440) Improve ILL page performance by moving to server side filtering
- [[33762]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33762) Restore page-section in ILL

## Installation and upgrade (web-based installer)

- [[33935]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33935) Installer list deleted files which shows warning in the logs

## MARC Authority data support

- [[33138]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33138) Don't copy tag 147 to all MARC frameworks, since it should only be used in a separate NAME_EVENT framework

## MARC Bibliographic data support

- [[33865]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33865) JS error when importing a staged MARC record file

## OPAC

- [[33902]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33902) On opac-detail.tt the libraryInfoModal is outside of HTML tags
- [[33813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33813) Accessibility: Lists button is not clearly identified
- [[33697]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33697) Remove deprecated RecordedBooks (rbdigital) integration
- [[33821]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33821) OPAC flatpickr no longer allows for direct input of date
- [[33767]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33767) Accessibility: The 'OPAC results' page contains semantically incorrect headings
- [[29993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29993) Syndetics cover images do not display in browse shelf when scrolling from the first page
- [[21330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21330) Add XSLT for authority detail page in OPAC

## Packaging

- [[33371]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33371) Add 'koha-common.service' systemd service

## Patrons

- [[33882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33882) member.tt Date of birth column makes it difficult to hide the age hint
- [[33875]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33875) Missing closing tag a in API key management page
- [[33829]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33829) Cannot add patron to patron list if PatronAutoComplete is off

## Reports

- [[33792]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33792) reserves_stats.pl ignores filled holds without itemnumber
- [[33713]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33713) Report batch operations should open in new tab

## Searching

- [[33297]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33297) Typo system preference RetainPatronSearchTerms in DB revs 220600044.pl

## SIP2

- [[33411]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33411) SIP2 includes other guarantees with the same guarantor when calculating against NoIssuesChargeGuarantees

## Staff interface

- [[33788]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33788) Items tab shows all previous borrowers instead of 3
- [[33463]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33463) 'Actions' column on plugins table should not be sortable

## System Administration

- [[33787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33787) Remove option to archive system debit types
- [[32775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32775) Ordering when there are multiple languages within a language group is wrong

## Templates

- [[33524]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33524) Use template wrapper for tabs: Authority editor
- [[33892]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33892) Use template wrapper for tabs: OPAC authority detail
- [[33883]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33883) "Make sure to copy your API secret" message overlaps text
- [[33891]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33891) Use template wrapper for tabs: OPAC advanced search
- [[33525]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33525) Use template wrapper for tabs: Basic MARC editor
- [[33779]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33779) Terminology: biblio record
- [[33859]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33859) Use the phrase 'Identity providers' instead of 'Authentication providers'
- [[33721]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33721) Show inactive funds in invoice.tt out of order
- [[33735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33735) Misspelling in SMS provier
- [[33553]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33553) Unecessary GetCategories calls in template
- [[33599]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33599) Use template wrapper for breadcrumbs: Various
- [[32914]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32914) Use template wrapper for batch record deletion and modification templates
- [[33158]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33158) Use template wrapper for authorized values and item types administration tabs
- [[33707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33707) News vs Quote of the day styling on staff interface main page
- [[33705]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33705) Tables have configure button even if they are not configurable

## Test Suite

- [[33834]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33834) api/v1/ill_requests.t fails randomly
- [[33777]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33777) Get Jenkins green again for Auth_with_shibboleth.t
- [[33743]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33743) xt/find-missing-filters.t parsing files outside of git repo
- [[33719]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33719) Search.t: too much noise about ContentWarningField
- [[32648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32648) Search.t is failing if run after Filter_MARC_ViewPolicy.t

## Tools

- [[26611]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26611) Required match checks don't work for authority records
- [[31585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31585) "ACQUISITION ORDER" action missing from log viewer search form
- [[33010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33010) CheckinSlip doesn't return checkins if checkout library and checkin library differ


