判断数据库是否存在
```
if exists (select * from sys.databases where name = '数据库名')  
```

判断表是否存在
```
if exists (select * from sysobjects where id = object_id(N'[表名]') and OBJECTPROPERTY(id, N'IsUserTable') = 1)  
```
