
# Release Notes for montgomery-v24.05.04-02

## About

- [[37575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37575) Typo 'AutoCreateAuthorites' in about.pl

## Accessibility

- [[37586]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37586) Improve accessibility of top navigation in the OPAC with aria-labels

## Acquisitions

- [[37450]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37450) Clicking 'Close basket' from the list of baskets does nothing
- [[37337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37337) Submitting a similar suggestion results in a blank page
- [[37411]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37411) Exporting budget planning gives 500 error
- [[37340]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37340) EDIFACT messages should be sortable by 'details'

## Architecture, internals, and plumbing

- [[36474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36474) updatetotalissues.pl  should not modify the record when the total issues has not changed
- [[37510]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37510) Koha::Object->delete should throw a Koha::Exception if there's a parent row constraint
- [[37509]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37509) Elasticsearch status info missing from 'Server information'
- [[36362]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36362) Only call Koha::Libraries->search() if necessary in Item::pickup_locations
- [[37400]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37400) On checkin don't search for a patron unless needed
- [[37260]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37260) Problem with connection to broker not displayed on the about page
- [[37371]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37371) Direct input of dates not working when editing only part of a date
- [[37216]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37216) Fix dbrev for EmailFieldSelection

## Bywater Only

- NOT IN BUGZILLA - Bug 37720: (follow-up) Adjust tests
- NOT IN BUGZILLA - Bug 37655: Basic editor needs to HTML-escape the bib record title used as a heading
- NOT IN BUGZILLA - Bug 37656: XSS in Advanced editor from Z39.50 search results
- NOT IN BUGZILLA - Bug 37654: XSS in Batch record import for Citation column
- NOT IN BUGZILLA - Bug 37681: Fix XSS in staff interface item URLs on detail page
- NOT IN BUGZILLA - Bug 13342: Not logged user can place a review/comment
- NOT IN BUGZILLA - Bug 36598: (QA follow-up): tidy up code

## Cataloging

- [[37591]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37591) Moredetail.tt page is opening very slowly
- [[37342]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37342) CSRF error - Cannot add new authorities from basic editor with 'Link authorities automatically'
- [[37399]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37399) Item type not displayed on holdings table if noItemTypeImages is disabled

## Circulation

- [[37413]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37413) Updating an item level hold on an item with no barcode to a next available hold also modifies the other holds on the record
- [[32696]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32696) Recalls can inadvertently extend the due date
- [[37552]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37552) Automatic renewals cronjob can die when an item scheduled for renewal is checked in
- [[36196]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36196) Handling NULL data in ajax calls for cities
- [[37407]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37407) Fast add / fast cataloging from patron checkout does not checkout item

## Command-line Utilities

- [[37775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37775) update_totalissues.pl uses $dbh->commit but does not use transactions
- [[37553]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37553) Fix CSRF handling in koha-svc.pl script
- [[37543]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37543) connexion_import_daemon.pl stopped working in 24.05 due to API changes related to CSRF-Token

## Course reserves

- [[37409]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37409) Edit button for items in course reserves list doesn't work

## Database

- [[37593]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37593) Fix typo in schema description for items.bookable
- [[37476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37476) RANK is a reserved word in MySQL 8.0.2+

## ERM

- [[37647]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37647) Unnecessary use of Text::CSV_XS in Koha/REST/V1/ERM/EHoldings/Titles/Local.pm
- [[37308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37308) Add user-agent to SUSHI outgoing requests
- [[37288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37288) Edit data provider form does not show the name

## Fines and fees

- [[37254]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37254) Dropdown values not cleared after pressing clear in circulation rules
- [[37263]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37263) Creating default article request fees is not working

## Hold requests

- [[37373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37373) Cursor should go to patron search box on loading holds page
- [[37351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37351) Checkboxes on waiting holds report are not kept when switching to another page
- [[37374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37374) Place hold button non-responsive for club holds
- [[29087]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29087) Holds to pull list can crash with a SQL::Abstract puke

## I18N/L10N

- [[37303]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37303) Fuzzy translations displayed on the UI

## ILL

- [[37389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37389) REST API queries joining on extended_attributes may cause severe performance issues

## Label/patron card printing

- [[37192]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37192) Can't print label from the item editor

## Lists

- [[37285]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37285) Printing lists only prints the ten first results

## MARC Authority data support

- [[37226]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37226) Authority hierarchy tree broken when a child (narrower) term appears under more than one parent (greater) term

## OPAC

- [[36566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36566) Correct ESLlint errors in OPAC enhanced content JS
- [[37324]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37324) Self registration complete login form won't login user
- [[37111]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37111) OPAC renewal - CSRF "op must be set"

## Patrons

- [[37542]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37542) Patron search is incorrectly parsing entries as dates and fetching the wrong patron if dateofbirth in search fields
- [[36882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36882) Flatpickr doesn't work for repeatable date patron attributes in overdues
- [[37489]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37489) Cannot delete patron image without uploading a file
- [[37523]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37523) CSRF error when modifying an existing patron record
- [[37378]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37378) Patron searches can fail when library groups are set to 'Limit patron data access by group'

## Point of Sale

- [[37563]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37563) Refund, payout, and discount modals in patron transactions and point of sale have broken/bad formatting of values
- [[36998]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36998) 'Issue refund' modal on cash register transactions page can mistakenly display amount from previously clicked on transaction

## Reports

- [[37763]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37763) 'Update and run SQL' appends the editor screen after the report results
- [[37077]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37077) SQL Reports - Picking only one option for each multiple selection results in wrong query
- [[37382]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37382) Report download is empty except for headers if .tab format is selected
- [[37093]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37093) 403 Forbidden Error when attempting to search for Mana Reports

## REST API

- [[29509]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29509) GET /patrons* routes permissions excessive

## Searching - Elasticsearch

- [[36879]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36879) Spurious warnings in QueryBuilder
- [[35792]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35792) Quiet warning: Use of uninitialized value $sub6

## Serials

- [[37873]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37873) Unable to delete user from routing list or preview/print routing list slip

## Staff interface

- [[31921]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31921) No confirmation alert when deleting a vendor
- [[33453]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33453) Confirmation button for 'Record cashup' should be yellow
- [[33455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33455) Heading on 'update password' page is too big
- [[36129]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36129) Check in "Hide all columns" doesn't persist on item batch modification/deletion
- [[37029]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37029) 'About Koha' button on staff side homepage seems out of place among application buttons
- [[28762]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28762) Item status shows incorrectly on course-details.pl
- [[26866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26866) Items table on additem should sort by cn_sort

## System Administration

- [[36907]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36907) OAI set mapping form field maxlength should match table column sizes
- [[37461]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37461) Typo in SMSSendAdditionalOptions description
- [[37419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37419) Deleting the record source deletes the associated biblio_metadata rows

## Templates

- [[37643]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37643) Check for NaN instead of truthiness if calendar.inc accepts_time
- [[37030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37030) Use template wrapper for breadcrumbs: Cash register stats
- [[35235]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35235) Mismatched label on notice edit form
- [[37496]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37496) Link to item details from holdings table links to all items
- [[35236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35236) Mismatched label on patron card batch edit form
- [[36885]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36885) Missing tooltip on budget planning page

## Test Suite

- [[37623]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37623) t/db_dependent/Letters.t tests fails to consider EmailFieldPrimary system preference
- [[37620]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37620) Fix randomly failing tests for cypress/integration/InfiniteScrollSelect_spec.ts
- [[37607]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37607) t/cypress/integration/ERM/DataProviders_spec.ts fails
- [[37302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37302) xt/api.t should fail if swagger-cli is missing

## Tools

- [[37612]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37612) Batch modifying patrons from patron lists broken by CSRF protection
- [[37186]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37186) Cannot delete a rotating collection
- [[37614]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37614) Printing patron cards from patron lists broken by CSRF protection


