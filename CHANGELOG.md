# Changelog

All notable changes to this project will be documented in this file, in reverse chronological order by release.

## 1.4.0 - TBD

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 1.3.14 - 2020-04-17

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [#18](https://github.com/laminas-api-tools/api-tools-admin-ui/pull/18) fixes Laminas API Tools references.

## 1.3.13 - 2019-11-27

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zfcampus/zf-apigility-admin-ui#156](https://github.com/zfcampus/zf-apigility-admin-ui/pull/156) fixes responsiveness on loading source code. Proper loader has been added.

- [zfcampus/zf-apigility-admin-ui#156](https://github.com/zfcampus/zf-apigility-admin-ui/pull/156) fixes responsiveness on loading fields configuration. Proper loader has been added.

- [zfcampus/zf-apigility-admin-ui#157](https://github.com/zfcampus/zf-apigility-admin-ui/pull/157) fixes errors on sidebar search.

- [zfcampus/zf-apigility-admin-ui#158](https://github.com/zfcampus/zf-apigility-admin-ui/pull/158) fixes removal of database adapter containing special chars in the name.

## 1.3.12 - 2019-11-24

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zfcampus/zf-apigility-admin-ui#151](https://github.com/zfcampus/zf-apigility-admin-ui/pull/151) fixes responsiveness on loading api details.

- [zfcampus/zf-apigility-admin-ui#153](https://github.com/zfcampus/zf-apigility-admin-ui/pull/153) fixes responsiveness on loading api services on sidebar.

## 1.3.11 - 2018-09-10

### Added

- Nothing.

### Changed

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zfcampus/zf-apigility-admin-ui#148](https://github.com/zfcampus/zf-apigility-admin-ui/pull/148) fixes how the UI parses authorizations retrieved for an RPC
  service to ensure they are mapped to the authorizations form correctly.

## 1.3.10 - 2018-09-10

### Added

- Nothing.

### Changed

- [zfcampus/zf-apigility-admin-ui#141](https://github.com/zfcampus/zf-apigility-admin-ui/pull/141) makes the "Delete all files..." text of modal dialogs clickable,
  making it easier to select the checkbox.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zfcampus/zf-apigility-admin-ui#147](https://github.com/zfcampus/zf-apigility-admin-ui/pull/147) fixes how authorizations are saved for RPC services. Previously,
  the UI was sending the RPC controller action using the same casing as the
  service name.  However, controller actions are, without variance, always using
  an initial lowercase letter. As a result, ACLs for RPC services were created
  in such a way that the expected resource could never be found. This release
  fixes that situation to ensure they are mapped correctly.

## 1.3.9 - 2016-12-19

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zfcampus/zf-apigility-admin-ui#130](https://github.com/zfcampus/zf-apigility-admin-ui/pull/130) updates the
  UI to ensure the `object_manager` key is passed when creating or updating a
  Doctrine-based service.
- [zfcampus/zf-apigility-admin-ui#136](https://github.com/zfcampus/zf-apigility-admin-ui/pull/136) updates the
  UI to allow selecting one of many Doctrine object managers; previously, the
  first item was always selected.

## 1.3.8 - 2016-08-17

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zfcampus/zf-apigility-admin-ui#128](https://github.com/zfcampus/zf-apigility-admin-ui/pull/128) fixes how
  the UI calls the authorization endpoints, ensuring the controller name is
  properly formed.

## 1.3.7 - 2016-08-14

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zfcampus/zf-apigility-admin-ui#123](https://github.com/zfcampus/zf-apigility-admin-ui/pull/123) fixes
  display of the sidebar on initial load when a default API version other than
  the latest version is selected; it now correctly *always* displays the latest
  version on initial load.
- [zfcampus/zf-apigility-admin-ui#125](https://github.com/zfcampus/zf-apigility-admin-ui/pull/125) fixes the
  "Add a description for this service" links on API dashboards. Previously, they
  had no handler, and thus did nothing; with this release, they provide a modal
  for updating the service description.

## 1.3.6 - 2016-08-12

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zfcampus/zf-apigility-admin-ui#119](https://github.com/zfcampus/zf-apigility-admin-ui/pull/119) fixes
  transitions to new API versions when selecting an API version in the sidebar.
  Previously, the sidebar would be updated, but the UI would not transition to
  the API's dashboard for that version.
- [zfcampus/zf-apigility-admin-ui#120](https://github.com/zfcampus/zf-apigility-admin-ui/pull/120) updates the
  About tab to provide updated links and information about the project.

## 1.3.5 - 2016-08-11

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zfcampus/zf-apigility-admin-ui#118](https://github.com/zfcampus/zf-apigility-admin-ui/pull/118) fixes the
  API dashboard new service modal handler to ensure that the sidebar is updated
  when a new service is successfully created.

## 1.3.4 - 2016-08-10

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Re-builds the distribution files, as they were not rebuilt for 1.3.3, and thus
  changes were not observed.

## 1.3.3 - 2016-08-10

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zfcampus/zf-apigility-admin-ui#117](https://github.com/zfcampus/zf-apigility-admin-ui/pull/117) fixes the
  about screen to no longer use a hard-coded version. Instead, it now attempts
  to query the api-tools-version API, returning the version that returns. If the
  API is not pressent, or errors in some way, the string `@dev` is now used for
  the version.

## 1.3.2 - 2016-08-09

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zfcampus/zf-apigility-admin-ui#116](https://github.com/zfcampus/zf-apigility-admin-ui/pull/116) ensures
  that the short service name, and not the full controller service name, is
  displayed on service pages.
- [zfcampus/zf-apigility-admin-ui#116](https://github.com/zfcampus/zf-apigility-admin-ui/pull/116) fixes
  issues with updating the sidebar after adding a new service; previously, the
  number and type of entries was correct, but no service names were displayed
  after update; they are now displayed correctly.
- [zfcampus/zf-apigility-admin-ui#116](https://github.com/zfcampus/zf-apigility-admin-ui/pull/116) fixes
  issues with updating the sidebar after removing a service; previously, the
  last service listed of the given type was removed regardless of the service
  removed; now the correct service is removed from the listing.

## 1.3.1 - 2016-08-06

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zfcampus/zf-apigility-admin-ui#114](https://github.com/zfcampus/zf-apigility-admin-ui/pull/114) fixes how
  the UI generates URIs to the various service endpoints (REST and RPC services,
  their input filters, their authorization rules, and their documentation) to
  ensure they work with the latest admin changes. In particular, prior to this
  patch, the service names were receiving both a duplicate prefix and suffix
  that caused the URLs to be invalid.

## 1.3.0 - 2016-07-27

### Added

- [zfcampus/zf-apigility-admin-ui#113](https://github.com/zfcampus/zf-apigility-admin-ui/pull/113) updates Laminas
  component dependencies to versions that are forwards compatible with other Laminas
  version 3 releases.
- [zfcampus/zf-apigility-admin-ui#107](https://github.com/zfcampus/zf-apigility-admin-ui/pull/107) adds a
  "Field type" input to new/edit field entries; this information can now be used
  by documentation systems (e.g., Swagger) to report field types.

### Deprecated

- Nothing.

### Removed

- [zfcampus/zf-apigility-admin-ui#113](https://github.com/zfcampus/zf-apigility-admin-ui/pull/113) removes
  support for PHP 5.5.
- [zfcampus/zf-apigility-admin-ui#113](https://github.com/zfcampus/zf-apigility-admin-ui/pull/113) removes
  the dependency on rwoverdijk/assetmanager, adding suggestions for:
  - rwoverdijk/assetmanager at `^1.7` (unreleased at this time)
  - zfcampus/zf-asset-manager at `^1.0`

### Fixed

- [zfcampus/zf-apigility-admin-ui#93](https://github.com/zfcampus/zf-apigility-admin-ui/pull/93) updates how
  controller names are sent to the admin API, providing the fully qualified
  class name. This update allows the UI to properly work with modules that use a
  PSR-4 directory structure.
- [zfcampus/zf-apigility-admin-ui#97](https://github.com/zfcampus/zf-apigility-admin-ui/pull/97) updates all
  API calls that pass the module name to normalize the module name using
  `encodeURIComponent()`; this allows using sub-namespaces in the backend code.

## 1.2.4 - 2016-07-27

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [zfcampus/zf-apigility-admin-ui#54](https://github.com/zfcampus/zf-apigility-admin-ui/pull/54) fixes display
  of field names generated from Doctrine entities, and also updates it to allow
  display and usage of underscore-separated names.
- [zfcampus/zf-apigility-admin-ui#85](https://github.com/zfcampus/zf-apigility-admin-ui/pull/85) adds
  additional information to error messages when unable to create a new service
  for reasons other than conflicts.
- [zfcampus/zf-apigility-admin-ui#91](https://github.com/zfcampus/zf-apigility-admin-ui/pull/91) fixes the
  templates for adding and editing validators and filters with boolean switches
  such that they now work properly.
- [zfcampus/zf-apigility-admin-ui#99](https://github.com/zfcampus/zf-apigility-admin-ui/pull/99) updates the
  template to make the copyright date in the footer dynamic.
