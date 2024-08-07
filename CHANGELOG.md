# CHANGELOG.md

## [1.1.0](https://github.com/ngocjohn/vehicle-info-card/releases/tag/v1.1.0) (2024-08-07)

### Features

- **Language Localization Support:** Added comprehensive support for localization across the card, enabling users to see translated strings based on their selected language.
- **Image Upload Integration:** Users can now upload images directly within the editor interface. [#25](https://github.com/ngocjohn/vehicle-info-card/pull/25)

## [1.0.7](https://github.com/ngocjohn/vehicle-info-card/releases/tag/v1.0.7) (2024-07-25)

### Features

- **Warning notification:** The error notifications will be shown for specific card types based on the presence of warnings or other conditions. The feature can be enabled or disabled through the card editor.

### Update

- Auxheat and pre-conditioning updated to Hour:Minute input format.

## [1.0.6](https://github.com/ngocjohn/vehicle-info-card/releases/tag/v1.0.6) (2024-07-08)

This update focuses on enhancing the visual aspects of the card and includes minor changes in the editor to improve user experience.

### Features

- **Theme Picker:** Added a new option to select a theme for the card. Users can now set the theme independently of system settings, providing more flexibility and customization.

### Updates

- **New Statuses:** Added two new statuses to the trip info card:
  - **Driving Time from Reset:** Displays the driving time since the last reset.
  - **Driving Time from Start:** Shows the driving time from the start of the trip.

## [1.0.5](https://github.com/ngocjohn/vehicle-info-card/releases/tag/v1.0.5) (2024-07-02)

### Features

- **New Remote Control Card**:
  - Introduced a new remote control card encompassing all available services offered by the integration.
  - This feature can be activated in the editor, allowing customization of which services are displayed on the tab.
  - Once activated, a new 'services' indicator will appear in the tab header, guiding you to the control tab.
  - Each service is represented by its own button, providing further configurations specific to that service.
  - For each service, the VIN/FIN is automatically set from the car entity ID.

### Updates

- **Trip Card Enhancement**:
  - Added the AdBlue level to the trip card status summary for more comprehensive trip information.
- **Tire Pressures Tab Update**:
  - Changed the display of the tire pressures tab. Now, the background of the car and the tire data are displayed for the specific tires.

## [1.0.4](https://github.com/ngocjohn/vehicle-info-card/releases/tag/v1.0.4) (2024-06-20)

### Changes

- **Sub Card Setup via UI**: Added a new function to set up individual sub cards through the user interface for improved clarity.
- **Enhanced Status Information**: Added more detailed status information for windows and doors, including the number of open doors or windows.
- **New Sensors**: Added new sensors for the starter battery and ignition, and updated to display their values for better monitoring and management.

### Fixes

- **Charge Power Status Display**: Fixed the issue with the charge power status display to show values accurately to two decimal places.
- **State of Charge Indicator Icons**: Corrected the display of icons for the state of charge indicator, ensuring they reflect the accurate state.

## [1.0.3](https://github.com/ngocjohn/vehicle-info-card/releases/tag/v1.0.3) (2024-06-15)

### Features

- **Charge Indicator for Electric Vehicles**: This indicator provides essential details including the charge power, current battery status, maximum set charge status, and the selected charging program. This enhancement offers clear and comprehensive insights into the charging process. #1

### Changes

- **Map Popup Settings in UI**: Added a new setting option to the User Interface for configuring basic map settings. This includes parameters such as default zoom level, the number of hours to display, and the theme mode. These settings can now be adjusted directly from the UI.
- **Slide Images URL in UI Editor**: Introduced the ability to insert slide images URLs directly within the UI editor. This enhancement improves the efficiency and flexibility of the UI editing process.

## [1.0.2](https://github.com/ngocjohn/vehicle-info-card/releases/tag/v1.0.2) (2024-06-09)

### Features

- **Eco Score Chart**: Added an eco score chart for Eco display card.
- **Additional Display Attributes**: Included additional display attributes for `sensor.lock` in Vehicle status card.

### Fixes

- **State of Charge Display**: Fixed the correct display of state of charge values for electric vehicles.

## [1.0.1](https://github.com/ngocjohn/vehicle-info-card/releases/tag/v1.0.1) (2024-06-06)

### Features

- **Swipe Between Cards**: Introduced functionality to swipe between cards for a more intuitive navigation experience.
- **Map Integration**: Added a feature to display the map as a new card when clicking on a marker, enhancing interaction with map elements.
- **Electric Vehicle Sensors**: Incorporated new sensors specifically for electric vehicles, providing more detailed and relevant data.

### Fixes

- **Unit of Measurement Display**: Corrected the display of units of measurement to ensure accuracy and consistency.
- **Card Order**: Adjusted the order of cards to reflect the correct sequence.

## 1.0.0 (2024-06-05)

Initial release
