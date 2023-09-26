# Bearer Authorization

## Reading

### [Intro to JWT](https://jwt.io/introduction/)

#### What is a JSON Web Token (JWT)?

> A compact and self-contained way to represent information between two parties as a JSON object. JWTs are often used for securely transmitting information between a client and a server, typically as part of an authentication or authorization process.

#### When should we use JSON Web Tokens?

> afor authentication, SSO, authorization, and user identity verification.

#### Claims are expected in which structural component of a JWT?

> Claims are expected in the Payload component of a JWT. The payload is the second part of a JWT, and it contains claims, which are statements about an entity (typically, the user) and additional data

### [Are JWTs Secure?](https://stackoverflow.com/questions/27301557/if-you-can-decode-jwt-how-are-they-secure)

#### If I get a JWT and I can decode the payload, how can we call that secure?

>  When you say you can "decode" the payload of a JWT, it's typically because JWTs are designed to be easily decoded to reveal their contents. Instead, it relies on the payload being tamper-evident (via the signature). While you can decode the payload, an attacker should not be able to tamper with it or create valid tokens without knowing the secret or private key used for signing.

#### If sending a JWT, what must sender and receiver both know? Hint, it’s appended in the signature.

> When sending a JWT, both the sender and receiver must know the shared secret key that is used to create and verify the signature of the JWT. The use of secret keys or public/private key pairs in the signature process is a fundamental aspect of JWT security, and it ensures the authenticity and integrity of the token.

#### Explain how concatenated content and secret can be sent and received securely to a non-technical recruiter.

> Imagine you're sending a secret message to someone, like a treasure map to a hidden treasure. You don't want anyone else to read the map, so you send the treasure map securely in a locked box with a special key, a JWT is sent with a signature (the locked box) that's created using a secret key (the special key). Only the recipient with the key can open and trust the JWT, ensuring the secure exchange of information between parties.

## Videos

### [JWTs Explained](https://www.youtube.com/watch?v=926mknSW9Lo)

#### Why use JWT?

> JSON Web Tokens (JWTs) are used in web development and application security for stateless authentication, cross-domain authorization, single sign-on (SSO), scalability, compactness, flexibility, security, and reduced database load. They are self-contained, standardized, and widely adopted for securely transmitting information between parties. Proper implementation and security measures are essential when using JWTs.

#### JWT is Compact and self-contained. Describe how this is useful to a non-technical friend.

> a JWT is like a compact suitcase that has everything you need for your online journey, making things fast and easy when you're using the internet.

#### What are the three components (the structure) of a JWT signature?

1. Header: Contains information about the token's encoding and signing algorithm.

2. Payload: Contains claims, which are statements about the entity and additional data.

3. Signature: Created by applying the specified algorithm to the encoded header, encoded payload, and a secret (or private key) to verify the JWT's authenticity and integrity.

### Bookmark and Review

[npm jsonwebtoken docs](https://www.npmjs.com/package/jsonwebtoken)

### Reflection

#### What are your learning goals after reading and reviewing the [class README?](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-07/)

> I am excited to learn about bearer tokens

## Things I want to know more about

> I would like to know more about how to proprely vet APIs that i can find online. I struggle to be able to tell if an API key is worth using or not, until I've already designed a project around it.
