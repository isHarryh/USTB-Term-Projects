第一次作业

## 人机交互与感知

**问：人机交互过程中人们经常利用的感知有哪几种？每种感知有什么特点?**

答：人们经常利用的感知包括视觉、听觉和触觉，各自的特点如下：

1. **视觉**：
   - 体量最大：人的视觉是人感知周围环境、获取环境信息的主要方式。
   - 范围最广：在合适的条件下，视觉信息可以在空间内传播相当远的距离。
   - 不完全性：基于视觉系统的生理结构，人可能无法看到某些事物，但是人可以对不完全的信息发挥一定的想象力。
   - 经验误差：人可能在运用视觉的过程中基于经验和参照物产生视错觉。
2. **听觉**：
   - 灵敏：人对声音，尤其是音高的变化相当敏感。
   - 易干扰：环境噪声可能影响听觉信息的准确传播。
   - 体量较大：人的听觉所带来的信息仅次于视觉。
   - 范围适中：声音经过一定距离后便会产生衰减。
3. **触觉**：
   - 非局部性：人的全身都有触觉，只是不同部位的敏感度不同，具有视觉等缺陷的残疾人主要通过触觉来感知环境。
   - 范围最窄：触觉的空间作用范围最窄，隐私性相对较好。

-----

**问：颜色模型有哪几种？试说明RGB、CMYK以及HSV颜色模型各适于在什么情况下应用？**

答：常见的颜色模型包括RGB、CMYK和HSV，各自的应用场景如下：

1. **RGB** (Red, Green, Blue)：
   - 红-绿蓝-三原色模型**适用于现代显示设备**，应用最广泛。显示器中每一个像素点的颜色都是由红绿蓝三种颜色的不同比例混合而成的。
2. **HSV** (Hue, Saturation, Value)：
   - 色相-饱和度-亮度颜色模型比较**贴合人眼的视觉感知**，易于被人使用。色相是颜色在圆形色相环中所处的角度（`0°`为红色），饱和度指示颜色的鲜艳程度。亮度也译作brightness，因此该颜色系统又名HSB。
   - 补充：HSL颜色模型也是常用的颜色模型，它类似于HSV颜色系统，L指的是light，即白光的分量。但它除了色相的概念和HSV一致，其他指标的计算都和HSV略有不同。
3. **CMYK** (Cyan, Magenta, Yellow, blacK)：
   - 青-品红-黄-黑色颜色模型是基于物理上的光吸收-反射原理制定的，**适合用于打印机等需要补色的情景**。不难发现，`青色=白色-红色`，`品红=白色-绿色`，`黄色=白色-蓝色`。

> 除了上面提到的颜色系统外，还有很多颜色系统被应用于不同的场景中。例如YUV颜色系统使用一个亮度信号Y以及两个色差信号U和V的颜色定义，主要应用于电视行业中。黑白电视机只接收亮度信号Y，彩色电视机需要同时接收亮度信号Y以及色差信号U和V。

-----

**问：人的认知过程分为哪几类？**

答：可有如下过程：

1. 感知（Recognition）：通过生理感知系统接受到外界信息。
2. 注意（Attention）：大脑关注到接收到的外界信息。
3. 记忆（Memorization）：大脑对信息产生记忆。
4. 学习（Learning）：大脑对信息进行加工并与其他记忆产生联系。
5. 听说读写（HSVW）：认知信息的主要输入/输出渠道。
6. 推理（Inference）：人对事物进行规划、思考和分析。
7. 决策（Decision）：人对事物做出反应。