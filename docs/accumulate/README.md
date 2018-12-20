---
title: SIP_VueTS文档
sidebar: auto
sidebarDepth: 2
---

# SIP_VueTS 文档

::: tip 提示
简介

:::

## 一、概述

本项目由 Vue2.X + Typescript2.7 基于[mVue](http://dev.bingocc.com/mvue/)改造的框架。

此框架用于品高云自助服务平台的重构，此文档基于该产品编写。适用于 SIP 团队的开发人员进行开发工作。

## 二、环境

前端开发环境：

- [Node.js](https://nodejs.org/en/) 和 npm
- [项目地址](https://github.com/winpzs/vue-test)

###

    git clone https://github.com/winpzs/vue-test

工程结构
 
###

    SIP+VueTS
    ├─── .vscode    vscode自定义设置
    ├─── build      webpack配置目录
    │    ├── webpack.base.conf.js
    │    ├── webpack.dev.conf.js
    │    └── webpack.prod.conf.js
    ├─── config     编译相关配置项
    ├─── nginx      nginx配置
    ├─── node_modules 包目录
    ├─── src          主目录
    │   ├── libs      系统内置工具类
    │   │    ├── sip    
    │   │    ├── config_helper.js
    │   │    ├── context.js
    │   │    ├── global_components.js
    │   │    ├── index_base.js
    │   │    ├── index_component_init.js      
    │   │    ├── lodash_loader.js             [JS实用工具库](https://www.lodashjs.com/) 
    │   │    └── zepto.js
    │   ├── modules    
    │   ├── pages
    │   ├── router
    │   ├── services
    │   ├── store
    │   ├── app.vue
    │   ├── main.js         
    │   └── vue-shims.d.ts
    ├─── static
    ├─── test
    ├─── .babelrc
    ├─── .editorconfig
    ├─── .gitignore
    ├─── .Dockerfile
    ├─── index.html
    ├─── package-lock.json
    ├─── package.json
    ├─── README.md
    ├─── README.md
    ├─── tsconfig.json
    ├─── typings.json
    │   ├── README.md
    │   └── .vuepress
    │       ├── public
    │       └── config.js
    └── vue-sip-helper.config.json

崔浩 | Front End Engineer | 2018.12
