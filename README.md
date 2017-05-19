# JS学习
## 总体目录
* JSDemo JS小程序
* JDMenu 京东无延迟菜单
## 知识点学习
### JDMenu 京东无延迟菜单
#### 1.开发普通二级菜单
* 事件代理方式进行绑定
* mouseenter和mouseover的区别：
* 使用mouseover/mouseout时候，如果鼠标移动到子元素上，即便没有离开父元素，也会触发父元素的mouseout事件；
* 使用mouseenter/mouseleave时，如果鼠标没有离开父元素，在其子元素上任意移动，也不会触发mouseleave事件；
#### 2.加入延迟优化
* 切换子菜单的时候，用setTimeout设置延迟
* debounce去抖o((⊙﹏⊙))o.技术：
* 在事件被频繁触发时买只执行一次
#### 3.基于用户行为预测的切换技术
* 跟踪鼠标的移动
* 用鼠标当前位置，和鼠标上一次位置与子菜单上下边缘形成的三角区域进行比较