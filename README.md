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
