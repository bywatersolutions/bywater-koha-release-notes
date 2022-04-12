
# Release Notes for cdoc-v21.05.13-01

## Acquisitions

- [[29287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29287) Display of funds on acquisitions home is not consistent with display on funds page

## Architecture, internals, and plumbing

- [[29886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29886) Add Koha::Suggestions->search_limited
- [[29687]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29687) Get rid of an uninitialized warning in XSLT.pm
- [[30115]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30115) Uninitialized value warning in C4/Output.pm
- [[29625]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29625) Wrong var name in Koha::BiblioUtils get_all_biblios_iterator

## Browser compatibility

- [[22671]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22671) Warn the user in offline circulation if applicationCache isn't supported

## Bywater Only

- NOT IN BUGZILLA - GitHub Actions: Build our own base.tgz for use with koha-dpkg
- NOT IN BUGZILLA - Create 'offline circ' log file
- NOT IN BUGZILLA - Fix translations for Koha 21.05.13

## Circulation

- [[30222]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30222) Auto_renew_digest still sends every day when renewals are not allowed
- [[30155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30155) We shouldn't calculate get_items_that_can_fill when we don't have any holds
- [[29220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29220) Minor fixes and improved code readability in circulation.pl

## Fines and fees

- [[30132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30132) overdue_notices.pl POD is incorrect regarding passing options
- [[28663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28663) One should not be able to apply a discount to a VOID accountline

## Hold requests

- [[30266]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30266) Holds marked waiting with a holdingbranch that does not match can cause loss of pickup locations

## I18N/L10N

- [[29596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29596) Add Yiddish language

## OPAC

- [[29795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29795) If branch is mandatory on patron self registration form, the pull down should default to empty
- [[29706]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29706) When placing a request on the opac, the user is shown titles they cannot place a hold on

## Packaging

- [[30084]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30084) Remove dependency of liblocale-codes-perl

## Patrons

- [[30098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30098) Patron search redirects when one result on any page of results
- [[28576]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28576) Add patron image in patron detail section does not specify image size limit

## Plugin architecture

- [[30072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30072) Add more holds hooks

## Reports

- [[26269]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26269) Overdues: Download file doesn't match result in staff interface when due date filters or 'show any available items currently checked out' are used
- [[30129]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30129) 500 error when search reports by date

## REST API

- [[30133]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30133) Pagination broken on pickup_locations routes when AllowHoldPolicyOverride=1
- [[29877]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29877) MaxReserves should be enforced consistently between staff interface and API

## Searching - Elasticsearch

- [[30153]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30153) FindDuplicate ElasticSearch should not use lowercase 'and'
- [[27770]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27770) ES: Deprecated aggregation order key [_term] used, replaced by [_key]

## SIP2

- [[28730]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28730) Add option to format AH field (due date)  in SIP checkout response

## Staff Client

- [[30164]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30164) Header filter not taken into account on the cities view

## Templates

- [[29853]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=29853) Text needs HTML filter before KohaSpan filter

## Test Suite

- [[30203]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=30203) Prevent data loss when running Circulation.t without prove


