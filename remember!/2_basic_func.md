## 基本初等函数
幂函数、指数函数、对数函数、三角、反三角
### 1. 幂函数
> 来源: [知乎](https://zhuanlan.zhihu.com/p/242880083)  

#### $y = x^a$
其中：- x的系数为1，a可以为任意实数  

#### 奇偶性
对于$y = x^{\frac{m}{n} \times (-1)^k}$
1. m 、 n 为奇数， k 为偶数时，定义域为R，是奇函数

2. m 、 n 为奇数， k 为奇数时，定义域为 $(-\infty, 0)\cup(0, +\infty)$ ，是奇函数

3. m 为奇数、 n 为偶数， k 为偶数时，定义域为 $[0, +\infty)$ ，是非奇非偶函数

4. m 为奇数、 n 为偶数， k 为奇数时，定义域为 $(0, +\infty)$ ，是非奇非偶函数

5. m 为偶数、 n 为奇数， k 为偶数时，定义域为R，是偶函数

6. m 为偶数、 n 为奇数， k 为奇数时，定义域为 R，是偶函数


#### 图像
![graph](https://pic4.zhimg.com/80/v2-030eb52991eb0f5d1e73b4a23720a3bf_1440w.jpg)

### 2. 指数函数
> 来源：[知乎1](https://zhuanlan.zhihu.com/p/257268753) [知乎2](https://zhuanlan.zhihu.com/p/20885564)
#### $y = a^x$
定义域： R， 值域： $(0, +\infty)$  

#### 单调性
0 < a < 1 时，图形单调递减
a < 1 时，图形单调递增
![graph](https://pic3.zhimg.com/80/v2-d5c6e936de7ffdf29822f20cdb4b919a_1440w.png)

##### 指数函数与对数互为反函数

### 对数函数
#### $y = \log_a{x}$
对数函数求值：$y = \log_a{x} = \log_a{a^n} = n$  

#### 对数换底公式
$\log_a{b} = \frac{\log_c{b}}{\log_c{a}}$  
且有$\log_a{b} = \frac{\log_b{b}}{\log_b{a}} = \frac{1}{\log_b{a}}$, 故$log_a{b}$与$log_b{a}$互为倒数  
![graph](https://pic3.zhimg.com/80/v2-e218057269dfe70932eeb8347fc7fbba_1440w.png)  

#### 单调性
0 < a < 1 时,函数单调递减
1 < a 时，函数单调递增

#### $log_10{x} = lg{x}$;  $log_e{x} = ln{x}$

### 三角函数
![graph](https://pic3.zhimg.com/80/v2-1224e8f5465c781be150946d81a30822_1440w.jpg)
#### 1. $y = cotx$
![graph](https://pic4.zhimg.com/80/v2-f290fd3346f2d0d949bc550165c06b9f_1440w.jpg)


$tanx = \frac{1}{cotx}$

### 反三角函数

#### 1. $y = arcsinx$
单增，奇函数、$| arcsinx | < \frac{\pi}{2}$（有界）
#### 2. $y = arccosx$
单增，无奇偶、$| arccosx | < {\pi}$（有界）
#### 3. $y = arctanx$
单增、奇函数、$| arctanx | < \frac{\pi}{2}$
![graph](https://pic3.zhimg.com/80/v2-cd9369a972755062c1f86aa1ced68ede_1440w.jpg)

### 反三角函数的导数
##### 反函数的导数等于直接函数的导数的倒数
$\frac{dx}{dy} = \frac{1}{\frac{dy}{dx}}$  

![graph](https://www.zhihu.com/equation?tex=%5Cbegin%7Barray%7D%7B%7Cl%7Cc%7Cc%7C%7D+%5Chline+%E7%BC%96%E5%8F%B7%09%26%5Ctext+%7B+%E5%AF%BC%E6%95%B0+%7D+%26+%5Ctext+%7B+%E5%AE%9A%E4%B9%89%E5%9F%9F+%7D+%5C%5C+%5Chline+1%09%26%28%5Carcsin+x%29%5E%7B%5Cprime%7D%3D%5Cfrac%7B1%7D%7B%5Csqrt%7B1-x%5E%7B2%7D%7D%7D+%26+-1%3Cx%3C1+%5C%5C+%5Chline+2%09%26%28%5Carccos+x%29%5E%7B%5Cprime%7D%3D-%5Cfrac%7B1%7D%7B%5Csqrt%7B1-x%5E%7B2%7D%7D%7D+%26+-1%3Cx%3C1+%5C%5C+%5Chline+3%09%26%28%5Carctan+x%29%5E%7B%5Cprime%7D%3D%5Cfrac%7B1%7D%7B1%2Bx%5E%7B2%7D%7D+%26+-%5Cinfty%3Cx%3C%5Cinfty+%5C%5C+%5Chline+4%09%26%28%5Coperatorname%7Barccot%7D+x%29%5E%7B%5Cprime%7D%3D-%5Cfrac%7B1%7D%7B1%2Bx%5E%7B2%7D%7D+%26+-%5Cinfty%3Cx%3C%5Cinfty+%5C%5C+%5Chline+5%09%26%28%5Coperatorname%7Barcsec%7D+x%29%5E%7B%5Cprime%7D%3D%5Cfrac%7B1%7D%7B%7Cx%7C+%5Csqrt%7Bx%5E%7B2%7D-1%7D%7D+%26+x+%5Cin%28-%5Cinfty%2C-1%29+%5Ccup%281%2C+%5Cinfty%29+%5C%5C+%5Chline+6%09%26%28%5Coperatorname%7Barccsc%7D+x%29%5E%7B%5Cprime%7D%3D-%5Cfrac%7B1%7D%7B%7Cx%7C+%5Csqrt%7Bx%5E%7B2%7D-1%7D%7D%26+x+%5Cin%28-%5Cinfty%2C-1%29+%5Ccup%281%2C+%5Cinfty%29+%5C%5C+%5Chline+%5Cend%7Barray%7D)