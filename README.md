# 声波通信
Send and receive data by sound wave
- 使用声波发送和接收数据
- 使用Base64进行数据编码，支持任意字符和二进制文件。
- 使用FFT（快速傅里叶变换）获取声音频率。（之前网上找的例子没有注释，一顿懵逼）
- 之前版本通过统计波形个数来计算频率，方法比较笨，而且有噪音就不能用了。
- 声音频率波段划分问题，划分太少能够编码的信息少，划分太多容易被干扰，噪音环境下出错率变高。
- 待优化改进……

## FFT
- 任何连续周期信号都可以由一组适当的正弦曲线组合而成。
