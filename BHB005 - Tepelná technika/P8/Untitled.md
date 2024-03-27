## Kondenzace vodní páry uvnitř konstrukce  
Zadání  
Stanovte oblast kondenzace vodní páry uvnitř konstrukce $S1_s$.  
Okrajové podmínky:  
$\Theta_i=20°C$  
$\Theta_{ai}=\Theta_i+\Delta\Theta_{ai}=0.6+20=20.6°C$  
$\varphi_i=50\%$  
$\Delta\varphi_{a,i}=5\%$  
$\varphi_{i,u}=\varphi_i+\Delta\varphi_{a,i}=50+5=55\%$  
$\Theta_e=-13°C$  
$\varphi_e=84\%$  
  
Postup výpočtu:  
1. Průběh teplot v konstrukci ($R_{si}$ pro výpočet šíření tepla) - viz předchozí protokoly  
2. Difúzní odpor konstrukce:  
a) difúzní odpor jedné vrstvy $Z_{pj}$:  
$$Z_{p,j}=\frac{d_j}{\delta_j}\;[m.s^{-1}]$$  
- $d_j$ - tloušťka j-té vrstvy \[m]  
- $\delta_j$ - součinitel difúzní vodivosti materiálu j-té vrstvy \[s] nebo \[$kg.m^{-1}.s^{-1}.Pa^{-1}$]  
b) difúzní odpor velé konstrukce $Z_p$:  
$$Z_p=\sum_j Z_{p,j}=\sum_j \frac{d_j}{\delta_j}\;[m.s^{-1}]$$  
  
//TODO: tabulka  
  
3. Difúzní odpor konstrukce při prostupu vodní páry $Z_{p,T}$  
$$Z_{p,T}=Z_{p,i}+Z_p+Z_{p,e}\;[m.s^{-1}]$$  
- $Z_{p,i}$ - dufúzní odpor při přestupu vodní páry na vnitřním povrrchu $[m.s^{-1}]$  
- $Z_{p,e}$ - dufúzní odpor při přestupu vodní páry na vnějším povrrchu $[m.s^{-1}]$  
  
4. Částešný tlak nasycené vodní páry $p_{sat,x}$ [Pa] na rozhraní jednotlivých vrstev:  
  
//TODO: tabulka  
  
[http://ps1.pst.fce.vutbr.cz/ps/bhb005/parc_tlak_vodni_pary.pdf](http://ps1.pst.fce.vutbr.cz/ps/bhb005/parc_tlak_vodni_pary.pdf) naše hodnota 2425 pro 20.6°C  
[http://ps1.pst.fce.vutbr.cz/ps/bhb005/parc_tlak_nasyc_vodni_pary.pdf](http://ps1.pst.fce.vutbr.cz/ps/bhb005/parc_tlak_nasyc_vodni_pary.pdf) vztahy  
  
5. Částečný tlak vidbí páry $p_i$ a $p_e$ [Pa] v interiéru a exteriéru:  
$$p_i=\frac{\varphi_{i,u}}{100\%}\cdot p_{sat,i}\;[Pa]$$  
$$p_e=\frac{\varphi_{e}}{100\%}\cdot p_{sat,e}\;[Pa]$$  
  
6. Grafické řešení:  
a) zakreslíme konstrukci v měřítku difúzních odporů  
b) vedeme tečny z bodů $p_i$ a $p_e$ ke křivce průběhu částečných tlaků vodní páry (čára $p_{sat}$)  
c) body dotyku A a B vymezujících oblast kondenzace:  
- kondenzační oblast  
- kondenzační rovina, pokud A = B (zpravidla na rozhraní vrstev)  
d) posouzení tlakové podmínky:  
- $p_x<p_{sat,x}$ : nedochází ke kondenzaci  
- $p_x>p_{sat,x}$ : dochází ke kondenzaci (oblast kondenzace vymezena body A a B)  
  
### Závěr