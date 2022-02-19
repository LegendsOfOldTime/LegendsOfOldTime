# 开发记录


## 语法

### 语法

#### 条件语句
````perl
IF = {
    limit = {
    }
}
ELSE_IF = {
    limit = {
    }
}
ELSE = {
}
````
### 解析执行顺序

`save_as_scope`这个语法如果是在`opinion`里执行，那么在`flavor`中是取不到的，
猜想是因为`flavor`和`save_as_scope`是一起执行 

###