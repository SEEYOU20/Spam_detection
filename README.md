# Spam_detection
Spam_detection朴素贝叶斯垃圾邮件检测
使用朴素贝叶斯实现了对中文邮件进行检测的垃圾邮件检测算法
使用中文分词、文本预处理、停用词过滤、10折交叉验证机制等比较了不同λ值的贝叶斯估计对算法性能带来的影响
SS:测试样例中spam被判断为spam的数量
SH:测试样例中spam被判断为ham的数量
HS:测试样例中ham被判断为spam的数量
HH:测试样例中ham被判断为ham的数量
Recall=SS/(SS+SH)*100%   
Precision=SS/(SS+HS)*100% 
F1=2*SS/(2*SS+HS+SH)
