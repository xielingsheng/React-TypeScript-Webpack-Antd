# React-TypeScript-Webpack-Antd

一个 React+TypeScript+Webpack+Antd 的模板

# 如何使用

克隆仓库：`git clone git@github.com:JianpengHe/React-TypeScript-Webpack-Antd.git`
切换目录：`cd React-TypeScript-Webpack-Antd`
安装依赖：`yarn`

开发环境：`yarn dev`
生产编译：`yarn build`

# 依赖及其版本

不解释了，看不懂可以跳过
`npm i --save cross-env@7.0.3 react@17.0.2 react-dom@17.0.2 typescript@4.2.4 antd`
`npm i --save-dev tslint tslint-react tslint-config-prettier webpack@5.28.0 webpack-cli@3.3.12 webpack-dev-server@3.11.2 webpack-merge@5.7.3 html-webpack-plugin@5.3.1 @types/webpack-env@1.16.0 webpackbar@5.0.0-3 style-loader@2.0.0 css-loader@5.2.4 mini-css-extract-plugin@1.4.0 postcss-loader@5.2.0 postcss-preset-env@6.7.0 less@4.1.1 less-loader@8.1.1 node-sass@5.0.0 sass-loader@11.0.1 css-minimizer-webpack-plugin@2.0.0 babel-loader@8.2.2 @babel/core@7.13.16 @babel/preset-env@7.13.15 @babel/plugin-transform-runtime@7.13.15 @babel/runtime-corejs3@7.13.17 @types/react@17.0.3 @types/react-dom@17.0.3 @babel/preset-react@7.13.13 @babel/preset-typescript@7.13.0 copy-webpack-plugin@8.1.1 clean-webpack-plugin@4.0.0-alpha.0`

# 环境和参数

dev: `cross-env NODE_ENV=development webpack-dev-server --config ./scripts/config/webpack.dev.js`
build: `cross-env NODE_ENV=production webpack --config ./scripts/config/webpack.prod.js`
