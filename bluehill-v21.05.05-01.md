
# Release Notes for bluehill-v21.05.05-01

## Acquisitions

- [[28956]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28956) Acquisitions: select correct default tax rate when receiving orders
- [[28960]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28960) EDI transfer_items uses a relationship where it's looking for a field

## Architecture, internals, and plumbing

- [[29420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29420) 401 Unauthorized pages come back as 200 OK under plack
- [[29134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29134) Patron search has poor performance when ExtendedAttributes enabled and many attributes match
- [[29175]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29175) finishreceive: Replace , by ;
- [[29139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29139) Paying gives ISE if UseEmailReceipts is enabled
- [[28373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28373) Items fields not used in default XSLT
- [[28992]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28992) Resolve warning from undefined BIG_LOOP

## Authentication

- [[28914]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28914) Wrong wording in authentication forms

## Bywater Only

- NOT IN BUGZILLA - DBRev 21.05.05.000
- NOT IN BUGZILLA - Fix translations for Koha 21.05.05

## Cataloging

- [[29137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29137) Unwanted authorised values are too easily created via the cataloging module
- [[27461]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27461) Fix field 008 length below 40 positions in cataloguing plugin
- [[28829]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28829) Useless single quote escaping in value_builder/unimarc_field_4XX.pl
- [[28676]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28676) AutoCreateAuthorities can repeatedly generate authority records when using Default linker and heading is cached

## Circulation

- [[29026]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29026) Behavior change when an empty barcode field is submitted in circulation
- [[28653]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28653) Sorting loans by due date doesn't work after renewing
- [[28985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28985) Negative rental amounts can be saved but not enforced
- [[21093]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21093) Specified due date incorrectly retained when using fast add

## Command-line Utilities

- [[29216]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29216) Correct --where documentation in update_patrons_category.pl
- [[28352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28352) Errors in search_for_data_inconsistencies.pl relating to authorised values and frameworks
- [[29078]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29078) Division by zero in touch_all scripts
- [[29076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29076) cleanup_database.pl dies of passed zebraqueue and not confirm

## Hold requests

- [[28510]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28510) Skip processing holds queue items from closed libraries when HoldsQueueSkipClosed is enabled
- [[29049]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29049) Holds page shows too many priority options in pulldown
- [[29073]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29073) Hold expiration added to new holds when DefaultHoldExpirationdate turned off

## MARC Authority data support

- [[24698]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24698) UNIMARC authorities leader plugin

## OPAC

- [[20277]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20277) Link to host item doesn't work in analytical records if 773$a is present
- [[29172]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29172) Can't use controlfields with CustomCoverImagesURL
- [[28930]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28930) Cardnumber is lost if an invalid self registration form is submitted to the server, and the server side form validation fails
- [[29128]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29128) Trailing whitespace in Browse shelf link on opac-detail.tt
- [[29091]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29091) Correct display of lists and tags on search results
- [[29067]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29067) Remove duplicate conditional statement from OPAC messaging settings title
- [[28934]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28934) OPAC registration form design is not consistent
- [[29064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29064) OPAC duplicate "Most popular titles" in 'title' tag
- [[29070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29070) Accessibility: OPAC Purchase Suggestions on search results page has insufficient contrast
- [[29068]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29068) Accessibility: OPAC search results summary text has insufficient contrast
- [[29065]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29065) Accessibility: OPAC clear search history link has insufficient contrast
- [[29038]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29038) Accessibility: OPACUserSummary heading doesn't have sufficient contrast
- [[29037]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29037) Accessibility: OPAC links don't have sufficient contrast
- [[29035]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29035) Accessibility: OPAC masthead_search label doesn't have sufficient contrast ratio
- [[29034]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29034) Accessibility: OPAC nav-links don't have sufficient contrast ratio
- [[28845]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28845) OpacAddMastheadLibraryPulldown does not respect multibranchlimit in OPAC_SEARCH_LIMIT

## Patrons

- [[29215]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29215) In patron form collapsing "Patron guarantor" display errors
- [[29025]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29025) Saved auth login and password are pre-filled in patron creation form
- [[18747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18747) Select All in Add Patron Option in Patron Lists only selects the first 20 entries

## Plugin architecture

- [[28303]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28303) Having multiple pluginsdir causes plugin_upload to try to write to the opac-tmpl folder
- [[28228]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28228) Warns from plugins when metadata value not defined for key

## Reports

- [[29271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29271) Cash register report not displaying or exporting correctly
- [[29279]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29279) Holds ratio report not sorting correctly

## REST API

- [[29157]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29157) Cannot set date/date-time attributes to NULL
- [[29072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29072) Move reference route /cities spec to YAML

## Searching

- [[28826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28826) Facet sort order differs between search engines

## Searching - Elasticsearch

- [[25030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25030) IncludeSeeFromInSearches not honoured in Elasticsearch
- [[28484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28484) Elasticsearch fails to parse query if exclamation point is in 245$a
- [[28316]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28316) Fix ES crashes related to various punctuation characters

## SIP2

- [[28464]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28464) Cancelling a waiting hold via SIP returns a failed response even when cancellation succeeds

## Staff Client

- [[29244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29244) alert/error and message dialogues should have the same width
- [[29131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29131) Row striping breaks color coding on item circulation alerts
- [[29062]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29062) Patron check-in slip repeats data
- [[28472]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28472) UpdateItemLocationOnCheckin not updating items where location is null

## System Administration

- [[29298]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29298) "Managing library" missing from histsearch table settings
- [[29004]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29004) Update GoogleOpenIDConnect preference to make it clear that it is OPAC-only
- [[29056]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29056) Remove demo functionality remnants

## Templates

- [[28579]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28579) Typo: No record have been imported because they all match an existing record in your catalog.
- [[28470]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28470) Typo: Are you sure you with to chart this report?
- [[29133]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29133) Wrong string format in select2.inc
- [[28438]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28438) Capitalization: Various corrections
- [[28927]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28927) Id opacmainuserblock used twice in OPAC

## Test Suite

- [[27155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27155) Include identifier test in Biblio_and_Items_plugin_hooks.t


