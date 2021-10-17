# Git Practice
A simple project to practice a few git/github workflows.  Replace the contents of this file with the contents indicated in the [instructions](./instructions.md).

## Link: 
https://datatracker.ietf.org/doc/html/rfc6749

## What I found interesting:
This article establishes an authentication framework named OAuth 2.0. I find this
article interesting because it shows the complexities involved in a secure authentication
framework. Although the gist of OAuth 2.0, like any other authentication framework, is for
the client to tell the server who they are; OAuth 2.0 requires the client to submit what is
known as an Access Token. If a client doesn't have an Access Token, but has access to a Refresh
Token, they may use it to request the former token. And if a client has none of those, there are
complex sequences of HTTP requests and responses, known as flows, that allow the client to
ultimately attain an Access Token. And this summary only touches the tip of the iceberg of
how truly complex this framework is. As more companies are utilizing this framework, it is becoming
more important for developers to learn (although many don't wish to embark on this chore).


### Tomer Ben-Yaakov's Comment
The web has become the most popular platform for which we develop software. As an aspiring software developer I believe it's important to educate oneself on the latest advancements in technology, specifically when it comes to security related frameworks such as OAuth 2.0. Academic computer science education doesn't really teach the intricacies of how the web works, or how clients are authenticated when sending requests to a server. Therefore, I truly appreciate you sharing this article as it does seem like companies are adapting this new technology into their servers and us aspiring developers must stay ahead of the curve for our skills to remain relevant in the workforce.

Thank you Sebastian, it was a very interesting yet challenging read!
