---
title: "Magnetické pole"
---

-> *forma "hmoty"*, silové pole, ktorého sila sa prenáša virtuálnymi fotónmi
	![|300](attachments/výmena_virtuálneho_fotónu.png)


## Stacionárne magnetické pole
**Kde sa vyskutuje**:
- okolie stacionárneho permanentného magnetu
- okolie vodiča s konštantným prúdom

*Siločiara* = `magnetická indukčná čiara`
-> priestorovo orientovaná uzavretá krivka, nikde sa nepretínajú
Dotyčnica je osou silového vektoru

![Sila na severné póly vs sila na pólovo zrovnanú časticu|280](attachments/siločiary_magnetického_poľa.png)

![|150](attachments/magnetické_pole_v_okolí_elektrického_prúdu.png)

**Homogénne magnetické pole** - magnetické pole, ktorého siločiary sú rovnobežné
napr. vo vnútri cievky alebo magnetu

### Magnetická indukcia
$$F_{mi}=\vec{B}\cdot{}\vec{I}\cdot{}l\cdot{}\sin\alpha$$
Jednotka $\textbf{Tesla} - T$
![|200](attachments/indukcna_sila_2.jpg)

![|200](attachments/indukcna_sila.jpg)

## Magnetický indukčný tok (flux)

`Orientovaná vodivá slučka` - uzavretý vodič, ktorým prechádza *e. prúd*
vodič musí ležať v rovine a nesmie sa pretínať

$$\Phi_B = BA\cos\theta$$

Kde A je povrch na ktorom pôsobí magnetické pole.

### Faradayov zákon indukcie

$$
\mathcal{E} = -\frac{\text{d}\Phi_B}{\text{dt}} 
\quad \lor \quad 
\mathcal{E} = -N\frac{\text{d}\Phi_B}{\text{dt}}
$$

Kde N je počet otočiek kábla a $\Phi_B$ je magnetický flux cez celú cievku alebo jednu otočku
Elektromotívna sila $\mathcal{E}$ je ekvivalent napätia $U$

$$\nabla \times \textbf{E} = - \frac{\partial \textbf{B}}{\partial t}$$

**Lenzov zákon**:
> todo: learn about this

Uplatnenie Faradayovho zákonu indukcie na interakciu magnetu a uzavretého obvodu

![|600](attachments/lenzov_zákon.png)

### Alternátor

Zdroj *striedavého* napätia, ktorý premieňa mechanickú prácu na elektrickú
Je založený na princípe **Faradayovho zákonu elektromagnetickej indukcie**

![Jednofázový alternátor|250](attachments/Pasted%20image%2020221114111059.png)

### Transformátor

Pracuje na základe [Faradayovom zákone em. indukcie](#Faradayov%20zákon%20indukcie)

Platia rovnice:
$$ U = -N\frac{\text{d}\Phi_B}{\text{dt}} \implies \frac{U_1}{U_2} = \frac{N_1}{N_2} $$
$$ \text{Zachovanie Energie} \to U_1 \cdot I_1 = U_2 \cdot I_2 $$

![|450](attachments/transformátor.png)

> todo:
> alternátor
> trojfázový elektromotor
> transformátor
> kondenzátor