---
title: 更新日志
---
## v1.3.8, 2019-06-26  
- `A` 新的SDK加载逻辑
- `F` 修复`字体样式`/`待办事项`渲染问题 [#175](https://github.com/xCss/Valine/issues/175) [#182](https://github.com/xCss/Valine/issues/182) 
- `F` 修复各节点无法访问的Bug [#188](https://github.com/xCss/Valine/issues/188) [#189](https://github.com/xCss/Valine/issues/189) [#190](https://github.com/xCss/Valine/issues/190) 
- `F` 其他 Bug 修复

## v1.3.7, 2019-06-21  
- `A` 新增`clazzName`字段，自定义配置LeanCloud表名 [#162](https://github.com/xCss/Valine/issues/162)
- `F` **修复LeanCloud服务不可访问问题**
- `F` 修复待办事项列表渲染`Bug` [#182](https://github.com/xCss/Valine/issues/182)
- `F` 尝试性修复字体大小问题 [#175](https://github.com/xCss/Valine/issues/175)
## v1.3.6, 2019-04-01
- `F` 修复代码高亮失效的 `Bug`
- `F` 修复以前可以使用`Pjax`而`v1.3.5`版本失效的 `Bug` (感谢小伙伴 [@sxyugao](https://github.com/sxyugao) 提供的建议)
- `F` 修复评论内容中点击 `@NickName` 跳转到新页面的 `Bug`
- `F` 其他 `Bug` 修复

## v1.3.5, 2019-03-29
- `A` 新增隐私保护：移除页面中的敏感(E-mail)数据 
- `A` 新增`recordIP` 属性(`Boolean`)：增加IP统计 by [@Showfom](https://github.com/Showfom) [#160](https://github.com/xCss/Valine/issues/160) 
- `U` 一些样式修改
- `U` 代码逻辑优化

## v1.3.4, 2018-11-24
- `F` 修复`img`的`xss`安全漏洞
- `F` 修复`embed`的`xss`安全漏洞
- `F` 修复评论框内容不重置的bug

## v1.3.3, 2018-09-26

- `F` 修复可以自定义`CSS`的 Bug

## v1.3.1, 2018-09-03

- `A` 新增 `avatarForce` 字段，每次访问强制拉取最新的`评论列表头像`
- `F` 修复提交评论后，评论框不重置的 Bug

## v1.3.0, 2018-07-29

- `A` 新增 `pid` 字段
- `A` 新增`at`锚点定位
- `U` 过滤掉 `iframe` 等HTML元素
- `F` BUG 修复


---------------------

更多[更新日志 >](https://github.com/xCss/Valine/releases)

---------------------