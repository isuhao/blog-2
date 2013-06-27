JAVASCRIPT WEB APIS


While the most common scripting language ECMAscript (more widely known as JavaScript) is developed by Ecma, a great many of the APIs made available in browsers have been defined at W3C.

current status：
+ Accessible Rich Internet Applications (WAI-ARIA)
+ DOM
+ DOM events
+ Declarative Web Applications
+ JavaScript APIs
+ Mobile Web Applications
+ WICD
+ Widgets
+ XBL
+ HTML
+ Web Components
+ Web Performance

What is scripting?

A script is program code that doesn’t need pre-processing (e.g. compiling) before being run. In the context of a Web browser, scripting usually refers to program code written in JavaScript that is executed by the browser when a page is downloaded, or in response to an event triggered by the user.

Scripting can make Web pages more dynamic. For example, without reloading a new version of a page it may allow modifications to the content of that page, or allow content to be added to or sent from that page. The former has been called DHTML (Dynamic HTML), and the latter AJAX (Asynchronous JavaScript and XML).

Beyond this, scripts increasingly allow developers to create a bridge between the browser and the platform it is running on, making it possible, for example, to create Web pages that incorporate information from the user’s environment, such as current location, address book details, etc.

This additional interactivity makes Web pages behave like a traditional software application. These Web pages are often called Web applications and can be made available either directly in the browser as a Web page, or can be packaged and distributed as Widgets.

What scripting interfaces are available ?

The most basic scripting interface developed at W3C is the DOM, the Document Object Model which allows programs and scripts to dynamically access and update the content, structure and style of documents. DOM specifications form the core of DHTML.

Modifications of the content using the DOM by the user and by scripts trigger events that developers can make use of to build rich user interfaces.

A number of more advanced interfaces are being standardized, for instance:

+　XMLHttpRequest makes it possible to load additional content from the Web without loading a new document, a core component of AJAX,
+ the Geolocation API makes the user’s current location available to browser-based applications,
+ several APIs make the integration of Web applications with the local file system and storage seamless.
+ 
WAI ARIA offers mechanisms to ensure that this additional interactivity remains usable independent of devices and disabilities. Additional considerations apply to the development of Web applications for mobile devices.

Beyond scripting

While scripting offers a great opportunity to develop new interfaces and experiment with new user interactions, over time a number of these additions benefit from a more declarative approach; for instance, instead of having each and every developer re-implement a calendar-interface that allows a user to pick a date, defining an input type (`<input type='date' />`) that does it automatically saves a lot of time and bugs, and creates a ground for further innovation.

Beyond the set of declarative interfaces made available through HTML, several technologies have been developed to make these Declarative Web Applications possible.