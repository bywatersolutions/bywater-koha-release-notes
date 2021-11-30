
# Release Notes for bluehill-v21.05.07-01

## About

- [[29123]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29123) Add Dataly Tech to About page
- [[28904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28904) Update information on Newsletter editor on about page
- [[29300]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29300) Release team 22.05

## Acquisitions

- [[28627]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28627) Revert the order receive page to display 'Actual cost' as ecost_tax_included/ecost_tax_excluded if unitprice not set
- [[27708]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27708) Cannot create EDI order if AcqCreateItem value is not "placing an order"
- [[29283]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29283) Cannot delete basket with cancelled order for deleted biblio
- [[14999]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14999) Adding to basket orders from staged files mixes up the prices between different orders

## Architecture, internals, and plumbing

- [[27032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27032) CanBookBeRenewed is not understandable and needs refactoring
- [[29330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29330) Koha cannot send emails with attachments using Koha::Email and message_queue table
- [[29408]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29408) The datatables api wrapper is ambiguously named
- [[29321]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29321) Remove a last without loop context
- [[29386]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29386) background jobs table data field is a TEXT which is too small
- [[29350]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29350) TT method 'delete' don't need to be escaped
- [[29218]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29218) "hidden" class is not working for DT if column visibility button is used
- [[26374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26374) Update for 19974 is not idempotent

## Bywater Only

- NOT IN BUGZILLA - Revert "BWS-PKG - GitHub Actions - Install Email::Valid"
- NOT IN BUGZILLA - GitHub Actions - Install Email::Valid
- NOT IN BUGZILLA - Fix translations for Koha 21.05.06
- NOT IN BUGZILLA - DBRev 21.05.05.004

## Cataloging

- [[29437]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29437) 500 error when performing a catalog search for an ISBN13 with no valid ISBN10
- [[29319]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29319) Errors when doing a cataloging search which starts with a number + letter

## Circulation

- [[29255]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29255) Built-in offline circulation broken with SQL error

## Command-line Utilities

- [[28994]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28994) Make writeoff_debts.pl use amountoutstanding, not amount

## Fines and fees

- [[29309]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29309) 'Pay all fines' should be 'Pay all charges'

## Hold requests

- [[29474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29474) Automatic renewals cronjob is slow on systems with large numbers of reserves

## Label/patron card printing

- [[25459]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25459) In patron cards layout, barcode position doesn't respect units

## Notices

- [[28803]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28803) process_message_queue.pl dies if any messsages in the message queue contain an invalid to_address
- [[29460]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29460) Typo 'pendin    g approval'

## OPAC

- [[28870]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28870) Cart shipping fails because of Non-ASCII characters in display-name of reply-to address
- [[29416]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29416) Regression: information from existing bib no longer populating on suggest for purchase
- [[28768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28768) OPAC reading history page (opac-readingrecord.pl) wont display news items
- [[29329]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29329) stray "s" in opac-detail
- [[28901]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28901) showCart incorrectly calculates position if content above navbar
- [[28910]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28910) Correct eslint errors in OPAC basket.js
- [[29318]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29318) OverDrive search page should not require edit_borrowers permission

## Patrons

- [[29524]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29524) Cannot set a new value for privacy_guarantor_checkouts in memberentry.pl
- [[29341]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29341) If OpacRenewalBranch = opacrenew, pseudonymization process leads to "internal server error" when patrons renew the loans at OPAC
- [[27145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27145) Patron deletion via intranet doesn't handle exceptions well
- [[28973]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28973) Improve Koha::Patron::can_see_patron_infos efficiency
- [[29227]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29227) Patron messaging preferences digest show as editable but are not
- [[29213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29213) Typo ol in member-alt-contact-style.inc

## Plugin architecture

- [[27173]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27173) Add plugin hooks for authority record changes
- [[28474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28474) Pass process_message_queue.pl params to before_send_messages plugin hooks

## Reports

- [[29204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29204) Error 500 when execute Circulation report with date period
- [[27884]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27884) Add HTML mail support for patron emailer script
- [[29352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29352) Runtime parameter labels should not be said to be optional
- [[29328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29328) Add missing list parameter to reports parameter menu

## REST API

- [[29405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29405) The patron spec for date_renewed is missing it's format definition
- [[17314]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17314) Routes to create, list and delete a purchase suggestion
- [[28613]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28613) Several objects.search-based routes missing parameters
- [[29272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29272) API not respecting $category->effective_change_password
- [[28585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28585) Cannot search on date fields

## Searching

- [[28847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28847) Branch limits while searching should be expanded in query building and not in CGI
- [[28365]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28365) (Bug 19873 follow-up) Make it possible to search on value 0

## Searching - Elasticsearch

- [[29284]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29284) Koha dies when an analytics search fails in Elasticsearch

## SIP2

- [[29564]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29564) Use List::MoreUtils so SIP U16/Xenial does not break
- [[29452]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29452) Unnecessary warns in sip logs
- [[29264]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29264) SIP config allows use of non-branchcode institution ids causes workers to die without responding
- [[26871]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26871) L1 cache still too long in SIP Server

## Staff Client

- [[29195]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29195) Highlighting broken on odd rows in circ-patron-search-results
- [[28913]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28913) Automatic checkin setting in item type setup should note required cronjob
- [[28573]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28573) Replace authority record with Z39.50/SRU creates new authority record

## System Administration

- [[29456]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29456) "Auto renewal" and "Hold reminder" notice shown as "unknown" on the patron category list view
- [[28729]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28729) Return-path header not set in emails
- [[29075]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29075) OPAC info should not be displayed in libraries table

## Templates

- [[29286]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29286) Typo: Librarien will need the manage_auth_values subpermission.

## Test Suite

- [[29485]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29485) selenium/administration_tasks.t is failing randomly
- [[29364]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29364) Search.t not reverting changes made to the framework
- [[29363]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29363) TestBuilder.t failing if biblionumber=123 does not exist
- [[29315]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29315) Remove warnings from Search.t
- [[29306]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29306) Holds.t: Fix Use of uninitialized value $_ in concatenation (.) or string

## Web services

- [[21105]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21105) oai.pl returns invalid earliestDatestamp


