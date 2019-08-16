# sapui5-web-components
The fastest way to get started with SAPUI5 Web Components

## Description
First, we need to install all the required packages.

```shell
$ npm install
```

Use [Parcel](https://parceljs.org/) as the development server. You can install Parcel globally.

```shell
$ npm install -g parcel
```

Once Parcel is installed, we can run it by pointing directly to our `index.html` file. Parcel will bundle all the necessary recourses for you and generate an URL for the server.

```shell
$ parcel src/index.html
Server running at http://localhost:1234
✨ Built in 3.84s.
```

As part of the enterprise readiness, all UI5 web components implement:

- standard themes supported by SAP products
  - http://localhost:1234?sap-ui-theme=sap_belize
  - http://localhost:1234?sap-ui-theme=sap_belize_hcb
- internationalisation
  - http://localhost:1234/?sap-ui-language=de
  - http://localhost:1234/?sap-ui-language=he
- right to left languages
  - http://localhost:1234/?sap-ui-rtl=true
