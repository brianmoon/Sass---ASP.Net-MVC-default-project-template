# SASS ASP.Net MVC Template

This is a SASS implementation of the ASP.Net MVC Template default stylesheet.

Running SASS via Visual Studio 2010 requires the Web Workbench extension from Mindscape.

URL: http://www.mindscapehq.com/products/web-workbench

## Usage:

* Copy the sass folder to the /Content folder of your ASP.Net MVC project.

* Build the web project or Run the Custom Tool on the style.scss file to generate the style.css file.

* Include a reference to the generated style.css file from your master page or main razor layout.

`<link href="@Url.Content("~/Content/sass/style.css")" rel="stylesheet" type="text/css" />`

## Output formatting

To change the format of the generated css file, include one of the following directives as the first line to the style.scss file.

> //* scss-compile-options: :style => :expanded
> //* scss-compile-options: :style => :compressed
> //* scss-compile-options: :style => :compact
> //* scss-compile-options: :style => :nested