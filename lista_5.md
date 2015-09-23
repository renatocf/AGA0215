
### **Nome: Renato Cordeiro Ferreira** - NUSP: 7990933

#### A) VERDADEIRO OU FALSO

1. **(V)** Os planos das órbitas da maioria dos planetas estão aproximadamente no mesmo plano da eclítica.
2. **(F)** No nosso sistema solar, os maiores planetas tem as mais altas densidades.
3. **(F)** Vênus e Mercúrio tem velocidades de rotação maiores do que a da Terra.
4. **(F)** No nosso sistema solar, todos os planetas tem Lua.
5. **(F)** No nosso sistema solar, todos os planetas rotam em torno de seu eixo no mesmo sentido.
6. **(V)** Excentricidade é o grau de elipticidade de uma órbita.
7. **(V)** Todos os planetas jovianos possuem anéis.
8. **(F)** Na formação do nosso sistema solar, o tempo desde a contração da nuvem de gás até formação do protosol é em torno de 1 século.
9. **(V)** Usando o modelo padrão de formação do sistema solar, deve-se usar também a possibilidade de eventos randômicos para explicar a posição do eixo de rotação de Urano.
10. **(F)** Um planeta na zona habitável significa que tem oxigênio em sua atmosfera. 

#### B) PREENCHER O QUE FALTA

1. O __cinturão de asteroides__ é formado por pequenos corpos que giram ao redor do Sol entre as órbitas de Marte e Júpiter.
2. Os planetas internos Mercúrio, Vênus, Terra e Marte são conhecidos como planetas __telúricos__.
3. Dentre os 8 planetas o de maior excentricidade orbital é __Mercúrio__.
4. Asteroides possuem uma composição química semelhante a de planetas __terrestres__.
5. Os cometas possuem três partes principais: __núcleo__, __coma__ e __cauda__.
6. Observando a figura do slide 15, a maior parte dos exoplanetas oficiais são __massivos e frios__ (massivos/leves e frios/quentes).
7. A zona habitável de uma estrela duas vezes mais massiva do que o Sol está na distância de __2__ UA da estrela.

#### C) PROBLEMAS

**1) A maior aproximação de um asteroide do Sol (periélio) é de 2 UA, e a sua maior distância (afélio) é de 4 UA. Qual o semieixo maior, período e excentricidade de sua órbita?**

O afélio e periélio de uma órbita excêntrica é dada por:
```
D_per = a(1-e)
D_af  = a(1+e)
```
Com `a` o tamanho do semieixo maior e `e` a excentricidade. Podemos calcular ambos os valores equacionando:
```
4 = a(1+e)
2 = a(1-e)

4/2 = (a(1+e))/(a(1-e))
→ 2 = (1+e)/(1-e)
→ 2(1-e) = 1+e
→ 2-2e = 1+e
→ (2-1) = (e+2e)
→ 1 = 3e
∴ e = 1/3

2 = a(1-e) = a(1-1/3) = a(2/3) = 2a/3
→ 1 = a/3
∴ a = 3
```
Logo, o semieixo maior `a` tem 3 UA e a excentricidade `e` é 1/3.

Para calcularmos o período da órbita utilizando a 3ª lei de Kepler deduzida pela lei da gravitação universal de Newton:
```
a³/T² = G(M⊙+m)/4π²
```
Com `a` o semieixo maior, `T` o período, `G` a constante gravitacional do nosso Sol, `M⊙` a massa do Sol e `m` a massa do cometa. Como `M⊙ >> m`, podemos aproximar a equação para:
```
a³/T² = GM⊙/4π²
```
Assim, tomando `G = 4π² AU³ year⁻² M⊙⁻¹`:
```
T²/a³ = 4π²/GM⊙
→ T² = 4π²a³/GM⊙
→ T  = √(4π²a³/GM⊙)
→ T  = √((4π²*3³)/(4π²/M⊙)M⊙)
→ T  = √(4π²*27)/4π²
→ T  = √27
∴ T  = 5.1961 anos
```
Logo, o período orbital do cometa é de aproximadamente 5.2 anos.

**2) O cometa Halley tem um período orbital de 76 anos, e seu afélio é de 35.3 UA. Quanto o cometa chegará próximo ao Sol? Como isso se compara à distância da Terra ao Sol? Qual é a sua excentricidade orbital?**

Consideremos que o período orbital `T` do cometa Halley seja de 76 anos, e que seu afélio `D_af` tenha 35.3 UA. Podemos calcular o semieixo maior `a` a partir da 3ª lei de Kepler deduzida a partir da lei da gravitação de Newton:
```
a³/T² = G(M⊙+m)/4π²
```
Com `a` o semieixo maior, `T` o período, `G` a constante gravitacional do nosso Sol, `M⊙` a massa do Sol e `m` a massa do cometa. Como `M⊙ >> m`, podemos aproximar a equação para:
```
a³/T² = GM⊙/4π²
```
Assim, tomando `G = 4π² AU³ year⁻² M⊙⁻¹`:
```
a³/T² = GM⊙/4π²
→ a³ = T²GM⊙/4π²
→ a  = ∛(T²GM⊙/4π²)
→ a  = ∛((76²(4π²/M⊙)M⊙)/4π²)
→ a  = ∛((76²4π²)/4π²)
→ a  = ∛(76²)
∴ a  = 17.9422 UA ≅ 18 UA
```
A partir desse valor e do afélio, podemos calcular a excentricidade orbital:
```
D_af = a(1+e)
→ e = (D_af/a) - 1
→ e ≅ 35.3/17.94 - 1 ≅ 1.967 - 1 = 0.967
```
Com a excentricidade, obtemos o periélio:
```
D_per = a(1-e) ≅ 17.942(1-0.967) ≅ 0.592 UA
```
Que é a máxima aproximação do cometa Halley ao Sol, totalizando aproximadamente 60% da distância da Terra ao Sol.

**3) Um planeta tipo Júpiter quente orbita uma estrela de massa 0,5M⊙ com um período de 4 dias. Qual a sua distância da estrela?**

Consideremos o período `T` da órbita de um planeta tipo Júpiter quente seja 4 dias, e a massa `M` da estrela em que ele orbita como sendo 0.5M⊙. Podemos calcular o semieixo maior `a` a partir da 3ª lei de Kepler deduzida a partir da lei da gravitação de Newton:
```
a³/T² = G(M+m)/4π²
```
Com `a` o semieixo maior, `T` o período, `G` a constante gravitacional do nosso Sol, `M` a massa da estrela e `m` a massa do planeta. Como, em geral, `M >> m`, podemos aproximar a equação para:
```
a³/T² = GM/4π²
```
Assim, tomando `M = 0.5M⊙` e `G = 4π² AU³ year⁻² M⊙⁻¹`:
```
a³/T² = G(0.5M⊙)/4π²
→ a³ = T²G(0.5M⊙)/4π²
→ a  = ∛(T²G(0.5M⊙)/4π²)
→ a  = ∛(((4/365)²*(4π²/M⊙)*(0.5M⊙))/4π²)
→ a  = ∛(((4/365)²*4π²*0.5)/4π²)
→ a  = ∛((4/365)²0.5)
∴ a  = 0.039 UA
```
Logo, o planeta está no máximo a 0.039 UA da sua estrela.

**4) Dois planetas que orbitam a estrela Gliese 876 estão numa ressonância de 2:1 (isto é, o período de um é duas vezes o do outro). O planeta interno possui um período orbital de 30 dias. Se a massa da estrela é ~ 1 M⊙, calcular o semieixo maior do planeta mais externo.**

Consideremos o período `T1` e `T2` de dois planetas que orbitam a estrela Gliese 876, tais que `T2 = 2*T1`. Consideremos que o período orbital do planeta mais interno seja `T1 = 30 dias` e que a massa do Gliese 876 seja aproximadamente a massa do Sol. Considerando que o sistema solar tem condições similares aos do nosso sistema solar (constante gravitacionais similares), podemos calcular o semieixo maior `a1` do planeta mais interno a partir da 3ª lei de Kepler deduzida a partir da lei da gravitação de Newton:
```
a³/T² = G(M⊙+m)/4π²
```
Com `a` o semieixo maior, `T` o período, `G` a constante gravitacional do nosso Sol, `M` a massa da estrela e `m` a massa do planeta. Como, em geral, `M >> m`, podemos aproximar a equação para:
```
a³/T² = GM⊙/4π²
```
Assim, tomando `G = 4π² AU³ year⁻² M⊙⁻¹`:
```
a1³/T1² = G(0.5M⊙)/4π²
→ a1³ = T1²GM⊙/4π²
→ a1  = ∛(T1²GM⊙/4π²)
→ a1  = ∛(((30/365)²(4π²/M⊙)M⊙)/4π²)
→ a1  = ∛(((30/365)²4π²)/4π²)
→ a1  = ∛(30/365)²
∴ a1  ≅ 0.189 UA
```
Logo, o semieixo maior do planeta mais interno é aproximadamente 0.189 UA.

Considerando, agora, que como no nosso sistema solar todos os planetas tenham a mesma proporção entre semieixos maiores e períodos, podemos aplicar a 3ª lei de Kepler para encontrar o tamanho do semieixo maior do planeta mais externo:
```
a1³/T1² = a2³/T2²
→ 0.189³/T1² = a2³/(2T1)²
→ 0.189³/T1² = a2³/(2T1)²
→ a2³ = (0.189³*2²*T1²)/T1²
→ a2³ = 0.189³ * 4
→ a2  = ∛(0.189³ * 4)
→ a2  = 0.189 * ∛4
→ a2  ≅ 0.189 * 1.58
∴ a2  ≅ 0.29862 UA
```
Logo, o semieixo maior do planeta mais externo é aproximadamente 0.29862 UA.

**5) Uma variação de cerca de 1m/s na velocidade radial de uma estrela pode ser detectada com a tecnologia atual. Para um planeta da massa de Júpiter, que orbita uma estrela semelhante ao Sol, isso corresponde a uma velocidade orbital de ~ 1 km/s. Baseado nesta informação, qual o limite superior do raio de uma órbita circular no qual Júpiter poderia ser detectado orbitando o Sol?**

Consideremos um planeta com tamanho próximo ao de Júpiter orbitando uma estrela similar ao Sol. A força centrípeta que mantém o planeta em órbita é a força gravitacional exercida entre a estrela e o planeta. Temos então:
```
mV_orb²/r = GmM/r²
```
Com `m` a massa do planeta, `M` a massa do planeta, `V_orb` a velocidade orbital do planeta, `r` a distância estrela-planeta e `G` a constante gravitacional do sistema solar. Simplificando a equação:
```
V_orb² = GM/r → r = GM/V_orb²
```
Substituindo `G = 6.67408 * 10^-11 m³ kg⁻¹ s⁻²`, `M⊙ = 1.989 * 10^30 kg` e `V_orb = 1000 m/s`, temos:
```
r = GM/V_orb² = (6.67408 * 10^-11) * (1.989 * 10^30) / (10^3)^2
→ r ≅ 6.67408 * 1.989 * 10^13
→ r ≅ 1.327474512 * 10^14 m
→ r = 887.3618 AU
```
Logo, Júpiter seria detectável (pela tecnologia atual) em até aproximadamente 887.36 UA do Sol.

**6) Estime a massa do planeta (em unidades de massa de Júpiter) que orbita em torno da estrela 51 Pegasi do slide 8.**

Consideremos um planeta tipo Júpiter que orbita em torno da estrela 51 Pegasi, cuja massa `M ≅ M⊙` e a velocidade radial é de `50 m/s`. Se a órbita desse planeta é aproximadamente circular, podemos obter o raio (semieixo maior) 3ª lei de Kepler deduzida a partir da lei da gravitação de Newton:
```
a³/T² = G(M⊙+m)/4π²
```
Com `r = a` o semieixo maior, `T` o período, `G` a constante gravitacional do nosso Sol, `M = M⊙` a massa da estrela e `m` a massa do planeta. Como, em geral, `M >> m`, podemos aproximar a equação para:
```
a³/T² = GM⊙/4π²
```
Tomando `G = 4π² AU³ year⁻² M⊙⁻¹`:
```
r³/T² = GM⊙/4π²
→ r³ = T²GM⊙/4π²
→ r  = ∛(T²GM⊙/4π²)
→ r  = ∛(((4.2/365)²(4π²/M⊙)M⊙)/4π²)
→ r  = ∛(((4.2/365)²4π²)/4π²)
→ r  = ∛((4.2/365)²)
∴ r  = 0.05096 UA ≅ 7.623 * 10^9 m
```
Podemos calcular a velocidade orbital do planeta utilizando a lei da gravitação de Newton. Igualando a força gravitacional à centrípeta:
```
mV_orb²/r = GmM/r²
```
Com `m` a massa do planeta, `M` a massa da estrela, `V_orb` a velocidade orbital do planeta, `r` a distância estrela-planeta e `G` a constante gravitacional do sistema solar. Simplificando a equação:
```
V_orb² = GM/r
```
Substituindo `G = 6.67408 * 10^-11 m³ kg⁻¹ s⁻²`, `M ≅ M⊙ = 1.989 * 10^30 kg` e `r ≅ 7.623 * 10^9 m`, temos:
```
V_orb² = GM/r = (6.67408 * 10^-11) * (1.989 * 10^30) / (7.623 * 10^9) = 1.742 * 10^10 
∴ V_orb = √(1.742 * 10^10) ≅ 1.32 * 10^5 m/s
```
Considerando que existe conservação do momentum linear na variação da velocidade radial das estrelas, vale que:
```
M_estrela * V_estrela = M_planeta * V_planeta
→ M⊙ * V_rad = m * V_orb
→ m = (M⊙ * V_rad) / V_orb
→ m = (1.989 * 10^30 * 50) / (1.32 * 10^5)
→ m = (1.989 * 5) / (1.32) * 10^26 ≅ 7.534 * 10^26 kg
→ m = 0.397 M♃
```
Logo, a massa do planeta orbitando em torno do 51 Pegasi é aproximadamente 0.397 M♃ (40% da massa de Júpiter).