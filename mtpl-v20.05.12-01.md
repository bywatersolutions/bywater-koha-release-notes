
# Release Notes for mtpl-v20.05.12-01

## Acquisitions

- [[27203]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27203) Order unitprice is not set anymore and  totals are 0
- [[28223]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28223) Total for budgets is incorrect when child funds have negative values
- [[23195]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23195) Shipping costs are inconsistent in where displayed
- [[26989]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26989) Ensure no CR occurs in an EDIFACT order message

## Architecture, internals, and plumbing

- [[20982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20982) opac-shelves.pl vulnerable to Cross-site scripting attacks
- [[15720]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15720) OCLC Connexion daemon does not verify username or password
- [[27942]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27942) QOTD: quote CSV uploads may contain JavaScript payloads (XSS)
- [[28367]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28367) Wrong plack condition in C4/Auth_with_shibboleth.pm
- [[28302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28302) Koha does not work with CGI::Compile 0.24
- [[28293]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28293) Wrong key used in Patrons::Import->generate_patron_attributes
- [[28244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28244) Ukrainian is misspelled in language tables for English
- [[28221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28221) process_message_queue.pl missing `use Try::Tiny`

## Authentication

- [[20854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20854) Redirect after logout with CAS 3.0 broken

## Browser compatibility

- [[27282]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27282) Printing broken in some versions of Chrome

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - More changes
- NOT IN BUGZILLA - Translation fixes for 20.05.12

## Cataloging

- [[27837]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27837) Permanent location is reverted to location when location updated and permanent_location mapped to MARC field
- [[23406]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23406) When using an authorised value for suppression, record doesn't show as suppressed in staff interface
- [[24564]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24564) The adding of new subfields according to IFLA updates doesn't respect existing tab
- [[27577]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27577) Autolink bibs after generating the biblionumber

## Circulation

- [[28202]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28202) Pickup libraries not sorted by name when placing hold
- [[28148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28148) JavaScript error when printing transfer slip for existing transfer
- [[28064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28064) Transits are not created at check in despite user responding 'Yes, print slip' to the prompt
- [[27836]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27836) Document that CircControl syspref changes which library's calendar to use
- [[28013]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28013) Improvements to CanBookBeRenewed

## Command-line Utilities

- [[28255]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28255) Follow up to bug 23463 - use item_object in misc/cronjobs/delete_items.pl
- [[27819]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27819) Spurious errors when running delete_records_via_leader.pl
- [[28028]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28028) Remove broken fix_onloan.pl maintenance script

## Database

- [[28298]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28298) DBRev 19.12.00.076 broken

## Fines and fees

- [[28266]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28266) Misspelled word: recieved in cashup confirmation pop-up
- [[28181]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28181) Archived debit type still shows as available in Point of Sale
- [[27811]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27811) Manage patrons fines and fees (updatecharges)  subpermissions shows links/buttons that cannot be accessed
- [[28144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28144) Historical OVERDUE fines may not have an issue_id

## Hold requests

- [[25760]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25760) Holds ratio report is not reporting on records with 1 hold
- [[28078]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28078) Add option to ignore hold counts when checking CanItemBeReserved

## Mana-kb

- [[27061]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27061) Double permission check in svc/mana/search

## MARC Authority data support

- [[28159]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28159) URI-encode existing values put into query string for z39.50 authority search

## Notices

- [[28258]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28258) Bad date formatting in AUTO_RENEWALS notice

## OPAC

- [[28241]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28241) OPACNoResultsFound {QUERY_KW} placeholder doesn't always match the search terms when commas are included in the search
- [[27566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27566) CSS rule not applying to HTML select / option -  displays with serif font ignoring rules

## Patrons

- [[28217]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28217) Several non-repeatable attributes when merging patrons
- [[26940]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26940) debarred comment in borrowers table is lost on patron modifications in memberentry.pl page

## Plugin architecture

- [[27120]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27120) Send biblio to Koha plugins hook 'intranet_catalog_biblio_tab'
- [[27114]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27114) Use Template Toolkit plugin for Koha plugins hook 'intranet_catalog_biblio_tab'

## REST API

- [[28248]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28248) Exception when getting all orders

## Searching

- [[28213]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28213) Deleting a patron or patron club causes server error on searching
- [[26533]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26533) Searching authorities using 'is exactly' doesn't work as expected

## Searching - Elasticsearch

- [[27724]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27724) Use lenient also in Elasticsearch authorities search

## Serials

- [[27842]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27842) Incorrect biblionumber handling in serials subscriptions

## SIP2

- [[28320]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28320) SIP SC Status message should check the DB connection
- [[28054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28054) SIPServer.pm is a program and requires a shebang

## System Administration

- [[28345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28345) Patron attributes no longer have option to select empty class
- [[28207]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28207) Crash when seeing MARC structure of a new framework
- [[27968]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27968) MARC framework CSV and ODS import incomplete or corrupted

## Templates

- [[28351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28351) Cannot set restrictions when 'dateformat' is other than 'us'
- [[26471]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26471) Datatables js error on missing pdfmake.min.js.map
- [[27232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27232) Missing spaces in member-alt-contact-style.inc make some strings appearing twice in po
- [[27861]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27861) Warning in C4/XSLT.pm - use of uninitialized value in numeric eq (==)
- [[27827]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27827) Authority type input field for new authority types should be wider
- [[27695]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27695) Fix style of messages on Elasticsearch configuration page

## Test Suite

- [[28288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28288) XISBN.t is failing is 500 is returned by the webservice
- [[28250]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28250) Debug from Selenium error handler is no longer working
- [[28249]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28249) Selenium->wait_for_element_visible can fall in an infinite loop
- [[28234]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28234) TestBuilder->build_sample_biblio does not deal correctly with encoding
- [[26405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26405) Circulation.t fails on 'AddRenewal left both fines'

## Tools

- [[28229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28229) Hide clubs from place a hold screen if no clubs exist
- [[27594]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27594) Add access to public download link for publicly-accessible uploads
- [[28170]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28170) Downloading some files via Tools - Upload is broken
- [[21818]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21818) Don't use AutoCommit flag in stage-marc-import.pl


