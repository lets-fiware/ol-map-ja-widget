## v1.0.0 (2021-05-16)

- ol map ja v1.0.0
- Add Japan GSI map feature
- Add overview map feature
- Add scale line feature
- Add swipe feature
- Add heatmap layer
- Add heatmap KML layer
- Add removePoI feature
- Add feature for building marker with Font Awesome icon
- Add custom style option with image or text
- Add initial location value and initial zoom Level value

NOTE: This WireCloud widget is based on Wirecloud/ol3-map-widget created by
CoNWeT Lab., Universidad Politecnica de Madrid and Future Internet Consulting
and Development Solutions S.L..

## v1.2.3 (2021-03-25)

- Fix some problems rendering the layer/setcenter buttons
- Added a button for setting the current zoom level as the **Initial Zoom
    Level** setting. This button is only available when using WireCloud v1.4 in
    edit mode.
- Added a button for setting both the **Initial Location** and the **Initial
    Zoom Level** settings from the current displayed area. This button is only
    available when using WireCloud v1.4 in edit mode.


## v1.2.2 (2021-03-23)

- Use PoI id for the selection popup menu if the PoI does not provide a title
    attribute.
- Added a button to set the **Initial Location** setting using the center of the
    current displayed area. This button is only available when using WireCloud
    v1.4 in edit mode.


## v1.2.1 (2020-03-07)

- Use OSM layer by default. Previous versions of the widget were using Wikimedia
    maps by default.


## v1.2.0 (2019-12-29)

- Update OpenLayers to v6.1.1. See #29.
- Fix getPixelFromCoordinate function. See #23 and #24.
- Allow poiInputCenter endpoint receive null. See #25.
- Add clustering support (enabled through a preference). See #27.
- Improve layer configurability. See #28.
    - Added support for the following general options: `opacity`, `visible`,
      `viewMaxZoom` and `viewMinZoom`
    - `extent` option is now transformed from `EPSG:4623`
    - Added a new command for updating layer options. Current available options
      for those updates are: `opacity`, `visible` and `url`.


## v1.1.3 (2019-10-22)

- Fix null event sent sometimes when changing the selected PoI when using the
    endpoints.


## v1.1.2 (2019-04-04)

- Bundle the LICENSE file with the widget
- Improve widget metadata


## v1.1.1 (2019-02-28)

- Fix proj4.js not being packaged into the widget. See #16.
- Fix creation of markers for polygons. See #17


## v1.1.0 (2019-02-08)

- Add a new preference for configuring the widget to be used for switching
    between layers. Also allow to disable this feature by providing an empty
    widget reference. See #14.
- Allow to indicate if the PoI is selectable or not. See #5
- Update OpenLayers to version 4.6.5
- Add a new option: minzoom. This option allows to configure the minimum zoom
    level at which the PoI will be displayed.
- Fix some problems managing current selected PoIs. See #8 and #13.
- Other small fixes: #11


## v1.0.3 (2018-02-23)

- Improve `Initial Location` preference parsing
- Fix some problems managing popovers
- Fix some problems managing `EndpointTypeError` (errors sending invalid data to
    the input endpoints)


## v1.0.2 (2018-01-24)

- Fix some problems managing PoI input events
- Fix some problems clicking outside PoI markers


## v1.0.1 (2018-01-24)

- Updated OpenLayers to version 4.3.1
- Add an input endpoint to delete PoIs
- Add an input endpoint to center PoIs
- Add an output endpoint to send the selected PoI
- Continuous integration using Travis and Coveralls


## v1.0

Initial version
