# UK Intellectual Property Office Assets

This project is used to build the UK Intellectual Property Office frontend UI styling.

The style sheets are also available independently as a <a href="https://www.npmjs.com/package/ipo-assets-frontend">Node.js module</a>:

```sh
npm i ipo-assets-frontend
```

## Usage

UK IPO assets have been built as an addon for existing <a href="https://github.com/alphagov/govuk_elements">GOV.UK Elements</a> and <a href="https://github.com/alphagov/govuk_frontend_toolkit">GOV.UK Frontend Toolkit</a>  packages.

When compiled with GOV.UK Frontend, it will produce styles heets ready for use on UK IPO projects.

## Requirements

UK IPO assets are available in two forms. This repository provides you with everything you should need to start development. 
The Node.js package is intended for the end user.

#### As a Visual Studio project:
* <a href="https://www.visualstudio.com/">Microsoft Visual Studio</a>. 
* <a href="https://nodejs.org/en/">Node.js</a> version 3.X+.
* <a href="https://github.com/alphagov/govuk_elements">GOV.UK Elements</a>. 
  * <a href="https://github.com/alphagov/govuk_frontend_toolkit">GOV.UK Frontend Toolkit</a>.  
  * <a href="https://github.com/alphagov/govuk_template">GOV.UK Template</a>. 
* A compiler such as <a href="https://marketplace.visualstudio.com/items?itemName=MadsKristensen.WebCompiler">Web Compiler</a>.
 

#### As a Node.js module:
* <a href="https://nodejs.org/en/">Node.js</a> version 3.X+.
* <a href="https://github.com/alphagov/govuk_elements">GOV.UK Elements</a>. 
  * <a href="https://github.com/alphagov/govuk_frontend_toolkit">GOV.UK Frontend Toolkit</a>.  
  * <a href="https://github.com/alphagov/govuk_template">GOV.UK Template</a>. 
* A SASS compiler such as <a href="https://github.com/dlmanning/gulp-sass">gulp-sass</a> (if you wish to manually compile your own stylsheets). 

## Installation

#### As a Visual Studio project: 

This is recommended for users who wish to make changes to the style sheets.

* Download and install <a href="https://nodejs.org/en/">Node.js</a>.
* Install <a href="https://marketplace.visualstudio.com/items?itemName=MadsKristensen.WebCompiler">Web Compiler</a> or <a href="https://marketplace.visualstudio.com/items?itemName=MadsKristensen.WebExtensionPack2017">Web Essentials 2017</a> for Visual Studio.
* Clone this repository: 
    ```sh
    https://github.com/intellectual-property-office/Assets.git
    ``` 
* Install all project dependencies:
    ```sh
    npm install
    ``` 
* Open the Visual Studio solution file

#### As a Node.js module:

This is recommended for users who wish to use the style sheets. 

* Download and install <a href="https://nodejs.org/en/">Node.js</a>.
* Run the following command to install the UK IPO assets module: 
    ```sh
    npm i ipo-assets-frontend
    ```
* Install all dependencies:
    ```sh
    npm install
    ```

## Help

For additional guidance, contact the UX team.
