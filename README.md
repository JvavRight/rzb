hfb 是第三方平台, 用来托管资金, 单独启动该项目就行(数据库得建表);
rzb_min 是后端,rzb_min使用到了spring cloud,得使用nacos(没有上传nacos);
rzb_min 涉及到了阿里云的云存储, 想要正常使用该项目得去阿里云的oss开通一下云存储,把rzb_oss部分的application.yml文件进行更改;
注意: 记得修改application.yml的部分代码, 比如数据库,redis,rabbitMQ等等;
rzb_admin 是后台前端页面,用来后台管理审核;
rzb_site 是用户前端页面,用来给用户操作;

