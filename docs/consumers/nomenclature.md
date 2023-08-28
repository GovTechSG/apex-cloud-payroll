# Nomenclature and Terms

These are the nomaclature and terms used in this guide.

| S/No | Terms                | Definition                                                                                                                                                                                                                                                                                                         |
| ---- | -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| 1    | Publisher            | API administrator of APIs made available on APEX platform.                                                                                                                                                                                                                                                         |
| 2    | Consumer             | Application utilizing the APIs which are published by APEX Publishers.                                                                                                                                                                                                                                             |
| 3    | Developer / SWD      | Software Developer (you) developing the client.                                                                                                                                                                                                                                                                    |
| 4    | Client               | The application that is attempting to act on the user’s behalf to access the user’s resources.                                                                                                                                                                                                                     |
| 5    | Authorization Server | The authorization server is what the user interacts with when a client is requesting access to their account. This server displays the consent prompt for user to approve or deny the request. The authorization server is also responsible for granting access tokens after the users authorizes the application. |
| 6    | Authorization Code   | A temporary code that the Authorization Server generates when the user authorizes a request. The client will exchange the authorization code for an access token.                                                                                                                                                  |
| 7    | Access Token         | The thing that allows a client to access an API. It is a string that represents authorization granted to the client by the user. It represents specific scopes and duration of access. It is granted by the user and enforced by the authorization server.                                                         |
| 8    | Resource Server      | The resource server (aka API server) is the server that hosts the protected resources and uses the access tokens to accept and respond to protected resource requests.                                                                                                                                             |
| 9    | Code Verifier        | Randomly generated string                                                                                                                                                                                                                                                                                          |
| 10   | Code Challenge       | Hashed value of Code Verifier                                                                                                                                                                                                                                                                                      |
| 11   | APEX                 | API Exchange Portal that developer can discover APIs, learn how to use them, request access and try them out.                                                                                                                                                                                                      |