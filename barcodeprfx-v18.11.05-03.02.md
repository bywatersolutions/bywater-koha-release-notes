
# Release Notes for barcodeprfx-v18.11.05-03.02

## Custom For Instance

- NOT IN BUGZILLA - Fix typo Koha::Patrons->new => Koha::Patron->new



# Release Notes for barcodeprfx-v18.11.05-03.01



# Release Notes for barcodeprfx-v18.11.05-03

## Bywater Only

- NOT IN BUGZILLA - Fix atomic updates

## Custom For Instance

- NOT IN BUGZILLA - Fix issues introduces by rebase to Koha version 18.11



# Release Notes for barcodeprfx-v18.11.05-02

## Circulation

- [[22809]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22809) Move "INVOICE" from template to a slip
- [[22761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22761) Move "Fee receipt" from template to a slip



# Release Notes for barcodeprfx-v18.11.05-01

## Acquisitions

- [[22762]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22762) Collection codes not displayed on receiving
- [[20830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20830) Make sure a fund is selected when ordering from staged file
- [[22444]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22444) currencies_manage permission doesn't provide link to manage currencies when selected alone
- [[21659]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21659) Link to basket groups from order receive page are broken
- [[22541]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22541) Invoice adjustments: show invoice number and include link on ordered.pl and spent.pl
- [[22390]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22390) When duplicating existing order lines new items are not created
- [[22611]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22611) Typo introduced into Koha::EDI by bug 15685

## Architecture, internals, and plumbing

- [[22542]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22542) Back browser should not allow to see other patrons details (see bug 5371)
- [[22478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22478) Cross-site scripting vulnerability in paginations
- [[22723]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22723) Syntax error on confess call in Koha/MetadataRecord/Authority.pm
- [[21172]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21172) Warning in addbiblio.pl - Argument "01e" isn't numeric in numeric ne (!=)
- [[22044]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22044) NoRenewalBeforePrecision should be set by default for new installations
- [[22451]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22451) Asset plugin is using the version from the DB
- [[22472]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22472) Should column_exists explode if the table does not exist?
- [[22618]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22618) Tests in t/Acquisition.t are actually context dependent
- [[22607]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22607) Default value in issues.renewals should be '0' not null
- [[21622]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21622) Incorrect GROUP BY clause in acqui/ scripts
- [[21998]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21998) Add pattern parameter in Koha::Token

## Authentication

- [[22692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22692) Logging in via cardnumber circumvents account logout
- [[22461]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22461) Regression in #20287: LDAP user replication broken with mapped extended patron attributes

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Bug 22068: (QA follow-up) Return meaningful error codes

## Cataloging

- [[16232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16232) Edit as new (duplicate) doesn't work correctly with Rancor
- [[21937]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21937) Syspref autoBarcode annual doesn't increment properly barcode in some cases
- [[22288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22288) Barcode file does not work in modifying items in batch
- [[10345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10345) Copy number should be incremented when adding multiple items at once
- [[21049]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21049) Rancor 007 field does not retain value

## Circulation

- [[21346]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21346) Clean up dialogs in returns.pl
- [[21013]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21013) Missing itemtype for checkut makes patron summary print explode
- [[22648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22648) Typo in SQL in smart-rules.pl
- [[22536]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22536) Display problem in Holds to Pull report

## Command-line Utilities

- [[20692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20692) koha-plack doesn't check for Include *-plack.conf line in /etc/apache2/sites-available/$INSTANCE.conf
- [[21975]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21975) Unnecessary substitutions in automatic item modification by age
- [[17746]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17746) koha-reset-passwd should use Koha::Patron->set_password

## Course reserves

- [[22652]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22652) Editing Course reserves is broken
- [[21003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21003) Don't show warning when editing a reserve item

## Database

- [[22642]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22642) DB upgrade 18.06.00.005 can fail
- [[22634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22634) Standardize table creation for stockrotation* tables in kohacstructure.sql

## Documentation

- [[22687]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22687) Typo in Koha::Manual breaks Portuguese links
- [[22174]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22174) Add link to help page for API key management
- [[19747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19747) No help page linked for article requests

## Fines and fees

- [[22626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22626) 'Filter paid transactions' broken on Transactions tab in staff

## Hold requests

- [[22650]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22650) Can place multiple item level holds on a single item
- [[22753]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22753) Move hold to top button doesn't work if waiting holds exist
- [[15505]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15505) Mark Hold Items 'On hold' instead of 'Available'
- [[22688]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22688) TT plugin for pickup locations code wrong
- [[21263]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21263) Pickup library not set correctly when using Default holds policy by item type
- [[17978]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17978) Include 'Next available'/title level holds in holds count when placing holds (opac and staff)

## I18N/L10N

- [[19497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19497) Translatability: Get rid of "Edit [% field.name |html %] field"

## ILL

- [[22464]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22464) Copyright notice does not pass forward request properties
- [[22121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22121) Display 'Price paid' on ILL requests according to CurrencyFormat pref

## Installation and upgrade (web-based installer)

- [[21545]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21545) Update German web Installer for 18.11

## Lists

- [[20891]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20891) Lists in staff don't load when \ was used in the description

## MARC Bibliographic data support

- [[21899]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21899) Update MARC21 frameworks to Update 27 (November 2018)
- [[19648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19648) Repeated positions and some options missing in cataloguing plugin 007 (XML file)

## Notices

- [[22139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22139) Fields of ACCTDETAILS not working properly
- [[14358]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14358) Changing the module refreshes the page and resets library choice
- [[20937]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20937) PrintNoticesMaxLines is not effective for overdue notices with a print type specified where a patron has an email

## OPAC

- [[21589]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21589) Series link formed from 830 field is incorrect
- [[22551]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22551) Stray "//" appears at bottom of opac-detail.tt
- [[19241]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19241) Items with status of hold show as available in cart
- [[22743]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22743) OverDrive results page is missing overdrive-login include
- [[22735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22735) Broken MARC and ISBD views
- [[22501]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22501) OPAC course reserves notes should allow html links
- [[22624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22624) Show OPAC description for authorised values in OPAC
- [[13629]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13629) SingleBranchMode removes both library and availability search from advanced search
- [[22680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22680) OPAC language footer not positioned correctly
- [[22075]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22075) Encoding problem with RIS export
- [[22620]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22620) OPAC description for collection in opac-reserve.tt
- [[22560]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22560) Forgotten password "token expired" page still shows boxes to reset password
- [[22561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22561) Forgotten password requirements hint doesn't list all rules for new passwords
- [[22550]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22550) OPAC suggestion form doesn't require mandatory fields

## Patrons

- [[22715]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22715) Searching for patrons with "" in the circulation note hangs patron search
- [[22646]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22646) Fix use of PrivacyPolicyURL

## Reports

- [[22090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22090) Cash register report missing data in CSV export

## REST api

- [[13895]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13895) Add routes for checkouts retrieval and renewal
- [[19661]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19661) Add routes for funds

## Searching

- [[22154]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22154) Subtype search for Format - Braille doesn't look for the right codes
- [[22595]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22595) Items search is mixing inputs
- [[12441]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12441) search.pl has incorrect reference to OPACdefaultSortField and OPACdefaultSortOrder
- [[22596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22596) html TT filter is breaking items search with custom field

## Searching - Elasticsearch

- [[22413]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22413) Elasticsearch - Search settings are lost after sorting, faceting or paging
- [[22339]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22339) Elasticsearch - fixed field mappings should match MARC ranges
- [[22474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22474) Authority and biblio field mapping improperly shared
- [[19670]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19670) search_marc_map.marc_field should have COLLATE= utf8mb4_bin
- [[22295]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22295) Elasticsearch - Advanced search should group terms entered in a single input
- [[22495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22495) Restore su-geo field in Elasticsearch mappings
- [[21974]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21974) cxn_pool must be configurable

## Self checkout

- [[22739]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22739) Self check in module JS breaks if  SelfCheckInTimeout  is unset
- [[18387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18387) 404 errors on page causes SCO user to be logged out
- [[22641]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22641) Incorrect filter on SCO printslip

## Serials

- [[22621]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22621) Filters on subscription result list search the wrong column

## System Administration

- [[18011]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18011) Enrollment period date on patron category can be set in the past without any error/warning messages
- [[22575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22575) Item type administration uses invalid error class for dialog

## Templates

- [[22716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22716) Use gender-neutral pronouns in system preference descriptions
- [[22702]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22702) Circulation note on patron page should allow for HTML tags
- [[22475]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22475) Shelving location doesn't appear on tags list view
- [[22586]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22586) IntranetReportsHomeHTML no longer renders as HTML on reports-home.pl
- [[21948]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21948) Clean up style of item detail page

## Tools

- [[22365]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22365) Warn on Log Viewer
- [[22069]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22069) Log viewer not displaying item renewals

## Web services

- [[22597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22597) Remove "more_subfields_xml" from GetPatronInfo response (xml broken)



# Release Notes for barcodeprfx-v18.11.04-03

## Bywater Only

- NOT IN BUGZILLA - Fix bug introduced by rebase

## Custom For Instance

- [[20256]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20256) Add ability to limit editing of items to home library
- [[22330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22330) Transfer limits should be respected for placing holds in staff interface and APIs
- [[21957]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21957) LinkBibHeadingsToAuthorities can be called twice when running link_bibs_to_authorities
- [[21450]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21450) link_bibs_to_authorities.pl is caching searches without the auth type



# Release Notes for barcodeprfx-v18.11.04-02

## Architecture, internals, and plumbing

- [[22618]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22618) Tests in t/Acquisition.t are actually database dependent



# Release Notes for barcodeprfx-v18.11.04-01

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

