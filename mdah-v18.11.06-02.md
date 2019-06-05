
# Release Notes for mdah-v18.11.06-02

## Circulation

- [[22982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22982) Paying lost fee does not always remove lost item from checkouts



# Release Notes for mdah-v18.11.06-01

## Acquisitions

- [[22908]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22908) Modsuggestion will generate a notice even if the modification failed
- [[22907]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22907) Cannot add new suggestion with strict SQL modes turned on
- [[22225]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22225) Tax hints and prices on orderreceive.pl may not match
- [[22713]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22713) Replacement price removed when receiving if using MarcItemFieldstoOrder
- [[22791]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22791) Calculation differs on aqui-home/spent and ordered.pl

## Architecture, internals, and plumbing

- [[7862]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7862) Warns when creating a new notice
- [[22478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22478) Cross-site scripting vulnerability in paginations
- [[21036]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21036) Fix a bunch of older warnings
- [[22813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22813) searchResults queries the Koha::Patron object inside two nested loops

## Authentication

- [[22717]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22717) Google OAuth auto registration error

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Cataloging

- [[22886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22886) Missing space between fields from Keyword to MARC mapping in cataloguing search
- [[21709]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21709) Addbiblio shows clickable tag editor icons which do nothing

## Circulation

- [[22896]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22896) Item to be transferred at checkin clears overridden due date
- [[15524]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15524) Set limit on maximum possible holds per patron by category

## Command-line Utilities

- [[20537]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20537) Warnings in overdue_notices.pl
- [[22875]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22875) Documentation misleading for import_patrons command line script

## Course reserves

- [[22899]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22899) Cannot view course details

## Database

- [[22782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22782) Schema change for SocialData

## Fines and fees

- [[22724]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22724) Staff without writeoff permissions have access to 'Write off selected' button on Pay Fines tab

## Installation and upgrade (web-based installer)

- [[21651]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21651) Force insert of notices related tables during the install process
- [[22527]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22527) Web installer links to wrong database manual when database user doesn't have required privileges

## Label/patron card printing

- [[22878]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22878) Cannot add a patron card layout with mysql strict mode on

## MARC Authority data support

- [[21450]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21450) link_bibs_to_authorities.pl is caching searches without the auth type

## OPAC

- [[14385]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14385) Extend OpacHiddenItems to allow specifying exempt borrower categories
- [[11853]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11853) Cannot clear date of birth via OPAC patron update
- [[22881]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22881) Trying to clear search history via the navbar X doesn't clear any searches
- [[22816]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22816) OPAC detail holdings table doesn't fill it's container
- [[22420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22420) Tag cloud feature broken

## Patrons

- [[20514]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20514) Searching for a patrons using the address option doesn't work with streetnumber
- [[22781]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22781) Fields on patron search results should be html/json filtered

## Reports

- [[22357]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22357) Every run of runreport.pl with --store-results creates a new row in saved reports

## Searching

- [[22901]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22901) On item search authorised values select disappears on conditional change
- [[22787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22787) Mapping missing for ů to u in word-phrase-utf-chr
- [[22010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22010) RecordedBooks and OverDrive should check preferences over passing variables

## Searching - Elasticsearch

- [[22705]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22705) Change default value of Elasticsearch cxn_pool to 'Static'

## Serials

- [[22812]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22812) Cannot add new subscription with strict SQL modes turned on

## SIP2

- [[15221]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15221) SIP server always sets the alert flag when item not returned

## Staff Client

- [[22914]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22914) Add holds column to batch item delete to fix show/hide columns behaviour
- [[17698]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17698) Make patron notes show up on staff dashboard

## System Administration

- [[22965]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22965) Typo in Classification Sources description on Admin homepage (admin-home.tt)
- [[22847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22847) Specific circ rule by patron category is displaying the default (or not displaying)

## Templates

- [[22932]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22932) GetLatestSerials should not return formatted date
- [[22904]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22904) Untranslatable strings in members-menu.js
- [[22800]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22800) No need to raw filter the mandatory fields var (OPAC suggestions)

## Test Suite

- [[22917]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22917) Circulation.t fails if tests are ran slowly
- [[22930]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22930) Make TestBuilder more strict about wrong arguments
- [[22836]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22836) Tests catching XSS vulnerabilities in pagination are not correct
- [[22433]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22433) SIP/Transaction.t is failing randomly
- [[21671]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21671) Koha/Patron/Modifications.t is failing randomly
- [[22453]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22453) TestBuilder should generate now() using the current timezone
- [[22808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22808) Move Cache.t to db_dependent

## Tools

- [[21831]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21831) Marc modification templates move all action moves only one field



# Release Notes for mdah-v18.11.05-05

## Acquisitions

- [[22802]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22802) When ordering from a staged file, if funds are populated per item order level fund should not be required

## Templates

- [[22734]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22734) Fund not marked as mandatory when ordering from a staged file



# Release Notes for mdah-v18.11.05-04

## Circulation

- [[22761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22761) Move "Fee receipt" from template to a slip

## Course reserves

- [[22899]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22899) Cannot view course details

## Hold requests

- [[22895]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22895) [18.11] cannot place item level holds



# Release Notes for mdah-v18.11.05-03

## Bywater Only

- NOT IN BUGZILLA - Fix atomic updates



# Release Notes for mdah-v18.11.05-02

## Circulation

- [[22809]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22809) Move "INVOICE" from template to a slip
- [[22761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22761) Move "Fee receipt" from template to a slip


