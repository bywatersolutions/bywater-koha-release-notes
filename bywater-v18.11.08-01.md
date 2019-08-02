
# Release Notes for bywater-v18.11.08-01

## Architecture, internals, and plumbing

- [[21180]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21180) Allow Talking Tech outbound script to limit based on patron home library branchcode
- [[23144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23144) Bad POD breaks svc/barcode

## Bywater Only

- NOT IN BUGZILLA - Bug XXX - Index for 856$z, Electronic-Copy-Availability

## Circulation

- [[23097]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23097) Circulation Overdues report patron link  goes to patron's holds tab

## Hold requests

- [[13640]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13640) Holds To Pull List includes items unreserveable items

## Installation and upgrade (command-line installer)

- [[23250]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23250) koha-create generates broken mysql password
- [[23090]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23090) MySQL validate_password plugin breaks koha-create

## OPAC

- [[23151]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23151) Patron self modification sends null dateofbirth
- [[23150]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23150) GDPR feature breaks patron self modification on OPAC
- [[22946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22946) Markup error in OPAC search results around selection links

## Self checkout

- [[23198]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23198) [18.11] Wrong icons/paths in 18.11 for self check modules

## Serials

- [[23065]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23065) 'New subscription' button in serials sometimes uses a blank form and sometimes defaults to current serial

## SIP2

- [[23057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23057) If checked_in_ok is set and item is not checked out, alert flag is supressed for *any* reason

## System Administration

- [[23153]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23153) In framework management action subfields goes directly to edition

## Templates

- [[22851]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22851) Navigation links in the serials module should be styled the same as other modules

## Tools

- [[15814]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15814) Templates for MARC modification: Edit action does not work when Description contains '



# Release Notes for bywater-v18.11.07-06

## Patrons

- [[23283]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23283) cannot view/edit additional attributes in 18.11.x

## SIP2

- [[23057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23057) If checked_in_ok is set and item is not checked out, alert flag is supressed for *any* reason



# Release Notes for bywater-v18.11.07-05

## Architecture, internals, and plumbing

- [[23144]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23144) Bad POD breaks svc/barcode



# Release Notes for bywater-v18.11.07-04

## Bywater Only

- NOT IN BUGZILLA - Fix for error in placerequest.pl



# Release Notes for bywater-v18.11.07-03

## Bywater Only

- NOT IN BUGZILLA - Fix for backported Bug 22877



# Release Notes for bywater-v18.11.07-02

## Circulation

- [[23018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23018) Refunding a lost item fee may trigger error if any fee has been written off related to that item



# Release Notes for bywater-v18.11.07-01

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



# Release Notes for bywater-v18.11.06-09

## Cataloging

- [[23045]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23045) Advanced cataloging editor (rancor) throws a JS error on incomplete/blank lines



# Release Notes for bywater-v18.11.06-08

## Hold requests

- [[23116]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23116) Cannot place overridden holds


