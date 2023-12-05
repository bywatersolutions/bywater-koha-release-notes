
# Release Notes for bywater-v23.05.06-01

## Acquisitions

- [[35273]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35273) When editing items on receive, aqorders_items is not updated correctly
- [[35254]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35254) Adding files to basket from a staged file uses wrong inputs for order information when not all records are selected
- [[35004]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35004) Cannot receive order lines with items created in cataloguing
- [[34880]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34880) Receive impossible if items created 'in cataloguing'
- [[34736]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34736) Item checkboxes move to wrong order line in multi-receive, breaking partial receive
- [[34036]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34036) Single receive doesn't reload data and order lines don't appear in received section
- [[34109]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34109) When adding items on receive, mandatory fields are not checked
- [[34108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34108) When items are added on order, item selection gets lost on editing items
- [[34169]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34169) Add validation for monetary input fields in acquisition module
- [[33863]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33863) On receive "change currency" is always checked
- [[33798]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33798) Vendor details - improve consistency of edit forms and display
- [[34022]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34022) Adding items on receive is broken
- [[33885]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33885) Get HTTP 500 when retrieving orders created by a non-existent (deleted) user
- [[33864]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33864) Problems in order receive modal
- [[33783]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33783) Populate actual cost with estimated cost if actual cost not set when receiving (bug 8179 follow-up)
- [[33784]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33784) Save clicks on single order receive
- [[33785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33785) A couple more UI changes related to Bug 8179
- [[8179]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8179) Receiving multiple order lines at once
- [[33771]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33771) Markup errors on orderreceive.tt after 8179
- [[11844]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11844) Additional fields for order lines
- [[33541]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33541) Show 'Document type' in list of suggestions when creating an order from a suggestion
- [[33098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33098) Revert suggestion status to 'Accepted' when orders made from a suggestion are cancelled
- [[33104]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33104) Add vendor interfaces
- [[33262]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33262) When an ordered record is deleted, we lose all information on what was ordered
- [[33103]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33103) Add vendor aliases
- [[29935]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29935) Add option to search in archived suggestions to all search tabs
- [[32705]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32705) Display actual cost in foreign currency and currency from the invoice
- [[25655]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25655) Additionally store actual cost in foreign currency and currency from the invoice
- [[33003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33003) Show the vendor type description on vendor detail page when AV is used
- [[32452]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32452) Link basket group name from basket summary page
- [[32417]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32417) Cannot insert order: Mandatory parameter biblionumber is missing

## Architecture, internals, and plumbing

- [[33030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33030) Add standardized subroutine for processing Template Toolkit syntax outside of notices
- [[35190]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35190) Additional_fields table should allow null values for authorised_value_category
- [[35043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35043) Handling of \t in PO files is confusing
- [[35024]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35024) Do not wrap PO files
- [[34959]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34959) Translator tool generates too many changes
- [[21828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21828) Improve efficiency of C4::Biblio::LinkBibHeadingsToAuthorities
- [[34720]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34720) UpdateNotForLoanStatusOnCheckin should be named UpdateNotForLoanStatusOnCheckout
- [[34844]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34844) manage_item_editor_templates is missing from userpermissions.sql
- [[34364]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34364) Background job - Fix visual progress of progress bar
- [[33964]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33964) Use Email::Sender::Transport::SMTP::Persistent for sending email
- [[33778]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33778) Move t/Auth_with_shibboleth.t to db_dependent
- [[26700]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26700) Remove unused C4/SIP/t directory
- [[33967]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33967) REMOTE_ADDR incorrect in plack.log when run behind a proxy
- [[33493]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33493) Add a filter relationship for branchtransfers
- [[32478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32478) Remove Koha::Config::SysPref->find since bypasses cache
- [[33236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33236) Move C4::Suggestions::NewSuggestion to Koha namespace
- [[33625]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33625) Enforce formatting on vue .js and .ts files
- [[33739]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33739) ModItemTransfer triggers indexing twice
- [[30649]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30649) Vendor EDI account passwords should be encrypted in the database
- [[33488]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33488) Library transfer limits should have an index on fromBranch
- [[33489]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33489) The borrowers table should have indexes on default patron search fields
- [[31735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31735) Avoid re-fetching objects from database by passing them down instead of object ids
- [[33567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33567) Remove fallback for Reference_NFL_statuses in C4/XSLT module
- [[33053]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33053) Tables item_groups and recalls have a biblio_id column with a default of 0
- [[33447]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33447) Add caching to Biblio->pickup_locations
- [[32013]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32013) Autorenewals is effectively a bulk action and should be treated as such
- [[30943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30943) Make background job classes use helpers
- [[32422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32422) Hardcoded paths in _common.scss prevent using external node_modules
- [[32330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32330) Table background_jobs is missing indexes

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Update versions from 22.11 to 23.05
- NOT IN BUGZILLA - Remove failing cypress test t/cypress/integration/ERM/Dialog_spec.ts
- NOT IN BUGZILLA - remove unreliable test t/db_dependent/selenium/system_preferences_search.t
- NOT IN BUGZILLA - GitHub Actions Add .github to make file
- NOT IN BUGZILLA - Translation fixes for Koha 23.05.05
- NOT IN BUGZILLA - Translation fixes for Koha 23.05.04
- NOT IN BUGZILLA - Translation fixes for Koha 23.05.03
- NOT IN BUGZILLA - Translation fixes for Koha 23.05.02
- NOT IN BUGZILLA - Amend release team
- NOT IN BUGZILLA - Koha 23.05.00 is here!
- NOT IN BUGZILLA - 23.05.00: Fix db_revs
- NOT IN BUGZILLA - 23.05.00: Update kohastructure.sql
- NOT IN BUGZILLA - Update debian/control file: 22.12.00-3 on deb9 (1b6e9c7b)
- NOT IN BUGZILLA - Update debian/changelog file: 22.12.00-3
- NOT IN BUGZILLA - Koha 22.12 - start of a new dev cycle

## Cataloging

- [[35181]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35181) Can no longer edit sample records with advanced cataloguing editor
- [[34014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34014) There is no way to fix records with broken MARCXML
- [[34029]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34029) Import breaks when data exceeds size of mapped database columns
- [[29732]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29732) Check alert in cataloguing authorities should be a static message
- [[31185]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31185) Link authorities automatically doesn't detect duplicate authorities
- [[30358]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30358) Strip leading/trailing whitespace characters from input fields when cataloguing
- [[33365]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33365) Add item type column to call number browser's results table
- [[32680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32680) Add hooks to allow cover images to be provided by plugins
- [[31212]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31212) Datelastseen should be a datetime
- [[28328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28328) Editing a record can cause an ISE if data too long for column
- [[31123]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31123) Add a simple way to add 'Harmful content warnings' to catalogue records
- [[30930]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30930) Ability to change authority type while editing record
- [[23656]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23656) Add search box at the top of the cataloging editor page
- [[20256]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20256) Add ability to limit editing of items to home library or library group

## Circulation

- [[33945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33945) Add ability to delay the loading of the current checkouts table on the checkouts page
- [[27992]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27992) When recording local use with statistical patron items are not checked in
- [[29007]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29007) Prompt for reason when cancelling waiting hold via popup
- [[34938]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34938) Add collection column to holds ratio report (circ/reserveratios.pl)
- [[35253]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35253) Make materials specified note easier to customize
- [[34457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34457) Add card number to hold details page
- [[34601]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34601) Cannot manage suggestions without CSRF error
- [[33961]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33961) In-built Offline circulation tool no longer working and should be removed
- [[33725]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33725) Add item's collection code to search results location column in staff interface
- [[33246]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33246) itemBarcodeFallbackSearch search results should show whether or not items are available
- [[31557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31557) Add ability for holds queue builder to prioritize either matching a patron's home library to the item's home or holding library
- [[25503]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25503) Add option to export items bundle contents in checkouts table
- [[33574]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33574) Restriction type is not stored, all restrictions fall back to MANUAL
- [[30403]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30403) Update notforloan status also on check out
- [[31615]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31615) Allow checkin of items bundles without verifying their contents
- [[18398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18398) CHECKIN/CHECKOUT/RENEWAL don't use AutoEmailPrimaryAddress but first valid e-mail
- [[32373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32373) Show date of restriction on patron screen
- [[33021]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33021) Show an alert when adding an item on hold to an item bundle
- [[25856]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25856) Suspended holds should be styled differently on request.pl
- [[30963]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30963) Automatically refresh the curbside pickups list

## Command-line Utilities

- [[33050]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33050) Allow to specify quote char in runreport.pl
- [[35171]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35171) runreport.pl cronjob should optionally send an email when the report has no results
- [[28995]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28995) Add --added_after to writeoff_debts.pl
- [[23924]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23924) Add a parameter to the script add_date_fields_to_marc_records.pl to specify a date field
- [[33360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33360) SendQueuedMessages: Improve limit behavior and add domain limits
- [[32686]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32686) Specify action of action_logs entries to purge
- [[32518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32518) Add reason option to cancel_unfilled_holds
- [[30069]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30069) Add edifact_messages to cleanup_database.pl

## Database

- [[34328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34328) Add Scottish Gaelic to the advanced search options
- [[32357]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32357) Set borrower_message_preferences.days_in_advance default to NULL
- [[32334]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32334) Sync comments in database with schema

## ERM

- [[34789]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34789) Fix typo in erm_eholdings_titles
- [[33491]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33491) EBSCO Packages - Add new agreement UI has some issues

## Fines and fees

- [[32271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32271) Overdue fines cap (amount) set to 0.00 when editing rule
- [[33028]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33028) Wrongly formatted monetary amounts in circulation rules break scripts and calculations
- [[33789]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33789) Checkout information is missing when adding a credit
- [[32450]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32450) Make it possible to exclude debit types from charges counted for circulation restriction (noissuecharge)
- [[31448]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31448) Add option to re-send email receipt when UseEmailReceipts is enabled
- [[32977]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32977) Add call number column to list of charges on transactions tab in patron account

## Hold requests

- [[33074]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33074) ReservesControlBranch not taken into account in opac-reserve.pl
- [[34178]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34178) Add caching of ItemsAnyAvailableAndNotRestricted to IsAvailableForItemLevelRequest
- [[30860]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30860) Performance: Add option for CanBookBeReserved to return all item values
- [[33791]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33791) $hold->fill does not set itemnumber when checking out without confirming hold

## I18N/L10N

- [[35081]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35081) "Your concern was sucessfully submitted." untranslatable
- [[34801]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34801) Fix incorrect use of __() in .tt and .inc files (bug 34038 follow-up)

## ILL

- [[21983]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21983) Better handling of deleted biblios on ILL requests
- [[32548]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32548) Make illrequestattributes easily available to ILL notices
- [[22440]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22440) Improve ILL page performance by moving to server side filtering
- [[21548]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21548) Make ILL patron category in koha-conf.xml match with ILL patron category in sample data

## Installation and upgrade (web-based installer)

- [[34520]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34520) Database update 22.06.00.078 breaks update process

## Lists

- [[32402]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32402) "Modification date" missing from OPAC lists table
- [[30418]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30418) Add permission and setting for public lists to allow staff with permission to edit contents
- [[32434]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32434) Records in lists not showing what other lists they belong to

## Mana-kb

- [[33356]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33356) Add link to mana-kb settings from 'Useful resources' in reports

## MARC Authority data support

- [[33557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33557) Add a system preference to disable/enable thesaurus checking during authority linking

## MARC Bibliographic data support

- [[29185]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29185) Show MARC21 tag 765 - Original Language Entry
- [[31432]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31432) MARC21: Make 245 n and p subfields visible in frameworks by default
- [[32689]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32689) Host item entry (773) missing a space between label and content when $i is used

## Notices

- [[8838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8838) Digest option for HOLD notice
- [[33759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33759) Typo: Thankyou
- [[33203]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33203) Overdue notice/status triggers letter selection is ambiguous
- [[23773]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23773) Send MEMBERSHIP_EXPIRY notice by SMS
- [[33314]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33314) Link to bibliographic record incomplete in default TICKET_NOTIFY notice
- [[33313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33313) TICKET_NOTIFY looking for IntranetBaseURL rather than staffClientBaseURL in default notice
- [[33223]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33223) Koha::Patron->notice_email_address isn't consistently used
- [[33658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33658) Capitalization: **To Reproduce**
- [[3150]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=3150) Move emails for sending cart and list contents into notices tool
- [[30555]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30555) Add more sample notice for SMS messages
- [[31858]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31858) TT syntax for ACQORDER notices

## OPAC

- [[35266]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35266) opac-MARCdetail: Can't call method "metadata" on an undefined value
- [[34518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34518) "Renew all" button doesn't work in OPAC
- [[12421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12421) No way to get back to search results from overdrive results
- [[34093]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34093) jQuery not loading on OAI XSLT pages
- [[33697]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33697) Remove deprecated RecordedBooks (rbdigital) integration
- [[21330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21330) Add XSLT for authority detail page in OPAC
- [[30621]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30621) Author should be its own column on opac-readingrecord.tt
- [[12029]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12029) Patrons should be able to delete their patron messages
- [[32998]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32998) Consolidate opac-tmpl/lib and opac-tmpl/bootstrap/lib
- [[33160]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33160) Make sure 773 (host item entry) displays in the cart when not linked by $w
- [[29449]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29449) Show userid on "your personal details" tab
- [[31028]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31028) Add 'Report a concern' feature for patrons to report concerns about catalog records
- [[31051]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31051) Show patron's 'savings' on the OPAC
- [[16522]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16522) Add 773 (Host item entry) to the cart and list displays and e-mails

## Packaging

- [[32994]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32994) Remove compiled files from src (2)

## Patrons

- [[26558]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26558) Guarantor information is lost when an error occurs during new account creation
- [[34891]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34891) View restrictions button (patrons page) doesn't link to tab
- [[34402]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34402) Sorting holds on patron account includes articles
- [[34280]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34280) Patrons with no email address produce a warning when saving
- [[33117]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33117) Patron checkout search not working if searching with second surname
- [[33820]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33820) Add hints to warn the librarian that they will be logged out if they change their username
- [[29046]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29046) Allow libraries to specify email order for "AutoEmailPrimaryAddress"
- [[28366]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28366) Add batch patron modification to patron search results
- [[21699]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21699) Allow circulation messages to be editable
- [[33038]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33038) Add classes to category code and category type in patron brief information for easier customization
- [[26598]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26598) Display guarantee's fines on guarantor's details page
- [[32426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32426) Make userid generation pluggable
- [[14251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14251) Allow use of CSS in discharge letter
- [[33266]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33266) Patron name missing space before surname

## Plugin architecture

- [[31339]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31339) Add Template::Toolkit WRAPPER for Koha Tool Plugins
- [[33776]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33776) Add inLibro in default plugin repositories

## Reports

- [[35193]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35193) Rename "Message subject" to "File name" when module "Reports" was chosen
- [[34456]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34456) Add the ability to download a template rendered report as a file
- [[34136]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34136) Add ability to render a report using a notice template
- [[33966]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33966) "Update and run SQL" for non-English templates
- [[30928]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30928) Add interface to statistics table
- [[23824]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23824) Add a 'Save and run' button to reports
- [[32057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32057) Add optional stack trace to action logs
- [[33152]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33152) Set focus for cursor to search input box when creating new report from "New SQL from Mana" option
- [[32613]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32613) Add auto-completion to our SQL reports editor
- [[17350]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17350) Add option to delete data stored in saved_reports with cleanup_database

## REST API

- [[34008]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34008) REST API: Add a list (GET) endpoint for itemtypes
- [[34333]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34333) Add cancellation request information embed option to the holds endpoint
- [[34339]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34339) $c->validation should be avoided (part 2)
- [[33556]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33556) $c->validation should be avoided (part 1)
- [[33996]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33996) Authority objects missing mapping
- [[31798]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31798) Add POST endpoint for Items
- [[21043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21043) Add POST endpoint for patron debits
- [[29453]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29453) Add GET endpoints to fetch patron credits and debits
- [[32735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32735) Add GET endpoint for listing Authorities
- [[33146]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33146) Add public GET endpoint for listing items
- [[32336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32336) MARCXML output of REST API may be badly encoded (UNIMARC)
- [[32118]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32118) Clarify expansion/embed modifiers
- [[32734]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32734) Add GET endpoint for listing Biblios
- [[31793]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31793) Add DELETE endpoint for Authorities

## Searching

- [[33297]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33297) Typo system preference RetainPatronSearchTerms in DB revs 220600044.pl
- [[33190]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33190) Add search history button to advance search form if EnableSearchHistory keep
- [[32960]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32960) Add option in item search for excluding checked out items

## Searching - Elasticsearch

- [[33594]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33594) Sorting results by Title A-Z might use wrong title field
- [[18829]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18829) Elasticsearch - Add ability to view the ES indexed record

## Self checkout

- [[34557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34557) Add option to prevent loading a patron's checkouts on the SCO

## Serials

- [[30451]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30451) Delete a subscription deletes the linked order
- [[32752]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32752) Add new serial issue status: "Out for binding", "Bound", and "Circulating"

## SIP2

- [[34258]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34258) Cannot renew item via SIP2
- [[34101]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34101) Limit items types that can be checked out via SIP2
- [[33580]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33580) Bring back ability to mark item as seen via SIP2 item information request
- [[25812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25812) Fines can be displayed on SIP checkin/checkout
- [[32431]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32431) Show date for expired patrons in SIP

## Staff interface

- [[33169]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33169) Improve vue breadcrumbs and left-hand menu
- [[34639]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34639) Item shown in transit on detail.pl even if marked as arrived or cancelled
- [[34616]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34616) "Edit SMTP server" page - Default SMTP configuration dialog has some issues
- [[33607]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33607) Show framework on record details page
- [[33532]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33532) Catalog concerns - Title of the page says Tools instead of Cataloging
- [[33191]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33191) AutoEmailPrimaryAddress options don't match labels in memberentry
- [[33281]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33281) Improve authority links and add them to MARC preview
- [[30624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30624) Add a permission to control the ability to change the logged in library
- [[28314]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28314) Spinning icon is not always going away for local covers in staff

## System Administration

- [[35078]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35078) Invalid HTML in OpacShowSavings system preference
- [[34748]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34748) Wrong column name basket_number in table settings for basket
- [[34622]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34622) SMTP server edit page unsets is_default if editing default server
- [[33286]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33286) 'Catalog record' should be 'Bibliographic record'
- [[33868]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33868) Upgrade the Multiple Select plugin in the staff interface
- [[27424]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27424) One should be able to assign an SMTP server as the default
- [[33550]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33550) Rename Patron restrictions administration page 'Patron restriction types'
- [[33673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33673) Global system preferences - change to just system preferences
- [[33197]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33197) Terminology: rename GDPR_Policy system preference
- [[32745]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32745) Jobs view breaks when there are jobs with context IS NULL
- [[33192]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33192) We should rename 'AutoEmailPrimaryAddress' to 'EmailFieldPrimary' for clarification

## Templates

- [[35272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35272) Add padding above vendor contracts section
- [[35205]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35205) Fix duplicate id attribute in desks search form
- [[34624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34624) Many header search forms lack for attribute for label
- [[34307]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34307) Update plugin wrapper to use template wrapper for breadcrumbs
- [[34124]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34124) Improve in-page navigation on table settings page
- [[33528]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33528) Use template wrapper for tabs: Patron details and circulation
- [[33343]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33343) Password fields should have auto-completion off
- [[33797]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33797) Extra space in supplier.tt
- [[33774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33774) Loading club table in every tab in patron details
- [[33769]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33769) Terminology:  'Warning: Item {barcode} is reserved'
- [[27775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27775) Add hint about drag and drop feature on framework subfield edit
- [[33349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33349) Patron attributes don't have identifying info in the staff interface
- [[33071]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33071) Show tooltip when hovering on home icon in staff interface breadcrumbs
- [[32319]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32319) Give header search submit button more padding

## Test Suite

- [[35215]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35215) Make a few assumptions more explicit in Suggestions.t
- [[34843]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34843) Koha/Database/Commenter.t is failing if the DB has been upgraded
- [[33733]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33733) Move t/XSLT.t to db_dependent
- [[31479]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31479) Provide an option to skip the test for atomic updates
- [[33584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33584) Fix failures for Database/Commenter.t on MySQL 8

## Tools

- [[24480]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24480) Fields added with MARC modifications templates are not added in an ordered way
- [[26978]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26978) Add item type criteria to batch extend due date tool
- [[34288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34288) Cannot use cataloguing tools without cataloguing permissions
- [[34225]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34225) KohaTable broken on batch item deletion and modification results
- [[32970]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32970) Allow export of batch item modification results in background jobs
- [[32021]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32021) Pages 'appear in position' field is not useful
- [[31611]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31611) More visibly highlight records that cannot be batch deleted/modified
- [[32019]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32019) Add option to mark items returned in batch modification

## Web services

- [[21284]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21284) ILS-DI: Allow GetPatronInfo to tell if a checked out item is on hold for someone else
- [[35008]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35008) ILS-DI should not ask for login with OpacPublic disabled


