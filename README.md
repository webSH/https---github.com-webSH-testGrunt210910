> Gruntfile.js
>>> package.json
1. npm init (初始化一个 package.json 文件)
   entry point:(index.js) 入口文件-可以输入 Gruntfile.js (并不会自动建立 Gruntfile.js 文件，可能需要手动？)
2. npm install grunt --save-dev （安装 Grunt） 
3. npm install -g grunt-cli （似乎应该先装这个）
4. 安装个插件吧（ 安装 JSHint ）
>> <1>npm install grunt-contrib-jshint --save-dev (安装失败，提示权限问题，但使用管理员运行 cmd 未解决。cnpm 安装 ok)
>> <2>npm install grunt-contrib-uglify

   