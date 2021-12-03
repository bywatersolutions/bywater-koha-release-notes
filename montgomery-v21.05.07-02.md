
# Release Notes for montgomery-v21.05.07-02

## About

- [[29123]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29123) Add Dataly Tech to About page
- [[28904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28904) Update information on Newsletter editor on about page
- [[29300]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29300) Release team 22.05

## Acquisitions

- [[28627]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28627) Revert the order receive page to display 'Actual cost' as ecost_tax_included/ecost_tax_excluded if unitprice not set
- [[27708]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27708) Cannot create EDI order if AcqCreateItem value is not "placing an order"
- [[29283]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29283) Cannot delete basket with cancelled order for deleted biblio
- [[14999]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14999) Adding to basket orders from staged files mixes up the prices between different orders
- [[28956]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28956) Acquisitions: select correct default tax rate when receiving orders
- [[28960]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28960) EDI transfer_items uses a relationship where it's looking for a field
- [[28946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28946) 500 error when choosing patron for purchase suggestion

## Architecture, internals, and plumbing

- [[27032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27032) CanBookBeRenewed is not understandable and needs refactoring
- [[29420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29420) HTTP status code incorrect when calling error pages directly under Plack/PSGI
- [[25333]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25333) Change message transport type for Talking Tech from "phone" to "itiva"
- [[29330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29330) Koha cannot send emails with attachments using Koha::Email and message_queue table
- [[29408]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29408) The datatables api wrapper is ambiguously named
- [[29321]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29321) Remove a last without loop context
- [[29386]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29386) background jobs table data field is a TEXT which is too small
- [[29350]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29350) TT method 'delete' don't need to be escaped
- [[29218]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29218) "hidden" class is not working for DT if column visibility button is used
- [[26374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26374) Update for 19974 is not idempotent
- [[29134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29134) Patron search has poor performance when ExtendedAttributes enabled and many attributes match
- [[29243]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29243) PrepareItemrecordDisplay should not be called with empty string in defaultvalues
- [[29135]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29135) OAI should not include biblionumbers from deleteditems when determining deletedbiblios
- [[29175]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29175) finishreceive: Replace , by ;
- [[29139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29139) Paying gives ISE if UseEmailReceipts is enabled
- [[28373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28373) Items fields not used in default XSLT
- [[28992]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28992) Resolve warning from undefined BIG_LOOP

## Authentication

- [[28914]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28914) Wrong wording in authentication forms

## Bywater Only

- NOT IN BUGZILLA - Revert "BWS-PKG - GitHub Actions - Install Email::Valid"
- NOT IN BUGZILLA - GitHub Actions - Install Email::Valid
- NOT IN BUGZILLA - Fix translations for Koha 21.05.06
- NOT IN BUGZILLA - DBRev 21.05.05.004
- NOT IN BUGZILLA - Fix translations for Koha 21.05.05

## Cataloging

- [[29437]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29437) 500 error when performing a catalog search for an ISBN13 with no valid ISBN10
- [[29319]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29319) Errors when doing a cataloging search which starts with a number + letter
- [[29137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29137) Unwanted authorised values are too easily created via the cataloging module
- [[27461]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27461) Fix field 008 length below 40 positions in cataloguing plugin
- [[28829]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28829) Useless single quote escaping in value_builder/unimarc_field_4XX.pl
- [[28676]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28676) AutoCreateAuthorities can repeatedly generate authority records when using Default linker and heading is cached

## Circulation

- [[29411]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29411) Single result for checkout search by name should redirect to check out tab
- [[15812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15812) Checkout search with too many results (single character search)  causes poor performance or timeout
- [[29234]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29234) Transfers generated by stock rotation alert but do not initiate at checkin
- [[29255]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29255) Built-in offline circulation broken with SQL error
- [[29026]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29026) Behavior change when an empty barcode field is submitted in circulation
- [[28653]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28653) Sorting loans by due date doesn't work after renewing
- [[28985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28985) Negative rental amounts can be saved but not enforced
- [[21093]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21093) Specified due date incorrectly retained when using fast add

## Command-line Utilities

- [[28994]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28994) Make writeoff_debts.pl use amountoutstanding, not amount
- [[29216]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29216) Correct --where documentation in update_patrons_category.pl
- [[28352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28352) Errors in search_for_data_inconsistencies.pl relating to authorised values and frameworks
- [[29078]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29078) Division by zero in touch_all scripts
- [[29076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29076) cleanup_database.pl dies of passed zebraqueue and not confirm

## Custom For Instance

- [[29483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29483) AllowRenewalIfOtherItemsAvailable has poor performance for records with many items
- [[29474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29474) Automatic renewals cronjob is slow on systems with large numbers of reserves
- [[29057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29057) Use font awesome icons on request.pl
- [[29130]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29130) Holds queue is empty while holds queue builder is running

## Fines and fees

- [[29309]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29309) 'Pay all fines' should be 'Pay all charges'

## Hold requests

- [[28510]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28510) Skip processing holds queue items from closed libraries when HoldsQueueSkipClosed is enabled
- [[29049]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29049) Holds page shows too many priority options in pulldown
- [[29073]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29073) Hold expiration added to new holds when DefaultHoldExpirationdate turned off

## Label/patron card printing

- [[25459]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25459) In patron cards layout, barcode position doesn't respect units
- [[28940]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28940) IntranetUserJS is called twice on spinelable-print.tt

## MARC Authority data support

- [[24698]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24698) UNIMARC authorities leader plugin

## Notices

- [[28803]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28803) process_message_queue.pl dies if any messsages in the message queue contain an invalid to_address
- [[29460]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29460) Typo 'pendin    g approval'
- [[29223]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29223) Auto-renewals can fail when not digested per branch and patron requests digest

## OPAC

- [[28870]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28870) Cart shipping fails because of Non-ASCII characters in display-name of reply-to address
- [[29416]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29416) Regression: information from existing bib no longer populating on suggest for purchase
- [[28768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28768) OPAC reading history page (opac-readingrecord.pl) wont display news items
- [[29329]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29329) stray "s" in opac-detail
- [[28901]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28901) showCart incorrectly calculates position if content above navbar
- [[28910]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28910) Correct eslint errors in OPAC basket.js
- [[29318]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29318) OverDrive search page should not require edit_borrowers permission
- [[20277]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20277) Link to host item doesn't work in analytical records if 773$a is present
- [[29172]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29172) Can't use controlfields with CustomCoverImagesURL
- [[28930]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28930) Cardnumber is lost if an invalid self registration form is submitted to the server, and the server side form validation fails
- [[29128]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29128) Trailing whitespace in Browse shelf link on opac-detail.tt
- [[29091]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29091) Correct display of lists and tags on search results
- [[29067]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29067) Remove duplicate conditional statement from OPAC messaging settings title
- [[28934]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28934) OPAC registration form design is not consistent
- [[29064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29064) OPAC duplicate "Most popular titles" in 'title' tag
- [[29070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29070) Accessibility: OPAC Purchase Suggestions on search results page has insufficient contrast
- [[29068]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29068) Accessibility: OPAC search results summary text has insufficient contrast
- [[29065]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29065) Accessibility: OPAC clear search history link has insufficient contrast
- [[29038]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29038) Accessibility: OPACUserSummary heading doesn't have sufficient contrast
- [[29037]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29037) Accessibility: OPAC links don't have sufficient contrast
- [[29035]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29035) Accessibility: OPAC masthead_search label doesn't have sufficient contrast ratio
- [[29034]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29034) Accessibility: OPAC nav-links don't have sufficient contrast ratio
- [[28845]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28845) OpacAddMastheadLibraryPulldown does not respect multibranchlimit in OPAC_SEARCH_LIMIT

## Patrons

- [[29524]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29524) Cannot set a new value for privacy_guarantor_checkouts in memberentry.pl
- [[29341]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29341) If OpacRenewalBranch = opacrenew, pseudonymization process leads to "internal server error" when patrons renew the loans at OPAC
- [[27145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27145) Patron deletion via intranet doesn't handle exceptions well
- [[29227]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29227) Patron messaging preferences digest show as editable but are not
- [[29213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29213) Typo ol in member-alt-contact-style.inc
- [[29215]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29215) In patron form collapsing "Patron guarantor" display errors
- [[29025]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29025) Saved auth login and password are pre-filled in patron creation form
- [[18747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18747) Select All in Add Patron Option in Patron Lists only selects the first 20 entries

## Plugin architecture

- [[29121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29121) Plugins with broken ->install prevent access to the plugins list
- [[27173]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27173) Add plugin hooks for authority record changes
- [[28474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28474) Pass process_message_queue.pl params to before_send_messages plugin hooks
- [[28303]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28303) Having multiple pluginsdir causes plugin_upload to try to write to the opac-tmpl folder
- [[28228]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28228) Warns from plugins when metadata value not defined for key

## Reports

- [[29204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29204) Error 500 when execute Circulation report with date period
- [[27884]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27884) Add HTML mail support for patron emailer script
- [[29352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29352) Runtime parameter labels should not be said to be optional
- [[29328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29328) Add missing list parameter to reports parameter menu
- [[29271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29271) Cash register report not displaying or exporting correctly
- [[29225]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29225) Report subgroup does not appear consistently
- [[29279]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29279) Holds ratio report not sorting correctly

## REST API

- [[29405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29405) The patron spec for date_renewed is missing it's format definition
- [[17314]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17314) Routes to create, list and delete a purchase suggestion
- [[28613]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28613) Several objects.search-based routes missing parameters
- [[29272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29272) API not respecting $category->effective_change_password
- [[28585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28585) Cannot search on date fields
- [[29157]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29157) Cannot set date/date-time attributes to NULL
- [[29072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29072) Move reference route /cities spec to YAML

## Searching

- [[28847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28847) Branch limits while searching should be expanded in query building and not in CGI
- [[28365]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28365) (Bug 19873 follow-up) Make it possible to search on value 0
- [[28826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28826) Facet sort order differs between search engines

## Searching - Elasticsearch

- [[29284]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29284) Koha dies when an analytics search fails in Elasticsearch
- [[25030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25030) IncludeSeeFromInSearches not honoured in Elasticsearch
- [[28484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28484) Elasticsearch fails to parse query if exclamation point is in 245$a
- [[28316]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28316) Fix ES crashes related to various punctuation characters

## SIP2

- [[29564]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29564) Use List::MoreUtils so SIP U16/Xenial does not break
- [[29452]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29452) Unnecessary warns in sip logs
- [[29264]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29264) SIP config allows use of non-branchcode institution ids causes workers to die without responding
- [[26871]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26871) L1 cache still too long in SIP Server
- [[28464]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28464) Cancelling a waiting hold via SIP returns a failed response even when cancellation succeeds

## Staff Client

- [[29195]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29195) Highlighting broken on odd rows in circ-patron-search-results
- [[28913]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28913) Automatic checkin setting in item type setup should note required cronjob
- [[28573]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28573) Replace authority record with Z39.50/SRU creates new authority record
- [[29244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29244) alert/error and message dialogues should have the same width
- [[29193]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29193) DataTables only showing 20 results on checkout search and patrons search on request.pl
- [[29131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29131) Row striping breaks color coding on item circulation alerts
- [[29062]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29062) Patron check-in slip repeats data
- [[28472]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28472) UpdateItemLocationOnCheckin not updating items where location is null
- [[28986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28986) Parent itemtype not selected when editing circ rules

## System Administration

- [[29456]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29456) "Auto renewal" and "Hold reminder" notice shown as "unknown" on the patron category list view
- [[28729]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28729) Return-path header not set in emails
- [[29075]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29075) OPAC info should not be displayed in libraries table
- [[29298]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29298) "Managing library" missing from histsearch table settings
- [[29004]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29004) Update GoogleOpenIDConnect preference to make it clear that it is OPAC-only
- [[29056]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29056) Remove demo functionality remnants

## Templates

- [[29286]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29286) Typo: Librarien will need the manage_auth_values subpermission.
- [[28579]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28579) Typo: No record have been imported because they all match an existing record in your catalog.
- [[28470]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28470) Typo: Are you sure you with to chart this report?
- [[29133]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29133) Wrong string format in select2.inc
- [[28438]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28438) Capitalization: Various corrections
- [[28927]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28927) Id opacmainuserblock used twice in OPAC

## Test Suite

- [[29485]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29485) selenium/administration_tasks.t is failing randomly
- [[29364]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29364) Search.t not reverting changes made to the framework
- [[29363]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29363) TestBuilder.t failing if biblionumber=123 does not exist
- [[29315]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29315) Remove warnings from Search.t
- [[29306]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29306) Holds.t: Fix Use of uninitialized value $_ in concatenation (.) or string
- [[27155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27155) Include identifier test in Biblio_and_Items_plugin_hooks.t

## Web services

- [[21105]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21105) oai.pl returns invalid earliestDatestamp


