# vue-page-creator
> vue模板页面生成器 自用

#### 设计后台数据 必须符合解析规则,请按以下原则设计数据

```json
//一级路由  name，component不能使用-或_ 
"path": "/after_sale",  path 两个单词或以上用_连接
"name": "aftersale",     name 不能使用-或_
"component": "/aftersale", component 不能使用-或_
"title": "售后",
"icon": "el-icon-shopping-cart-1",

// 二级路由
"children": [
   {
       "detail_title": "售后",
       "submenu": [
           {
               "submenu_title": "所有售后",
               "path": "/all_after_sale",  path 两个单词或以上用_连接
               "component": "/aftersale/all-after-sale" 前一个路径 (/aftersale) 必须与一级路由的name一致 且两个单词或以上用-连接注意是-不是_
           },
           {
               "submenu_title": "退款申请",
               "path": "/drawback_apply",
               "component": "/aftersale/drawback-apply"
           },
           {
               "submenu_title": "退货申请",
               "path": "/refund_apply",
               "component": "/aftersale/refund-apply"
           }
       ]
   }]
```

#### 使用方法

##### ```注意：先cd到server文件夹下，再操作以下命令```

```shell
json-server --w .\menu.json     # 启动服务器
```

```shell
 node .\createVuePage.js    # 生成页面
```
