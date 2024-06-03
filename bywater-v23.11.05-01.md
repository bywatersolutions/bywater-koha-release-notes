
# Release Notes for bywater-v23.11.05-01

## About

- [[35504]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35504) Release team 24.05
- [[35584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35584) Missing licenses in about page

## Accessibility

- [[35157]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35157) The searchfieldstype select element produces invalid HTML
- [[35365]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35365) Incorrectly closed <th> tag on patron search page

## Acquisitions

- [[36036]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36036) Fix location field when ordering from staged files
- [[35913]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35913) Item order prices do not fall back to MarcFieldsToOrder if not set by MarcItemFieldsToOrder
- [[34853]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34853) Move EDI link to new line in invoice column of acquisition details display
- [[35514]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35514) New order line form: Total prices not updated when adding multiple items
- [[35912]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35912) Item prices not populating order form when adding to a basket from a staged file
- [[35634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35634) Permissions mismatch for vendor issues
- [[34708]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34708) Ability to modify an order line to increase quantity of ordered item
- [[20755]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20755) Allow separate email configuration for acquisition and serials emails
- [[33664]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33664) Add ability to cancel order lines in closed baskets
- [[14092]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14092) Add ability to search on 'all statuses' to orders search
- [[34501]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34501) Patron purchase suggestion table should include the non-public note
- [[12732]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12732) Allow sorting by basket creation date to the late orders table
- [[31631]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31631) Optionally choose for tax-exclusive values to be used for calculating fund values (spent, ordered)
- [[34752]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34752) Use AV descriptions in display for sort1/sort2 in basket display
- [[28449]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28449) Link from basket summary to invoice for an order line
- [[34618]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34618) Add sort 1 and 2 fields to basket in acquisitions
- [[33499]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33499) Make interface URL clickable on vendor details
- [[32984]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32984) The EDIFACT message that receives an item should be linked on the 'Acquisition details' tab on catalogue details page
- [[33105]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33105) Add vendor issues

## Architecture, internals, and plumbing

- [[36244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36244) Template toolkit syntax not escaped in letter templates
- [[35388]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35388) Add comment to circ/transfers_to_send.pl about limited use in stock rotation context
- [[35921]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35921) Improve performance of acquisitions start page when there are many budgets
- [[35248]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35248) Bookings needs unit tests
- [[35950]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35950) Move the handling of statistics patron logic out of CanBookBeIssued
- [[35718]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35718) Remove ES6 warnings from JavaScript system preferences
- [[35490]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35490) Remove GetMarcItem from C4::Biblio
- [[35277]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35277) Pseudonymization should be done in a background job
- [[35833]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35833) Fix few noisy warnings from C4/Koha and search
- [[35687]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35687) Upgrade to 23.06.00.013 may fail
- [[35304]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35304) Add new Sortable library to didyoumean configuration
- [[35194]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35194) Javascript error: Uncaught TypeError: $(...).sortable is not a function
- [[35269]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35269) Koha::Item->update_item_location should be named `trigger_location_update`
- [[33749]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33749) Move Koha::MetadataRecord::stripWhitespaceChars into a RecordProcessor filter
- [[35196]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35196) Remove misc/perlmodule_[ls|rm].pl
- [[35043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35043) Handling of \t in PO files is confusing
- [[34468]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34468) Add a progress callback to job_progress.js
- [[35001]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35001) Simplify patron->is_active in light of TrackLastPatronActivityTriggers
- [[35136]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35136) Error during database update after Bug 31383
- [[31383]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31383) Additional contents: We need a parent and child table
- [[33947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33947) Move GetAllIssues to Koha
- [[33949]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33949) Replace GetAllIssues with Koha::Checkouts - opac
- [[33170]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33170) Refactor MarcItemFieldsToOrder code to make adding more fields simpler
- [[33843]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33843) Use filter_by_last_update in Koha::Notice::Util
- [[33837]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33837) Objects->filter_by_last_update: Does not allow time comparison
- [[29033]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29033) Add C4::Context->multivalue_preference
- [[34828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34828) Add Koha::Biblio::Metadata::Extractor* classes
- [[34336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34336) Test::DBIx::Class should be removed
- [[33958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33958) Add Koha::Biblio->normalized_oclc
- [[33245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33245) Add $patron->is_active
- [[21828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21828) Improve efficiency of C4::Biblio::LinkBibHeadingsToAuthorities
- [[33948]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33948) Replace GetAllIssues with Koha::Checkouts - staff
- [[32496]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32496) Reduce unnecessary unblessings of objects in Circulation.pm
- [[30825]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30825) Get rid of GetReservesControlBranch
- [[34720]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34720) UpdateNotForLoanStatusOnCheckin should be named UpdateNotForLoanStatusOnCheckout
- [[34844]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34844) manage_item_editor_templates is missing from userpermissions.sql
- [[33955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33955) Add Koha::Biblio->normalized_upc
- [[34415]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34415) Remove Test::DBIx::Class from t/EdiTransport.t
- [[34812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34812) Remove Test::DBIx::Class from Koha.t
- [[33045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33045) Use process_tt in C4::Record::marcrecord2csv
- [[34414]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34414) Remove DBD::Mock
- [[33940]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33940) Move get_cardnumber_length and checkcardnumber to Koha
- [[17499]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17499) Koha objects for messaging preferences
- [[34441]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34441) Typo: paramater
- [[34357]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34357) Subroutine Koha::ItemType::SUPER::imageurl redefined
- [[34359]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34359) Get rid of Koha/BiblioUtils/Iterator
- [[34494]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34494) Table tmp_holdsqueue fails to be created for MySQL 8
- [[33379]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33379) virtualshelfcontents.flags seems useless
- [[34321]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34321) Tidy skeleton too
- [[33444]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33444) AddRenewal should take a hash of parameters
- [[33046]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33046) Use process_tt in C4::Reports::Guided::EmailReport
- [[33041]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33041) Use process_tt in C4::Serial::NewIssue
- [[33043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33043) Use process_tt in SIP modules
- [[33745]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33745) Speed up Koha::Object attribute accessors
- [[33956]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33956) opac-user.pl should use Koha::Biblio->opac_summary_html
- [[33954]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33954) Add Koha::Biblio->opac_summary_html
- [[33953]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33953) Add Koha::Biblio->ratings
- [[33952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33952) Add Koha::Biblio->normalized_isbn
- [[34212]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34212) Bug 23336 follow-up code improvements
- [[33963]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33963) Remove C4::BackgroundJob
- [[33962]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33962) Remove C4::BackgroundJob from process_koc
- [[33967]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33967) REMOTE_ADDR incorrect in plack.log when run behind a proxy
- [[32478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32478) Remove Koha::Config::SysPref->find since bypasses cache

## Authentication

- [[34755]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34755) Error authenticating to external OpenID Connect (OIDC) identity provider : wrong_csrf_token
- [[35231]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35231) Cannot logout from OPAC and not login afterwards

## Bywater Only

- NOT IN BUGZILLA - Fix issue with upgrade for bug 31383
- NOT IN BUGZILLA - Remove failing ERM related unit tests, needs debugging
- NOT IN BUGZILLA - remove xt/find-misplaced-executables.t
- NOT IN BUGZILLA - Re-enable building docker images
- NOT IN BUGZILLA - Remove t/db_dependent/selenium/system_preferences_search.t
- NOT IN BUGZILLA - Remove t/db_dependent/selenium/patrons_search.t
- NOT IN BUGZILLA - Koha 23.11.00 is here!
- NOT IN BUGZILLA - Bug 34287: Add check on public availability endpoint
- NOT IN BUGZILLA - Koha 23.06 - start of a new dev cycle

## Cataloging

- [[35651]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35651) Toggle for advanced editor should not show to staff without advanced_editor permissions
- [[35425]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35425) Sortable prevents mouse selection of text inside child input/textarea elements
- [[35383]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35383) Dragging and dropping subfield of repeated tags doesn't work
- [[34275]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34275) Add a button to easily toggle between advanced/basic cataloging editors
- [[31477]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31477) Switch icon for inventory
- [[26314]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26314) "Volumes: show volumes" showing regardless of whether there are volumes linked to the record
- [[32335]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32335) Allow stock rotation items to be moved several stages ahead
- [[34657]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34657) Merge cataloging plugins for UNIMARC 123d, e, f, and g
- [[34029]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34029) Import breaks when data exceeds size of mapped database columns
- [[31132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31132) Add button to clear the cataloguing authority plugin form
- [[33884]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33884) Remove unused Koha::RDF code

## Circulation

- [[36139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36139) Bug 35518 follow-up: fix AutoSwitchPatron
- [[36331]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36331) Items that cannot be held are prevented renewal when there are holds on the record
- [[35944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35944) Bookings is not taken into account in CanBookBeRenewed
- [[35532]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35532) Use of calendar for date range in bookings is not clear
- [[35840]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35840) Local use is double-counted when using both RecordLocalUseOnReturn and statistical patrons
- [[35357]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35357) Item not removed from holds queue when checked out to a different patron
- [[35469]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35469) Cannot create bookings without circulation permissions
- [[35773]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35773) Cannot create bookings without edit_borrowers, label_creator, routing or order_manage permissions
- [[35924]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35924) The 'checkin slip' button should not be available for patrons whose privacy is set to never
- [[36100]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36100) Regression in bookings edit
- [[36175]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36175) Checking out items that are booked doesn't quite work
- [[36091]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36091) Spelling: Use "card number" instead of cardnumber in text
- [[35483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35483) Restore item level to record level hold switch in hold table
- [[30230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30230) Search for patrons in checkout should not require edit_borrowers permission
- [[35535]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35535) Cancel hold -button does not work in pop-up (Hold found, item is already waiting)
- [[35216]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35216) Use return variable names from CanBookBeIssued in circulation.pl for consistency
- [[18139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18139) 'Too many checked out' can confuse librarians
- [[35468]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35468) Bookings permission mismatch
- [[35251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35251) Issue table does not recalculate number of checkouts after a check in
- [[35068]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35068) Split 'Renew or check in selected items' button in issues table into separate buttons
- [[21159]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21159) Update item shelving location (952$c) on checkout
- [[34529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34529) Offline circulation should be able to accept userid as well as cardnumber
- [[35188]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35188) force_checkout permission can override all blocks on a patron account but only shows when they are restricted
- [[28805]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28805) Add on-site option to batch checkout functionality
- [[29002]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29002) Add ability to book items ahead of time
- [[8367]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8367) How long is a hold waiting for pickup at a more granular level
- [[33575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33575) Add table settings to the holds table for a specific record in the staff interface
- [[34924]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34924) Add ability to send 'final auto renewal notice'
- [[33887]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33887) Automatic checkin should be able to optionally fill the next hold with the returned item
- [[25393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25393) Create separate 'no automatic renewal before' rule
- [[34547]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34547) Add transfer reason to list of checkins
- [[34300]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34300) Add link to place a hold on ordered items in baskets
- [[32740]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32740) Add a new option patron home library to OverdueNoticeFrom
- [[25560]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25560) Define itemtype specific rules in the UpdateNotForLoanStatusOnCheckin system preference
- [[9525]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=9525) Add option to define float groups and rules for float
- [[29145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29145) Allow patrons to have overdue items that would not result in debarment when removing overdue debarments
- [[34626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34626) Add waiting since date to holdswaiting patron message
- [[33961]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33961) In-built Offline circulation tool no longer working and should be removed
- [[33398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33398) Show primary_contact_method when holds are triggered
- [[33945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33945) Add ability to delay the loading of the current checkouts table on the checkouts page

## Command-line Utilities

- [[36508]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36508) Patron userid field can be overwritten by update_patron_categories when limiting by fines
- [[35479]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35479) Nightly cronjob for plugins should log the plugins that are being run
- [[26831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26831) Enable librarians to control when unaccepted private list share invites are removed by the cleanup_database.pl cronjob
- [[35074]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35074) Add --patron_category to writeoff_debts.pl
- [[33239]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33239) Add the ability to run borrowers-force-messaging-defaults.pl only on a specified message name
- [[33204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33204) Add the ability to filter on patron library for borrowers-force-messaging-defaults.pl
- [[34064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34064) Compare kohastructure.sql against current database using database audit script
- [[23241]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23241) Remove misc/bin/koha-index-daemon-ctl.sh
- [[28995]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28995) Add --added_after to writeoff_debts.pl
- [[33871]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33871) Add where parameter to sitemap.pl
- [[33698]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33698) Add fields to verbose output of cronjob delete_items.pl

## Database

- [[34328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34328) Add Scottish Gaelic to the advanced search options

## Documentation

- [[34955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34955) One Koha manual

## ERM

- [[35757]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35757) Sushi service and counter registry tests are failing
- [[34587]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34587) Add a Usage Statistics module to ERM
- [[35418]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35418) SUSHI harvest hangs
- [[35115]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35115) ERM - Potential MARC data loss when importing titles from list
- [[35229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35229) Fix and add further cypress tests for Usage reporting
- [[34497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34497) Vue - Dialog component should allow for confirmation input options
- [[34215]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34215) Vue Toolbar component should be more flexible
- [[34789]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34789) Fix typo in erm_eholdings_titles
- [[34735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34735) Current/disabled links in breadcrumbs are styled differently when in ERM module
- [[33480]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33480) Improve display of the vendor aliases in the ERM module
- [[34217]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34217) Add missing cypress tests for vendors in agreements and licenses
- [[34691]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34691) Active link in the menu is not always correctly styled - again
- [[34418]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34418) Allow empty nodes in breadcrumb's elements

## Fines and fees

- [[34985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34985) Add a quantity field to the manual invoice form
- [[34377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34377) Accounting transactions should show managing librarian info for credits/debits
- [[32271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32271) Overdue fines cap (amount) set to 0.00 when editing rule
- [[33028]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33028) Wrongly formatted monetary amounts in circulation rules break scripts and calculations

## Hold requests

- [[35997]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35997) Cancelling a hold should remove the hold from the queue
- [[35489]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35489) Holds on items with no barcode are missing an input for itemnumber
- [[35306]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35306) Expired holds are not displayed correctly in staff interface
- [[17617]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17617) Add the ability of sending a confirmation e-mail to patron when hold is placed
- [[33845]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33845) Hold notes should show when viewing a patron's hold list
- [[33087]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33087) OPACHoldsIfAvailableAtPickup considers On order as available
- [[34160]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34160) Link item barcode to the item more details page from the holds queue viewer
- [[31692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31692) Let librarians change item level holds to record level holds when possible
- [[28966]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28966) Holds queue viewer too slow to load for large numbers of holds
- [[34320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34320) Hold reordering arrows look broken after Font Awesome upgrade

## I18N/L10N

- [[35475]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35475) Untranslatable strings in booking modal and JS
- [[35476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35476) Submit button for adding new processings is not translatable
- [[35376]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35376) Rephrase: Be careful removing attribute to this processing, the items using it will be impacted as well!
- [[35374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35374) Translations contain config from ERM/data providers
- [[35377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35377) Terminology: Callnumber shoudl be call number
- [[35258]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35258) Updating po files locally fails
- [[34098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34098) Improve translation of some strings in the patron import template
- [[35091]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35091) Improve translation of usage statistics country list
- [[34834]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34834) Add translation context for "Order"
- [[3007]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=3007) Remove untranslated unimarc_field_700-4 value builder
- [[34228]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34228) Add translation context to "Managed by"
- [[34247]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34247) Improve translation of notice character count
- [[34433]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34433) 'Custom cover image' in lightbox is untranslatable

## ILL

- [[36130]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36130) ILL batches table not showing all batches
- [[34282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34282) ILL batches - availability checking has issues
- [[34058]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34058) ILL - Left filters not considering all terms in input
- [[18203]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18203) Add per borrower category restrictions on placing ILL requests in OPAC
- [[33970]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33970) We need a "backend" column in "illrequestattributes" table
- [[35098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35098) ILL batch is not displayed in ILL table
- [[35096]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35096) ILL request manage page explodes if it belongs to a batch
- [[35094]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35094) ILL new request is broken
- [[35093]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35093) ILL table is broken
- [[30719]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30719) ILL should provide the ability to create batch requests
- [[34905]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34905) ILL - "Place request with partners" icon is gone
- [[33716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33716) ILL - Allow for a disclaimer stage per request type
- [[32911]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32911) Remove ILL partner_code config from koha-conf.xml and turn it into a system preference
- [[27542]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27542) It should be possible to cancel an ILL request sent to a partner
- [[34598]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34598) Error 500 is shown when ILL request is not found
- [[34351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34351) ILL list table - access_url column content should be clickable
- [[21983]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21983) Better handling of deleted biblios on ILL requests

## Installation and upgrade (command-line installer)

- [[35473]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35473) Core bookings and room reservations plugin tables clash
- [[34979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34979) System preferences missing from sysprefs.sql

## Installation and upgrade (web-based installer)

- [[36232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36232) Error fixing OAI-PMH:AutoUpdateSetsEmbedItemData syspref name on the DB
- [[35686]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35686) Case missing from installer step 3 template title
- [[34520]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34520) Database update 22.06.00.078 breaks update process

## Label/patron card printing

- [[10762]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10762) Make it possible to adjust the barcode height and width on labels

## Lists

- [[15222]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15222) Add to cart option/other list options missing from OPAC lists display

## MARC Authority data support

- [[27943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27943) MARC21 authorities not support 7XX on display
- [[28166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28166) Optionally add MARC fields to authority search
- [[34075]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34075) Allow specifying default tab view for authorities

## MARC Bibliographic data support

- [[34020]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34020) Sequence of MARC 264 subfields different on XSLT result list and detail page
- [[35099]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35099) Cannot load records with invalid marcxml
- [[34667]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34667) Update MARC21 default framework to Update 36 (June 2023)
- [[34665]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34665) Update MARC21 default framework to Update 35 (Dec. 2022)
- [[34659]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34659) Update MARC21 default framework to Update 34 (July 2022)
- [[34658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34658) Update MARC21 default framework to Update 33 (Nov. 2021)
- [[34649]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34649) Update MARC21 default framework to Update 32 (June 2021)
- [[34648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34648) Update MARC21 frameworks to Update 31 (December 2020)
- [[34677]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34677) Update to MARC21 relator terms list

## Notices

- [[31427]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31427) Automatic renewal errors should come before many other renewal errors
- [[18397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18397) Add recipient/sender information to notices tab in staff interface
- [[34854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34854) Add ability to skip Talking Tech Itiva notifications for a patron if a given field matches a given value
- [[32986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32986) Add ability to generate custom slips for patrons
- [[35187]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35187) Fix line breaks in some HTML notices, including WELCOME
- [[8838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8838) Digest option for HOLD notice

## OPAC

- [[34886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34886) Regression in when hold button appears
- [[36070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36070) "Place recall" hover styling on OPAC not consistent
- [[35578]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35578) Validate "Where" in OPAC Authority search
- [[35795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35795) Missing closing tag in OPAC course details template
- [[35841]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35841) Update text of 'Cancel' hold button on OPAC
- [[35676]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35676) OPAC search results - link for "Check for suggestions" generates a blank page
- [[33244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33244) Do not show lists in OPAC if OpacPublic is disabled
- [[34894]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34894) Convert OpacSuppressionMessage system preference to HTML customization
- [[34889]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34889) Convert PatronSelfRegistrationAdditionalInstructions system preference to HTML customization
- [[34869]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34869) Convert OPACResultsSidebar system preference to HTML customization
- [[23798]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23798) Convert OpacMaintenanceNotice system preference to additional contents
- [[35261]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35261) Update links for self registration avoiding "here"
- [[34438]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34438) OPAC self registration form does not include lang (preferred language for notices) field
- [[34866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34866) Use template wrapper for breadcrumbs: OPAC part 4
- [[34855]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34855) Use template wrapper for breadcrumbs: OPAC part 3
- [[26824]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26824) Use confirmation modal when removing titles from a list in the OPAC
- [[33809]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33809) Accessibility: OPAC results page needs more descriptive links
- [[31503]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31503) Allow several consent types on the consents tab of OPAC account page
- [[32721]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32721) Allow specifying UserCSS and UserJS at library level for the OPAC
- [[34852]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34852) Use template wrapper for breadcrumbs: OPAC part 2
- [[34849]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34849) Use template wrapper for breadcrumbs: OPAC part 1
- [[28130]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28130) Show list of serial email alerts a patron subscribed to in patron account in OPAC
- [[33812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33812) Accessibility: OPAC messaging preferences is missing form labels
- [[34865]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34865) Syspref OPACURLOpenInNewWindow not working for Library URLs
- [[27634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27634) Turn off patron self-registration if no default category is set
- [[33818]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33818) Accessibility: Non descriptive title on ISBD detail
- [[27378]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27378) Enable compliance with EU Cookie Legislation via cookie consent
- [[34584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34584) Remove Twitter share button from the OPAC
- [[32711]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32711) Add biblio details to trusted self-checkout modal
- [[30979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30979) Add ability for OPAC users to checkout to themselves
- [[29691]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29691) Use template plugins to display OPAC news on homepage
- [[33697]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33697) Remove deprecated RecordedBooks (rbdigital) integration

## Patrons

- [[35980]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35980) Add message to patron needs permission check
- [[35445]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35445) OPAC registration verification triggered by email URL scanners
- [[35743]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35743) The "category" filter is not selected in the column filter dropdown
- [[35356]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35356) SMS number field shows on moremember.pl even when null
- [[35366]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35366) Circulation history of patron is only visible when there is a current checkout
- [[35335]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35335) Circulation history tab in patron information causes 500 error
- [[12133]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12133) Guarantor requirements when registering a patron
- [[34517]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34517) Add option to search patron attribute in standard search
- [[21431]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21431) Differentiate password change and password reset in action logs
- [[15157]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15157) Cronjob to automatically restrict patrons with pending/unpaid charges
- [[35264]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35264) Update patron import to use protected column
- [[32730]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32730) Add patron lists tab to patron details and circulation pages
- [[26170]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26170) Add protected status for patrons
- [[35030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35030) Extend TrackLastPatronActivity with placing article request
- [[35027]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35027) Add holds to patron activity triggers
- [[15504]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15504) Track Patron's Last Activity
- [[31357]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31357) Separate holds history from intranetreadinghistory
- [[33620]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33620) Don't show patron-privacyguarantor/patron-privacy_guarantor_fines if  borrowerRelationship is empty
- [[16223]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16223) Automatically remove any borrower debarments after a payment
- [[12532]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12532) Copy guarantee email to guarantor (or redirect if guarantee has no email set)
- [[28688]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28688) Automatically renew patron membership
- [[33522]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33522) Optionally skip (in)active patrons when sending membership expiry notices
- [[33428]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33428) Should only search in searchable patron attributes if searching in standard fields
- [[33271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33271) Show information about patron's guarantees charges on patron details page
- [[33117]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33117) Patron checkout search not working if searching with second surname

## Plugin architecture

- [[30897]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30897) Gracefully reload Koha after plugin install/upgrade
- [[35930]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35930) ILL module broken if plugins disabled
- [[25672]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25672) Administrators should be able to restrict client-side plugin upload to trusted sources

## Preservation

- [[35759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35759) Preservation module home yields a blank page
- [[35477]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35477) Adding non-existent items to the waiting list should display a warning
- [[35463]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35463) Link preservation module help to the manual
- [[35387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35387) Capitalization: Labels in preservation module are not capitalized
- [[34030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34030) Print slips in a batch from the preservation module
- [[33547]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33547) Print slips from the preservation module
- [[30708]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30708) Creation of a new 'Preservation' module

## Reports

- [[35936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35936) Cannot save existing report with incorrect AV category
- [[33608]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33608) Allow to get statistics about found/recovered books
- [[23059]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23059) reserves_stats.pl: Simplify reserve status handling
- [[6419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=6419) Add customizable areas to intranet home pages

## REST API

- [[36329]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36329) Transfer limits should respect `BranchTransferLimitsType`
- [[33036]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33036) Add route to merge bibliographic records
- [[35368]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35368) "Add a checkout" shows up twice in online documentation
- [[35744]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35744) Implement +strings for GET /patrons/:patron_id
- [[35218]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35218) No tests for /erm/sushi_service
- [[35219]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35219) ERM usage endpoints not showing up in documentation
- [[35230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35230) `catalogue_item` missing description
- [[29523]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29523) Add a way to prevent embedding objects that should not be allowed
- [[33690]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33690) Add ability to send welcome notice when creating patrons using the REST API
- [[34333]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34333) Add cancellation request information embed option to the holds endpoint
- [[34339]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34339) $c->validation should be avoided (part 2)
- [[33556]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33556) $c->validation should be avoided (part 1)
- [[23336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23336) Add an API endpoint for checking an item out to a patron
- [[33971]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33971) Remove support for x-koha-query header

## Searching

- [[26468]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26468) Item search should include a way to limit by damaged
- [[33217]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33217) Allow different default sorting when click author links

## Searching - Elasticsearch

- [[35265]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35265) Remove drag and drop in Elasticsearch mappings
- [[35618]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35618) catalogue/showelastic.pl uses deprecated/removed parameter "type"
- [[33353]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33353) Add compatibility with Elasticsearch 8 and OpenSearch 2
- [[27153]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27153) ElasticSearch should search keywords apostrophe blind

## Self checkout

- [[35065]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35065) Convert SelfCheckHelpMessage system preference to HTML customization
- [[35063]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35063) Convert SelfCheckInMainUserBlock system preference to HTML customization
- [[35048]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35048) Convert SCOMainUserBlock system preference to HTML customization
- [[34557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34557) Add option to prevent loading a patron's checkouts on the SCO
- [[35007]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35007) Configure self checkout tables consistently
- [[35013]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35013) Font Awesome icons broken in self checkout and self checkin

## Serials

- [[31297]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31297) Cannot add new subscription patterns from edit subscription page
- [[31846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31846) Allow setting serials search results limit
- [[34199]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34199) Add part_name and part_number to subscription detail page
- [[34230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34230) Add part_name and part_number to subscription result list
- [[30451]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30451) Delete a subscription deletes the linked order
- [[33039]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33039) Add ability to specify a template for serial subscription "Published on (text)" field

## SIP2

- [[36605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36605) TrackLastPatronActivity for SIP should track both patron status and patron information requests
- [[34868]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34868) Add ability for SIP2 to distinguish missing item from other lost types
- [[25814]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25814) SIP: Add a message on successful checkin
- [[25816]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25816) Add OPAC messages in SIP display
- [[34153]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34153) Add ability to allow items with additional materials notes to be checked out via SIP
- [[34737]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34737) Enhance SIP2SortBinMapping to support additional match conditions
- [[34016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34016) Enable fulfillment of recalled items through SIP2

## Staff interface

- [[36215]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36215) Bookings calendar only shows bookings within RESTdefaultPageSize
- [[36150]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36150) Circulation home page styling does not match Cataloging home page styling
- [[35389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35389) Hide 'Transfers to send' on circulation home page when stock rotation is disabled
- [[35300]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35300) Add page-section to table of invoice files
- [[35753]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35753) Checkbox() function in additional-contents not necessary
- [[35396]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35396) Replace Datatables' column filters throttling with input timeout
- [[35742]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35742) Cannot remove new user added to fund
- [[35745]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35745) Setting suggester on the suggestion edit form does not show library and category
- [[33464]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33464) Report "Orders by fund" is missing page-section class on results
- [[34298]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34298) Duplicate existing orders is missing page section on order list
- [[34872]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34872) Cart pop-up is missing page section
- [[35772]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35772) Double escaping of patron fields in bookings modal
- [[35592]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35592) Missing closing div tag in bookings alert in circulation.tt
- [[35574]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35574) Bookings page should require only manage_bookings permissions
- [[35303]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35303) Staff interface header - patron search autocomplete no longer works (Uncaught TypeError: search_fields.forEach is not a function)
- [[26916]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26916) Show searchable patron attributes in patron search dropdown
- [[34188]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34188) Require library selection when logging in
- [[35059]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35059) Display item's shelving location on the items tab
- [[34227]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34227) Add persistent selections and batch operations to item search
- [[35119]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35119) Make bibliographic encoding errors more prominent and match current styling
- [[35037]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35037) Revise the appearance of the last patron button
- [[21246]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21246) Extend the 'Last patron' navigation feature to 'Last X patrons'
- [[34873]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34873) "Sending your cart/list" headings are inconsistent
- [[34055]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34055) Add API client class to get items
- [[34660]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34660) Make the Deliveries table on housebound.tt a dataTable for easier sorting
- [[14156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14156) Add id tags to each MARC note in the display
- [[34721]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34721) Change facet description for Limit to available items to accurately reflect what it does
- [[34135]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34135) Show the icons for selected tab to the left of the search bar in the staff interface
- [[34292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34292) Date formatting in checkouts list broken
- [[32910]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32910) Upgrade fontawesome icons to V6
- [[33988]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33988) Font awesome fa-gears on staff main page look wrong after upgrade to FA6

## System Administration

- [[35530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35530) Can't tell if UserCSS and UserJS in libraries are for staff interface or OPAC
- [[35831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35831) Move UpdateItemLocationOnCheckout to Checkout policy section
- [[35395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35395) Update description of DefaultPatronSearchMethod
- [[35293]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35293) Regression: Bug 33390 (QA follow-up) patch overwrote the template changes to bug 25560
- [[35460]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35460) Unable to add or edit hold rules in circulation rules table
- [[34791]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34791) CookieConsent preference should hint that there's HTML content blocks available for customisation
- [[33390]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33390) Expand links to authorized values interface when an authval is mentioned in preferences
- [[35263]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35263) Cannot update patron categories
- [[35221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35221) TrackLastPatronActivityTriggers description is misleading
- [[31832]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31832) Add reference for EnableItemGroups to EnableItemGroupHolds system preference
- [[35057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35057) Improve table heading "Lib" in MARC field structure page
- [[35032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35032) Remove the use of "onclick" from Koha to MARC mapping template
- [[31731]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31731) Offer user a dropdown of authorized values instead of a text field in preferences
- [[34748]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34748) Wrong column name basket_number in table settings for basket
- [[29822]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29822) Use table column selection modal for DefaultPatronSearchFields preference
- [[33828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33828) ExportCircHistory description is misleading
- [[34807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34807) Move EnableItemGroups in cataloging preferences
- [[34240]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34240) Add hint about having to use Koha-to-MARC mappings for Koha link in frameworks

## Templates

- [[36382]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36382) XSS in showLastPatron dropdown
- [[35426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35426) Improve layout of bookings modal form
- [[35422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35422) Unexpected translation string for Suggestions template
- [[35397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35397) SIP2AddOpacMessagesToScreenMessage syspref description issue
- [[36157]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36157) Links in the "Run with template" dropdown at guided_reports.pl have odd formatting
- [[36158]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36158) Text on the "Show SQL code" button at guided_reports.pl breaks if report notice templates exist
- [[34862]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34862) blocking_errors.inc not included everywhere
- [[35951]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35951) We don't need category-out-of-age-limit.inc
- [[35406]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35406) Typo in holds queue viewer template
- [[35350]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35350) Update label creator pop-up windows with consistent footer markup
- [[35349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35349) Reindent label item search template
- [[35820]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35820) Table on Hold ratios page at circ/reserveratios.pl has wrong id
- [[35407]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35407) Terminology: Show fewer collection codes
- [[35323]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35323) Terminology: Add additional elements to the "More Searches" bar...
- [[35260]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35260) Review batch checkout page
- [[35893]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35893) Missing closing li HTML tag in opac.pref
- [[35379]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35379) 'searchfield' parameter name misleading when translating
- [[35419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35419) Update page title for bookings
- [[35517]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35517) Choose correct default header search tab according to permissions
- [[35602]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35602) Typo: AutoMemberNum
- [[35650]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35650) 'Check the logs' string dot-inconsistent
- [[35529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35529) Avoid 'click' for links in library administration
- [[35417]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35417) Update breadcrumbs and page titles for vendor issues
- [[35413]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35413) Terminology: differentiate issues for vendor issues and serials
- [[35528]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35528) Avoid 'click' for links in system preferences
- [[35526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35526) Terminology: Id, sushi and counter are abbreviations
- [[35525]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35525) Spelling: SMS is an abbreviation
- [[35524]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35524) Terminology: Bookseller in basket group CSV export
- [[35523]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35523) Fix doubled up quotes in cash register deletion confirmation message
- [[35450]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35450) Preservation system preferences should be authorised value pull downs
- [[34398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34398) Inconsistencies in Record matching rules page titles, breadcrumbs, and header
- [[35449]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35449) Accessibility: No links on "here"
- [[35415]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35415) Rephrase: Some patrons have requested a privacy ...
- [[35404]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35404) Wrong copy and paste in string (ILL batches)
- [[35412]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35412) Capitalization: Toggle Dropdown
- [[35378]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35378) 'This authority type is used {count} times' missing dot
- [[34519]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34519) Add a template plugin for ExtendedAttributeTypes to fetch searchable patron attributes
- [[34404]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34404) Inconsistencies in Budgets and funds page titles, breadcrumbs, and header
- [[35241]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35241) Markup errors in point of sale template
- [[33928]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33928) Improve translation of title tags: Various
- [[34773]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34773) Improve translation of title tags: Cataloging tools
- [[34397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34397) Inconsistencies in Classification sources page titles, breadcrumbs, and header
- [[34406]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34406) Inconsistencies in Identity providers/domains page titles, breadcrumbs, and header
- [[34802]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34802) Improve translation of title tags: Tags and comments
- [[34769]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34769) Improve translation of title tags: Patron lists
- [[34940]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34940) Highlight logged-in library in facets
- [[33916]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33916) Improve translation of title tags: Labels
- [[34824]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34824) Add colon after "Title" in new acquisition order details
- [[34422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34422) Reindent facets.inc
- [[34831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34831) Add input types "tel", "email" and "url" to vendor edit form
- [[34392]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34392) Run automated Stylelint fixes on staff CSS
- [[35058]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35058) No contents displaying when an authority record is saved
- [[34401]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34401) Inconsistencies in Item search fields page titles, breadcrumbs, and header
- [[34395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34395) Inconsistencies in Authority types page titles, breadcrumbs, and header
- [[34399]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34399) Inconsistencies in Record overlay rules page titles, breadcrumbs, and header
- [[34405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34405) Inconsistencies in EDI accounts/Library EAN page titles, breadcrumbs, and header
- [[33426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33426) Add client storage of user-selected DataTables configuration to suggestion.tt
- [[26053]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26053) Add styling to show expired patron restrictions as inactive
- [[34393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34393) Inconsistencies in MARC bibliographic framework page titles, breadcrumbs, and header
- [[34562]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34562) Update more pop-up windows with consistent footer markup
- [[34390]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34390) Inconsistencies in Credit types page titles, breadcrumbs, and header
- [[34796]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34796) Improve translation of title tags: Tools - Additional tools
- [[34661]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34661) Update UNIMARC cataloging plugins with consistent footers
- [[34566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34566) Update MARC21 cataloging plugins with consistent footers
- [[34630]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34630) Update MARC21 cataloging plugin templates with consistent body class
- [[34270]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34270) Upgrade and prune jQueryUI assets in the staff interface
- [[34035]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34035) Move translatable strings out of opac-bottom.inc: Tags
- [[34034]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34034) Move translatable strings out of opac-bottom.inc: OverDrive and OpenLibrary
- [[34031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34031) Move various translatable strings out of opac-bottom.inc
- [[34026]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34026) Move translatable cover-handling strings out of opac-bottom.inc
- [[33983]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33983) Move translatable strings out of OPAC's datatables.inc into JavaScript
- [[34619]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34619) Show debug mode column in list of SMTP servers
- [[34389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34389) Inconsistencies in Debit types page titles, breadcrumbs, and header
- [[34391]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34391) Inconsistencies in Cash registers page headers
- [[34114]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34114) Replace the use of jQueryUI sortable
- [[34453]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34453) Update background of quick spine label pop-up
- [[34383]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34383) Inconsistencies in Patron attributes page titles, breadcrumbs, and header
- [[34553]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34553) Update send list and send cart popup footers
- [[33911]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33911) Improve translation of title tags: Catalog, basket, and lists
- [[33927]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33927) Improve translation of title tags: Tools
- [[33919]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33919) Improve translation of title tags: Patron clubs
- [[33918]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33918) Improve translation of title tags: Patron card creator
- [[33924]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33924) Improve translation of title tags: Rotating collections
- [[34400]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34400) Inconsistencies in OAI sets page titles, breadcrumbs, and header
- [[34411]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34411) Inconsistencies in Additional fields page titles, breadcrumbs, and header
- [[34409]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34409) Inconsistencies in Audio alerts page titles, breadcrumbs, and header
- [[34407]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34407) Inconsistencies in Z39.50 servers page titles, breadcrumbs, and header
- [[34380]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34380) Inconsistencies in Item types page titles, breadcrumbs, and header
- [[34624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34624) Many header search forms lack for attribute for label
- [[34403]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34403) Inconsistencies in Currencies and exchange rates page titles, breadcrumbs, and header
- [[34412]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34412) Inconsistencies in system preferences page titles, breadcrumbs, and header
- [[34085]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34085) Remove the use of event attributes from basket groups template
- [[33895]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33895) Use template wrapper for tabs: OPAC user summary
- [[34394]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34394) Inconsistencies in MARC Bibliographic framework test page title and breadcrumbs
- [[34196]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34196) UI adjustment to filters on funds administration page
- [[34043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34043) Improve translation of CSV header templates
- [[34373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34373) Improve layout of curbside pickups items ready list
- [[34323]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34323) Enhance header search icon for more options
- [[33921]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33921) Improve translation of title tags: Plugins and Point of sale
- [[33915]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33915) Improve translation of title tags: Installer and onboarding
- [[33917]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33917) Improve translation of title tags: Offline circulation and patron lists
- [[31014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31014) Minor UI problems in QOTD editor tool
- [[33923]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33923) Improve translation of title tags: Reports
- [[33922]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33922) Improve translation of title tags: Recalls
- [[33914]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33914) Improve translation of title tags: Course reserves
- [[33912]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33912) Improve translation of title tags: Cataloging
- [[33908]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33908) Improve translation of title tags: Acquisitions
- [[34388]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34388) Inconsistencies in Patron restriction types page headers
- [[34408]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34408) Inconsistencies in SMTP servers page titles, breadcrumbs, and header
- [[33910]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33910) Improve translation of title tags: Authorities
- [[33913]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33913) Improve translation of title tags: Circulation, holds, and ILL
- [[33920]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33920) Improve translation of title tags: Patrons
- [[34384]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34384) Inconsistencies in Library transfer limits page titles, breadcrumbs, and header
- [[34382]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34382) Inconsistencies in Patron categories page titles, breadcrumbs, and header
- [[34381]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34381) Inconsistencies in Authorized values page title
- [[34378]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34378) Inconsistencies in Libraries page titles, breadcrumbs, and header
- [[34129]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34129) Responsive table button icon broken after FontAwesome upgrade
- [[34344]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34344) Make item types breadcrumbs uniform
- [[34197]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34197) Group and label vendor contact settings
- [[34322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34322) Correct icon triggering more fund search options
- [[33909]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33909) Improve translation of title tags: Administration
- [[34226]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34226) Format dates from DT filters before querying the REST API
- [[33804]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33804) Implement as_due_date for $date (js-date-format)
- [[34112]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34112) Replace fa.fa-pencil-alt with fa-solid.fa-pencil in edit buttons
- [[34042]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34042) Item search broken by FontAwesome upgrade
- [[33998]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33998) Installer and onboarding have incorrect Font Awesome asset links

## Test Suite

- [[36356]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36356) FrameworkPlugin.t does not rollback properly
- [[35940]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35940) Cypress tests for the Preservation module are failing
- [[35556]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35556) selenium/administration_tasks.t failing if too many patron categories
- [[35393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35393) Fix Objects.t for a Jenkins failure when run just after midnight
- [[35201]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35201) Cypress tests for the Preservation module are failing
- [[35041]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35041) Fix Jenkins failure on t_db_dependent_Koha_Patron_t
- [[34842]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34842) t/db_dependent/Illrequest/Config.t is failing if the DB has been upgraded
- [[34843]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34843) Koha/Database/Commenter.t is failing if the DB has been upgraded
- [[34845]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34845) GetBasketGroupAsCSV.t is failing if the DB has been upgraded
- [[34319]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34319) Upgrade Cypress
- [[33833]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33833) Remove  Test::DBIx::Class from t/SocialData.t
- [[34690]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34690) Cypress - Fix random failure in Dialog_spec.ts
- [[33870]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33870) Remove T::D::C from Sitemapper.t
- [[33869]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33869) Move Matcher.t to db_dependent

## Tools

- [[36159]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36159) Patron imports record a change for non-text columns that are not in the import file
- [[34977]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34977) Allow to delete multiple patron lists at once
- [[34964]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34964) Add descriptions for different HTML customization regions
- [[29181]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29181) Allow patron card creator to use a report to get list of borrowers
- [[34820]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34820) Improve inventory tool message for items with non-matching notforloan values
- [[34818]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34818) Cannot perform batch patron modification without selecting a patron attribute
- [[21083]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21083) Batch patron modification does not allow to modify repeatable patron attributes
- [[34288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34288) Cannot use cataloguing tools without cataloguing permissions
- [[25079]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25079) Show club enrollment question answers in staff interface


