Example app from https://medium.com/@vipinswarnkar1989/mern-stack-crud-app-using-create-react-app-react-redux-3299059db793

```
mkdir express-server && cd express-server
npm init
npm install express --save
npm install body-parser mongoose morgan babel-preset-es2015-node6 source-map-support --save
npm install --save babel-preset-es2015-node6
npm install --save source-map-support
npm install --save babel-register
```

To test API:
```
mongod --bind_ip=$IP --nojournal
npm start
```