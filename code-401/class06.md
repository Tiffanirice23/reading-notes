# Readings: Authentication

## Readings

### [Securing Passwords](https://thehackernews.com/2014/04/securing-passwords-with-bcrypt-hashing.html)

#### Explain to a non-technical friend how you would safely hash and store a password.

> Imagine your password is like a special key that unlocks your personal lockbox, and you want to keep that key safe. Your password (the key) is turned into a unique pattern with a secret ingredient and kept safe inside a strong lockbox. Only the computer knows how to recreate this pattern with the secret ingredient to see if it matches.

#### What is Bcrypt?

> A widely used cryptographic hashing function that is specifically designed for securely hashing passwords. Bcrypt is a preferred choice for securely hashing passwords in web applications and other systems where password security is crucial.

#### Why might you use something like Bcrypt?

> Using Bcrypt or similar password hashing algorithms is a fundamental practice in cybersecurity for protecting sensitive user credentials and maintaining the security and trustworthiness of your application or system. You might use it for several important reasons, such as password security, salted hashes, standardization, ect.

### [Basic Auth](https://en.wikipedia.org/wiki/Basic_access_authentication)

#### What is Basic Authentication?

> Basic Authentication is a simple and straightforward method for authenticating users in web applications and APIs. It's based on the HTTP protocol and involves the transmission of a username and password, typically in an encoded form, to access protected resources. It is considered relatively insecure when used on its own

#### What properties are necessary in the header of a Basic Auth request?

> A request contains a header field in the form of `Authorization: Basic <credentials>`, where credentials is the Base64 encoding of ID and password joined by a single colon `:`

#### How are `username:password` in Basic Auth encoded?

> The username and password are joined with a ‘:’ then “base64 encoded” and placed after the string ‘Basic.

### [OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

#### Define the authentication process to a non-technical recruiter.

> Authentication is like proving who you are when you want to access something, just like showing your ID card to get into a secure building. It uses a combination of something you know (a password) and sometimes something you have (a card or phone) or something unique to you (biometrics). 

#### How should your error messaging respond (both HTTP and HTML)? Why?

> Effective error messaging involves providing appropriate HTTP status codes, clear HTML error messages, and a user-friendly experience. The goal is to guide users in understanding and resolving issues while also providing enough information for developers to diagnose and fix problems on the server side.

#### Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

## Bookmark and Review

#### [bcrypt docs](https://www.npmjs.com/package/bcrypt)

## Additional Questions

#### Looking ahead at this module’s [course schedule](https://codefellows.github.io/code-401-javascript-guide/curriculum/#module-2), What do you look forward to learning?

> I look forward to learning about role based access control, as it seems like it'd be very important for future jobs.

#### What are your learning goals after reading and reviewing the [class README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-06/)

> Getting faster at backend developement and learning all about password encryption
