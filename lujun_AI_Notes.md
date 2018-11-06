# 2018.11.6
### Introduction
- why write this note ? <br> 
```
1. I want to find out where to start AI , ML, DS
2. The relationship btw them 
3. what are future development of those technologies.
```
### what is AI
- what is the robots <br>
1>`source` : 1920, 捷克作家，卡雷尔(Karel Čapek)，舞台剧《罗萨姆的万能机器人》(Rossum's Universal Robots)，robota(奴隶) -> robot. <br>
2>`Core` : 模仿人类的复杂性为，对条件反射的及时判断（不是封闭预存指令？ 我们的记忆不是封闭预存的吗，我们难道不是根据经验来处理问题吗？）
 机器人研发的关键是构造反射-> 如何观测感知外部世界的变化，并作出相应反馈
3>`Challenge`: 
 perception ： 感知环境 -> 量化物理世界 （sencer + deep learning -> 在复杂动态环境下，做规划和决策）<br>
 planning：分析推理 <br>
 control：运动控制 (如何建立动力学模型)，Moravec's paradox （playing chess VS one-year-old child: perception+mobility）  
 The question a robot should ask : where i am now !
 
- Key concept / 先驱
1> 形式推理 （formal reasoning）；AI 基本假设 -> 人的`思考过程` 可以`机械化`, the process of human thought can be `mechanized`.
```
1. Aristotle : formal analysis of syllogism
2. Euclid : model of formal reasoning 欧几里得
3.  al-Khwārizmī : algebra -> algorithm 花剌子密
4. Raymond Lulle: 逻辑机 （影响莱布尼茨）
5. 17 世纪， 莱布尼茨，霍布斯，笛卡尔 尝试， 理性的思科系统 -转换-> 代数学/几何学  
6. 20 世纪， 布尔（思维的定律），弗雷格（概念文字），罗素和怀特海（数学原理 1913），希尔伯特
7. 能否将所有数学推理形式化? -> 哥德尔不完备定理，图灵机，lambda 演算。
```
2> CS  
```
1. 查尔斯.巴贝奇 （第一台编程计算机）
2. 愛達·勒芙蕾絲
3. Z3, ENIAC, Colossus -> 图灵，约翰.冯.诺依曼
```

3> 控制论 神经网络 图灵测试 符号推理
```
1. 维纳 (控制论)
2. 香农（信息论）
3. Walter Pitts和 Warren McCulloch （理想化的人工神经元网络）
4. 马文.明斯基
5. 图灵（1950), 图灵测试
6. 50年代中期， 数字计算机-> 符号操作 （艾伦·纽厄尔，赫伯特·西蒙，J. C. Shaw），（John Searle 论其为强人工智能）
```

#### Referance
1.(CHAOS MUSEUM)  
2.Lijun's Github[https://github.com/junjy007/aifoundation/blob/master/AIFoundation.ipynb]  
3.Wiki  https://zh.wikipedia.org/wiki/%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E5%8F%B2
