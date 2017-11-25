### 一个简单的C++扩展，其功能相当于js的如下代码：

    module.exports.hello = () => 'world';

### 安装编译

    npm install -g node-gyp

    node-gyp configure

    node-gyp build

    node test/main.js