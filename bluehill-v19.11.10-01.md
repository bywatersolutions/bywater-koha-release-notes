
# Release Notes for bluehill-v19.11.10-01

## Acquisitions

- [[25751]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25751) When an ORDERED suggestion is edited, the status resets to "No status"
- [[25887]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25887) Filtering funds by library resets to empty in library pull down
- [[25599]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25599) Allow use of cataloguing placeholders when ACQ framework is used creating new record (UseACQFrameworkForBiblioRecords)
- [[25499]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25499) Fund code column is empty when closing a budget

## Architecture, internals, and plumbing

- [[26341]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26341) Database update for bug 21443 is not idempotent and will destroy settings
- [[26374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26374) Update for 19974 is not idempotent
- [[26322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26322) REST API plugin authorization is not checked anymore
- [[26253]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26253) duplicated mana_config in etc/koha-conf.xml
- [[26331]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26331) svc/letters/preview is not executable which prevents CGI functioning
- [[21539]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21539) addorderiso2709.pl forces librarian to select a ccode and notforloan code when using MarcItemFieldsToOrder
- [[26228]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26228) Update gulpfile to work with Node.js v12
- [[26270]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26270) XISBN.t is failing since today
- [[24663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24663) OPACPublic must be tested for all opac scripts
- [[25360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25360) Use secure flag for CGISESSID cookie
- [[23634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23634) Privilege escalation vulnerability for staff users with 'edit_borrowers' permission and 'OpacResetPassword' enabled
- [[26000]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26000) Holiday exceptions are incorrectly cached for an individual branch
- [[20882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20882) URI column in the items table is limited to 255 characters
- [[25950]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25950) REMOTE_ADDR set to null if client_ip in X-Forwarded-For matches a koha_trusted_proxies value

## Bywater Only

- NOT IN BUGZILLA - Fixing po files for 19.11.10
- NOT IN BUGZILLA - Merge branch 'new/security-release-19.11.10' into 19.11.x
- NOT IN BUGZILLA - Merge branch 'new/security-release-19.11.09' into 19.11.x
- NOT IN BUGZILLA - Fixing po files for 19.11.09

## Cataloging

- [[26368]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26368) Add support for OCLC Encoding level values
- [[26233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26233) Edit item date sort still does not sort correctly

## Circulation

- [[26510]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26510) Transport Cost Matrix editor doesn't show all data when HoldsQueueSkipClosed is enabled
- [[26362]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26362) Overdue report shows incorrect branches for patron, holdingbranch, and homebranch
- [[25584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25584) When a 'return claim' is added, the button disappears, but the claim date doesn't show up
- [[25958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25958) Allow LongOverdue cron to exclude specified lost values
- [[26076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26076) Paying selected accountlines in full may result in the error "You must pay a value less than or equal to $x"
- [[26078]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26078) "Item returns to issuing library" creates infinite transfer loop
- [[25783]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25783) Holds Queue treating item-level holds as bib-level
- [[26361]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26361) JS error on returns.tt in 20.05
- [[26012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26012) Date in 'Paid for' information not formatted to Time/DateFormat system preferences
- [[25724]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25724) Transferred item checked in to shelving cart has cart location removed when transfer is filled
- [[25293]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25293) Don't call escapeHtml on null
- [[25868]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25868) Transfers page must show effective itemtype
- [[25726]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25726) Holds to Pull made empty by pathological holds
- [[25566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25566) Change in DecreaseLoanHighHolds behaviour
- [[25850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25850) CalcDateDue freezes with 'useDaysMode' set to 'Dayweek' and the due date lands on a Sunday
- [[25890]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25890) Checkouts table not sorting on check out date correctly

## Command-line Utilities

- [[25853]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25853) update_patrons_category.pl has incorrect permissions in repo
- [[25683]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25683) update_patron_categories.pl should recognize no fine history = 0 outstanding fines

## Database

- [[24379]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24379) Patron login attempts happen to be NULL instead of 0
- [[24640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24640) quotes.timestamp should default to NULL

## Fines and fees

- [[26376]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26376) Add itemnumber to writeoffs

## Hold requests

- [[26387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26387) Suppress Holds Queue warning if hold is bib level and has an itemtype set

## I18N/L10N

- [[25922]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25922) aria-labels are currently not translatable
- [[25443]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25443) Improve translation of "Select the host record to link%s to"

## Installation and upgrade (web-based installer)

- [[25448]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25448) Update German (de-DE) framework files

## Label/patron card printing

- [[25852]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25852) If a layout is edited, the layout type will revert to barcode

## OPAC

- [[21066]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21066) Replace opac_news.timestamp by published_on and add updated_on as timestamp
- [[26388]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26388) Renew all and Renew selected buttons should account for items that can't be renewed
- [[26041]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26041) Accessibility: The date picker calendar is not keyboard accessible
- [[26069]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26069) Twitter share button leaks information to Twitter
- [[26119]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26119) Patron attribute option to display in OPAC is not compatible with PatronSelfRegistrationVerifyByEmail
- [[26070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26070) Google Transliterate API has been deprecated
- [[25982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25982) OPAC shelves RSS link output is HTML not XML
- [[25984]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25984) Accessibility: Shelf browse lacks focus visibility when cover image is missing
- [[25244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25244) Accessibility: Checkboxes on the search results page do not contain specific aria labels
- [[25237]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25237) Accessibility: The 'Author details' in the full record display contains semantically incorrect headings
- [[25155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25155) Accessibility: The 'Login modal' contains semantically incorrect headings
- [[24473]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24473) Syndetics content should be $raw filtered on opac-detail.tt
- [[25869]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25869) Coce images not loading for lists (virtualshelves)

## Packaging

- [[25792]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25792) Rename 'ttf-dejavu' package to 'fonts-dejavu' for Debian 11
- [[25778]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25778) koha-plack puts duplicate entries into PERL5LIB when multiple instances named
- [[25920]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25920) Add liblocale-codes-perl package to fix ubuntu-stable (focal)

## Patrons

- [[25336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25336) Show checkouts/fines to guarantor is in the wrong section of the patron file

## Reports

- [[17801]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17801) 'Top Most-circulated items' gives wrong results when filtering by checkout date
- [[26090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26090) Catalog by itemtype report fails if SQL strict mode is on
- [[26165]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26165) Duplicating large saved report leads to error due to length of URI
- [[26111]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26111) Serials module does not appear in reports dictionary

## REST API

- [[26271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26271) Call to /api/v1/patrons/<patron_id>/account returns 500 error if manager_id is NULL
- [[26143]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26143) The API does not handle requesting all resources
- [[25944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25944) Bug in ill_requests patch schema

## Searching

- [[17661]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17661) Differences in field ending (whitespace, punctuation) cause duplicate facets

## Searching - Elasticsearch

- [[26313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26313) "Show analytics" and "Show volumes" links don't work with Elasticsearch and UseControlNumber
- [[25882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25882) Elasticsearch - Advanced search itemtype limits are being double quoted
- [[26009]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26009) Elasticsearch homebranch and holdingbranch facets are limited to 10
- [[25873]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25873) Elasticsearch - Records with malformed data are not indexed

## Searching - Zebra

- [[26369]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26369) Set use_zebra_facets to 0 in the templates
- [[23086]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23086) Search for collection is broken

## Self checkout

- [[23102]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23102) 404 errors on page causes SCI user to be logged out
- [[25791]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25791) SCO print dialog pops up twice

## SIP2

- [[25541]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25541) Add ability to prevent checkin via SIP of items with holds
- [[26370]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26370) Add ability to disable demagnetizing items via SIP2 for arbitrary patron categories
- [[25903]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25903) Sending a SIP patron information request with a summary field flag in indexes 6-9 will crash server

## Staff Client

- [[15326]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15326) Add CMS feature

## System Administration

- [[25005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25005) Admin Rights issue for Suggestion to Purchase
- [[25709]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25709) Rename systempreference from NotesBlacklist to NotesToHide

## Templates

- [[26324]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26324) Spelling error resizeable vs resizable
- [[26213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26213) Remove the use of jquery.checkboxes plugin when adding orders from MARC file
- [[26098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26098) JS error on the fund list view if no fund displayed
- [[25762]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25762) Typo in linkitem.tt
- [[25351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25351) Move cart-related strings out of opac-bottom.inc and into basket.js

## Test Suite

- [[26364]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26364) XISBN.t makes a bad assumption about return values
- [[24147]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24147) Objects.t is failing randomly
- [[25641]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25641) Koha/XSLT/Base.t is failing on U20
- [[26162]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26162) Prevent Selenium's StaleElementReferenceException
- [[26043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26043) Holds.t is failing randomly
- [[25729]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25729) Charges/Fees.t is failing on slow servers due to wrong date comparison
- [[26033]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26033) framapic is closing

## Tools

- [[26236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26236) log viewer does not translate the interface properly
- [[25893]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25893) Log viewer no longer searches using wildcards
- [[25862]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25862) TinyMCE editor mangles  local url links  (relative_urls is true) in tools/koha-new.pl

## Z39.50 / SRU / OpenSearch Servers

- [[23542]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23542) SRU import encoding issue


