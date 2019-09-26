### 介绍
用于转换日期到字符串

### GIT
	http://gitlab.nb01.net/fe/common-modules/simple-date-format.git
### 引入及使用
#### 1.安装
    npm install --save simple-date-format
#### 2.引入
    import format from 'simple-date-format'
    or
    const format = require('simple-date-format')
#### 3. 使用
    // 只支持到 年 月 日 时 分 秒字段的转换
    let dateStr = format(new Date(), 'yyyy-MM-dd HH:mm:ss')
#### 4. 说明  
    yy      年份后两位
    yyyy    四位年份
    MM      月份
    dd      日期
    HH      小时24制
    hh      小时12制
    mm      分钟
    ss      秒
