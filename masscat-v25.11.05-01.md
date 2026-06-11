
# Release Notes for masscat-v25.11.05-01

## About

- [[42740]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42740) Suggestion status is not kept when editing a suggestion

## Accessibility

- [[42448]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42448) Staff Interface News (newsfooter) text does not have sufficient color contrast
- [[42236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42236) OPAC lists table header contains no text
- [[42165]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42165) OPAC main search should include role="search"
- [[42300]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42300) OPAC detail page: authority links have no text
- [[41934]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41934) Empty table header in course reserves table causes accessibility error
- [[41933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41933) Course reserves OPAC DataTables search field missing accessible label
- [[42142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42142) The gear icon to toggle panel for login settings needs accessibility updates
- [[42149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42149) The main navigation needs an aria-label
- [[42143]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42143) The breadcrumbs on Patron pages render an empty link

## Acquisitions

- [[42723]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42723) Purchase suggestion 500 page error when EmailPurchaseSuggestions is set to "email address of library"
- [[42757]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42757) Suggester is not passed by purchase-suggestions.pl
- [[41998]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41998) Some templates in suggestion.pl are computed even through a redirection
- [[42710]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42710) Purchase suggestion creation form (staff interface) no longer defaults to logged-in library
- [[42750]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42750) Purchase suggestions made from members/purchase-suggestions.pl no longer redirect back
- [[41997]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41997) Default suggester is not passed by the suggestion creation form
- [[42312]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42312) Must enter all four lines of physical address when editing a vendor
- [[41783]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41783) Query parameters for suggestions filtering is not encoded
- [[42010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42010) Include escaping when using PO numbers in EDI acquisitions

## Architecture, internals, and plumbing

- [[42163]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42163) wrapper-staff-tool-plugin.inc no longer loads the admin menu
- [[42317]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42317) [CVE-2014-1626] Require MARC::File::XML > 1.0.2
- [[42463]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42463) Deleting a SMS provider should use text() rather than html()
- [[42356]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42356) New yarn build warning: if() syntax is deprecated
- [[41440]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41440) Add caching to language_get_description and get_rfc4646_from_iso639
- [[41454]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41454) Remove unused dbh calls
- [[42175]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42175) Running under Mojo is broken in k.t.d
- [[41521]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41521) WebService::ILS::OverDrive not passing pl_valid
- [[41587]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41587) node audit identified several vulnerable node dependencies
- [[30261]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30261) opac/tracklinks.pl renders 404 incorrectly

## Authentication

- [[42222]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42222) Use of uninitialized string in string eq in Auth.pm

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Skip atomic-update check via CUSTOM_PACKAGE and run xt security tests
- NOT IN BUGZILLA - Skip failing cypress tests in GitHub Actions ( they pass locally )
- NOT IN BUGZILLA - DBRev 25.11.04.006
- NOT IN BUGZILLA - DBRev 25.11.04.002

## Cataloging

- [[42262]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42262) MARC 006 tag editor plugin drops blank value in position 17 when editing existing tag
- [[42176]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42176) Form to create an authorized value is submitted when cancelled
- [[42424]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42424) Javascript error prevents saving when an instance of an 'important' or 'required' subfield is deleted
- [[40633]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40633) Add keyboard shortcut to advanced cataloging editor for fixed length field plugins
- [[42221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42221) autoBarcode set to incremental EAN-13 barcodes do not increment
- [[42072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42072) Batch item deletion "Delete records" message is confusing
- [[33857]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33857) Reduce and resize local cover images
- [[31717]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31717) Value builder unimarc_field_010.pl should also use 214$c
- [[41367]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41367) Staff user interface - no sidebar menu when on record sources pages

## Circulation

- [[41940]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41940) Use of uninitialized value... warnings in circulation.pl
- [[41343]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41343) Overdue report is too intensive on systems with many overdues
- [[37966]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37966) When overriding a hold to renew a book the due date becomes "now" if not specified
- [[39748]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39748) Daylight savings breaks circulation (when DST change eliminates 00:00 to 00:59)
- [[41938]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41938) Argument "" isn't numeric in numeric gt (>) ... warnings in circulation.tt
- [[21941]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21941) Incorrect GROUP BY in circ/reserveratios.pl
- [[15792]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15792) Double-clicking the 'renew' button on circulation.pl will double-charge account management fee
- [[41788]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41788) Make running the holds queue on click optional
- [[41510]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41510) Fallback on bookable itemtype can break if item has no itemtype

## Command-line Utilities

- [[41353]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41353) koha-dump failing on mysqldump PROCESS privileges
- [[41062]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41062) Expand cronjob erm_run_harvester.pl with parameter for providers
- [[41851]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41851) Add logging to EDI cron job
- [[41967]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41967) cleanup_database.pl ignores integer values for --labels and --cards and defaults to 1 day
- [[40744]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40744) Don't give noisy warning when PatronSelfRegistration is turned off

## Database

- [[39107]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39107) kohastructure.sql doesn't load on new MySQL versions
- [[42273]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42273) 'idenfity' typo in `categories` table
- [[41460]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41460) On Mysql on upgrade from 25.05 to 25.11 I got the error TEXT column 'value' can't have a default value

## Fines and fees

- [[41386]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41386) Adding 0.00 as value for "Expired hold charge" in circulation rules can lead to exception Koha::Exceptions::Account::AmountNotPositive

## Hold requests

- [[42255]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42255) Grouped holds counted inconsistently for circ rules
- [[42343]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42343) JS error holdsQueueTable is undefined when no holds exist
- [[41267]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41267) It should be possible to prevent some itemtypes from filling other biblio level holds
- [[42147]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42147) Action logs for hold creation contain less data
- [[41801]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41801) FixPriority recursive calls for lowestPriority holds can be removed
- [[41335]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41335) Toggling the hold options does not always work in opac-reserve

## I18N/L10N

- [[41769]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41769) ", by" in suggestions table in the staff interface is not translated
- [[42341]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42341) "Print label" on staff detail page is not translatable
- [[42302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42302) xgettext.pl does not output to STDOUT correctly

## ILL

- [[42244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42244) Fix JS TypeError on patrons ILL table
- [[41247]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41247) ILL batches modal does not reset correctly
- [[41861]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41861) ILL request cost and price paid don't show if 0
- [[41944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41944) Error 500 on non-existent ILL request (op=illview)

## Installation and upgrade (command-line installer)

- [[42412]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42412) Upgrade to 25.11.02.004 using MySQL fails with Exception: Incorrect DATE value:  value: '0000-00-00'
- [[42374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42374) DB Upgrade from the UI is broken
- [[42301]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42301) updatedatabase fails on mysql when adding a unique key to a text column (introduced by 35380)
- [[42318]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42318) Table record_sources is not populated with data on install

## Lists

- [[42267]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42267) Update lists pages to use grid layout for forms

## Mana-kb

- [[41373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41373) Report share with mana not working when language_loop is not true

## MARC Authority data support

- [[41962]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41962) Add comment to SearchAuthorities about unused params, update POD accordingly
- [[21453]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21453) blinddetail-biblio-search.pl/.tt use hardcoded subfield values for MARC21
- [[41843]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41843) Koha::Authorities->move_to_deleted can die on encoding errors
- [[41859]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41859) Authority search autocomplete results not consistent with search results

## MARC Bibliographic data support

- [[41759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41759) The display of MARC 21 field 026 data (Fingerprint Identifier) is missing (both in intranet and OPAC)

## OPAC

- [[42545]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42545) Koha::Calendar::days_between skips holiday subtraction for end date if time is early
- [[42570]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42570) OPAC patron summary shows literal holds count instead of group-aware count
- [[41690]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41690) Add MARC21 245$b (subtitle) to Cite option
- [[41942]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41942) Hiding primary contact method hides lang with PatronSelfModificationBorrowerUnwantedField
- [[34025]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34025) Uniform titles (130 / 240 /730) in bibliographic record to link to authority file
- [[39027]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39027) News are ordered with oldest on top
- [[41870]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41870) Warning "Use of uninitialized value $borrowernumber" in opac-detail.pl
- [[42017]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42017) Fix content type of OPAC news RSS
- [[41866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41866) "Use of uninitialized value..." warning in opac-search.pl
- [[41665]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41665) Only include Greybox in OPAC if IdRef is enabled
- [[40481]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40481) The items table on koha/opac-MARCdetail.pl does not honor OPACHiddenItems

## Patrons

- [[41073]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41073) Import users expiry date default does not apply
- [[42169]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42169) Unify patron category change popups
- [[42474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42474) Patron categories form label: "Upperage limit" should be "Upper age limit"
- [[37143]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37143) Patron registration allows for saving required fields with a single space instead of information
- [[41045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41045) Suggestions manage permissions added to patrons who previously had no permissions in that category

## Plugin architecture

- [[40972]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40972) New hook: extend MARC filter

## Point of Sale

- [[41751]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41751) Cash register transaction history returns 403 for users with only anonymous_refund permission
- [[37671]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37671) Can't print receipt for refund from cash register transaction history
- [[41585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41585) Refunds don't always appear on the register page

## Reports

- [[41918]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41918) Prevent users from running the same report multiple times concurrently
- [[42361]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42361) SQL Injection in reports/catalogue_out.pl via Filter parameter (error-based, triggered when Criteria matches /branchcode/)
- [[38414]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38414) Reports permissions not properly enforced
- [[39164]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39164) Add max_statement_time to SQL report queries
- [[41699]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41699) onsite_checkout not available in Statistics wizards

## REST API

- [[42206]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42206) Add REST endpoint GET /libraries/{library_id}/closed_dates
- [[41901]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41901) Allow duplicate check when adding authority via API
- [[41733]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41733) Honor EmailPatronRegistrations preference in the API
- [[35380]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35380) PUT /biblios/:biblio_id doesn't apply record overlay rules
- [[41614]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41614) additional_contents REST endpoint broke the display location filter

## Searching - Elasticsearch

- [[40658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40658) When sorting by local-number we should use the sort field
- [[40577]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40577) Bulk update Elasticsearch index for bibliographic records after authority change
- [[42016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42016) Add identifier-other search field for authorities (MARC 21)
- [[36550]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36550) koha-elasticsearch commit default should be configurable
- [[42107]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42107) Add score to staff search results
- [[41863]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41863) Facets generated from Authorized values sometimes show empty labels
- [[41758]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41758) Add Fingerprint Identifier data to Elasticsearch index mappings
- [[28884]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28884) ElasticSearch: Question mark in title search returns no results

## Searching - Zebra

- [[41795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41795) UNIMARC: a Zebra search for Corporate Body Name authorities will also return Collective Titles

## Self checkout

- [[27826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27826) Self checkout dies on '?' as a barcode

## Serials

- [[38009]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38009) Add a generate next button in serials receive page
- [[41846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41846) Notes field of routing list displays HTML characters
- [[42277]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42277) JS error when viewing a subscription
- [[42076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42076) Add vendor ID column to serial vendor search results

## SIP2

- [[42447]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42447) SIP template fields in the database are too small
- [[41383]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41383) SIP2 server does not search patrons by unique patron attributes (alternate IDs unusable in SIP2)
- [[41985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41985) Fix wording on SIP2 account form - 'Syspref' to 'System preference'

## Staff interface

- [[42521]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42521) Cannot login from suggestion.pl
- [[42398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42398) Form validation does not work on additional content news
- [[41516]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41516) Terminology: Change cardnumber to card number for system preference descriptions
- [[42309]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42309) JS error when there are no cash registers
- [[41476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41476) Plugins table explode if one of the plugin is in error
- [[42182]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42182) StaffReportsHome HTML customization does not work when library limited

## System Administration

- [[42638]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42638) Cannot delete an identity provider domain
- [[28297]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28297) Can't save system preference and field not marked as modified when changing value
- [[41980]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41980) SIP codes in the new SIP Config UI could have better descriptions

## Templates

- [[32453]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32453) Object methods _result and _resultset methods not available in templates
- [[42467]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42467) Remove event attributes from MARC modification templates template
- [[42445]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42445) Remove event attributes from list creation template
- [[42442]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42442) Remove event attributes from bibliographic record merge template
- [[42439]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42439) Remove event attributes from label-edit-batch.tt
- [[42438]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42438) Remove event attributes from icon selection include file
- [[42103]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42103) Spelling: marc record
- [[42104]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42104) Spelling: capitalize id (instead of id and Id)
- [[42140]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42140) Patron information - no space between guarantor name and relationship on patron details page
- [[42131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42131) Terminology: Return in action logs should be Check-in
- [[41827]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41827) Update authority types pages to use grid layout for forms
- [[41823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41823) Update acquisitions admin pages to use grid layout for forms
- [[40113]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40113) Update accounting admin pages to use grid layout for forms
- [[39780]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39780) Update library groups form to use grid layout
- [[42106]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42106) Spelling: Failed to load plugin url: {0}
- [[40727]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40727) Minor styling bug in print/email receipt pop-up menu
- [[41835]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41835) Add item forms Tag editor buttons on serial edition page are misaligned
- [[41760]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41760) Fix <tbody> and <tfoot> in several templates
- [[42134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42134) String displays incorrectly: words “notices” and “for” appear concatenated
- [[23269]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23269) Long hold queues are slowing the service
- [[41778]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41778) Broken display of not for loan status on item detail page
- [[42012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42012) e.preventDefault not called in clubs.tt club_hold_search handler
- [[35237]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35237) Duplicate ids in markup of patron card layout edit form

## Test Suite

- [[42581]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42581) xt/api.t shouldn't test routes injected by plugins
- [[42578]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42578) Koha/Hold.t failing on date comparison
- [[42359]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42359) t/db_dependent/Reports/Guided.t fails when ReportsLog is enabled
- [[41216]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41216) Resurrect tt_valid.t
- [[42126]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42126) t/db_dependent/00-strict.t not testing all perl files
- [[40962]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40962) t/db_dependent/OAI/Server.t is failing

## Tools

- [[42156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42156) Staging and matching authorities with bad characters can fail
- [[8088]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8088) Png-images of covers lost transparency
- [[41884]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41884) Job report for batch item modifications that fail due to PreventWithdrawingItemsStatus has no details on failed items

## Transaction logs

- [[42030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42030) Add diff support to SUGGESTION action logs

## Web services

- [[37713]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37713) OAI-PMH - Honour OpacSuppression syspref


