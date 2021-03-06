---
category: components
chinese: 面包屑
type: Views
english: Breadcrumb
---

显示当前页面在系统层级结构中的位置，并能向上返回。

## 何时使用

- 当系统拥有超过两级以上的层级结构时；
- 当需要告知用户『你在哪里』时；
- 当需要向上导航的功能时。

## API

| 参数      | 说明                              | 类型              |  可选值 | 默认值 |
|-----------|-----------------------------------|-----------------|---------|--------|
| routes    | router 的路由栈信息               | Array             |         | -      |
| params    | 路由的参数                        | Object            |         | -      |
| separator | 分隔符自定义                      | String or Element |         | '>'    |
| title     | 标题                             | String            |         | ''     |  
| itemRender | 自定义链接函数，和 react-router 配置使用 | (route, params, routes, paths) => React.ReactNode | | - |

