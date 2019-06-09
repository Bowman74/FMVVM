## [0.9.5] - 6/7/2019.

* This release adds:
 
- #18 Call dispose on ViewModel objects popped off the stack..
- Added navigateAndRemoveCurrent to NavigationService

## [0.9.4] - 6/7/2019.

* This release adds:
 
- #17 Add MessageService for publish / subscribe functionality.

## [0.9.3] - 5/31/2019.

* This release adds:
 
- #7 The NavigationService can now navigate to another viewmodel to get a return value.

- #8 Breaking change, changes to fields and elements in a NotificationList now use the more standard Listenable class.

## [0.9.2] - 5/26/2019.

* This release adds:
 
- Correction of FieldManager indexes.
- Handle setting default of boolean for PropertyInfo

## [0.9.1] - 5/26/2019.

* This release adds:
 
- Factory methods to NotificationList.

## [0.9.0] - 5/15/2019.

* This release adds:
 
- There is a breaking change for how the data binding works to make it much more inline with Flutter designs. This release has added a new BindingWidget.

## [0.8.4] - 5/14/2019.

* This release adds:
 
- Fix to missing ViewHolder reference in bindings.dart

## [0.8.3] - 5/14/2019.

* This release adds:
 
- FmvvmApp class for easier bootstrapping of the framework.
- Fixes to documentation

## [0.8.2] - 5/13/2019.

* This release adds:
 
- Tweaks to the documentation
- The ability to specifically and send a parameter to a value converter

## [0.8.1] - 5/12/2019.

* This release adds:
 
- notificationList for binding to lists
- Allowed Stateful and Stateless widgets to bind to and BindableBase object, not just viewModels
- Clean up project
- Add list samples

## [0.8.0] - 5/11/2019.

* Initial release includes:
 
- Dependency injection
- Data binding
- viewmodel to viewmodel navigation
