# V1.4.2_10更新日志
1、bean模式可指定更新字段
2、用户配置>注解>D全局设置

# V1.4.1_8更新日志
 1、增加class或bean自动获取表名、字段、数据和名称、主键、是否自增注解功能
 
 2、表名、主键和自增可通过table、pk、autoInc函数动态设置，函数设置优先级>注解配置
 
 3、增加setInc、setDec函数用于数据库字段自增或自减
 
 4、增加asc、desc排序函数
 
 5、添加fetchSql=true调试模式中输出占位参数功能
 
 6、拆分field()函数为field()和data()，前者参数为","拼接的字段名字符串，后者参数为数据
