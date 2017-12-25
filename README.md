# example
前端笔记及案例
---------------------------------------
### 高度坍塌：
  #### 触发条件：
    当一个元素，它的子元素为非正常文档流内的元素时，该元素不会被这样的子元素高度所撑开。

  #### 解决办法：
     1.在坍塌元素之前，添加一个空的块级元素，并为其设置clear:both属性
     2.为父级元素设置overflow:hidden属性
