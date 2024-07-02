# algebra
硬件技术团队编程基础作业
# 作者前言
本程序使用CLion编写，所用CMake版本为3.30，编译器为GCC x86_64-w64-mingw32(13.1.0)

不用VSCode是因为我菜，配置不来CMake，大概是跟settings.json中的include path有关，一直无法成功运行，而CLion的自动配置解决了这一点。望周知。
## 本项目由高性能机器人ATRI赞助。
![萝卜子最可爱啦！！！！](https://github.com/DearATRI/LiuShuchang_hw1/blob/main/origin_202203071827293004.jpg)
# 各分块代码实现及运行截图
1. 矩阵相加   
加就完事了。  
![矩阵相加](https://github.com/DearATRI/LiuShuchang_hw1/blob/main/Screenshot%202024-07-02%20172823.png)
2. 矩阵相减  
减就完事了。  
![矩阵相减](https://github.com/DearATRI/LiuShuchang_hw1/blob/main/Screenshot%202024-07-02%20173418.png)
3. 矩阵乘法  
利用三重循环套数学公式即可。  
![矩阵相乘](https://github.com/DearATRI/LiuShuchang_hw1/blob/main/Screenshot%202024-07-02%20174950.png)
4. 矩阵数乘  
直接每个元素乘上相应倍数即可
![矩阵数乘](https://github.com/DearATRI/LiuShuchang_hw1/blob/main/Screenshot%202024-07-02%20175846.png)
5. 矩阵转置  
创建一个行列数与所给矩阵相反的新矩阵，逆转(i，j)参数接收所给矩阵的元素即可。  
![矩阵转置](https://github.com/DearATRI/LiuShuchang_hw1/blob/main/Screenshot%202024-07-02%20175955.png)
6. 行列式求值  
使用余子式展开求值的数学方法  
创建两个函数，第一个函数DET为计算的主要部分，第二个函数Minor专门用于计算余子式的值，而第二个函数中会调用第一个函数.如此形成递归  
![行列式求值](https://github.com/DearATRI/LiuShuchang_hw1/blob/main/Screenshot%202024-07-02%20180112.png)
7. 矩阵求逆  
未实现（菜）
8. 矩阵求秩  
未实现（菜）
9. 矩阵求迹  
直接对角线元素相加即可  
![矩阵求迹](https://github.com/DearATRI/LiuShuchang_hw1/blob/main/Screenshot%202024-07-02%20180155.png)
# 后记
这次课程收获颇丰，教了非常多实用的内容，也激发了我自学的动力。感谢组织者和讲授者们！
