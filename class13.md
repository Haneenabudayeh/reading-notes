# THE PAST, PRESENT & FUTURE OF LOCAL STORAGE FOR WEB APPLICATIONS:


Web Storage is a new HTML5 API offering important benefits over traditional cookies. Although the specification is still in W3C draft status, all major browsers support it already.


## The Limitations of Cookies
First, there were cookies. They have been a huge driving factor for the Web since the early days. In both a good and a bad way.

### What is HTML Web Storage?
With web storage, web applications can store data locally within the user's browser.

Before HTML5, application data had to be stored in cookies, included in every server request. Web storage is more secure, and large amounts of data can be stored locally, without affecting website performance.

Unlike cookies, the storage limit is far larger (at least 5MB) and information is never transferred to the server.

Web storage is per origin (per domain and protocol). All pages, from one origin, can store and access the same data.

### HTML Web Storage Objects
- HTML web storage provides two objects for storing data on the client:

1. window.localStorage - stores data with no expiration date
1. window.sessionStorage - stores data for one session (data is lost when the browser tab is closed)


#### Types of Web Storage
* Local storage: Stores data with no expiration date. The data will be available even when the browser/ browsing tab is closed or reopened.

* Session storage: Stores data for one session. Data persisted will be cleared as soon as the user closes the browser.

*In both the cases, please note that the web storage data will not be available between different browsers*.

#### Storage Events
When we set or remove data from the web storage, a storage event will be fired on the window object. We can add listeners to the event and handle the storage changes if required.

#### The event object has the following attributes

- key – the property that has changed
- newValue – the newly set value
- oldValue –  previously stored  value
- url – the full url path from where the event originated
- storageArea –  localStorage or sessionStorage obje
