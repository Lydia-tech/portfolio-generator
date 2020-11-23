### To initialize a node repository 
```git
npm install -y
```
### Ensure that .gitignore contains the following 
```shell
node_modules
.DS_Store
```
### Target entrypoint file in package.json
```json
{
  "main": "app.js",
}
```

### install npm packages such as inquierer
```git
npm install inquirer
```

### Check versions of npm or node
```git
node --version
npm --version
```

### use terminal to search for a package
```git
npm search <package>
//
npm search inquirer
```

// commonjs - old way
const inquirer = require('inquirer');

//ES6 - new way
// import inquirer from 'inquirer';

const numbers = [5, 7, 8]
console.log(numbers)
console.log(`Hello Node! we have numbers ${numbers}!`)