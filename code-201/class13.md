## Read: Class 13

### Local Storage and How To Use It On Websites

#### Why would a developer use local storage for a web application?

> Local storage can provide a convenient and secure way to store and retrieve data on the client-side, improving performance, user experience, and enabling offline capabilities.

#### What information should not be stored in local storage?

> Sensitive information should not be stored in local storage. This includes personally identifiable information (PII) such as social security numbers, credit card numbers, passwords, or other sensitive data. Ensure that any data that is stored on the client-side is non-sensitive and non-critical.

#### Local storage can store what type of data? How would you convert it to that type before storing?

> Local storage can store data in the form of strings. This means that before storing any data in local storage, it needs to be converted to a string.

> It can be converted by using the `toString()` method. When retrieving data from local storage, we need to convert it back to its original data type by using `parseInt()`.

*Sources*

- [Local Storage and How To Use It On Websites](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

- [“The Past, Present, and Future of Local Storage for Web Applications”](http://diveinto.html5doctor.com/storage.html)
