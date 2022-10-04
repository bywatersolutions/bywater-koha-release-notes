
# Release Notes for clic-v21.11.11-02

## Acquisitions

- [[31054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31054) Manual importing for EDIFACT invoices fails with a 500 error page

## Architecture, internals, and plumbing

- [[31473]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31473) Test about bad OpacHiddenItems conf fragile
- [[31001]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31001) "CGI::param called in list context" warning in basket.pl flooding error log
- [[30744]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30744) Use RecordProcessor in get_marc_notes to ensure non-public notes do not leak
- [[30848]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30848) Introduce Koha::Filter::ExpandCodedFields
- [[31058]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31058) Bad import in auto_unsuspend_holds
- [[30939]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30939) remove_unused_authorities.pl is broken
- [[29454]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29454) Stash itemtypes in plugin objects to reduce DB calls

## Bywater Only

- NOT IN BUGZILLA - Remove unreliable selenium tests
- NOT IN BUGZILLA - Remove copyright from misc/translator/po/#fr-FR-messages.po#
- NOT IN BUGZILLA - Add x flag to  DBRev 21.11.11.000
- NOT IN BUGZILLA - Remove t/00-check-atomic-updates.t
- NOT IN BUGZILLA - DBRev 21.11.11.000
- NOT IN BUGZILLA - Fix translations for Koha 21.11.11
- NOT IN BUGZILLA - DBRev 21.11.10.001

## Cataloging

- [[30976]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30976) Cover images for biblio should be displayed first
- [[31179]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31179) Duplicate item is duplicating internal item fields
- [[30716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30716) Add Collection column to cn_browser results table
- [[29958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29958) Missing dateaccessioned is set to today when storing an item
- [[30775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30775) 952w should have datepicker plugin enabled for it by default
- [[30871]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30871) Make it clear that 008 Type of Material is controlled by Leader 6th position in MARC21

## Circulation

- [[27996]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27996) Format of "Due date" on Circulation > Overdues page
- [[29050]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29050) Add punctuation in Unseen Renewals message
- [[31085]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31085) The return claims table no longer reloads on resolution
- [[31087]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31087) Undefined notes in returns claims get stringified to 'null'

## Command-line Utilities

- [[30667]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30667) Holds reminder cronjob (holds_reminder.pl) never uses default letter template
- [[30914]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30914) cleanup_database.pl --transfers --old-reserves --confirm does not work

## Fines and fees

- [[30567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30567) Create manual invoice with FR currency format show the incorrect format

## Installation and upgrade (command-line installer)

- [[25622]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25622) Change way MySQL password is generated by koha-create

## Label/patron card printing

- [[30837]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30837) Fix table width on 'Print summary'

## Notices

- [[31122]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31122) Terminology: Replace & with and for Notices & slips

## OPAC

- [[31064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31064) Local login is difficult to style using CSS
- [[30918]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30918) Non-public note is visible in OPAC in Title Notes tab

## Patrons

- [[29525]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29525) Privacy settings for patrons should also affect holds history

## Searching

- [[30865]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30865) Koha::Biblio->get_components_query should double quote Host-item search

## Searching - Elasticsearch

- [[30152]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30152) Elasticsearch - queries with OR don't work with limits

## Searching - Zebra

- [[31106]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31106) Error searching for analytics in detail view

## Serials

- [[24010]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24010) Number of issues to display to staff accepts non-integer values
- [[29055]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29055) Focus on keyword field when subscription biblio search window opens

## Staff Client

- [[31038]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31038) Amounts in cashup summary modal no longer properly formatted
- [[31067]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31067) Sub-tools permission not applying on intranet-main.tt

## System Administration

- [[29951]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29951) Cannot add splitting rule to classification sources
- [[31117]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31117) Cloning standard circulation rules for all libraries show up as from '*'

## Templates

- [[31071]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31071) Regression: date due removed from staff search results
- [[30767]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30767) Terminology: Do not forget that the issue has not been checked in yet.
- [[30766]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30766) Typo: Cannot cancel receipt. Possible reasons :
- [[30763]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30763) Typo: Barcode proceeds bibliographic data
- [[30770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30770) Terminology: Lost reserve
- [[30764]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30764) Terminology: Cancelled reserve
- [[30773]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30773) Standardize spelling i-tive / Itiva
- [[31040]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31040) jsTree image being used outside of jsTree plugin
- [[26486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26486) Group edit buttons in reports toolbar
- [[30994]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30994) Typo: item was on loan. couldn't be returned.
- [[20395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20395) Use Price formatter in more templates (paycollect, request, parcel, smart-rules)

## Test Suite

- [[31108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31108) rename ./t/00-check-atomic-updates.pl extension to *.t

## Tools

- [[31220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31220) Error when attempting to export selected labels as PDF
- [[30911]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30911) Datatables error on course-details.pl after adding a bib-level course reserve
- [[30903]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30903) CSV import of quotes broken
- [[31066]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31066) Can't use regex in batch modification on fields associated with a plugin
- [[31062]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=31062) Change description of QOTD tool in tools-home
- [[22659]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22659) Add 'save and continue' functionality to news and HTML customizations

