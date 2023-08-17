---
tag: Fadiga
aliases: fadiga, tipos de fadiga
---
- Fadiga sob tensão
- Fadiga superficial

## Limite de Resistência à Fadiga ($S_f$)
- Diagrama S-N
	- Determina a quantidade de cilcos suportados pela peça
	- O limite de resistência a fadiga = Tensão de Ruptura 
		- Tensão de ruptura ($\sigma_{rup}$ ou $S_{\micro}$ ou $S_u$)
		- $S_f$ usado o valor do corpo de prova
		- Para $S_u$ > 1.400 MPa
		- $$S_f'= 0,504 * S_{rup} = 0,504 * S_{\micro}$$
## Fatores Modificadores
$$S_f = K_a * K_b * K_c * K_d * K_e * s_f'$$

$K_d$ = Fator devido à temperatura
$K_e$ = Fatores diversos 

## Fator de acabameto ($K_a$)
- Considera o acabamento superficial da peça
$$K_a = a *\sigma_{rup}^b$$
a e b são tabelados

## Fator devido ao tamanho ($K_b$)
Polegada:
$$K_b = \frac{d}{0,3}^{-1133} \rightarrow 0,11 <= d <= 2 $$

Milímetro
$$K_b=\bigg(\frac{d}{7,62}\bigg)^{-0,1133}=1,24*d^{-0,107}$$
### Diâmetro Efetivo
$$d_e=0,808 (h*b)^{0,5}$$

# Exercício 1 
Uma peça metalica sob uma carga fletora F.
A mola flutua entre 9,3 e 10,67 kN.
Limite de resistência a tração $\sigma_{rup}=1.400 MPa$ 
Limite de escoamenteo $S_e = 950MPa$.
Espessura = 18 mm
Fator de acabamento: a = 272MPa e b = -0,995
Sendo um acoplamento forjado para a peça, calcule o fator de seguraça ($F_s$) contra o escoamento  e a fadiga.

> [!question] Calcule
> $S_f=$
> $K_a=$
> $d_e=$


[[Fadiga - Exercício 1]]
![[Fadiga - Exercício 1]]

$$d_1=d_2$$
$$R_1 = R_2 = \frac{F}{2}*d_1$$
Máx
$$R_1=\frac{10.670}{2}*0,15$$
$$R_1=R_2=800,25Nm$$
Mín
$$R_1=R_2=\frac{9.300}{2}*0,15$$
$$R_1=R_2=697,5Nm$$

---
$$K_a = a*\sigma_{rup}^b$$
$$K_a=272*1.400^{-0,995}$$
$$K_a  = 0,201$$
---
$$d_e=0,808*(h*b)^{0,5}$$
$$d_e=0,808(75*18)^{0,5}$$
$$d_e=29,6$$
---
$$K_b=\bigg(\frac{d}{7,62}\bigg)^{-0,1133}$$
$$K_b=\bigg(\frac{29,6}{7,62}\bigg)^{-0,1133}$$
$$K_b=0,857$$
---
Reações em carga, tipos de reação
Carga centrada
Distribuida
Lados das reações
Porque das reações
