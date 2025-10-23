# IZS 'Info' Embedded Widget

The `IZS embedded widget` is a versatile tool designed and developed for seamless integration into your website. This README provides a brief guide on how to use the widget.

## Table of Contents

- [Usage](#usage)
- [Support](#support)

## Usage

To get started with the `IZS 'Info' embedded widget`, you need to include the widget's script and styles on your website.

### Step 1: Include the Widget Styles and Script

Add the following link tag to the `<head>` section 

```html
<link rel="stylesheet" href="https://info-widget.izs-apps.com/izs-info-widget.css">
```

and following script tag to the `<body>` section of your HTML file:

```html
<script src="https://info-widget.izs-apps.com/izs-info-widget.js"></script>
```

Example:

```html
<head>
    ...
    <link rel="stylesheet" href="https://info-widget.izs-apps.com/izs-info-widget.css">
    ...
</head>
<body>
    ...
    <script src="https://info-widget.izs-apps.com/izs-info-widget.js"></script>
</body>
```

### Step 2: Initialize the Widget

In the <body> section of your HTML file where you want the widget to appear, add the following html element with defined id attribute 

```html
<div id="izsInfoWidget"></div>
```

and initialize the widget with the folowing code, where you call the widget function with the selector of the widget container and the configuration object with required PDL id.

```javascript
IzsInfoWidget.init('#izsInfoWidget', {
  pdlId: 'sfe6efef87876efeeefe'
});
```

### Basic Example

Here is a basic example of how to use the widget:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://info-widget.izs-apps.com/izs-info-widget.css">
  <title>IZS Info Embedded Widget Example</title>
</head>
<body>
  <div id="izsInfoWidget"></div>
  
  <script src="https://info-widget.izs-apps.com/izs-info-widget.js"></script>
  <script>
    document.addEventListener('DOMContentLoaded', () => {
      IzsInfoWidget.init('#izsInfoWidget', {
        pdlId: 'sfe6efef87876efeeefe'
      });
    });
  </script>
</body>
</html>
```

## Support

If you encounter any issues or have any questions, please reach out to our support team at info@izs-institut.de
