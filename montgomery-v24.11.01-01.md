
# Release Notes for montgomery-v24.11.01-01

## Accessibility

- [[33766]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33766) Fix ambiguous form field in OPAC login form
- [[37988]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37988) Accessibility: The 'Home' icon in the staff interface cannot be accessed with a keyboard
- [[37758]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37758) Accessibility: "translControl1" field is missing a descriptive label

## Acquisitions

- [[38343]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38343) False display of closed invoices in receive process
- [[38326]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38326) copyno not copied over when set in MarcItemFieldsToOrder system preference
- [[38235]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38235) Suggestion confirmation letter sent when it should not
- [[34355]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34355) Automated MARC record ordering process
- [[37511]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37511) Add option to place the currency symbol before or after the amount
- [[38204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38204) Add `GET /acquisitions/baskets`
- [[37109]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37109) Don't provide old claims fields when duplicating acquisitions orders
- [[8855]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8855) Link from receipt to invoice
- [[34805]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34805) Add order search form to acquisitions module start page
- [[37081]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37081) Add order confusing when ordering from a staged file
- [[37337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37337) Submitting a similar suggestion results in a blank page
- [[33363]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33363) More specific permissions for purchase suggestions
- [[36767]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36767) Add a hint to the EDI account form that the SFTP/FTP port will fallback to port 22 if not defined
- [[35597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35597) Purchase suggestion changes aren't logged

## Architecture, internals, and plumbing

- [[37292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37292) Add an index on expires column for oauth_access_tokens
- [[28294]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28294) C4::Circulation::updateWrongTransfer should be moved into Koha::
- [[38424]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38424) Upgrade redocly/cli to the latest release
- [[36640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36640) Upgrade DataTables from 1.13.6 to 2.x
- [[33641]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33641) We should record return library in old checkouts (oldissues)
- [[38011]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38011) Add a foreign key link between vendors and subscriptions
- [[37865]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37865) Use of uninitialized value $op in string at circulation.pl
- [[38279]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38279) C4::ImportBatch::EmbedItemsInImportBiblio is not used
- [[31224]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31224) Koha::Biblio::Metadata->record should use the EmbedItems filter
- [[38342]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38342) Koha::Object->store warning on invalid ENUM value
- [[35721]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35721) Replace ModItemTransfer calls in circ/returns.pl
- [[38273]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38273) Koha::Object->discard_changes should return the Koha::Object for chaining
- [[38243]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38243) Datatable's header_filter is unused
- [[38120]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38120) Commented lines in auth.tt should be removed
- [[38274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38274) Typo in Arabic language description
- [[37869]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37869) Plugin hook before_send_messages not triggered for any messages sent without use of process_message_queue.pl
- [[37868]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37868) Remove C4::Reserves::ToggleSuspend
- [[37845]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37845) Remove C4::Members::DeleteExpiredOpacRegistrations
- [[37844]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37844) Remove C4::Members::DeleteUnverifiedOpacRegistrations
- [[36694]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36694) Remove HC Sticky library in favor of CSS
- [[37728]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37728) More "op" are missing in POSTed forms
- [[38081]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38081) maskitoTimeOptionsGenerator does not properly support 12-hour times in calendar.inc
- [[36594]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36594) Library hours display issues
- [[35655]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35655) Make it possible to switch off RabbitMQ without any warns in logs/about page
- [[30856]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30856) Remove CanReserveBeCanceledFromOpac
- [[37480]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37480) Make C4::Serials::addroutingmember use Koha::Objects
- [[37380]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37380) Move GetMarcControlnumber to Koha namespace
- [[17729]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17729) Replace IsItemOnHoldAndFound with $item->holds->filter_by_found->count
- [[37797]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37797) Choosing not to delete a budget does not need to be a form submission
- [[37757]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37757) notice_email_address explodes if EmailFieldPrimary is not valid
- [[37493]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37493) Cypress videos and screenshots should be .gitignored
- [[23387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23387) Cache ClassSource
- [[24471]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24471) Rename ILL method handle_commit_maybe
- [[35026]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35026) Refactor addorderiso2709.pl to use object methods
- [[35539]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35539) Remove unused columns from categories table
- [[37216]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37216) Fix dbrev for EmailFieldSelection
- [[36875]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36875) SQL injection in additional content pages
- [[36818]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36818) Remote-Code-Execution (RCE) in upload-cover-image.pl (CVE-2024-36057)
- [[36367]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36367) Remove context stack
- [[36330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36330) Fix typo: reseve

## Authentication

- [[36026]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36026) Add TLS MySQL connection without mutual authentication
- [[36822]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36822) When creating a new patron via LDAP or Shibboleth 0000-00-00 is inserted for invalid updated_on
- [[37691]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37691) Password expiration reset not clear enough

## Bywater Only

- NOT IN BUGZILLA - Fix issue with get_template_and_user AutoSelfCheckID causing unit test failures
- NOT IN BUGZILLA - GitHub Actions - Set default branch using GitHub Actions
- NOT IN BUGZILLA - GitHub Actions - Update image from 24.05 to 24.11
- NOT IN BUGZILLA - Move 241101000.pl into db_revs and set execute bit
- NOT IN BUGZILLA - 24.11.00: Update history.txt
- NOT IN BUGZILLA - 24.11.00: Update contributors.yaml
- NOT IN BUGZILLA - Update contributor list with some new contributors
- NOT IN BUGZILLA - DBRev 24.06.00.000: Start of a new release cycle

## Cataloging

- [[35659]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35659) OAI harvester
- [[37392]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37392) Edit item permission by library group is broken
- [[36054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36054) Don't mark MARC21 005 as mandatory in frameworks now that AddBiblio and ModBibilio will set it no matter what
- [[38057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38057) Fix checkmarks in change framework menu in advanced editor after Bootstrap5 update
- [[36496]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36496) Inventory results table needs an export option
- [[36515]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36515) Amend MARC modification templates so control fields can be copied to subfields
- [[29560]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29560) Add option to create MARC links when adding items to bundles

## Circulation

- [[37592]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37592) Add a record of creation and modification to bookings
- [[37866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37866) Unable to resolve claim from patron details page
- [[33736]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33736) Add bookings to collect circulation report
- [[37354]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37354) Bookings should respect circulation rules for max loan periods
- [[38287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38287) Saving default checkout, hold and return policy with empty bookings values causes error
- [[38175]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38175) Improve bookings behavior with new status field
- [[35906]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35906) Add bookable option on itemtypes
- [[14787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14787) Allow confirm/continue option to circulation warnings at checkout
- [[14180]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14180) Make "Always show checkouts immediately" a global setting
- [[38013]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38013) Some checkin messages on checkins page lack specific CSS classes
- [[38246]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38246) If using automatic return claim resolution on checkout, each checkout will overwrite the previous resolution
- [[38222]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38222) Let staff pick a cancellation reason when canceling a booking
- [[38193]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38193) Add cancellation_reason field to bookings table
- [[37803]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37803) Add patron notification when a new booking has been created successfully
- [[37204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37204) Add a booking has changed notice to update a patron should a booking be updated
- [[33292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33292) Claim return doesn't refund lost item charge when MarkLostItemsAsReturned includes "When marking an item as a return claim" and "Refund lost item fee" is on
- [[38060]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38060) Bookings table does not render if tab opened from the URL
- [[27919]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27919) Split claims return from LOST
- [[37023]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37023) Filling a hold should update the timestamp
- [[38016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38016) Relabel booking precaution column heading in circulation rules tables
- [[37601]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37601) Add status field to bookings table
- [[37636]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37636) Checkout slip prints out of order
- [[37783]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37783) Fix form that looks like it would POST without an op in reserve/request.tt
- [[34440]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34440) Add warm-up and cool-down periods to bookings
- [[36915]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36915) Send email notification when a booking is cancelled
- [[35931]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35931) Pre-select items with due date today in the renew column on details page and on checkout page
- [[36716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36716) Need a better way of looping through smart-rules ( circ table ) columns
- [[36475]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36475) "Print summary" tables cannot be column configured
- [[37552]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37552) Automatic renewals cronjob can die when an item scheduled for renewal is checked in
- [[36547]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36547) Add 'Checked out on' column to overdues table
- [[23781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23781) Recalls notices and messaging preferences
- [[28924]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28924) Allow checkout fine limit to be determined by patron category
- [[37126]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37126) Provide link to patron account when checking out to statistical patron ends checkout
- [[36476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36476) Add holds priority column to patron summary print

## Command-line Utilities

- [[36766]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36766) Add command-line utility to SFTP a file to a remote server
- [[36977]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36977) Google does not read sitemaps with the name sitemapNNNN.xml
- [[38156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38156) Auto renew cron job mangles digest notices when parallel processing is enabled
- [[37682]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37682) Improve speed of koha-preferences CLI tool (by lazy-loading modules)
- [[37657]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37657) Improve speed of koha-preferences CLI tool (by using minimal dbh)
- [[37613]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37613) Follow-up to bug 9596 to change the option and documentation to match Terminology Guidelines
- [[9596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=9596) Allow longoverdue.pl to be configured per library on the command line
- [[36770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36770) Add a --report_id parameter to export_records.pl
- [[29507]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29507) Speed up auto renew cronjob via parallel processing
- [[37038]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37038) koha-elasticsearch creates a file named 0
- [[37181]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37181) Add --confirm option switch to pseudonymize_statistics.pl

## Course reserves

- [[35978]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35978) Extend breadcrumbs course reserves with sections

## Custom For Instance

- NOT IN BUGZILLA - Remove failing test t/db_dependent/api/v1/erm_sushi_services.t

## Database

- [[38602]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38602) Columns bookings.creation_date and bookings.modification_date not added if multiple databases are in use
- [[38522]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38522) Increase length of erm_argreements.license_info
- [[22421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22421) accountlines.issue_id is missing a foreign key constraint
- [[38434]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38434) (Bug 35906 follow-up) dbrev different from kohastructure.sql

## ERM

- [[38466]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38466) KBART import fails silently if file extension is wrong
- [[37576]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37576) Add additional fields support to ERM agreements
- [[37577]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37577) Add additional fields support to ERM packages
- [[35287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35287) Add additional fields support to ERM licenses
- [[37810]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37810) Some SUSHI providers return ServiceActive instead of Service_Active
- [[37526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37526) Handle redirects in SUSHI requests
- [[37856]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37856) Some SUSHI providers require the platform parameter
- [[37274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37274) Standardize the toolbar in Vue components

## Fines and fees

- [[34325]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34325) On the manual invoice and credit forms rename "Barcode" to "Item barcode" for clarity

## Hold requests

- [[29079]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29079) Make bibliographic information in holds queue customizable
- [[28833]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28833) Speed up holds queue builder via parallel processing
- [[36064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36064) Add information about holds with cancellation requests to staff start page
- [[36595]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36595) Add patron email to the holds queue table
- [[30411]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30411) Add separate shelving location column to holds queue

## I18N/L10N

- [[38492]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38492) Some javascript translatable strings do not get picked up for translation
- [[36836]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36836) Review ERM module for translation issues
- [[37781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37781) Add translation context for "On" (when used alone)
- [[32313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32313) Complete database column descriptions for cataloguing module in guided reports
- [[18493]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18493) Many languages are missing from the advanced search languages dropdown

## ILL

- [[36221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36221) Improve styling of Standard backend create OPAC form
- [[35570]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35570) Add a generic master form in ILL
- [[38376]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38376) ILL Standard form does not consider id in openURL
- [[38166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38166) Core status graph strings should be translatable
- [[38359]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38359) ILL UI pages offset no longer works after Bootstrap 5 upgrade
- [[38288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38288) Provide openURL backwards compatibility with FreeForm
- [[38276]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38276) ILL Standard form does not consider DOI in openURL
- [[35725]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35725) Generic master form does not keep patron and cardnumber when changing type
- [[36118]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36118) ILL request log does not display patron information
- [[34597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34597) Expired patrons can still place ILL requests through OPAC

## Installation and upgrade (command-line installer)

- [[38299]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38299) Errors with updates caught in C4::Installer should be colored/highlighted
- [[34088]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34088) Schema upgrade should short circuit faster if no upgrade needs to be done
- [[38394]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38394) Remove try/catch and say_failures for 24.11
- [[37818]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37818) XXX trick in installer code is not longer needed
- [[37820]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37820) Upgrade fails at 23.12.00.023 [Bug 36993]
- [[36978]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36978) Upgrade fails at 23.06.00.007 [Bug 34029]
- [[36986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36986) (Bug 26176 follow-up) Fix rename StaffLoginBranchBasedOnIP in DBRev

## Installation and upgrade (web-based installer)

- [[38622]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38622) Fix Koha sample data to include preferred_name
- [[38383]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38383) say_info messages in web installer have bad contrast/font color

## Lists

- [[30955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30955) Send a notice to new owner when transferring shared list
- [[37177]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37177) "item" should be "record" in list page
- [[13888]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13888) 'Lists' permission should allow/disallow using the lists module in staff

## MARC Authority data support

- [[37349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37349) Use cache for authority types when linking bibliographic records to authorities
- [[36603]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36603) UNIMARC: automatically copy the ISNI number over when linking authorities with authorities
- [[35305]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35305) Add XSLT for authority details page in staff interface
- [[37226]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37226) Authority hierarchy tree broken when a child (narrower) term appears under more than one parent (greater) term
- [[37135]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37135) Update MARC21 authority frameworks to Update 38
- [[37134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37134) Update MARC21 authority frameworks to Update 37
- [[37133]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37133) Update MARC21 authority frameworks to Update 36
- [[37132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37132) Update MARC21 authority frameworks to Update 35
- [[37128]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37128) Update MARC21 authority frameworks to Update 34
- [[37125]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37125) Update MARC21 authority frameworks to Update 33
- [[37124]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37124) Update MARC21 authority frameworks to Update 32
- [[37123]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37123) Update MARC21 authority frameworks to Update 31
- [[37122]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37122) Update MARC21 authority frameworks to Update 30

## MARC Bibliographic data support

- [[36055]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36055) Simplify MARC21 fast add framework
- [[36111]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36111) Online resource link should be based on the presence of 856$u (MARC21)
- [[37121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37121) MARC21 Addition to relator terms in technical notice 2024-05-14
- [[37120]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37120) Add heading subfields for 647 (MARC21)

## Notices

- [[38758]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38758) Make formatting date and datetime fields in notices a bit shorter/easier
- [[17976]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17976) TT syntax for notices - Add an equivalence for items.fine
- [[23295]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23295) Automatically debar patrons if SMS or email notice fail
- [[29194]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29194) Patron messaging preferences should be logically ordered
- [[37967]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37967) Allow auto renewals notices to be sent via phone
- [[36758]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36758) We should notify an assignee when they are assigned a ticket
- [[36815]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36815) Add the option to 'Reset to default' in the notices editor
- [[35639]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35639) Long SMS messages are not sent if they exceed the character limitation of the messaging driver

## OPAC

- [[38620]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38620) Non-existent hc-sticky asset included in opac-tags
- [[38595]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38595) Table settings behavior broken on some tables in the OPAC
- [[38594]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38594) Table settings for courses reserves not working in the OPAC
- [[14670]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14670) Add 'cite' option to detail page in OPAC
- [[37221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37221) No way to turn off OverDrive integrations without removing all system preference values
- [[38304]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38304) Remove SaveState options for OPAC tables
- [[38055]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38055) Space between label and value for MARC field 530
- [[38125]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38125) Setting patron reading privacy to "never" will immediately delete all reading history without warning
- [[14007]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14007) Values listed in OpacHiddenItems should not appear in OPAC facets
- [[37742]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37742) My virtual card error message not showing
- [[37391]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37391) QR code for bibliographic record in OPAC should use canonical link
- [[37412]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37412) Style placeholder text in the OPAC
- [[38197]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38197) Remove old version of Bootstrap JS left behind during upgrade
- [[37972]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37972) Allow selection of tab in patron's summary table by query param
- [[36742]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36742) Improve OPAC behavior for instances with only one library, including libraries page
- [[37362]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37362) Do not show the lists button if there are no public lists and opacuserlogin is off
- [[26933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26933) Improve handling of multiple covers on catalog search results in the OPAC
- [[36337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36337) Hiding lists with OpacPublic breaks styling for language list
- [[37841]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37841) Switch OPAC language menu alignment in header and footer
- [[37833]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37833) Incorrect logic controlling display of OPAC language selection menus
- [[37046]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37046) Use template wrapper for OPAC curbside pickup tabs
- [[37048]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37048) Use template wrapper for self checkout page
- [[34486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34486) Hide more OPAC holdings table columns when they are empty
- [[26777]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26777) Give the user the option to display their patron card barcode from the OPAC
- [[36453]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36453) BlockExpiredPatronOpacActions should allow multiple actions options
- [[30873]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30873) "Libraries" link on OPAC should be hideable by system preference
- [[33317]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33317) Add system preference to set meta robots for the OPAC
- [[36651]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36651) Add placeholder text to the search bar in the OPAC
- [[29539]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29539) UNIMARC: authority number in $9 displays for thesaurus controlled fields instead of content of $a

## Packaging

- [[35755]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35755) Upgrade Business::ISBN to at least 3.008 minimum version

## Patrons

- [[38315]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38315) Add a class to expired patrons in patron search
- [[36454]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36454) Provide indication if a patron is expired or restricted on patron search autocomplete
- [[28633]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28633) Add a preferred name field to patrons
- [[23486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23486) TrackLastPatronActivityTriggers should have an option for patron creation
- [[33462]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33462) Force password change for new patrons entered by staff
- [[38283]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38283) Patron search modal has a button opened by a <button> and closed by a </a>
- [[30648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30648) Title is lost in holds history when bibliographic record is deleted
- [[27123]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27123) Add messages to batch patron modification
- [[37807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37807) "Export today's checked in barcodes" not disabled when needed
- [[34608]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34608) Add sort1 and sort2 to patron search results
- [[37881]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37881) Guarantor code broken
- [[36085]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36085) Setting and unsetting the protected flag should be limited to superlibrarian accounts
- [[36169]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36169) Add guarantee to patron categories with category type 'Staff'
- [[36912]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36912) Add more spans/classes to member-display-address-style.inc for additional styling

## Plugin architecture

- [[37495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37495) Add ability to use metadata to filter plugins to run for plugins_nightly.pl
- [[37033]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37033) Allow plugins to load JavaScript on the cart pop-up in the staff interface
- [[35568]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35568) Add a plugin hook to allow modification of notices created via GetPreparedLetter

## Reports

- [[32413]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32413) JSON reports shows inaccurate results with repeated parameters
- [[37328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37328) Cannot delete report after using 'Update and run SQ' button
- [[23685]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23685) Exporting report may consume unlimited memory
- [[37745]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37745) Duplicate class attributes break dropdown items
- [[37740]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37740) Saved reports GROUP tabs don't show the proper panel
- [[37734]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37734) Insert runtime parameter button is not working in Reports
- [[36707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36707) Links on itemnumbers in report should say "item" instead of "record"
- [[37615]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37615) Clean up the form for sending cardnumbers from a report to batch patron modification
- [[37188]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37188) Batch patron modification from report results should be an option when borrowernumber is selected

## REST API

- [[37850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37850) branchillemail missing from public libraries REST endpoint
- [[37809]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37809) Add missing embeds to checkouts endpoints
- [[28965]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28965) Add public routes for lists
- [[37639]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37639) items.stack ( shelving control number ) not included in items API endpoint
- [[30661]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30661) Able to update more hold parameters via REST API
- [[30660]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30660) Add cancellation reason to holds delete endpoint
- [[37253]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37253) Enhance POST /checkouts endpoint to accept barcode or item_id
- [[37902]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37902) Timezone ignored when passing rfc3339 formatted date (search 'q')
- [[37791]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37791) Fix terminology 'Biblio not found'
- [[37686]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37686) render_resource_not_found() and render_resource_deleted() misses
- [[29509]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29509) GET /patrons* routes permissions excessive
- [[36641]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36641) Add an endpoint to list circulation rules
- [[37262]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37262) api/v1/extended_attribute_types does not filter additional fields for unmapped tablenames
- [[37261]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37261) api/v1/extended_attribute_types does not return additional fields for unmapped tablenames
- [[35430]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35430) Add endpoints for managing stock rotation rota's
- [[35197]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35197) Expose additional_field definitions through REST API
- [[36575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36575) Wrong patron can be returned for API validation route

## Searching

- [[37238]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37238) Add table settings to itemsearch results
- [[36991]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36991) Add ability to scan call numbers index/search field
- [[37969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37969) Add missing language code nor (Norwegian/inclusive)
- [[37979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37979) typo in PQF index : index.koha.classification-soruce
- [[14322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14322) Add option to create a shareable link for item searches
- [[32252]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32252) Number of results in a facet do not show after facet selection
- [[34481]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34481) Add IncludeSeeAlsoFromInSearches like IncludeSeeFromInSearches

## Searching - Elasticsearch

- [[30745]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30745) Elasticsearch: Search never returns with after-date and/or before-date in label batch item search
- [[36725]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36725) Add "current publication frequency" to Elasticsearch index mappings (MARC21 310$a)
- [[36798]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36798) Add ability to search across all ISBNs using the ISBN-search
- [[37430]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37430) (Bug 33407 follow-up) ISBD punctuation removal in ES searches
- [[37446]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37446) Home/holding library facets missing user friendly label
- [[36952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36952) Add 370 to authority index (MARC21)
- [[36953]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36953) Add 678 to authority index (MARC21)
- [[36727]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36727) Add incorrect ISSN to Elasticsearch index mappings
- [[33407]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33407) With ES and QueryAutoTruncate on, a search containing ISBD punctuation returns no results

## Serials

- [[37873]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37873) Unable to delete user from routing list or preview/print routing list slip

## SIP2

- [[38073]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38073) Missing use after Bug 25812
- [[18317]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18317) Allow check out of already checked out items through SIP

## Staff interface

- [[38436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38436) Adjust code for column visibility (after DataTables upgrade)
- [[38444]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38444) Bug 34147 follow-up: add tests
- [[38484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38484) Filters on the "Holds to pull" page is broken
- [[38485]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38485) Update column visibility on holdings table correctly
- [[38482]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38482) Disable save state for items tables
- [[38391]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38391) DT's add filters called too many times
- [[36182]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36182) Add vendor column to holdings table
- [[38379]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38379) Remove obsolete Bootstrap classes from installer templates
- [[38312]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38312) Patron form behind fixed header
- [[33484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33484) Ability to remember user's selected table configuration and search filters for tables
- [[38248]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38248) Staff interface detail page item table lookup fails when item has lost status but no claims returned
- [[37980]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37980) Style corrections for installer and onboarding following Bootstrap 5 update
- [[38192]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38192) State not restored correctly on suggestion tables
- [[38191]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38191) Suggestions filters do not expand
- [[38190]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38190) JS error on suggestion page
- [[37954]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37954) Unable to hide barcode column in holdings table
- [[33635]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33635) CSV export display broken diacritics in Excel
- [[37959]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37959) Item circulation alerts table appears to be broken
- [[37812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37812) Adjust Vue modals for Bootstrap 5
- [[37955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37955) Clicking table's 'configure' button no longer opens column settings page properly
- [[37330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37330) LocalCoverImages for items don't show after 33526
- [[35402]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35402) Update the OPAC and staff interface to Bootstrap 5
- [[37732]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37732) Update templates to use Bootstrap styles when alert class comes from the perl script
- [[37733]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37733) Preservation link in the header menu is not styled correctly
- [[37004]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37004) Staff search results: Add a HTML class ( branchcode ) to each item entry in the results list
- [[37755]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37755) Change in Bootstrap5 has broken batch patron modification
- [[37753]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37753) Navigation links when editing authority type subfields are in plain text instead of the tabbed style
- [[37752]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37752) Tabs for MARC subfield structure are missing a class
- [[37739]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37739) Can't delete vendors after Bootstrap 5 update
- [[37697]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37697) CSS from HTML customizations previews bleeds through to rest of page
- [[37452]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37452) The 'Compare matched records' diff view page is missing page-sections
- [[37574]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37574) Add visual indicator that bookings are expired
- [[20411]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20411) Remove StaffDetailItemSelection system preference and make the feature always on
- [[37309]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37309) Improve 'delete' and 'modify' links for items on the bibliographic detail page
- [[2486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=2486) Show user comments in staff interface
- [[37141]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37141) Add option to display completed bookings from patron page
- [[37484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37484) Sorting dates in the housebound deliveries table should work for different date formats
- [[36941]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36941) Highlight that some libraries should not be available at login when StaffLoginRestrictBranchByIP is enabled
- [[36777]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36777) Create a new section for system preferences related to lost item handling
- [[35153]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35153) Convert IntranetmainUserblock system preference to additional contents

## System Administration

- [[38069]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38069) Table settings not saving
- [[38293]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38293) Cannot add Specific OPAC JS or CSS
- [[37662]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37662) Library information - text inconsistencies between the table, edit form, and display page
- [[37888]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37888) Default filtering of background jobs could be improved
- [[28575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28575) Add ability to choose if lost fee is refunded based on when lost fee was paid off
- [[38053]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38053) Change section and description of DefaultLongOverduePatronCategories and DefaultLongOverdueSkipPatronCategories system preferences
- [[36217]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36217) Jobs page include last hour filter does not work
- [[37769]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37769) Fix forms that POST without an op in currency administration
- [[37767]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37767) Fix forms that POST without an op in Authority types
- [[27490]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27490) Rename system preference language to StaffInterfaceLanguages
- [[37765]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37765) Fix forms that POST without an op in systempreferences
- [[37768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37768) Fix form that POSTs without an op in itemtype administration
- [[37513]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37513) Disable 'Delete' button if the record source cannot be deleted
- [[37436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37436) Move EmailPatronWhenHoldIsPlaced to holds policy system preferences
- [[33731]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33731) Allow audio alerts to be used on SCO pages
- [[34185]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34185) Code mixes OpacItemLocation and OPACItemLocation
- [[35044]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35044) Additional fields: Allow for repeatable fields
- [[37419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37419) Deleting the record source deletes the associated biblio_metadata rows
- [[36926]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36926) Move syspref PlaceHoldsOnOrdersFromSuggestions

## Templates

- [[31470]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31470) Incorrect selector for relationship dropdown used in members.js
- [[37946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37946) Double menu when clicking the caret in Z39.50 search
- [[38346]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38346) Make sidebar checkboxes consistent
- [[38380]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38380) Fix other instances of obsolete col-*-offset classes from templates
- [[37910]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37910) Minor spacing issues in the catalog concerns page
- [[30699]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30699) Fix various HTML validity errors in staff interface templates
- [[38305]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38305) Can't delete or archive suggestions
- [[33178]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33178) Use template wrapper for authority and bibliographic subfield entry form tabs
- [[37795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37795) job-progress.inc progress bar broken by Bootstrap5 upgrade
- [[38129]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38129) Add note regarding permissions in suggestion manager search pop-up modal
- [[37945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37945) Links for system preferences subsections don't work
- [[37846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37846) Serial prediction pattern test appears at the bottom of the page
- [[35838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35838) Use template wrapper for tabs: Curbside pickups administration
- [[33907]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33907) Improve translation of title tags: OPAC part 1
- [[32218]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32218) Rephrase: Allow OPAC access to users from this domain to login with this identity provider.
- [[34183]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=34183) Remove MARC format hint from OPACResultsLibrary description
- [[37515]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37515) Add common class to all places where an item type image is shown
- [[36945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36945) Fix several missed instance of breadcrumb WRAPPER use
- [[37759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37759) Duplicated "Set library" menu item caused by bad merge
- [[37748]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37748) In Bootstrap 5 "disabled" class must be on anchor tag, not list item
- [[37578]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37578) Remove the Charges tab from checkout and patron details
- [[33526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33526) Use template wrapper for tabs: bibliographic detail page
- [[33195]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33195) Reindent the bibliographic details page

## Test Suite

- [[38501]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38501) Prevent failures of Koha/Booking.t when running tests on an updated database
- [[38418]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38418) SIP/Transaction.t fails if wrong `dateformat` set
- [[38043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38043) KohaTimes filter is missing tests
- [[38049]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38049) Admin/RecordSources_spec.ts is still failing randomly
- [[37917]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37917) RecordSources_spec.ts is failing randomly
- [[37898]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37898) All db dependent tests should run within a transaction
- [[37929]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37929) Cypress tests for agreements aren't all running
- [[37870]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37870) UI/Form/Builder/Item.t and Biblio.t are still failing randomly (cn_source sort)

## Tools

- [[37944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37944) Object deletion should be logged with a JSON diff of changes, implement for items
- [[37943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37943) Object creation should be logged with a JSON diff of changes, implement for items
- [[37522]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37522) Logging item modification should record the original version of the item
- [[37103]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37103) Link log viewer options to corresponding system preference
- [[36083]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36083) Not able to create customizable areas to intranet home pages that are library specific
- [[35100]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=35100) Items assigned to StockRotation do not advance if a hold is triggered before the initial transfer
- [[37779]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37779) Fix forms that POST without an op in tag moderation
- [[37859]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37859) Tabs for record comments are in plain text (related to Bootstrap 5 update)
- [[37785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37785) Remove dead code in tools/letter.tt that looks like a form that would POST without an op
- [[36132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36132) Allow users to delete multiple patron lists at once on any page

## Web services

- [[38605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38605) t/db_dependent/Koha/OAIHarvester.t fails with wrong date format
- [[36315]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36315) ILSDI GetRecord speed improvement
- [[31161]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31161) OAI-PMH - Honour OpacHiddenItems system preferences

## Z39.50 / SRU / OpenSearch Servers

- [[36996]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36996) Add a system preference to mark items unavailable in Z39.50 responder


