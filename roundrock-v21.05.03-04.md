
# Release Notes for roundrock-v21.05.03-04

## About

- [[27661]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27661) Clarify error for message broker
- [[7143]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7143) Bug for tracking changes to the about page
- [[26425]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26425) Fix history.txt once and for all

## Acquisitions

- [[28773]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28773) Aquisitions from external source not working for non english language
- [[28408]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28408) Last modification date for suggestions is wrong
- [[28283]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28283) 'Quantity received' should have inputmode="numeric"
- [[27793]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27793) Store Contents of FTX segment of EDI quotes for inclusion in orders
- [[23971]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23971) Add logging for basket related actions
- [[27240]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27240) Export basket: remove spaces and don't export links
- [[22773]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22773) Bulk close invoices and filter invoice view (open/closed)
- [[23929]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23929) Invoice adjustments should filter inactive funds
- [[27719]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27719) Receiving orders hangs on processing when missing a replacement price
- [[27671]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27671) Missing include in orderreceive.tt
- [[27606]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27606) Breadcrumbs on parcel.pl should include a link to the vendor
- [[27608]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27608) Correct 'accepted by' inconsistency in suggestion.tt
- [[20212]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20212) Improve performance of acquisitions receive page
- [[27446]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27446) Markup errors in suggestion/suggestion.tt
- [[26630]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26630) Allow custom text for each library on the purchase suggestion page
- [[27023]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27023) Add class names in the suggestions column in suggestions management
- [[26582]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26582) Add Koha::Acquisition::Basket->close
- [[26729]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26729) When adding a new vendor set focus for cursor to name input box
- [[21882]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21882) Add price column to acquisition details tab in staff interface
- [[15329]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15329) Show budget in addition to fund for late orders in acquisition
- [[21898]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21898) Add basket info available for ACQORDER
- [[26680]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26680) Update (rcvd) to (received) with its own class in basket view
- [[26738]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26738) Unable to change manager of purchase suggestion
- [[26712]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26712) Set focus for cursor to basket name input box on basketheader.pl
- [[6819]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=6819) Don't offer cancel order links for received order lines on basket summary
- [[21811]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21811) Add warning when order receive form is saved without entering 'quantity received'
- [[26503]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26503) Allow to limit on standing orders in acquisition advanced search
- [[23420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23420) Add "SuggestionsUnwantedFields" to hide fields from the suggestions form
- [[26089]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26089) Add acquisitions-related reports to acquisitions sidebar menu
- [[11176]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11176) Purchase suggestions should respect the 'active' switch on budgets
- [[17458]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17458) When receiving an order, information about user and date on top are incorrect
- [[23682]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23682) Add ability to manually import EDI invoices as an alternative to automatic importing on download
- [[26014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26014) Add publication year and edition to Z39.50 results in acquisition
- [[25033]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25033) Counts of suggestions are confusing
- [[24157]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24157) Additional acquisitions permissions

## Architecture, internals, and plumbing

- [[28776]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28776) Warns from GetItemsInfo when biblio marked as serial
- [[28620]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28620) Remove trailing space when logging with log4perl
- [[28622]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28622) Selected branchcode incorrectly passed to adv search
- [[28561]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28561) Order_by triggers a DBIx warning Unable to properly collapse has_many results
- [[28571]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28571) C4::Auth::_session_log is not used and must be removed
- [[28570]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28570) bor_issues_top.pl using a /tmp file to log debug
- [[28519]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28519) Add a 2nd directory for Perl modules
- [[24434]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24434) C4::Circulation::updateWrongTransfer is never called but should be
- [[27942]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27942) QOTD: quote CSV uploads may contain JavaScript payloads (XSS)
- [[28317]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28317) Remove CGI::Session::Serialize::yaml dependency by using the default serializer
- [[27844]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27844) koha-worker systemd service should run as %i-koha in package install
- [[28276]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28276) Do not fetch config ($KOHA_CONF) from memcached
- [[27756]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27756) background_jobs_worker.pl is memory inefficient
- [[28278]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28278) Improve $KOHA_CONF parsing speed by using XML::LibXML
- [[27246]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27246) Remove apache only code from C4::Context BEGIN
- [[28244]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28244) Ukrainian is misspelled in language tables for English
- [[27636]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27636) Replace Koha::Account::pay with a simpler method
- [[27995]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27995) Koha::Account::Line->apply should return the update Koha::Account::Line object
- [[28210]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28210) C4::Circulation::LostItem should pass through skip_record_index to MarkIssueReturned
- [[27281]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27281) Replace call to `C4::Circulation::DeleteTransfer` with `Koha::Item::Transfer->cancel({ comment => $comment })` in `C4::Circulation::LostItem`
- [[23271]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23271) Koha::Patron::Category should use Koha::Object::Limit::Library
- [[27896]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27896) Remove C4::Circulation::DeleteTransfer
- [[23583]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23583) Handle OpacHiddenItems with yaml_preference
- [[28096]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28096) API datatables wrapper does not deal correctly with hidden columns
- [[27857]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27857) Koha::Patron->extended_attributes skips checks
- [[28110]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28110) YAML::XS minimum version should be 0.67, not 0.41
- [[27069]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27069) Change holdallowed values from numbers to strings
- [[28031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28031) Koha::Patron::Attribute->_check_repeatable doesn't exclude the object's ID
- [[28056]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28056) Add Koha::Exceptions::Patron::MissingMandatoryExtendedAttribute
- [[27858]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27858) Make Koha::Patron::Attribute->store raise an exception on invalid type/code
- [[27833]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27833) Koha::Exceptions::Patron::Attribute::* should have parameters
- [[24000]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24000) Some modules do not return 1
- [[26705]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26705) System preference NoticeBcc not working
- [[27939]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27939) Update yarn.lock file
- [[27930]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27930) Move _escape_* functions from acq/parcel.tt to be re-usable
- [[27268]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27268) Move C4::Biblio::GetMarcNotes to Koha namespace
- [[27851]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27851) Add Koha::Old::Checkouts->filter_by_todays_checkins method
- [[26742]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26742) Add configuration for message broker
- [[22824]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22824) Replace YAML::Syck with YAML::XS
- [[26057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26057) Add Koha::Item::Transfer->cancel method
- [[26363]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26363) Provide a systemd unit file for background_jobs_worker
- [[26618]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26618) C4/RotatingCollections.pm should not use C4::Circulation::transferbook
- [[26481]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26481) Add Koha::Item::Transfer->in_transit method
- [[25767]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25767) Add Koha::Item::Transfer->receive method
- [[25757]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25757) Add a Koha::Item::Transfer->transit method
- [[25755]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25755) Add a Koha::Item->request_transfer method
- [[27673]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27673) Replace YAML with YAML::XS
- [[27534]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27534) koha upgrade throws SQL error while applying Bug 25333 - Change message transport type for Talking Tech from "phone" to "itiva"
- [[27131]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27131) Move code from circ/pendingreserves.pl to modules
- [[25026]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25026) RaiseError must be set for the UI
- [[23830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23830) Koha::AuthorisedValues should use Koha::Objects::Limit::Library
- [[27581]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27581) Rename UseICU system preference to UseICUStyleQuotes
- [[25552]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25552) Add missing Claims Returned option to MarkLostItemsAsReturned
- [[25670]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25670) Add useful methods to Koha::Acquisition::Orders
- [[27486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27486) Rename system preference delimiter to CSVDelimiter
- [[27487]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27487) Rename system preference reviewson to OPACComments
- [[26048]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26048) PSGI Koha does not use custom ErrorDocument pages
- [[27491]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27491) Rename system preference opaclanguages  to OPACLanguages
- [[25802]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25802) Koha::Calendar->addDate should be renamed addDuration to better reflect it's purpose
- [[27485]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27485) Rename system preference gist to TaxRates
- [[26947]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26947) kohastructure.sql should be updated for each release
- [[26950]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26950) Checkin failure messages are unclear or too specific
- [[25306]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25306) Unnecessary update of framework in ModBiblioMarc
- [[27252]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27252) ES5 no longer supported (since 20.11.00)
- [[27331]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27331) fr-FR/1-Obligatoire/authorised_values.sql is invalid
- [[27030]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27030) The new "Processing" hold status is missing in C4::Reserves module documentation
- [[27072]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27072) Don't process staff interface CSS with rtlcss
- [[26963]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26963) Improve Koha::Item::pickup_locations performance
- [[25067]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25067) Move PO file manipulation code into gulp tasks
- [[25334]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25334) Add generic 'phone' message transport type
- [[26584]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26584) Remove unused C4::Acquisition::CloseBasket function
- [[26132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26132) Improve readability of TooMany
- [[22394]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22394) Remove C4::Accounts::manualinvoice
- [[25333]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25333) Change message transport type for Talking Tech from "phone" to "itiva"
- [[26638]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26638) System preference ArticleRequestsMandatoryFieldsItemsOnly is unused
- [[26721]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26721) Debit and credit type pages should check for the specific permission
- [[25898]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25898) Prohibit indirect object notation
- [[26569]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26569) Use gender-neutral pronouns in systempreference explanation field in DB
- [[23376]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23376) Cleanup order receive page code
- [[26515]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26515) Add Koha::Acquisition::Order->cancel
- [[26580]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26580) Remove unused C4::Acquisition::DelBasket function
- [[26579]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26579) Remove unused C4::Acquisition::DelOrder function
- [[26577]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26577) Make basket.pl and cancelorder.pl use $order->cancel
- [[26555]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26555) Add a way for Koha::Object(s) to carry execution information
- [[26621]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26621) .mailmap adjustments
- [[23895]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23895) Tidy up the directories under installer/data/mysql/
- [[26485]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26485) Simplify itemnumber handling in returns.pl
- [[20582]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20582) Turn Koha into a Mojolicious application
- [[22417]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22417) Add a task queue
- [[26268]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26268) Remove items.paid for once and for all
- [[26325]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26325) Add primary_key_exists function to Installer.pm
- [[26432]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26432) Remove unused ModZebrations
- [[26524]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26524) Add Koha::Acquisition::Basket->orders
- [[26562]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26562) Searches are shared between sessions
- [[26384]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26384) Missing test to catch for execution flags
- [[26470]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26470) itemnumber not available for plugin hook
- [[24663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24663) OPACPublic must be tested for all opac scripts
- [[23634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23634) Privilege escalation vulnerability for staff users with 'edit_borrowers' permission and 'OpacResetPassword' enabled
- [[25504]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25504) Wrong API spec breaks plack without meaningful error
- [[23166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23166) Simplify code related to orders in catalogue/*detail.pl
- [[26239]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26239) Number::Format issues with large negative numbers
- [[22393]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22393) Remove last remaining manualinvoice use
- [[25114]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25114) Remove duplicated logic from GetLoanLength()
- [[25663]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25663) Koha::RefundLostItemFeeRules should be merged into Koha::CirculationRules
- [[26133]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26133) Unneeded calls in detail.pl can be removed
- [[23092]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23092) Add 'daterequested' to the transfers table
- [[25909]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25909) Recent change to datatables JS in the OPAC causes errors
- [[21395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21395) Make perlcritic happy
- [[24986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24986) Maximum row size reached soon for borrowers and deletedborrowers
- [[25287]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25287) Add columns_settings support to API datatables wrapper

## Authentication

- [[28489]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28489) CGI::Session is incorrectly serialized to DB in production env / when strict_sql_modes = 0
- [[28385]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28385) LDAP server configuration broken since migration from XML::Simple
- [[20854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20854) Redirect after logout with CAS 3.0 broken
- [[21325]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21325) Prevent authentication when sending userid and password via querystring parameters
- [[18506]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18506) SSO - Shibboleth Only Mode

## Bywater Only

- NOT IN BUGZILLA - Remove t/db_dependent/selenium/administration_tasks.t, it's failing due to fragility
- NOT IN BUGZILLA - Followup - Make rabbitmq-server optional for koha-common debian package
- NOT IN BUGZILLA - Make rabbitmq-server optional for koha-common debian package
- NOT IN BUGZILLA - GitHub Actions - Move koha-dpkg from master image to 21.05 image
- NOT IN BUGZILLA - GitHub Actions - Move from 20.05 to 21.05
- NOT IN BUGZILLA - Fix translations for Koha 21.05.03
- NOT IN BUGZILLA - Fix translations for Koha 21.05.02
- NOT IN BUGZILLA - Translation fixes for 21.05.01 release
- NOT IN BUGZILLA - Koha 21.05.00 is here!
- NOT IN BUGZILLA - Add and fix few messages in second plural form for pl, be, ru languages
- NOT IN BUGZILLA - 21.05.00 - Update history.txt
- NOT IN BUGZILLA - 21.05.00 - Update contributors.yaml
- NOT IN BUGZILLA - Koha 20.12 - start of a new dev cycle
- NOT IN BUGZILLA - v20.11.00
- NOT IN BUGZILLA - Koha 20.11.00 is here!
- NOT IN BUGZILLA - Adjust history and contributors list
- NOT IN BUGZILLA - Fix some updatedatabase.pl issues
- NOT IN BUGZILLA - Compiled CSS (OPAC)
- NOT IN BUGZILLA - Koha 20.06 - start of a new dev cycle

## Cataloging

- [[28828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28828) Bug 22399 breaks unimarc_field_4XX.tt and marc21_linking_section.tt value builders
- [[28727]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28727) "Edit item" button on moredetail should be enabled with edit_items permission
- [[28533]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28533) Requesting whole field in 'itemcallnumber' system preference causes internal server error
- [[28611]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28611) Incorrect Select2 width
- [[28513]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28513) Analytic search links formed incorrectly
- [[28542]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28542) Move new authority from Z39.50/SRU to a button
- [[28383]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28383) Log in via the itemsearch URL leads to Internal Server Error
- [[28204]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28204) Table highlighting is broken at the cataloguing/additem.pl
- [[28171]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28171) Serial enumeration / chronology sorting is broken in biblio page
- [[28179]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28179) Use a lightbox gallery to display the images - detail page, staff interface
- [[28270]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28270) Wrong tooltip displayed on moredetail for the claim lost status
- [[27125]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27125) Show authority type for UNIMARC in authority search result display
- [[18017]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18017) Use index_heading and index_match_heading in UNIMARC authorities zebra configuration
- [[28035]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28035) Improve breadcrumbs of cataloging search page
- [[27980]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27980) Replace obsolete title-string sorting: Catalog templates
- [[27545]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27545) NewItemsDefaultLocation is only used from additem.pl
- [[27886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27886) Authority linking broken in advanced editor
- [[24108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24108) Configure if biblionumber or control number is used for saved files from detail page or advanced cataloguing editor
- [[23302]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23302) Less clicks on Z3950 search results
- [[27508]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27508) Can't duplicate the MARC field tag with JavaScript if option "advancedMARCeditor" is set to "Don't display"
- [[20971]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20971) Corrupted storable string breaks SubfieldsToUseWhenPrefill functionality
- [[11299]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11299) Add a button to automatically link authority records in cataloguing (AJAX)
- [[27130]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27130) Adding local cover image at item level shows 'File type' section
- [[27135]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27135) Viewing local cover images at item level shows a link to upload image at record level
- [[26921]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26921) Create cover image even when there is no record identificator
- [[27128]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27128) Follow-up to bug 25728 - Don't prefill av's code
- [[27012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27012) Merging records with holds causes SQL error
- [[12533]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12533) Improve authority search result display
- [[26145]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26145) Add the ability to attach a cover image at item level
- [[16314]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16314) Show upload link for upload plugin in basic MARC editor
- [[15851]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15851) Only display "Analytics: Show analytics" when records have linked analytics
- [[26139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26139) 'Place hold' button isn't hidden in all detail views if there are no items available for loan
- [[25728]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25728) Add the ability to create a new authorised value within the cataloguing module
- [[5428]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=5428) Back to results after deleting a record
- [[20154]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20154) Stay in the open tab when editing authority record
- [[24134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24134) Add placeholder for 2 digit years to allow autogeneration of dates in 008
- [[24176]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24176) Show the date of the last circulation in the items table in the staff interface
- [[26083]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26083) Item editor defaults to lost

## Circulation

- [[27847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27847) Don't obscure page when checkin modal is non-blocking
- [[28455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28455) If TrackLastPatronActivity is enabled we should update 'lastseen' field on checkouts
- [[28382]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28382) 'Reserve' should be passed through as transfer reason appropriately in branchtransfers
- [[27064]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27064) Transferring an item with a hold allows the user to set a hold waiting without transferring to the correct branch
- [[16785]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16785) Autocomplete broken on overdues report
- [[24154]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24154) No indication that Default checkout, hold and return policy are set if values are blank
- [[28230]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28230) Renewing/Checking out record with AE or OE letter in title can make Koha totally unfunctional
- [[27924]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27924) Display number of holds awaiting pickup on check out screens
- [[23207]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23207) Allow automatic checkin/return at end of circulation period
- [[21883]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21883) Show authorized value description for withdrawn in check-in
- [[18912]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18912) Show more item information when using itemBarcodeFallbackSearch
- [[28139]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28139) Processing holds are not filled automatically
- [[28136]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28136) Transferred holds are not triggering
- [[28034]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28034) Add DataTables to lists of clubs in "Clubs" tabs on patron account
- [[27993]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27993) Koha::Item::Transfer->in_transit should not count cancelled transfers
- [[27969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27969) On checkin, relabel "Remember due date" as "Remember return date"
- [[18532]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18532) Messaging preferences for auto renewals
- [[27058]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27058) Cannot place hold to ordered item when on shelf holds are not allowed
- [[12224]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12224) Allow easy printing of patron check-in slip
- [[25690]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25690) SIP should not allow to check out an item in transfer because of a hold to another patron
- [[27808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27808) Item's onloan column remains unset if a checked out item is issued to another patron without being returned first
- [[26937]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26937) Add an optional delay to the CheckPrevCheckout system preference
- [[26457]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26457) DB DeadLock when renewing checkout items
- [[24488]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24488) Holds to Pull sometimes shows the wrong 'first patron' details
- [[27011]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27011) Warnings in returns.pl
- [[26953]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26953) Phone & SMS transports always displayed in overdue status triggers
- [[27133]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27133) Header missing for "Copy no" on the relative's checkouts table
- [[25534]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25534) Add ability to specifying and store a reason when cancelling a hold
- [[24083]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24083) Koha should support "seen" vs "unseen" renewals
- [[23916]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23916) Issuer should be recorded and visible in patron circulation history
- [[14866]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14866) Make high holds work with different item types and number of open days
- [[19351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19351) Add copynumber in the checkouts table in staff interface
- [[15780]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15780) Include inventory number in patron account summary print
- [[12656]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12656) Allow a CANCELLATION_REASON to be specified on the cancel_expired_holds.pl job
- [[23979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23979) "Account is locked" message should be displayed on all patron pages
- [[26694]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26694) Set focus for cursor to search input box on guarantor_search.pl
- [[26643]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26643) Staff should be notified that a transfer has been completed on checkin
- [[19382]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19382) Add ability to block guarantees based on fees owed by guarantor and other guarantees
- [[26529]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26529) Holds rules enforced incorrectly when not set at library level
- [[23695]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23695) Items holdingbranch should be set to the originating library when generating a manual transfer
- [[25261]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25261) Multiple parts handling - confirmation alert
- [[26501]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26501) Article requests: Add datatables to requests form in staff client
- [[26323]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26323) Not_for_loan, damaged, location and ccode values must be retrieved from the correct AV category
- [[25969]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25969) Checking in a found hold at a different branch then confirming the hold causes internal server error
- [[25958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25958) Allow LongOverdue cron to exclude specified lost values
- [[16112]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16112) Specify renewal date for batch renew
- [[21750]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21750) Move collection to its own column in checkins table
- [[18501]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18501) Automatic refunds need protection from failure
- [[25430]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25430) Improve the styling of the claims returned tab
- [[16748]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16748) Batch checkout needs set due date
- [[20469]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20469) Add item status to staff article requests form
- [[21946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21946) Group circulation by item type
- [[24201]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24201) Attach desk to intranet session
- [[26108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26108) Checkins should not require item to have been checked out
- [[24279]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24279) Claims Returned does not work when set from moredetail.pl or additem.pl
- [[25799]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25799) Edition information to Holds queue report
- [[25798]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25798) Copyright year to Holds to pull report
- [[25851]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25851) 19.11 upgrade creates holdallowed rule with empty value
- [[25440]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25440) Remove undef and CGI warnings and fix template variables list in circulation rules
- [[24159]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24159) Allow daysMode for calculating due and renewal dates to be set at the circulation rules level
- [[25232]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25232) Add ability to skip triggering holds with a given notforloan value
- [[25658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25658) Print icon sometimes obscures patron barcode

## Command-line Utilities

- [[28749]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28749) All backups behave as if --without-db-name is passed
- [[28399]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28399) batchRebuildItemsTables.pl error 'Already in a transaction'
- [[28291]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28291) koha-translate install script producing incorrectly encoded YAML translation files
- [[15986]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15986) Add a script for sending hold waiting reminder notices
- [[28001]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28001) Fix delete_patrons.pl if no category is passed
- [[27839]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27839) koha-worker missing tab-completion in bash
- [[27049]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27049) Add a script to bulk writeoff debts
- [[26459]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26459) Allow sip_cli_emulator to handle cancelling holds
- [[27048]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27048) Add timestamps to verbose output of rebuild_zebra.pl
- [[27050]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27050) Allow multiple category_codes in delete_patrons.pl
- [[27563]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27563) Remove check-url.pl in favor of check-url-quick.pl
- [[24541]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24541) Database clean-up: purge messages
- [[21111]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21111) Add --exclude-indexes option to koha-run-backups
- [[26641]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26641) link_bibs_to_authorities.pl: Add the ability to specify the MARC field to operate on
- [[24306]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24306) Add debug option to koha-indexer
- [[24153]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24153) Add a confirm flag to the cleanup_database.pl cronjob
- [[24152]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24152) Add the ability to purge pseudonymized data
- [[25538]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25538) koha-shell should pass --login to sudo if no command

## Course reserves

- [[26819]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26819) Error when adding items to course reserves - can't view items in the staff interface
- [[26880]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26880) Add explanatory text to Add course reserve screens
- [[14648]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14648) Batch remove reserve items
- [[25606]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25606) Adds "Remove all reserves" button to course details

## Database

- [[7806]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=7806) Don't use 0000-00-00 to signal a non-existing date
- [[17809]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17809) Correct some authorised values in fr-FR
- [[24658]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24658) Deleting items with fines does not update itemnumber in accountlines to NULL causing ISE
- [[27003]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27003) action_logs table error when adding an item
- [[18050]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18050) Missing constraint on aqbudgets.budget_period_id in aqbudgets
- [[13535]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13535) Table alert is missing FK and not deleted with the patron
- [[24379]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24379) Patron login attempts happen to be NULL instead of 0

## Developer documentation

- [[28305]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28305) Remove doc reference to XML::Simple in C4::Context
- [[26617]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26617) Add koha-testing-docker to INSTALL file and correct URL

## Documentation

- [[25700]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25700) Recent Kohacons are missing from the timeline

## Fines and fees

- [[26760]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26760) Redirect to paycollect.pl when clicking on "Save and pay"
- [[28344]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28344) One should be able to issue refunds against payments that have already been cashed up.
- [[23215]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23215) Remove PayPal logic from Koha
- [[16486]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16486) Display the TIME a fine was collected/written off
- [[27971]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27971) The VOID method should be updated to respect double-entry accounting
- [[24300]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24300) Add a 'payout amount' option to accounts
- [[28168]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28168) Manual invoice form pre-fills Amount field with invalid number
- [[28127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28127) POS register details tables should have a transaction date
- [[27796]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27796) SIP payment types should not be available as refund types
- [[27967]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27967) Modals on the borrower account page don't validate minimum values
- [[26272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26272) Allow cashup summaries to be displayed from the library summary page
- [[26273]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26273) Expose cashup summary history for a cash register
- [[27290]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27290) Cash register allows for 'amount tendered' less than amount being paid
- [[27044]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27044) Deprecate core support for PayPal payments
- [[24603]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24603) Allow to cancel charges in patron accounting
- [[24786]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24786) Allow setting a cash register for a login session and configuring library-default cash registers
- [[23091]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23091) Add options to charge new or restore forgiven overdues when a lost item is returned
- [[26172]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26172) Add a cashup summary view (with option to print)
- [[26327]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26327) Include checkout library in fines
- [[26189]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26189) Table options on points of sale misaligned
- [[19036]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19036) Number payment receipts / payment slips
- [[26160]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26160) Add column configuration to the Point of sale, Items for purchase table
- [[24610]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24610) Let user switch between 'Pay' and 'Write off' mode

## Hold requests

- [[28779]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28779) Calling request.pl with non-existent biblionumber gives internal server error
- [[28833]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28833) Speed up holds queue builder via parallel processing
- [[28754]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28754) C4::Reserves::FixPriority creates many warns when holds have lowestPriority set
- [[28057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28057) Confusion of biblionumber and biblioitemnumber in request.pl
- [[27885]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27885) Populate biblionumbers parameter when placing hold on single title
- [[28644]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28644) Can't call method "borrowernumber" on an undefined value at C4/Reserves.pm line 607
- [[28520]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28520) Cancelling a hold that is in transit hides item's transit status
- [[28338]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28338) Validate item holdability and pickup location separately
- [[28496]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28496) Club holds form broken
- [[28273]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28273) Multi-holds allow invalid pickup locations
- [[28286]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28286) Place hold button not displayed when biblio has only Ordered items
- [[27865]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27865) Hold pickup location dropdown on patron pages should respect hold fulfillment policies
- [[27864]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27864) Visual feedback on overridden pickup locations when placing biblio-level hold
- [[28169]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28169) Reverting waiting hold causes holds page Javascript stop functioning
- [[27790]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27790) Possibility to filter Holds to pull list using pickup place
- [[12362]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12362) Branch transfer records orphaned on cancelled holds
- [[16787]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16787) 'Too many holds' message appears inappropriately and is missing data
- [[28125]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28125) All OPAC holds blocked when OPACHiddenItems contains incorrect values
- [[26498]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26498) Add option to set a default expire date for holds at reservation time
- [[28092]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28092) Holds to pull needs to include reserve notes
- [[27894]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27894) Add visual feedback on overridden pickup locations
- [[24359]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24359) Remove items from Holds Queue when checked in
- [[27803]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27803) publicationyear / copyrightdate not included in Holds to Pull
- [[27718]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27718) Holds to Pull list doesn't respect holdallowed circulation rule anymore
- [[27733]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27733) Sort pickup locations by library name instead of branchcode
- [[27732]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27732) JavaScript error on place hold page in the staff interface
- [[27706]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27706) Holds to Pull libraries column filter doesn't work
- [[26367]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26367) Warn in HoldsQueue if request itemtype set but request is not item specific
- [[27016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27016) Make the pickup locations dropdowns use Select2
- [[26634]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26634) Hold rules applied incorrectly when All Libraries rules are more specific than branch rules
- [[24412]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24412) Attach waiting hold to desk
- [[24598]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24598) Hold not reset properly if checked out to another patron
- [[19889]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19889) LocalHoldsPriority needs exclusions
- [[18958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18958) If patron has multiple record level holds on one record transferring first hold causes next hold to become item level
- [[26281]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26281) Add cancellation reason to holds history
- [[22789]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22789) Establish non-priority holds
- [[25892]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25892) Clarify the visual hierarchy of holds by library and itemtype

## Holidays

- [[27835]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27835) Closed days offsets with one day

## I18N/L10N

- [[28154]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28154) Translate script faces encoding issues
- [[27816]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27816) "Click to edit" in Point of sale is untranslatable
- [[26697]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26697) Make translation file for types and descriptions of charges consistent between OPAC and staff
- [[26439]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26439) Move translatable cart-related strings out of js_includes.inc and into basket.js
- [[26398]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26398) Credit and Debit types on creating a manual credits and manual invoices are not translatable
- [[25596]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25596) "Overpayment refund" is not translatable
- [[26237]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26237) Move translatable strings out of preferences.tt and into JavaScript files
- [[26395]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26395) Move translatable strings out of letter.tt into letter.js
- [[26229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26229) Move translatable strings out of categories.tt and into categories.js
- [[26441]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26441) Move translatable strings out of catalog-strings.inc into catalog.js
- [[26418]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26418) The "description" for REFUND accountlines is not translatable
- [[26065]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26065) Move translatable strings out of marc_modification_templates.tt and into marc_modification_templates.js

## ILL

- [[22818]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22818) ILL should be able to send notices
- [[20799]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20799) Add a link from biblio detail view to ILL request detail view, if a biblio has an ILL request
- [[23391]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23391) Hide finished ILL requests

## Installation and upgrade (command-line installer)

- [[25674]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25674) Add RabbitMQ options to koha-create
- [[27466]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27466) Update process failing for 20.06.00.023

## Installation and upgrade (web-based installer)

- [[27625]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27625) Remove uk-UA installer data
- [[27624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27624) Remove ru-RU installer data
- [[27623]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27623) Remove pl-PL installer data
- [[27621]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27621) Remove it-IT installer data
- [[28281]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28281) Installer doesn't work on some languages (pl-PL) because it double decodes installer data
- [[24972]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24972) Remove de-DE installer data
- [[24973]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24973) Allow to localize and translate system preferences with new yaml based installer

## Label/patron card printing

- [[15563]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15563) Add option to regularly delete patroncard and label batches to cleanup_database.pl cronjob
- [[28119]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28119) Use full description in layout type selection
- [[28041]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28041) Improve breadcrumbs and headings on label creator pages
- [[26962]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26962) Koha notice/slips/receipts should print in true black (#000000)

## Lists

- [[27715]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27715) Possibly SQL injection in virtualshelves
- [[13701]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13701) Sharing lists: Text hardcoded to 2 weeks, but could be any time frame
- [[24884]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24884) Remove 'New list' button in 'Public lists' tab if OpacAllowPublicListCreation is disabled

## MARC Authority data support

- [[28160]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28160) Values from 150$a aren't prefilled in z39.50 search form from an existing authority record
- [[21958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21958) _check_valid_auth_link checks too many subfields
- [[27737]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27737) Tag editor for authority lookup broken in authority editor

## MARC Bibliographic data support

- [[26852]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26852) Add missing X11$e and remove relator term subfields from MARC21 headings
- [[27852]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27852) Link YES_NO authorized value category to 942$n in Default framework
- [[8976]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8976) Default sequence of subfields in cataloguing and item editor
- [[12966]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12966) Edition statement missing from card view in Z39.50 result list (acq+cataloguing)
- [[27022]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27022) Add publisher number (MARC21 028) to OPAC and staff detail pages
- [[15141]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15141) Add MARC21 770/772 to OPAC and staff detail pages
- [[15436]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15436) MARC21: Use semicolon between series name and volume information
- [[16728]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16728) Add MARC21 777 - Issued with entry to staff and OPAC detail pages
- [[24322]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24322) National Library of Medicine (NLM) call number to XSLT Detail
- [[15437]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15437) MARC21: Show $i for 780/785

## MARC Bibliographic record staging/import

- [[26199]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26199) Record matching rule match check should include Leader/LDR
- [[26853]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26853) Data lost due to "Data too long for column" errors during MARC import

## Notices

- [[28813]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28813) Fix recording and display of delivery errors for patron notices
- [[28581]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28581) Patron's queue_notice uses inbound_email_address incorrectly
- [[28582]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28582) Can't enqueue letter HASH(0x55edf1806850) at /usr/share/koha/Koha/ArticleRequest.pm line 123.
- [[26734]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26734) Convert accounts (monetary) notices to use GetPreparedLetter
- [[13613]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13613) Don't allow digest to be selected without a digest-able transport selected
- [[14723]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14723) Additional delivery notes to messages
- [[28258]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28258) Bad date formatting in AUTO_RENEWALS notice
- [[14233]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14233) Add logging support to notices and slips management
- [[28017]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28017) Allow non-FQDN and IP addresses in emails
- [[28023]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28023) Typo in Reply-To header
- [[11257]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11257) Document "items.content" for DUEDGST and PREDUEDGST and update sample notices
- [[21886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21886) Add option to send notices from owning library instead of issuing library
- [[27103]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27103) Adding a hold cancellation reason should not always send a notice
- [[26745]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26745) Notice titles/subjects should support Template Toolkit
- [[25776]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25776) Add last updated date for notices and slips
- [[24197]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24197) Custom destination for failed overdue notices
- [[16371]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16371) Quote of the Day (QOTD) for the staff interface

## OPAC

- [[28784]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28784) DoS in opac-search.pl causes OOM situation and 100% CPU (doesn't require login!)
- [[28861]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28861) Item type column always hidden in holds history
- [[28868]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28868) Masthead.inc is missing class name
- [[28764]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28764) Sorting not correct in pagination on OPAC lists
- [[28569]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28569) In opac-suggestions.pl user library is not preselected
- [[28741]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28741) OAI ListSets does not correctly build resumption token
- [[28469]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28469) Move "Skip to main content" link to top of page
- [[28662]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28662) Not possible to log out of patron account in OPAC with JavaScript disabled
- [[28679]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28679) Unable to click "Log in to your account" when  GoogleOpenIDConnect  is enabled
- [[28631]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28631) Holds History title link returns "not found" error
- [[28660]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28660) Self checkout is not automatically logging in
- [[28597]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28597) OPAC suggestions do not display news for logged in branch
- [[28299]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28299) OpacHiddenItems not working in OPAC lists
- [[28462]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28462) TT tag on several lines break the translator tool
- [[28242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28242) Accessibility: OPAC - add captions and legends to tables and forms
- [[28545]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28545) Noisy uninitialized warn at opac-MARCdetail.pl line 313
- [[28388]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28388) Search result set is lost when viewing the MARC plain view (opac-showmarc.pl)
- [[28511]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28511) Road types in OPAC should prefer OPAC description if one exists
- [[28422]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28422) OPAC MARC detail view doesn't correctly evaluate holdability
- [[28313]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28313) Add street type to alternate address in OPAC
- [[28600]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28600) Variable "$patron" is not available
- [[28518]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28518) "Return to the last advanced search" exclude keywords if more than 3
- [[18989]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18989) Allow displaying biblios with all items hidden by OpacHiddenItems
- [[18112]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18112) Add street type to main address in OPAC
- [[27876]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27876) Accessibility: OPAC - Reduce heading redundancy
- [[27740]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27740) Accessibility: OPAC - Headings should have correct tags and hierarchy
- [[28193]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28193) OpacLoginInstructions news block broken by Bug 20168
- [[27814]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27814) Improve responsive behavior of the user page in the OPAC
- [[27566]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27566) CSS rule not applying to HTML select / option -  displays with serif font ignoring rules
- [[28086]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28086) Email address shown on OpacMaintenancePage should use ReplytoDefault if set
- [[27830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27830) OPAC library list does not use AddressFormat
- [[28162]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28162) Self registration fails if patron extended attributes are editable
- [[28140]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28140) Accessibility: OPAC - "sort_by"  select isn't labelled on search results page
- [[27961]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27961) External track clicks links should get uri filtered
- [[21260]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21260) Improve the Availability line of OPAC XSLT search results
- [[28114]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28114) OPAC Results availability line does not show homebranch/holding branch correctly
- [[27726]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27726) OPACProblemReports cuts off message text
- [[28018]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28018) Replace obsolete title-string sorting: OPAC templates
- [[27889]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27889) Form fields in OPAC are "out of shape"
- [[27748]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27748) Encoding problem in link to OverDrive results
- [[27610]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27610) Accessibility: OPAC - h1 on each page is Logo but should be page description/title
- [[27742]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27742) Accessibility: OPAC - Page titles should have unique information first
- [[27881]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27881) Markup error in masthead-langmenu.inc
- [[27860]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27860) Bad KohaAdminEmailAddress breaks patron self registration and password reset feature
- [[27681]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27681) Style OPAC self-registration CAPTCHA as uppercase
- [[27728]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27728) Add a search box on OPAC search history
- [[27731]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27731) Place hold link for individual OPAC search result broken
- [[26406]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26406) Suggestions filter does not work
- [[27618]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27618) Don't show dropdown if PatronSelfRegistrationLibraryList only has one library
- [[27005]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27005) Adding a filter in the datatable of opac-readingrecord page
- [[12260]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12260) Printing a page from bootstrap shows unnecessary links
- [[20410]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20410) Remove OpacGroupResults system preference and feature
- [[27628]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27628) Fix minor HTML markup errors in OPAC search results templates
- [[27633]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27633) Display of 440$v doubled up in the OPAC
- [[26578]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26578) OverDrive results can return false positives when searches contain CCL syntax
- [[27261]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27261) PatronSelfRegistrationBorrowerUnwantedField should exclude branchcode
- [[27440]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27440) Improve structure and style of result toolbars in the OPAC
- [[27493]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27493) Improve structure and style of checkbox columns in tables
- [[27543]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27543) Tooltip on opac-messaging.pl obscured by table headers
- [[27098]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27098) Rename 'Relatives fines' to 'Relatives charges' in OPAC
- [[22752]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22752) Show item-level hold details for patrons when logged into their account
- [[27047]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27047) Purchase suggestions search filter is broken
- [[25775]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25775) Add DataTables controls to user's checkouts table in OPAC
- [[27325]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27325) Fix singular/plural forms on the OPAC dashboard
- [[26123]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26123) Show info about existing OPAC note/Patron message on patron's dashboard
- [[26847]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26847) Make borrower category code accessible in all pages of the OPAC
- [[27168]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27168) Most popular doesn't always sort correctly
- [[27200]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27200) "Browse search" is broken
- [[27148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27148) Internal Server Error during self registration 20.11
- [[26941]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26941) Missing OPAC password recovery error messages
- [[26973]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26973) extendedPatronAttributes not showing during selfregistration
- [[20936]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20936) Holds history for patrons in OPAC
- [[16696]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=16696) Rename "Publisher" to "Publication details" on detail and result lists
- [[26148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26148) OpenLibrary "Preview" link target is unclear to patrons
- [[26886]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26886) OPAC suggestions: possible duplicate message should stand out more
- [[26718]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26718) Change 'Your reading history" to "Your checkout history"
- [[26783]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26783) Set OpacRenewalAllowed to "Allowed" for new installations
- [[26763]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26763) Use standard information style for multi-hold message
- [[26825]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26825) Add span for publication date in OPAC
- [[26805]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26805) Remove remaining instances of jquery.checkboxes plugin from the OPAC
- [[26695]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26695) Set focus for cursor to login box on the login popup modal
- [[26753]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26753) Set focus for cursor to password field on Overdrive login popup on OPAC
- [[26828]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26828) Set focus for cursor to current password field when updating in the OPAC
- [[26830]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26830) Set focus for cursor to name input box when creating a new list in the OPAC
- [[26881]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26881) Remove the period at the end of 'Limit to currently available items' in facets
- [[26758]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26758) Correct OPAC ILL requests page markup
- [[26706]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26706) Fix btn-default styling for better contrast
- [[26749]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26749) Correct dropdown markup in OPAC cart
- [[26719]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26719) Replace MSG_NO_RECORD_SELECTED with translatable string
- [[26810]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26810) OpacCustomSearch is no longer a system preference, we must use the template variable
- [[26747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26747) OverDrive always available titles display 999999 copies available
- [[26752]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26752) OPAC list download button broken by Bootstrap 4 upgrade
- [[26735]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26735) Overdrive login modal broken in the OPAC
- [[26655]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26655) Accessibility: Checkboxes on OPAC lists do not contain aria labels
- [[26519]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26519) Clean up OPAC buttons with incorrect classes
- [[5927]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=5927) Show series information in search results page
- [[19616]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19616) Add MARC21 505$g - Formatted Contents Note / Miscellaneous information
- [[25242]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25242) Accessibility: The 'Holdings' table partially obscures navigation links at 200% zoom
- [[25771]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25771) Allow the user to sort checkouts by the renew column in the OPAC
- [[26266]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26266) Add jQuery validator to opac-password-recovery.tt
- [[26299]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26299) Help text for OPAC SMS number should be less North American-centric
- [[26454]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26454) Add system preference to set meta description for the OPAC
- [[26478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26478) Display issue with buttons on the self checkout screens
- [[26505]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26505) Suspend hold modal broken in the OPAC
- [[26421]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26421) Use Bootstrap screen reader text class for shelf browser messages
- [[26262]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26262) Paging on course reserves tables in OPAC is broken
- [[20168]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20168) Update of the OPAC bootstrap template to bootstrap v4
- [[8732]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8732) Add a system preference to allow users to choose to display an icon based on the Koha bibliographic level itemtype
- [[26039]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26039) Accessibility: Shelf browser is not announced upon loading
- [[26179]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26179) Remove redundant import of Google font
- [[25871]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25871) Add "only library" to OpacItemLocation options
- [[26070]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26070) Google Transliterate API has been deprecated
- [[23797]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23797) Convert OpacLoginInstructions system preference to news block
- [[23796]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23796) Convert OpacCustomSearch system preference to news block
- [[23795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23795) Convert OpacCredits system preference to news block
- [[25801]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25801) Add itemnumber parameter to the OPAC detail page that allows to show a single item
- [[24473]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24473) Syndetics content should be $raw filtered on opac-detail.tt
- [[22807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22807) Accessibility: Add 'Skip to main content' link
- [[25236]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25236) Accessibility: The 'Refine your search' box contains semantically incorrect headings
- [[24405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24405) Links in facets are styled differently than other links on the results page in OPAC

## Packaging

- [[28616]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28616) Remove Data::Printer dependency
- [[26672]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26672) Create metapackage to install Koha and all its dependencies
- [[26702]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26702) Remove explicit libnet-stomp-perl from debian/control.in

## Patrons

- [[28350]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28350) Sort by "circ note" is broken on the patron search result view
- [[28490]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28490) Cannot modify patrons in some categories (e.g. Child category)
- [[26995]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26995) Drop column relationship from borrower tables
- [[26940]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26940) debarred comment in borrowers table is lost on patron modifications in memberentry.pl page
- [[21549]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21549) Lock expired patron accounts after x days
- [[27990]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27990) Replace obsolete title-string sorting: Patrons
- [[27607]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27607) Add the ability to compare patron records during merge process
- [[25946]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25946) borrowerRelationship can no longer be empty
- [[27717]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27717) Date of birth fails to display for babies under 1 year
- [[27822]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27822) Wrong systempreference for AddressFormat (es-ES)
- [[8326]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=8326) Allow patron attributes to be made repeatable after initial creation
- [[17364]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17364) branchcode in BorrowerUnwantedField causes software error when saving patron record
- [[22150]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22150) Make it easier to unselect one member permission after selecting all
- [[27420]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27420) A mistake in bug 5161 leads to some patron attributes appearing without a fieldset
- [[26797]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26797) Error when trying to access Relative Checkouts between Professional and Organizational patron categories
- [[26687]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26687) Add a Font Awesome icon for superlibrarian patrons
- [[26666]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26666) Display issue with address information
- [[26534]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26534) Add a Font Awesome icon to help identify staff patrons
- [[13625]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=13625) RenewalSendNotice setting should be reflected in messaging preferences descriptions
- [[23816]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23816) Allow to have different password strength and length settings for different patron categories
- [[26285]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26285) Use country code + number (E.164) validation for SMS numbers
- [[20057]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20057) Auto-approve option for borrower modifications
- [[6725]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=6725) Make patron duplicate matching flexible
- [[25364]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25364) Add "Other" to the gender options in a patron record
- [[25654]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25654) Make the contact and non-patron guarantor sections separate on patron entry form
- [[21345]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21345) Patron records with attached files not obvious from patron details view
- [[22087]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22087) Show city and state in patron search results
- [[24151]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24151) Add a pseudonymization process for patrons and transactions

## Plugin architecture

- [[27820]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27820) plugins_nightly.pl script missing use
- [[25245]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25245) Add a plugin hook to allow running code on a nightly basis
- [[26803]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26803) Fix PLUGIN_DIR when plugin_dirs is multivalued
- [[26338]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26338) Show tool plugins run in tools home
- [[26138]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26138) Errors if enable_plugins is zero
- [[26063]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26063) Use Koha::Plugins->call for other hooks
- [[21468]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21468) Plugins need hooks for checkin and checkout actions
- [[24031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24031) Add plugin hook after_hold_create
- [[25855]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25855) Add hook to AddRenewal using a new _after_circ_actions method in circulation

## Reports

- [[28804]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28804) 500 Error when running report with bad syntax
- [[28264]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28264) Transaction type is empty in cash register statistics wizard report
- [[27644]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27644) Add button to SQL report editor for inserting runtime parameters
- [[24695]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24695) Improve SQL report validation
- [[27994]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27994) Replace obsolete title-string sorting: Reports templates
- [[27380]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27380) Add option for taking a list parameter in reports
- [[27643]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27643) Add CodeMirror custom syntax highlighting for SQL runtime parameters
- [[26708]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26708) Add option to preview SQL from list of saved reports
- [[22152]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22152) Hide printing the tools navigation when printing reports
- [[24665]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24665) Add ability to run cash register report with new cash register feature
- [[24834]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24834) Display report number after running
- [[24958]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24958) Remember last selected tab in SQL reports
- [[26269]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26269) "Download file of displayed overdues" in Circulation->Overdues produces .csv with fewer results than the displayed list under certain circumstances

## REST API

- [[28632]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28632) patrons.t fragile on slow boxes
- [[28604]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28604) Bad encoding when using marc-in-json
- [[28480]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28480) GET /patrons missing q parameters on the spec
- [[27931]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27931) Add GET /items/:item_id/pickup_locations
- [[28463]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28463) Change spec for better looking in the docs
- [[28461]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28461) Specify only one tag per route
- [[28414]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28414) Fix labels for return claims routes
- [[28369]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28369) additionalProperties missing in holds routes
- [[28370]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28370) Routes still missing additionalProperties in spec
- [[28424]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28424) POST /patrons/:patron_id/account/credits return value wrong
- [[28272]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28272) Definition files are missing additionalProperties: false
- [[28189]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28189) Move the base swagger file to YAML
- [[28254]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28254) Make it possible to override rules in PUT /holds/:hold_id/pickup_location
- [[27898]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27898) Make PUT /holds/:hold_id handle x-koha-override for pickup locations
- [[27797]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27797) Make POST /holds use the stashed koha.overrides
- [[27760]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27760) Add handling for x-koha-override
- [[27932]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27932) Add GET /biblios/:biblio_id/pickup_locations
- [[28002]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28002) Add optional extended_attributes param to POST /patrons
- [[28157]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28157) Add the ability to set a library from which an API request pretends to come from
- [[23666]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23666) Add routes for extended patron attributes
- [[27366]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27366) Add GET /patrons/:patron_id/holds
- [[27855]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27855) Allow embedding extended_attributes on /patrons routes
- [[27854]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27854) Clean GET /patrons controller
- [[26636]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26636) Add objects.find Mojolicious helper
- [[27863]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27863) Cannot select different pickup locations even with AllowHoldsPolicyOverride on request.pl
- [[26274]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26274) Expose cash register cashup summaries via an API route.
- [[27587]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27587) Use Basic auth on API tests
- [[27352]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27352) Add GET /biblios/:biblio_id/items
- [[27034]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27034) $c->objects->search shouldn't use path parameters
- [[27353]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27353) Return the number of total records
- [[27544]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27544) Simplify /checkouts implementation

## Searching

- [[28384]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28384) Add 'no_items' option to TransformMarcToKoha
- [[21249]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21249) Syspref to choose whether to search homebranch, holding branch or both for library groups in advanced search
- [[27746]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27746) Use of uninitialized value $oclc in pattern match (m//) error at C4/Koha.pm
- [[23763]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23763) Move pagination calculations to a subroutine
- [[20888]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20888) Allow use of boolean operator 'not' in item search
- [[26032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26032) Add 'is new' filter in items search
- [[25867]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25867) Label holdingbranch as Current library rather than Current location

## Searching - Elasticsearch

- [[22801]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22801) Advance search yr uses copydate instead of date-of-publication
- [[28268]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28268) Improve memory usage when indexing authorities in Elasticsearch
- [[27682]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27682) Add a floating table header for Search engine configuration
- [[27316]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27316) In mappings use yes/no for sortable
- [[25054]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25054) Display search field aliases in search engine configuration
- [[26991]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26991) Add action logs to search engine administration
- [[26903]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26903) Authority records not being indexed in Elasticsearch
- [[26180]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26180) Elasticsearch - Add option to index records in descending order
- [[19482]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19482) Elasticsearch - prevent removal / editing of required indexes
- [[26310]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26310) Allow setting trace_to parameter in Elasticsearch config
- [[24155]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24155) Weights should be (optionally) applied to Advanced search
- [[25265]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25265) Elasticsearch - Batch editing items on a biblio can lead to incorrect index
- [[26507]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26507) New items not indexed
- [[24807]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24807) Add "year" type to improve sorting by publication date

## Searching - Zebra

- [[27348]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27348) Error defining INDEXER_PARAMS in /etc/default/koha-common
- [[21286]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21286) Advanced search for Corporate-name creates Zebra errors
- [[26581]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26581) Elasticsearch - Records can be indexed multiple times during returns

## Self checkout

- [[28488]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28488) Javascript error in self-checkout (__ is not defined)
- [[26301]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26301) Self-checkout blocks renew for overdues even when OverduesBlockRenewing allows it in opac-user.pl

## Serials

- [[23243]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23243) Allow filtering out of historic subscription expirations in the check expiration of serials page
- [[28036]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28036) Improve breadcrumbs of serial claims page
- [[27998]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27998) Replace obsolete title-string sorting: Serials templates
- [[26484]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26484) Add serials-related reports to serials sidebar menu

## SIP2

- [[27908]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27908) Add support for circulation status 1 ( other ) for damaged items
- [[27907]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27907) Add support for circulation status 2 ( on order )
- [[27906]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27906) Add support for circulation status 9 ( waiting to be re-shelved )
- [[27600]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27600) SIP2: renew_all shouldn't perform a password check
- [[14300]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=14300) siplogs do not record process IDs
- [[26591]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26591) Add a choice to prevent the checkout or warn the user if CheckPrevCheckout is used via SIP2
- [[27589]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27589) Error when specifying CR field in SIP Config
- [[26701]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26701) Remove scripts from C4/SIP directory
- [[27196]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27196) Waiting title level hold checked in at wrong location via SIP leaves hold in a broken state and drops connection
- [[27166]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27166) SIP2 Connection is killed when an item that was not issued is checked in and generates a transfer
- [[25761]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25761) Implementation of too_many_overdue has unintended consequences
- [[26896]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26896) SIP option holds_block_checkin does not actually block checkin of items on hold
- [[12556]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=12556) SelfCheck machine starts the hold instantly with an email sent out
- [[21979]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21979) Add option to SIP2 config to send arbitrary item field in CR instead of collection code
- [[25541]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25541) Add ability to prevent checkin via SIP of items with holds

## Staff Client

- [[28872]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28872) AcquisitionLog, NewsLog, NoticesLog should use 1/0 for their values
- [[28802]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28802) Untranslatable strings in browser.js
- [[28834]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28834) Improve wording biblios/authorities on tools home page
- [[28728]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28728) Holds ratio page links to itself pointlessly
- [[28747]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28747) Clarify wording on RestrictionBlockRenewing syspref
- [[28601]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28601) Wrong breadcrumb for 'Home' on circulation-home
- [[28598]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28598) Changing date or time format on a production server will NOT create duplicate fines and we should remove the syspref warnings
- [[28467]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28467) Add wording to TrackLastPatronActivity description to tell users that it records SIP authentication
- [[28368]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28368) Error when printing receipt of point of sale
- [[28187]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28187) rowGroup headings are getting their styles overriden
- [[28091]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28091) Add meta tag with Koha version number to staff interface pages
- [[26703]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26703) Modify the "title" elements to contain unique information first
- [[27983]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27983) Replace obsolete title-string sorting: Acquisitions templates part 2
- [[27982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27982) Replace obsolete title-string sorting: Acquisitions templates part 1
- [[27926]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27926) Date of birth sorting with British English format is broken
- [[27846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27846) Accessibility: Staff Client - Breadcrumbs should be more accessible
- [[22569]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22569) Add a 'Transfers to send' report
- [[27405]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27405) Update intranet-tmpl/prog/en/modules/pos/register.tt for ACC2
- [[27410]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27410) Update intranet-tmpl/prog/en/modules/members/maninvoice.tt to reflect ACC2
- [[27408]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27408) Update intranet-tmpl/prog/en/modules/members/mancredit.tt for ACC2
- [[27777]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27777) Improve tables on Point of Sale page for low screen resolutions
- [[27582]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27582) Breadcrumb incorrect for POS: Library details page
- [[27404]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27404) Update intranet-tmpl/prog/en/modules/labels/label-edit-range.tt for ACC2
- [[27321]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27321) Make excluded database columns in system preferences more clearly disabled
- [[27407]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27407) Update intranet-tmpl/prog/en/modules/reserve/request.tt for ACC2
- [[27412]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27412) Update intranet-tmpl/prog/en/modules/tools/overduerules.tt to adhere to ACC2
- [[27411]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27411) Update tools/automatic_item_modification_by_age.tt to reflect ACC2
- [[27409]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27409) Update members/boraccount.tt for ACC2
- [[27406]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27406) Update admin/searchengine/elasticsearch/mappings.tt to adhere to ACC2
- [[27336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27336) JS error in Administration - System preferences page
- [[26707]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26707) Split cart and lists button on bibliographic detail pages
- [[26939]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26939) Account payment_type in the cash register details page should use description instead of code
- [[18170]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18170) Show damaged status on check-in
- [[26458]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26458) Get item details using only itemnumber
- [[26473]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26473) Get items for editing using only itemnumber
- [[11223]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=11223) Incorrect ind 1 semantics for MARC21 785 on the detail page in staff
- [[25744]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25744) Replace i tags with em AND b tags with strong in the staff interface
- [[26007]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26007) Warning/reminder for changes to Koha to MARC mapping
- [[15400]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15400) Display patron age in useful places in the staff interface

## System Administration

- [[28704]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28704) Library MARCOrgCode field needs maxlength attribute
- [[28567]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28567) Pick-up location is not saved correctly when creating a new library
- [[27975]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27975) Replace obsolete title-string sorting: Administration templates
- [[27805]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27805) Use input type "email" for email preferences
- [[26633]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26633) Add advanced editor for transfer limits
- [[27716]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27716) Insufficient access control for printer profiles
- [[27652]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27652) Offer selections for preferences which ask for patron categories
- [[27598]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27598) Add UPLOAD as a built-in system authorized value category
- [[27251]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27251) Rewrite the QOTD editor using the Koha REST API
- [[27415]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27415) Add note to ILLHiddenRequestStatuses preference to the ILLSTATUS authorized value category
- [[27263]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27263) Link to preferences mentioned in system preference descriptions
- [[27264]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27264) Reword sentence of OPACHoldsHistory
- [[27349]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27349) Mana system preference wrong type YesNo
- [[27351]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27351) UsageStatsCountry system preference wrong type YesNo
- [[27310]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27310) Wrong CSS float on 'Visibility' in framework edition
- [[27250]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27250) DELETE calls are stacked on the SMTP servers admin page
- [[27026]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27026) New circulation rule "Days mode" values are not explained anywhere
- [[26922]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26922) SendAlerts does not correctly handle error on sending emails
- [[22343]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22343) Add configuration options for SMTP servers
- [[26948]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26948) Some Koha Emails are double encoded (HOLD, ODUE, ...)
- [[23823]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23823) Allow system preferences to be bookmarked
- [[26809]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26809) Inconsistent use of full stops on admin-home.tt
- [[26595]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26595) Add SMTP server column to libraries table
- [[26290]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26290) Add the ability to set a default SMTP server in koha-conf.xml
- [[26490]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26490) Column configuration for account-fines hides the wrong columns
- [[26283]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26283) dateexpiry and dateenrolled are missing in the new modal for BorrowerMandatoryField and others
- [[25630]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25630) More capitalization and terminology fixes for system preferences
- [[25709]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25709) Rename systempreference from NotesBlacklist to NotesToHide
- [[20815]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=20815) Add ability to choose if lost fee is refunded based on length of time item has been lost
- [[22844]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22844) Simplify the process of selecting database columns for system preferences
- [[25288]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25288) Make the libraries list use the API

## Task Scheduler

- [[27109]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27109) Better labels for background job details
- [[27127]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27127) Wrong display of messages if there was only 1 record modified

## Templates

- [[28825]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28825) Can't edit local cover image for item from details page
- [[28733]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28733) Desks link is in "Patrons and circ" section on admin homepage but in "Basic parameters" on the sidebar
- [[28689]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28689) Extra %s in alert message when saving an item
- [[27498]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27498) Add a link for the hold ratios to acquisitions home page
- [[28443]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28443) Terminology: Issuing should be Checking out
- [[28428]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28428) Capitalization: Password Updated
- [[28280]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28280) Item types configuration page doesn't use Price filter for default replacement cost and processing fee
- [[28522]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28522) Correct eslint errors in staff-global.js
- [[28427]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28427) Terminology: Shelf should be list
- [[28423]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28423) JavaScript error on MARC modifications page
- [[27899]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27899) Missing description for libraryNotPickupLocation on request.pl
- [[28135]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28135) Replace use of input type number in additem.js
- [[28134]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28134) Replace use of input type number in onboarding templates
- [[27455]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27455) Add focus to branch code when a new library is added
- [[28190]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28190) Library limitation column not toggable on itemtypes table
- [[27465]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27465) Add column visibility to the admin/cities.pl
- [[27277]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27277) Queued vs Enqueued
- [[28132]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28132) Remove "this" from button descriptions on basket and basket group pages
- [[28081]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28081) Make card number a label in patron search results
- [[28055]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28055) Convert DataTables option names to current version
- [[26970]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26970) Add row highlight on drag in Elasticsearch mapping template
- [[28046]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28046) Add "Additional fields" link on acquisition navigation menu
- [[28006]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28006) Restore "Additional fields" link on serials navigation menu
- [[28066]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28066) Remove select tag's size attribute where it is 1
- [[28047]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28047) Standardize: Call number, callnumber, Call no. etc.
- [[28016]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28016) Replace obsolete title-string sorting: Assorted templates
- [[27974]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27974) Replace obsolete title-string sorting: Circulation templates
- [[27749]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27749) Phase out jquery.cookie.js: Search to hold
- [[28033]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28033) Minor capitalization corrections
- [[27751]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27751) Phase out jquery.cookie.js: Batch item modifications
- [[27699]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27699) Add cash register information to responsive staff interface header menu
- [[27668]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27668) Improve validation of patron entry form in the OPAC
- [[24623]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24623) Phase out jquery.cookie.js: Advanced MARC editor
- [[24624]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24624) Phase out jquery.cookie.js: Receipt summary
- [[26960]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26960) Move batch item modification template JavaScript to the footer
- [[26959]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26959) Reindent batch item modification template
- [[25846]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25846) Improve handling of multiple covers on catalog search results in the staff client
- [[27473]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27473) Improve link text in the installer
- [[27792]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27792) Improve jEditable configuration for point of sale fields
- [[27592]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27592) Link audio alerts to corresponding preference and back
- [[27605]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27605) Add floating toolbar to patron search page
- [[27403]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27403) Enable fixedHeader for Datatables
- [[27476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27476) Improve link text for logging in on OPAC
- [[27289]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27289) Template tweaks for point of sale page
- [[26602]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26602) Datatables - Actions columns should not be exported
- [[27430]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27430) Use minimum length for patron category on password hint
- [[21851]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21851) Improve style of sidebar forms
- [[27402]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27402) Add column filtering to the Datatables REST API wrapper
- [[27471]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27471) Improve link text when successfully merging authorities and remove JS redirect
- [[27478]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27478) Improve link text when viewing an ILL requested item
- [[27469]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27469) Improve link text when returning to vendor page
- [[27479]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27479) Improve link text after successfully resetting password in OPAC
- [[27477]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27477) Improve link text when a record has too many items on the OPAC
- [[27474]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27474) Improve link text to define a label printer profile if none defined and fix conditional
- [[27472]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27472) Improve link text when successfully merging bibliographic records
- [[27027]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27027) Typo: has successfully been modified.. %s
- [[26982]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26982) Typo in system preference UsageStats: statisics
- [[27475]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27475) Improve link text to define a patron card printer profile if none are defined
- [[27439]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27439) Improve hint labels on patron attribute type entry form
- [[27437]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27437) Improve hint labels on library creation form
- [[26985]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26985) Remove code for "Upcoming events" from codebase as not implemented
- [[27324]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27324) Use Koha.Preference() for intranetbookbag everywhere
- [[27356]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27356) Don't hide the SMTP servers table when last displayed is deleted
- [[27292]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27292) TablesSettings.GetColumns() returning nothing creates unexpected Javascript on request.tt
- [[27031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27031) Koha.Preference() should be used more often in header.inc and js_includes.inc
- [[27124]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27124) JS error "select2Width is not defined"
- [[26935]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26935) Incorrect basketid sent for claimacquisition and claimissues
- [[25941]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25941) Reindent Upload local cover image page
- [[25834]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25834) Relabel "Search to add" to "Search for guarantor" or "Add guarantor" on patron form
- [[26817]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26817) "Total" line in checkouts table is too short when ExportCircHistory is activated
- [[25469]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25469) Typo: Item does not belongs to your library
- [[24012]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24012) Display 'Locked' budget with a lock icon
- [[26806]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26806) Remove the jquery.checkboxes plugin from the staff client
- [[26800]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26800) Remove the use of jquery.checkboxes plugin from checkout page
- [[26799]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26799) Remove the use of jquery.checkboxes plugin from patron payment page
- [[26798]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26798) Remove the use of jquery.checkboxes plugin from patron detail page
- [[26795]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26795) Remove the use of jquery.checkboxes plugin from ILL pages
- [[26769]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26769) Remove the use of jquery.checkboxes plugin from staff interface search history
- [[26768]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26768) Remove the use of jquery.checkboxes plugin from library transfer limits page
- [[26767]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26767) Remove the use of jquery.checkboxes plugin from duplicate orders template
- [[26826]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26826) Set focus for cursor to name input box when creating a new list
- [[26889]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26889) Remove extra space from "Damaged :" in item search
- [[26724]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26724) Improve link text for downloading the CSV file on patron import page
- [[26833]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26833) Logged in library doesn't show with suggestions count
- [[26808]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26808) Improve tab key access to circulation confirmation dialog
- [[26782]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26782) Circulation conditions: first 2 columns show as sortable, but cannot be sorted
- [[26678]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26678) When putting an item into manual transfer, tabs from detail view show in table
- [[24899]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24899) Reindent record matching rules template
- [[25354]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25354) Clean up JavaScript markup in cataloging plugin scripts
- [[26456]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26456) Reindent MARC subfield structure template
- [[26576]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26576) Subfield descriptions on authority detail view are cut off
- [[26152]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26152) Remove the use of jquery.checkboxes plugin from serial collection page
- [[26154]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26154) Remove the use of jquery.checkboxes plugin from batch item deletion and modification
- [[23852]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23852) Merge biblio-title.inc and biblio-default-view.inc
- [[26280]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26280) Add unique IDs or class names for each condition in returns.tt
- [[26530]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26530) Use patron card number as checkbox label during patron merge
- [[26164]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26164) Replace OPAC table sort icons with SVG
- [[26419]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26419) Replace OPAC Koha logo with SVG
- [[26015]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26015) Terminology: staff interface should be used everywhere
- [[25727]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25727) Update the Select2 JS lib
- [[26234]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26234) Default DataTables must know our own classes
- [[25906]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25906) Style corrections for OPAC serial pages
- [[25832]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25832) Add DataTables to MARC subfield structure admin page for authorities
- [[26194]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26194) Messages about missing cash registers should link to cash register management
- [[25879]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25879) Improve display of guarantor information in the patron entry form
- [[26087]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26087) Add table configuration and export options to orders by fund report
- [[26091]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26091) Add column configuration and export options to catalog statistics report
- [[26093]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26093) Markup error after Bug 24279 creates formatting problem
- [[26061]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26061) Improve style of sidebar datepickers
- [[26060]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26060) Replace staff interface table sort icons with SVG
- [[25031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25031) Improve handling of multiple covers on the biblio detail page in the staff client
- [[25827]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25827) Add floating toolbar to the holds summary page in staff interface
- [[23148]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23148) Replace Bridge icons with transparent PNG files
- [[25896]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25896) Missing closing `td` tag in smart-rules.tt
- [[25974]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25974) Remove inline style from table settings administration page
- [[23410]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23410) Add submenus to system preferences sidebar menu
- [[24156]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24156) Basket - Make sort order and number of items to display configurable

## Test Suite

- [[28873]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28873) Incorrect age displayed in db_dependent/Koha/Patrons.t
- [[28509]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28509) Koha/Acquisition/Orders.t is failing randomly
- [[28483]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28483) Warnings from Search.t must be removed
- [[28516]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28516) Koha/Patrons/Import.t is failing randomly
- [[28479]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28479) TestBuilder.pm uses incorrect method for checking if objects to be created exists
- [[18146]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=18146) C4::Circulation CanBookBeRenewed  lacks full test coverage
- [[27317]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27317) (Bug 27127 follow-up) fix t/db_dependent/Koha/BackgroundJobs.t
- [[27062]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27062) pickup_location tests don't deal correctly with existing libraries
- [[26031]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26031) www/search_utf8.t is failing randomly and must be removed/replaced
- [[26971]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26971) Remove obsolete test translatable-templates.t
- [[26892]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26892) Remove warnings from t/db_dependent/Koha/Patrons.t
- [[26462]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26462) t/db_dependent/Holds.t tests delete data unnecessarily
- [[26365]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26365) Koha/Acquisition/Order.t is failing with MySQL 8
- [[26401]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26401) xt/fix-old-fsf-address* are no longer needed
- [[26250]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26250) Test suite does not pass if Elastic is used as search engine
- [[25113]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25113) Make CirculationRules.t flexible for new scope combinations
- [[26157]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26157) Redirect expected DBI warnings
- [[25811]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25811) authentication.t is failing randomly

## Tools

- [[28525]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28525) TinyMCE for system prefs does some automatic code clean up
- [[28835]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28835) Ability to pass list contents to batch record modification broken
- [[28336]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28336) Cannot change matching rules for authorities
- [[28745]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28745) Batch item modifications no longer displayed modified items
- [[26205]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26205) News changes aren't logged
- [[28418]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28418) Show template_id of MARC modification templates
- [[28191]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28191) Update wording on batch patron deletion to reflect changes from bug 26517
- [[27929]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27929) Regex option in item batch modification is hidden for itemcallnumber if 952$o linked to cn_browser plugin
- [[28353]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28353) Regression: Batch item deletion no longer shows which items were not removed
- [[28158]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28158) Lost items not charging when marked lost from batch item modification
- [[28220]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28220) Exception not caught when importing patrons
- [[28108]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28108) Move action logs 'SERIAL CLAIM' and 'ACQUISITION CLAIM' to a new 'CLAIMS' module
- [[17202]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17202) Deleting a rotating collection with items should either be prohibited or items should be removed
- [[28178]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28178) Image viewer does not select the correct image
- [[28198]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28198) Sample notices SQL fails on HOLD_REMINDER: Column count doesn't match value count
- [[24446]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=24446) Stockrotation: Update to use daterequested in branchtransfers
- [[28014]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28014) Add table settings to batch patron modification
- [[27773]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27773) Hide unique holidays and exceptions which have passed
- [[25476]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25476) Uploaded files can't be easily browsed via upload.pl
- [[28037]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28037) Improve breadcrumbs of CSV profiles page
- [[28007]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28007) Replace obsolete title-string sorting: Tools templates
- [[27869]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27869) QotD CSV upload JavaScript errors
- [[27766]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27766) Hide expired news items by default
- [[27694]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27694) News tool editor (codemirror) automatically converts HTML entities
- [[27669]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=27669) reverting and importing status never set when importing/reverting a batch
- [[4037]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=4037) Inventory tool missing item type filter
- [[23019]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23019) Ability to create 'matching profiles' when importing records
- [[26804]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26804) News: Move the news preview out of the table and into a modal
- [[26736]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26736) Compare values of reports log entries
- [[26572]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26572) Add autocomplete to librarian field in log viewer
- [[26844]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26844) Log viewer does not indicate which logs are enabled
- [[25897]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25897) Inventory table call number sort should use cn_sort value
- [[26664]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26664) Inventory: Sorting column 'Last seen' goes wrong
- [[26592]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26592) XSS vulnerability when ysearch is used
- [[15032]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=15032) [Plack] Scripts that fork (like stage-marc-import.pl) don't work as expected
- [[23114]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=23114) Inventory: allow to scan barcodes into input field
- [[26207]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26207) Compare values of system preference log entries
- [[25101]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25101) Add ability to skip previewing results when batch extending due dates
- [[21066]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=21066) Replace opac_news.timestamp by published_on and add updated_on as timestamp
- [[26086]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26086) Add a 'cron' interface limit to the log viewer
- [[25694]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25694) Add ability to delete a MARC modification template when viewing
- [[22660]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22660) Allow use of CodeMirror for editing HTML in the news editor
- [[5087]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=5087) Option to not show CSV profiles in OPAC

## Web services

- [[28630]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=28630) ILSDI::AuthenticatePatron should set borrowers.lastseen
- [[17229]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=17229) ILS-DI HoldTitle and HoldItem should check if patron is expired
- [[26665]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=26665) OAI 'Set' and 'Metadata' dropdowns broken
- [[25650]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25650) Add location and itype descriptions in ILS-DI GetRecords
- [[22806]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=22806) CanBookBeReserve and CanItemBeReserve do not check AllowHoldsOnPatronsPossessions
- [[25460]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=25460) Allow using item information in OAI set mappings and automatically update sets when items are added, edited or deleted
- [[19353]](http://bugs.koha-community.org/bugzilla3/show_bug.cgi?id=19353) Make possible to have custom XSL template for marcxml and marc21 metadata prefixes in OAI server


