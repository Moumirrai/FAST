#### Převod periody a frekvence
Perioda a frekvence je obrácená hodnota, takže to druhé dostaneme tak že dáme $\large\frac{1}{x}$ $$\large 4\cdot10^{-4}\ s \ =\  \frac{1}{4\cdot10^{-4}}\ Hz = 2500\ Hz = 2.5 \ kHz$$
Naopak je to stejně

#### Teplotní protažení tyče
![[Vzorečkynn#Teplotní deformace $ large Delta l$]]

---
O kolik se protáhne ocelová tyč dlouhá 1.25m při zahřátí o 52,2°C ?
- PAMATOVAT $\alpha$ pro ocel je $1.2\cdot 10^{-5}$
$$\large 1.2\cdot 10^{-5}\cdot 1.25\cdot 52.2=\color{red}{7.83\cdot10^{-4}}\color{white}m$$
$$\large 7.83\cdot 10^{-4}\ m= 0.000783\ m=\color{lime}783\ qm$$

Může se stát že vzoreček budeme muset přskládat tak abychom dostali o kolik musíme tyč zchladit nebo zahřát aby se prodloužila o danou délku.

#### Změna hladiny statického napětí - úchylkoměr
- nulové čtení $d_0=102\mu m$
- čtení po zatížení $d=124\mu m$
- modul pružnosti $E=2.1\cdot 10^5\ N\cdot mm^{-2}$ 
- $l_0=100mm (\cdot 1000) = 100000\mu m$
$$\large \Delta\varepsilon=\frac{\Delta l}{l_0}=\frac{(124-102)}{100\cdot1000}=2.2\cdot 10^{-4}\mu m$$
$$\large \Delta \sigma=E\cdot \Delta \varepsilon=E=\color{lime} 2.1\cdot 10^5\ N\cdot mm^{-2}\cdot \color{orange}2.2\cdot10^{-4}\color{white}=46.2\ N\cdot mm^{-2}$$
#### Změna hladiny statického napětí - strunový tenzometr
- nulové čtení $f_0=931Hz$
- čtení po zatížení $f=965Hz$
- modul pružnosti $E=2.1\cdot 10^5\ N\cdot mm^{-2}$ 
- konstanta tenzometru $K=2.14\cdot 10^{-3}\mu m/m Hz^2$
$$\large \Delta\varepsilon=K\cdot[f^2-f_0^2]\color{red}\cdot10^{-6}\color{white}=137.95 \cdot 10^{-6}\ \ \ \text{toto je v oficiálním taháku}$$
PATATOVAT SI ŽE TAM JE 10 NA -6, TO V TAKÁHU NENÍ, POZOR!!!!!!
$$\large \Delta \sigma=E\cdot \Delta \varepsilon=2.1\cdot 10^5\cdot 137.95\cdot10^{-6}=\color{lime}28.97\ N\cdot mm^{-2}$$
POZOR, někdy je zadaná perioda, a je potřeba ji [[#Převod periody a frekvence|převést na frekvenci]], nebo na to je vzoreček v taháku 

#### Výpočet rychlosti šíření impoulsu ultrazvuku v betonové stěně
- tloušťka 100mm 
- doba průchodu $26.1\mu s$
- doba průchodu etanolem $111.7\mu s$
- časová charakteristika etanolu $109.8 \mu s$
$$\large\text{mrtvý čas}= T_0=T_e-E=111.7-109.8=1.9\mu s$$
<mark style="background: #FF5582A6;">Mrtvý čas může vyjít i záporný</mark>

$$\large v_i=\frac{L_i}{T_i-T_0}=\frac{0.1}{26.1-1.9}=4132.23=4130\ m/s$$
	Dosazjeme $L_i$ v metrech a časy v $\mu s$ , <mark style="background: #FFB86CA6;">tak nám vyjdou metry za sekundu</mark>

#### Výpočet pevnosti tlaku z rychlosti šíření ultrazvuku
- rychlost šíření v jednorozměrném prostředí je $4000\ m\cdot s^{-1}$
- $K_3=1.0541$ //to je v taháku 
$$\large v_3=K_3\cdot V_z=1.0541\cdot 4000=4216.4\ m\cdot s^{-1}$$
$$\large 4216.4\ m\cdot s^{-1}=4.2164\ km\cdot s^{-1}$$
## WTF??? XD vůbec nevím co dál

#### Výpočet dynamickémo modulu pružnosti v tlaku betonu pomocí ultrazvuku v trojrozměrném prostředí 
- $k_3=1.0541$  //v taháku 
- $v_L=4050\ m\cdot s^{-1}$ //rychlost
- $\varrho = 2200\ kg/m^{-3}$ //hustota

Celý tento vzoreček je v taháku, chill
$$\large E_{cu}=\varrho\cdot v_L^{2}\cdot k^{-2}=2200\cdot 4.05^2\cdot 1.0541^{-2}=32476.49 = 32500\ N/mm^2$$
<mark style="background: #FF5582A6;">Zase dosazovat rychlost v km/s, abychom neuseli nějak převádět</mark>

#### Stanovení dynamického modulu pružnosti ve snyku a dynamický poissonův koeficient
- na základě vlastní frekvence hranolu rezonanční metodou
- $a=b=100mm$
- $m=6.8\ kg$
- $f_t=3.7 kHz$
- $E_{brL}=33500\ N/mm^2$
- $l=300\ mm$
Hustota
$$\large \varrho=\frac{m}{a\cdot b\cdot l}=2266.67\ kg/m^3$$
Modul pružnosti $G_{cr}$ - je to celé v taháku
$$\large G_{cr}=4\cdot k\cdot l^2\cdot f_t^2\cdot \varrho=13216.47=13200\ N/mm^2$$
Poissonův součinitel $V_{cr}$ - taky celé v taháku
$$\large V_{cr}=\frac{E_{bcL}}{2\cdot G_{cr}}-1=\frac{33500}{2\cdot 13200}-1=0.27$$
#### Statický modul pružnosti betonu zatěžováním Ec
- horní napětí $fc=24.3\ N/mm^2$
- délka základy $H=200\ mm$
- rozdíl délky při zatěžování $\Delta l'=2\mu m$    a   $\Delta l''=56\mu m$
$$\large \Delta l^{1,2}=\frac{\Delta l'+\Delta l''}{2}=54\mu m=54\cdot 10^{-6}m$$
$$\large \Delta \varepsilon^{1,2}=\frac{\Delta l^{1,2}}{H}=\frac{54\cdot 10^{-6}}{0.2}=2.7\cdot 10^{-4}$$
$$\large \Delta\sigma=\frac{fc}{3}-0.5=\frac{24.3}{3}-0.5=7.6\ N/mm^2$$

$$\large Ec=\frac{\Delta\sigma}{\Delta \varepsilon^{1,2}}=\frac{7.6}{2.7\cdot 10^{-4}} = 28\ 148.15$$

#### Pevnost v tlaku ze zkoušty statiského modulu pružnosti
- poměrné zkrácení základen $\Delta\varepsilon^{1,2}=0.240\cdot 10^{-3}$
- modul pružnosti $Ec=30\ 000\ N/mm^2$
$$\large Ec=\frac{\Delta\sigma}{\Delta \varepsilon^{1,2}}$$
$$\large \Delta\sigma=Ec\cdot \Delta \varepsilon^{1,2}=30\ 000\cdot 0.24\cdot10^{-3}=7.2\ N/mm^2$$
$$\large \Delta\sigma=\frac{fc}{3}-0.5$$
$$\large fc=(\Delta\sigma+0.5)\cdot 3=(7.2+0.5)\cdot 3=23.1\ N/mm^2$$
#### Hodnota průměrného poměrného přetvoření $\Delta\varepsilon^{1,2}$ 
- $Ec=32\ 000\ N/mm^2$
- $\Delta\sigma=8.3\ N/mm^2$ 
$$\large Ec=\frac{\Delta\sigma}{\Delta \varepsilon^{1,2}}$$
$$\large \Delta \varepsilon^{1,2}=\frac{\Delta\sigma}{Ec}=$$

## HALO?????

n