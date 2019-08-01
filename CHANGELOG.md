# v0.10.5 (2019-07-31)
* `*uiContentLoading` is a new structural directive that  will will render a progress spinner while the input value is `true` else it will render the content within the container (similar to `*ngIf`)
* **ui-progress-button** fix stroke width
* **ui-progress-button** add fade animation to the button text

# v0.10.4 (2019-07-29)
* [progress-button] implement button augmentor directive, that enables loading state configuraiton via a progress bar
* [spinner-button] implement button augmentor directive, that enables loading state configuraiton via a spinner

# v0.10.3 (2019-07-17)
* correctly export pipe modules / classes (support AOT builds)

# v0.10.2 (2019-07-17)
* **BREAKING CHANGE** rename `UiSnackbarIntlService` to `UiSnackbarIntl`

# v0.10.1 (2019-07-17)
#### Components

* [snackbar](https://uipath.github.io/angular-components/components/UiSnackBarComponent.html)

#### Services

* [snackbar-service](https://uipath.github.io/angular-components/components/UiSnackBarComponent.html)

#### Directives

* [nl2br](https://uipath.github.io/angular-components/pipes/UiNl2BrPipe.html)

# v0.10.0 (2019-06-13)
* **BREAKING CHANGE** components will no longer be importent directly `@uipath/angular/components`, they will now be imported from their corresponding folder, eg: `@uipath/angular/components/{{NAME}}`
* **BREAKING CHANGE** directives will no longer be importent directly `@uipath/angular/directives`, they will now be imported from their corresponding folder, eg: `@uipath/angular/directives/{{NAME}}`


# v0.9.6 (2019-06-06)
* **NgLet** move embedded view creation in `ctor`, this will allow `ViewChild` queries to be configured with `static: true` strategy

# v0.9.5 (2019-06-05)
* upgrade to `angular@8`
* **UiGrid** complete `visible$` columns BehaviorSubject
* **UiGridFilter** call destroy hook in child classes

# v0.9.3-hotfix1 (2019-06-05)
* **UiGrid** correctly bind to the search `maxlength` attribute

# v0.9.3 (2019-06-02)

### Fixes:

* **UiGridModule** remove barrel definitions for decorated classes (fixes AOT build issues).

# v0.9.2 (2019-06-01)

### Features:

* **EventGenerator** expose the `cursor` utility that injects a cursor image, to help visualize UTs.

# v0.9.1 (2019-06-01)

### First Official Release

#### Components

* [grid](https://uipath.github.io/angular-components/modules/UiGridModule.html)
* [suggest](https://uipath.github.io/angular-components/modules/UiSuggestModule.html)

#### Directives

* [autofocus](https://uipath.github.io/angular-components/modules/UiAutofocusModule.html)
* [click-outside](https://uipath.github.io/angular-components/modules/UiClickOutsideModule.html)
* [clipboard](https://uipath.github.io/angular-components/modules/UiClipboardModule.html)
* [date-format](https://uipath.github.io/angular-components/modules/UiDateFormatModule.html)
* [second-format](https://uipath.github.io/angular-components/modules/UiSecondFormatModule.html)
* [drag-and-drop](https://uipath.github.io/angular-components/modules/UiDragAndDropModule.html)
* [ng-let](https://uipath.github.io/angular-components/modules/UiNgLetModule.html)
* [scroll-into-view](https://uipath.github.io/angular-components/modules/UiScrollIntoViewModule.html)
* [virtual-scroll-range-loader](https://uipath.github.io/angular-components/modules/UiVirtualScrollRangeLoaderModule.html)
* [virtual-scroll-viewport-resize](https://uipath.github.io/angular-components/modules/UiVirtualScrollViewportResizeModule.html)

#### a11y

* [queued-announcer](https://uipath.github.io/angular-components/injectables/QueuedAnnouncer.html)

#### Testing

* [EventGenerator](https://uipath.github.io/angular-components/classes/EventGenerator.html)
* [Key](https://uipath.github.io/angular-components/classes/Key.html)
* [FakeFileList](https://uipath.github.io/angular-components/classes/FakeFileList.html)