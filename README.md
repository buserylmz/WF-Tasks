## Example 
```
var argv = require('minimist')(process.argv.slice(2));
console.dir(argv);
```
```
$ node example/parse.js -a beep -b boop
{ _: [], a: 'beep', b: 'boop' }
```
## Install 

npm install yargs --save
npm install minimist
