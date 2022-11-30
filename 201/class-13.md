# Class 13: Local Storage

[Local Storage and How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

1. Why would a developer use local storage for a web application?
<br> When you use the web with its default setting (HTTP as the main transport layer) whatever you have done in a session, the state will reset when you close the web and re open it. But it is important for a web app developer to store the state of the interface, and local storage allow this to take place. It will keep a key on the user’s computer and read it out when the user returns.

2. What information should not be stored in local storage?
<br>Sensitive information. like personal details or password.


3. Local storage can store what type of data? How would you convert it to that type before storing?
<br> Local storage store striong data. You can work around this by using the native `JSON.stringify()` and `JSON.parse()` methods.

## Bookmark
[“The Past, Present, and Future of Local Storage for Web Applications”](http://diveinto.html5doctor.com/storage.html)

## Things I want to know more about
<br> I will like to know how to do calls to retrieve the data store in local storage.