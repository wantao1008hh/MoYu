#魔域
### 初步实现了定点来回走动挂机

#### 1. 循环领取火线任务（叹息骑士），主要目的就是为了128级升级，解放双手
#### 2. 支持死亡复活
#### 3. 支持防外挂答题检测，播报警告
#### 4. 支持需要捡起的宝宝，其他宝宝扔掉
#### 5. 使用yolov5训练了验证码数据集 数据集使用不同字体生成，并添加噪点，数据较少，可以粗略识别答题

### 截取
![](./result/验证码1.png)  ![](./result/验证码2.jpg)
 
![](./result/result_验证码1.png)  ![](./result/result_验证码2.jpg)

#### 耗时：0.01562356948852539
#### 识别结果：[('7', '0.72', (22, 22, 26, 36)), ('-', '0.77', (73, 45, 22, 16)), ('4', '0.84', (129, 24, 24, 34))]
