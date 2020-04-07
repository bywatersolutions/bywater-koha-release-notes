
# Release Notes for bluehill-v19.05.09-01

## Acquisitions

- [[24389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24389) Claiming an order can display an invalid successful message

## Architecture, internals, and plumbing

- [[24051]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24051) batchMod.pl: DBIx::Class::ResultSet::search_rs(): search( %condition ) is deprecated
- [[24388]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24388) Useless test in acqui/lateorders.tt
- [[20882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20882) URI column in the items table is limited to 255 characters
- [[24643]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24643) Koha::DateUtils::dt_from_string rfc3339 cannot handle high precision seconds

## Authentication

- [[24673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24673) CSRF vulnerability in opac-messaging.pl
- [[24878]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24878) Authentication check missing on calendar tools
- [[16719]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16719) LDAP: Using empty strings as 'failsafe' attribute mapping defeats database constraints

## Bywater Only

- NOT IN BUGZILLA - Fix failing unit test in t/db_dependent/Circulation.t
- NOT IN BUGZILLA - GitHub Actions - Add Arlington
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[18499]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18499) 'Call Number Browser' on edit items screen uses the default classification source rather than the item specific source
- [[13574]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13574) Repeatable item subfields don't show correctly in MARC view (OPAC and staff)
- [[13420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13420) Holdings table sorting on volume information incorrect

## Circulation

- [[24846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24846) Add a tool to bulk edit due dates
- [[24514]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24514) Holds Awaiting Pickup sorting by title before surname

## Database

- [[24640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24640) quotes.timestamp should default to NULL

## Documentation

- [[21633]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21633) Did finesMode = test ever send email?

## I18N/L10N

- [[24664]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24664) Add missing *-messages-js.po

## MARC Authority data support

- [[24094]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24094) Authority punctuation mismatch prevents linking to correct records

## OPAC

- [[24676]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24676) opac-auth.tt contains trivial HTML error
- [[17221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17221) Orphan comma in shelf browser
- [[18933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18933) Unable to set SMS number in OPAC messaging preferences to empty
- [[23527]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23527) BakerTaylorBookstoreURL is converted to escaped characters by template, rendering it invalid
- [[24654]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24654) Trailing double-quote in RDA 264 subfield b on OPAC XSLT

## Patrons

- [[19791]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19791) Patron Modification log redirects to circulation page

## REST API

- [[24260]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24260) REST Self Registration

## Searching - Elasticsearch

- [[24506]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24506) Multibranch limit does not work with ElasticSearch

## SIP2

- [[23640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23640) L1 cache too long in SIP Server
- [[24449]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24449) SIP2 - too_many_overdue flag is not implemented

## Staff Client

- [[24649]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24649) Cloning item subfields misses a <li> tag
- [[24516]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24516) Column Configuration does not hide Return Date
- [[13305]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13305) Fix tab order in cataloguing/item editor

## Templates

- [[21663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21663) Incorrect filter prevents predefined notes from being added to patron acccounts
- [[24110]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24110) Template vars are incorrectly html filtered when dumped
- [[24621]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24621) Phase out jquery.cookie.js: Basic MARC editor
- [[24619]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24619) Phase out jquery.cookie.js: MARC Frameworks
- [[11281]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11281) Add column configuration to 'Holds awaiting pickup' tables allowing to print both tables separately

## Test Suite

- [[24494]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24494) 00-valid-xml.t shouldn't check node_modules
- [[24881]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24881) Circulation.t still fails if tests are ran slowly
- [[22860]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22860) Selenium tests authentication.t does not remove all data it created
- [[24590]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24590) Koha/Object.t is failing on MySQL 8

## Tools

- [[22245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22245) MARC modification templates does not allow move or copy control fields



# Release Notes for bluehill-v19.05.08-10

## Tools

- [[25020]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25020) Extending due dates to a specified date should preserve time portion of original due date



# Release Notes for bluehill-v19.05.08-09

## OPAC

- [[25024]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25024) OPAC incorrectly marks branch as invalid pickup location when similarly named branch is blocked



# Release Notes for bluehill-v19.05.08-08

## Architecture, internals, and plumbing

- [[24754]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24754) UserEnv not set for ISLDI requests

## Circulation

- [[24759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24759) OpacRenewalBranch code should be a Koha::Item method
- [[24846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24846) Add a tool to bulk edit due dates

## Patrons

- [[24988]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24988) autorenew_checkouts should default to yes
- [[24476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24476) Allow patrons to opt-out of auto-renewal

## Searching - Elasticsearch

- [[24269]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24269) Authority matching in Elasticsearch is broken when authority has subdivisions
- [[23137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23137) Elasticsearch - should have command line tool to reset mappings

## Self checkout

- [[23165]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23165) Renewals for Self Checkout (SCO) module do not record branchcode in statistics

## SIP2

- [[24993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24993) koha-sip --restart is too fast, doesn't always start sip



# Release Notes for bluehill-v19.05.08-04

## SIP2

- [[24966]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24966) Fix calls to maybe_add where method call does not return a value
- [[21979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21979) Add option to SIP2 config to send arbitrary item field in CR instead of collection code



# Release Notes for bluehill-v19.05.08-02

## Circulation

- [[24802]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24802) Updating holds can cause suspensions to apply to wrong hold



# Release Notes for bluehill-v19.05.08-01

## Acquisitions

- [[9993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=9993) On editing basket group delivery place resets to logged in library
- [[22868]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22868) Circulation staff with suggestions_manage can have access to acquisition data
- [[17667]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17667) Standing orders - cancelling a receipt increase the original quantity
- [[24404]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24404) Add missing space on invoices page
- [[24277]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24277) Date Received in acquisitions cannot be changed

## Architecture, internals, and plumbing

- [[23290]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23290) XSLT system preferences allow administrators to exploit XML and XSLT vulnerabilities
- [[24213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24213) Koha::Object->get_from_storage should return undef if the object has been deleted
- [[23896]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23896) logaction should pass the correct interface to Koha::Logger
- [[23407]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23407) XSLT Details pages don't use items, we shouldn't pass them
- [[22220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22220) Error in ReWriteRule for 'bib' in apache-shared-intranet.conf
- [[24313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24313) XSLT errors should show in the logs
- [[24016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24016) manager_id in Koha::Patron::Message->store should not depend on userenv alone

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Prune Docker images
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Bug 24333: Add password class to AutoSelfCheck syspref

## Cataloging

- [[16683]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16683) Help links to fields 59X in cataloguing form are broken
- [[24452]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24452) Advanced editor - show multiple spaces visually
- [[24236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24236) Using quotes in a cataloging search, resulting in multiple pages, will not allow you to advance page
- [[24423]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24423) Broken link to return to record after batch item modification or deletion
- [[24323]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24323) Advanced editor - Invalid 008 with helper silently fails to save

## Circulation

- [[24214]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24214) Due date displayed in ISO format (when sticky)
- [[23233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23233) AllowItemsOnHoldCheckout is misnamed and should only work for for SIP-based checkouts

## Command-line Utilities

- [[24511]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24511) Patron emailer report not using specified email column
- [[24105]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24105) Longoverdue gives error message when --itemtypes are specified

## Database

- [[24289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24289) Deleting branch will not delete entry in special or repeatable holidays
- [[24377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24377) Record branch in statistics for auto-renewal

## Fines and fees

- [[24637]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24637) Pay selected & Pay amount does not log branchcode in 19.05
- [[23443]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23443) Paying off a lost fee will return the item, even if it is checked out to a different patron

## Hold requests

- [[21296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21296) Suspend hold ignores system preference on intranet
- [[20567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20567) "Holds per record (count)" limit is not enforced after item is captured for hold

## I18N/L10N

- [[23790]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23790) fr-CA translation of ACCOUNT_DEBIT and ACCOUNT_CREDIT notices

## MARC Authority data support

- [[24421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24421) Generated authorities are missing subfields

## MARC Bibliographic record staging/import

- [[24348]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24348) Record matching rules: required match checks does not work

## OPAC

- [[22302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22302) ITEMTYPECAT description doesn't fall back to description if OPAC description is empty
- [[24523]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24523) Fix opac-password-recovery markup mistake
- [[17697]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17697) Improve NotesBlacklist system preference description to make clear where it will apply
- [[24486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24486) Account Wording Information is duplicated in Patron's Fines Tab on OPAC
- [[24061]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24061) Print List (opac-shelves.pl) broken in Chrome
- [[24206]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24206) Change URLs for default options in OPACSearchForTitleIn
- [[23528]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23528) Show 'log in to add tags' link on all search result entries
- [[24371]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24371) OPAC 'Showing only available items/Show all items' is double encoded

## Patrons

- [[14759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14759) Replacement for Text::Unaccent

## Plugin architecture

- [[22835]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22835) Serve static files from plugins through the API
- [[22834]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22834) Add a method for plugins to return the absolute path for bundled files

## Searching

- [[10879]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10879) OverDrive should check for OverDriveLibraryID before performing search
- [[24443]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24443) Consider NULL as 0 for issues in items search
- [[15142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15142) Titles facet does not work in UNIMARC

## Searching - Elasticsearch

- [[23676]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23676) Elasticsearch - 0 is not a valid boolean for suppress
- [[22426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22426) Elasticsearch - Index location is missing in advanced search
- [[17885]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17885) Koha::SearchEngine::Elasticsearch->reset_elasticsearch_mappings throws DBD::mysql Duplicate entry exceptions
- [[24123]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24123) bulkmarcimport.pl doesn't support UTF-8 encoded MARCXML records

## Serials

- [[23064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23064) Cannot edit subscription with strict SQL modes turned on

## SIP2

- [[20292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20292) Filter/censor info sent via SIP

## Staff Client

- [[24515]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24515) Column Configuration for pay-fines-table does not hide Account Type properly

## System Administration

- [[24025]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24025) Make CodeMirror content searchable
- [[24329]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24329) Patron cardnumber change times are lost during upgrade for bug 3820

## Templates

- [[24054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24054) Typo in ClaimReturnedWarningThreshold system preference
- [[23947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23947) Phase out jquery.cookie.js: Authority merge
- [[23944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23944) Phase out use of jquery.cookie.js in favor of js.cookie.js
- [[23113]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23113) members/pay.tt account_grp is not longer used
- [[24391]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24391) Remove event attributes from patron clubs edit template

## Test Suite

- [[24543]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24543) Wrong test in api/v1/checkouts.t
- [[23274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23274) t/db_dependent/XISBN.t fails with Elasticsearch

## Tools

- [[24497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24497) CodeMirror indentation problems
- [[24275]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24275) Inventory table should be sortable by title without leading articles (allow for title sort with anti-the)
- [[24484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24484) Add explanatory text to batch patron deletion
- [[23377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23377) bulkmarcimport.pl disables syspref caching
- [[10352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10352) Cataloguing log search mixing itemnumber/bibnumber



# Release Notes for bluehill-v19.05.07-04

## Searching - Elasticsearch

- [[23719]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23719) Record matching for authorities using defined fields is broken under ES



# Release Notes for bluehill-v19.05.07-03

## SIP2

- [[24705]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24705) Holds placed via SIP will be given first priority



# Release Notes for bluehill-v19.05.07-02

## SIP2

- [[24566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24566) UpdateItemLocationOnCheckin triggers SIP2 alert flag, even with checked_in_ok enabled



# Release Notes for bluehill-v19.05.07-01

## Acquisitions

- [[24244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24244) Cannot create suggestion with branch set to 'Any'
- [[24242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24242) Funds with no library assigned do not appear on edit suggestions page
- [[5365]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=5365) It should be more clear how to reopen a basket in a basket group

## Architecture, internals, and plumbing

- [[23997]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23997) sample_z3950_servers.sql is failing on MySQL 8

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[24173]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24173) Advanced Editor: Show subtitle & published date on the search page
- [[24232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24232) Fix permissions for deleting a bib record after attaching the last item to another bib
- [[11500]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11500) Use dateformat syspref and datepicker on additems.pl (and other item cataloguing pages)
- [[24090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24090) Subfield text in red when mandatory in record edition

## Circulation

- [[23382]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23382) Issuing rules failing after bug 20912
- [[24166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24166) Barcode removal breaks circulation.pl/moremember.pl
- [[24337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24337) Checkout note cannot be marked seen if more than 20 exist
- [[24335]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24335) Cannot mark checkout notes seen/not seen in bulk
- [[24308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24308) Suggestions table on suggestions.pl should have separate columns for dates
- [[24259]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24259) Circulation fails if no circ rule defined but checkout override confirmed

## Command-line Utilities

- [[19465]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19465) Allow choosing Elasticsearch server on instance creation

## Course reserves

- [[24283]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24283) Missing close parens and closing strong tag in course reserves

## Database

- [[23995]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23995) Check constraints are supported differently by MySQL and MariaDB so we should remove them for now.

## Hold requests

- [[24485]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24485) AllowHoldPolicyOverride should allow Staff to override the Holds Per Record Rule
- [[20948]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20948) Item-level hold info displayed regardless its priority (detail.pl)

## I18N/L10N

- [[24063]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24063) Add Sami language characters to Zebra
- [[24358]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24358) "Bibliographic record does not exist!" is not translatable
- [[18688]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18688) Warnings about UTF-8 charset when creating a new language
- [[24046]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24046) 'Activate filters' untranslatable

## ILL

- [[21270]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21270) "Not finding what you're looking" display needs to be fixed

## Installation and upgrade (command-line installer)

- [[24328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24328) Bibliographic frameworks fail to install

## Installation and upgrade (web-based installer)

- [[24314]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24314) Update de-DE MARC21 frameworks for updates 28+29 (May and November 2019)
- [[24137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24137) Marc21 bibliographic fails to install for ru-Ru and uk-UA

## MARC Authority data support

- [[24267]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24267) C4::Breeding::ImportBreedingAuth is ineffective

## MARC Bibliographic data support

- [[24312]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24312) Update MARC21 frameworks to Updates 28+29 (May and November 2019)
- [[24274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24274) New installations should not contain field 01e Coded field error (RLIN)
- [[24281]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24281) Fix the list of types of visual materials
- [[23731]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23731) Display LC call number in OPAC and staff detail pages

## Notices

- [[24235]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24235) /misc/cronjobs/advance_notices.pl DUEDGST does NOT send sms, just e-mail

## OPAC

- [[24212]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24212) OPAC send list dialog opens too small in IE
- [[24245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24245) opac-registration-confirmation.tt has incorrect HTML body id
- [[24240]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24240) List on opac missing close form tag under some conditions

## Reports

- [[13806]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13806) No input sanitization where creating Reports subgroup

## REST API

- [[24191]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24191) Sorting doesn't use to_model

## Searching

- [[24121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24121) Item types icons in intra search results are requesting icons from opac images path
- [[14419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14419) Expanding facets (Show more) performs a new search

## Searching - Elasticsearch

- [[24264]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24264) Elasticsearch - Cannot search for genre/form authorities

## Serials

- [[21232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21232) Problems when linking a subscription to a non-existing biblionumber

## Staff Client

- [[22381]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22381) Wording on Calendar-related system preferences not standardized

## System Administration

- [[24184]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24184) Reword FallbackToSMSIfNoEmail syspref text

## Templates

- [[24054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24054) Typo in ClaimReturnedWarningThreshold system preference
- [[24104]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24104) Item search - dropdown buttons overflow
- [[10469]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10469) Display more when editing subfields in frameworks
- [[23956]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23956) Replace famfamfam calendar icon in staff client with CSS data-url
- [[23889]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23889) Improve style of menu header in advanced cataloging editor
- [[24282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24282) SCSS conversion broke style in search results item status
- [[24230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24230) intranet_js plugin hook is after body end tag



# Release Notes for bluehill-v19.05.06-05

## Database

- [[24377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24377) Record branch in statistics for auto-renewal



# Release Notes for bluehill-v19.05.06-04

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Add Auto-rebasing of XSLT branches, leave disabled

## Circulation

- [[24547]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24547) Add more action logs for holds



# Release Notes for bluehill-v19.05.06-03



# Release Notes for bluehill-v19.05.06-02

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Prevent workflow from running on tags, associate release with correct branch

## Custom For Instance

- NOT IN BUGZILLA - Fix template param filters so unit tests pass


