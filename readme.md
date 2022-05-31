# **Code Grepper API Documentation**

<img align="right" width="250" style="margin-left: 10px;" height="250" src="./assets/Grepper%20Logo.png">

**NOTE:** You can find the older documentation [here](./old.md).

[Code Grepper][cgurl] also known as Grepper is a platform to help developers solve technical problems. [Grepper][cgurl] is powered by an amazing community of 200k(and growing fast) developers. Developers within the community contribute answers to technical problems primarily through the [Grepper][cgurl] browser extension which allows a user to quickly add a “code snippet” as an answer to a problem they ran into and recently solved. At present the community has put in 318k answers, which together have been viewed over 62 million times.

[cgurl]: https://codegrepper.com

## **Table Of Contents**

- [NPM Package](https://www.npmjs.com/package/grepper)
- [Users](./docs/users/)
  - [Get User](./docs/users/GETUSER.MD)
  - [Get My Info](./docs/users/USERBYTOKEN.MD)
  - [Get Who To Follow](./docs/users/WHOTOFOLLOW.md)
- [Answers](./docs/answers)
  - [Get Answers](./docs/answers/GETANSWERS.MD)
  - [Publish Answer](./docs/answers/PUBLISHANSWER.MD)
  - [Similiar Queries](./docs/answers/SIMILIARQUERIES.MD)
- [Teams](./docs/teams)
  - [Invite User](./docs/teams/INVITEUSER.MD)
- [Auth](./docs/auth)
  - [Access Token](./docs/auth/TOKEN.MD)

## Authorization

| Icon | Description                                                       |
| ---- | ----------------------------------------------------------------- |
| 🔒   | This API endpoint requires [Authorization](./docs/auth/TOKEN.MD). |
| ✅   | No [Authorization](./docs/auth/TOKEN.MD) required.                |
