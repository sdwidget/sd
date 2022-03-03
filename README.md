# SmartDeFi Widget


## Installation

Copy the javascript and css files into your websites html 

### Best practice

Add the css file to the `<head>` section and js files at the end of `<body>` tag

## Usage

Add a `<div>` element where you would like the widget to display and add the corresponding data tags.

| Propertiy  | Required | values                |
| ---------- | -------- | ------------------------ |
| data-token | required | Token address|
| data-chain | required | 56 for BSC or 1 for ETH |
| data-theme | optional | dark or light | 
| data-elevation | optional | on or off|
  
### Example

`<div id="sd-widget" data-token="contract address" data-chain="56" data-theme="dark" data-elevation="on"></div>`
