# hexo-widget-tree

[中文文档](./README.zh.md)

[Demo](https://www.yunyoujun.cn/yun/hexo-widget-tree.html)

Hexo 文章树状菜单预览插件

（如果你的主题支持 PJAX，那么它也可以实现无刷新浏览。）

## 使用

```sh
npm install hexo-widget-tree
# yarn add hexo-widget-tree
```

点击页面左侧中间的按钮，展开树状菜单。

点击带有加号的文件夹图标以展开子项，点击文件夹名则会直接跳转到分类页，

## 配置

- `cdn`: true, 默认使用 [jsdelivr CDN](https://cdn.jsdelivr.net/npm/hexo-widget-tree).
- `hide`: false, 自动隐藏按钮（将鼠标放置于页面左边中间即可浮现触发按钮）
- `layout`: 你想要插入的页面所属的布局类型。 更多信息见 [注入器（Injector） | hexo](https://hexo.io/zh-cn/api/injector.html#to-lt-string-gt)。

```yaml
widget_tree:
  cdn: false
  hide: false
  # layout:
  #   - home
  #   - page
```
