# learnSQL     

主要学习界面	：https://www.liaoxuefeng.com/wiki/1177760294764384/1218728442198976   

SQL_1-->SQL_3	: SQL的基本介绍和安装。    
SQL_4		: SQL表的主键、外键、索引。    
SQL_5		: init-test-data.sql是从本次学习媒介对象的gitHub上clone下来的，学习用。  
SQL_6		: 基本查询。  
SQL_7		：条件查询WHERE <条件表达式>。  
SQL_8		：投影查询。  
SQL_9		：排序ORDER BY。  
SQL_10		：分页查询LIMIT <M> OFFSET <N>。  
SQL_11		: 聚合查询COUNT(*)，SUM()、AVG()、MAX()，MIN()。  
SQL_12		: 多表查询。  
SQL_13		: 连接查询LEFT/RIGHT/FULL OUTER JOIN。    
SQL_14		: 修改数据INSERT  
SQL_15		: 修改数据UPDATE  
SQL_16		: 修改数据DELETE  
SQL_17		: 管理SQL，数据库/表。  
SQL_18		：实用SQL语句【插入OR替换，插入OR更新，插入OR忽略，快照，写入查询结果集】。   
SQL_19		：事务。  

dev_mysql_com_Tutorialdocu.docx	：MySQL官网下当前8.0版本的教程第三章，暂时把基本操作学完了，第三章从第一节，记录到，第四节，由我自己的账户实时操作，已经全部验证正确。3.5以后的还没有看。pet.txt和event.txt文件都是该学习记录的衍生文件。  

Note ：.md文件需要按下两个空格后再换行，不然github上，没有显示正确换行。  
Note : SQL_5以后的内容，是总结性的，不知道问题出在哪的时候可以先找SQL_X，具体的问题可以查找dev_mysql_com_Tutorialdocu.docx或者搜索该教程的网站，有索引点击更方便。  


-----------------ERROR--------------------  
$ git push origin_github master
Connection reset by 13.250.177.223 port 22
fatal: Could not read from remote repository.  
  
Please make sure you have he correct access rights and the repository exists.  
解决办法：  
网上找了很多，都没有解决。应该是github用https而不是http的缘故，语句换一换解决了。  
本来是：  
git remote add origin git@github.com:IamWWT/learnSQL.git  
换成:  
git remote add origin https://github.com/IamWWT/learnSQL.git  
