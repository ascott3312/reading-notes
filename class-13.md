# Local Storage
 1.What we really want is:
    a lot of storage space
    b. on the client
    c. that persists beyond a page refresh
    d, isn’t transmitted to the server 
## Cookies 
  - Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides:
  - Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
  - Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
  - Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful
### HTML5    
    - HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. 
    - The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. 
    - However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, 
    - you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.
#### History
    1. Microsoft - user data IE Explorere
    1. Adobe introduced a feature in Flash 6 (2002)
    1. Google launched Gears, an open source browser plugin (2007)
    1. Brad Neuberg and others continued to hack away on dojox.storage (2009)
    
