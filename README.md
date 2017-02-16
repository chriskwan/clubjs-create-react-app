# clubjs-create-react-app
Tutorial on [Create React App](https://github.com/facebookincubator/create-react-app) for [club.js](https://github.com/dggriffin/club.js)

* Getting a React app up and running quickly (e.g. for a hackathon) can be a pain: https://twitter.com/thomasfuchs/status/708675139253174273

* Create React App: https://github.com/facebookincubator/create-react-app

* Deploying to GitHub Pages: https://medium.freecodecamp.com/surge-vs-github-pages-deploying-a-create-react-app-project-c0ecbf317089#.747cxv9g3

1. Add a homepage field to `package.json`: `"homepage": "https://<github-username>.github.io/<project-repo>"`
1. `npm run build`
1. `npm install --save-dev gh-pages`
1. Add a new line to scripts in `package.json`: `"deploy" : "npm run build&&gh-pages -d build"`
1. `npm run deploy`
1. Check it out on GitHub pages!

* My hackathon project using Create React App: https://github.com/chriskwan/bookstagram

* I <3 Create React App: https://twitter.com/chriskwan/status/830862683733909504