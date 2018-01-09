
# Release Notes for barcodeprfx-v17.05.07-01

## Acquisitions

- [[19813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19813) MarcItemFieldsToOrder cannot handle a tag not existing

## Architecture, internals, and plumbing

- [[19655]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19655) To.json doesn't escape newlines which can create invalid JSON

## Bywater Only

- NOT IN BUGZILLA - Restore the storing of itemnumber for writeoffs
- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Bug 19614: Fix XSS in members/pay.pl
- NOT IN BUGZILLA - Bug 19612: Fix XSS in members/memberentry.pl
- NOT IN BUGZILLA - Bug 19611: Fix XSS Flaws in supplier.pl
- NOT IN BUGZILLA - Bug 19319: Only fetch the record if it exists
- NOT IN BUGZILLA - Bug 19570: Add autocomplete to opac-main as well
- NOT IN BUGZILLA - Bug 19569: Set X-Frame-Options=SAMEORIGIN - opac-showmarc.ok
- NOT IN BUGZILLA - Bug 19568: Escape url params with url filter - opac-opensearch.tt

## Cataloging

- [[19595]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19595) Clicking plugin link does not fill item's date acquired field
- [[18833]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18833) plugin unimarc_field_210c pagination error
- [[19646]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19646) value_builder marc21_linking_section template is broken

## Command-line Utilities

- [[19190]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19190) Silly calculation of average time in touch_all scripts

## Database

- [[19724]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19724) Add timestamp to biblio_metadata and deletedbiblio_metadata

## Hold requests

- [[19533]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19533) Hold pulldown for itemtype is empty if hold placement needs override

## Label/patron card printing

- [[10222]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10222) Error when saving Demco label templates
- [[19681]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19681) label-item-search.pl result count formatting error when there is only one page

## Notices

- [[18990]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18990) Overdue Notices are not sending through SMS correctly

## OPAC

- [[12497]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12497) Make OPAC search history feature accessible when it should
- [[19640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19640) IdRef webservice display is broken

## Packaging

- [[18907]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18907) Warning "dpkg-source: warning: relation < is deprecated: use << or <="

## Reports

- [[19638]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19638) False positives for 'Update SQL' button

## System Administration

- [[12768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12768) Replacement cost and processing fee management

## Templates

- [[19751]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19751) Holds awaiting pickup report should not be fixed-width
- [[19692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19692) Unclosed div in opac-shelves.tt

## Test Suite

- [[19775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19775) Search/History.t is failing randomly

## Tools

- [[19674]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19674) Broken indicators of changed fields in manage staged MARC records template
- [[19643]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19643) Pagination buttons on staged marc management are stacking instead of inline
- [[19683]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19683) Export.pl does not populate the Authority Types dropdown correctly



# Release Notes for barcodeprfx-v17.05.06-01

## Acquisitions

- [[19596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19596) Internal server error if open order with deleted biblio / null biblionumber
- [[19195]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19195) Noisy warns when creating or editing a basket
- [[18999]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18999) Acq: Shipping cost not included in total spent on acq home and funds page
- [[19425]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19425) Adding orders from order file with multiple budgets per record triggers error
- [[19296]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19296) Tax is being subtracted from orders when vendor price does not include gst and ordering from a file
- [[19180]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19180) Vendor name is missing from breadcrumbs when closing an order

## Architecture, internals, and plumbing

- [[19344]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19344) DB fields login_attempts and lang may be inverted
- [[19317]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19317) Move of checkouts - Remove leftover
- [[18584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18584) Our legacy code contains trailing-spaces

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[19503]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19503) Duplicating a dropdown menu subfield yields an empty subfield tag
- [[18422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18422) Add Select2 to authority editor
- [[16204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16204) Show friendly error message when trying to edit record which no longer exists

## Circulation

- [[19487]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19487) Internal server error when writing off lost fine for item not checked out
- [[19374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19374) CircSidebar overlapping transferred items table

## Hold requests

- [[19135]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19135) AllowHoldsOnPatronsPossessions is not working

## MARC Authority data support

- [[19415]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19415) FindDuplicateAuthority is searching on biblioserver since 16.05
- [[17380]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17380) Resolve several problems related to Default authority framework
- [[18801]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18801) Merging authorities has an invalid 'Default' type in the merge framework selector
- [[18811]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18811) Visibility settings inconsistent between framework and authority editor

## OPAC

- [[19345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19345) SendMail error does not display error message in password recovery
- [[16463]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16463) OPAC discharge page should warn the user about checkouts before they request
- [[19068]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19068) OPAC purchase suggestion doesn't allow users to enter quantity of items

## Patrons

- [[19398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19398) Wrong date format in quick patron search table
- [[15644]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15644) City dropdown default selection when modifying a patron matches only on city
- [[12346]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12346) False patron modification alerts on members-home.pl

## Reports

- [[19495]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19495) Automatic report conversion needs to do global replace on 'biblioitems' and 'marcxml'
- [[18742]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18742) Circulation statistics wizard no longer exports the total row

## Searching - Elasticsearch

- [[18374]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18374) Respect QueryAutoTruncate syspref in Elasticsearch

## Serials

- [[19315]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19315) Routing preview may use wrong biblionumber

## SIP2

- [[16755]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16755) Allow SIP2 field DA (hold patron name) to be customized

## Staff Client

- [[18884]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18884) Advanced search on staff client, Availability limit not properly limiting
- [[19193]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19193) When displaying the fines of the guarantee on the guarantor account, price is not in correct format.

## System Administration

- [[12768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12768) Replacement cost and processing fee management
- [[16726]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16726) Text in Preferences search box does not clear
- [[15173]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15173) SubfieldsToAllowForRestrictedEditing not working properly

## Templates

- [[19329]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19329) IntranetSlipPrinterJS label is obsoleted

## Test Suite

- [[19423]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19423) DecreaseLoanHighHolds.t is failing randomly
- [[17664]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17664) Silence non-zebra warnings in t/db_dependent/Search.t
- [[19386]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19386) t/db_dependent/SIP/Patron.t is failing randomly
- [[19405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19405) t/db_dependent/api/v1/holds.t fails randomly
- [[19403]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19403) Again and again, Circulation.t is failing randomly
- [[19392]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19392) auth_values_input_www.t does not clean up
- [[19307]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19307) t/db_dependent/Circulation/NoIssuesChargeGuarantees.t fails if AllowFineOverride set to allow
- [[19337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19337) Allow basic_workflow.t be configured by ENV
- [[19262]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19262) pod_spell.t does not work


