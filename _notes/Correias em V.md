Ref: https://drive.google.com/file/d/1UyW_G1IdQNc3QXvLOOvKruXeKcfT30kV/view?usp=share_link

Dados necessários:
	1. Tipo do motor
	2. Potência do motor;
	3. Rotação do Motor
	4. Tipo de Máquina
	5. Rotação da Máquina
	6. Distância entre Centros
	7. Tempo de trabalho diário

# Fórmulas
## I. Potência Projetada
$$HPP = hp * Fs$$

HPP = Potência Projetada
hp = Potência do motor
Fs = Fator de Serviço

## II. Diâmetro da Polia

$$D = d * \frac{RPMmaio}{RPMmenor} = d * i$$

D = Diâmetro maior
d = Diâmetro menor
i = Relação de Transmissão

## III. Distância entre Centros
- Quando o centro entre as polias não é conhecido:
$$C=\frac{3d+D}{2}$$
## IV. Comprimento experimental da Polia
$$L = 2C+1,57*(D+d)+\frac{(D-d)^2}{4C})$$
## V. Recalculo da Distância entre Centros (DC)
$$DC=\frac{A-h(D-d)}{2}$$
### A
$$A=Lc-1,57(D+d)$$
### Fator de correção da distância entre centros (h)
$$h=\frac{D-d}{A}$$
O valor encontrato é consultado na tabela

## VI. Potência transmitida por correia (hp)
$$hp = (hpb+hpa)*Fc*Fg$$
## VII. Número de correias (n)
$$n=\frac{HPP}{hp}$$
## VIII. Velocidade periférica da correia (V)
$$V=\frac{D*rpm \, menor}{19.100}(m/s)$$

## Potência Projetada
![[Correias em V]]
$$HPP = 40*1,3=52hp$$

### Diâmetro Maior da Polia
![[Correias em V]]
$$D = 180 * 1,21 = 217,8mm$$

### Distância mínima entre Centros
$$C = 2000 - \frac{180}{2} - \frac{217,8}{2} - 1000 (circulação) = 801,1mm$$ -> 596,7

### Comprimento Experimental da Correia
![[Correias em V]]
$$L = 2 * 596,7 +1,57 * (217,8 + 180)+ (\frac{217,8-180}{4*596,7})$$
$$L=1193,4 + 1,57*397,8+\frac{37,8}{2386,8}$$
$$L=1193,4+624,55+0,02$$
$$L=1817,97mm$$

Modelo: 5V710 -> Lc: 1805mm

![[Correias em V]]
$$A=1805-1,57*(217,8+180)$$
$$A=1805-1,57*397,8$$
$$A=1805-624,55$$
$$A=1180,45$$

$$DC = \frac{A-h(D-d)}{2}$$
$$DC = \frac{1180,45-0,02(217,8-180)}{2}$$
$$DC = \frac{1180,45-0,02(37,8)}{2}$$
$$DC=\frac{1180,45-0,76}{2}$$
$$DC = \frac{1179,69}{2}$$
$$DC = 589,85mm$$

### Potência Transmitida por Correia
$hp = (hpb+hpa)*Fc*Fg$ (Potência transmitida por correia)
$hp = (15,7+1,1)*0,96*1$
$hp=16,8*0,96*1$
$hp=16,13hp$

### Número de Correias

$N=\frac{HPP}{hp}$

$N=\frac{52}{16,13}$

$N=3,22$ -> 3 polias

### Velocidade Periférica da Correia

$V=\frac{d*RPM maior}{19100}$

$V=\frac{180*1750}{19100}$

$V=\frac{315000}{19100}$

$V=16,49m/s$


### Tensão Estática da Correia

$TS=\frac{34*(2,5-Fg)*HPP}{Fg*N*V}+MV^2$

$TS = \frac{34*(2,5-0,96)*52}{0,96*3*16,49}+0,017*16,49^2$


$TS =\frac{34*1,54*52}{47,49}+0,017*271,92$

$TS=\frac{2722,72}{47,49}+4,62$

$TS=57,33+4,62$

$TS=61,95 Kgf$

### Tensão de Deslocamento

$t=Dc[1-0,125(\frac{D-d}{Dc})^2]$

$t=589,85[1-0,125*(\frac{217,8-180}{589,85})^2]$
$t=589,85*[1-0,125*(\frac{37,8}{589,85})^2]$
$t=589,85*(1-0,125*0,06^2)$
$t=589,85*1$
$t=589,85mm$

$Deslocamento = \frac{t}{100}$

$Deslocamento=\frac{589,85}{100}$

$Deslocamento=5,89mm$

### Força Mínima de Deslocamento

$Fmin = \frac{Ts+Y}{25}$

$Fmin = \frac{61,95+2}{25}$

$Fmin = \frac{63,95}{25}$

$Fmin=2,56Kgf$

### Força Máxima de Deslocamento

$Fmax=\frac{1,5*Ts+Y}{25}$
$Fmax=\frac{1,5*61,95+2}{25}$
$Fmax = \frac{92,92+2}{25}$
$Fmax=\frac{94,920}{25}$
$Fmax=3,8Kgf$

#trabalhos/feitos/listas
#### Exercício 2:
Um multiplicador de força de uma empresa de alimentos deve passar por uma manutenção e ter suas correias e rolamentos redimensionados.

- Uso intermediário, em ambiente úmido e poerento
- Relação de Transmissão: 1,6
- Fator de Serviço: 1,3
- Diâmetro da Polia Menor: 100mm
- Centro entre os eixos: 604mm
- Potência Básica: 3,83hp
- Potência Adicional: 0,38hp
- Fator de Correção: 1,04
- Fator de Correção do Arco: 0,93
- Fator de esforços dinâmicos: 3
- Fator de Rotação: 0,405
- Força Radial: 30kN
![](file:///C:/Users/dudum/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

1. Determine a potência projetada por correia:
	$HPP=hp*Fs$
	$HPP = 10 * 1,3$
	$HPP=13hp$

2. Determine a seção adequada:
	Gráfico 1: 1800rpm x 10hp -> Perfil 3V

3. Determine o comprimento experimental:
	$D=d*i$
	$D=100*1,6$
	$D=160mm$

	$L=2C+1,57*(D+d)+\frac{(D-d)^2}{4C}$
	
	$L=2*604+1,57*(160+100)+\frac{(160-100)^2}{4*604}$

	$L=1208+1,57*260+\frac{60^2}{2416}$

	$L=1208+408,2+\frac{3600}{2416}$

	$L=1616,2+1,49$

	$L=1617,69mm$

4. Escolha a correia adequada:
	L=1617,69 -> 1600(tabela) -> Modelo 3V630

5. Determine a distância mínima entre centros
	$A=Lc-1,57(D+d)$
	$A=1600-1,57*(160+100)$
	$A=1600-1,57*260$
	$A=1600-408,2$
	$A=1191,8$

	$h=\frac{D+d}{A}$
	$h=\frac{160+100}{1191,8}$
	$h=\frac{260}{1191,8}$
	$h=0,05$ -> 0,03 (tabela)

	$Dc=\frac{A-h*(D-d)}{2}$

	$Dc=\frac{1191,8-0,03*(160-100)}{2}$
	
	$Dc=\frac{1191,8-0,03*60}{2}$
	
	$Dc=\frac{1191,8-1,8}{2}$
	
	$Dc=\frac{1190}{2}$
	
	$Dc=595mm$

6. Determine a potência transmitida por correia:
	$hp=(hpb+hba)*Fc*Fg$
	$hp=(3,83+0,38)*1,04*0,93$
	$hp=4,21*0,97$
	$hp=4,07hp$

7. Determine o número de correias:
	$N=\frac{HPP}{hp}$
	
	$N=\frac{13}{4,07}$
	
	$N=3,19$ -> 3 Correias




### Exercício em sala
Para um sistema de guindaste é utilizado um sistema de transmissão correias, determine o tipo e a quantidade de correias
- Motor de torque normal
  - 12 HP
  - 1750 rpm
- Fs: 1,6
- hppc: 5,32 (potência projetada por correia)
- L:1525

$HPP=hp*Fs$
$HPP=12*1,6$
$HPP=19,2$

1750 rpm x 12 hp = Modelo 3V
L = 1525 = 3V600

$N=\frac{HPP}{hppc}$

$N=\frac{19,2}{5,32}$

$N=3,6 ≈ 4\;correias$




















































