
# Release Notes for washoe-v18.11.04-03

## Bywater Only

- NOT IN BUGZILLA - Fix bug introduced by rebase



# Release Notes for washoe-v18.11.04-02

## Architecture, internals, and plumbing

- [[22618]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22618) Tests in t/Acquisition.t are actually database dependent



# Release Notes for washoe-v18.11.04-01

## About

- [[7143]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7143) Bug for tracking changes to the about page

## Acquisitions

- [[22565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22565) Partially receiving order and adding internal note on invoice updates note on every order on the system
- [[18736]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18736) Problems in order calculations (rounding errors)
- [[20782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20782) EDI: Clicking the 'Invoice' link on the 'EDI Messages' page does not take you directly to the corresponding invoice
- [[22296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22296) Invoice adjustments are not populating to budget views
- [[22498]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22498) Can not select any funds for invoice adjustments
- [[14850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14850) Funds from inactive budgets appear in 'Funds' dropdown on acqui/invoice.pl
- [[18166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18166) Show internal and vendor notes for received orders
- [[21427]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21427) Format prices on ordered/spent lists
- [[21966]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21966) Fix descriptions of acquisition permissions to be more clear (again)
- [[22171]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22171) Format shipping cost on invoice.pl with with 2 decimals

## Architecture, internals, and plumbing

- [[22219]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22219) C4::Biblio->GetItemsForInventory can return wrong count / duplicated items when skipping waiting holds
- [[21987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21987) Local cover 'thumbnail' size is bigger than 'imagefile' size in biblioimages table
- [[18584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18584) Our legacy code contains trailing-spaces
- [[22084]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22084) Plugin upgrade method and database plugin version storage will never be triggered for existing installs
- [[21622]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21622) Incorrect GROUP BY clause in acqui/ scripts
- [[22391]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22391) Incorrect GROUP BY in /acqui/ajax-getauthvaluedropbox.pl
- [[22388]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22388) svc/split_callnumbers should have execute flag set

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[16251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16251) Material type is not correctly set for Rancor 008 widget
- [[22140]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22140) More use of EasyAnalyticalRecords pref

## Circulation

- [[13763]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13763) Renew feature does not check for the BarcodeInputFilter option
- [[21030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21030) Date widget on suspend modal not working correctly
- [[18957]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18957) Item renewed online does not show the time of renewal
- [[22130]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22130) Batch checkout: authorized value description is never shown with notforloan status
- [[17236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17236) Add minute and hours to last checked out item display for hourly loans
- [[22351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22351) SCSS conversion broke style on last checked out information

## Command-line Utilities

- [[22397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22397) Wrong message in koha-sip --start
- [[22396]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22396) koha-sip script does not start the server correctly
- [[22323]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22323) Cronjob runreport.pl has a CSV encoding issue
- [[12488]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12488) Make bulkmarcimport.pl -d use DELETE instead of TRUNCATE

## Database

- [[22476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22476) MarkLostItemsAsReturned has wrong defaults for new installs
- [[13515]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13515) Table messages is missing FK constraints and is never cleaned up

## Developer documentation

- [[20544]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20544) Wrong comment in database documentation for items.itemnotes

## Hold requests

- [[21765]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21765) AutoUnsuspendReserves manually sets holds fields instead of calling ->resume

## Installation and upgrade (command-line installer)

- [[17496]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17496) install-CPAN.pl documentation/removal
- [[20174]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20174) Remove xml_sax.pl target from Makefile.pl

## Installation and upgrade (web-based installer)

- [[21710]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21710) Fix typo atributes in some installer files

## Label/patron card printing

- [[22429]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22429) Infinite loop in patron card printing
- [[22275]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22275) 18.06.00.060 DB update fails (incomplete/incorrect defaults)

## OPAC

- [[21846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21846) Using emoji as tags doesn't discriminate between emoji when calculating weights or searching
- [[22360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22360) On order information missing in OPAC normal display
- [[21335]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21335) Remove redundant includes of right-to-left.css
- [[10676]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10676) OpacHiddenItems not working for restricted on OPAC detail

## Patrons

- [[16276]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16276) When automatically deleting expired borrowers, make sure they didn't log in recently
- [[22386]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22386) Importing using attributes as matchpoint broken
- [[22067]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22067) Koha::Patron->can_see_patron_infos should return if no patron is passed

## Reports

- [[21560]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21560) Optimize ODS exports
- [[22147]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22147) Hide 'Batch modify' button when printing reports
- [[18393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18393) Statistics wizard for acquisitions not filtering correctly by collection code
- [[22287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22287) Correct new charts CSS

## REST api

- [[22206]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22206) Add route to handle holds suspensions
- [[20006]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20006) Adapt /v1/holds to new naming guidelines
- [[16497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16497) Add API routes for libraries

## Searching

- [[20823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20823) UNIMARC XSLT does not display 604$t
- [[22442]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22442) Item search CSV export broken

## Searching - Elasticsearch

- [[22246]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22246) Elasticsearch indexing needs a maximum length for `__sort` fields
- [[20535]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20535) ModZebra called with $record with items stripped in ModBiblioMarc
- [[22228]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22228) Elasticsearch - standalone colons should be escaped when performing a search
- [[19575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19575) Use canonical field names and resolve aliased fields

## Self checkout

- [[22378]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22378) Fix sound alerts on SCO

## Serials

- [[13735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13735) Item form in serials module doesn't respect max length set in the frameworks
- [[22404]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22404) Some labels in subscription add form has wrong parameter "for"
- [[15149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15149) Serials: Test prediction pattern does not consider Subscription start and end date
- [[21845]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21845) Sort of issues in OPAC subscription table
- [[22156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22156) Subscription result list sorts on "checkbox" by default
- [[22239]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22239) JavaScript error on subscription detail page when there are no orders

## SIP2

- [[21997]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21997) SIP patron information requests can lock patron out of account
- [[19832]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19832) SIP checkout removes extra hold on same biblio

## Staff Client

- [[19046]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19046) IntranetCatalogSearchPulldown doesn't retain last selection
- [[22419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22419) Removing multiple records from intranet cart causes browser timeout
- [[21904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21904) Patron search library dropdown should be limited  by group if "Hide patron info" is enabled for group

## System Administration

- [[22170]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22170) Library group description input field should be longer
- [[22389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22389) Classification splitting sources regex - cannot consistentlyadd/delete
- [[18143]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18143) Silence floody MARC framework export

## Templates

- [[21130]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21130) Detail XSLT produces translatable HTML class
- [[20658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20658) Move template JavaScript to the footer: Installer and onboarding
- [[22477]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22477) Missing DataTables configuration when searching patrons for holds
- [[22422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22422) improve item location display with class "shelvingloc"
- [[22303]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22303) Wrong bottom in virtualshelves/addbybiblionumber.tt
- [[22466]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22466) TT methods must not be escaped
- [[22300]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22300) Staff search results: Opt groups in 'sort' pull down are not well formatted
- [[22080]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22080) Easier translation of ElasticSearch mappings page
- [[20102]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20102) Remove attribute "text/css" for style element used in staff client templates
- [[8387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8387) Hide headings in tools when user has no permissions for any listed below

## Test Suite

- [[22493]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22493) DecreaseLoanHighHolds.t creates some items/patrons with set values
- [[22416]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22416) Search.t tests need adjustment for EasyAnalyticRecords syspref
- [[21692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21692) Koha::Account->new has no tests
- [[21798]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21798) We need t::lib::TestBuilder::build_sample_biblio
- [[21971]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21971) TestBuilder::build_sample_item

## Tools

- [[22411]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22411) Dates in log viewer not formatted correctly

## Web services

- [[21832]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21832) Restore is_expired in ILS-DI GetPatronInfo service


