
# Release Notes for mdah-v18.05.10-01

## About

- [[21441]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21441) System information gives reference to a non-existant table

## Acquisitions

- [[22282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22282) Internal software error when exporting basket group as PDF
- [[20865]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20865) Remove space before : on order receive filters

## Architecture, internals, and plumbing

- [[21969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21969) Koha::Account->outstanding_* should look for debits/credits by checking 'amount'
- [[22097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22097) CataloguingLog should be suppressed for item branch transfers
- [[21907]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21907) Error from mainpage when Article requests enabled and either IndependentBranches or IndependentBranchesPatronModifications is enabled
- [[19816]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19816) output_pref must implement 'dateonly' for dateformat => rfc3339
- [[22124]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22124) Update cataloguing plugin system to not generate type parameter in script tag
- [[21478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21478) Koha::Hold->suspend_hold allows suspending in transit holds
- [[19920]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19920) changepassword is exported from C4::Members but has been removed
- [[22125]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22125) branches.pickup_location should be flagged as boolean
- [[21170]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21170) Warnings in MARCdetail.pl - isn't numeric in numeric eq (==)
- [[22006]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22006) Koha::Account::Line->item should return undef if no item linked
- [[21912]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21912) Koha::Objects->search lacks tests

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[22395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22395) Data in 245 field (subfield a or b) will be deleted if it has Quotation Marks
- [[22242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22242) Javascript error in value builder cased by Select2
- [[20491]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20491) Use "Date due" in table header of item table
- [[22122]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22122) Make sequence of Z39.50 search options match in acq and cataloguing

## Circulation

- [[22119]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22119) Add price formatting in circulation
- [[22120]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22120) Add price formatting to patron summary print
- [[17347]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17347) 'Renew' tab should ignore whitespace at begining and end of barcode
- [[22083]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22083) Typo in circulation_batch_checkouts.tt
- [[21877]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21877) Show authorized value description for withdrawn in checkout
- [[22203]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22203) Holds modal no longer links to patron
- [[22111]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22111) Correctly format fines when placing holds (maxoutstanding warning)
- [[21491]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21491) When 'Default lost item fee refund on return policy' is unset it says no but acts as if 'yes'
- [[22054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22054) Display a nicer error message when trying to renew an on-site checkout from renew page

## Database

- [[13515]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13515) Table messages is missing FK constraints and is never cleaned up

## Developer documentation

- [[21290]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21290) POD of ModItem mentions MARC for items

## Holidays

- [[21885]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21885) Improve date selection on calendar for selecting the end date on a range

## ILL

- [[22101]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22101) ILL requests missing in menu on advanced search page

## Installation and upgrade (web-based installer)

- [[11922]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11922) Add SHOW_BCODE patron attribute for Norwegian web installer
- [[22095]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22095) Dead link in web installer

## MARC Authority data support

- [[19994]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19994) use Modern::Perl in Authorities perl scripts

## Notices

- [[21829]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21829) Date displays as a datetime in notices

## OPAC

- [[21808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21808) Field 711 is not handled correctly in showAuthor XSLT for relator term or code
- [[22207]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22207) Course reserves page does not have unique body id
- [[22118]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22118) Format hold fee when placing holds in OPAC
- [[21192]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21192) Borrower Fields on OPAC's Personal Details Screen Use Self Register Field Options Incorrectly
- [[22085]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22085) UNIMARC default XSLT broken by Bug 14716

## Patrons

- [[22149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22149) Grammar fix in the manage_circ_rules_from_any_libraries description
- [[21930]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21930) Typo in the manage_circ_rules_from_any_libraries description
- [[20165]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20165) Capitalization: Street Address should be Street address in patron search options

## Reports

- [[22278]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22278) Newly created report group is not selected after saving an SQL report
- [[20679]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20679) Remove 'rows per page' from reports print layout
- [[20274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20274) itemtypes.plugin report: not handling item-level_itypes syspref
- [[22082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22082) Ambiguous column in patron stats

## REST api

- [[22132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22132) Add Basic authentication to the REST API

## Searching

- [[18909]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18909) Enable the maximum zebra records size to be specified per instance

## Serials

- [[16231]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16231) Correct permission handling in subscription edit menu

## System Administration

- [[15110]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15110) Improve decreaseHighHolds system preference description
- [[21926]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21926) Enhance OAI-PMH:archiveID system preference description
- [[21855]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21855) Remove mention of deprecated delete_unverified_opac_registrations.pl cronjob
- [[7403]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7403) Remove warning from CataloguingLog system preference
- [[21637]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21637) Capitalization: EasyAnalyticalRecords syspref option "Don't Display" should be "Don't display"

## Templates

- [[21840]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21840) Fix some typos in the templates
- [[22236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22236) Translation should generate tags with consistent attribute order
- [[20569]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20569) Improve description of CheckPrevCheckout system preference
- [[22113]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22113) Add price formatting on item lost report
- [[21866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21866) Rephrase "Warning: This *report* was written for an older version of Koha" to refer to plugins

## Test Suite

- [[22254]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22254) t/db_dependent/Koha/Patrons.t contains a DateTime math error
- [[22107]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22107) Avoid deleting data in some tests

## Tools

- [[20634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20634) Inventory form has 2 identical labels "Library:"
- [[22136]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22136) Import patrons notes hides a note because the syspref isn't referenced correctly
- [[22011]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22011) Typo in Item Batch Modification
- [[22036]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22036) Tidy up tags/review script



# Release Notes for mdah-v18.05.08-03

## Searching - Zebra

- [[20078]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20078) Indexes 'arl' (Accelerated reading level) and 'arp' (Accelerated reading point) not usable in search menus



# Release Notes for mdah-v18.05.08-02

## Cataloging

- [[585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=585) Using 'document.forms[0]' notation prevents use of other forms on page


