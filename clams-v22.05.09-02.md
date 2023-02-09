
# Release Notes for clams-v22.05.09-02

## Acquisitions

- [[32016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32016) Fix 'clear filter' button behavior on datatable saving their state
- [[31459]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31459) Make order receive page faster on systems with many budgets
- [[29554]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29554) neworderempty.pl may create records with biblioitems.itemtype NULL
- [[31587]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31587) Basket not accessible from ACQORDER notice
- [[31649]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31649) Acquisition basket CSV export fails if biblio does not exist

## Architecture, internals, and plumbing

- [[32465]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32465) koha-worker debian script missing 'queue' in help
- [[32481]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32481) Rabbit times out when too many jobs are queued and the response takes too long
- [[32330]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32330) Table background_jobs is missing indexes
- [[32457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32457) CGI::param called in list context from acqui/addorder.pl line 182
- [[31675]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31675) Remove packages from debian/control that are no longer used
- [[31873]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31873) Can't call method "safe_delete" on an undefined value at cataloguing/additem.pl
- [[32242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32242) The job has not been sent to the message broker: (Wide character in syswrite ... )
- [[31196]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31196) Key "default_value_for_mod_marc-" cleared from cache but not set anymore
- [[31920]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31920) Unit test t/db_dependent/Holds.t leaves behind database cruft
- [[31776]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31776) Typo in cleanup_database.pl cron's help/usage
- [[31785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31785) Adding or editing library does not respect public flag
- [[31469]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31469) log4perl.conf: Plack logfiles need %n in conversionpattern
- [[26648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26648) Prevent internal server error if item attached to old checkout has been removed
- [[20457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20457) Overdue and pre-overdue cronjobs not skipping phone notices
- [[31441]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31441) Koha::Item::as_marc_field ignores subfields where kohafield is an empty string

## Bywater Only

- NOT IN BUGZILLA - Github Actions - Update command to check if NCIP server exists for this version
- NOT IN BUGZILLA - Bug 32208: Extend Auth.t
- NOT IN BUGZILLA - Bug 31908: Add selenium tests

## Cataloging

- [[31881]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31881) Link in MARC view does not work
- [[31682]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31682) Silence warn when using automatic linker in biblio editor

## Circulation

- [[28975]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28975) Holds queue lists can show holds from all libraries even with IndependentBranches
- [[31903]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31903) Article requests: Edit URLs link missing in the New tab
- [[30944]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30944) Fix single cancel recall button in recalls tab in staff interface and correctly handle cancellations with branch transfers

## Command-line Utilities

- [[32012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32012) runreport.pl should use binmode UTF-8

## Documentation

- [[27315]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27315) The man pages for the command line utilities do not display properly

## Fines and fees

- [[22042]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22042) BlockReturnofWithdrawn Items does not block refund generation when item is withdrawn and lost
- [[29987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29987) Manual credits are not recorded for a register

## Hold requests

- [[31575]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31575) Missing warning for holds where AllowHoldPolicyOverride can be used to force a hold to be placed
- [[31540]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31540) Holds reminder cronjob should consider expiration date of holds, and not send notices if hold expired

## I18N/L10N

- [[31738]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31738) Unstranslatable string in checkouts.js for recalls
- [[30517]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30517) Translation breaks editing parent type circulation rule

## Lists

- [[32302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32302) "ISBN" label shows when no ISBN data present when sending list

## MARC Authority data support

- [[19693]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19693) Update of an authority record creates inconsistency when the heading tag is changed
- [[31660]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31660) MARC preview for authority search results comes up empty

## MARC Bibliographic data support

- [[31869]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31869) Unable to save thesaurus value to frameworks subfields

## Notices

- [[27265]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27265) process_message_queue.pl cron should be able to take multiple types as a parameter

## OPAC

- [[32597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32597) Article requests not stacking in patron view
- [[32114]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32114) Template error in OPAC search results RSS
- [[31685]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31685) Article request count in table caption of opac-user missing

## Packaging

- [[31588]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31588) Update cpanfile for new OpenAPI versions

## Patrons

- [[32491]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32491) Can no longer search patrons in format 'surname, firstname'
- [[32505]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32505) Cannot search by dateofbirth in specified dateformat
- [[31492]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31492) Patron image upload fails on first attempt with CSRF failure
- [[31739]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31739) Password reset from staff fails if previous expired reset-entry exists

## Plugin architecture

- [[31684]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31684) Plugin versions starting with a "v" cause unnecessary warnings

## Reports

- [[28967]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28967) Patrons with no checkouts report shows patrons from other libraries with IndependentBranches
- [[31594]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31594) Report results count of shown can be incorrect on last page

## Searching

- [[20596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20596) Authority record matching rule causes staging failure when MARC record contains multiple tag values for a match point
- [[15048]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15048) Genre/Form (655) searches fail on searches with $x 'General subdivision' subfield values

## Searching - Elasticsearch

- [[29048]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29048) Incorrect search for linked authority records from authority search result list in OPAC
- [[29561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29561) Remove blank facet for languages

## Searching - Zebra

- [[31532]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31532) Zebra search results including 880 with original script incorrect because of Bug 15187

## Self checkout

- [[32115]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32115) Add ID to check-out default help message dialog to allow customization

## SIP2

- [[32624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32624) Patrons fines are not accurate in SIP2 when NoIssuesChargeGuarantorsWithGuarantees or NoIssuesChargeGuarantees are enabled

## Staff interface

- [[32596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32596) Background jobs viewer not showing finished jobs
- [[32355]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32355) Add class url to all URL syspref
- [[18556]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18556) Message "Patron's address in doubt" is confusing

## System Administration

- [[30694]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30694) Impossible to delete line in circulation and fine rules
- [[32291]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32291) "library category" messages should be removed (not used)
- [[31976]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31976) Incorrect default category selected by authorized values page
- [[31619]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31619) Cannot select title when setting non-default value for OPACSuggestionMandatoryFields

## Templates

- [[32348]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32348) Library public is missing from columns settings
- [[31677]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31677) Convert basic MARC editor tabs to Bootstrap
- [[31678]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31678) Convert authority editor tabs to Bootstrap
- [[31420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31420) Managing funds: Labels of statistic fields overlap with pull downs
- [[29671]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29671) Dropbox mode is unchecked after check in confirm on item with Materials specified
- [[31559]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31559) Staff results page doesn't always use up full available screen width
- [[31653]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31653) jQuery upgrade broke search button hover effect
- [[31412]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31412) Set focus for cursor to Name when adding a new SMTP server

## Test Suite

- [[32349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32349) Remove TEST_QA
- [[32622]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32622) Auth.t failing on D10
- [[31883]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31883) Filter trim causes false warnings
- [[31593]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31593) Remove Test::DBIx::Class from Context.t

## Tools

- [[32255]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32255) Cannot use file upload in batch record modification
- [[32456]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32456) Date accessioned is now cleared when items are replaced
- [[32389]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32389) Syndetics links are built wrong on the staff results page
- [[32037]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=32037) Circulation module in action logs has bad links for deleted items
- [[31609]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31609) JavaScript error on Additional contents main page
- [[31644]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31644) MARCModification template fails to copy to/from subfield 0
- [[31595]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31595) Import patrons tool should not process extended attributes if no attributes are being imported


