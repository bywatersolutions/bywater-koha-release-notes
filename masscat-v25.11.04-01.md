
# Release Notes for masscat-v25.11.04-01

## About

- [[41319]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41319) Link content of 'Contributing companies and institutions' to bug sponsors

## Architecture, internals, and plumbing

- [[39606]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39606) Cover change from bug 39294 with a Cypress test
- [[42353]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42353) Tell which version of node to use
- [[41916]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41916) SIP2 module cypress tests failing
- [[41587]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41587) node audit identified several vulnerable node dependencies
- [[42071]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42071) Suggestion does not load when viewing the suggestion
- [[41599]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41599) reports/acquisitions_stats.pl calls output_error incorrectly
- [[30803]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30803) output_error should not assume a 404 status
- [[41864]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41864) (Bug 40966 follow-up) Simple OPAC search generates warnings: Odd number of elements in anonymous hash
- [[41036]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41036) Koha::ImportBatch is not logging errors
- [[41857]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41857) Suggestions table actions broken (Update manager and Delete selected)
- [[39721]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39721) Remove GetSuggestion from C4/Suggestions.pm

## Bywater Only

- NOT IN BUGZILLA - DBRev 25.11.03.002
- NOT IN BUGZILLA - Bug 34000: Unit tests
- NOT IN BUGZILLA - Bug 42366: Fix debug_mode test for koha-conf.xml
- NOT IN BUGZILLA - Bug 42252: Prevent XSS when deleting a list at the OPAC
- NOT IN BUGZILLA - Bug 42136: Add tests
- NOT IN BUGZILLA - Bug 42254: (QA follow-up) Remove unused var, fixing a FIXME
- NOT IN BUGZILLA - Bug 42253: (QA follow-up) prevent XSS injection in data- attribute

## Cataloging

- [[40306]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40306) Use GET in form of value_builder/unimarc_field_4XX.pl
- [[40711]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40711) Fix value builder for 181 in UNIMARC
- [[41170]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41170) Highlight previously edited item on add items page
- [[41417]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41417) 500 error when creating new authorized values from additem.pl

## Circulation

- [[41338]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41338) Hold found dialog does not show item home and check-in libraries
- [[41134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41134) Add table settings to transfers
- [[41058]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41058) Using Show Checkouts button when LoadCheckoutsTableDelay is set causes collision/error. loadIssuesTableDelayTimeoutId  not assigned
- [[41518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41518) "Scheduled for automatic renewal" displays even if patron does not allow automatic renewals
- [[41886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41886) Biblio::check_booking counts checkouts on non-bookable items causing false clashes
- [[41131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41131) Libaray transfer limits basic editor allows one to prevent transfers from a library to itself and block related holds
- [[37707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37707) Lead/Trail times should work in combination

## Command-line Utilities

- [[41316]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41316) Using patron-homelibrary option for overdue notices does not change which rules are used
- [[38549]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38549) Make create_superlibrarian.pl script accept a name parameter
- [[28528]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28528) bulkmarcimport delete option doesn't delete biblio_metadata
- [[41097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41097) Deduping authorities script (dedup_authorities.pl) can die on duplicated ids

## Continuous Integration

- [[41368]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41368) Tools/ManageMarcImport_spec.ts is failing

## Database

- [[41409]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41409) Streetnumber has a different data type in borrower_modifications

## Fines and fees

- [[29923]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29923) Do not generate overpayment refund from writeoff of fine
- [[41761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41761) Updating accountlines note sets accountlines.date to current date

## I18N/L10N

- [[39580]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39580) Make Elasticsearch process_error error string translatable

## ILL

- [[40105]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40105) Patrons cannot add notes when creating an ILL

## Installation and upgrade (command-line installer)

- [[41337]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41337) koha-create --request-db and --populate-db creates log files owned by root (intranet-error.log, opac-error.log)

## Notices

- [[39749]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39749) RestrictPatronsWithFailedNotices should not trigger for DUPLICATE_MESSAGE failures
- [[41393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41393) Advance notices should set the reply to address

## OPAC

- [[41970]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41970) PA_CLASS does not show in fieldset ID on opac-memberentry.pl
- [[41558]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41558) Broken links to tab on opac-user
- [[25314]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25314) Make OPAC facets collapse

## Patrons

- [[41986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41986) Names in "Contact information" need more clarity
- [[21555]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21555) Merging Patrons allows for all patrons to be selected
- [[41904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41904) "Use of uninitialized value..." warning in del_message.pl
- [[41675]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41675) Username value is ignored in Patron quick-add form

## Reports

- [[41715]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41715) Argument "YYYY-MM-DD" isn't numeric in numeric lt (<)... warnings in issues_stats.pl
- [[40896]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40896) Run report button should be disabled after click

## Searching

- [[41496]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41496) Item search copy sharable link not working
- [[41444]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41444) Fetch transfers directly for search results

## Self checkout

- [[41645]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41645) Make self-checkout use responsive CSS
- [[41647]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41647) Make self-checkin use responsive CSS

## Serials

- [[41330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41330) Brace are not escaped in serials number management

## SIP2

- [[36752]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36752) Remove TODO about missing summary info in the SIP2 code
- [[41818]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41818) SIP2 message in AF field should be stripped of newlines and carriage returns
- [[41811]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41811) SIP server will inadvertently remove non-alphanumeric characters from the end of a message

## Staff interface

- [[41989]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41989) addbook shows the translated interface
- [[39055]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39055) Unauthenticated are not redirected properly in reports module after login
- [[41976]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41976) [Vue] LinkWrapper.vue isn't scoped properly
- [[41958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41958) Rename BibTex to BibTeX (with a capital X) for the staff interface cart and list download options (to match the OPAC)
- [[41692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41692) "See all charges" link in the guarantor details does not activate Guarantees charges tab
- [[41885]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41885) Rename iso2709 to MARC for the staff interface download options for the cart and lists (to match the OPAC)
- [[24949]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24949) Provide password visibility toggle / icon to unmask password on staff login screen

## System Administration

- [[41360]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41360) Transport cost matrix assumes all transfers are disabled upon first use

## Templates

- [[42014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=42014) Patron lists tab shows blank content when no patron lists exist
- [[41807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41807) Fix automatic tab selection on basket groups page
- [[41838]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41838) Fix automatic tab selection on MARC subfield edit pages
- [[40568]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40568) Various corrections to recalls templates
- [[40787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40787) Plugins buttons misaligned when search box is enabled

## Test Suite

- [[41384]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41384) SIP2/Accounts.ts  is failing randomly
- [[41830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41830) Acquisitions/Vendors_spec.ts is failing randomly
- [[41616]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=41616) Warnings on authority_hooks.t


