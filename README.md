# lego-helper

一个帮助你提升开发效率的 VSCode 扩展，让你编码快如闪电！

## Features

这里涵盖了使用 Lego 开发时的大部分代码提示：

- Lego 公用组件模板
- 通用 pug 代码片段
- 常用 js 代码片段
- 挂载在 Vue 的全局方法、指令
- 公用 CSS 类名提示与补全

### Install

1. 下载最新版本 lego-helper.vsix 扩展包文件
2. 打开 VSCode 扩展管理面板
3. 选择：”···“ → ”从 VSIX 安装“
4. 选择扩展包文件，进行安装

### Snippets

💡不必刻意去记，当你需要它的时候，它就会出现。

#### Vue single file components snippets

| snippet       | purpose                    |
| ------------- | -------------------------- |
| `vinit`       | vue init(pug + less)       |
| `vhtml`       | vue html                   |
| `vpug`        | vue pug                    |
| `vjs`         | vue javascript             |
| `vjsall`      | vue javascript all options |
| `vcss`        | vue css                    |
| `vcssscoped`  | vue css scoped             |
| `vless`       | vue less                   |
| `vlessscoped` | vue less scoped            |
| `vsass`       | vue sass                   |
| `vsassscoped` | vue sass scoped            |

#### Common components template

| snippet               | purpose                       |
| --------------------- | ----------------------------- |
| `page-header`         | page-header component#1       |
| `page-header`         | page-header component#2       |
| `gt-table-pagination` | gt-table-pagination component |
| `gt-input`            | gt-input component            |
| `date-picker`         | date-picker component         |
| `upload-file`         | upload-file component         |
| `submit-btn`          | submit-btn component          |
| `icon`                | icon component                |
| `echarts`             | echarts component             |
| `baidu-map`           | baidu-map component           |

#### Pug template

| snippet               | purpose                     |
| --------------------- | --------------------------- |
| `.page-content`       | page-content template       |
| `.page-header`        | page-header template        |
| `.page-header__title` | page-header__title template |
| `.page-header__right` | page-header__right template |
| `el-select`           | el-select template          |
| `el-tooltip`          | el-tooltip template         |

#### Vue global directives

| snippet                 | purpose        |
| ----------------------- | -------------- |
| `v-acl`                 | auth directive |
| `v-copy`                | copy directive |
| `v-copy.dblclick`       | copy directive |
| `v-copy.icon`           | copy directive |
| `v-copy.icon=`          | copy directive |
| `v-copy:onSuccess.icon` | copy directive |

#### Vue global methods

| snippet                 | purpose                  |
| ----------------------- | ------------------------ |
| `$isPermitted`          | vm.$isPermitted          |
| `$loginInfo`            | vm.$loginInfo            |
| `$checkIdcardPrivilege` | vm.$checkIdcardPrivilege |
| `$goProfile`            | vm.$goProfile            |
| `$goReport`             | vm.$goReport             |
| `$config`               | vm.$config               |
| `$trackEvent`           | vm.$trackEvent           |
| `$trackSiteSearch`      | vm.$trackSiteSearch      |
| `$matomo`               | vm.$matomo               |

#### Script snippets

| snippet                               | purpose                                  |
| ------------------------------------- | ---------------------------------------- |
| `chunkimport`                         | arrow-func import                        |
| `genPostReq`                          | genPostReq                               |
| `onTableInit, onInitTable, initTable` | onTableInit                              |
| `tableOption`                         | tableOption                              |
| `columns`                             | tableOption.columns                      |
| `column`                              | tableOption column item                  |
| `access:`                             | tableOption.column.access                |
| `auth:`                               | tableOption.column.auth                  |
| `enums:`                              | tableOption.column.enums                 |
| `formatter:`                          | tableOption.column.formatter             |
| `show-overflow-tooltip`               | tableOption.column.show-overflow-tooltip |
| `actions`                             | tableOption.actions                      |
| `action`                              | tableOption action item                  |

#### Common css className

| snippet               | purpose                         |
| --------------------- | ------------------------------- |
| `.text-danger`        | color red                       |
| `.text-error`         | color red                       |
| `.color-danger`       | color red                       |
| `.color-error`        | color red                       |
| `.color-red`          | color red                       |
| `.text-success`       | color green                     |
| `.color-success`      | color green                     |
| `.color-green`        | color green                     |
| `.text-disable`       | color grey                      |
| `.color-disable`      | color grey                      |
| `.color-grey`         | color grey                      |
| `.text-blue`          | color primary                   |
| `.text-primary`       | color primary                   |
| `.color-primary`      | color primary                   |
| `.text-black`         | color black                     |
| `.text-warning`       | color orange                    |
| `.color-orange`       | color orange                    |
| `.multi-ellips-2`     | text overflow                   |
| `.multi-ellips-3`     | text overflow                   |
| `.multi-ellips-4`     | text overflow                   |
| `.multi-ellips-5`     | text overflow                   |
| `.ellipsis`           | text overflow                   |
| `.ft-12`              | font-size: 12px;                |
| `.ft-14`              | font-size: 14px;                |
| `.ft-16`              | font-size: 16px;                |
| `.ft-18`              | font-size: 18px;                |
| `.ft-20`              | font-size: 20px;                |
| `.ft-30`              | font-size: 30px;                |
| `.fr`                 | float: right;                   |
| `.fl`                 | float: left;                    |
| `.text-left`          | text-align: left;               |
| `.text-right`         | text-align: right;              |
| `.text-center`        | text-align: center;             |
| `.hidden`             | display: none;                  |
| `.fb`                 | display: flex;                  |
| `.fb-row`             | flex-direction: row;            |
| `.fb-row-rev`         | flex-direction: row-reverse;    |
| `.fb-col`             | flex-direction: column;         |
| `.fb-col-rev`         | flex-direction: column-reverse; |
| `.fb-nowrap`          | flex-wrap: nowrap;              |
| `.fb-wrap`            | flex-wrap: wrap;                |
| `.fb-wrap-rev`        | flex-wrap: wrap-reverse;        |
| `.fb-main-start`      | justify-content: flex-start;    |
| `.fb-main-center`     | justify-content: center;        |
| `.fb-main-end`        | justify-content: flex-end;      |
| `.fb-main-between`    | justify-content: space-between; |
| `.fb-main-around`     | justify-content: space-around;  |
| `.fb-cross-start`     | align-items: flex-start;        |
| `.fb-cross-center`    | align-items: center;            |
| `.fb-cross-end`       | align-items: flex-end;          |
| `.fb-cross-baseline`  | align-items: baseline;          |
| `.fb-cross-stretch`   | align-items: stretch;           |
| `.item-order-1`       | order: 1;                       |
| `.item-order-2`       | order: 2;                       |
| `.item-order-3`       | order: 3;                       |
| `.item-grow-1`        | flex-grow: 1;                   |
| `.item-grow-2`        | flex-grow: 2;                   |
| `.item-shrink-0`      | flex-shrink: 0;                 |
| `.item-basis-120`     | flex-basis: 120px;              |
| `.item-flex-1`        | flex: 1;                        |
| `.item-flex-2`        | flex: 2;                        |
| `.item-self-start`    | align-self: flex-start;         |
| `.item-self-center`   | align-self: center;             |
| `.item-self-end`      | align-self: flex-end;           |
| `.item-self-baseline` | align-self: baseline;           |
| `.item-self-stretch`  | align-self: stretch;            |

## Building

[http://192.168.8.218:10080/fanbj/lego-helper/blob/master/BUILD.md](http://192.168.8.218:10080/fanbj/lego-helper/blob/master/BUILD.md)

---

**Enjoy!**
