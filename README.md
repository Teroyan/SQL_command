# SQL_command
记录SQL中常用的命令
# SLQ常用命令：

#Ctrl+F 快速查找

##### SELECT  查

```sql
select  字段  
from  表
where  条件;	

查询的值不重复
select distinct  字段
from  表
where  条件;

条件：列 运算符 值
运算符： =	 等于
            <>	不等于
            >	大于
            <	小于
            >=	大于等于
            <=	小于等于
            BETWEEN	在某个范围内
            LIKE	搜索某种模式
```

##### INSERT  插入数据

```sql
INSERT INTO 表名 VALUES(值1,值2,值3,...)    #注意：字符类型需要用引号

INSERT INTO 表名 (列1,列2,列3,...) VALUES(值1,值2,值3,...)
```

##### 数据加密

```SQL
MD5('数据');

PASSWORD('数据');

ENCRYPT('数据');   #字段类型最好是CHAR BINARY
```

##### ALTER 修改字段类型

```
ALTER TABLE 表名 MODIFY COLUMN 类型;
```

##### ORDER BY排序

```
ORDER BY 列名 [DESC|ASC];         #默认按该列的字母或者数字升序排列;
										#DESC:逆字母顺序、ASC
ORDER BY 列名1,列名2;

```

