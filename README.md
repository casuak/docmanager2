# Document-Management-System

文献管理系统

## 目录

* [0 常用信息](#0-常用信息)
* [1 登陆页](#1-登陆页)
* [2 系统功能](#2-系统功能)
  * [2-1 用户管理](#2-1-用户管理)
  * [2-2 角色管理](#2-2-角色管理)
  * [2-3 功能管理](#2-3-功能管理)
  * [2-4 字典管理](#2-4-字典管理)
    * [2-4-1 字典类型管理](#2-4-1-字典类型管理)

## 0 常用信息

1. 所有实体
  1-1 
2. 所有实体之间的关联

## 1 登陆页

1. 页面构成  
用户名输入框（自动记录上次登陆使用的用户名）  
密码输入框  
记住密码勾选框  

2. 管理员（拥有系统所有权限）  
用户名：admin  
密码：admin

## 2 系统功能

包含了维持系统运作的基础功能

### 2-1 用户管理

1. 管理使用本系统的所有用户，用户和角色（多对多）关联，和功能（多对多）通过角色间接关联
2. 基本操作  
  2.1 增
  2.2 删
  2.3 改
  2.4 查

### 2-2 角色管理

1. 管理使用本系统的所有角色，角色和用户（多对多）、功能（多对多）关联
2. 基本操作  
  2.1 增
  2.2 删
  2.3 改
  2.4 查

### 2-3 功能管理

1. 管理本系统所有显示在左边导航列表的功能，功能和角色（多对多）关联，和用户（多对多）通过角色间接关联
2. 基本操作  
  2.1 增
  2.2 删
  2.3 改
  2.4 查
3. 功能分二级，第一级为功能分类，不指向具体页面；第二级为功能，指向具体页面

### 2-4 字典管理

1. 管理本系统中所有的字典项，字典项与字典类型、父字典项、其他表中字典项（一对多）关联  
字典项的作用是规范国家、省份之类的字段值，当需要修改字典项的值时，无需修改所有用到该字典项的记录，只需修改字典项的值即可  
2. 基本操作  
  2.1 增
  2.2 删
  2.3 改
  2.4 查

#### 2-4-1 字典类型管理

1. 管理所有字典类型
2. 基本操作  
  2.1 增
  2.2 删
  2.3 改
  2.4 查
