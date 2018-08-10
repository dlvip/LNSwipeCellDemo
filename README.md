# LNSwipeCell
一套友好的、方便集成的针对cell的左滑编辑功能！
实现一个和微信功能一样的左滑编辑页面。

# Interduce 【简单介绍】
- 按照苹果官方的MVC的设计模式封装的Cell控件，类似UITableView的实现方式
- LNSwipeCell的编辑功能的数据由*LNSwipeCellDataSource*提供
- LNSwipeCell的编辑功能的事件由*LNSwipeCellDelete*提供
- UIView+Extension类是为了一步到位的访问和修改UIView子类的Frame相关属性

# Features【能做什么】
 - [x] 实现左滑显示，标为已读、删除 按钮
 - [x] 触摸到已经打开的cell的contentView，关闭cell
 - [x] 触模到其他cell，关闭已经打开的cell
 - [x] 滑动tableView，关闭已经打开的cell
 - [ ] 点击删除按钮，变化为确认删除按钮

# Class【使用到的类】
1. LNSwipeCell   -- 封装了左滑编辑的cell
2. LNSwipeModel  -- 支持cell编辑的数据
3. UIView+Extension -- 快速访问和修改UIView的Frame相关属性

# Getting Started【开始使用】

## 文字介绍
- 把三个类拖进工程中
- 让你的cell继承LNSwipeCell，因为lNSwipeCell只封装了左滑编辑的逻辑和实现，因此你要根据需求自己绘制cell的UI
- 把之前加载到cell的contentView上的视图，都加载到cell的ln_contentView上


## 代码介绍
详细使用请看代码



