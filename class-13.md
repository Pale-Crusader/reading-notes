# Code 201 Reading Notes

* [Link Back to Reading Notes Main](https://pale-crusader.github.io/reading-notes)


> Here’s what to read before class:

> Article:

> [“The Past, Present, and Future of Local Storage for Web Applications”](http://diveinto.html5doctor.com/storage.html)


### Ye Olde Style Historical Document Style For Amusing Irony

* I like this, the subtle bit of humor the font and styling adds to a technical document

#### <pun> Key (and Valuable) Points </pun>
* Web browsers don't have the luxury of local storage beyond cookies, which are built for only small bits of data, aren't encrypted except on SSL and low browser down

* ideally browsers would want lots of storage on the client's side which persists after pages refresh and isn't wasting bandwidth by being transmitted to the server 

* before HTML5 is _History_, which makes me glad we have it as before trying to get those wasn't so great

#### The Glorious Present

* “HTML5 Storage”, is known as Web Storage also, as well was Local Storage, or DOM storage depending on the different browser because people can't always agree

* It does all the aforementioned things we wanted

* IE 8.0+, FIREFOX 3.5+, SAFARI 4.0+, CHROME 4.0+, OPERA 10.5+, IPHONE 2.0+, ANDROID 2.0+ support it

* this is how you can use javascript function to check for HTML5 Storage support of client's browser

> ```function supports_html5_storage() {```
> ```  try {```
> ```    return 'localStorage' in window && window['localStorage'] !== null;```
> ```  } catch (e) {```
> ```    return false;```
> ```  }```
> ```}```

* This is a third party library version

> ```if (Modernizr.localstorage) {```
> ```  // window.localStorage is available!```
> ```} else {```
> ```  // no native support for HTML5 storage :(```
> ```  // maybe try dojox.storage or a third-party solution```
> ```}```

* After Detected it can be used based on key/value pair. The data is stared based on named key and later be retrieved via the same key, like a declared variable/value or property/value.

> ```interface Storage {```
> ```  getter any getItem(in DOMString key);```
> ```  setter creator void setItem(in DOMString key, in any data);```
> ```};```


* ```setItem()``` with a named  key that exists already overwrites previous value, which calling with ```getItem()``` with a non existence key returns null 

* event listeners can be added the the window with ```addEventListener("storage", handle_storage)```

* 5 megabytes is the standard storage limit for HTML5 storage on most browsers, ```QUOTA_EXCEEDED_ERR``` is what you get when you go over

#### Contentious Future

* beyond the 5 mb of key/value pair limts of today there are different opinions on the right solution
	* Web SQL Database, has Javascript interface commands
	* Indexed Database API, stores things as object