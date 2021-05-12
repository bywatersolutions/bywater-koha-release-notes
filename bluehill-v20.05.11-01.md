
# Release Notes for bluehill-v20.05.11-01

## Acquisitions

- [[28103]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28103) Barcode fails when adding item during order receive
- [[28077]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28077) Missing colon on suggestion modification page
- [[27900]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27900) regression: add from existing record with null results deadends
- [[28003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28003) Invoice adjustments using inactive budgets do not indicate that status

## Architecture, internals, and plumbing

- [[28156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28156) Koha::Account::Line->renewable must be named is_renewable
- [[28053]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28053) Warning in C4::Members::patronflags
- [[27807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27807) API DataTables Wrapper fails for ordered on multiple columns

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions - Build and push Docker Image
- NOT IN BUGZILLA - Translation fix again for 20.05.11
- NOT IN BUGZILLA - Fix translations for 20.05.11

## Cataloging

- [[28123]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28123) Commas in file names of uploaded files cause inconsistently broken 856$u links
- [[27739]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27739) Advanced editor should use DefaultCountryField008 system preference rather than hardcoding xxu
- [[27738]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27738) Set fallback for unset DefaultCountryField008 to |||, "no attempt to code"

## Command-line Utilities

- [[27656]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27656) misc/cronjobs/longoverdue.pl better error message

## Fines and fees

- [[28147]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28147) Pass itemnumber when writing off a single debit
- [[27927]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27927) longoverdue cronjob renews items before marking lost when both RenewAccruingItemWhenPaid and  WhenLostForgiveFine  are enabled
- [[25508]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25508) Confusing renewal message when paying accruing fine with RenewAccruingItemWhenPaid turned off
- [[28097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28097) t/db_dependent/Koha/Account/Line.t test fails with FinesMode set to calculate

## Hold requests

- [[18729]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18729) Librarian unable to update hold pickup library from patron pages without "modify_holds_priority" permission
- [[27529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27529) Cannot place hold on OPAC if hold_fullfillment_policy is set to group and  OPACAllowUserToChooseBranch  not allowed
- [[27921]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27921) Timestamp in holds log is out of date when a hold is marked as waiting
- [[26999]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26999) "Any library" not translatable on the hold list

## Lists

- [[28069]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28069) Can't sort lists on staff client

## OPAC

- [[27979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27979) Multiple item URIs break redirect if TrackClicks enabled
- [[27726]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27726) OPACProblemReports cuts off message text
- [[28094]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28094) Fix bad encoding of OVERRIDE_SYSPREF_LibraryName
- [[27991]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27991) Message field for checkout notes should have a maxlength set
- [[27940]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27940) Fix missing email in OpacMaintenance page
- [[28021]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28021) OPAC detail page contains incorrect Bootstrap classes (20.05.x)

## Patrons

- [[28043]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28043) Some patron clubs operations don't work from later pages of results
- [[27937]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27937) Date of birth entered  without correct format causes internal server error
- [[26517]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26517) Avoid deleting patrons with permission

## Searching

- [[26679]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26679) Genre tags linking to subject search, causing null results
- [[27746]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27746) Use of uninitialized value $oclc in pattern match (m//) error at C4/Koha.pm
- [[28074]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28074) Browse controls on staff detail pages are sometimes weird
- [[27928]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27928) FindDuplicate is hardcoded to use Zebra

## Searching - Elasticsearch

- [[26312]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26312) Add some error handling during Elasticsearch indexing

## Serials

- [[27397]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27397) Serials: The description input field when defining numbering patterns is too short

## SIP2

- [[27936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27936) AllowItemsOnHoldCheckoutSIP does not allow checkout of items currently waiting for a hold
- [[28052]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28052) keys omitted in check for system preference override
- [[28054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28054) SIPServer.pm is a program and requires a shebang

## System Administration

- [[28121]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28121) Wrong punctuation on desk deletion
- [[27999]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27999) Display the description of authorized values category

## Templates

- [[28004]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28004) Incomplete breadcrumbs in authorized valued
- [[28042]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28042) Button corrections in OAI set mappings template
- [[28032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28032) Button corrections in point of sale pages

## Tools

- [[28015]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28015) Inventory tool fails when timeformat=12h
- [[28044]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28044) Calendar: Tables with closed days are no longer color coded
- [[26942]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26942) TinyMCE in the News Tool is still doing some types of automatic code cleanup
- [[27963]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27963) touch_all_items.pl script is not working at all

## Web services

- [[27584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27584) Improve OAI-PMH provider performance

## Z39.50 / SRU / OpenSearch Servers

- [[26528]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26528) Koha return no result if  there's  invalid records in Z39.50/SRU server reply
- [[28112]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28112) Z39.50 does not populate form with all passed criteria


