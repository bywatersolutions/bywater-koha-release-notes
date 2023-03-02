
# Release Notes for bywater-v22.05.10-01

## Acquisitions

- [[32406]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32406) Cannot search pending orders using non-latin-1 scripts
- [[32377]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32377) GetBudgetHierarchy slows down acqui/histsearch.pl
- [[32694]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32694) Keep current option for budgets in receiving broken

## Architecture, internals, and plumbing

- [[28672]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28672) Improve EDI debug logging
- [[32612]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32612) Koha background worker should log to worker-error/output.log
- [[18247]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18247) Remove SQL queries from branch_transfer_limit.pl administrative script
- [[32393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32393) background job worker explodes if JSON is incorrect
- [[32394]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32394) Long tasks queue is never used
- [[32561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32561) background job worker is still running with all the modules in RAM
- [[32573]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32573) background_jobs_worker.pl should ACK a message before it forks and runs the job
- [[31893]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31893) Some pages load about.tt template to check authentication rather than using checkauth
- [[32656]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32656) Script delete_records_via_leader.pl no longer deletes items

## Bywater Only

- NOT IN BUGZILLA - Correct increment verion db_rev
- NOT IN BUGZILLA - Fix translations for 22.05.10

## Cataloging

- [[29173]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29173) Button "replace authority record via Z39/50/SRU" doesn't pre-fill
- [[30250]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30250) Configure when to apply framework defaults when cataloguing
- [[32321]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32321) 006 field not correctly prepopulated in Advanced cataloging editor
- [[32692]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32692) Terminology: MARC framework tag subfield editor uses intranet instead of staff interface

## Circulation

- [[29792]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29792) Transfers created from 'wrong transfer' checkin are not sent if modal is dismissed
- [[29021]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29021) Automatic renewal due to RenewAccruingItemWhenPaid should not be considered Seen

## Fines and fees

- [[30254]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30254) New overdue fine applied to incorrectly when using "Refund lost item charge and charge new overdue fine" option in circ rules

## I18N/L10N

- [[32356]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32356) xx-XX installer dir /kohadevbox/koha/installer/data/mysql/xx-XX already exists.

## Lists

- [[32237]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32237) Batch delete records "no record IDs defined"

## Notices

- [[32221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32221) Password entry should be removed from placeholder list in notices editor

## OPAC

- [[8948]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8948) MARC21 field 787 doesn't display

## Patrons

- [[32574]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32574) memberresultst table cannot be column configured in 22.05.x
- [[32655]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32655) Variables showing in patron messaging preferences
- [[32570]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32570) City is duplicated in patron search if the patron has both city and state

## Plugin architecture

- [[32539]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32539) UI hooks can break the UI

## REST API

- [[32409]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32409) Cannot search cashups using non-latin-1 scripts

## Searching - Zebra

- [[32741]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32741) Attribute codes should not be repeated in bib1.att
- [[32416]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32416) arp - Accelerated reader point searches fail due to conflicting attribute

## Self checkout

- [[19188]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19188) Self checkout: Fine blocking checkout is missing currency symbol

## SIP2

- [[32408]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32408) If a fine can be overridden on checkout in Koha, what should the SIP client do?
- [[32537]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32537) Add 'no_block' option to sip_cli_emulator

## Staff interface

- [[31768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31768) Tags is a 'Tool' but doesn't include the tools nav sidebar
- [[32523]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32523) Shortcuts / Links to missing fields in MARC-Editor don't work as expected
- [[28314]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28314) Spinning icon is not always going away for local covers in staff
- [[32797]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32797) Cannot save OAI set mapping rule for subfield 0
- [[32644]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32644) Terminology: staff/intranet and biblio in plugins home page

## Templates

- [[31407]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31407) Set focus for cursor to Currency when adding a new currency
- [[32295]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32295) Punctuation: Filters :
- [[32290]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32290) ILL requests uses some wrong terminology
- [[32294]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32294) Capitalization: Enter your User ID...
- [[32289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32289) Punctuation: Delete desk "...?"
- [[32672]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32672) Incorrect CSS path to jquery-ui
- [[32688]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32688) Convert recalls awaiting pickup tabs to Bootstrap

## Tools

- [[26628]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26628) Clubs permissions should grant access to Tools page


