---
tag: Usinagem, tipos de usinagem
aliases: usinagem, tipos de usinagem, CNC
---

Processo de remoção de material em forma de cavaco

## Convencional
 - Torneamento
 - Fresamento
 - Lixamento
 - Furação
 - Retificação
 - Mandrilhamento
 - Aplainamento

## Não Convencional
 - Jato d'água
 - Corte lazer
 - Corte plasma
 - Corte por feixe de elétrons
 - Eletro erosão
 - Corte eletroquímico

## Ferramentas
- Elevada [[Conhecimento Técnico/Propriedades Mecânicas|dureza]] a frio e a quente - Superior a da peça
- [[Conhecimento Técnico/Propriedades Mecânicas|Tenacidade]] para resistir a esforço de corte e impacto
- Resistência a abrasão
- Disponibilidade no mercado
- Custo
- Estabilidade química

### Materiais para ferramentas
- Aço carbono
- Aço rápido comum
- Aço rápido cobalto
- Ligas fundidas
- Metais duros
- Cermentos ou compósitos
- Cerâmicas
- Diamantes
- Nitreto de boo cúbico (CBN)

### Geometria da ferramenta
- Influência
	- Cavaco
	- Saída do cavaco
	- Força de corte
	- Desgaste da ferramenta
	- Qualidade da peça 
	
## Meteriais para usinagem
- ISO P - Aço
- ISO M - Aço inoxidável
	- Mínimo 12% de cromo
	- Ligas níquel molibdênio
- ISO K - Ferro fundido
	- Cavacos curtos
	- São frágeis para usinar
- ISO S - Ligas resistentes ao calor
	- Meterial pastoso
	- Dificíl usinagem
	- Pouca vida útil da ferramenta
- ISO H - Aços endurecidos
	- Aços de 45 a 55 HRc
	- Ferro fundido de #complete  
	
## Operações
### Desbaste
  - Conferir formas e dimensões próximas as finais

### Acabamento
  - Obter dimensões e formas finais

### Movimentos
- Corte
	- Entre a peça e a aresta de corte
- Avanço
	- Entre a peça e a aresta de corte
- Efetivo
	- Resultado do movimento simultâneo de corte e de avanço

### Percursos
- Corte (Lc)
	- Espaço percorrido pelo ponto de referência da aresta de corte sobre a aresta cortante
- Percurso de avanço (Lf)

### Velocidades
#### Corte (Vc)
 -  Velocidade do ponto de referência da aresta segundo a direção do corte

$$Vc=\frac{\pi*d*RPM}{1.000}$$

#### Velocidade de avanço ($V_f$)
$$V_f=f*RPM=f*\frac{1.000*Vc}{\pi*d}$$

f = Avanço (mm por rotação)

#### Velocidade efetiva de corte ($V_e$)
$$\vec{V_e}=\vec{V_c}+\vec{V_f}$$
$$V_e^2=V_c^2+V_c^2$$

#### Tempo de corte ($T_c$)
$$T_c=\frac{l_f}{V_f}=\frac{\pi*d*l_f}{1.000*f*V_c}$$
$l_f$ = Percurso de corte

#### Área da seção transversal do cavaco
$$A=a_p*f$$
$a_p$ = profundidade ou largura da usinagem (mm)
	- Perpendicular ao plano de trabalho

#### Rotação (RPM)
$$RPM = \frac{V_c*1.000}{\pi*D}$$

# Exercício 1
D = 150 mm
n = 1.200 RPM
f = 0,5 mm/rot
Torneamento

$$Vc=\frac{\pi*150*1.200}{1.000}=\frac{565.486}{1.000}$$
$$Vc=565 \, m/min$$
---
$$V_f=0,5*1.200$$
$$V_f=600 \, mm/min$$
$$V_f=\frac{600}{1.000}=0,6 \, m/min$$
---
$$V_e^2=565^2+0,6^2$$
$$V_e=\sqrt{319.225}=565 \, m/min$$

# Exercício 2
$D_{broca}$ = 3/4" -> 19,05 mm
n = 800 RPM
f = 1 mm/rot
Furação
$$Vc=\frac{\pi*19,05*800}{1.000}=\frac{47.877}{1.000}$$
$$Vc=47,8 \, m/min$$
---
$$V_f=1*800$$
$$V_f=800 \, mm/min$$
$$V_f=\frac{800}{1.000}=0,8 \, m/min$$
---
$$V_e^2=47,8^2+0,8^2$$
$$V_e=\sqrt{2.285}=47,8$$

# Exercício 3
$l_f$ = 50 mm
D = 80 mm
$V_c$ = 32 m/mm
f = 0,8 mm/rot
$a_p$ = 3 mm
RPM disponível = 70, 100, 120, 150, 175, 200
$T_c$ = 

$$RPM = \frac{32*1.000}{\pi*80}$$
$$RPM = \frac{32.000}{25,133}=1.273 \, rpm$$
-> Não disponível - Corrigir 

---
$$V_f=0,8*1.273$$
$$V_f=1.018 \, m/min$$
---
$$T_c=\frac{\pi*80*50}{1.000*0,8*32}$$
$$T_c=\frac{12.566}{25.600}=:::::$$
-> 5,4 min

