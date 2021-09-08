# 文系でも必ずわかる中学数学 × Python 超簡単プログラミング入門

## Jupyter server の起動

1. `pipenv shell` でpipenv仮想環境に入る。
2. `jupyter notebook` で Sever起動。    
   ※ 1. を忘れると Root の Jupyter server が起動して Module を Import できず Error が起こる。

---

### Section 2 直線を表す Graph

# 比例の式

x と y が同じ割合で変化することを「y は、 x に比例する」と言い、

![\begin{align*} \color{white}y=ax(a\neq0)
\end{align*}
](https://render.githubusercontent.com/render/math?math=%5CLarge+%5Cdisplaystyle+%5Cbegin%7Balign%2A%7D%0A%5Ccolor%7Bwhite%7Dy%3Dax%28a%5Cneq0%29%0A%5Cend%7Balign%2A%7D%0A)

という式で表す。

a は比例定数で

![\begin{align*} \color{white}a = \frac{y}{x} \end{align*}
](https://render.githubusercontent.com/render/math?math=%5Cdisplaystyle+%5Cbegin%7Balign%2A%7D%0A%5Ccolor%7Bwhite%7Da+%3D+%5Cfrac%7By%7D%7Bx%7D%0A%5Cend%7Balign%2A%7D%0A)

で、求められる。(直線の傾き、変化の割合)

## 直線を表す式

直線が y 軸と交わる点を「切片」と言い、ここで直線の傾きを a、切片を b とすると平面上の直線はすべて

![\begin{align*} \color{white}y = ax +b \end{align*}
](https://render.githubusercontent.com/render/math?math=%5CLARGE+%5Cdisplaystyle+%5Cbegin%7Balign%2A%7D%0A%5Ccolor%7Bwhite%7Dy+%3D+ax+%2Bb%0A%5Cend%7Balign%2A%7D%0A)

で、表すことができる。

## (x,y)を通って傾きが a の直線の式

![\begin{align*} \color{white} y = a(x - x_1) + y_1 \end{align*}
](https://render.githubusercontent.com/render/math?math=%5CLARGE+%5Cdisplaystyle+%5Cbegin%7Balign%2A%7D%0A%5Ccolor%7Bwhite%7D+y+%3D+a%28x+-+x_1%29+%2B+y_1%0A%5Cend%7Balign%2A%7D%0A)

## 与えられた2点を通る直線の式

![\begin{align*} \color{white} y= \frac{y_2-y_1}{x_2-x1}(x-x_1) +y_1 (x_1 \neq x_2)
\end{align*}
](https://render.githubusercontent.com/render/math?math=%5CLARGE+%5Cdisplaystyle+%5Cbegin%7Balign%2A%7D%0A%5Ccolor%7Bwhite%7D+y%3D+%5Cfrac%7By_2-y_1%7D%7Bx_2-x1%7D%28x-x_1%29+%2By_1+%28x_1+%5Cneq+x_2%29%0A%5Cend%7Balign%2A%7D%0A)

### Sextion 4 垂直に交わる線

## 2つの直線の傾きをa1、a2とすると、この2つの直線が直角に交わるときは

![\begin{align*} \color{white} a_1a_2 = -1 \end{align*}
](https://render.githubusercontent.com/render/math?math=%5CLARGE+%5Cdisplaystyle+%5Cbegin%7Balign%2A%7D%0A%5Ccolor%7Bwhite%7D+a_1a_2+%3D+-1%0A%5Cend%7Balign%2A%7D%0A)

が成立し、これを「垂直条件」と言う。

## 線分の中点

![\begin{align*} \color{white} ( \frac{x_1 + x_2}{2}, \frac{y_1 + y_2}{2} )
\end{align*}
](https://render.githubusercontent.com/render/math?math=%5CLARGE+%5Cdisplaystyle+%5Cbegin%7Balign%2A%7D%0A%5Ccolor%7Bwhite%7D+%28+%5Cfrac%7Bx_1+%2B+x_2%7D%7B2%7D%2C+%5Cfrac%7By_1+%2B+y_2%7D%7B2%7D+%29%0A%5Cend%7Balign%2A%7D%0A)

### Section 5

# ピタゴラスの定理

直角三角形の斜辺の長さの2乗は、残りの2辺の長さを2乗して足したものと等しい」という定理。

![\begin{align*} \color{white}c^2 = a^2 + b^2 \end{align*}](https://render.githubusercontent.com/render/math?math=%5Clarge+%5Cdisplaystyle+%5Cbegin%7Balign%2A%7D%0A++%5Ccolor%7Bwhite%7Dc%5E2+%3D+a%5E2+%2B+b%5E2%0A%5Cend%7Balign%2A%7D)

## 2点間の距離

![\begin{align*} \color{white}\sqrt{(x_2-x_1)^2+(y_2-y_1)^2} \end{align*}
](https://render.githubusercontent.com/render/math?math=%5Cdisplaystyle+%5Cbegin%7Balign%2A%7D%0A%5Ccolor%7Bwhite%7D%5Csqrt%7B%28x_2-x_1%29%5E2%2B%28y_2-y_1%29%5E2%7D%0A%5Cend%7Balign%2A%7D%0A)

## 点と直線の距離の公式

ある直接と点(x1, y1)の距離を d とすると、その距離は

![\begin{align*} d = \frac{\left|ax_1 + by_1 + c\right|}{\sqrt{a^2 + b^2}} \end{align*}
](https://render.githubusercontent.com/render/math?math=%5CHuge+%5Cdisplaystyle+%5Cbegin%7Balign%2A%7D%0Ad+%3D+%5Cfrac%7B%5Cleft%7Cax_1+%2B+by_1+%2B+c%5Cright%7C%7D%7B%5Csqrt%7Ba%5E2+%2B+b%5E2%7D%7D%0A%5Cend%7Balign%2A%7D%0A)

で求めることができる。