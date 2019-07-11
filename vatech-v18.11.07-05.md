
# Release Notes for vatech-v18.11.07-05

## Architecture, internals, and plumbing

- [[23144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23144) Bad POD breaks svc/barcode

## Patrons

- [[23283]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23283) cannot view/edit additional attributes in 18.11.x

## SIP2

- [[23057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23057) If checked_in_ok is set and item is not checked out, alert flag is supressed for *any* reason



# Release Notes for vatech-v18.11.07-04

## Bywater Only

- NOT IN BUGZILLA - Fix for error in placerequest.pl



# Release Notes for vatech-v18.11.07-03

## Bywater Only

- NOT IN BUGZILLA - Fix for backported Bug 22877



# Release Notes for vatech-v18.11.07-02

## Circulation

- [[23018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23018) Refunding a lost item fee may trigger error if any fee has been written off related to that item



# Release Notes for vatech-v18.11.07-01

## Architecture, internals, and plumbing

- [[16750]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16750) Redirect from selectbranchprinter.pl to additem.pl causes software error

## Authentication

- [[22585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22585) Fix remaining double-escaped CAS links

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability
- NOT IN BUGZILLA - Bug 23058: Prevent XSS vulnerabiliies when 'tag' is passed to opac-search

## Cataloging

- [[7890]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7890) Required fields in the MARC editor should be highlighted
- [[21887]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21887) 856$u link problem in XSLT result lists and detail page

## Circulation

- [[18344]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18344) Overdue fines 'cap at replacement price' and 'cap by amount' should work together

## Database

- [[23022]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23022) Koha is not compatible with MySQL >= 8.0.11 because of NO_AUTO_CREATE_USER mode

## ILL

- [[22099]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22099) "List requests" button displays when listing requests

## Installation and upgrade (web-based installer)

- [[22770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22770) Typo in German translation for Greek in language pull down

## Lists

- [[22941]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22941) Giving malformed sortfield to list results in Internal Server Error

## MARC Authority data support

- [[23053]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23053) Local-Number cannot be used for authority matching due to non-existence of 'phrase' index
- [[22919]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22919) Authorities MARC Structure not inserted with SQL strict modes

## MARC Bibliographic data support

- [[20986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20986) MARC21 Supplement and Index Textual Holdings don't display

## OPAC

- [[22945]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22945) Markup error in OPAC search results around lists display
- [[23076]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23076) Include OpacUserJS on OPAC maintenance page
- [[22954]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22954) Minor markup error in OPAC messaging template
- [[22952]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22952) Markup error in OPAC suggestions template
- [[22948]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22948) Markup error in OPAC bibliographic detail template
- [[22955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22955) Markup error in OPAC lists template
- [[22950]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22950) Markup error in OPAC recent comment template
- [[22953]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22953) Markup warning in OPAC user summary template

## Patrons

- [[22910]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22910) Unique attributes should not be copied when duplicating a patron

## Searching

- [[14794]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14794) Searching patron by birthday returns no results if format incorrect

## Serials

- [[10215]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=10215) Increase the size of opacnote and librariannote for table subscriptionhistory
- [[11492]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11492) Receiving a serial item causes routing list notes to be lost

## SIP2

- [[19457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19457) If CheckPrevCheckout is set to "Do", then checkouts are blocked at the SIPServer

## Staff Client

- [[22958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22958) The Help link on SMS providers page should link to the correct chapter in the manual

## System Administration

- [[8558]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8558) Better confirmation message for importing frameworks
- [[22947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22947) Markup error in OPAC preferences file

## Tools

- [[23006]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23006) Can't use inventory tool with barcodes that contain regex relevant characters ($,...)



# Release Notes for vatech-v18.11.06-09

## Cataloging

- [[23045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23045) Advanced cataloging editor (rancor) throws a JS error on incomplete/blank lines



# Release Notes for vatech-v18.11.06-08

## Hold requests

- [[23116]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23116) Cannot place overridden holds



# Release Notes for vatech-v18.11.06-07

## Patrons

- [[23082]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23082) Fatal error editing a restricted patron



# Release Notes for vatech-v18.11.06-06

## Circulation

- [[23120]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23120) Internal server error when checking in item to transfer and printing slip



# Release Notes for vatech-v18.11.06-05

## Circulation

- [[23140]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23140) Typo in returns.tt prevents printing branchcode in transfer slips



# Release Notes for vatech-v18.11.06-04

## Circulation

- [[22877]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22877) Returning a lost item not marked as returned can generate additional overdue fines



# Release Notes for vatech-v18.11.06-03

## Bywater Only

- NOT IN BUGZILLA - SUBMIT TO COMMUNITY - Supress Holds Queue warning if request has no item but request has an itemtype

## Self checkout

- [[23102]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23102) 404 errors on page causes SCI user to be logged out

## SIP2

- [[23057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23057) If checked_in_ok is set and item is not checked out, alert flag is supressed for *any* reason



# Release Notes for vatech-v18.11.06-02

## Authentication

- [[22585]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22585) CAS login link for staff intranet is double-escaped

## Circulation

- [[22982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22982) Paying lost fee does not always remove lost item from checkouts

## SIP2

- [[23057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23057) If checked_in_ok is set and item is not checked out, alert flag is supressed for *any* reason



# Release Notes for vatech-v18.11.06-01

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


