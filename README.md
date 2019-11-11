# commanderadmin
电商模板，只有静态页面
> A Vue.js project
预览步骤
1.下载项目
2.npm install
3.npm start

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

#### 基础组件库用了vant 采用按需导入方式加载

## src 文件描述
```javascript
/* -----components----- */
tpl.vue ==>> 模板文件，
dateTiemPicker ==>> 时间选择器，


/* -----page----- */
Login ==>> 登录页
home ==>> 主页
myAccount ==>> 我的账号
assetDetails ==>> 资产明细
fullStatus ==>> 整体状况
areaOrder ==>> 小区订单
orderExpress ==>> 订单配送
    confirmDelivery ==>> 以确认送达
clientGetCargo ==>> 顾客提货
myBuyOrder ==>> 我的购买订单
discountCoupon ==>> 优惠劵
myAgreement ==>> 我的协议
```

## 目录结构

项目完结 加
自动生成目录结构教程（https://juejin.im/post/5dc1340e6fb9a04abf552b40）

|-- commanderAdminStatic
    |-- .babelrc
    |-- .editorconfig
    |-- .eslintignore
    |-- .eslintrc.js
    |-- .gitignore
    |-- .postcssrc.js
    |-- directoryList.md
    |-- index.html
    |-- package-lock.json
    |-- package.json
    |-- README.md
    |-- yarn-error.log
    |-- build
    |   |-- build.js
    |   |-- check-versions.js
    |   |-- logo.png
    |   |-- utils.js
    |   |-- vue-loader.conf.js
    |   |-- webpack.base.conf.js
    |   |-- webpack.dev.conf.js
    |   |-- webpack.prod.conf.js
    |-- config
    |   |-- dev.env.js
    |   |-- index.js
    |   |-- prod.env.js
    |   |-- test.env.js
    |-- src
    |   |-- App.vue
    |   |-- main.js
    |   |-- assets
    |   |   |-- bg_discountCoupon.png
    |   |   |-- bg_discountCoupon_disable.png
    |   |   |-- bg_no_order.png
    |   |   |-- header_bg.png
    |   |   |-- home_user_rights_1.png
    |   |   |-- home_user_rights_2.png
    |   |   |-- home_user_rights_3.png
    |   |   |-- icon_arrow_bottom_black.png
    |   |   |-- icon_arrow_orange.png
    |   |   |-- icon_arrow_right_black.png
    |   |   |-- icon_home_1.png
    |   |   |-- icon_home_2.png
    |   |   |-- icon_home_3.png
    |   |   |-- icon_home_4.png
    |   |   |-- icon_home_5.png
    |   |   |-- icon_home_header_lable.png
    |   |   |-- icon_mini_success.png
    |   |   |-- icon_reat_success.png
    |   |   |-- icon_time.png
    |   |   |-- icon_todo_list.png
    |   |   |-- icon_VIP.png
    |   |   |-- login_main.png
    |   |   |-- my_agreement.png
    |   |-- components
    |   |   |-- tpl.vue
    |   |   |-- dateTiemPicker
    |   |       |-- dateTiemPicker.vue
    |   |-- page
    |   |   |-- areaOrder
    |   |   |   |-- areaOrder.vue
    |   |   |-- assetDetails
    |   |   |   |-- assetDetails.vue
    |   |   |-- clientGetCargo
    |   |   |   |-- clientGetCargo.vue
    |   |   |-- discountCoupon
    |   |   |   |-- discountCoupon.vue
    |   |   |-- fullStatus
    |   |   |   |-- fullStatus.vue
    |   |   |-- home
    |   |   |   |-- home.vue
    |   |   |-- Login
    |   |   |   |-- Login.vue
    |   |   |-- myAccount
    |   |   |   |-- myAccount.vue
    |   |   |-- myAgreement
    |   |   |   |-- myAgreement.vue
    |   |   |-- myBuyOrder
    |   |   |   |-- myBuyOrder.vue
    |   |   |-- orderExpress
    |   |       |-- orderExpress.vue
    |   |       |-- confirmDelivery
    |   |           |-- confirmDelivery.vue
    |   |-- router
    |       |-- index.js
    |-- static
    |   |-- .gitkeep
    |   |-- init.css
    |   |-- public.css
    |-- test
        |-- e2e
        |   |-- nightwatch.conf.js
        |   |-- runner.js
        |   |-- custom-assertions
        |   |   |-- elementCount.js
        |   |-- specs
        |       |-- test.js
        |-- unit
            |-- .eslintrc
            |-- jest.conf.js
            |-- setup.js
            |-- specs
                |-- HelloWorld.spec.js

