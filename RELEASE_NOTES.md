## New in v2.7.0-beta (Released 2023-03-03)
* Target net7.0
* Introduces `okStream` and `okStreamChunked` (#765)

## New in v2.6.2 (Released 2022-01-26)
* Removing keys from session state (#757)
* FIX: Issue parsing boundary from multipart/form-data Content-Type header (#759)

## New in v2.6.1 (Released 2021-05-15)
* Allow to set custom Server header (#755)
* Report assigned ephemeral port  when binding to port 0 (#754)

## New in v2.6.0 (Released 2020-12-07)
* Target netstandard2.1 and drop net461
* Introduces proxy web part
* Optimization: use byte arrays instead of strings for hardcoded literals
* FIX: Sequence map bug in getHeaders (#747)

## New in v2.6.0-beta (Released 2020-07-18)
* Makes HttpContext.userState a mutable dictionary enabling global user state per request.
* FIX: Prevent showing detailed errors when proxied
* Removes Owin module.
* Removes lensed properties.

## New in v2.5.6 (Released 2019-09-06)
* Added method NOT_IMPLEMENTED (#733)
* FIX: CoreRT compiled binaries not working (#735)

## New in v2.5.5 (Released 2019-06-04)
* Support for "x-forwarded-for".
* A few changes to logging.

## New in v2.5.4 (Released 2019-04-14)
* Fix compilation error (#728)

## New in v2.5.3 (Released 2018-11-10)
* Fix regression in Owin module (#717)

## New in v2.5.2 (Released 2018-10-11)
* Fixes type name collision issue (#715)

## New in v2.5.1 (Released 2018-09-29)
* Fix multiple problems with last-modified handling (#713).
* Introduces combinator `Redirection.see_other` (#712).

## New in v2.5.0 (Released 2018-09-08)
* This release brings a few performance fixes which allows Suave to start competing in the TechEmpower Framework Benchmarks.
* Fix #706 - Websockets don't work in Firefox.
* This release also includes breaking changes in the Suave.Logging namespace as we diverge from Logary facade.

## New in v2.5.0-beta2 (Pre-released 2018-07-31)
* Fix #706 - Websockets don't work in firefox

## New in v2.5.0-beta (Pre-released 2018-07-27)
* Performance optimizations (mostly by removing harmful or unneeded async code)

## New in v2.4.3 (Released 2018-06-24)
* Fix #702 - Can't parse  negatives number in forms

## New in v2.4.2 (Released 2018-06-20)
* Improve pathScan logic

## New in v2.4.1 (Released 2018-06-10)
* Removed external source code references from build process to address licensing concerns.

## New in v2.4.0 (Released 2018-04-23)
* Cleanup of non-.Net Core cruft (reducing maintenance burden)
* Move build to FAKE 5
* Upgrade Logary Facade to v3 (Gauge Int64 -> Float)
* More liberal nuget constrains
