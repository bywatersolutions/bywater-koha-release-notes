
# Release Notes for montgomery-v21.05.12-01

## Acquisitions

- [[29895]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29895) Button [Add multiple items] stops responding when it's pressed and some multiple items added to basket
- [[29570]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29570) Unable to sort summary column of pending_orders table on parcel.pl by summary column
- [[29670]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29670) Restore functionality broken by bug 27708 for AcqCreateItem set to "placing an order"
- [[29464]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29464) GET /acquisitions/orders doesn't honour sorting
- [[24866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24866) Display budget hierarchy in the budget dropdown menu used when placing a new order
- [[29419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29419) Suggest for purchase clears item type, quantity, library and reason if bib exists
- [[28855]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28855) Purging suggestions test should not be on timestamp

## Architecture, internals, and plumbing

- [[29420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29420) HTTP status code incorrect when calling error pages directly under Plack/PSGI
- [[29956]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29956) Cookie can contain plain text password
- [[29966]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29966) SCO Help page passes flags while not needing authentication
- [[29785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29785) Koha::Object->messages must be renamed
- [[29809]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29809) StockRotationItems->itemnumber is poorly named
- [[29646]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29646) Bad or repeated opac-password-recovery attempt crashes on wrong borrowernumber
- [[29764]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29764) EmbedItems RecordProcessor filter POD incorrect
- [[29806]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29806) ->pickup_locations should always be called in scalar context
- [[18320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18320) patroncards/edit-layout.pl raises warnings
- [[29336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29336) Some authorised_value FKs are too short
- [[29758]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29758) CGI::param in list context in boraccount.pl warning
- [[18540]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18540) koha-indexdefs-to-zebra.xsl introduces MARC21 stuff into UNIMARC xslts
- [[29812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29812) C4::Context not included, but used in Koha::Token
- [[29804]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29804) Koha::Hold->is_pickup_location_valid explodes if empty list of pickup locations
- [[29914]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29914) check_cookie_auth not strict enough
- [[29702]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29702) all_libraries routine in library groups make a DB call per member of group
- [[29789]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29789) Unused $error in cataloguing/additem.pl
- [[29494]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29494) html-template-to-template-toolkit.pl no longer required
- [[29427]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29427) Debug mode not honoured in SMTP transport

## Authentication

- [[29487]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29487) Set autocomplete off for userid/password fields at login

## Bywater Only

- NOT IN BUGZILLA - Removing unit tests that are failing do to Koha::Logger issues
- NOT IN BUGZILLA - GitHub Actions - Switch koah-dpkg from 21.05 to 21.11
- NOT IN BUGZILLA - Remove failing Selenium tests, they pass locally
- NOT IN BUGZILLA - Fix translations for Koha 21.05.11
- NOT IN BUGZILLA - Increment version number for 21.05.10 release
- NOT IN BUGZILLA - Fix translations for Koha 21.05.09
- NOT IN BUGZILLA - DBRev 21.05.08.002
- NOT IN BUGZILLA - Translation fixes for 21.05.08

## Cataloging

- [[29511]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29511) While editing MARC records, blank subfields appear in varying order
- [[9565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=9565) Deleting a record should alert or fail if there are current subscriptions
- [[28853]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28853) Textarea in biblio record editor breaks authority plugin

## Circulation

- [[28271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28271) Add the ability to set a new lost status when a claim is resolved
- [[27296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27296) Return claims should be filtered by default to show unresolved claims
- [[29495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29495) Issue link is lost in return claims when using 'MarkLostItemsAsReturned'
- [[11750]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11750) Overdue report does not limit patron attributes
- [[29476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29476) Earliest renewal date is displayed wrong in circ/renew.pl for issues with auto renewing

## Command-line Utilities

- [[29054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29054) Stop warns from advance_notices.pl if not running in verbose mode

## Custom For Instance

- [[29474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29474) Automatic renewals cronjob is slow on systems with large numbers of reserves
- [[27032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27032) CanBookBeRenewed is not understandable and needs refactoring
- [[29507]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29507) Speed up auto renew cronjob via parallel processing
- [[29483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29483) AllowRenewalIfOtherItemsAvailable has poor performance for records with many items
- [[29130]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29130) Holds queue is empty while holds queue builder is running
- [[28974]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28974) Add pagination to holds queue viewer
- [[29015]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29015) Add option to limit Holds Queue report by shelving location / collection
- [[29100]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29100) Add checkouts data loop to predue notices script ( advance_notices.pl )
- [[29058]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29058) Add option to not load existing holds table automatically
- [[26587]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26587) Cache libraries in Branches TT plugin to improve performance
- [[29454]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29454) Stash itemtypes in plugin objects to reduce DB calls

## Database

- [[30065]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30065) Correct errors in backporting of database updates

## Fines and fees

- [[29952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29952) Filter Paid Transactions Broken on Transactions tab in Staff
- [[29385]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29385) Add missing cash register support to SIP2
- [[29457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29457) Fee Cancellation records the wrong manager_id
- [[28481]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28481) Register details "Older transactions" search does not include the selected day in the "To" field in date range
- [[27801]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27801) Entering multiple lines of an item in Point of Sale can make the Collect Payment field off

## Hold requests

- [[29043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29043) Items are processed but not displayed on request.pl before a patron is selected
- [[21652]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21652) reserves.waitingdate is set to current date by printing new hold slip
- [[3142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=3142) Standardize how OPAC and staff determine requestability
- [[29736]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29736) Error when placing a hold for a club without members
- [[29553]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29553) Holds: Can't call method "notforloan" on an undefined value when placing a hold
- [[29349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29349) Item-level holds should assume the same pickup location as bib-level holds
- [[29115]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29115) Placing a club hold is not showing warnings when unable to place a hold

## I18N/L10N

- [[29040]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29040) Uninitialized value warning in Languages.pm

## ILL

- [[28932]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28932) Backend overriding status_graph element causes duplicate actions

## Lists

- [[29601]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29601) The list download option ISBD is useless when you cleared OPACISBD

## Notices

- [[29943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29943) Fix typo in notices yaml file
- [[29557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29557) Auto renew notices should handle failed renewal due to patron expiration
- [[29381]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29381) Auto-renewal digest messages are sent on every cron run

## OPAC

- [[29320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29320) Use OverDrive availability API V2
- [[30045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30045) SCO print slip is broken
- [[29840]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29840) opac-reserve explodes if invalid biblionumber is passed
- [[29544]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29544) A patron can set everybody's checkout notes
- [[17127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17127) Can't hide MARC21 500 and others with NotesToHide
- [[29604]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29604) Term highlighting adds unwanted pseudo element in the contentblock of OPAC details page
- [[29696]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29696) "Suggest for purchase" missing biblio link
- [[28698]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28698) News for all displays in all locations
- [[29611]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29611) Clubs enrollment layout problem in the OPAC
- [[29556]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29556) MARC21slim2MODS.xsl broken by duplicate template name "part"
- [[29036]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29036) Accessibility: OPAC buttons don't have sufficient contrast

## Packaging

- [[29881]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29881) Remove SQLite2 dependency
- [[28926]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28926) Update cpanfile for Mojolicious::Plugin::OpenAPI v2.16

## Patrons

- [[22993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22993) Messaging preferences not set for patrons imported through API
- [[30090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30090) Don't export action buttons from patron results

## Plugin architecture

- [[29931]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29931) Script plugins-enable.pl should check the cookie status before running plugins

## Reports

- [[28977]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28977) Most-circulated items (cat_issues_top.pl) is failing with SQL Mode ONLY_FULL_GROUP_BY
- [[29786]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29786) Holds to pull report shows incorrect item for item level holds
- [[29530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29530) When NumSavedReports is set, show value in pull down of entries
- [[29680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29680) Reports menu 'Show SQL code' wrong border radius
- [[29729]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29729) If serials_stats.pl returns no results dataTables get angry
- [[29488]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29488) NumSavedReports system preference doesn't work

## REST API

- [[29508]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29508) GET /patrons/:patron_id should use Koha::Patrons->search_limited
- [[29506]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29506) objects.search should call search_limited if present
- [[29503]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29503) GET /patrons should use Koha::Patrons->search_limited
- [[29018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29018) Deleting patrons from REST API doesn't do any checks or move to deletedborrowers

## Searching - Elasticsearch

- [[29436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29436) Cannot reorder facets in staff interface elasticsearch configuration

## Self checkout

- [[28735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28735) Self-checkout users can access opac-user.pl for sco user when not using AutoSelfCheckID
- [[29543]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29543) Self-checkout allows returning everybody's loans

## Serials

- [[28216]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28216) Fix vendor list group by in serials statistics wizard

## SIP2

- [[29754]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29754) Patron fines counted twice for SIP when NoIssuesChargeGuarantorsWithGuarantees is enabled

## Staff Client

- [[29541]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29541) Patron images can be accessed with just 'catalogue' permission
- [[29903]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29903) Message deletion possible from different branch
- [[29542]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29542) User with 'catalogue' permission can view everybody's (private) virtualshelves
- [[29540]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29540) Accounts with just 'catalogue' permission can modify/delete holds

## System Administration

- [[29591]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29591) Add autorenew_checkouts to BorrowerMandatory/Unwanted fields system preferences

## Templates

- [[30082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30082) Bibliographic details tab missing when user can't add local cover image
- [[29932]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29932) Phase out jquery.cookie.js: bibs_selected (Browse selected records)
- [[29933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29933) Fix stray usage of jquery.cookie.js plugin
- [[29967]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29967) Increase size of description fields for authorized values in templates
- [[29807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29807) Branches template plugin doesn't handle empty lists correctly
- [[26102]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26102) Javascript injection in intranet search
- [[29571]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29571) Mainpage : "All libraries" pending suggestions are visible only if the current library has suggestions
- [[29580]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29580) Misplaced closing 'td' tag in overdue.tt
- [[29529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29529) Fix \n in hint on Koha to MARC mappings
- [[29513]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29513) Accessibility: Staff Client - Convert remaining breadcrumbs sections from div to nav blocks
- [[29514]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29514) ILL requests: Remove extraneous &rsaquo; HTML entity from breadcrumbs

## Test Suite

- [[29862]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29862) TestBuilder.t fails with ES enabled
- [[29838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29838) No string interpolation when expected in t/db_dependent/ImportBatch.t
- [[29884]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29884) Missing test in api/v1/patrons.t

## Tools

- [[29722]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29722) Add some diversity to sample quotes
- [[29156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29156) File missing warning in Koha::UploadedFile should be for permanent files only
- [[28832]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28832) [21.05] Batch modification always clears permanent_location if it is mapped in frameworks
- [[29808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29808) Stock rotation fails to advance when an item is checked out from the branch that is the next stage
- [[29521]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29521) Patron Club name hyperlinks not operational + weird CSS behavior

## Web services

- [[29484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29484) ListSets doesn't return noSetHierarchy when appropriate

## Z39.50 / SRU / OpenSearch Servers

- [[19865]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19865) Side scroll bar in z39.50 MARC view


