{
  "name": "@bhojrajjoshi2020/semvertest",
  "version": "0.0.0",
  "description": "Sample code for semvertest",
  "main": "constants.js",
  "dependencies": {
    "authorizenet": "^1.0.7",
    "chai": "^3.5.0",
    "eslint": "^2.12.0"
  },
  "devDependencies": {},
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "https://github.com/bhojrajjoshi2020/semvertest.git"
  },
  "keywords": [
    "AuthorizeNet",
    "sample",
    "codes"
  ],
  "author": "",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/bhojrajjoshi2020/semvertest/issues"
  },
  "homepage": "https://github.com/bhojrajjoshi2020/semvertest#readme",
  "publishConfig": {
    "registry": "https://npm.pkg.github.com/"
  },
  "plugins": [
    "@semantic-release/commit-analyzer",
    "@semantic-release/release-notes-generator",
    ["@semantic-release/exec", {
      #"verifyConditionsCmd": "./verify.sh",
      "publishCmd": "./publish.sh ${nextRelease.version} ${options.branch} ${commits.length} ${Date.now()}"
    }],
  ]
}
