# readyState

字典值 | 状态 | 含义
-- | -- | --
0 | UNSENT | 代理被创建，但尚未调用open()方法。
1 | OPENED | open()方法已经被调用。
2 | HEADERSRECEIVED | send()方法已经被调用并且头部和状态已经可获得。
3 | LOADING | 下载中;responseText 属性已经包含部分数据。
4 | DONE | 下载操作已完成。
