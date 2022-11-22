---
title: "Obvody"
---

## Striedavý prúd

### Rezistor 

Rovnako platí **ohmov zákon** $I = \frac{U}{R}$
$$U(t) = U_{m} \cdot \sin(\omega{}t + \phi)$$
$$I(t) = I_{m} \cdot \sin(\omega{}t + \phi)$$

### Kondenzátor

$$q = C \cdot U(t)$$
$$I(t) = \frac{dq}{dt} = C U_{m} \omega \cdot \cos(\omega{}t + \phi)$$

Napätie zaostáva za prúdom o $\pi/2$
$$R = X_{C} = \frac{U_m}{I_m} = \frac{1}{\omega{}C}$$

### Cievka

$$I = L \frac{dI}{dt}$$
$$U(t) = L I_{m} \omega \cdot \cos(\omega{}t + \phi)$$

$$R = X_{L} = \frac{U_m}{I_m} = \omega L$$

### Spolu

V sérií: (impedancia)
$$Z = R + X_{L} + X_{C}$$
$$Z = R + j \omega L + \frac{1}{j \omega{} C} \qquad j^{2}=-1$$
$$|Z| = \sqrt{R^{2} + \left(\omega L - \frac{1}{\omega{} C}\right)^{2}}$$