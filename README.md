# nodejs es6语法 import export等支持demo

step1:
```
npm install --save-dev babel-preset-env
```

step2:
```
npm install --save babel-register
```

step3:
```
require('babel-register')

require('./app.js')
```

*app.js 为入口文件，可以使用import代替require来引入文件*
