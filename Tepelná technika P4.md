##### 1. Hodnoty veličin (viz předchozí protokoly):
- součinitel prostupu tepla $U_j$ $[W.m^{-2}.K^{-1}]$ všechno obalovaných konstrukcí
- plocha $A_j$ $[m^2]$ všech obalovaných konstrukcí na systémové hranici budovy
- součet ploch obalových konstrukcí, tzv. teplosměnná plocha obálky budovy:
$$A=\sum A_j\ \ \ [m^2]$$
- objem budovy $V$ $[m^3]$ stanovený systémovou hranicí
- faktor tvaru budovy $\frac{A}{V}$ $[m^{-1}]$
##### 2. Měrná ztráta prostupem tepla $H_r$ $[W.K^{-1}]$:
- měrná ztráta k venkovnímu prostředí
- měrná ztráta k nevytápěnému prostoru
- měrná ztráta k zemině
- měrná ztráta k jinak vytápěnému prostoru
$$H_T=\sum (A_j\cdot U_j\cdot b_j)+A\cdot \Delta U_{tbm}\ \ \ [W.K^{-1}]$$
- $\Delta U_{tbm}$ - průměrný vliv všech tepelných vazeb $[W.m^2.K^{-1}]$ podle odst. H.2.3 ČSN 73 0540-4:2005
    - $\Delta U_{tbm}=0,02\ W.m^2.K^{-1}$ pro důsledně optimalizované tepelné vazby (tepelné mosty)
    - $\Delta U_{tbm}=0,05\ W.m^2.K^{-1}$ pro mírné tepelné vazby
    - $\Delta U_{tbm}=0,10\ W.m^2.K^{-1}$ pro bežné tepelné vazby
    - $\Delta U_{tbm}=0,20\ W.m^2.K^{-1}$ pro výrazné tepelné vazby
- $b_j$ - činitel teplotní redukce $[-]$
    - pro konstrukce s rozdílem teplot mezi interiérem a exteriérem stejným, jako je základní rozdíl teplot $(\Theta_{i}-\Theta_{e})$ je $b_j=1,0$
    - pro konstrukce přilehlé k nevytápěnému prostoru nebo k zemině viz tabulka F.2 ČSN 73 0540-3:2005
    - pro jinak vytápěné prostory:
        $$b_j=\frac{\Theta_{i}-\Theta_{sousední\ nevytáp\ prostor}}{\Theta_{i}-\Theta_{e}}$$
3. Průměrný součinitel prostupu tepla $U_{em}$ $[W.m^{-2}.K^{-1}]$:
$$U_{em}=\frac{H_T}{A}\ \ \ [W.m^{-2}.K^{-1}]$$

```math
a = 5*5
b = a-5
```




