## Dvojitý integrál

#### Obsah uzavřené oblasti
$$\large P=\iint_D\  dxdy$$
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

#### Těžiště oblasti $\Omega$ 
$$\large\begin{align*}
x_0&=\frac{1}{m}\iiint_{\Omega}\color{red}x\color{white}\rho(x,y,z)\ dxdydz \\
y_0&=\frac{1}{m}\iiint_{\Omega}\color{red}y\color{white}\rho(x,y,z)\ dxdydz \\
z_0&=\frac{1}{m}\iiint_{\Omega}\color{red}z\color{white}\rho(x,y,z)\ dxdydz
\end{align*}$$
#### Statický moment
$$\large\begin{align*}
S_{xz}&=\iiint_{\Omega}\color{red}y\color{white}\rho(x,y,z)\ dxdydz \\
S_{yz}&=\iiint_{\Omega}\color{red}x\color{white}\rho(x,y,z)\ dxdydz \\
S_{xy}&=\iiint_{\Omega}\color{red}z\color{white}\rho(x,y,z)\ dxdydz
\end{align*}$$