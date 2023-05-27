---
tag: Parafusos, elementos de máquina, elementos de fixação, união desmontável
aliases: parafusos, união desmontável, elemento de fixação
---
Constantes de partes 

kb constante de mola
	Danificado tende a romper
	Usa-se o Diâmetro maior da rosca, 
	Com a área (Abe - Área Resistente) relativa determina o De
	Ao sofrer tração
	Definido de acordo com o aperto
	$$Kp=\frac{f}{lb}$$
	
	
Prensagem elevada
	De acordo com o torque

 Dados dos parafusos
	 Cabeça,
	 Rosca (perfil e tolerância)
		 Quando nada é citadoa rosca é esquerda
	 Comprimento nominal
	 Comprimento de rosca 
	 Material
	 Acabamento superficial
 
 Rosca UNC (Witchworth) Perfil 2 - Mais utilizada

# Exercício 1 
Um cabeçote de um ciilndro hidráulico de dimensões indicadas
na figura
A pressão no interior do cilindro atinge 20Kgh cm2 (bar)
O cabeçote é manufaturado em fofo cinzento com:
	- Classe: 25
	- Tensão de ruptura a tração: $\sigma= 14Kgf/mm^2$ 
	- Tensão de ruptura a compressão: $\sigma =70Kgf/mm^2$
	- E fofo=$10.000 Kgf/mm^2$ 
	- E aço=$21000 Kgf/mm^2$
	- Distância entre os parafusos <= 100

Determine a bitola e a quantidade de parafusos

![[20230505_192104.jpg]]

1. Determinar a força na tampa
	$$A=\frac{\pi*d^2}{4}$$
	$$A=\frac{\pi*49^2}{4}$$
	$$A=1885,74cm^2$$
	$$P=\frac{F}{A}$$
	$$F=P*A$$
	$$F=20*1885,74=37.714,82Kgf$$
	
 1. Fator inicial de aperto (FI)
	$$FI=F*Fs$$
	$$FI=37714,82*4 = 150.859,28Kgf$$
3. Quantidade de parafusos (n)
	$$n=\frac{\pi*d}{100}$$
	$$n=\frac{\pi*560}{100}$$
	$$n=\frac{1759,3}{100} = 17,6$$
	
	 *Deve ser múltiplo de 4 
   $$n=20$$
4. Força por parafuso (FP)
	$$FP=\frac{FI}{n}$$
	$$FP=\frac{150.859,28}{20}=7.543Kgf$$

5. Pré dimensionamento do Parafuso
	$$\sigma i\le0,75*\sigma e$$
	$$\sigma i=0,6*\sigma e$$
	$$\sigma i=0,6*90=54$$
---
$$\sigma=\frac{Fe}{Abe}$$
	$$Abe=\frac{Fe}{\sigma}$$
	$$Abe=\frac{\sigma i}{\sigma}$$
	$$Abe=\frac{7543}{54} = 139,7mm^2$$
---
$$d=\sqrt[2]{\frac{A*4}{\pi}}$$
	$$d=\sqrt[2]\frac{139,64*4}{\pi} = \sqrt[2]\frac{55,86}{\pi} = \sqrt[2]{177,8} = 13,3mm$$
	

6. tabela de rosca de acordo com a área (tabela)
	M16x2mm com área resistente 169,7mm^2 

7. Constante de mola do Parafuso (Kb)
	$$Ab=\frac{\pi*d^2}{4}$$
	$$Ab=\frac{\pi*16^2}{4}=\frac{804,2}{4}=201,1mm^2$$
---
$$Kb=\frac{Ab*Eb}{lb}$$
	$$Kb=\frac{201,1*21.000}{70} = \frac{4.223.100}{70} = 60.330Kgf/mm$$
	 
8. Constante de mola das partes
	$$Kp=\frac{Ap*Ep}{lp}$$
	$$Kp = \frac{2.479,5*10.000}{70} = \frac{24.795.000}{70} = 354.214,3Kgf/mm$$
9. Área de aperto (DE)
	$$DE=S+\frac{l}{2}$$
	$$DE=24+\frac{70}{2}=24+35=59mm$$
---
Área de aperto
	$$D=d+1,5=16+2=18$$
	d = Diâmetro do parafuso
	D = Diâmetro do furo, geralmente 1mm de folga (d+dolfa), acima de 1" - 1,5mm e acima de 2" - 2mm
	$$Área=\frac{\pi}{4}\bigg[\bigg(S+\frac{l}{2}\bigg)^2-D^2\bigg]$$
	$$Área=\frac{\pi}{4}(DE^2-D^2)$$
	$$Área=\frac{\pi}{4}(59^2-16^2)=\frac{\pi}{4}(3.481-256)=\frac{\pi}{4}*3.225=2.532,9mm^2$$
1. Força de Tração atuante no parafuso (Fb)
	$$Fb=\frac{Kb}{Kp+Kb}*\frac{F}{n}+FI$$
	$$Fb=\frac{60.330}{354.214,3+60.330}*\frac{3.774}{20}+7.543=\frac{60.330}{414.544}*188,7+7.543$$
	$$Fb=0,1*188,7+7.543=18,9+7.543=7.561,9Kgf/mm$$
11. Tensão no parafuso
	$$\sigma b = \frac{Fb}{Abe}$$
	$$\sigma b = \frac{7.561,9}{139,7}=54,1Kgf/mm$$
---
Errado -> Considerando Abe 
	 $$\sigma b\le0,75*\sigma e *Abe\rightarrow 54,1\le0,75*90*139,7 \rightarrow 1.081,2 \le 9.429,8$$
---
$$\sigma b\le0,75*\sigma e\rightarrow 54,1\le0,75*90 \rightarrow 54,1 \le 67,5$$
1. Torque
---
Errado
	$$T=0,2*d*FI$$
	$$T=0,2*16*150.859,28 = 482.749,7Kgf/mm$$
---
$$T=0,2*d*FI$$
	$$T=0,2*16*75,43 = 24Kgf/mm$$
13. Resumo
	Parafuso: M16x2mmx82mm
	Quantidade: 20
	Torque: $24Kgf/mm^2$

# Exercício 2
- Um suporte é utilizado para segurar uma carga que varia de 0 a 4.000Kgf
- Parafuso: M12x1,75 (rosca normal)
- Cabeça do parafuso -> S=19mm
- Quantidade: 4
- Espessura das partes -> 12mm
- Tensão de escoamento -> $\sigma e = 35Kgf/mm^2$
- Tensao de fadiga corrigida -> $\sigma n = 16Kgf/mm^2$
- Fator de concentração -> K=3
- Área efetiva do parafuso -> $AB=92,7mm^2$
- Furo passante -> D=15mm
- Módulo de elasticidade do aço -> Ep=21.000Kgf

---
## Variáveis das Parts
$$Área=\frac{\pi}{4}\bigg[\bigg(S+\frac{l}{2}\bigg)^2-D^2\bigg]$$
$$Área=\frac{\pi}{4}\bigg[\bigg(19+\frac{12}{2}\bigg)^2-15^2\bigg]$$
$$Área=0,8\bigg[\bigg(19+6\bigg)^2-225\bigg]$$
$$Área=0,8(25^2-225)=0,8(625-225)=0,8*400$$
$$Área=314,2mm^2$$

$$Kp=\frac{A*E}{l}$$
$$Kp=\frac{314,2*21.000}{12}=\frac{6.597.344}{12}$$
$$Kp=549.778Kgf/mm^2$$

## Variáveis do Parafuso
$$Área = \pi*r^2$$
$$Área = \pi*6^2=\pi*64$$
$$Área=113,1mm^2$$

$$Kb=\frac{A*E}{l}$$
$$Kb=\frac{113,1*21.000}{12}=\frac{2.375.044}{12}$$
$$Kb=197.920 \approx 198.000Kgf/mm^2$$
---
1. Qual o Fator de Segurança (Fs) para $F_i=0$
$$\frac{1}{Fs}=\frac{\sigma m}{\sigma e}+K\frac{\sigma v}{\sigma n}$$
Fs = Fator de segurança
$\sigma m$ = Tensão média
$\sigma e$ = Tensão de escoamento
$\sigma v$ = Tensão variável
$\sigma n$ = Tensão de fadiga corrigida
K = Fator de concentração

$$F = \frac{F}{n}$$
$$F_{máx} = \frac{4.000}{4}=1.000Kgf$$
$$F_{mín} = \frac{0}{4}=0Kgf$$

$$\sigma m=\frac{F}{A} = \frac{\frac{F_{máx}+F_{mín}}{2}}{A}=\frac{\frac{1.000+0}{2}}{92,7}$$
$$\sigma m =\frac{500}{92,7}=5,4Kgf$$


$\sigma v$ por ser uma força estática, toma-se como a média
	- Caso a força variasse no tempo teriamos a média
	- Ex: 0 a 400 em $T_1$, 400 a 1.000 em $T_2$
Logo, nesse caso $\sigma m = \sigma v$

$$F = \frac{F}{n}$$
$$F_{máx} = \frac{4.000}{4}=1.000Kgf$$
$$F_{mín} = \frac{0}{4}=0Kgf$$

$$\sigma m=\frac{F}{A} = \frac{\frac{F_{máx}+F_{mín}}{2}}{A}=\frac{\frac{1.000+0}{2}}{92,7}$$
$$\sigma m =\frac{500}{92,7}=5,4Kgf$$

** Situação crítica - Fs < 1 -> não houve força de aperto inicial

Como a tenão mínima ($F_{mín}$) é 0, a variação ($\sigma v$)
3. Qual o menor $F_i$ que impede a perda de compressão do suporte
	$F_p=0$
	$$F_p=F_i-\frac{Kp}{(K_p+K_b)}*F$$
	$$F_i=\frac{K_p}{(K_p+K_b)}*F-F_p$$
	** Verificar 
	$$F_i=\frac{549.778}{(549.778+198.000)}*4.000-0$$
		$$F_i=\frac{549.778}{747.778}*4.000=0,735*4.000$$
	$$F_i=735Kgf \rightarrow F_i*4=2.940Kgf$$
	
4. Qual o Fs para $F_i=4.000Kgf$	
*Verificar*
$$F_b=F_i+\frac{Kb}{(K_b+K_p)}*F$$
$$F_p=1.000+\frac{187.920}{(556.600+198.000)}*1.000$$
$$F_p=\frac{187.920}{754.600}*1.000+1.000=0,294*1.000+1.000$$
$$F_p=1.262Kgf$$
---
$$F_{min}=\frac{198.000}{556.600+198.000}*0+1.000$$
$$F_{min}=1.000Kgf$$
---
Força variável
$$F_v=\frac{F_{máx}-F_{mín}}{2}$$
$$F_v=\frac{1.264-1.000}{2}=\frac{264}{2}=132kgf$$
---
$$\sigma m=\frac{F_m}{A}=1132/92,7=12,21Kgf/mm^2$$
$$\sigma v = \frac{F_v}{A}=132/92,7=1,42$$
---
$$\frac{1}{Fs}=\frac{\sigma m}{\sigma e}+K\frac{\sigma v}{\sigma n}$$
$$\frac{1}{Fs}=\frac{12,21}{35}+3\frac{1,42}{16}=0,615$$
$$Fs=1,65$$

5. Com $F_i=4.000Kgf$, determine a força mínima de compressão
$$F_i=\frac{F_i}{n}=\frac{4.000}{4}=1.000Kgf$$
$$F_{p(mín)}=F_i-\frac{K_p}{(K_p+K_b)}*F$$
$$F_{p(mín)}=1.000-\frac{556.600}{(556.600+187.920)}*1.500$$
$$F_{p(mín)}=1.000-\frac{556.600}{744.520}*1.500$$
$$F_{p(mín)}=1.000-0,748*1.500=1.000-1.121,2$$
$$F_{p(mín)}=-121,2Kgf$$

# Exercício 3
- Parafuso para biela: 3/8"-24UNF
- Força inical de aperto = 1.600Kgf
- $\sigma e = 63Kgf/mm^2$
- Tensão de fadiga corrigida: sigma n = 40 Kgf mm2
- Área das partes: $A_p=320mm^2$
- A carga de trabalho varia de 0 a 1.150Kgf
![[20230519_211326.jpg]]
25 e 25
1. Determine o Fs
	Kb
	Área cilindro $(pi*d)$ div 4
	50mm
	F med
	F var
	Fb
	Fb - F max 1.150 com Fi 1600
	F(carga) para Fb mín = 0
    Kb - calculada (3133,75 kgf mm2)
$$D=\frac{3}{8}*25,4=9,5mm$$
$$A=\frac{\pi*D^2}{4}=70,8mm^2$$
$$K_b=\frac{70,8*21.000}{50}=29.770Kgf/mm^2$$
$$K_p=\frac{320*21.000}{50}=134.400Kgf/mm^2$$
$$F_{mín}=\frac{29.770}{(29.770+134.400}*0+1.600=1.600Kgf$$
$$F_{b(máx)}=1.808Kgf$$
$$\sigma m =\frac{F_m}{A}=\frac{1704}{64}=26,6$$
$$\sigma v=\frac{F_v}{A}=\frac{104}{64}=1,62$$
$$\frac{1}{Fs}=\frac{26,6}{63}+3\frac{1,62}{40}$$
$$\frac{1}{Fs}=0,544$$
$$Fs=1,83$$

---
# Parafusos - Pente de rosca
M8x1,75mm
M12x2mm

## Notas
Os 3  primeiros filetes não atuam efetivamente
Kb age sobre o diâmetro maior
Força no parafuso
Fs a partir da solicitação externa
Sf = Tensão de fadiga
St = Tensão alternada
