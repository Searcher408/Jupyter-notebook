# ReCaptcha
Verified code recognition based on CNN

- 问题说明：
主要提供5类验证码图片，难度依次递增，每一类验证码提供1万个训练样本，最后通过另外5000个测试样本的识别率评分。
 - 第1类：数字四则运算，有噪点干扰，输出计算结果；
 - 第2类：数字、英文，有噪点干扰，文字无旋转形变，输出数字、英文；
 - 第3类：数字、英文，有噪点干扰，文字有旋转形变，输出数字、英文；
 - 第4类：汉字，有噪点干扰，文字无旋转形变，输出汉字；
 - 第5类：汉字，有噪点干扰，文字有旋转形变，输出汉字。
- 用户期望：
对验证码图片中的数据、英文、汉字成功识别。
-任务要求：
通过对已标注好的数据样本进行机器学习训练，从而达到系统自动识别验证码的效果。
- 技术指标：
数据、英文、汉字的正确识别率。



