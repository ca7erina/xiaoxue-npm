1.
```
npm init .
```

2.
```
$ node
> var area = require('./index.js');
undefined
> area(2,4)
8
>
(^C again to quit)
> 
```

3.
```
npm login or npm adduser <your username>
```

4.
```
$ npm version 1.0.0
v1.0.0
$ git add package.json test.js
$ git commit -m "release 1.0.0"
$ git tag 1.0.0
$ git push && git push --tags
$ npm publish
```

5.
```
npm install xiaoxue-npm
import area from '../node_modules/xiaoxue-npm';
```
