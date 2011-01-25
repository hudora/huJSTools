huJSTools - a collection of Javascript helper functions
=======================================================

huJSTools includes various Javascript helper methods. They must be used in combination with ExtJS and provide methods for easy handling of often-used tasks. To use the javascript helpers you will have to link the `web` directory into the directory declared the `static_dir` directory in your `app.yaml`. Then include the `huJSTools.js` and `huJSTools.css` files into your HTML page template.

Currently the helper includes the following methods:

 * `Hudora.Formatters.formatAddress(fields)`: format a model (object with fields) representing an adress record into a string ready to be written to a DisplayField in ExtJS.

 * `Hudora.Formatters.formatDate(date)`: parse the given date string (e.g. from a JSON server response) and return it formated in the HUDORA default format "Weekday, YYYY-MM-DD".

 * `Hudora.Helpers.spinnerMessageBox(message)`: display a non-closable messagebox with a spinner indicating progress
 * `Hudora.Helpers.errorMessageBox(title, message)`: display a error message box without having to write five lines of code every time you need an error messagebox.

 * `Hudora.Helpers.getUrlParamater(param)`: extract a query parameter from the current URL or return an object with all parameters if no parameter name is provided.


