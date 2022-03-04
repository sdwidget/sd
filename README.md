# SmartDeFi Widget


## Installation

Include the javascript and css files into your website

#### CSS

``` <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/sdwidget/sd/css/sdwidget.css" /> ```

#### JS

`<script src="https://cdn.jsdelivr.net/gh/sdwidget/sd/js/sdwidget.js" defer></script>`   


### Best practice

Add the css to the `<head>` section and js at the end of your `<body>` element 
#### Note - if the js script is not placed at end of body tag, make sure you use defer in script tag


## Usage

Add a `<div id="sd-widget"></div>` element where you would like the widget to display and add the corresponding data properties.

| Property  | Required | Values                | Description | 
| :--------- | :------- | :----------------------- | :----- |
| data-token | required | Token address            |         |
| data-chain | required | 56 or 1 | 56 for BSC or 1 for ETH |
| data-infura | optional | infura API key | Required for ETH chain |
| data-theme | optional | dark or light | Default dark |
| data-elevation | optional | on or off| Default off |
  

### Rendering element example

`<div id="sd-widget" data-token="SD token address" data-chain="56" data-theme="dark" data-elevation="on"></div>`

### Full code example

```
<!doctype html>
<html lang="en">
  <head>

    <!-- SmartDeFi CSS file -->
    <link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/sdwidget/sd/css/sdwidget.css" />
    
    <title>SmartDeFi Widget</title>
  </head>
  <body>

  <!-- SmartDeFi render element -->
  <div id="sd-widget" data-token="SD token address" data-chain="56" data-theme="dark" data-elevation="on"></div>

  <!-- SmartDeFi js script -->
  <script src="https://cdn.jsdelivr.net/gh/sdwidget/sd/js/sdwidget.js" defer></script>

  </body>
</html>
```
