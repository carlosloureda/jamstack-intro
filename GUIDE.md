# Introduction

JAMStack: Javascript APIS Markup

- They only use CDN so we skip servers, load balancers ...
- CDN is cheap!
- Platform agnostic

- Better security
- Better performance
- Better reliability

## Parts of the course

- Vanilla JAMStack
- Serverless Contact Form
- User Dashboard SPA
- Persisting Data

# Vanilla JAMStack

[branch section-1-basic-jam-site]()

To run the first project, go to `/sections/basic/` and exec:

```sh
npx serve
```

App should be running on [http://localhost:5000/](http://localhost:5000/)

More info on [serve (by Vercel)](https://github.com/vercel/serve)

- Served css and js
- Deploy to github

  - `yarn global add netlify-cli`
  - `npm install netlify-cli -g`

---

# Tricks

## GIt

`git status -sb` --> alias s
// simplified gi status

- [semantic-releases](https://github.com/semantic-release/semantic-release#:~:text=semantic%2Drelease%20uses%20the%20commit,changelog%20and%20publishes%20the%20release)
- [angular coomit convenction](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines)

- [hub.github.com](hub.github.com)
  Set of tools for CLI -> Create repos & PR from CLI

```
git create {repoName}

# open the browser the repo
git browse
```
