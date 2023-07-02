---
tag: Processo dos gases ideais, processo dos gases ideais, gases ideais
aliases: Processo dos gases ideais, processo dos gases ideais
---

[[Fórumlas Termodinâmica|Fórmulas básicas da termodinâmica]]

## Isotérmico / Isotermo (*Boyle - Marriote*) ($T_i=T_f$)
- [[Conceitos da Termodinâmica|Temperatura]] constante ($T_i=T_f$)
- [[Fórumlas Termodinâmica|Variação de energia interna]] ($\Delta u$) = 0
- [[Fórumlas Termodinâmica|Variação da entalpia]] ($\Delta H$ ) = 0
- [[Processos dos gases ideais|Trabalho por variação de volume]] = [[Processos dos gases ideais|Trabalho por variação de pressão]] = [[Conceitos da Termodinâmica|Calor]]-> ($W_{dv}=W_{dp}=Q$) 

### Trabalho por variação de volume ($W_{dv}$)
$$W_{dv} = m * R * T_i * ln \frac{V_f}{V_i} = m * R * T_i * ln \frac{P_i}{P_f}$$
$$W_{dv} = W_{dp} = Q$$

### Trabalho por variação de pressão ($W_{dp}$)
$$W_{dp} = m * R * T_i * ln \frac{P_i}{P_f} = m * R * T_i * ln \frac{V_f}{V_i}$$
$$W_{dp} = W_{dv} = Q$$
### Variação entropia ($\Delta s$)
![[Fórumlas Termodinâmica]]

## Isóbaro *(Bay-Lussak)* ($P_i = P_f$)
- [[Conceitos da Termodinâmica|Pressão]] constante ($P_i=P_f$)
- Trabalho por variação de pressão ($W_{dp}$) = 0
- [[Conceitos da Termodinâmica|Calor]] = [[Fórumlas Termodinâmica|Variação da entalpia]] ($Q = \Delta H$)

### Trabalho por variação de volume ($W_{dv}$)
$$W_{dv} = P_i(V_f-V_i) = m * R(T_f-T_i)$$

### Variação de energia interna ($\Delta u$)
$$\Delta u = m * C_v(T_f-T_i) = \frac{W_{dv}}{K-1}$$

### Variação da entalpia ($\Delta H$)
$$\Delta H = m * C_p * (t_f-T_i) = \frac{K * W_{dv}}{K-1} = K * \Delta u$$

### Variação da entropia ($\Delta s$)
$$\Delta s = m * C_p * ln \frac{T_f}{T_i} = m * C_p * ln \frac{V_f}{V_i}$$

## Isométrico / Isovolumétrico / Isocóro *(Charles)* ($V_i=V_f$)
- [[Propriedades da matéria|Volume]] constante ($V_i=V_f$)
- Se não há variação de [[Propriedades da matéria|volume]] (V), o [[Processos dos gases ideais|trabalho por variação de volume]] ($W_{dv}$) é 0. ($W_{dv} = 0$)

### Trabalho por variação de pressão ($W_{dp}$)
$$W_{dp} = - V_i(P_f - P_i) = -m * R * (T_f- T_i) = -(K-1) \Delta u = \frac{(K-1) \Delta H}{K}$$

### Variação de energia interna ($\Delta u$)
$$m * C_v * (T_f - T_i)$$

### Variação da entalpia ($\Delta H$)
$$\Delta H = m * C_p * (T_f - T_i) = K * \Delta u$$

### Variação da entropia ($\Delta s$)
$$\Delta s = m * C_v * ln \frac{T_f}{T_i} = m * C_v * ln \frac{P_f}{P_i}$$

## Isentropo / Isentrópico ($S_i = S_f$)
- [[Conceitos da Termodinâmica|Entropia]] constante ($S_i = S_f$)
- O sistema é isolado termicamente
- Variação de [[Conceitos da Termodinâmica|calor]] = variação da [[Conceitos da Termodinâmica|entropia]] = 0 -> ($Q = \Delta s = 0$)
- Trabalho por variação de volume = - [[Fórumlas Termodinâmica|variação de energia interna]] ($W_{dv} = - \Delta u$)

### Constante de Boltzmann ($K$) 
$$K = \frac{C_p}{C_v} = 1 + \frac{R}{C_v}$$
### Relações
1. $$\frac{V_i}{V_f} = \bigg( \frac{P_f}{P_i} \bigg) ^ \frac{1}{K} = \bigg(\frac{T_f}{T_i} \bigg )^ \frac{1}{K-1}$$
2. $$\frac{T_f}{T_i} = \bigg( \frac{P_f}{P_i} \bigg) ^ \frac{K-1}{K} = \bigg(\frac{V_i}{V_f} \bigg )^ {K-1}$$
3. $$\frac{V_f}{V_i} = \bigg( \frac{P_i}{P_f} \bigg) ^ \frac{1}{K} = \bigg( \frac{T_i}{T_f} \bigg) ^ \frac{1}{K-1}$$
### Trabalho por variação de volume ($W_{dv}$)
1. 
$$ W_{df} = - \Delta u =  
\frac{P_i * V_i}{K - 1} * \bigg[ 1 - \bigg( \frac{V_i}{V_f} \bigg)^{K-1} \bigg] = 
\frac{P_i * V_i}{K - 1} * \bigg[ 1 - \bigg( \frac{P_f}{P_i} \bigg)^ \frac{K-1}{K} \bigg] =
$$ 
$$
= \frac{m * R}{K - 1} (T_i - T_f) = 
\frac{P_i * V_i - P_f * V_f}{K-1} = 
$$
2. $$ T_f - T_i = \frac{- W_{dv}}{m * R} = \frac{- W_{dv}}{m * C_v}$$
###  Trabalho por variação de pressão ($W_{dp}$)
$$W_{dp} = K - W_{dv}$$

### Variação da entalpia ($\Delta H$)
$$\Delta H = - W_{dp} = m * C_p(T_f-T_i) = K * \Delta u = -K * W_{dv}$$


## Polítropo / Polítropico ($dQ \neq 0, \, dS \neq 0, \, \Delta s \neq 0$)
- Usa-se o coeficiente polítropo ($n$) no lugar da [[Fórumlas Termodinâmica|constante de Boltzmann]] ($K$)
- [[Conceitos da Termodinâmica|Sistema]] não isolado termicamente

1. $$P_i * V_i^n = P_f * V_f^n$$
2. $$\frac{P_f}{P_i} = \bigg( \frac{V_i}{V_f} \bigg) ^ n$$
3. 