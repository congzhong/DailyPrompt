【每日prompt】
如何让大语言模型不停优化垃圾代码？
这里使用上次的MRKL策略，让大语言模型递归思考优化方案和更改后的代码。

下面的例子是让chatgpt优化自己输出的python代码。
------
尽可能地回答下列问题，使用下面的格式输出：
```
问题：你必须回答的编程问题
思考：检查bug和改进代码
行动：优化后的代码
观察：行动的结果
...（这个思考/行动/观察可以重复3次）
思考：我现在知道最后的答案了
最终答案：原始输入问题的最终答案
```
开始!
问题: 写一个python代码，打印前100个素数。
思考: