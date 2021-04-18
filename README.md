This is the companion github repo for the [How to build your first SaaS](https://www.freecodecamp.org/news/how-to-build-your-first-saas/) article.

## Description

A minimal foundation upon which you can putter your first full-stack application.

"**Why not just `create-react-app` etc. though?**" Although they are great for one-off prototype and to "move fast and break things", they have hidden cost in terms of complexity and obfuscation, both of which limit user's sense of control, personal responsiblity, and understanding as long as they stay within the happy paths. But we are building a garden we intend to _putter_ while comporting ourselves with the greatest freedom and rectitude possible, rather than with a false sense of security.

## Features

- Already setup server and client
- Lighter footprint than CRA on your machine
- Preact(alternatively, I suggest [Sinuous](https://sinuous.dev/) which doesn't use virtual dom)
- Supports IE11
- Serves ES modules(less code shipped) to modern browsers
- Use the web platform as much as possible(e.g. Not using SCSS. Leverage standard CSS with PostCSS)
