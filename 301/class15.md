Readings: Authentication

- What is OAuth?
an open-standard security mechanism that lets you authorize one application to engage with another on your account.

- Give an example of what using OAuth would look like.
The simplest example of OAuth in action is one website saying “hey, do you want to log into our website with other website's login?

- How does OAuth work? What are the steps that it takes to authenticate the user?
Step 1 – The User Shows Intent.
Step 2 – The Consumer Gets Permission.
Step 3 – The User Is Redirected to the Service Provider.
Step 4 – The User Gives Permission.
Step 5 – The Consumer Obtains an Access Token.
Step 6 – The Consumer Accesses the Protected Resource.

- What is OpenID?
OpenID is an open standard for federated authentication. When visiting a website, users present their OpenID to sign in. The user then authenticates with their chosen OpenID provider, which issues an assertion to confirm the user's identity. The website verifies this assertion in order to sign the user in.





- What is the difference between authorization and authentication?
authentication is the process of verifying who someone is, whereas authorization is the process of verifying what specific applications, files, and data a user has access to.

- What is Authorization Code Flow?
they can use the Authorization Code Flow, which exchanges an Authorization Code for a token.

- What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
a security extension to OAuth 2.0 for public clients on mobile devices, designed to prevent interception of the authorisation code by a malicious application that has sneaked into the same device.

- What is Implicit Flow with Form Post?
uses OIDC to implement web sign-in that is very similar to the way SAML and WS-Federation operates. The web app requests and obtains tokens through the front channel, without the need for secrets or extra backend calls.

- What is Client Credentials Flow?
The client credentials flow is used when an application needs to obtain permission to act on its own behalf. An application will exchange it's client_id , client_secret , and grant_type=client_credentials for an application access token.

- What is Device Authorization Flow?
The user authorizes the device, so the device can receive tokens. Receive Tokens (Device Flow): After the user successfully authorizes the device, receive tokens. Call your API (Device Flow): Use the retrieved Access Token to call your API.

- What is Resource Owner Password Flow?
The Resource Owner Password Flow is really pretty simple, as it allows the client to exchange a user's username and password for an access token. it means the client applications, let's say an Android app will really need ask for the username and password.
