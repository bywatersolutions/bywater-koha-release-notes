
# Release Notes for bywater-v22.11.06-02

## About

- [[32665]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32665) warnPrefRequireChoosingExistingAuthority condition incorrect in about.pl
- [[32687]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32687) About may list version of SQL client in container, not actual server
- [[30808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30808) Release team 23.05

## Acquisitions

- [[33653]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33653) Search for late orders can show received order lines
- [[33262]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33262) When an ordered record is deleted, we lose all information on what was ordered
- [[32484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32484) Enable framework plugins when UseACQFrameworkForBiblioRecords is set
- [[33238]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33238) Error adding suggestion to basket as non-superlibrarian (Bug 29886 follow-up)
- [[31722]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31722) Don't show EDIFACT note on basket group page if EDIFACT is turned off
- [[33414]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33414) Dates displayed in ISO format in orders by fund
- [[32437]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32437) When adding to a basket form a staged file and matching the imported records are ignored when set to overwrite
- [[33082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33082) Add yellow buttons and page sections to 'copy order' pages
- [[31056]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31056) Unable to 'Close and export as PDF' a basket group
- [[33002]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33002) 'Archive selected' button missing?
- [[32603]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32603) Suggester category in Suggestions management
- [[32401]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32401) x-koha-query cannot contain non-ISO-8859-1 values
- [[20473]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20473) "Item information" tab should not appear if item is not created upon placing an order
- [[32382]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32382) Fund input misaligned on invoice summary page
- [[32531]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32531) Filter 'Include archived' no longer shows non-archived suggestions
- [[32417]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32417) Cannot insert order: Mandatory parameter biblionumber is missing
- [[31984]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31984) TaxRate system preference - add note about updating vendor tax rates where required
- [[15348]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15348) Change/Edit estimated delivery date per order line
- [[32167]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32167) When adding an order from a a staged file without item fields we only add price if there is a vendor discount
- [[32045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32045) Cannot order multiple from staged file
- [[32171]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32171) Order prices not populated when adding to a basket from a staged file
- [[32166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32166) When adding to a basket from a staged file we may use the wrong inputs
- [[31711]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31711) When creating order lines "From a new file" you are no longer redirected to acq after import
- [[31840]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31840) Incorrect warning that order total amount exceeds allowed budget when editing existing order
- [[32076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32076) Form for editing a basket group is misaligned
- [[27017]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27017) Add further defensive coding to EDI Invoice handling
- [[25763]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25763) Allow update of order fund after receipt
- [[31115]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31115) Additional fields for invoices
- [[31569]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31569) Remove GetImportsRecordRange from acqui/addorderiso2709
- [[31257]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31257) Add a new English 1 page layout to export a basket as PDF
- [[31333]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31333) Add the ability to limit purchase suggestions by patron category
- [[31586]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31586) Log basket number as object when an email order is sent
- [[27817]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27817) Enhance display of title information throughout acquisitions
- [[31374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31374) Add a non-public note column to the suggestions table
- [[31388]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31388) Add select2 to fund selection in new order form
- [[31377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31377) Add basket's internal note to tables on vendor search result list
- [[31017]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31017) Add type field for vendors
- [[31158]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31158) Can't filter suggestions by date ranges
- [[28269]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28269) Order search should be possible with ISSN too
- [[10086]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10086) No way to go back to the basket on uncertain prices page
- [[13614]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13614) Replace usage of YUI on basket groups page

## Architecture, internals, and plumbing

- [[33898]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33898) background_jobs_worker.pl may leave defunct children processes for extended periods of time
- [[33488]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33488) Library transfer limits should have an index on fromBranch
- [[33489]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33489) The borrowers table should have indexes on default patron search fields
- [[33710]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33710) Ignore howto files
- [[33167]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33167) Cleanup staff interface catalog details page
- [[33053]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33053) Tables item_groups and recalls have a biblio_id column with a default of 0
- [[32990]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32990) Possible deadlock in C4::ImportBatch::_update_batch_record_counts
- [[33066]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33066) We need a KohaTable Vue component
- [[33447]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33447) Add caching to Biblio->pickup_locations
- [[32992]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32992) Move background worker script to misc/workers
- [[33229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33229) Patron reading history should be cleared when privacy set to never
- [[33088]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33088) background-job-progressbar.js no longer needed in batch_record_modification.tt
- [[32418]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32418) CRASH: Can't call method "unblessed" on an undefined value at cataloguing/additem.pl
- [[32716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32716) update NGINX config examples to increase proxy_buffer_size
- [[33289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33289) Vue - Add API client class to interact with svc/config/systempreferences
- [[33367]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33367) tmp/modified_authorities/README.txt seems useless
- [[33368]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33368) borrowers.flags is about to reach the limit
- [[32794]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32794) mailto links in 856 can be incorrectly formed by XSLT
- [[33083]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33083) Handle generic collection of records methods
- [[33080]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33080) Add helpers that return result_set for further processing
- [[32991]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32991) Improve our Dialog component and remove routes for deletion
- [[32781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32781) CreateEHoldingsFromBiblios not dealing with non-existent package correcly
- [[30920]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30920) Add caching to C4::Biblio::GetAuthorisedValueDesc
- [[32975]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32975) Error in package.json's definition of css:build vs css:build:prod
- [[32609]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32609) Remove compiled files from src
- [[32472]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32472) [21.11 CRASH] The method Koha::Item->count is not covered by tests
- [[32585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32585) Followup on Bug 32583 - fix some variable references
- [[32939]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32939) Have generic fetch functions in vue modules
- [[32806]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32806) Some Vue files need to be moved for better reusability
- [[32935]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32935) basketgroup.js is not longer used and should be removed
- [[32978]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32978) 'npm install' fails in ktd on aarch64, giving unsupported architecture error for node-sass
- [[23247]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23247) Use EmbedItems in opac-MARCdetail.pl
- [[32922]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32922) Remove space in shebang
- [[30310]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30310) Replace Moment.js with Day.js
- [[31095]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31095) Remove Koha::Patron::Debarment::GetDebarments and use $patron->restrictions in preference
- [[32583]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32583) Restore display of only one item in catalogue/moredetails
- [[32582]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32582) Mailmap maps to wrong email address
- [[32528]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32528) Koha::Item->safe_to_delete should short-circuit earlier
- [[32529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32529) Holds in processing should block item deletion
- [[32330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32330) Table background_jobs is missing indexes
- [[32394]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32394) Long tasks queue is never used
- [[32422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32422) Hardcoded paths in _common.scss prevent using external node_modules
- [[32224]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32224) Add cypress and prettier to the yarn commands
- [[32248]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32248) t/00-checkdatabase-version.t should be removed
- [[32154]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32154) Missing primary key on erm_user_roles table
- [[32223]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32223) package.json script paths too specific
- [[32151]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32151) [WARN] Use of uninitialized value in numeric ne (!=) at C4/Ris.pm line 834.
- [[32163]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32163) ErmUserRole has wrong koha_object[s]_class
- [[32161]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32161) ErmEholdingsPackagesAgreement has wrong koha_object_class
- [[32162]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32162) erm_eholdings_packages_agreements does not have a primary key
- [[12758]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12758) Failure when loading or parsing XSLT stylesheets over HTTPS
- [[32119]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32119) Cannot add new guarantee
- [[31889]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31889) Insert 952 tags in correct order when embedding items
- [[31517]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31517) C4::Tags should use Koha::Tags objects instead of raw SQL
- [[27259]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27259) HomeOrHoldingBranch is not used in all places
- [[29672]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29672) Increase performance of Koha::Plugins->call
- [[25716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25716) Add ability to specify additional options in koha-conf.xml for z3950_responder.pl when using koha-z3950-responder
- [[31871]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31871) Due date not shown on items tab
- [[28375]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28375) Inefficiencies in fetching COinS
- [[31842]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31842) admin/branches: DT search generates js error on col.data.split
- [[31437]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31437) ModItemTransfer triggers indexing twice
- [[30168]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30168) Use checkout object in GetSoonestRenewDate
- [[31519]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31519) Unused template parameters in request.pl
- [[31666]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31666) Add job progress bar to stage-marc-import.pl
- [[28186]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28186) Use Koha::Authority in C4::AuthoritiesMarc::AddAuthority
- [[15545]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15545) Remove remainders of unfinished reqholdnotes functionality
- [[29744]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29744) Harmonize psgi/plack detection methods
- [[31468]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31468) Koha::Logger should prefix interface with 'plack'
- [[30982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30982) Use the REST API for background job list view
- [[31389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31389) Calculate user permissions in separate function
- [[31590]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31590) Remove Text::CSV::Unicode
- [[30921]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30921) Replace use of C4::XSLT::transformMARCXML4XSLT with RecordProcessor
- [[31535]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31535) Fix a staff warn or two
- [[29184]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29184) Warn from chargelostitem when no replacement cost set for item
- [[31396]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31396) OPAC shelf browser broken after removal GetItemsInfo from opac-detail
- [[31351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31351) Worker dies on reindex job when operator last name/first name/branch name contains non-ASCII chars
- [[27272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27272) Move C4::Items::GetItemsInfo to Koha namespace
- [[29697]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29697) Replace GetMarcBiblio occurrences with $biblio->metadata->record
- [[30016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30016) Remove GetOpenIssue subroutine
- [[31315]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31315) Remove GetItemsInfo from moredetail
- [[24295]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24295) C4::Circulation::GetTransfers should be removed, use Koha::Item->get_transfer instead
- [[31313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31313) Remove GetItemsInfo from opac-detail
- [[31321]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31321) Remove GetItemsInfo from catalogue/detail.pl
- [[29939]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29939) Replace opac-ratings-ajax.pl with a new REST API route
- [[29955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29955) Move C4::Acquisition::populate_order_with_prices to Koha::Acquisition::Order
- [[27342]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27342) Improve readability and improvement of C4::Auth::get_template_and_user
- [[30901]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30901) Add template method to be able to look up renewal data in Koha slips and notices
- [[31312]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31312) Remove GetItemsInfo from misc/migration_tools/rebuild_zebra.pl
- [[31318]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31318) Remove GetItemsInfo from serials/routing-preview
- [[31314]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31314) Remove GetItemsInfo from opac-reserve.pl
- [[31320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31320) Remove GetItemsInfo from virtualshelves/sendshelf.pl
- [[31317]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31317) Remove GetItemsInfo from opac-tags
- [[31310]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31310) Remove GetItemsInfo from catalogue/imageviewer
- [[31309]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31309) Remove GetItemsInfo from basket/sendbasket
- [[31328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31328) Make Koha::Item->get_transfer* use Koha::Item::Transfers->filter_by_current
- [[31308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31308) Remove GetItemsInfo from basket/basket
- [[31307]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31307) already_reserved never used in opac/opac-reserve.pl
- [[31311]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31311) Remove GetItemsInfo from labels/label-item-search
- [[31316]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31316) Remove GetItemsInfo from opac-sendbasket
- [[31319]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31319) Remove GetItemsInfo from tags/list.pl
- [[31306]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31306) Add Koha::Items->search_ordered method
- [[30543]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30543) Decouple DumpSearchQueryTemplate from other template dump preferences
- [[31183]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31183) Add Koha::Item::Transfers->filter_by_current
- [[31305]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31305) Useless "type" parameter passed in detail.tt
- [[30874]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30874) Simplify patron category handling in memberentry
- [[31288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31288) Check userenv in ->disown_or_delete
- [[31274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31274) OPACSuggestionAutoFill must be 1 or 0
- [[30984]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30984) Action logs should log the cronjob script name that generated the given log
- [[30612]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30612) Add account_lines method to Koha::[Old::]Checkout
- [[30578]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30578) We should drop circ/ysearch.pl in preference to using the REST API's
- [[31133]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31133) TestBuilder fragile on virtual fks
- [[31140]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31140) TestBuilder.t is failing on item groups modules
- [[30275]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30275) Checkout renewals should be stored in their own table
- [[23991]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23991) Move SearchSuggestion to Koha::Suggestions
- [[30823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30823) Recalls should use 'FILL' in action logs
- [[30822]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30822) BatchCommit does not deal with indexation correctly
- [[30420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30420) Rename Koha::Patron->get_overdues with ->overdues
- [[29623]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29623) Cache effective circulation rules
- [[30824]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30824) Improve performance of BatchCommitItems
- [[30813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30813) Refactor TransformMarcToKoha to remove TransformMarcToKohaOneField
- [[30876]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30876) recalls/recalls_to_pull.pl introduces an incorrect use of ->search in list context

## Authentication

- [[32354]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32354) Handle session_state param given by OAuth identity provider
- [[31378]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31378) Add a generic OAuth2/OIDC client implementation
- [[32178]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32178) query parameters in check_api_auth lets anyone assume a user id
- [[32138]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32138) OIDC client uses backwards default mapping
- [[32141]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32141) New and edit identity provider UIs inconsistent
- [[32139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32139) "Update on login" setting not set when creating domain from new IdP page
- [[32066]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32066) 2FA: User could get stuck temporarily on login screen when disabling pref
- [[31495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31495) Allow viewing CMS pages when enforcing GDPR policy
- [[30588]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30588) Add the option to require 2FA setup on first staff login
- [[25936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25936) Notify users if their password has changed
- [[28787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28787) Send a notice with the TOTP token

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Update BASE_URL to work with both koha-bywater and koha-bywater-future
- NOT IN BUGZILLA - Remove all ERM cypress tests for now
- NOT IN BUGZILLA - Re-enable building docker images
- NOT IN BUGZILLA - Fix test exectuable
- NOT IN BUGZILLA - Remove t/db_dependent/selenium/system_preferences_search.t
- NOT IN BUGZILLA - Fix translations for Koha 22.11.06
- NOT IN BUGZILLA - Fix translations for Koha 22.11.05
- NOT IN BUGZILLA - Fix translations for Koha 22.11.03
- NOT IN BUGZILLA - Fix translations for Koha 22.11.03
- NOT IN BUGZILLA - RMaint: Built resources
- NOT IN BUGZILLA - Built files
- NOT IN BUGZILLA - Fix translations for Koha 22.11.02
- NOT IN BUGZILLA - Compile eRM Vue app
- NOT IN BUGZILLA - Add executable flag to 221101000.pl
- NOT IN BUGZILLA - Fix translations for Koha 22.11.01
- NOT IN BUGZILLA - 22.11.00: Update kohastructure.sql
- NOT IN BUGZILLA - 22.11.00: Update history.txt
- NOT IN BUGZILLA - 22.11.00: Update contributors.yaml
- NOT IN BUGZILLA - 22.11.00: Update .mailmap
- NOT IN BUGZILLA - Bug 37159: Updated tab style
- NOT IN BUGZILLA - Bug 28739: Execute the letter processing inside a transaction
- NOT IN BUGZILLA - Koha 22.06 - start of a new dev cycle

## Cataloging

- [[20256]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20256) Add ability to limit editing of items to home library or library group
- [[28328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28328) Editing a record can cause an ISE if data too long for column
- [[33445]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33445) Regression - Replacing authority via Z39.50 will not search for anything but the value from the existing authority
- [[33655]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33655) z39.50 search no longer shows search in progress
- [[33591]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33591) Cannot merge bibliographic records
- [[32253]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32253) Advanced cataloging editor doesn't load every line initially
- [[32874]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32874) Fix cataloguing/value_builder/unimarc_field_700-4.pl
- [[32865]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32865) Clean up cataloguing/value_builder/unimarc_field_146a.pl
- [[32870]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32870) Fix cataloguing/value_builder/unimarc_field_225a_bis.pl
- [[32869]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32869) Fix cataloguing/value_builder/unimarc_field_210c.pl
- [[32873]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32873) Fix cataloguing/value_builder/unimarc_field_686a.pl
- [[32868]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32868) Fix cataloguing/value_builder/unimarc_field_210c_bis.pl
- [[32871]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32871) Fix cataloguing/value_builder/unimarc_field_225a.pl
- [[32866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32866) Clean up cataloguing/value_builder/unimarc_field_146h.pl
- [[32867]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32867) Clean up cataloguing/value_builder/unimarc_field_146i.pl
- [[32817]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32817) Clean up cataloguing/value_builder/dateaccessioned.pl
- [[32818]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32818) Clean up cataloguing/value_builder/marc21_field_005.pl
- [[32872]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32872) Fix cataloguing/value_builder/unimarc_field_4XX.pl
- [[32875]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32875) Fix cataloguing/value_builder/unimarc_leader_authorities.pl
- [[32876]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32876) Fix cataloguing/value_builder/unimarc_leader.pl
- [[33375]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33375) Advanced editor crashes when using MySQL 8 due to reserved rank keyword
- [[32850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32850) Fix cataloguing/value_builder/unimarc_field_124.pl
- [[32864]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32864) Fix cataloguing/value_builder/unimarc_field_141.pl
- [[32863]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32863) Fix cataloguing/value_builder/unimarc_field_140.pl
- [[32862]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32862) Fix cataloguing/value_builder/unimarc_field_135a.pl
- [[32861]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32861) Fix cataloguing/value_builder/unimarc_field_130.pl
- [[32860]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32860) Fix cataloguing/value_builder/unimarc_field_128c.pl
- [[32859]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32859) Fix cataloguing/value_builder/unimarc_field_128b.pl
- [[32858]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32858) Fix cataloguing/value_builder/unimarc_field_128a.pl
- [[32857]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32857) Fix cataloguing/value_builder/unimarc_field_127.pl
- [[32855]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32855) Fix cataloguing/value_builder/unimarc_field_126b.pl
- [[32854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32854) Fix cataloguing/value_builder/unimarc_field_126a.pl
- [[32852]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32852) Fix cataloguing/value_builder/unimarc_field_125b.pl
- [[32851]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32851) Fix cataloguing/value_builder/unimarc_field_125a.pl
- [[32849]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32849) Fix cataloguing/value_builder/unimarc_field_124g.pl
- [[32848]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32848) Fix cataloguing/value_builder/unimarc_field_124f.pl
- [[32847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32847) Fix cataloguing/value_builder/unimarc_field_124e.pl
- [[32846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32846) Fix cataloguing/value_builder/unimarc_field_124d.pl
- [[32845]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32845) Fix cataloguing/value_builder/unimarc_field_124c.pl
- [[32844]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32844) Fix cataloguing/value_builder/unimarc_field_124b.pl
- [[32843]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32843) Fix cataloguing/value_builder/unimarc_field_124a.pl
- [[32842]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32842) Fix cataloguing/value_builder/unimarc_field_123j.pl
- [[32841]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32841) Fix cataloguing/value_builder/unimarc_field_123i.pl
- [[32840]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32840) Fix cataloguing/value_builder/unimarc_field_123g.pl
- [[32839]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32839) Fix cataloguing/value_builder/unimarc_field_123f.pl
- [[32838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32838) Fix cataloguing/value_builder/unimarc_field_123e.pl
- [[32837]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32837) Fix cataloguing/value_builder/unimarc_field_123d.pl
- [[32834]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32834) Fix cataloguing/value_builder/unimarc_field_121b.pl
- [[32836]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32836) Fix cataloguing/value_builder/unimarc_field_123a.pl
- [[32833]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32833) Fix cataloguing/value_builder/unimarc_field_121a.pl
- [[32832]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32832) Fix cataloguing/value_builder/unimarc_field_120.pl
- [[32831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32831) Fix cataloguing/value_builder/unimarc_field_117.pl
- [[32830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32830) Fix cataloguing/value_builder/unimarc_field_116.pl
- [[19361]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19361) Linking an authorised value category to a field in a framework can lose data
- [[3831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=3831) Add a warning/hint when FA framework is missing
- [[31665]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31665) 952$d ( Date acquired ) no longer prefills with todays date when focused
- [[32567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32567) Update plugin unimarc_field_110.pl 'Script of title' and 'Transliteration code'
- [[15869]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15869) Change framework on overlay
- [[32204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32204) in-page anchor to edititem on additem.pl not working
- [[32550]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32550) 'Clear on loan' link on Batch item modification doesn't untick on loan items
- [[24606]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24606) Allow storing item values as a template for creating new items
- [[32188]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32188) Only show template controls above item form if templates have been defined
- [[30250]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30250) Configure when to apply framework defaults when cataloguing
- [[31987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31987) Update plugin unimarc_field_110.pl fields
- [[31877]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31877) Capitalization: Delete this Tag and Repeat this Tag
- [[31876]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31876) Capitalization: Click to Expand this Tag
- [[25387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25387) Avoid merge different type of authorities
- [[29662]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29662) PrefillItem should apply to all subfields when SubfieldsToUseWhenPrefill is null
- [[31417]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31417) Re-instate the cataloguing sidebar menu
- [[31724]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31724) MARC framework subfield deletion - 'i' added to end of the breadcrumb on confirm deletion page
- [[31536]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31536) Add UNIMARC framework plugin to fetch PPN from sudoc.fr
- [[31371]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31371) Value builder for UNIMARC field 283
- [[31372]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31372) Value builder for UNIMARC field 325
- [[23063]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23063) Item table in cataloguing doesn't respect CurrencyFormat
- [[26368]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26368) Add support for OCLC Encoding level values
- [[27981]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27981) Add option to automatically set the 001 control number to the biblionumber
- [[30941]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30941) Add value builders for UNIMARC 146 ($b, $c, $d, $e and $f)
- [[30507]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30507) Value builder for UNIMARC field 183
- [[30506]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30506) Value builder for UNIMARC field 182
- [[30504]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30504) Value builder for UNIMARC field 181
- [[24857]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24857) Add ability to group items for records
- [[30392]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30392) Add a deleted_on column to deleteditems

## Circulation

- [[33847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33847) Database update replaces undefined rules with defaults rather than the value that would be used
- [[32129]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32129) Use patron categorycode of most relevant recall when checking if item can be a waiting recall
- [[33613]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33613) Claim return doesn't charge when "Ask if a lost fee should be charged" is selected and marked to charge
- [[33021]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33021) Show an alert when adding an item on hold to an item bundle
- [[32121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32121) Show an alert when adding a checked out item to an item bundle
- [[33577]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33577) Buttons on reserve/request.pl are misaligned
- [[33300]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33300) Wrong system preference name AutomaticWrongTransfer
- [[26967]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26967) Patron autocomplete does not correctly format addresses
- [[18398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18398) CHECKIN/CHECKOUT/RENEWAL don't use AutoEmailPrimaryAddress but first valid e-mail
- [[33574]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33574) Restriction type is not stored, all restrictions fall back to MANUAL
- [[29234]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29234) Transfers generated by stock rotation alert but do not initiate at checkin
- [[32883]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32883) Curbside pickups - Order "To be staged" by date and time of scheduled pickup
- [[32503]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32503) Holds awaiting pickup doesn't sort dates correctly
- [[31563]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31563) Numbers on claims tab not showing in translated templates
- [[32891]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32891) Curbside pickups - Cannot select slot in the last hour
- [[32653]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32653) Curbside pickups - wrong dates available at the OPAC
- [[30642]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30642) We should record the renewal type (automatic/manual)
- [[14784]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14784) Missing checkin message for debarred patrons when issuing rules 'fine days = 0'
- [[31233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31233) Fine grace period in circulation conditions is misnamed
- [[32134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32134) Show the bundle size when checked out
- [[31080]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31080) Block adding the bundle item to its own bundle
- [[31447]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31447) "Please confirm checkout" message uses patron's home library not holds pick up library
- [[31261]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31261) Curbside pickups - remove slots in the past
- [[31262]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31262) Curbside pickups - disable dates without slots
- [[32111]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32111) Cannot schedule a pickup at the OPAC
- [[24860]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24860) Add ability to place item group level holds
- [[21381]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21381) Add serial enumeration to circulation history
- [[29792]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29792) Transfers created from 'wrong transfer' checkin are not sent if modal is dismissed
- [[23012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23012) Possibility to mark processing fee by default refund when item is found
- [[30407]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30407) Add ability to syspref UpdateNotForLoanStatusOnCheckin to show only the notforloan values description
- [[31753]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31753) Dialog boxes inside of modals don't seem wide enough
- [[31728]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31728) Duplicate claims modal template markup
- [[29012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29012) Some rules are not saved when left blank while editing a 'rule' line in smart-rules.pl
- [[25426]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25426) Allow return policy to be selected via syspref and not just home library
- [[31485]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31485) Move ItemsDeniedRenewal checks from C4::Circulation to Koha::Item
- [[30944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30944) Fix single cancel recall button in recalls tab in staff interface and correctly handle cancellations with branch transfers
- [[22115]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22115) Table of checkouts doesn't respect CurrencyFormat setting
- [[31419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31419) Add accesskeys to recall modal
- [[30802]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30802) numReturnedItemsToShow doesn't show more than 20 items on the return screen
- [[7021]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7021) Add patron category to the statistics table
- [[30755]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30755) auto_too_soon should not be counted as an error in autorenewals
- [[20262]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20262) Add ability to refund lost item fees without creating credits
- [[31343]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31343) DataTables error on waitingreserves.tt
- [[31395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31395) Checking in non-existent barcodes makes Koha explode
- [[28854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28854) Add ability to create bundles of items for circulation
- [[31265]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31265) Curbside pickups - improve slots selection
- [[29983]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29983) Display the return claims column in the circulation overdues page (overdue.tt)
- [[30650]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30650) Add a curbside pickup module
- [[30964]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30964) Add information about overdues and restrictions on the curbside pickup list
- [[30965]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30965) Add patron autocomplete search to curbside pickups
- [[31157]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31157) overdue_notices.pl --frombranch option should be available as a system preference
- [[23838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23838) Add ability to view item renew history
- [[31192]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31192) Checking in an unkown barcode causes error
- [[31083]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31083) Part name (245$p) breaks item bundle detail view
- [[29129]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29129) The clear screen and print icons in circulation should be configurable to print either ISSUESLIP or ISSUEQSLIP
- [[30947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30947) Simplify date handling in CanbookBeIssued
- [[30924]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30924) Fix recalls-related errors in transfers and cancelling actions

## Command-line Utilities

- [[33360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33360) SendQueuedMessages: Improve limit behavior and add domain limits
- [[33677]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33677) Remove --verbose from koha-worker manpage
- [[33645]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33645) koha-foreach always returns 1 if --chdir not specified
- [[33626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33626) compare_es_to_db.pl does not work with Search::Elasticsearch 7.0
- [[33603]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33603) misc/maintenance/search_for_data_inconsistencies.pl fails if biblio.biblionumber on control field
- [[33108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33108) We need a way to launch the ES indexer automatically
- [[32800]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32800) build_oai_sets.pl fails on deleted records
- [[32798]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32798) build_oai_sets.pl passes wrong parameter to Koha::Biblio::Metadata->record
- [[32793]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32793) import_patrons.pl typo in usage
- [[31969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31969) Options for cleanup_database.pl to remove finished jobs from the background job queue
- [[32093]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32093) cleanup_database.pl bg-jobs parameter should be bg-days
- [[31854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31854) Document conflict with delete_patrons.pl --not_borrowed_since and anonymization
- [[28555]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28555) Improve output of verbose option for overdue_notices.pl
- [[17379]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17379) Add a man page for koha-passwd
- [[31203]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31203) Cronjobs should log completion as well as logging begin
- [[30684]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30684) koha-* scripts --restart should start even when not running
- [[21903]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21903) koha-dump be able to include koha-upload
- [[26311]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26311) Add patron invalid age to search_for_data_inconsistencies.pl
- [[29325]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29325) commit_file.pl error 'Already in a transaction'

## Database

- [[32357]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32357) Set borrower_message_preferences.days_in_advance default to NULL
- [[28674]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28674) old_reserves.item_level_hold and reserves.item_level_hold comments have typo "hpld" not "hold"
- [[30571]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30571) Table z3950servers: Make host, syntax and encoding NOT NULL
- [[30497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30497) Constraint old_reserves_ibfk_4 should be SET NULL instead of CASCADE
- [[30490]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30490) Adjust foreign key for parent item type
- [[30472]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30472) Field borrower_relationships.guarantor_id should be marked as NOT NULL
- [[30483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30483) Do not allow NULL in issues.borrowernumber and issues.itemnumber
- [[30899]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30899) Upgrade sometimes fails at "Upgrade to 21.11.05.004"

## ERM

- [[33064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33064) Add a search option for licenses to top search bar
- [[33355]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33355) ERM UI and markup has some issues
- [[33490]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33490) Agreements - Filter by expired results in error
- [[33623]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33623) getAll not encoding URL params
- [[33408]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33408) Fetch sysprefs from svc/config/systempreferences
- [[33491]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33491) EBSCO Packages - Add new agreement UI has some issues
- [[33483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33483) Cannot link EBSCO's package with local agreement
- [[33466]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33466) Link vendor name in list of licenses
- [[32924]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32924) Filter agreements by logged in librarian
- [[33482]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33482) Errors from EBSCO's ws are not reported to the UI
- [[32782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32782) Add UNIMARC support to the ERM module
- [[33354]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33354) Error 400 Bad Request when submitting form in ERM
- [[33648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33648) Errors when enabling ERM in 22.11
- [[33485]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33485) Add/remove title from holdings is not using the correct endpoint
- [[33481]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33481) EBSCO ws return 415: Content type 'application/octet-stream' not supported
- [[33422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33422) ERM - Search header should change to match the section you are in
- [[33381]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33381) Active link in the menu is not always correctly styled
- [[33346]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33346) Add Help link to Koha manual in ERM module
- [[32807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32807) No need to fetch all if we need to know if one exist
- [[33290]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33290) Incorrect variable used in http-client.js
- [[32495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32495) Required fields in API and UI form don't match
- [[32983]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32983) Use REST API route to retrieve authorised values
- [[32180]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32180) ERM - Mandatory fields don't have the 'required' class on the label
- [[32728]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32728) ERM - Search header should change to match the section you are in
- [[32925]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32925) Display loading info when a form is submitted
- [[32779]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32779) Import from list is broken
- [[32468]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32468) Vendors select only allows selecting from first 20 vendors by default
- [[32181]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32181) ERM - Cannot filter by expired when adding an agreement to EBSCO's package
- [[32130]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32130) Vue files must be kept tidy
- [[32030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32030) Electronic resource management (ERM)

## Fines and fees

- [[30254]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30254) New overdue fine applied to incorrectly when using "Refund lost item charge and charge new overdue fine" option in circ rules
- [[22042]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22042) BlockReturnofWithdrawn Items does not block refund generation when item is withdrawn and lost
- [[31713]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31713) Allow easy printing of patron's fines
- [[24381]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24381) ACCOUNT_CREDIT and ACCOUNT_DEBIT slip not printing information about paid fines/fees
- [[31254]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31254) Add additional fields for accountlines
- [[30619]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30619) Add the option to email receipts as an alternative to printing
- [[27802]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27802) Set focus for cursor on first input field when adding a cash register
- [[30335]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30335) Add ability to hide/disable manual invoices and manual credits in patron accounts
- [[24865]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24865) Customize the accountlines description

## Hold requests

- [[33761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33761) Holds queue is not selecting items with completed transfers
- [[30687]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30687) Unable to override hold policy if no pickup locations are available
- [[32993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32993) Holds priority changed incorrectly with dropdown selector
- [[32627]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32627) Reprinting holds slips should not reset the expiration date
- [[33672]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33672) Item group features shows when placing holds if EnableItemGroupHolds is disabled
- [[33302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33302) Placing item level holds in OPAC allows to pick forbidden pick-up locations, but then places no hold
- [[33611]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33611) Holds being placed in the future if DefaultHoldExpirationdate is set
- [[33210]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33210) (Bug 31963 follow-up) No hold fee message on OPAC should be displayed when there is no fee
- [[32421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32421) Add collection ( ccode ) column to holds to pull
- [[32455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32455) Don't send hold notices from the library's inbound email address
- [[32470]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32470) (Bug 14783 follow-up) Fix mysql error in db_rev for 22.06.000.064
- [[30794]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30794) 'Default checkout, hold and return policy' overrides Unlimited holds in 'Default checkout, hold policy by patron category'
- [[29102]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29102) DecreaseLoanHighHolds will decrease loan period if patron has an 'unfound' hold
- [[31963]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31963) Only show hold fee message on OPAC and charge hold fee if HoldFeeMode conditions are true as described in the system preference
- [[31948]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31948) Add timestamp to tmp_holdsqueue
- [[14783]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14783) Allow patrons to change pickup location for non-waiting holds
- [[31808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31808) When placing a hold patron name is not displaying correctly
- [[29196]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29196) Follow-up to Bug 27068 - Remove unnecessary check
- [[29389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29389) Add holding branch to holds queue report
- [[29071]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29071) HoldsSplitQueueNumbering not set for new installs
- [[31105]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31105) Holds to pull counts items from other branches when independentbranches is active
- [[30213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30213) Hide Delete (aka Priority) column when user only has place_hold permission
- [[30500]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30500) Add option to allow user to change the pickup location while a hold is in transit
- [[14364]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14364) Allow automatically canceled expired waiting holds to fill the next hold
- [[31086]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31086) Do not allow hold requests with no branchcode
- [[29057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29057) Use font awesome icons on request.pl
- [[23659]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23659) Allow hold pickup location to default to item home branch for item-level holds

## Holidays

- [[31057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31057) Add clarifying text to 'To date' in the calendar tool

## I18N/L10N

- [[26403]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26403) Move debit and credit types to YAML files and fix other related translation issues
- [[32931]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32931) ERM - (is perpetual) Yes / No options untranslatable
- [[30352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30352) "Not for loan" in result list doesn't translate in OPAC
- [[33533]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33533) Translatability: Do not separate "Patron" or "Organization" and "identity" in memberentrygen.tt
- [[33323]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33323) Select button in patron search modal is not translatable
- [[33332]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33332) Fix formatting of TT comments to improve translations
- [[31640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31640) Fuzzy translations of preferences can cause missing sections and inaccurate translations
- [[22490]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22490) Some strings in JavaScript files are untranslatable
- [[32588]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32588) Filters on top of 'Items with no checkouts' report are untranslatable
- [[32292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32292) Update and add database column descriptions used in guided reports
- [[31715]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31715) Add missing German translations for language descriptions
- [[31807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31807) Context for translation: Filter (verb) vs. Filter (noun)
- [[28708]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28708) fr-CA localization file
- [[30991]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30991) [% ELSE %]0[% END %] will break translations if used for assigning variables
- [[30733]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30733) Simplify translatable strings

## ILL

- [[33702]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33702) Patrons should only see their own ILLs in the OPAC
- [[22440]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22440) Improve ILL page performance by moving to server side filtering
- [[32799]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32799) ILLSTATUS authorized value category name is confusing
- [[32546]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32546) Move ILL system preferences to their own tab in administration
- [[22321]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22321) Make it possible to edit illrequests.borrowernumber
- [[30484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30484) Interlibrary loans should have the ability to send notices based on request supplier updates
- [[28634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28634) ILL partner request notices are attached to the request creator rather than the partner recipient
- [[28909]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28909) Allow interlibrary loans illview method to use backend template
- [[24239]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24239) Let the ILL module set ad hoc hard due dates

## Installation and upgrade (command-line installer)

- [[28267]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28267) Older databases fail to upgrade due to having a row format other than "DYNAMIC"
- [[33051]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33051) 22600075.pl is not idempotent
- [[32191]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32191) Consistent upgrade messages
- [[29673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29673) Allow an English sql localization script

## Installation and upgrade (web-based installer)

- [[33671]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33671) Database update  22.06.00.048  breaks update process
- [[33128]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33128) Add Polish translations for language descriptions
- [[33059]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33059) Capitalization: Fix sample authorised value descriptions
- [[32918]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32918) ERM authorized values should be in installer/data/mysql/en/mandatory/auth_values.yml
- [[32399]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32399) Database update for bug 30483 is failing
- [[31403]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31403) Activate circulation sidebar (CircSidebar system preference) on default in new installations

## Label/patron card printing

- [[31633]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31633) Add home and holding data attributes to quick spine label print to help customizing
- [[28512]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28512) Quick spine label creator: Add CSS class with logged in library's branchcode
- [[30837]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30837) Fix table width on 'Print summary'

## Lists

- [[32173]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32173) Add count of total titles in list to staff interface
- [[30933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30933) Add a designated owner for shared and public lists at patron deletion
- [[25498]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25498) Allow to change owner of public or shared list
- [[11889]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11889) Option to keep public or shared lists when deleting patron

## MARC Authority data support

- [[33557]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33557) Add a system preference to disable/enable thesaurus checking during authority linking
- [[33277]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33277) Correctly handle linking subfields with no defined thesaurus
- [[32250]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32250) link_bibs_to_authorities generates too many background jobs
- [[33159]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33159) Thesaurus is not defined by second indicator for controlled fields outside of 6XX
- [[30280]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30280) Support authority records with common subject headings from different thesaurus
- [[30025]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30025) Split BiblioAddsAuthorities into 2 preferences
- [[30218]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30218) Add subfield g to 150 heading_fields

## MARC Bibliographic data support

- [[32766]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32766) Update plugin unimarc_field_116.pl fields
- [[33419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33419) Make home library and holding library in items mandatory by default
- [[31432]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31432) MARC21: Make 245 n and p subfields visible in frameworks by default
- [[31860]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31860) Standardize capitalization for item subfield descriptions (UNIMARC 995/MARC21 952)
- [[32689]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32689) Host item entry (773) missing a space between label and content when $i is used
- [[23032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23032) Add 264 to Alternate Graphic Representation (MARC21 880)
- [[21705]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21705) Map copyrightdate to both 260/264c by default for new MARC21 installations
- [[31526]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31526) Diff view on manage staged imports page is broken
- [[25449]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25449) Make itemtype mandatory by default
- [[30430]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30430) UNIMARC XSLT : displaying field B_214

## MARC Bibliographic record staging/import

- [[27421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27421) Porting tools/stage-marc-import.pl to BackgroundJob

## Notices

- [[32917]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32917) Change patron.firstname and patron.surname in password change sample notice
- [[33622]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33622) Notice content does not show on default tab if TranslateNotices enabled
- [[33649]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33649) Fix use of cronlogaction
- [[29354]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29354) Make overdue_notices.pl send HTML attachment as .html
- [[31858]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31858) TT syntax for ACQORDER notices
- [[29100]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29100) Add checkouts data loop to predue/due notices script (advance_notices.pl)
- [[24616]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24616) Cannot copy notice to another library if it already exists
- [[32442]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32442) Invalid Template Toolkit in notices can cause errors
- [[31743]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31743) Cannot change my notice language when EnhancedMessagingPreferencesOPAC is off
- [[31714]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31714) Add a more generic way to print patron slips
- [[31626]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31626) Add letter ID to the message queue table
- [[31170]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31170) Capitalization: Overdue Item Fine Description
- [[19966]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19966) Add ability to pass objects directly to slips and notices

## OPAC

- [[32995]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32995) Koha agent string not sent for OverDrive fulfillment requests
- [[33069]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33069) File download from list in OPAC gives error
- [[33102]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33102) Cart in OPAC and staff interface does no longer display infos from biblioitems table
- [[33233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33233) OPAC advanced search inputs stay disabled when using browser's back button
- [[32412]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32412) OPACShelfBrowser controls add extra Coce images to biblio-cover-slider
- [[32701]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32701) Self checkout help page lacks required I18N JavaScript
- [[29311]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29311) Do not allow editing of bibliographic information when entering suggestion from existing bibs
- [[33160]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33160) Make sure 773 (host item entry) displays in the cart when not linked by $w
- [[33299]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33299) Item type column is empty when placing item level holds in OPAC
- [[25590]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25590) Street number is missing from alternate address in the OPAC
- [[30162]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30162) XSLT has broken link for traced series because of OPAC/staff interface confusion
- [[32674]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32674) When placing a hold in OPAC page explodes into error 500
- [[31221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31221) Buttons overflow in OPAC search results in mobile view
- [[33101]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33101) Basket More details view doesn't work
- [[32611]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32611) Not for loan items don't show the specific not for loan value in OPAC detail page
- [[32338]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32338) OPAC - Mobile - Selection toolbar in search result is shifted and not adjusted
- [[32946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32946) 'Send list/cart' forms in OPAC is misaligned
- [[32125]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32125) Implement contextual return on OPAC comments
- [[31699]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31699) Add a generic way to redirect back to the page you were on at login for modal logins
- [[26765]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26765) Make author span a clickable link on OPAC results list
- [[32712]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32712) OPACShowCheckoutName makes OPAC explode
- [[16522]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16522) Add 773 (Host item entry) to the cart and list displays and e-mails
- [[32251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32251) opac-page.pl: Add a fallback for when language cookie was removed
- [[32445]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32445) Status display of 'not for loan' items is broken in OPAC/staff
- [[20207]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20207) Anonymous suggestions show in OPAC even when OPACViewOthersSuggestions is set to 'Don't show'
- [[32185]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32185) Template error in opac-reserve.pl
- [[30880]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30880) Expand OPACResultsUnavailableGroupingBy to have a 'branch only' option
- [[31907]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31907) Show items as On hold when in processing
- [[31654]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31654) Hide non-public libraries from MastheadLibraryPulldown
- [[30036]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30036) Add XSLT for authority results view in OPAC
- [[7960]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7960) Choice to not show the text labels for item types
- [[31672]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31672) Remove 'Your' from tab descriptions in OPAC patron account
- [[31775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31775) Show opac_info of single library
- [[31635]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31635) Empty title for current result in OPAC results browser's tooltip on paging
- [[31634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31634) Add part_number and part_name in OPAC result browser
- [[23538]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23538) Email library when new patrons self register
- [[31463]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31463) (Bug 31313 follow-up) Show item order status on opac-detail
- [[8305]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8305) Add an icon for iOS home screens
- [[29144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29144) Move branches.opac_info to AdditionalContents allowing multi language
- [[30847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30847) Cleanup opac-reserve.pl
- [[31331]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31331) OPAC suggestions table doesn't sort correctly by suggestiondate in some dateformats
- [[29897]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29897) Display author identifiers for researchers
- [[30927]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30927) Improve formatting or iCal files for checkout due dates
- [[31303]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31303) Fatal error when viewing OPAC user account with waiting holds
- [[22456]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22456) Allow patrons to cancel their waiting holds
- [[30678]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30678) Add OCLC_NO as option to OPACSearchForTitleIn
- [[30195]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30195) Suggestion form in OPAC should use ISBN to FindDuplicate
- [[30508]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30508) Do not display OPAC message about block from holds when OPACHoldRequests is disabled

## Packaging

- [[33629]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33629) allow pbuilder to use network via build-git-snapshot
- [[32994]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32994) Remove compiled files from src (2)
- [[32666]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32666) Automatic debian/control updates (stable)
- [[31588]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31588) Update cpanfile for new OpenAPI versions
- [[29882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29882) Remove unrequired package definitions in list-deps script
- [[21366]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21366) Add Plack reload

## Patrons

- [[33684]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33684) Able to save patron with empty mandatory date fields
- [[25379]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25379) HTML in circulation notes doesn't show correctly on checkin
- [[32232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32232) Koha crashes if dateofbirth is 1947-04-27, 1948-04-25, or 1949-04-24
- [[19249]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19249) Date picker broken in "Quick add new patron" form
- [[32510]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32510) "New list" option is not available when too many patron's lists
- [[32976]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32976) Patron image Add/Edit button should not appear if permission is turned off
- [[32904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32904) Patrons table processing eternally and not loading
- [[32770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32770) Patron search field groups no longer exist
- [[31890]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31890) PrefillGuaranteeField should include option to prefill surname
- [[32491]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32491) Can no longer search patrons in format 'surname, firstname'
- [[31937]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31937) Prevent cleanup_database.pl from locking too many accounts
- [[10950]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10950) Add pronoun field to patron record
- [[30646]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30646) Add option to send WELCOME notice for new patrons added at first login via LDAP/SAML
- [[31562]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31562) Patron 'flags' don't respect unwanted fields
- [[31597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31597) Missing semicolon after try-catch in restrictions.pl
- [[23681]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23681) Make patron restrictions user definable
- [[29971]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29971) Remember selections across patron search pages
- [[21978]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21978) Add middle name field
- [[12446]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12446) Enable an adult to have a guarantor

## Plugin architecture

- [[30367]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30367) Plugins: Search explodes in error when searching for specific keywords
- [[31896]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31896) New recall hook when adding recall
- [[31894]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31894) Extend hold hooks with more actions
- [[31895]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31895) New account hook when adding credit

## Reports

- [[33513]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33513) Batch update from report module - no patrons loaded into view
- [[27513]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27513) Add description to reports page
- [[32805]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32805) When recording localuse in the statistics table location is always NULL
- [[32589]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32589) Improve headings on result tables for 'checkouts with no items' report
- [[29579]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29579) Show saved SQL report ID in database query

## REST API

- [[31799]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31799) Add PUT endpoint for Items
- [[31798]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31798) Add POST endpoint for Items
- [[31797]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31797) Add DELETE endpoint for Items
- [[32735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32735) Add GET endpoint for listing Authorities
- [[31796]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31796) Add PUT endpoint for Authorities
- [[31795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31795) Add POST endpoint for Authorities
- [[31793]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31793) Add DELETE endpoint for Authorities
- [[31794]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31794) Add GET endpoint for Authorities
- [[33329]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33329) GET /biblios encoding wrong when UNIMARC
- [[33470]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33470) Don't calculate overridden values when placing a hold via the REST API
- [[33328]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33328) x-marc-schema should be renamed x-record-schema
- [[32336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32336) MARCXML output of REST API may be badly encoded (UNIMARC)
- [[32923]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32923) x-koha-embed must a header of collectionFormat csv
- [[33227]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33227) OpenAPI validation is failing for paths/biblios.yaml
- [[32713]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32713) x-koha-embed appears to no longer properly validate
- [[32734]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32734) Add GET endpoint for listing Biblios
- [[31800]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31800) Add POST endpoint for Biblios
- [[32118]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32118) Clarify expansion/embed modifiers
- [[33161]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33161) Implement +strings for GET /items and GET /items/:item_id
- [[31801]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31801) Add PUT endpoint for Biblios
- [[33145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33145) Invalid specification for ERM routes
- [[32997]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32997) Add GET endpoint for listing authorised value categories
- [[32981]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32981) Add GET endpoint for listing authorised values by a given category
- [[33020]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33020) Unsupported method history
- [[30962]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30962) Add POST endpoint for validating a user password
- [[31160]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31160) Required fields in the Patrons API are a bit random
- [[31381]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31381) Searching patrons by letter broken when using non-mandatory extended attributes
- [[26635]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26635) Expand coded values in REST API call
- [[22678]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22678) Set 'Koha::Logger' as the default mojo logger for the REST API
- [[31555]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31555) Getting holds via REST API needs edit_borrowers permission
- [[31104]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31104) Pagination generates HTTP "Link:" header which is over 8192 bytes apache's limit
- [[31128]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31128) Add effective_not_for_loan_status to API item objects

## Searching

- [[33569]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33569) Order by relevance may not be visible
- [[33093]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33093) (Bug 27546 follow-up) With ES searching within results does not work for 'Keyword' and 'Keyword as phrase'
- [[33506]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33506) Series has wrong index name on scan index page and search option selection is not retained
- [[31338]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31338) Show in advanced search when IncludeSeeFromInSearches is used
- [[14911]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14911) Item search: Display additional title information
- [[31326]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31326) Koha::Biblio->get_components_query fetches too many component parts
- [[32126]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32126) Adding item search fields is broken - can't add more than one field
- [[31543]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31543) MaxComponentRecords link is broken
- [[31967]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31967) Search terms retained in header search when only one result
- [[15187]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15187) Adding 880 Fields to index-list in order to Increase Search for ALL non-latin Scripts
- [[31847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31847) Add page section to item search results
- [[17170]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17170) Add the ability to create 'saved searches' for use as filters when searching the catalog
- [[31252]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31252) Advanced search in staff interface should call barcodedecode if the search index is a barcode
- [[28372]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28372) Use variables for 007 controlfield translations in MARC21slim2intranetResults.xsl
- [[27136]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27136) Add additional languages
- [[24127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24127) Improve wording on location drop-down in advanced search in the staff interface
- [[26247]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26247) Search terms retained in header search creates UX inconsistency
- [[23919]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23919) Make ISSN searchable with and without hyphen
- [[30858]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30858) Add serial enumeration/chronology to itemsearch.pl
- [[27546]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27546) Add option to search within results on the staff interface
- [[11158]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11158) Authorities 'starts with'  search returns the same as 'contains' when using ICU
- [[30327]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30327) Sort component parts

## Searching - Elasticsearch

- [[33206]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33206) Bad title__sort made of multisubfield 245
- [[33486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33486) Remove Koha::BackgroundJob::UpdateElasticIndex->process routine
- [[32594]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32594) Add a dedicated ES indexing background worker
- [[31695]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31695) Type standard number is missing field ci_raw in field_config.yaml
- [[33019]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33019) Records not indexed in Elasticsearch ES when first catalogued
- [[31690]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31690) Add see from tracings in See-from index (Elasticsearch, MARC21)
- [[31689]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31689) Add see from tracings in Match-heading-see-from index (Elasticsearch, MARC21)
- [[31693]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31693) Remove non-existent fields from the See-also-from index (Elasticsearch, MARC21)
- [[31691]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31691) Remove non-existent fields from the See-from index (Elasticsearch, MARC21)
- [[31687]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31687) Add see from and see also from tracings in Match index (Elasticsearch, MARC21)
- [[25375]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25375) Elasticsearch: Limit on available items does not work
- [[31537]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31537) Elasticsearch - index mapping for 003 control-number-identifier is twice in mappings.yaml
- [[29632]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29632) Callnumber sorting is incorrect in Elasticsearch

## Searching - Zebra

- [[32937]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32937) Zebra: Ignore copyright symbol when searching
- [[31841]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31841) Shelving location search in staff interface sometimes creates invalid Zebra query
- [[31614]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31614) Add configurable timeout for Zebra connections
- [[30879]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30879) Add option to sort components by biblionumber

## Self checkout

- [[32921]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32921) SelfCheckTimeout doesn't logout if SelfCheckReceiptPrompt modal is open
- [[31496]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31496) SCO slip uses data of patron's home library instead of the SCO staff users's library

## Serials

- [[33512]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33512) Labels/buttons are confusing on serials-edit page
- [[33037]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33037) [Bugs 32555  and 31313 follow-up] Koha does not display difference between enumchron and serialseq in record detail view (OPAC and intranet)
- [[33560]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33560) Batch edit link broken if subscriptions are selected using "select all" link
- [[33261]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33261) Dates for issues on subscription detail page display unformatted
- [[33040]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33040) Add "Date published (text)" to serials tab on record view (detail.pl)
- [[33014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33014) Add link to serial advanced search
- [[32555]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32555) Error when viewing serial in OPAC
- [[28950]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28950) serialsUpdate cron does not mark an issue late until the next issue is expected
- [[26549]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26549) Show value of global system preferences on subscription form
- [[24010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24010) Number of issues to display to staff accepts non-integer values

## SIP2

- [[33580]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33580) Bring back ability to mark item as seen via SIP2 item information request
- [[33216]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33216) SIP fee paid messages explode if payment registers are enabled and the SIP account has no register
- [[32684]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32684) Implement SIP patron status field "too many items lost"
- [[20058]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20058) Option to use shelving location instead of homebranch for sorting

## Staff interface

- [[33642]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33642) Typo: No log found .
- [[33253]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33253) 2FA - Form not excluded from autofill
- [[28315]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28315) PopupMARCFieldDoc is defined twice in addbiblio.tt
- [[33643]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33643) Add page-section to 'scan index' page
- [[33615]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33615) Date picker icon not visible
- [[33631]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33631) results_summary label and content are slightly misaligned in staff interface
- [[33596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33596) Merge result page is missing page-section
- [[33588]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33588) Inventory item list is missing page-section class
- [[33505]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33505) Improve styling of scan index page
- [[33621]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33621) Javascript error when claiming return via circulation.pl
- [[33590]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33590) WRAPPER tab_panel breaks JS on some pages (Select all/Clear all, post-Ajax updates)
- [[32301]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32301) Show correct defaultSortField in staff interface advanced search
- [[33391]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33391) Currently active menu item on navmenulist should not change style on hover
- [[33133]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33133) Fast cataloging should be visible in cataloging
- [[32886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32886) Set focus for cursor to Code when adding a new restriction
- [[33090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33090) page-sections are missing in the account line details page
- [[32576]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32576) ILL needs the page-section treatment
- [[32568]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32568) Add page section to list of checkins
- [[32768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32768) Autocomplete suggestions container should always be on top of other UI elements
- [[32941]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32941) Sys prefs side menu styling applying where not intended
- [[32908]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32908) Item type icons broken in the bibliographic record details page
- [[32027]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32027) Terminology: change "librarian interface" to "staff interface" in additional contents tool
- [[32772]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32772) Patron autocomplete should not use contains on all fields
- [[32881]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32881) System preferences sub menu text is hard to read
- [[32239]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32239) Report options for adding groups/sub groups are misaligned
- [[31962]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31962) Add tooltip to 'configure' on datatable controls
- [[32504]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32504) Empty column name, misaligning visibility, and export for basket/orders in table settings
- [[32733]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32733) Add more page-sections to basket summary page
- [[32520]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32520) Patron autocomplete should respect DefaultPatronSearchFields
- [[32718]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32718) Capitalization: Display Order
- [[31950]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31950) Page section on library view is too wide / not aligned with toolbar
- [[32517]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32517) Patron search dies on case mismatch of patron category
- [[32272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32272) Last borrower and previous borrower display on moredetail.pl is broken
- [[31935]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31935) Serials subscription form is misaligned
- [[32475]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32475) The phrase "System prefs" should be replaced with the correct terminology "System preferences"
- [[32368]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32368) Add page-section to saved report results
- [[32194]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32194) "Can be guarantee" value should show uppercase "No"
- [[32257]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32257) Label for patron attributes misaligned on patron batch mod
- [[32261]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32261) Insufficient user feedback when selecting patron in autocomplete
- [[32236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32236) Batch item modification - alignment of tick box for 'Use default values'
- [[32260]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32260) Prevent alert when searching patron (autocomplete)
- [[32046]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32046) When adding a new records from a staged files, there are style issues
- [[32299]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32299) Add page-section to Z39.50/SRU results (cat)
- [[32241]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32241) Add page-section to list of records in batch record modificaton (tool)
- [[32298]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32298) Add page-section to cataloguing search results (cat)
- [[31774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31774) Add 'page-section' to Manage staged MARC records page
- [[32214]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32214) Staff interface toolbar - no options when search catalog selected
- [[31751]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31751) Breadcrumb style
- [[32155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32155) Course reserves - instructors display is misaligned on course information page
- [[32170]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32170) Add page-section to CSV profiles (tools)
- [[32169]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32169) Add page-section to item list on top of batch item edit (tools)
- [[31819]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31819) Formatting of item form in acq when ordering is broken
- [[32005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32005) Spacing between entries in left side navigation on staff catalog detail page is uneven
- [[31902]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31902) Inconsistent table formatting for 'Existing holds'
- [[32004]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32004) Increase font size in top navigation pull downs
- [[32028]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32028) Add page-section to various administration pages (part 2)
- [[31271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31271) "Edit search" always resets search options to keyword
- [[31919]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31919) Hovered items in "More" should change background color
- [[32006]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32006) Add page-section to local use system preference tab (admin)
- [[31974]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31974) Regression: Bug 31813 incorrectly affected labels in the header search
- [[32002]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32002) Make submit button yellow on administration > Did you mean?
- [[31960]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31960) Information on job detail view is misaligned
- [[31664]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31664) Show pending transfers on catalog details page
- [[32035]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32035) "Koha" less prominent in new staff interface
- [[31760]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31760) Fix contrast of separator in top header in staff client (WCAG)
- [[31952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31952) Sending an empty system preference search breaks layout
- [[31910]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31910) Article request form is misaligned/misformatted
- [[31905]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31905) Buttons lack spacing on holds
- [[31162]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31162) Add a clear cataloguing module home page
- [[30952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30952) New design for staff interface
- [[31940]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31940) Add page-section to admin > library groups area
- [[31906]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31906) Managed by on basket summary page is misaligned
- [[31834]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31834) Inconsistent table formatting for list of MARC imports
- [[31927]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31927) Use bigger font-size for bibliographic information on staff details page
- [[31911]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31911) Headings are inconsistent in rotating collections
- [[31812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31812) Add yellow button to stage imports page
- [[31831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31831) Make inactive search options font slightly bigger
- [[31882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31882) Fix page title of pages in the new cataloging module home page
- [[31917]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31917) Headings don't seem quite right for system preference search
- [[31929]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31929) On vendor edit page options are not aligned
- [[31955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31955) Add page-section to additional fields (admin)
- [[31945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31945) Add page-section to admin > patron categories area
- [[31850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31850) Patron import: welcome email option style as list
- [[31879]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31879) Convert mainpage.css to SCSS
- [[31936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31936) Link to advanced search form in acquisitions is missing
- [[31941]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31941) Add page-section to admin > item types area
- [[31939]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31939) Add page-section to admin > libraries area
- [[31806]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31806) Add 'page-section' to holds page
- [[31864]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31864) Fix breadcrumbs for each link coming from the new cataloging module home page
- [[31813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31813) Specify white-space: normal for spans styled as labels
- [[31861]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31861) Table controls on checkouts table are buttons
- [[31886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31886) No side menu when searching for syspref
- [[31837]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31837) Add page-section to basket summary page
- [[31765]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31765) Add 'page-section' to import patrons page
- [[31821]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31821) Add page-section to vendor result list (acq)
- [[31822]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31822) Add page-section to vendor detail page (acq)
- [[31830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31830) Add page-section to budgets and funds table on acq start page (acq)
- [[31771]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31771) Add 'page-section' to stock rotation pages
- [[31770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31770) Add 'page-section' to rotating collections page
- [[31848]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31848) Holds queue: Submit button for filters on the left is closer to nav than to its form
- [[31803]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31803) "remove from cart" button displayed even if not in cart
- [[31829]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31829) Change password form in patron account is misaligned
- [[31750]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31750) Need more padding in cataloguing
- [[31811]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31811) Add 'page-section' to MARC modification templates pages
- [[31810]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31810) Place hold button should be yellow
- [[31835]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31835) Add page-section to holds queue
- [[31781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31781) Transferred items table (branchtransfers.tt) needs page-section class
- [[31780]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31780) Add 'page-section' to audio alerts ( audio_alerts.tt )
- [[31762]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31762) Flat vs 3D or mixed
- [[31747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31747) Round corners in boxes
- [[31773]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31773) Add 'page-section' to manage MARC import page
- [[31766]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31766) Add 'page-section' to notices and slips page
- [[31764]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31764) Add 'page-section' to patron clubs page
- [[31767]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31767) Add 'page-section' to tags page
- [[31758]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31758) Add 'page-section' to system preferences page
- [[31763]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31763) Add 'page-section' to patron lists page
- [[31749]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31749) Detail view broken
- [[31566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31566) 'Patrons selected' counter doubles on 'Select all'
- [[31663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31663) Item not showing transit status on detail page in staff interface
- [[31601]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31601) Materials specified note should include an ID on both the check in and checkout pages
- [[31565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31565) Patron search filter by category code with special character returns no results
- [[31439]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31439) Item count bullet (&bull;) should be easier to style/remove
- [[15326]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15326) Add CMS feature
- [[30922]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30922) Make the "Relative's checkouts" table configurable by the table settings
- [[27779]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27779) Cashup summary 'refunds' should denote what the refund was actioned against
- [[27497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27497) Display Koha version in staff interface home page
- [[30077]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30077) Add option for library dropdown in search function for staff interface
- [[31229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31229) Column visibility broken on patron search view
- [[31116]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31116) Article requests doesn't respect the 'CircSidebar' preference
- [[31039]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31039) Rebase issues lead to duplicate JS for cash summary modal printing
- [[29282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29282) Show items.issue and items.renewals in the holdings table on the detail page in the staff interface

## System Administration

- [[33335]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33335) MARC overlay rules broken because of "categorycode.categorycode " which contains "-"
- [[33586]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33586) Library and category are switched in table configuration for patron search results table settings
- [[33196]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33196) Terminology: rephrase Pseudonymization system preference to be more general
- [[33197]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33197) Terminology: rename GDPR_Policy system preference
- [[32745]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32745) Jobs view breaks when there are jobs with context IS NULL
- [[33634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33634) Sidebar navigation links in system preferences not taking user to the clicked section
- [[33549]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33549) Patron restriction types - Style missing for dialog messages
- [[33509]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33509) Staff search result list shows "other holdings" with AlternateHoldingsField when there are no alternate holdings
- [[32964]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32964) OPACResultsMaxItemsUnavailable description is misleading
- [[33060]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33060) Fix yes/no setting to 1/0 in system preference YAML files
- [[32803]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32803) EnableItemGroups and EnableItemGroupHolds options are wrong
- [[33004]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33004) Add VENDOR_TYPE to default authorised value categories
- [[32788]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32788) Curbside pickups - Order curbside pickup slots chronologically
- [[32544]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32544) borrowers.flags should not be an option in any BorrowerMandatory or BorrowerUnwanted system preferences
- [[32786]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32786) Curbside pickup admin page has cities search bar
- [[32761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32761) Typos in description of CircControlReturnsBranch system preference
- [[32787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32787) Patron restrictions admin page has patron categories search bar
- [[32535]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32535) BorrowerUnwantedField syspref should not include borrowers.flags
- [[31887]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31887) Search on MARC field does not work in Elasticsearch mappings table
- [[31995]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31995) build_holds_queue.pl should check to see if the RealTime syspref is on
- [[31422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31422) Library limitations might cause data loss when editing patrons
- [[31730]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31730) Link to authorized value interface when an authval is mentioned in preferences
- [[31923]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31923) 'Ignore' tab description is misleading
- [[31931]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31931) Terminology for HoldsSplitQueue - staff client should be staff interface
- [[31577]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31577) Use patron category multi-select for OpacHiddenItemsExceptions system preference
- [[31603]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31603) Add search option for plugin page
- [[31475]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31475) Group system preferences for suggestions on OPAC tab under new heading
- [[31545]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31545) ComponentSortField description is incorrect
- [[30462]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30462) Improve the default display for the background jobs queue management page
- [[31214]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31214) Regression: subfield code editable in MARC framework editor
- [[31264]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31264) CalendarFirstDayOfWeek not taken into account when configuring curbside pickups
- [[31191]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31191) Specify FacetLabelTruncationLength is only for Zebra
- [[29951]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29951) Cannot add splitting rule to classification sources
- [[30937]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30937) Add a detail view for libraries
- [[30850]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30850) Add default mapping for biblio.author to 110$a (MARC21)

## Templates

- [[33320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33320) Patron modification requests: options are squashed
- [[33699]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33699) Typo in identity_provider_domains.tt (presedence)
- [[22375]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22375) Due dates should be formatted consistently
- [[33696]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33696) Doubled up home icon in budgets page
- [[33601]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33601) Use template wrapper for breadcrumbs: Tools, part 8
- [[33600]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33600) Use template wrapper for breadcrumbs: Tools, part 7
- [[33582]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33582) Use template wrapper for breadcrumbs: Tools, part 4
- [[31405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31405) Set focus for cursor to setSpec input when adding a new OAI set
- [[31410]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31410) Set focus for cursor to Server name when adding a new Z39.50 or SRU server
- [[33551]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33551) Rogue span in patron restriction types admin page title
- [[33597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33597) Get rid of few SameSite warnings
- [[33598]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33598) Use template wrapper for breadcrumbs: Tools, part 5
- [[33566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33566) Use template wrapper for breadcrumbs: Tools, part 1
- [[33564]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33564) Use template wrapper for breadcrumbs: Serials part 3
- [[33559]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33559) Use template wrapper for breadcrumbs: Serials part 2
- [[33437]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33437) Use template wrapper for breadcrumbs: Reports part 2
- [[33336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33336) Use a dedicated column for plugin status in plugins table
- [[33572]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33572) Use template wrapper for breadcrumbs: Tools, part 3
- [[33571]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33571) Use template wrapper for breadcrumbs: Tools, part 2
- [[33579]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33579) Typo: record record
- [[33565]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33565) Use template wrapper for breadcrumbs: Tags
- [[32642]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32642) Loading spinner always visible when cover image is short (OPAC)
- [[33127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33127) Use template wrapper for breadcrumbs: Administration part 5
- [[33310]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33310) Use template wrapper for tabs: Suggestions
- [[33388]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33388) Use template wrapper for breadcrumbs: Patrons part 4
- [[33439]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33439) Use template wrapper for breadcrumbs: Reports part 4
- [[33438]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33438) Use template wrapper for breadcrumbs: Reports part 3
- [[33555]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33555) Use template wrapper for breadcrumbs: Rotating collections
- [[33558]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33558) Use template wrapper for breadcrumbs: Serials part 1
- [[32634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32634) Add 'page-section' to various pages
- [[32954]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32954) Standardize action fieldsets in rotating collections, suggestions, tools
- [[33181]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33181) Use template wrapper for tabs on record merge pages
- [[33187]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33187) Use template wrapper for tabs article requests and holds awaiting pickup pages
- [[33129]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33129) Use template wrapper for breadcrumbs: Administration part 6
- [[32956]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32956) Use template wrapper for HTML customizations tabs
- [[32955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32955) Standardize structure around action fieldsets in various templates
- [[32127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32127) Sort patron categories by description in templates
- [[33345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33345) On-site checkout checkbox does not work since issue date using flatpickr
- [[33154]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33154) Tab WRAPPER follow-up: label text must be translatable
- [[33077]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33077) Improve ease of translating template title tags
- [[33265]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33265) Additional unformatted navigation items when on serial receive page
- [[33111]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33111) Use template wrapper for breadcrumbs: Administration part 4
- [[33007]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33007) Use template wrapper for breadcrumbs: Administration part 2
- [[33006]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33006) Use template wrapper for breadcrumbs: Administration part 1
- [[33130]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33130) Use template wrapper for breadcrumbs: Authorities
- [[33131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33131) Use template wrapper for breadcrumbs: Catalog part 1
- [[33147]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33147) Use template wrapper for breadcrumbs: Catalog part 2
- [[33324]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33324) Use template wrapper for tabs: Tools
- [[33333]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33333) Use template wrapper for tabs: SQL reports
- [[33307]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33307) Use template wrapper for tabs: Lists
- [[33294]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33294) Use template wrapper for tabs: Checkout history
- [[33293]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33293) Use template wrapper for tabs: Holds
- [[33186]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33186) Use template wrapper for tabs on search history and advanced search
- [[33185]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33185) Use template wrapper for tabs on authority and biblio MARC details
- [[33001]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33001) Use template wrapper for breadcrumbs: Acquisitions part 2
- [[33005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33005) Use template wrapper for breadcrumbs: Acquisitions part 3
- [[33382]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33382) Use template wrapper for breadcrumbs: Patron clubs
- [[33373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33373) Use template wrapper for breadcrumbs: Circulation part 3
- [[33372]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33372) Use template wrapper for breadcrumbs: Circulation part 2
- [[33180]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33180) Use template wrapper for tabs: Budgets and Search engine configuration
- [[33383]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33383) Use template wrapper for breadcrumbs: Course reserves
- [[33384]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33384) Use template wrapper for breadcrumbs: Labels
- [[33385]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33385) Use template wrapper for breadcrumbs: Patrons part 1
- [[33386]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33386) Use template wrapper for breadcrumbs: Patrons part 2
- [[33387]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33387) Use template wrapper for breadcrumbs: Patrons part 3
- [[33389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33389) Use template wrapper for breadcrumbs: Patrons part 5
- [[33409]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33409) Use template wrapper for breadcrumbs: Patrons lists
- [[33410]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33410) Use template wrapper for breadcrumbs: Patron card creator
- [[33429]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33429) Use template wrapper for breadcrumbs: Plugins
- [[33434]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33434) Use template wrapper for breadcrumbs: Point of sale
- [[33436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33436) Use template wrapper for breadcrumbs: Reports part 1
- [[31994]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31994) Clicking the next button of a DataTable loading its data from the HTML does nothing
- [[33272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33272) Color of the "(remove)" link when an item is in the cart (OPAC)
- [[32263]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32263) Capitalization: ...and on the Libraries page in the OPAC.
- [[33149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33149) Use template wrapper for breadcrumbs: Circulation part 1
- [[33148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33148) Use template wrapper for breadcrumbs: Cataloging
- [[32447]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32447) In items table barcode column can not be filtered
- [[33322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33322) "Please select at least one suggestion" when doing a catalog search from suggestions page
- [[32771]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32771) Standardize structure around action fieldsets in serials
- [[31409]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31409) Set focus for cursor to Fund code when adding a new fund
- [[33136]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33136) Catalog search pop-up is missing page-section
- [[32217]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32217) Typo: Error authenticating in external provider
- [[32003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32003) Accessibility: Order search results has two h1 headings
- [[32945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32945) Capitalization: id (part 2)
- [[32969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32969) Remove references to jQueryUI assets and style in the OPAC
- [[33278]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33278) Correct JS for activating default tab on various pages
- [[33137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33137) Make sure columns on transactions and 'pay fines' tab are matching up
- [[33058]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33058) Terminology: change 'fine' to 'charge' for viewing a guarantee's charges in OPAC
- [[33056]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33056) Terminology: change 'fine' to 'charge' when making a payment/writeoff
- [[33126]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33126) Markup error in staff interface tab wrapper
- [[32952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32952) Standardize action fieldsets in authorities, cataloging, and circulation
- [[32683]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32683) Convert header search tabs to Bootstrap
- [[32746]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32746) Standardize structure around action fieldsets in acquisitions
- [[33031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33031) Update OPAC lists page to use Bootstrap markup for tabs
- [[32658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32658) Use template wrapper in order from staged file template
- [[33000]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33000) Use template wrapper for breadcrumbs: Acquisitions part 1
- [[33068]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33068) Use template wrapper for breadcrumbs: Administration part 3
- [[33095]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33095) Text is white on white when hovering over pay/writeoff buttons in paycollect
- [[32507]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32507) Use template wrapper to build breadcrumb navigation
- [[32159]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32159) Uncertain prices has 2 level 1 headings
- [[32973]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32973) Use template wrapper for breadcrumbs: about, main, and error page
- [[32293]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32293) Terminology: Some budgets are not defined in item records
- [[33015]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33015) 'Cancel' link still points to tools home when it should be cataloguing home on some pages
- [[32215]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32215) 'You Searched for' for patron restrictions is not used
- [[33011]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33011) Capitalization: Show in Staff interface?
- [[32912]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32912) Use template wrapper for notices tabs
- [[33016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33016) MARC diff view still shows tools instead of cataloging in title and breadcrumbs
- [[32933]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32933) Use val() instead of attr("value") when getting field values with jQuery
- [[32757]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32757) "Save changes" button on housebound tab should be yellow
- [[32605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32605) Restore some form styling from before the redesign
- [[32769]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32769) Standardize structure around action fieldsets in administration
- [[32743]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32743) Reindent the invoice details page
- [[32698]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32698) Use template wrapper for serials pages tabs
- [[32661]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32661) Use template wrapper for invoices page tabs
- [[32660]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32660) Use template wrapper for basket groups tabs
- [[32662]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32662) Use template wrapper for item circulation alerts page
- [[32649]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32649) Use template wrapper for library transfer limits tabs
- [[32571]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32571) Use template wrapper to build tabbed components
- [[32222]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32222) Capitalization: id
- [[32023]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32023) Remove horizontal line from OPAC navigation for CMS pages
- [[32226]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32226) Capitalization: Edit html content
- [[32264]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32264) Capitalization/Terminology: Show in Staff client?
- [[32230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32230) Capitalization: Manage Domains
- [[32606]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32606) Revert Flatpickr style changes made in Bug 31943
- [[32785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32785) Typo: Maximum number of simultaneus pickups per interval (curbside pickups)
- [[32633]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32633) Add 'page-section' to cataloging and authority pages
- [[32587]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32587) Add page-section to items with no checkouts report
- [[32586]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32586) Reindent items with no checkouts reports template
- [[32482]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32482) Reindent holds awaiting pickup template
- [[32690]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32690) Reindent the serial collection template
- [[32738]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32738) Correct upload local cover image title tag
- [[32618]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32618) Add 'page-section' to various administration pages
- [[32562]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32562) Reindent the about page template
- [[31932]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31932) The basket summary page template needs a cleanup
- [[32229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32229) Typo: Items missing from bundle at checkin for %s
- [[32628]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32628) Add 'page-section' to various serials pages
- [[32616]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32616) Add 'page-section' to various acquisitions pages
- [[32632]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32632) Add 'page-section' to some tools pages
- [[32400]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32400) Add page-section to tables for end of year rollover (acq)
- [[32319]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32319) Give header search submit button more padding
- [[32095]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32095) Remove bullets from statuses in inventory tool
- [[32378]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32378) Incorrect label for in identity provider domains
- [[32061]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32061) <span> in the title of z39.50 servers page
- [[32300]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32300) Add page-section to cataloguing plugins (cat)
- [[32200]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32200) Add page-section checkout notes page (circ)
- [[32323]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32323) Correct focus state of some DataTables controls
- [[32320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32320) Remove text-shadow from header menu links
- [[32074]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32074) Edit vendor has a floating toolbar, but still an additional save button at the bottom
- [[32283]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32283) Capitalization: opac users of this domain to login with this identity provider
- [[32282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32282) Capitalization: User id
- [[28235]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28235) Custom cover images are very large in staff search results and OPAC details
- [[32213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32213) Reindent item search fields template
- [[32310]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32310) Correct CSS in the staff interface which still uses old color scheme
- [[32303]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32303) DT pagination on system preference search result
- [[32198]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32198) Add page-section to stock rotation stages list (cat)
- [[32238]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32238) Add page-section to label creator pages
- [[32254]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32254) Add 'page-section' to various tools pages
- [[32308]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32308) Update Chocolat image viewer CSS to conform to redesign color scheme
- [[32270]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32270) Add page-section to label creator - manage label layouts
- [[32212]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32212) Add separate Bootstrap 4 node module for the OPAC
- [[32109]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32109) Toolbar containing text links lacks spacing
- [[32182]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32182) Replace static tabs markup with Bootstrap
- [[32112]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32112) Move "Delete selected items" button to new line
- [[32207]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32207) Add page-section to some circulation pages
- [[32199]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32199) Add page-section to various patron pages
- [[32197]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32197) Add page-section to catalog's stock rotation page
- [[32042]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32042) Add page-section to catalog's item detail view
- [[32193]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32193) Reindent item details template
- [[32147]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32147) Capitalization: E-Resource management should be E-resource management
- [[32099]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32099) Consistent classes for primary buttons: Assorted templates
- [[32098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32098) Consistent classes for primary buttons: Clubs and rotating collections
- [[32096]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32096) Consistent classes for primary buttons: Tools
- [[32094]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32094) Consistent classes for primary buttons: Serials
- [[32086]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32086) Consistent classes for primary buttons: Patrons
- [[32179]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32179) ERM is missing page-sections
- [[32072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32072) Consistent classes for primary buttons: Cataloging
- [[32158]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32158) Specify due date field is very long now
- [[31759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31759) Improve styling of tabs
- [[32145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32145) Cancel hold modal confirm/submit button has a white background and text can't be read
- [[32073]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32073) Consistent classes for primary buttons: Circulation
- [[32165]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32165) Add page-section to some catalog pages
- [[32108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32108) Change "x" icon to replace patron when scheduling a pickup
- [[13600]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13600) XSLT: 8xx not showing if there is no 4xx
- [[32091]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32091) Consistent classes for primary buttons: Reports
- [[32097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32097) Consistent classes for primary buttons: Lists
- [[32102]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32102) Improve specificity of batch record modification breadcrumbs
- [[32043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32043) Circulation alerts can overlap other elements on smaller screens
- [[32071]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32071) Consistent classes for primary buttons: Catalog
- [[32101]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32101) Add padding to floating toolbars
- [[32148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32148) Buttons must inherit Bootstrap size classes
- [[31928]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31928) Add page-section to callnumber browser value builder (cat)
- [[32146]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32146) Add page-section to course reserves
- [[31828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31828) Add page-section to list of open invoices on receive shipment page (acq)
- [[31827]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31827) Add page-section to list to log viewer
- [[31826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31826) Add page-section to item form on order receive page (acq)
- [[31824]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31824) Add page-section to list of pending/received orders (acq)
- [[31823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31823) Add page-section to uncertain prices page (acq)
- [[31414]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31414) Set focus for cursor to Name when adding additional fields for baskets or subscriptions
- [[32088]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32088) Consistent classes for primary buttons: Patron card creator
- [[32087]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32087) Consistent classes for primary buttons: Course reserves
- [[32085]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32085) Consistent classes for primary buttons: Labels
- [[30718]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30718) Use flatpickr's altInput option everywhere
- [[31943]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31943) Date inputs wider than other inputs
- [[32070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32070) Consistent classes for primary buttons: Acquisitions
- [[32068]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32068) Consistent classes for primary buttons: Administration
- [[32044]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32044) Yellow buttons are styled differently in different spots
- [[32050]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32050) Add 'page-section' to calendar page
- [[32014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32014) Tweak style of checkout settings panel
- [[32038]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32038) Sidebar and footer style improvements on suggestions page
- [[32022]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32022) Style tweaks to fieldsets and page-section
- [[31986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31986) Add page-section to various administration pages
- [[31993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31993) Improve specificity of authorized values breadcrumbs
- [[31991]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31991) Restore style of sidebar forms
- [[31996]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31996) Make note-style messages consistent with dialogs
- [[31973]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31973) Restore background color to message-style alerts
- [[31718]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31718) Change the IF ELSE values in MARC subfields structure breadcrumbs to facilitate translation
- [[31888]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31888) In Elasticsearch mappings page save button should be yellow
- [[31885]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31885) In renew page submit button should be yellow
- [[31884]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31884) In check in page submit button should be yellow
- [[30487]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30487) Convert checkout and patron details page tabs to Bootstrap
- [[30309]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30309) Convert lists tabs in the staff interface to Bootstrap
- [[31402]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31402) Update tools sidebar to match tools start page
- [[31625]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31625) Reindent tools home and tools sidebar
- [[30304]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30304) Reindent lists template in the staff interface
- [[31528]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31528) Replace scss-lint configuration with one for stylelint
- [[31529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31529) Fix errors in SCSS files raised by stylelint
- [[27195]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27195) Set focus for cursor to city input box when creating new cities
- [[27191]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27191) Set focus for cursor to category code input box when creating new patron categories
- [[27193]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27193) Set focus for cursor to patron attribute type code input box when creating new patron attributes
- [[27436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27436) Set focus for cursor to report name field when creating new SQL report
- [[31398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31398) Set focus for cursor to framework code field when creating a new authority type
- [[31399]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31399) Set focus for cursor to first input field when adding new classification source, filing rule, or splitting rule
- [[31400]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31400) Set focus for cursor to matching rule code when adding a new matching rule
- [[31397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31397) Set focus for cursor to framework code field when creating a new bibliographic framework
- [[27081]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27081) Notes missing from lost items report column configuration when CSV export is active
- [[31404]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31404) Update circulation sidebar to match circulation start page
- [[31490]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31490) Terminology: change "staff client" to "staff interface" in marc-overlay-rules
- [[31435]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31435) "Configure this table" appears for non-configurable tables
- [[31428]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31428) Shorten new button text "Configure this table"
- [[29723]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29723) Add a "Configure table" button for KohaTable tables
- [[30389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30389) Switch to Bootstrap tabs on the page for adding orders from MARC file
- [[22276]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22276) Add client storage of user-selected DataTables configuration
- [[30333]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30333) Move view actions on acquisitions receipt summary page into menu
- [[30785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30785) Typo in SIP2SortBinMapping
- [[30859]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30859) Upgrade jQuery Validation plugin from v1.19.1
- [[30917]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30917) Improve course reserves breadcrumbs
- [[30388]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30388) Fix some errors in the template for ordering from a MARC file
- [[30384]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30384) Reindent template for ordering from a MARC file

## Test Suite

- [[33403]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33403) Letters.t: Foreign key exception if you do not have a numberpattern with id=1
- [[33416]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33416) Agreements.ts is failing
- [[33402]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33402) ERM Cypress tests needs to be moved to their own directory
- [[32648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32648) Search.t is failing if run after Filter_MARC_ViewPolicy.t
- [[32710]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32710) UI/Form/Builder/Item.t is failing randomly
- [[33282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33282) Cypress tests are failing
- [[33235]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33235) Cypress tests are failing
- [[33263]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33263) selenium/patrons_search.t is failing randomly
- [[33214]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33214) Make sure cache is cleared properly
- [[33054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33054) Koha/Acquisition/Order.t is failing randomly
- [[32353]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32353) reserves.item_group_id should be undefined in tests by default
- [[32898]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32898) Cypress tests are failing
- [[32673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32673) Remove misc/load_testing/ scripts
- [[32376]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32376) selenium/authentication_2fa.t produces artefact
- [[32650]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32650) Koha/Holds.t is failing randomly
- [[28670]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28670) api/v1/patrons_holds.t is failing randomly
- [[32366]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32366) BatchDeleteBiblio task should have tests to prove indexing all takes place in one step
- [[29274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29274) z_reset.t is wrong
- [[32351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32351) Fix all TestBuilder calls failing due to wrong column names
- [[32350]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32350) We should die if TestBuilder is passed a column we're not expecting
- [[32352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32352) xt/check_makefile.t failing on node_modules
- [[32304]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32304) Fix subtest search_limited and purge in BackgroundJobs.t
- [[32343]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32343) Koha/Patron.t is failing randomly
- [[32269]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32269) Circulation.t is failing randomly
- [[32010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32010) selenium/authentication_2fa.t is failing randomly
- [[32268]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32268) t/db_dependent/XSLT.t is failing randomly
- [[32267]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32267) Koha/ERM/Agreements.t is failing
- [[32131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32131) Cypress tests are failing if ERMModule is off
- [[32240]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32240) api/erm_users.t fails if checkouts exist
- [[32064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32064) Add missing test to template permission calculation
- [[31992]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31992) t::lib::Mocks::Zebra still using old stage for import page
- [[31870]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31870) Cleaning up t/db_dependent/Context.t
- [[31676]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31676) Make db_dependent/Circulation.t tests more robust
- [[31108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31108) rename ./t/00-check-atomic-updates.pl extension to *.t

## Tools

- [[33576]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33576) Records are not indexed when imported if using Elasticsearch
- [[33412]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33412) (bug 15869 follow-up) Overlay record framework is always setting records to original framework
- [[33637]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33637) Batch patron modification broken
- [[33156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33156) Batch patron modification tool is missing search bar and other attributes
- [[32041]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32041) OPAC and staff interface results page do not honor SyndeticsCoverImageSize
- [[32164]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32164) Add link to MARC modification templates from batch record modification page
- [[32804]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32804) Importing and replacing items causes inconsistency when itemnumber match and biblio match disagree
- [[32967]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32967) Recalls notices are using the wrong database columns
- [[30869]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30869) Stock rotation rotas cannot be deleted
- [[22428]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22428) MARC modification template cuts text to 100 characters
- [[32600]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32600) Housebound module needs page-section treatment
- [[32631]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32631) Error when previewing record during batch record modification
- [[32054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32054) GetImportRecordMatches returns the wrong match when passed 'best only'
- [[31891]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31891) Regression: show "MARC staging results" with clear link to manage staged batch
- [[32104]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32104) Console error on additional_content.pl after saving
- [[32103]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32103) Content field in HTML customizations is too narrow ( CodeMirror )
- [[31782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31782) Patron autocomplete broken when using js/autocomplete/patrons.js
- [[31752]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31752) Alignment of labels in notices is wonky
- [[27920]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27920) Add ability to update patron expiration dates when importing patrons
- [[31553]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31553) News item contents field does not always expand when you click on a non-default language
- [[31644]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31644) MARCModification template fails to copy to/from subfield 0
- [[31754]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31754) Improve appearance of behavior of DataTables controls
- [[31373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31373) Notice template validation is missing INCLUDE_PATH
- [[6936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=6936) Allow to limit on multiple itemtypes when exporting bibliographic records
- [[31385]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31385) Additional contents: Allow searching a CMS page by code in multilanguage env
- [[31211]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31211) Check slips and notices for valid Template Toolkit and report errors
- [[31000]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31000) Use of uninitialized value $record_type in string eq
- [[30889]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30889) Background jobs lead to wrong/missing info in logs

## Transaction logs

- [[28799]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28799) Action logs should capture lost items found

## Web services

- [[33504]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33504) ILS-DI does not record renewer_id for renewals creating issue with renewal history view
- [[30636]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30636) ILS-DI shows incorrect availability when not for loan by item type

## Z39.50 / SRU / OpenSearch Servers

- [[33231]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=33231) (Bug 30813 follow-up) No publication date nor edition statements in Z39.50 biblio search results
- [[26433]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26433) Control number search option missing from SRU mapping options


