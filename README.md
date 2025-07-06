Теорема (Бином Ньютона):
$\forall x, y \in \mathbb{R}$ $n \in \mathbb{N}$
$(x + y)^n = \sum_{k = 0}^{n} С_{n}^{k} x^n y^{n - k}$

Лемма:
$C_{n}^{0} = C_{n}^{n} = 1 \; ; \; C_{n}^{1} = C_{n}^{n - 1} = n$ 
$C_{k}^{n} + C_{k - 1}^{n} = C_{k}^{n + 1}$
Доказательство:
Докажем с помощью математической индукции
1) База n = 1: $(x + y)^1$ = x + y = $C_{1}^{0} x^0 y + C_{1}^{1} x^1 y^0$ = y + x
2) Индукционный переход (n $\rightarrow$ n + 1): Фиксируем $n \in \mathbb{N}$ и пусть $\forall x, y \in \mathbb{R} = \sum_{k = 0}^{n}C_{n}^{k} x^k y^{n - k}$
$$\Rightarrow (x + y)^{n + 1} = (x + y)\left( \sum_{k = 0}^{n} x^k y^{n - k} \right) = \sum_{k = 0}^{n} C_{n}^{k} x^{k + 1} y^{n - k} + \sum_{k = 0}^{n} C_{n}^{k} x^k y^{n + 1 - k}$$
Сдвинем индекс первой суммы $j = k + 1$ и переименуем j в k и приведём подобные члены
$$\Rightarrow \sum_{j = 1}^{n + 1} C_{n}^{j - 1} x^j y^{n + 1 - j} + \sum_{k = 0}^{n} C_{n}^{k} x^k y^{n + 1 - k} = \sum_{k = 1}^{n + 1} C_{n}^{k - 1} x^k y^{n + 1 - k} + \sum_{k = 0}^{n} C_{n}^{k} x^k y^{n + 1 - k} = $$ 
$$ = C_{n}^{n} x^{n + 1} y^0 + \sum_{k = 1}^{n}(C_{n}^{k -1 } + C_{n}^{k})x^k y^{n + 1 - k} + C_{n}^{0} x^0 y^{n + 1} = $$
$$ = C_{n + 1}^{n + 1} x^{n + 1} y^0 + \sum_{k = 1}^{n} C_{n + 1}^{k} x^k y^{n + 1 -k} + C_{n + 1}^{0} x^0 y^{n + 1} = \sum_{k = 0}^{n + 1} C_{n + 1}^{k} x^k y^{n + 1 - k}$$
