## Authentication

### [What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

#### What is OAuth?

> OAuth (Open Authorization) is an open standard protocol that allows secure authorization and delegation of access to resources on behalf of a user without sharing their credentials. It provides a framework for applications to obtain limited access to user accounts on various services (known as resource servers) using tokens.

#### Give an example of what using OAuth would look like.

> When a user decides to use an application, they are redirected to the service's login page where they can review the requested permissions and decide whether to grant access. If access is granted, the service generates an authorization grant. The application then exchanges this grant for an access token, which it can use to securely access the user's data on the service. With the access token, the application can make API requests and interact with the authorized resources

#### How does OAuth work? What are the steps that it takes to authenticate the user?

1. The user interacts with a client application and expresses their desire to access a resource or service.

2. The client application redirects the user to the authorization server, which hosts the user's account and manages authorization. The request includes the client's identification information.

3. The authorization server presents the user with a consent screen, describing the requested permissions and scope of access the client application is seeking. The user decides whether to grant or deny access.

4. If the user grants access, the authorization server issues an authorization grant to the client application. This grant serves as proof that the user has given consent.

5. The client application sends the authorization grant to the authorization server, along with its identification information, to request an access token.

6. The authorization server verifies the authorization grant and, if valid, issues an access token to the client application. The access token represents the client's authorized access to the requested resources.

7. The client application uses the access token to make API requests to the resource server, which hosts the protected resources. The access token is sent as a credential in the request headers.

8. The resource server validates the access token received from the client application. If the token is valid and authorized, the server processes the request and returns the requested resources.

#### What is OpenID?

> OpenID is an open standard and decentralized authentication protocol that allows users to authenticate themselves across different websites or applications using a single set of credentials. OpenID offers a convenient "Single Sign-On" (SSO) experience for users, as they only need to remember and manage one set of credentials for multiple services.

### [Authorization and Authentication flows](https://auth0.com/docs/flows)

#### What is the difference between authorization and authentication?

> Authentication is the process of verifying the identity of a user or entity. It ensures that the user or entity is who they claim to be. Authentication typically involves providing credentials, such as a username and password, and validating those credentials against stored user data or an identity provider.

> Authorization comes after authentication and determines what actions or resources a user or entity is allowed to access based on their authenticated identity. It involves granting or denying permissions to perform specific operations or access specific resources.

#### What is Authorization Code Flow?

> The Authorization Code Flow ensures that sensitive information, such as access tokens, is never exposed to the end-user's browser and provides a higher level of security compared to other authentication flows. It separates the roles of the authorization server and the client application, making it suitable for web applications where the client secret can be securely stored on the server-side.

#### What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

> An enhanced version of the OAuth 2.0 Authorization Code Flow. It adds an additional security layer to protect against certain attacks, particularly those targeting native or mobile applications where it is challenging to securely store a client secret. The use of PKCE provides an additional layer of security by ensuring that the authorization code cannot be used by an attacker even if intercepted. The code verifier remains confidential within the client application and is never exposed to the authorization server or end-user's browser.

#### What is Implicit Flow with Form Post?

> The Implicit Flow with Form Post is an OAuth 2.0 authentication flow that was commonly used in the past for single-page applications. It was designed to obtain an access token directly from the authorization server without an intermediate authorization code exchange step.

#### What is Client Credentials Flow?

> The Client Credentials Flow is an OAuth 2.0 authentication flow used by confidential clients, such as server-side applications or services, to obtain an access token without user involvement. Unlike other flows that authenticate a user, the Client Credentials Flow directly authenticates the client application itself.

#### What is Device Authorization Flow?

> An OAuth 2.0 authentication flow designed for devices with limited input capabilities, such as smart TVs, gaming consoles, or devices without a web browser. It allows users to authenticate and authorize access to their accounts on these devices by using a secondary device, such as a smartphone or computer, to complete the authentication process.

#### What is Resource Owner Password Flow?

> an OAuth 2.0 authentication flow that allows client applications to directly obtain an access token from the authorization server by presenting the resource owner's (user's) credentials. This flow is typically used when the client application is highly trusted or controlled, such as a first-party application owned by the same entity as the authorization server.

*Video - Bookmarked and Reviewed*

- [Auth0 for single page apps](https://auth0.com/docs/libraries/auth0-react)
