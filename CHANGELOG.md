## [1.5.1] - 02-Oct-2019
* Fix setEditingState error. Close #16

## [1.5.0] - 23-Sep-2019
* Added TextInputConfiguration options - `inputType`, `obscureText`, `autocorrect`, `actionLabel`, `inputAction`, `keyboardAppearance`.
* Use theme's cursorColor instead of primaryColor

## [1.4.0] - 23-Sep-2019
* Resize the suggestions overlay when on-screen keyboard appears
* Fixed iOS crash when deleting a chip with the keyboard. Closes [#1](https://github.com/danvick/flutter_chips_input/issues/1). Thanks to [Dmitry Korchagin](https://github.com/dgsc-fav)

## [1.3.1] - 15-Aug-2019
* Resolve overlay assertion error `'_overlay != null': is not true`.

## [1.3.0] - 12-Jun-2019
* New attribute `textStyle` allows changing the `TextStyle` of the TextInput

## [1.2.1] - 12-Jun-2019
* Removed unwanted top and bottom padding from ListView in suggestions overlay. Credit [Kenneth Gulbrandsøy](https://github.com/kengu)

## [1.2.0] - 25-Mar-2019
* Max number of chips can now be set using `maxChips` attribute

## [1.1.0] - 26-Jan-2019
* Input can now be disabled by setting `enabled` attribute to `false`

## [1.0.4] - 17-Jan-2019
* Fixed bug in later versions of Flutter where implementation of abstract method `void updateFloatingCursor(RawFloatingCursorPoint point);` missing
* Fixed bug where `initialValue` chips cannot be deleted with keyboard
* Fixed bug where `onChanged()` not fired when deleting chip using keyboard

## [1.0.3] - 16-Dec-2018
* Minor improvements in documentation

## [1.0.2] - 16-Dec-2018
* Improved library description. 
* Properly formatted example code in README

## [1.0.1] - 15-Dec-2018
* Added example to README

## [1.0.0] - 15-Dec-2018
* Initial release.
