# md-tech/laravel-permission
为laravel-permission添加按文件进行权限操作及回滚

## 安装及使用

1. 原版功能
   
   请查看 [原始文档](https://docs.spatie.be/laravel-permission/v2/introduction/) 进行基础安装和使用的介绍

2. 添加功能使用

   1. 按config中的 migration_path 设置，在对应文件夹中创建permission.log 文件，并在其中按格式写好权限
   2. 执行 permission:migrate 进行迁移
   3. 执行 permission:rollback 进行回滚