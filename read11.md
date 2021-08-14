# [reading-note-301](https://mohammadsilwadi.github.io/reading-note-301/)

## What is OAuth

OAuth is an authentication protocol that allows you to approve one application interacting with another on your behalf without giving away your password.

## Give an example of what using OAuth would look like

Facebook, GitHub

## How does OAuth work? What are the steps that it takes to authenticate the user?

+ The User Shows Intent.
+ The Consumer Gets Permission.
+ The User Is Redirected to the Service Provider.
Bitly directs Joe to Twitter for authorization>
+ The User Gives Permission.
+ The Consumer Obtains an Access Token.

## What is OpenID?

OpenID Connect is an interoperable authentication protocol based on the OAuth 2.0 family of specifications. ... OpenID Connect allows for clients of all types, including browser-based JavaScript and native mobile apps, to launch sign-in flows and receive verifiable assertions about the identity of signed-in users.

## Authorization and Authentication flows

## What is the difference between authorization and authentication?

Authentication confirms that users are who they say they are. Authorization gives those users permission to access a resource.

## What is Authorization Code Flow?

Authorization code flow is used to obtain an access token to authorize API requests. ... Access tokens while having a limited lifetime, can be renewed with a refresh token. A refresh token is valid indefinitely and provides ability for your application to schedule tasks on behalf of a user without their interaction.

## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

The Authorization Code Flow + PKCE is an OpenId Connect flow specifically designed to authenticate native or mobile application users.

## What is Implicit Flow with Form Post?

uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls.

## What is Client Credentials Flow?

 a server to server flow

## What is Device Authorization Flow?

. This is commonly seen on Apple TV apps, or devices like hardware encoders that can stream video to a YouTube channel.

## What is Resource Owner Password Flow?

 allows exchanging the username and password of a user for an access token
 
 ## Things I want to know more about
 
knowing  more about how to secure the website and the applications