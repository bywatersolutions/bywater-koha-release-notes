
# Release Notes for bywater-v24.11.06-01

## Acquisitions

- [[38411]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38411) When adding multiple items on receive, mandatory fields are not checked

## Architecture, internals, and plumbing

- [[40033]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=40033) The background jobs page calls GetPlugins incorrectly, resulting in a 500 error
- [[39772]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39772) Background jobs page lists unknown job types for jobs implemented by plugins
- [[39920]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39920) do_check_for_previous_checkout should us 'IN' over 'OR'

## Cataloging

- [[39462]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39462) (bug 37870 follow-up) Default values from framework are inserted into existing record while editing
- [[37364]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37364) Improve creation of 773 fields for item bundles regarding MARC21 245 and 264
- [[39991]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39991) Record comparison in vendor file - results no longer side by side

## Circulation

- [[38477]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38477) Regression: new overdue fine applied incorrectly when using "Refund lost item charge and charge new overdue fine" option in circ rules

## Command-line Utilities

- [[39887]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39887) Improve documentation of overdue_notices.pl

## ERM

- [[37934]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=37934) Extend length of API key, requestor ID and customer ID for data providers
- [[39823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39823) SUSHI harvest fails to display error if the provider's response does not contain Severity

## OPAC

- [[38981]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38981) Local cover images failing to load in OPAC search results
- [[38184]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38184) OpacTrustedCheckout module does not show due date
- [[39313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39313) OpacTrustedCheckout self-checkout modal not checking out valid barcode
- [[39095]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39095) Clicking 'Cancel' for article requests in the OPAC patron account does not respond

## Patrons

- [[39331]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39331) Guarantor relationships not removed when changing patron category from memberentry.pl
- [[38892]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38892) Patron category 'can be a guarantee' means that same category cannot be a guarantor (again)
- [[38847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38847) Renewing an expired child patron without a guarantor and with ChildNeedsGuarantor set results in an internal server error

## Plugin architecture

- [[39870]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39870) Add plugin hook for making arbitrary data available to notices

## Reports

- [[39955]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39955) Report subgroup filter not cleared when changing tabs

## Staff interface

- [[39305]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39305) About page must warn if Plack is not running
- [[39987]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39987) Batch item deletion breadcrumb uses wrong link

## Templates

- [[38127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=38127) Missing column headings in 'Add user' pop-up modal

## Test Suite

- [[39304]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39304) Jenkins not failing when git command fails
- [[36625]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=36625) t/db_dependent/Koha/Biblio.t leaves test data in the database

## Tools

- [[39295]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=39295) Patron card creator infinite loop during line wrapping in template/layout incompatibility


