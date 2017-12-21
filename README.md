##安装方法
npm install lvyii_cors_headers --save
或者
yarn add lvyii_cors_headers

```javascript
const lvyiiHeaders = require('lvyii-cors-headers');

res.setHeader('Access-Control-Allow-Headers', lvyiiHeaders.join(', '));
```
