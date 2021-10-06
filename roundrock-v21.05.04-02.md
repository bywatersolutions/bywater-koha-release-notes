
# Release Notes for roundrock-v21.05.04-02

## Architecture, internals, and plumbing

- [[29139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29139) Paying gives ISE if UseEmailReceipts is enabled
- [[28772]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28772) Any user that can work with reports can see API keys of any other user
- [[28759]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28759) Users with pretty basic staff interface permissions can see/add/remove API keys of any other user
- [[28941]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28941) No filtering on suggestion at the OPAC
- [[28935]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28935) No filtering on patron's data on member entry pages (OPAC, self registration, staff interface)
- [[28929]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28929) No filtering on borrowers.flags on member entry pages (OPAC, self registration, staff interface)
- [[28373]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28373) Items fields not used in default XSLT
- [[28744]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28744) Class with empty/no to_api_mapping should generate an empty from_api_mapping
- [[28881]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28881) Suggestion not displayed on the order receive page

## Bywater Only

- NOT IN BUGZILLA - Fix translations for Koha 21.05.04
- NOT IN BUGZILLA - [21.05] Fix unit tests for t/Search.t

## Cataloging

- [[29137]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29137) Unwanted authorised values are too easily created via the cataloging module
- [[28812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28812) Authority tag editor only copies $a from record to search form

## Circulation

- [[28774]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28774) Warnings from GetIssuingCharge when rental discount is not set
- [[28891]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28891) RecordStaffUserOnCheckout display a new column but default sort column isn't changed
- [[25619]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25619) Updating an expiration date for a waiting hold won't save

## Hold requests

- [[29148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29148) Holds to Pull doesn't reflect item-level holds
- [[7703]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7703) Don't block bulk hold action on search results if some items can't be placed on hold

## MARC Authority data support

- [[21958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21958) _check_valid_auth_link checks too many subfields

## MARC Bibliographic data support

- [[10265]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10265) 8xx serial added entries need spaces and punctuation in XSLT display

## OPAC

- [[28885]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28885) OpacBrowseResults can cause errors with bad search indexes
- [[26223]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26223) The OPAC ISBD view does not display item information

## Patrons

- [[28392]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28392) streettype and B_streettype cannot be hidden via BorrowerUnwantedField
- [[21794]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21794) Incomplete address displayed on patron details page when City field is empty
- [[28882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28882) Incorrect permissions check client-side

## Searching

- [[29152]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29152) Change to default search behavior when limiting by branch
- [[28554]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28554) In itemsearch sort filters by description

## Staff Client

- [[29062]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29062) Patron check-in slip repeats data
- [[28722]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28722) tools/batchMod.pl needs to import C4::Auth::haspermission
- [[28912]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28912) Pseudonymization should display a nice error message when brcypt_settings are not defined
- [[20529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20529) Return to results link is truncated when the search contains a double quote

## System Administration

- [[28936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28936) Sort1 and Sort2 should be included in BorrowerUnwantedField and related sysprefs

## Templates

- [[28149]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28149) Improve internationalization and formatting on background jobs page

## Web services

- [[26195]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26195) Add a way to specify authorised values should be expanded [OAI]


