Key concepts I have used and learned from this
- [x] "DOMContentLoaded"
- [x] "load"


 
 #### DOMContentLoaded
 ```
The DOMContentLoaded event fires 
when the initial HTML document has been completely loaded and parsed, 
without waiting for stylesheets, images, and subframes to finish loading.

the browser fully loaded HTML, and the DOM tree is built, but external resources like pictures <img> and stylesheets may be not yet loaded.
```

 #### load
```
Not only HTML is loaded, 
but also all the external resources: images, styles etc.
```


#### beforeunload/unload 

- The user is leaving the page.


#### Events

- DOMContentLoaded event: DOM is ready, so the handler can lookup DOM nodes, initialize the interface.
- load event: external resources are loaded, so styles are applied, image sizes are known etc.
- beforeunload event: the user is leaving: we can check if the user saved the changes and ask them whether they really want to leave.
- unload: the user almost left, but we still can initiate some operations, such as sending out statistics.
# video-load-js
