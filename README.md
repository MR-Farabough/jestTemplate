# jestTemplate

Create package.json `npm init`

Install jest `npm install --save-dev jest`

Create a test file `<filename>.test.js`

> Add the following section to your package.json:

<code> 
{
  "scripts": {
    "test": "jest"
  }
}
</code>

Run test `npm test`

### If You want to add a watch affect

> Add the following section to your package.json:

<code> 
{
  "scripts": {
    "test": "jest",
    "watch": "jest --watch *.js"
  }
}
</code>

Run watch `npm run watch`