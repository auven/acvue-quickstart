# {{ name }}

> {{ description }}

## 开发步骤

``` bash
# 安装依赖
npm install

# 开启服务器，默认 localhost:8080 ，实时监听文件改变，热更新
# 开发网页
npm run dev
# 开发 APICloud app
npm run dev@app

# 打包网页生辰环境代码
npm run build
# 打包 APICloud app 生产环境代码
npm run build@app

# build for production and view the bundle analyzer report
npm run build --report
{{#unit}}

# run unit tests
npm run unit
{{/unit}}
{{#e2e}}

# run e2e tests
npm run e2e
{{/e2e}}
{{#if_or unit e2e}}

# run all tests
npm test
{{/if_or}}
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
