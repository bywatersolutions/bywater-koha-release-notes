
# Release Notes for masscat-v22.05.07-01

## About

- [[30544]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30544) Add font awesome version to licenses page

## Acquisitions

- [[31017]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31017) Add type field for vendors
- [[32167]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32167) When adding an order from a a staged file without item fields we only add price if there is a vendor discount
- [[31367]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31367) Display of sub-funds does not include totals of sub-sub-funds on acquisitions home page
- [[27550]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27550) "Duplicate budget" does not keep users associated with the funds
- [[30359]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30359) GetBudgetHierarchy is slow on order receive page
- [[29658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29658) Crash on cancelling cancelled order
- [[23202]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23202) Problems when adding multiple items to an order in acquisitions
- [[30658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30658) (Bug 29496 follow-up) CheckMandatorySubfields don't  work properly with select field in serials-edit.tt for Supplemental issue
- [[30268]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30268) When creating an order from a staged file, mandatory item subfields that are empty do not block form submission
- [[31144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31144) When modifying an order we should not load the vendor default discount
- [[14680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14680) When creating orders from a staged file discounts supplied in the form are added
- [[31134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31134) t/Ediorder.t tests failing on 22.05.02
- [[31054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31054) Manual importing for EDIFACT invoices fails with a 500 error page
- [[30938]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30938) Fix column configuration to the acquisitions home page
- [[29607]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29607) addorderiso2709: The stored discount when importing an order from a file is invalid
- [[30127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30127) By default show pending suggestions tab
- [[30510]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30510) Add a Patron reason column to the suggestion table in the staff interface
- [[28082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28082) Add acquisitions toolbar to vendors on vendor search page
- [[30438]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30438) Add select all/clear buttons to invoices.tt open and closed tables
- [[30135]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30135) We should allow configuration of whether EDI LSQ segments map to 'location' or 'collection'
- [[30130]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30130) Allow setting EDI type at the vendor level
- [[16258]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16258) Add a preference to turn EDIFACT off
- [[27212]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27212) Add column configuration to the acquisitions home page
- [[24866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24866) Display budget hierarchy in the budget dropdown menu used when placing a new order
- [[26296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26296) Use new table column selection modal for OPAC suggestion fields

## Architecture, internals, and plumbing

- [[30813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30813) Refactor TransformMarcToKoha to remove TransformMarcToKohaOneField
- [[29955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29955) Move C4::Acquisition::populate_order_with_prices to Koha::Acquisition::Order
- [[30982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30982) Use the REST API for background job list view
- [[28167]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28167) A warning when setting which library to use in intranet and UseCashRegisters is disabled
- [[30042]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30042) Remove Date::Calc use
- [[31177]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31177) Misplaced import in C4::ILSDI::Services
- [[30262]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30262) opac/tracklinks.pl inconsistent with GetMarcUrls for whitespace
- [[32011]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32011) 2FA - Problem with qr_code generation
- [[31390]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31390) Remove noisy warns in C4::Templates
- [[31351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31351) Worker dies on reindex job when operator last name/first name/branch name contains non-ASCII chars
- [[31473]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31473) Test about bad OpacHiddenItems conf fragile
- [[31222]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31222) DBIC queries for batch mod can be very large
- [[31245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31245) Job detail view for batch mod explode if job not started
- [[31274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31274) OPACSuggestionAutoFill must be 1 or 0
- [[27849]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27849) Koha::Token may access undefined C4::Context->userenv
- [[30984]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30984) Action logs should log the cronjob script name that generated the given log
- [[30468]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30468) koha-mysql does not honor Koha's timezone setting
- [[31145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31145) Add some defaults for acquisitions in TestBuilder
- [[31001]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31001) "CGI::param called in list context" warning in basket.pl flooding error log
- [[30823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30823) Recalls should use 'FILL' in action logs
- [[30744]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30744) Use RecordProcessor in get_marc_notes to ensure non-public notes do not leak
- [[30848]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30848) Introduce Koha::Filter::ExpandCodedFields
- [[31058]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31058) Bad import in auto_unsuspend_holds
- [[30939]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30939) remove_unused_authorities.pl is broken
- [[31053]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31053) Add Context module to Koha/Encryption
- [[29454]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29454) Stash itemtypes in plugin objects to reduce DB calls
- [[30950]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30950) timepicker.inc is no longer used and should be removed
- [[30954]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30954) includes/background_jobs_update_elastic_index.inc  must be removed
- [[30974]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30974) Job size not correct for indexing jobs
- [[30409]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30409) barcodedecode() should always trim barcode
- [[30399]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30399) Patron.t fails when there is a patron attribute that is mandatory
- [[30877]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30877) use List::MoreUtils::uniq from recalls_to_pull.pl
- [[30057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30057) Move Virtualshelves exceptions to their own file
- [[29871]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29871) Remove marcflavour param in Koha::Biblio->get_marc_notes
- [[30876]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30876) recalls/recalls_to_pull.pl introduces an incorrect use of ->search in list context
- [[30009]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30009) Records with invalid MarcXML show notes tab 'Descriptions(1)' but tab is empty
- [[30714]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30714) Checkins from other branches spam the cataloguing log
- [[30728]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30728) Allow real-time holds queue opt-out
- [[30727]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30727) Holds queue updates can be called multiple times on batch record deletion
- [[30668]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30668) UpdateItemLocationOnCheckin spams the cataloguing log
- [[30703]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30703) Remove a few CookieManager warnings
- [[30702]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30702) Remove Context L785 warning
- [[30638]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30638) Odd number of elements in anonymous hash at C4/Letters.pm line 827
- [[30639]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30639) Patron search does not split search terms
- [[30467]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30467) BatchDeleteItem task does not deal with indexation correctly
- [[30465]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30465) BatchUpdateBiblio task does not deal with indexation correctly
- [[28998]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28998) Encrypt borrowers.secret
- [[30464]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30464) BatchUpdateAuthority task does not deal with indexation correctly
- [[30460]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30460) BatchDeleteBiblio task does not deal with indexation correctly
- [[30459]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30459) BatchDeleteAuthority task does not deal with indexation correctly
- [[30291]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30291) Rename recalls.* column names
- [[30692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30692) Wrong progress displayed for ES indexing tasks
- [[30360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30360) Add helper methods to Koha::BackgroundJobs
- [[30167]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30167) Return soonest renewal date when CanBookBeRenewed returns %too_soon
- [[27344]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27344) Implement Elastic's update_index_background using Koha::BackgroundJob
- [[29894]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29894) 2FA: Add few validations, clear secret, send register notice
- [[30626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30626) DT REST API wrapper not building the filter query correctly
- [[28371]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28371) Improve performance of XSLTParse4Display
- [[29155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29155) Upgrade jquery version to 3.6.0
- [[27253]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27253) borrowers.updated_on cannot be null on fresh install, but can be null with upgrade
- [[29420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29420) HTTP status code incorrect when calling error pages directly under Plack/PSGI
- [[29483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29483) AllowRenewalIfOtherItemsAvailable has poor performance for records with many items
- [[27783]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27783) Introduce background job queues
- [[26019]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26019) Koha should set SameSite attribute on cookies
- [[29859]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29859) Favor iterators over as_list
- [[29957]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29957) Cookies not removed after logout
- [[29695]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29695) Centralize columns' descriptions
- [[30501]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30501) sysprefs.sql has an error
- [[30076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30076) Add ability to check patron messaging preferences from a notice
- [[29609]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29609) Links to guess the biblio default view need to be centralized
- [[30345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30345) Koha::BackgroundJob->enqueue should set borrowernumber=undef if no userenv
- [[30394]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30394) Add 'draw' handling to the datatables wrapper and REST API
- [[30393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30393) datatables wrapper should handle searching for %, _ and \
- [[28416]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28416) Email::Sender::Transport::SMTP is using 10Mo of RAM
- [[30059]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30059) Add a JS equivalent to Koha::Patron->get_age
- [[29791]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29791) KohaOpacLanguage cookie should set the secure flag if using HTTPS
- [[30294]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30294) Rename Koha::Recall->* used relationship names
- [[29788]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29788) Make Koha::Item->safe_to_delete return a Koha::Result::Boolean object
- [[29486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29486) _koha_marc_update_bib_ids no longer needed for GetMarcBiblio
- [[30181]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30181) Koha::BackgroundJob->_derived_class returns an empty object
- [[30061]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30061) Simplify Koha::Patron->get_age
- [[30058]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30058) Add a Koha::Patrons method to filter by permissions
- [[30007]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30007) Make ->anonymize methods throw an exception if AnonymousPatron is not set
- [[29857]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29857) We must stringify our exceptions correctly
- [[30023]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30023) Add Koha::Old::Checkout->anonymize
- [[29703]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29703) Simplify GetBranchItemRule using get_effective_rules
- [[30060]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30060) Missing primary key on user_permissions
- [[29844]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29844) Remove uses of wantarray in Koha::Objects
- [[29660]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29660) reserve/request.pl should not deal with biblioitem
- [[26704]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26704) Koha::Item store triggers should utilise Koha::Object::Messages for message passing
- [[29397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29397) Add a select2 wrapper for the API
- [[29984]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29984) Remove unused method Koha::Patrons->anonymise_issue_history
- [[29843]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29843) Add ->anonymize and ->filter_by_anonymizable to Koha::Old::Checkouts
- [[29868]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29868) Add Koha::Old::Hold->anonymize
- [[29869]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29869) Add Koha::Hold->fill
- [[29780]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29780) Add Koha::Old::Holds->anonymize
- [[29847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29847) Koha::Patron::HouseboundProfile->housebound_visits should return a resultset
- [[29914]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29914) check_cookie_auth not strict enough
- [[29562]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29562) Pass objects to CanItemBeReserved and checkHighHolds
- [[29757]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29757) Add filter_by_non_reversible/reversible methods for offsets
- [[29629]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29629) Remove two unused intranet MODS XSLT sheets
- [[29403]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29403) dt_from_string should fail if passed more data than expected for the format
- [[29718]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29718) DateTime - our 'iso' is not ISO 8601
- [[18320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18320) patroncards/edit-layout.pl raises warnings
- [[29336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29336) Some authorised_value FKs are too short
- [[18540]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18540) koha-indexdefs-to-zebra.xsl introduces MARC21 stuff into UNIMARC xslts
- [[29516]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29516) Remove dependency on IO::Scalar
- [[29789]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29789) Unused $error in cataloguing/additem.pl
- [[29765]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29765) Make Koha::Patron->safe_to_delete return a Koha::Result::Boolean object
- [[29746]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29746) Add a handy Koha::Result::Boolean class
- [[27266]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27266) Move C4::Biblio::GetMarcAuthors to Koha namespace
- [[28617]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28617) misc/kohalib.pl no longer useful

## Authentication

- [[31382]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31382) Cannot reach password reset page when password expired
- [[31247]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31247) Staff interface 2FA blocks logging into the OPAC
- [[30842]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30842) Two-factor  authentication code should be valid longer
- [[29926]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29926) Add ability for superlibrarians to edit password expiration dates
- [[29925]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29925) Add a 'set new password' page for patron's with expired passwords
- [[29924]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29924) Introduce password expiration to patron categories
- [[29873]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29873) 2FA: Generate QR code without exposing secret via HTTP GET
- [[28786]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28786) Two-factor authentication for staff client - TOTP
- [[29915]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29915) Anonymous session generates 1 new session ID per hit

## Bywater Only

- NOT IN BUGZILLA - Set borrower date fields to NULL if the value is "0000-00-00"
- NOT IN BUGZILLA - GitHub Actions - Notify package importer
- NOT IN BUGZILLA - Remove t/00-check-atomic-updates.t
- NOT IN BUGZILLA - Bug 31219: Prevent JS injection in patron extended attributes
- NOT IN BUGZILLA - Correct version in Koha.pm
- NOT IN BUGZILLA - Remove atomicupdate file
- NOT IN BUGZILLA - Koha 22.05.00 is here!
- NOT IN BUGZILLA - 22.05.00: Fix translations (bis)
- NOT IN BUGZILLA - 22.05.00: Fix translations
- NOT IN BUGZILLA - 22.05.00: Update kohastructure.sql
- NOT IN BUGZILLA - 22.05.00: Update mailmap
- NOT IN BUGZILLA - 22.05.00: Update history.txt
- NOT IN BUGZILLA - 22.05.00: Update contributors.yaml
- NOT IN BUGZILLA - Add Jeremy Breuillard to mailmap
- NOT IN BUGZILLA - Add Thibaud Guillot to mailmap

## Cataloging

- [[31643]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31643) Link authorities automatically requires ALL cataloging and authorities permissions
- [[27981]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27981) Add option to automatically set the 001 control number to the biblionumber
- [[31818]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31818) Advanced editor doesn't show keyboard shortcuts
- [[31234]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31234) SubfieldsToAllowForRestrictedEditing : data from drop-down menu not stored
- [[31646]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31646) Focus input by default when clicking on a dropdown field in the cataloguing editor
- [[31250]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31250) Don't remove advanced/basic cataloging editor cookie on logout
- [[31863]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31863) Advanced cataloging editor no longer auto-resizes
- [[30909]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30909) Regression, Permanent shelving location is always updated when editing location VIA ADDITEM.PL if both are mapped to MARC fields
- [[31223]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31223) Batch edit items explodes if plugins disabled
- [[27683]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27683) Bind results of GetAnalyticsCount to the EasyAnalyticalRecords pref
- [[30976]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30976) Cover images for biblio should be displayed first
- [[31179]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31179) Duplicate item is duplicating internal item fields
- [[30716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30716) Add Collection column to cn_browser results table
- [[29958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29958) Missing dateaccessioned is set to today when storing an item
- [[30775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30775) 952w should have datepicker plugin enabled for it by default
- [[30871]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30871) Make it clear that 008 Type of Material is controlled by Leader 6th position in MARC21
- [[29963]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29963) Date accessioned plugin should not automatically fill today's date on cataloguing screens
- [[30797]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30797) Subfields linked to the dateaccessioned.pl value builder on addbiblio.pl throw a JS error
- [[30604]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30604) Add value builders for UNIMARC 146 ($a, $h and $i)
- [[30644]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30644) Cannot delete items
- [[30435]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30435) Remove unused MACLES cataloging plugin
- [[29781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29781) Allow item batch modification to use capturing groups in regex option
- [[29391]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29391) Improve output of reservoir search

## Circulation

- [[28553]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28553) Patrons can be set to receive auto_renew notices as SMS, but Koha does not generate them
- [[26626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26626) When checking in a hold that is not found the X option is 'ignore' and when hold is found it is 'cancel'
- [[29012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29012) Some rules are not saved when left blank while editing a 'rule' line in smart-rules.pl
- [[31120]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31120) Items will renew for zero ( 0 ) days if renewalperiod is blank/empty value
- [[30905]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30905) Show waiting recalls in patron account on checkouts tab
- [[30447]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30447) pendingreserves.pl is checking too many transfers
- [[31129]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31129) Number of restrictions is always "0" on the "Check out" tab
- [[29051]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29051) Seen renewal methods incorrectly blocked
- [[27996]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27996) Format of "Due date" on Circulation > Overdues page
- [[29050]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29050) Add punctuation in Unseen Renewals message
- [[31085]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31085) The return claims table no longer reloads on resolution
- [[31087]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31087) Undefined notes in returns claims get stringified to 'null'
- [[30924]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30924) Fix recalls-related errors in transfers and cancelling actions
- [[30971]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30971) Recalls - log viewer error
- [[30907]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30907) Remaining incorrect uses of Koha::Recall->item_level_recall
- [[30886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30886) Recall status cannot be correct on OPAC detail page
- [[30885]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30885) Recall - detail page explosion
- [[30735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30735) Filtering by patron attribute with AV does not work in overdues report
- [[30226]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30226) Add system preference to disable auto-renew checkbox at checkout
- [[19532]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19532) Recalls for Koha
- [[30104]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30104) Holds to pull is broken
- [[27946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27946) Add a charge per article request to patron categories

## Command-line Utilities

- [[31969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31969) Options for cleanup_database.pl to remove finished jobs from the background job queue
- [[31342]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31342) process_message_queue can run over the top of itself causing double-up emails
- [[31299]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31299) Duplicate output in search_for_data_inconsistencies.pl
- [[31239]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31239) search_for_data_inconsistencies.pl fails for Koha to MARC mapping using biblio table
- [[31356]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31356) Itiva outbound script doesn't respect calendar when calculating expiration date for holds
- [[31282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31282) Broken characters in patron_emailer.pl verbose mode
- [[31325]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31325) Fix koha-preferences get
- [[31155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31155) Document --since option in help of borrowers-force-messaging-defaults.pl
- [[30308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30308) bulkmarcimport.pl broken by OAI-PMH:AutoUpdateSets(EmbedItemData)
- [[30914]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30914) cleanup_database.pl --transfers --old-reserves --confirm does not work
- [[29325]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29325) commit_file.pl error 'Already in a transaction'
- [[30788]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30788) Argument "" isn't numeric in multiplication (*) at /usr/share/koha/lib/C4/Overdues.pm
- [[30776]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30776) import_webservice_batch.pl cronjob completely broken
- [[30666]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30666) Holds reminder cronjob (holds_reminder.pl) uses DateTime::subtract wrong
- [[30667]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30667) Holds reminder cronjob (holds_reminder.pl) never uses default letter template
- [[30520]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30520) Command line stage and import broken
- [[30511]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30511) Don't lock entire database when dumping Koha instance
- [[10517]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10517) koha-restore fails to create mysqluser@mysql_hostname so zebra update fails
- [[28962]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28962) Unverified self registrations should be removed shortly

## Database

- [[30483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30483) Do not allow NULL in issues.borrowernumber and issues.itemnumber
- [[30899]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30899) Upgrade sometimes fails at "Upgrade to 21.11.05.004"
- [[30912]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30912) Database update fails for 21.12.00.016 Bug 30060
- [[30852]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30852) article_requests missing index on debit_id
- [[30600]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30600) Recalls sync problem between DBIx and kohastructure.sql
- [[30620]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30620) Add a warning close to /*!VERSION lines in kohastructure.sql
- [[30572]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30572) Field search_marc_to_field.sort needs syncing too
- [[30449]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30449) Missing FK constraint on borrower_attribute_types
- [[30565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30565) Field stockrotationrotas.description should be NOT NULL, title UNIQUE
- [[30498]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30498) Enum search_field.type should contain year in kohastructure
- [[30481]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30481) Drop unique constraint deleteditemsstocknumberidx for deleteditems
- [[30128]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30128) language_subtag_registry.description is too short
- [[29605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29605) DB structure may not be synced with kohastructure.sql

## Documentation

- [[31465]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31465) Link system preference tabs to correct manual pages

## Fines and fees

- [[31513]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31513) NaN errors when using refund and payout with CurrencyFormat = FR
- [[31121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31121) Format date range on top of cashup summary page
- [[30458]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30458) Librarian ( manager_id ) not included in accountline when using "Payout amount" button
- [[31163]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31163) Sort cashup history so that newest entries are first
- [[31036]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31036) Cash management doesn't take SIP00 (Cash via SIP2) transactions into account
- [[30567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30567) Create manual invoice with FR currency format show the incorrect format
- [[30139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30139) Point of sale sets wrong 'Amount being paid' with CurrencyFormat = FR
- [[28138]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28138) Add system preference to make the payment type required
- [[29759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29759) Refund credit when cancelling an article request
- [[29457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29457) Fee Cancellation records the wrong manager_id

## Hold requests

- [[31518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31518) Hidden items count not displayed on hold request page
- [[31112]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31112) Able to renew checkout when the number of holds exceeds available number of items
- [[31355]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31355) Specific item holds table on OPAC only showing 10 items
- [[19540]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19540) opac-reserve does not correctly warn of too_much reserves
- [[30878]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30878) Canceling holds from 'Holds awaiting pickup' should not reset the selected tab
- [[31086]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31086) Do not allow hold requests with no branchcode
- [[30935]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30935) Holds to pull shows wrong first patron
- [[30960]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30960) Koha lets you place item-level holds without a pick-up place
- [[23659]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23659) Allow hold pickup location to default to item home branch for item-level holds
- [[30730]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30730) Holds to Pull should not list items with a notforloan status
- [[30710]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30710) Background tasks can be called multiple times on batch item deletion
- [[29346]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29346) Real-time holds queue update
- [[30693]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30693) Javascript broken on request.pl
- [[30577]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30577) Item specific holds location can be missed when placing title level holds
- [[30108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30108) Allow making hold dates required
- [[30395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30395) Internal server error at reserve/request.pl on a biblio with non-ISO formatted date in publicationyear
- [[29136]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29136) Patron search on request.pl has performance and display issues
- [[28782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28782) Get rid of custom query param list creation for request.pl
- [[30085]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30085) Improve performance of CanItemBeReserved
- [[29760]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29760) Show patron category in Holds queue
- [[29976]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29976) (Bug 21729 followup) fix holds unit tests
- [[29058]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29058) Add option to not load existing holds table automatically
- [[27868]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27868) Adding the Expiration Date to the Holds Awaiting Pickup report
- [[21729]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21729) When reverting a hold the expirationdate should be reset
- [[28377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28377) Use the API to suspend/resume holds

## I18N/L10N

- [[31292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31292) Untranslatable string in sample_notices.yaml
- [[30992]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30992) Hard to translate single word strings
- [[30028]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30028) Patron message delete confirmation untranslatable
- [[28707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28707) Missing strings in translation of sample data
- [[31068]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31068) Context for translation: Print (verb) vs. Print (noun)
- [[30991]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30991) [% ELSE %]0[% END %] will break translations if used for assigning variables
- [[30733]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30733) Simplify translatable strings
- [[30373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30373) Rewrite UNIMARC installer data to YAML
- [[30477]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30477) Add new UNIMARC installer translation files
- [[30476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30476) Remove NORMARC translation files
- [[26244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26244) Move translatable strings out of memberentrygen.tt and into JavaScript
- [[26257]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26257) Move translatable strings out of subscription-add.tt and into subscription-add.js
- [[29596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29596) Add Yiddish language

## ILL

- [[30890]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30890) ILL breadcrumbs are wrong

## Installation and upgrade (command-line installer)

- [[32110]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32110) Duplicated additional content entries on DBRev 210600016
- [[31673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31673) DB update of bug 31086 fails: Cannot change column 'branchcode': used in a foreign key constraint
- [[25622]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25622) Change way MySQL password is generated by koha-create
- [[30539]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30539) Koha upgrade error "Column 'claimed_on' cannot be null"

## Installation and upgrade (web-based installer)

- [[27619]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27619) Remove fr-FR installer data
- [[30276]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30276) Web-based installer failing on db upgrade for 30060

## Label/patron card printing

- [[31352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31352) Terminology: Borrower name
- [[31137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31137) Error editing label template
- [[30837]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30837) Fix table width on 'Print summary'

## Lists

- [[29114]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29114) Can not add barcodes with whitespaces at the beginning to the list
- [[26346]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26346) Add option to make a public list editable by library staff only
- [[28716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28716) Hide toolbar and opaccredits when printing lists

## MARC Authority data support

- [[29434]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29434) In UNIMARC instances, the authority finder uses MARC21 relationship codes
- [[29333]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29333) Importing UNIMARC authorities in MARCXML UTF-8 breaks the encoding
- [[29260]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29260) UNIMARC 210a is reported to Author (meeting/conference) when upgrading an authority through Z3950
- [[13412]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13412) Allow configuration of auto-created authorities
- [[20615]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20615) Add the link of number of times the authority are used in edit mode
- [[29990]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29990) Show authority heading use in search results
- [[11083]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11083) Authority search result display in staff interface should be XSLT driven
- [[29965]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29965) MARC preview for authority search results

## MARC Bibliographic data support

- [[31238]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31238) Unable to save authorised value to frameworks subfields
- [[29001]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29001) Subfields attributes are not preserved when order is changed in framework
- [[20362]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20362) Direct link to authority records missing in staff detail view (1xx, 7xx)

## MARC Bibliographic record staging/import

- [[26632]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26632) BatchStageMarcRecords passes a random number to AddBiblioToBatch / AddAuthToBatch
- [[31269]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31269) DataTables error when managing staged MARC records
- [[30789]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30789) Improve performance of AddBiblio when importing records with many items
- [[30738]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30738) Forked CGI MARC import warnings are not logged

## Notices

- [[29409]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29409) Update for bug 25333 can fail due to bad data or constraints
- [[31281]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31281) Overdue notices reply-to email address of a branch not respected
- [[26689]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26689) Monetary accounts notices should be definable at the credit_type/debit_type level
- [[30838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30838) to_address is misleading for SMS transports
- [[31122]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31122) Terminology: Replace & with and for Notices & slips
- [[30290]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30290) Article requests: Add TOC information to AR notices
- [[29943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29943) Fix typo in notices yaml file
- [[29491]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29491) Improve display of notices in patron details
- [[29557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29557) Auto renew notices should handle failed renewal due to patron expiration
- [[29586]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29586) "Hold reminder" notice doesn't show in messaging preferences in new installation

## OPAC

- [[31605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31605) Improve style of OPAC suggestions search form
- [[31527]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31527) Breadcrumbs for anonymous suggestions are not correct
- [[31531]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31531) Some modules loaded twice in opac-memberentry.pl
- [[31483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31483) Minor UI problem in opac-reset-password.pl
- [[30231]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30231) Don't display (rejected) forms of series entry in search results
- [[31387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31387) Marking othernames as required via PatronSelfRegistrationBorrowerMandatoryField does not display required label
- [[31217]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31217) Fix Coce JavaScript to hide single-pixel cover images in the OPAC lightbox gallery
- [[29782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29782) Additional contents: Fix handling records without title or content
- [[31294]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31294) Article requests: Mandatory subfields in OPAC don't show they are required
- [[31346]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31346) On the OPAC detail page some Syndetics links are wrong
- [[31272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31272) Show library name not code when placing item level holds in OPAC
- [[31186]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31186) Search result numbering in OPAC got suppressed
- [[29922]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29922) Group of libraries are now displayed in alphabetical order
- [[31069]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31069) Did you mean? in the OPAC - links have <span> tags
- [[31146]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31146) Minor UI problem in recalls history in OPAC
- [[30566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30566) Incorporate link handling in OPAC's biblio-title include
- [[31064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31064) Local login is difficult to style using CSS
- [[30918]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30918) Non-public note is visible in OPAC in Title Notes tab
- [[30689]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30689) Incorrect Babeltheque setting can cause console warning
- [[30688]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30688) Error in path to CSS background image
- [[30613]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30613) Hide RSS feed link when viewing private list in the OPAC
- [[29616]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29616) Replace library information popup in the OPAC with a modal
- [[14242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14242) Use ISBN-field to fill out purchase suggestions using Google Books API
- [[30550]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30550) OPAC recalls page tries to use jQueryUI datepicker
- [[30288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30288) Provide links to OPACUserJS and OPACUserCSS from News/HTML customizations
- [[30488]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30488) Error when placing a recall in the OPAC
- [[29066]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29066) Remove text in OPAC search form and use Font Awesome icons
- [[17018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17018) Split AdvancedSearchTypes for staff and OPAC
- [[30243]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30243) When OPACSuggestionMandatoryFields includes branchcode the dropdown should default to an empty value
- [[24221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24221) Convert OPACMySummaryNote system preference to news block
- [[29713]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29713) Make item table when placing an item level hold sortable
- [[15594]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15594) Sequence of  MARC 260 subfields different on XSLT result list and detail page
- [[30190]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30190) Green buttons turn blue for a second when clicking them
- [[27627]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27627) Fix invalid HTML in OPAC results XSLT: change spans to divs
- [[27613]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27613) Pipe separated contents are hard to customize (OPAC)
- [[29845]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29845) Styling OverDrive buttons is difficult
- [[30089]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30089) Placing holds on OPAC broken
- [[29603]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29603) Fix responsive behavior of facets menu in OPAC search results
- [[29960]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29960) Remove Modernizr dependency in the OPAC
- [[30101]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30101) OPAC advanced search page broken by Bug 29844
- [[29515]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29515) Don't require title for HTML customizations
- [[24630]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24630) UNIMARC XSLT Update for bug 7611
- [[29526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29526) Add 'Immediately delete holds history' button to patron privacy tab in opac
- [[29949]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29949) Remove use of title-numeric sorting routine from OPAC datatables JS
- [[24220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24220) Convert OpacMoreSearches system preference to news block
- [[29212]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29212) Use Flatpickr on OPAC pages
- [[29899]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29899) Show public note to patrons when placing a hold
- [[29778]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29778) Deleting additional_contents leaves entries for additional languages
- [[28876]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28876) No renewal before advisory text not wrapped in selector
- [[13188]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13188) Make it possible to configure mandatory patron data differently between OPAC registration and modification

## Packaging

- [[31348]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31348) Plack stop should be graceful
- [[31499]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31499) Add libhttp-tiny-perl 0.076 dependency for ES7
- [[30209]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30209) Upgrade 'libdbd-sqlite2-perl' package to 'libdbd-sqlite3-perl'

## Patrons

- [[31525]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31525) Street number not being accessed correctly on patron search results page
- [[31562]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31562) Patron 'flags' don't respect unwanted fields
- [[31497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31497) Quick add: mandatory fields save as empty when not filled in before first save attempt
- [[31516]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31516) Missing error handling for accessing deleted/non-existent club enrollment
- [[31486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31486) Deleting a message from checkouts tab redirects to detail tab in patron account
- [[31421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31421) Library limitation on patron category breaks patron search
- [[7660]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7660) Enhanced messaging preferences are not set when creating a child patron from the adult
- [[20439]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20439) SMS provider sorting
- [[31153]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31153) Search bar not visible on recalls history page
- [[30891]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30891) SMS provider shows on staff side even if SMS::Send driver is not set to "Email"
- [[30026]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30026) International phone number not supported for sending SMS
- [[30713]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30713) Patron entry should limit date of birth selection to dates in the past
- [[30603]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30603) Sort 1 and Sort 2 on patron form are on longer free text when AV categories are empty
- [[30611]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30611) Add ability to trigger a patron password reset from the staff client
- [[30607]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30607) Enable 'Clear filter' option on DataTables Search for patron searches
- [[30622]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30622) Search for cardnumber needs to go directly to patron record when placing a hold
- [[30563]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30563) Add system preference to make the cash register field required when collecting a payment
- [[30576]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30576) DefaultPatronSearchFields no longer takes effect
- [[30405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30405) Style of address in patron search result are 110%
- [[30237]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30237) Rename/rephrase AutoEmailOpacUser/ACCTDETAILS feature to clarify intended use
- [[9097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=9097) Add option to trigger 'Welcome mail' manually
- [[29005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29005) Add option to send WELCOME notice for new patrons added via patron imports
- [[30485]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30485) Searching all patrons from the header does not display the patron search view
- [[29059]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29059) Keep non-repeatable attribute from patron to preserve
- [[30120]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30120) Allow extended attributes during self registration when using PatronSelfRegistrationVerifyByEmail
- [[30063]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30063) Make the main patron search use the /patrons REST API route
- [[30404]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30404) Enlarge all patron searches pop-up
- [[30094]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30094) Rewrite the patron search when requesting an article with the REST API route
- [[30093]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30093) Rewrite the patron search when placing a hold with the REST API route
- [[30055]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30055) Rewrite some of the patron searches to make them use the REST API routes
- [[6815]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=6815) Capture member photo via webcam
- [[27812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27812) Remove the ability to transmit a patron's plain text password over email
- [[29525]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29525) Privacy settings for patrons should also affect holds history
- [[15156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15156) Get all Borrowers with pending/unpaid fines/accountlines

## Plugin architecture

- [[30180]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30180) Deprecate after_hold_create hook
- [[30410]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30410) Add a way for plugins to register background tasks
- [[30072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30072) Add more holds hooks

## Reports

- [[31276]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31276) Report results are limited to 999,999 no matter the actual number of results
- [[21982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21982) Circulation statistics wizard does not count deleted items
- [[27045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27045) Exports using CSV profiles with tab as separator don't work correctly
- [[29312]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29312) Punctuation: Total number of results: 961 (300 shown) .
- [[30532]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30532) guided_reports.pl has a problem
- [[29579]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29579) Show saved SQL report ID in database query
- [[29767]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29767) Add cash registers, debit and credit types to report runtime parameters
- [[5697]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=5697) Automatic linking in guided reports

## REST API

- [[29105]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29105) Add effective_item_type_id to the API items responses
- [[30780]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30780) Librarians with only "place_holds" permissions can not update holds data via REST API
- [[30923]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30923) OAuth2 implementation is not experimental
- [[30855]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30855) Rename /import => /import_batches
- [[30853]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30853) Missing description for 'baskets' in swagger.yaml
- [[30854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30854) Missing description for 'import_record_matches' in swagger.yaml
- [[30674]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30674) x-koha-override should use collectionFormat: csv
- [[30536]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30536) Embeds should be defined in a single place
- [[29810]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29810) Add embed options documentation
- [[30408]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30408) API and OpenAPI versions should be string in spec
- [[30194]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30194) Update required JSON::Validator version
- [[30074]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30074) Missing extended_attributes relationship in DBIC schema
- [[29975]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29975) (Bug 21729 followup) patron_expiration_date missing in API
- [[29772]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29772) Make DELETE /patrons/:patron_id return error codes in error conditions
- [[28020]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28020) Error responses should return a code

## Searching

- [[15187]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15187) Adding 880 Fields to index-list in order to Increase Search for ALL non-latin Scripts
- [[31213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31213) When performing a basic search with no results, repeat the search with term quoted
- [[30865]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30865) Koha::Biblio->get_components_query should double quote Host-item search
- [[30327]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30327) Sort component parts
- [[30740]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30740) Link to authorities 'used in' should not use equal
- [[27035]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27035) Shows the number of results in a facet after facet selection
- [[22605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22605) Adding the option to modify/edit searches on the staff interface
- [[20689]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20689) Improve usability of Item search fields administration page

## Searching - Elasticsearch

- [[25375]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25375) Elasticsearch: Limit on available items does not work
- [[31023]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31023) Cannot create new GENRE/FORM authorities when  QueryRegexEscapeOptions  set to 'Unescape escaped'
- [[31076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31076) Bug 22605 breaks date of publication range search
- [[27667]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27667) Display the number of non-indexed records
- [[30882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30882) Add max_result_window to index config
- [[29632]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29632) Callnumber sorting is incorrect in Elasticsearch
- [[30152]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30152) Elasticsearch - queries with OR don't work with limits
- [[25669]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25669) ElasticSearch 6: [types removal] Specifying types in put mapping requests is deprecated (incompatible with 7)
- [[25616]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25616) Uppercase hard coded lower case boolean operators for Elasticsearch
- [[27770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27770) ES: Deprecated aggregation order key [_term] used, replaced by [_key]
- [[29856]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29856) Make the ES config more flexible

## Searching - Zebra

- [[30879]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30879) Add option to sort components by biblionumber
- [[31106]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31106) Error searching for analytics in detail view

## Self checkout

- [[31488]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31488) Rephrase "You have checked out too many items" to be friendlier

## Serials

- [[29608]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29608) Editing numbering patterns does require full serials permission
- [[30039]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30039) Add publication date column to serial claims table
- [[26377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26377) Clearly label parts of subscription-add.pl that relate to optional item records
- [[24010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24010) Number of issues to display to staff accepts non-integer values
- [[29055]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29055) Focus on keyword field when subscription biblio search window opens
- [[30973]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30973) Serials search wrong body id
- [[23352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23352) Define serial's collection in the subscription
- [[30205]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30205) Add biblio.subtitle to the subscription-detail.pl page
- [[29815]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29815) Pre-populate 'Date acquired' field when adding/editing items
- [[6734]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=6734) Show location in full and brief subscription history in OPAC

## SIP2

- [[31236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31236) Add ability to send custom item fields via SIP using Template Toolkit
- [[31296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31296) Add ability to disable demagnetizing items via SIP2 based on itemtypes
- [[31033]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31033) SIP2 configuration does not correctly handle multiple simultaneous connections by default
- [[12225]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12225) SIP does not respect the "no block" flag
- [[31202]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31202) Koha removes optional SIP fields with a value of "0"
- [[29094]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29094) Placing holds via SIP2 does not check if a patron can hold the given item
- [[29755]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29755) SIP2 code does not correctly handle NoIssuesChargeGuarantees  or  NoIssuesChargeGuarantorsWithGuarantees
- [[29936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29936) Add ability to disable hold capture via SIP checkin
- [[26370]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26370) Add ability to disable demagnetizing items via SIP2 based on patron categories
- [[25815]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25815) SIP Checkout: add more information on why the patron is blocked
- [[20517]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20517) Use the "sort bin" field in SIP2 Checkin Response
- [[29874]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29874) Remove unused method C4::SIP::ILS::Item::fill_reserve

## Staff interface

- [[32172]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32172) Random biblionumber passed when clicking 'Z3950  SRU/Search' from the search results in staff client
- [[32122]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32122) Wrong permissions check on item circulation alerts
- [[31565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31565) Patron search filter by category code with special character returns no results
- [[28864]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28864) The patron search results in the patron card creator doesn't seem to use PatronsPerPage syspref
- [[30499]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30499) Keyboard shortcuts broken on several pages
- [[31251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31251) "Clear" patron attribute link does not work
- [[31244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31244) Logout when not logged in raise a 500
- [[31138]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31138) DataTables is not raising error to the end user
- [[30471]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30471) Typo in circulation rules - lost item fee refund policy
- [[31039]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31039) Rebase issues lead to duplicate JS for cash summary modal printing
- [[31038]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31038) Amounts in cashup summary modal no longer properly formatted
- [[31067]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31067) Sub-tools permission not applying on intranet-main.tt
- [[30798]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30798) Columns Home library and Checked out from in wrong order on table settings for account_fines table
- [[30747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30747) Column settings on otherholdings table in detail.tt doesnt work
- [[29092]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29092) Table settings for account_fines table is missing Updated on column and hides the wrong things
- [[27631]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27631) Accessibility: Staff interface - `h1` on each page is Logo but should be page description/title
- [[20398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20398) Add a system preference to disable search result highlighting in the staff interface
- [[21225]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21225) Add Syndetics cover images to staff client
- [[30425]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30425) April fools!
- [[17748]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17748) Show due date in item search results
- [[30081]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30081) Display item type in patron's holds table
- [[29541]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29541) Patron images can be accessed with just 'catalogue' permission
- [[29575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29575) Add a JS render function equivalent of the patron-title.inc TT include

## System Administration

- [[31995]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31995) build_holds_queue.pl should check to see if the RealTime syspref is on
- [[30462]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30462) Improve the default display for the background jobs queue management page
- [[31401]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31401) Update administration sidebar to match entries on administration start page
- [[31364]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31364) Saving multi-select system preference don't save when all checks are removed
- [[31489]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31489) Typo in EnableExpiredPasswordReset description
- [[31289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31289) Hide article requests column in circulation rules when ArticleRequests syspref is disabled
- [[31249]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31249) update_patrons_category.pl cron does not log to action_logs
- [[31020]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31020) PassItemMarcToXSLT only applies on results pages
- [[29951]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29951) Cannot add splitting rule to classification sources
- [[31117]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31117) Cloning standard circulation rules for all libraries show up as from '*'
- [[30585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30585) Table settings for course_reserves_table are wrong due to lack of "Holding library" option
- [[27519]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27519) Normalize Show/Don't show vs Display/Don't display in system preferences
- [[30864]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30864) Patron category form - no validation for password expiration field
- [[13952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13952) Import and export of authority types
- [[29634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29634) Map biblio.medium to 245$h by default (MARC21)
- [[29626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29626) Map biblioitems.place to 264$a by default (MARC21)
- [[29627]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29627) Map biblioitems.publishercode to 264$b by default (MARC21)
- [[29832]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29832) Make library column in desk list sortable
- [[7374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7374) Add remote image option for authorized values

## Templates

- [[31558]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31558) Upgrade of TinyMCE broke image drag and drop
- [[31530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31530) HTML tags in TT comments in patron-search.inc
- [[31542]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31542) Home page links wrong font-family
- [[31379]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31379) Change results per page text for default
- [[31425]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31425) Minor correction to patron categories admin title
- [[31228]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31228) Fix Coce JavaScript to hide single-pixel cover images in both the staff client detail and results pages
- [[31302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31302) Spelling: You can download the scanned materials via the following url(s):
- [[31246]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31246) <span> displayed in 'Additional fields' section
- [[30570]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30570) Replace the use of jQueryUI tabs in OPAC templates
- [[31141]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31141) We can remove 'select_column' from waiting_holds.inc
- [[31071]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31071) Regression: date due removed from staff search results
- [[30767]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30767) Terminology: Do not forget that the issue has not been checked in yet.
- [[30766]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30766) Typo: Cannot cancel receipt. Possible reasons :
- [[30762]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30762) Terminology: Go to Staff client
- [[30763]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30763) Typo: Barcode proceeds bibliographic data
- [[30784]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30784) Rephrase OPACMandatoryHoldDates slightly
- [[30770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30770) Terminology: Lost reserve
- [[30764]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30764) Terminology: Cancelled reserve
- [[30773]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30773) Standardize spelling i-tive / Itiva
- [[30769]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30769) Typo: Item typeX:
- [[30990]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30990) Terminology: DefaultHoldPickupLocation
- [[31040]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31040) jsTree image being used outside of jsTree plugin
- [[26486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26486) Group edit buttons in reports toolbar
- [[30994]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30994) Typo: item was on loan. couldn't be returned.
- [[30936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30936) Reindent authority detail template in staff interface
- [[30609]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30609) Reindent serial claims template
- [[20395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20395) Use Price formatter in more templates (paycollect, request, parcel, smart-rules)
- [[30768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30768) Typo: pin should be PIN
- [[30807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30807) Use patron-title.inc in patron payments pages
- [[30806]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30806) Use patron-title.inc in member-flags template
- [[30629]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30629) <span> in title of patron card creator template needs to be removed
- [[30774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30774) Typo: i %sEdit %sReserve %s
- [[30772]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30772) Terminology: Replace instances of "reserve" with "hold"
- [[30761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30761) Typo: PLease
- [[30640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30640) Focus does not always move to correct search header form field
- [[30695]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30695) Checkouts and holds count display in tab could be better in patron details
- [[30720]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30720) Batch delete links from result list missing permission checks
- [[30422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30422) Authorities editor update broke the feature added by Bug 20154
- [[13142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13142) Change "mobile phone" label back to "other phone"
- [[30722]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30722) Typo in overdue recalls template
- [[30706]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30706) DateFormat change only takes effect after a restart of services
- [[30514]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30514) Error in date format check following datepicker removal
- [[27470]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27470) Improve link text for logging in
- [[30475]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30475) Convert tools pages tabs to Bootstrap (part 2)
- [[30474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30474) Convert tools pages tabs to Bootstrap (part 1)
- [[30473]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30473) Convert suggestions page tabs to Bootstrap
- [[30549]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30549) Replace the use of jQueryUI Accordion on pending patron updates page
- [[30632]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30632) Fix report author display in list of saved reports
- [[30466]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30466) Convert serials pages tabs to Bootstrap
- [[30436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30436) Convert article requests tabs to Bootstrap
- [[27750]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27750) Remove jquery.cookie.js plugin
- [[30433]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30433) Convert advanced search tabs to Bootstrap
- [[30424]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30424) Reindent advanced search template in the staff interface
- [[30545]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30545) Replace the use of jQueryUI Accordion on the notices page
- [[30494]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30494) Replace the use of jQueryUI Accordion on the table settings page
- [[30491]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30491) Convert saved reports tabs to Bootstrap
- [[30489]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30489) Convert MARC and authority subfield edit tabs to Bootstrap
- [[30457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30457) Convert holds page tabs to Bootstrap
- [[30454]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30454) Convert holds awaiting pickup tabs to Bootstrap
- [[30453]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30453) Convert offline circulation tabs to Bootstrap
- [[30434]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30434) Convert catalog merge page tabs to Bootstrap
- [[30136]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30136) Add back to top button when scrolling
- [[29648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29648) Make KohaTable tables 'default length' and 'default sort' configurable
- [[30512]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30512) Staff interface search results template error
- [[29602]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29602) We must be nicer with translators
- [[30223]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30223) Move book cover image upload JS to a separate file
- [[30417]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30417) Switch to Bootstrap tabs on the basic library transfer limit page
- [[30456]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30456) Convert checkout history tabs to Bootstrap
- [[30423]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30423) Convert authority merge page tabs to Bootstrap
- [[30419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30419) Convert authority detail page tabs to Bootstrap
- [[30401]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30401) Convert budgets administration page tabs to Bootstrap
- [[30400]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30400) Convert invoices page tabs to Bootstrap
- [[30398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30398) Reindent invoices template
- [[30396]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30396) Convert basket groups page tabs to Bootstrap
- [[30378]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30378) Convert about page tabs to Bootstrap
- [[30011]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30011) Upgrade jQueryUI to 1.13.1 in the OPAC and staff interface
- [[29228]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29228) Use Flatpickr on offline circulation page
- [[30227]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30227) Replace the use of jQueryUI tabs on bibliographic detail page
- [[30317]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30317) Replace the use of jQueryUI tabs on search history page
- [[30316]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30316) Replace the use of jQueryUI tabs on MARC detail page
- [[29998]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29998) Replace the use of jQueryUI tabs on item types administration page
- [[29999]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29999) Replace the use of jQueryUI tabs on authorized values administration page
- [[24415]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24415) Authority enhancement - Improve access to tabs
- [[30000]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30000) Replace the use of jQueryUI tabs on the search engine configuration page
- [[25025]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25025) Drag-and-drop cover image upload
- [[26975]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26975) Reindent authorities editor template
- [[29876]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29876) Style report id in report results heading
- [[28405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28405) Add author info to the holds page in the staff interface
- [[29458]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29458) Show login button consistently in relation to login instructions, reset and register links
- [[29277]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29277) Replace the use of jQueryUI tabs on item circulation alerts page
- [[29867]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29867) Reindent authorized values administration template
- [[28993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28993) Switch magnifying glass in staff detail pages to FA icon
- [[11873]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11873) Upgrade jstree jQuery plugin to the latest version
- [[29289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29289) 'Show fines to guarantor' should have its own id on patron detail page
- [[29529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29529) Fix \n in hint on Koha to MARC mappings
- [[29406]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29406) Improve display of OPAC suppression message

## Test Suite

- [[31598]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31598) Fix random failure on Jenkins for t/db_dependent/Upload.t
- [[31201]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31201) Pseudonymization.t failing if selenium/patrons_search.t failed before
- [[31139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31139) basic_workflow.t is failing
- [[31108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31108) rename ./t/00-check-atomic-updates.pl extension to *.t
- [[30734]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30734) t/db_dependent/Koha/BackgroundJob.t fails on D9 and D10
- [[29705]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29705) Test suite has some IssuingRules left-overs
- [[30596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30596) api/v1/acquisitions_baskets.t is failing randomly
- [[30446]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30446) Add a test for GetTagsLabels
- [[30125]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30125) Add full-stack tests for API pagination

## Tools

- [[31482]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31482) Label creator does not call barcodedecode
- [[31564]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31564) Pass start label when exporting single label as PDF
- [[31154]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31154) Batch item modification fails when "Use default values" is checked
- [[28290]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28290) Record matching rules with no subfields cause ISE
- [[28327]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28327) System preference CSVdelimiter special case for tabulation
- [[30779]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30779) Do not need to remove items from import biblios marc
- [[31455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31455) Batch modification tool orders found items by itemnumber
- [[31204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31204) Edit dropdown on results.tt should indicate it is record modification
- [[31220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31220) Error when attempting to export selected labels as PDF
- [[30911]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30911) Datatables error on course-details.pl after adding a bib-level course reserve
- [[30903]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30903) CSV import of quotes broken
- [[31066]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31066) Can't use regex in batch modification on fields associated with a plugin
- [[31062]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31062) Change description of QOTD tool in tools-home
- [[30889]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30889) Background jobs lead to wrong/missing info in logs
- [[22659]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22659) Add 'save and continue' functionality to news and HTML customizations
- [[30904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30904) (bug 24387 follow-up) Modifying library in news (additional contents) causes inconsistencies
- [[30778]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30778) ModBiblioInBatch is not used and can be removed
- [[30972]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30972) "Replace existing covers" checkbox replaces ALL local covers for a biblio, not only the specific item's covers
- [[30701]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30701) On small screens, upload tool buttons cannot be clicked
- [[29719]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29719) onloan dates are cleared from items when importing and overlaying
- [[30709]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30709) 'Insert' button in notices editor not adding selected placeholders to notice
- [[29698]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29698) items are not available for TT syntax for PREDUEDGST
- [[22785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22785) Manage matches when importing through stage MARC record import
- [[28840]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28840) Better texts in batch record modification/deletion
- [[29946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29946) Sort profiles alphabetically when  staging MARC records for import
- [[14393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14393) Add collection code filter to inventory
- [[29821]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29821) Add interface for generating barcodes using svc/barcode
- [[22827]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22827) Automatic item modifications by age: add age depencency on other field(s) than dateaccessioned
- [[29824]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29824) Allow for quick spine labels to be editable for printing
- [[23873]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23873) Allow marc modification templates to use capturing groups in substitutions
- [[27904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27904) Improve display in creating profile for staging MARC records for import
- [[20076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20076) Overdues email to library for patrons without email should be optional

## Web services

- [[22347]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22347) Translatability of ILSDI results for getavaibility
- [[20894]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20894) Add barcode size parameters to /svc/barcode


