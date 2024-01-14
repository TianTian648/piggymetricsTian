## 数据层查询工具
CrudRepository是Spring Data JPA的一部分，可以自动生成查询语句，比如
```
Account findByName(String name);
```
但是这里的语句个人感觉直观性不如MyBatisPlus，所以要对工具做替换。
## RequestMapping替换成具体的查询方式 单纯看着难受

