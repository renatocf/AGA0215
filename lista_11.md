
### **Nome: Renato Cordeiro Ferreira** - NUSP: 7990933

#### A) Falso ou verdadeiro

01. **(V)** Os aglomerados globulares pertencem ao disco da Galáxia.
02. **(V)** RR Lyrae é um tipo de variável pulsante.
03. **(F)** O halo da Galáxia contém gás e poeira em quantidade suficiente para formar estrelas.
04. **(V)** O halo da Galáxia contém somente estrelas velhas.
05. **(V)** Até os anos 30, as observações feitas no visível não levavam em conta a absorção da luz pelo meio interestelar. Por isso a extensão do disco foi estimada como sendo menor.
06. **(F)** O bojo contém mais estrelas jovens do que velhas.
07. **(V)** O disco é formado após o halo da Galáxia.
08. **(V)** Os braços de espiral são regiões especiais do disco nas quais ocorre a formação de estrelas.
09. **(F)** A curva de rotação da Galáxia é um indicativo de que a mesma rota como um corpo sólido.
10. **(V)** Observações do bojo no infravermelho e rádio faz com que consiga-se estudar regiões
mais profundas.
11. **(V)** Janelas de Baade são regiões do disco localizadas da direção do centro da Galáxia
onde o meio interestelar é mais tênue.
12. **(V)** São observadas nebulosas de emissão próximo ao centro da Galáxia.
13. **(F)** No centro da galáxia é observado baixa atividade energética. 

#### B) Completar o que falta

01. A grande dificuldade em estudar a estrutura em larga escala da nossa Galáxia é o fato de que __estamos dentro dela__.
02. A parte altamente achatada e mais ou menos circular da nossa Galáxia chama-se __disco__.
03. A região aproximadamente esférica e composta por estrelas fracas e aglomerados globulares, e na qual a Galáxia encontra-se imersa, chama-se __halo__.
04. Cefeidas e RR Lyrae são observadas variando em __luminosidade ou brilho__ com períodos de horas a dias.
05. Cefeidas e RR Lyrae encontram-se na região do diagrama HR denominada __faixa de instabilidade__.
06. De acordo com a relação período-luminosidade das Cefeidas, quando maior o período de pulsação __maior__ a luminosidade.
07. Estrelas e gás no disco Galáctico movem-se em órbitas __aproximadamente elípticas ao longo do plano galáctico__.
08. A componente da Galáxia que contém mais regiões de formação estelar é o __disco__.
09. As estrelas do halo da Galáxia movem-se em órbitas __órbitas randômicas em 3 dimensões__.
10. A localização do nosso sistema solar dentro do disco da galáxia é __periférica__.
11. Sgr A* é um candidato a __buraco negro__.
12. A curva de rotação da Galáxia indica a presença de __matéria escura__.

#### Problemas

**01. Um astrônomo observando no HST pode ver uma estrela de luminosidade solar a uma distância de 100 kpc. As mais brilhantes Cefeidas possuem luminosidades de cerca de 30.000 vezes a luminosidade do Sol. Considerando a magnitude absoluta do Sol como sendo de +5, calcular a magnitude absoluta destas Cefeidas brilhantes. Desprezando a absorção interestelar, o quão longe estas Cefeidas podem ser vistas pelo HST?**

A magnitude absoluta dessas Cefeidas brilhantes é dada por:

```
Mc - M☉ = -2.5 * log(Lc/L☉)
Mc - 5 = -2.5 * log((3*10^4*L☉)/L☉)
Mc = 5 - 2.5 * log(3*10^4)
Mc = 5 - 2.5 * log(3*10^4)
Mc = 5 - 2.5 * (log 3 + log 10^4)
Mc = 5 - 2.5 * (0.47712125472 + 4)
Mc = -6.1928031368
```
Logo, a magnitude das Cefeidas brilhantes é de aproximadamente -6.2.

**02. Qual é a distância máxima na qual o HST pode ver a Cefeida da questão anterior se ela estiver no disco da Galáxia que possui uma extinção interestelar média de 2,5 mag por kpc?**

**03. A região do nosso sistema solar está rotando ao redor do centro da galáxia com uma velocidade orbital estimada de 220 km/s. Sabendo que a distância do Sol ao centro da Galáxia é de 8 kpc, quanto tempo o nosso sistema solar leva para dar uma volta completa em torno do centro (em anos)?**

Assumindo uma órbita aproximadamente circular de rotação do sistema solar em torno do centro da galáxia, temos:que a distância percorrida pelo sistema solar é dado por:
```
D = 2πR = 2 * 3.14159265 * (8 * 3.08567758 * 10^16)
∴ D = 1.55103072 * 10^18 km
```
Considerando o tempo como sendo o produto da velocidade e distância, temos:
```
t = D / v_ss = 1.55103072 * 10^18 / 220 = 7.05013964 * 10^15s
∴ t = 223,410,216 anos
```

Logo, o sistema solar demora aproximadamente 223,410,216 anos para rodar em torno do centro da galáxia.

**04. Na figura abaixo é mostrada uma imagem no infravermelho em altíssima resolução (0,1 pc de tamanho) do centro da Galáxia, onde se pode observar estrelas individuais e suas órbitas. A curva sólida da segunda figura mostra a órbita elíptica que melhor ajusta as observações do movimento da estrela S2 ao redor de SgrA*: uma órbita de período de 15 anos com um semi-eixo maior de 950 UA. Qual é a massa estimada (em M☉) do objeto localizado em SgrA*?**

Podemos relacionar o semi-eixo maior (em UA), o período orbital (em anos terrestres) e a massa de dois objetos em rotação um com relação ao outro por meio da 3ª Lei de Kepler corrigida por Newton:
```
T²/a³ = 4π²/G(M+m)
```
Com `m` a massa da estrela e `M` a massa de SgrA\*. Como SgrA\* é um candidato a buraco negro, podemos reescrever a equação para:
```
T²/a³ = 4π²/GM
```
Com `T = 15 anos`, `a = 950 UA`, `G =  4π^2 AU^3 yr^-2 M☉^-1`. Temos então:
```
15^2/950^3 = 4π²/(4π²*M)
→ 15^2/950^3 = 1/M
→ 950^3/15^2 = M
∴ M = 3,810,555.56
```
Logo, a massa do possível buraco negro é de aproximadamente 4 milhões de massas solares;