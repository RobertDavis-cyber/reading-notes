## Class 15 Reading Notes My Reading Journal for seattle-code-301d92

## Readings:  Readings: Authentication

## What is OAuth

1.What is OAuth?--*Enables an end user's account information to be used by third-party services, such as Facebook and Google, without exposing the user's account credentials to the third party.*

2.Give an example of what using OAuth would look like.--*For example, you can tell Facebook that it's OK for ESPN.com to access your profile or post updates to your timeline without having to give ESPN your Facebook password.*

3.How does OAuth work? What are the steps that it takes to authenticate the user?--*OAuth authentication follows a six step pattern:

1.An application requests authorization on a user's behalf.
2.The application obtains a Grant Token.
3.The client requests an access token by using the Grant Token.
4.The authorization server validates the Grant Token.
5.Issues an Access Token.
6.Refresh Token.*

4.What is OpenID?--*OpenID connects an identity protocol that utilizes the authorization and authentication mechanisms of OAuth*

## Authorization and Authentication flows

1.What is the difference between authorization and authentication?--*Authentication and authorization are two vital information security processes that administrators use to protect systems and information. Authentication verifies the identity of a user or service, and authorization determines their access rights.*

2.What is Authorization Code Flow?--*The auth code flow requires a user-agent that supports redirection from the authorization server (the Microsoft identity platform) back to your application.*

3.What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?--*The Authorization Code Flow + PKCE is an OpenId Connect flow specifically designed to authenticate native or mobile application users.*

4.What is Implicit Flow with Form Post?--* implicit grant is that tokens ID tokens or access tokens) are returned directly from the authorize endpoint instead of the token endpoint.*

5.What is Client Credentials Flow?--*In the client credentials flow, permissions are granted directly to the application itself by an administrator.*

6.What is Device Authorization Flow?--*The OAuth 2.0 authorization code grant type, or auth code flow, enables a client application to obtain authorized access to protected resources like web APIs. *

7.What is Resource Owner Password Flow?--*The Resource Owner Password Credentials flow allows exchanging the username and password of a user for an access token and, optionally, a refresh token.*

## Bookmark and Review

*Auth0 for single page apps*
(https://auth0.com/docs/libraries/auth0-react)
