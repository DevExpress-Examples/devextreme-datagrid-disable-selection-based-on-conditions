<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/246374284/23.1.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T869704)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
# DataGrid for DevExtreme - How to prevent/disable selection of specific rows

This example demonstrates how to disable selection in certain rows in [multiple record selection mode](https://js.devexpress.com/Demos/WidgetsGallery/Demo/DataGrid/MultipleRecordSelectionModes/jQuery/Light/). In this example, a row is disabled if its **approved** value is `false`. 

![The first row is disabled](devextreme-datagrid-disable-selecting-certain-rows.png)

Specify the following properties to implement the technique:

1. Implement the [onEditorPreparing](https://js.devexpress.com/Documentation/ApiReference/UI_Components/dxDataGrid/Configuration/#onEditorPreparing) event handler to display disabled selection checkboxes.
2. Implement the [onSelectionChanged](https://js.devexpress.com/Documentation/ApiReference/UI_Components/dxDataGrid/Configuration/#onSelectionChanged) event handler. In this handler, specify the checkboxes that need to stay disabled after a user toggles the **Select All** checkbox.

Note that you need to set the [remoteOperations](https://js.devexpress.com/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/remoteOperations/) to `false` for this example to work.

## Files to Review

- **jQuery**
    - [index.html](jQuery/src/index.html)
    - [index.js](jQuery/src/index.js)
- **Angular**
    - [app.component.html](Angular/src/app/app.component.html)
    - [app.component.ts](Angular/src/app/app.component.ts)
- **Vue**
    - [HomeContent.vue](Vue/src/components/HomeContent.vue)
- **React**
    - [App.tsx](React/src/App.tsx)
- **ASP.NET Core**    
    - [Index.cshtml](ASPNETCore/Views/Home/Index.cshtml)

## Documentation

- [Getting Started with DataGrid](https://js.devexpress.com/Documentation/Guide/UI_Components/DataGrid/Getting_Started_with_DataGrid/)

- [DataGrid - API Reference](https://js.devexpress.com/Documentation/ApiReference/UI_Components/dxDataGrid/)

## More Examples

- [DataGrid for DevExtreme - How to show/hide or enable/disable Edit Form items based on another item's value](https://github.com/DevExpress-Examples/devextreme-datagrid-hide-show-edit-form-items-dynamically)

- [DataGrid for DevExtreme - Multiple cell selection](https://github.com/DevExpress-Examples/devextreme-datagrid-multiple-cell-selection)

- [DataGrid for DevExtreme - Update multiple values in a row after selecting an item in a lookup column editor](https://github.com/DevExpress-Examples/devextreme-datagrid-update-multiple-cells)
<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=devextreme-datagrid-disable-selecting-certain-rows&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=devextreme-datagrid-disable-selecting-certain-rows&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
