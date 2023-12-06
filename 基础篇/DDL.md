# DDL
## 数据库操作
#### 查询
1. 查询所有数据库   
>**SHOW DATABASES;**
![查询](image-3.png)
1. 查询当前数据库
>**SELECT DATABASE();**
>![查询当前数据库](image-9.png)
* 创建
> **CREATE DATABASE [IF NOT EXISTS]数据库的名称 [DEFAULT CHARSET字符集][COLLATE排序规则]；**
> ![创建以及创建完毕后的数据库](image-5.png)
> ![创建二](image-6.png)
* 删除
>**DROP DATABASE [IF EXIST]名称;**
![删除操作](image-7.png)
* 使用数据库
> **USE DATABASE 名称；**
> ![使用](image-8.png)


## 表操作
#### 创建
  > ![创建](image-10.png)
  > ---
  >![创建实例](image-11.png)
  >注意：
  >1. 最好全程用英文输入法打，好累啊打中英文切换
  >2. 字符类型是varchar()后面要加上大小
  >3. 最后一个字段后面不用加逗号，其他都要加，跟golang的结构体设定差不多
  >4. 注释要用单引号或者双引号来引导
  > ----
  
* 查询
> 1. 查询所有的表结构（前提是已经进入到某个数据库）
> **SHOW TABLES;**
> 2. 查询表结构（但是只是结构，具体数值不展示）
> **DESC 名称；**
> ![查询表结构](image-12.png)
> 3. 查询指定表的建表语句（详细结构信息）
> **SHOW CREATE TABLE IT_USER;**
> ![详细结构信息](image-13.png)
