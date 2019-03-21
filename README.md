# Installing latest Node.js LTS with NPM
https://tecadmin.net/install-latest-nodejs-npm-on-ubuntu/

# Installing Yarn

```bash
$ sudo apt-get install gcc g++ make
$ curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
$ echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
$ sudo apt-get update && sudo apt-get install yarn
```

# Installing npm depenedecnies
```bash
$ npm audit fix --force
$ npm install --save-dev  @babel/core@^7.0.0-0
$ npm install @babel/preset-env --save-dev
```

# Transpiling ES6 to ES5

```bash
$ npm run build
```
