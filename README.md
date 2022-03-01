# sinopia
自建本地仓库

# install
$ npm install sinopia -g
$ npm install nrm -g

> 由于版本问题，sinopia报错需要补全回调参数，例如修改fs.unlink(tmp)为fs.unlink(tmp, function() {})

# 设置本地地址，建议使用本机IP
$ npm set registry http://localhost:4873/

$ npm set ca null

# 增加用户，设置用户名、密码、邮箱
$ npm adduser --registry http://localhost:4873/

> 开发

# 使用webpack-simple创建无路由项目模板，开发公共组件，删除冗余文件
$ npm install webpack-simple -g

$ vue init webpack-simple CustomComponent


> 发布

$ npm login

$ npm publish
