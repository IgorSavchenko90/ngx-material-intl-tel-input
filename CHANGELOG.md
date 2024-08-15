# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [18.2.0] - 2024-08-15

### Added

- Add country's name tooltip when hovering over country selection element.

### Fixed

- Fix match area codes or priority when determining country code ([#13](https://github.com/juanjotorres90/ngx-material-intl-tel-input/pull/13))

## [18.1.1] - 2024-07-27

### Added

- Add error border color when the field is invalid, dirty and not focused.

### Fixed

- Fix 'ng-invalid' class not being applied when the field is not valid ([#11](https://github.com/juanjotorres90/ngx-material-intl-tel-input/issues/11)).

## [18.1.0] - 2024-07-13

### Added

- Add 'emojiFlag' option to use standard emoji icons for the country flags.
- Add 'hidePhoneIcon' option to hide the phone icon.

## [18.0.1] - 2024-06-08

### Added

- Add 'fieldControlName' option to get the form control from the parent form group by name.
- Ability to dynamically change the form field value.
- Ability to dynamically enable or disable the form field.

### Fixed

- Fix "AbstractControl" not assignable to FieldControl.
- Fix setting the initial value and status of the phone field control when it was set in the parent form group control.

## [18.0.0] - 2024-05-26

### Added

- Add support for Angular 18.
- Add 'includeDialCode' option to include the dial code in the phone number input.
- Auto select number input after changing country code.
- Add support for Material 3 theming.
- Use of Signal Inputs to dynamically change the disabled or required state of the phone field.
- Add 'currentValue' output event to retrieve the current phone number value without using a FormControl.

### Fixed

- Fix Northern Mariana Islands number format.

### Changed

- Upgrade project to nx 19.1.
- Use of Signal Inputs for component options.
- The component is now zoneless.

## [17.3.0] - 2024-03-16

### Added

- Add 'enableSearch' option to enable or disable country search.
- Add 'excludedCountries' option to exclude countries from the list.

### Changed

- Update mat select dropdown styling.

## [17.2.2] - 2024-03-11

### Added

- Add linting and unit tests execution on pre-commit and ci.

### Fixed

- Fix flags css on library build.

## [17.2.1] - 2024-03-10

### Added

- Add 'autoSelectCountry' option to enable auto selecting a country on initialization.
- Add 'autoSelectedCountry' option to set the country to be auto selected.
- Add 'numberValidation' option to disable phone number validation.
- Add 'preferredCountries' option to show them on top of the country list.
- Add 'visibleCountries' option to only show the specified countries.
- Export "CountryISO" type.

### Changed

- Fetch country data refactor. Now a service handles all the logic.

### Removed

- Remove unused css.

## [17.2.0] - 2024-03-07

🎉🚀 First stable release 🚀🎉

### Added

- Export "TextLabels" type.

### Fixed

- Remove telephone form to avoid hydration issues.
- Rename main FormControl from "formControl" to "fieldControl" to avoid errors.
- Show field required error only when the field control is dirty.

## [0.0.3] - 2024-03-07

- Update library README image preview.

## [0.0.2] - 2024-03-06

- Add README to library build.

## [0.0.1] - 2024-03-06

- Initial version.
