# SpaceInvaders-Atari2600
Based on other people's code
## 注意事项
1. tensorflow使用1.13版本
2. 若训练过程中因内存不够引起代码中止，请减小内存池的大小
3. 若训练过程中因内存不够引起代码中止，也可以改进算法。改进思路：将连续的单帧图片压入经验池，每次随机选取到一个样本时再向前连续索取三帧样本
