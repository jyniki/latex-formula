## markdown 常用公式编辑
### 1. 基本用法
#### 1.1 呈现位置
`$...$`用来在文本中嵌入显示; `$$....$$`则为隔行居中显示

#### 1.2 常用希腊字母表示
|  写法    |表示      |  
|:----:|:----:|
| `$\alpha$`| $\alpha$ |
| `$\beta$`| $\beta$|
|`$\gamma$`| $\gamma$|	 
|`$\delta$`| $\delta$|
|`$\epsilon$`|$\epsilon$|
|`$\eta$`|$\eta$|
|`$\theta$`|$\theta$|
|`$\lambda$`|$\lambda$|
|`$\mu$`|$\mu$| 
|`$\omega$`|$\omega$|
|`$\pi$`|$\pi$	 |
|`$\xi$`|$\xi$	 |
|`$\tau$`|$\tau$	 |
|`$\phi$`|$\phi$	 |
|`$\psi$`|$\psi$	 |
|`$\upsilon$`|$\upsilon$|
|`$\nu$`|$\nu$	 |

> 注：  
> - 首字母大写即为大写表示：`$\Theta$`为 $\Theta$
> - 加`var`前缀则为斜体表示：`\$vartheta$`为 $\vartheta$

#### 1.3 上下标    
`_`表示下标，`^`表示上标  
        
|  写法    |表示      |  
|:----:|:----:|
|`$I_i$`|$I_i$|
|`$I^j$`|$I^j$|
|`$I_i^{ka+b}$`|$I_i^{ka+b}$|

#### 1.4 矢量
利用`\vec`和`\overrightarrow`(注意空格)     

|  写法    |表示      |  
|:----:|:----:|
|`$\vec {a}$`| $\vec {a}$ |   
|`$\overrightarrow {a+b}$`|  $\overrightarrow {a+b}$ |
|`$x \to 0$`|$x \to 0$|

#### 1.5 分组与括号

|  写法    |表示      |  
|:----:|:----:|
|小括号 `$(a+b+c)$`|	$(a+b+c)$ |
|中括号 有空格 `$[a\ b\ c]$`	|$[a\ b\ c]$|
|中括号 无空格  `$[a b c]$` 	|$[a b c]$|
|大括号`{}`用来分组    `$10^{20}$`|$10^{20}$|
|若无大括号`{}` `$10^20$`|$10^20$  `(error)`|
|尖括号 `$<\overrightarrow {xyz}>$`|$<\overrightarrow {xyz}>$|

#### 1.6  求和，极限，积分，分式，根式   

|  写法    |表示      |  
|:----:|:----:|
|求和 `$\sum_{i-1}^{N}(W_i*X_i+b_i)$` |$\sum_{i-1}^{N}(W_i*X_i+b_i)$|
|极限`$\lim_{x \to 0}{f(x)}$`|$\lim_{x \to 0}{f(x)}$|
|积分`$int_0^\infty{f(x)dx}$`|$int_0^\infty{f(x)dx}$|
|分式  `$\frac {x+y}{x_0+y_0}$`|$\frac {x+y}{x_0+y_0}$|
|根式 `$\sqrt[x][y]$`|$\sqrt[x][y]$|

#### 1.7 函数
常用函数

|  写法    |表示      |  
|:----:|:----:|
| `$\min{(w*x+b)}$`|$\min{(w*x+b)}$|
|`$\max{(w*x+b)}$`|$\max{(w*x+b)}$|
|`$\sin{(w*x+b)}$`|$\sin{(w*x+b)}$|
|`$\cos{(w*x+b)}$`|$\cos{(w*x+b)}$|
|`$\tan{(w*x+b)}$`|$\tan{(w*x+b)}$|
|`$\ln{(w*x+b)}$`|$\ln{(w*x+b)}$|
 
其他函数通用写法：   
`$$softmax= \frac {e^{x_i}}{\sum_{j=0}^N{e^x_j}}$$`
$$softmax= \frac {e^{x_i}}{\sum_{j=0}^N{e^x_j}}$$

#### 1.8 算式与特殊符号
|  写法    |表示      |  
|:----:|:----:|
||$\pm$|
||$\div$|
||$\times$|
||$\sum$|
||$\prod$|
||$\leq$|
||$\neq$|
||$\geq$|
||$\infty$|
||$\cup$|
||$\cap$|
||$\subset$|
||$\subseteq$|
||$\supset$|
||$\supseteq$|
||$\in$|
||$\notin$|
||$\emptyset$|
||$\forall$|
||$\exists$|
||$\lnot$|
||$\nabla$|
||$\partial$|
