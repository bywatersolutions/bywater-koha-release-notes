
# Release Notes for masscat-v21.05.13-01

## Acquisitions

- [[29287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29287) Display of funds on acquisitions home is not consistent with display on funds page
- [[29895]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29895) Button [Add multiple items] stops responding when it's pressed and some multiple items added to basket
- [[29570]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29570) Unable to sort summary column of pending_orders table on parcel.pl by summary column
- [[29670]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29670) Restore functionality broken by bug 27708 for AcqCreateItem set to "placing an order"
- [[24866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24866) Display budget hierarchy in the budget dropdown menu used when placing a new order
- [[29419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29419) Suggest for purchase clears item type, quantity, library and reason if bib exists

## Architecture, internals, and plumbing

- [[29420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29420) HTTP status code incorrect when calling error pages directly under Plack/PSGI
- [[29886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29886) Add Koha::Suggestions->search_limited
- [[29687]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29687) Get rid of an uninitialized warning in XSLT.pm
- [[29956]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29956) Cookie can contain plain text password
- [[30115]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30115) Uninitialized value warning in C4/Output.pm
- [[29625]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29625) Wrong var name in Koha::BiblioUtils get_all_biblios_iterator
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

## Browser compatibility

- [[22671]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22671) Warn the user in offline circulation if applicationCache isn't supported

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions: Build our own base.tgz for use with koha-dpkg
- NOT IN BUGZILLA - Create 'offline circ' log file
- NOT IN BUGZILLA - Removing unit tests that are failing do to Koha::Logger issues
- NOT IN BUGZILLA - GitHub Actions - Switch koah-dpkg from 21.05 to 21.11
- NOT IN BUGZILLA - Remove failing Selenium tests, they pass locally
- NOT IN BUGZILLA - Fix translations for Koha 21.05.13
- NOT IN BUGZILLA - Fix translations for Koha 21.05.11
- NOT IN BUGZILLA - Increment version number for 21.05.10 release
- NOT IN BUGZILLA - Fix translations for Koha 21.05.09
- NOT IN BUGZILLA - DBRev 21.05.08.002

## Cataloging

- [[29511]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29511) While editing MARC records, blank subfields appear in varying order

## Circulation

- [[30222]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30222) Auto_renew_digest still sends every day when renewals are not allowed
- [[30155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30155) We shouldn't calculate get_items_that_can_fill when we don't have any holds
- [[29220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29220) Minor fixes and improved code readability in circulation.pl
- [[28271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28271) Add the ability to set a new lost status when a claim is resolved
- [[27296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27296) Return claims should be filtered by default to show unresolved claims
- [[29495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29495) Issue link is lost in return claims when using 'MarkLostItemsAsReturned'
- [[11750]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11750) Overdue report does not limit patron attributes
- [[29476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29476) Earliest renewal date is displayed wrong in circ/renew.pl for issues with auto renewing

## Command-line Utilities

- [[29054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29054) Stop warns from advance_notices.pl if not running in verbose mode

## Database

- [[30065]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30065) Correct errors in backporting of database updates

## Fines and fees

- [[30132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30132) overdue_notices.pl POD is incorrect regarding passing options
- [[28663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28663) One should not be able to apply a discount to a VOID accountline
- [[29952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29952) Filter Paid Transactions Broken on Transactions tab in Staff
- [[29385]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29385) Add missing cash register support to SIP2
- [[29457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29457) Fee Cancellation records the wrong manager_id

## Hold requests

- [[30266]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30266) Holds marked waiting with a holdingbranch that does not match can cause loss of pickup locations
- [[29043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29043) Items are processed but not displayed on request.pl before a patron is selected
- [[21652]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21652) reserves.waitingdate is set to current date by printing new hold slip
- [[3142]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=3142) Standardize how OPAC and staff determine requestability
- [[29736]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29736) Error when placing a hold for a club without members
- [[29553]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29553) Holds: Can't call method "notforloan" on an undefined value when placing a hold

## I18N/L10N

- [[29596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29596) Add Yiddish language

## ILL

- [[28932]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28932) Backend overriding status_graph element causes duplicate actions

## Notices

- [[29943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29943) Fix typo in notices yaml file
- [[29557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29557) Auto renew notices should handle failed renewal due to patron expiration
- [[29381]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29381) Auto-renewal digest messages are sent on every cron run

## OPAC

- [[29795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29795) If branch is mandatory on patron self registration form, the pull down should default to empty
- [[29706]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29706) When placing a request on the opac, the user is shown titles they cannot place a hold on
- [[29320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29320) Use OverDrive availability API V2
- [[30045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30045) SCO print slip is broken
- [[29840]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29840) opac-reserve explodes if invalid biblionumber is passed
- [[29544]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29544) A patron can set everybody's checkout notes
- [[17127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17127) Can't hide MARC21 500 and others with NotesToHide
- [[29604]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29604) Term highlighting adds unwanted pseudo element in the contentblock of OPAC details page
- [[29696]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29696) "Suggest for purchase" missing biblio link

## Packaging

- [[30084]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30084) Remove dependency of liblocale-codes-perl
- [[29881]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29881) Remove SQLite2 dependency
- [[28926]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28926) Update cpanfile for Mojolicious::Plugin::OpenAPI v2.16

## Patrons

- [[22993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22993) Messaging preferences not set for patrons imported through API
- [[30098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30098) Patron search redirects when one result on any page of results
- [[28576]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28576) Add patron image in patron detail section does not specify image size limit
- [[30090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30090) Don't export action buttons from patron results

## Plugin architecture

- [[29931]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29931) Script plugins-enable.pl should check the cookie status before running plugins
- [[30072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30072) Add more holds hooks

## Reports

- [[26269]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26269) Overdues: Download file doesn't match result in staff interface when due date filters or 'show any available items currently checked out' are used
- [[30129]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30129) 500 error when search reports by date
- [[28977]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28977) Most-circulated items (cat_issues_top.pl) is failing with SQL Mode ONLY_FULL_GROUP_BY
- [[29530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29530) When NumSavedReports is set, show value in pull down of entries
- [[29680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29680) Reports menu 'Show SQL code' wrong border radius
- [[29729]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29729) If serials_stats.pl returns no results dataTables get angry

## REST API

- [[30133]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30133) Pagination broken on pickup_locations routes when AllowHoldPolicyOverride=1
- [[29877]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29877) MaxReserves should be enforced consistently between staff interface and API
- [[29508]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29508) GET /patrons/:patron_id should use Koha::Patrons->search_limited
- [[29506]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29506) objects.search should call search_limited if present
- [[29503]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29503) GET /patrons should use Koha::Patrons->search_limited
- [[29018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29018) Deleting patrons from REST API doesn't do any checks or move to deletedborrowers

## Searching - Elasticsearch

- [[30153]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30153) FindDuplicate ElasticSearch should not use lowercase 'and'
- [[27770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27770) ES: Deprecated aggregation order key [_term] used, replaced by [_key]
- [[29436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29436) Cannot reorder facets in staff interface elasticsearch configuration

## Self checkout

- [[28735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28735) Self-checkout users can access opac-user.pl for sco user when not using AutoSelfCheckID
- [[29543]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29543) Self-checkout allows returning everybody's loans

## SIP2

- [[29754]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29754) Patron fines counted twice for SIP when NoIssuesChargeGuarantorsWithGuarantees is enabled

## Staff Client

- [[30164]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30164) Header filter not taken into account on the cities view
- [[29541]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29541) Patron images can be accessed with just 'catalogue' permission
- [[29903]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29903) Message deletion possible from different branch
- [[29542]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29542) User with 'catalogue' permission can view everybody's (private) virtualshelves
- [[29540]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29540) Accounts with just 'catalogue' permission can modify/delete holds

## System Administration

- [[29591]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29591) Add autorenew_checkouts to BorrowerMandatory/Unwanted fields system preferences

## Templates

- [[29853]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29853) Text needs HTML filter before KohaSpan filter
- [[30082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30082) Bibliographic details tab missing when user can't add local cover image
- [[29932]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29932) Phase out jquery.cookie.js: bibs_selected (Browse selected records)
- [[29933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29933) Fix stray usage of jquery.cookie.js plugin
- [[29967]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29967) Increase size of description fields for authorized values in templates
- [[29807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29807) Branches template plugin doesn't handle empty lists correctly
- [[26102]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26102) Javascript injection in intranet search
- [[29571]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29571) Mainpage : "All libraries" pending suggestions are visible only if the current library has suggestions

## Test Suite

- [[30203]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30203) Prevent data loss when running Circulation.t without prove
- [[29862]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29862) TestBuilder.t fails with ES enabled
- [[29838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29838) No string interpolation when expected in t/db_dependent/ImportBatch.t
- [[29884]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29884) Missing test in api/v1/patrons.t

## Tools

- [[29722]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29722) Add some diversity to sample quotes
- [[29156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29156) File missing warning in Koha::UploadedFile should be for permanent files only
- [[28832]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28832) [21.05] Batch modification always clears permanent_location if it is mapped in frameworks
- [[29808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29808) Stock rotation fails to advance when an item is checked out from the branch that is the next stage

## Z39.50 / SRU / OpenSearch Servers

- [[19865]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19865) Side scroll bar in z39.50 MARC view


