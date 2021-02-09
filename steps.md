# initialization
- npm init
- npm install express --save
- added .gitignore file
- git config --global core.autocrlf true

# removed node_models directory from remote
- git rm -r --cached node_modules
- git commit -m 'remmove node_modules directory'
- git push

# setting up express
- https://expressjs.com/en/starter/generator.html
- ngx express-generator
- deleted jade from package.json

# setting up Jest as a tes-framework
- https://www.albertgao.xyz/2017/05/24/how-to-test-expressjs-with-jest-and-supertest/
- npm install --save-dev babel-cli babel-preset-env jest supertest superagent
- added a "test" script-tag within the package.json and configured it further like described here: https://jestjs.io/docs/en/configuration
- added a first test to check if the server runs (server.test.js)