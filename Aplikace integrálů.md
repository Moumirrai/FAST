## Dvojitý integrál

#### Obsah uzavřené oblasti
$$\large P=\iint_D\  dxdy$$

#### Obsah plochy na uzavřené oblasti spojité funkce

$$\large P(S)=\iint_{\Omega}\sqrt{1+\left( \frac{\partial f}{\partial x}(x,y)\right)^2+\left( \frac{\partial f}{\partial y}(x,y)\right)^2}$$
$$\large z = f(x,y)$$

#### Těžiště rovinné desky
##### Celková hmotnost
- u homogenní desky prostě jen [[#Obsah uzavřené oblasti|plocha]]
$$\large m=\iint_D\rho(x,y)\ dxdy$$
- $\rho(x,y)$ - hustota, u <mark style="background: #FF5582A6;">homogenní desky = 1</mark>

##### Statický moment
$$\large
\begin{align*}
S_x &=\iint_Dy\ dxdy \\
S_y &=\iint_D x\ dxdy
\end{align*}$$
Na oblasti D
[[Definice#Statický moment síly k bodu (vázaný moment)|mechanika]]

‎ 
‎ 
‎ ‎ 
‎ 
‎ 



##### Souřadnice těžiště 
$$\large 
\begin{align*}
x_0&=\frac{S_y}{m} \\ \\
y_0&=\frac{S_x}{m}
\end{align*}$$
#### [[34. Moment setrvačnosti|Moment setrvačnosti]] rovinné desky
$$\large\begin{align*}
I_x&=\iint_D y^2\rho(x,y)\ dxdy\\
I_y&=\iint_D x^2\rho(x,y)\ dxdy\\ 
I_p&=\iint_D (x^2+y^2)\rho(x,y)\ dxdy & \text{polární moment}
\end{align*}$$
## Trojitý integrál 

#### Objem tělesa
$$\large
V=\iiint_{\Omega}1\ dxdydz
$$
#### Hmotnost tělesa
- to samé jak u [[#Celková hmotnost|dvojitého]]

#### Statický moment
$$\large\begin{align*}
S_{yz}&=\iiint_{\Omega}\color{red}x\color{white}\rho(x,y,z)\ dxdydz \\
S_{xz}&=\iiint_{\Omega}\color{red}y\color{white}\rho(x,y,z)\ dxdydz \\
S_{xy}&=\iiint_{\Omega}\color{red}z\color{white}\rho(x,y,z)\ dxdydz
\end{align*}$$
‎ 
‎ 
‎ 
‎ 
#### Těžiště oblasti $\Omega$ 
$$\large\begin{align*}
x_0&=\frac{S_{yz}}{m} = \frac{1}{m}\iiint_{\Omega}\color{red}x\color{white}\rho(x,y,z)\ dxdydz \\
y_0&= \frac{S_{xz}}{m} = \frac{1}{m}\iiint_{\Omega}\color{red}y\color{white}\rho(x,y,z)\ dxdydz \\
z_0&=\frac{S_{xy}}{m} = \frac{1}{m}\iiint_{\Omega}\color{red}z\color{white}\rho(x,y,z)\ dxdydz
\end{align*}$$

#### Moment setrvačnosti
$$\large\begin{align*}
I_{x}&=\iiint_{\Omega}(y^2+z^2)\cdot\rho(x,y,z)\ dxdydz \\
I_{y}&=\iiint_{\Omega}(x^2+z^2)\cdot\rho(x,y,z)\ dxdydz \\
I_{z}&=\iiint_{\Omega}(x^2+y^2)\cdot\rho(x,y,z)\ dxdydz
\end{align*}$$