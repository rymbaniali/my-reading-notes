THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS:

it is important to have local storage that can store alot of data that persists beyond a page refresh and without send it to the server.


In the past Cookies were invented they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:

1. Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL).
2. Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful.
3. Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over.

BEFORE HTML5:

userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure.
In 2002, Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of “Flash cookies.” it store up to 100 KB of data per domain.

By 2006, with the advent of ExternalInterface in Flash 8, accessing LSOs from JavaScript became an order of magnitude easier and faster. Brad rewrote AMASS and integrated it into the popular Dojo Toolkit under the moniker dojox.storage. In 2007, Google launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers.After obtaining permission from the user once, Gears can store unlimited amounts of data per domain in SQL database tables.By 2009, dojox.storage could auto-detect (and provide a unified interface on top of) Adobe Flash, Gears, Adobe AIR, and an early prototype of HTML5 storage that was only implemented in older versions of Firefox.

All these solutions are either specific to a single browser, or reliant on a third-party plugin.So HTML5 set out ​to provide a standardized API, implemented natively and consistently in multiple browsers, without having to rely on third-party plugins.


HTML5 Storage is a specification named Web Storage, which was at one time part of the HTML5 specification. it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser.Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually).

HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string.


Html5 storage limitations:
1. it is storing strings, not data in its original format. If we have to storing a lot of integers or floats, the difference in representation can really add up. Each digit in that float is being stored as a character, not in the usual representation of a floating point number.
2.it gives 5 megabytes storage quota.