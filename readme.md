## 任务十三：零基础JavaScript编码（一）

- 面向人群：

  零基础或初学者

- 难度：

  简单





### 重要说明

百度前端技术学院的课程任务是由百度前端工程师专为对前端不同掌握程度的同学设计。我们尽力保证课程内容的质量以及学习难度的合理性，但即使如此，真正决定课程效果的，还是你的每一次思考和实践。

课程多数题目的解决方案都不是唯一的，这和我们在实际工作中的情况也是一致的。因此，我们的要求不仅仅是实现设计稿的效果，更是要多去思考不同的解决方案，评估不同方案的优劣，然后使用在该场景下最优雅的方式去实现。那些最终没有被我们采纳的方案，同样也可以帮助我们学到很多知识。所以，我们列出的参考资料未必是实现需求所必须的。有的时候，实现题目的要求很简单，甚至参考资料里就有，但是背后的思考和亲手去实践却是任务最关键的一部分。在学习这些资料时，要多思考，多提问，多质疑。相信通过和小伙伴们的交流，能让你的学习事半功倍。



### 任务目的

- JavaScript初体验
- 初步明白JavaScript的简单基本语法，如变量、函数
- 初步了解JavaScript的事件是什么
- 初步了解JavaScript中的DOM是什么





### 任务描述

- 参考以下示例代码，补充其中的JavaScript功能，完成一个JavaScript代码的编写
- 本任务完成的功能为：用户可以在输入框中输入任何内容，点击“确认填写”按钮后，用户输入的内容会显示在“您输入的值是”文字的右边

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>IFE JavaScript Task 01</title>
  </head>
<body>

  <label>请输入北京今天空气质量：<input id="aqi-input" type="text"></label>
  <button id="button">确认填写</button>

  <div>您输入的值是：<span id="aqi-display">尚无录入</span></div>

<script type="text/javascript">

(function() {
  /*	
  在注释下方写下代码
  给按钮button绑定一个点击事件
  在事件处理函数中
  获取aqi-input输入的值，并显示在aqi-display中
  */

})();

</script>
</body>
</html>

```





### 任务注意事项

- 实现简单功能的同时，请仔细学习JavaScript基本语法、事件、DOM相关的知识
- 请注意代码风格的整齐、优雅
- 代码中含有必要的注释
- 可以不考虑输入的合法性
- 建议不使用任何第三方库、框架
- 示例代码仅为示例，可以直接使用，也可以完全自己重写







### 任务协作建议

- 团队集中讨论，明确题目要求，保证队伍各自对题目要求认知一致
- 各自完成任务实践
- 交叉互相Review其他人的代码，建议每个人至少看一个同组队友的代码
- 相互讨论，最后合成一份组内最佳代码进行提交





### 在线学习参考资料

- [JavaScript入门篇](http://www.imooc.com/view/36)
- [MDN JavaScript](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript)

