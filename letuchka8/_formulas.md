# Simulated Annealing

## Три закона охлаждения

$$
T_{\text{geom}}(t) = T_0 \cdot \alpha^t, \qquad \alpha = 0.95
$$

$$
T_{\log}(t) = \dfrac{T_0}{\ln(t + 2)}
$$

$$
T_{\text{vfa}}(t) = T_0 \cdot \exp\!\left(-\beta \cdot (t+1)^{1/d}\right), \qquad \beta = 1,\ d = 1
$$

## Тестовые функции

$$
f_1(x) = 5 - 24x + 17x^2 - \tfrac{11}{3}x^3 + \tfrac{1}{4}x^4, \qquad x \in [-1,\, 9]
$$

$$
f_2(x) = x \sin(3x) + 0.5x, \qquad x \in [-8,\, 8]
$$