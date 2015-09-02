
### **Nome: Renato Cordeiro Ferreira** - NUSP: 7990933

#### A) Preencher o que falta

1. Quando um planeta apresenta movimento __retrógado__, ele aparenta se mover para oeste durante algumas semanas.
2. Como o Sol e a Lua, na maior parte das vezes os planetas apresentam um movimento de __oeste-leste__ (direção) de um dia pro outro.
3. As observações de Galileu das __manchas solares__ provou que o Sol estava em rotação em torno de seu próprio eixo.
4. Nos séculos XVIII e XIX, os trânsitos raros de __Vênus__ foram usados para se determinar a UA.
5. Kepler derivou suas leis a partir das observações planetárias de __Tycho Brahe__.
6. A excentricidade de uma órbita perfeitamente circular é __0__.
7. Um planeta ou um cometa deverá __acelerar__ sua velocidade quando se aproxima do Sol.
8. Quando a massa de um corpo é dobrada, sua gravidade fica __duas vezes__ mais intensa.
9. De acordo com a 2ª lei de Newton, quando a mesma força atua em dois corpos, o corpo de maior massa possui a __menor__ aceleração.
10. De acordo com Newton, a gravidade do __Sol__ é necessária para explicar as órbitas dos planetas do sistema solar.
11. As modificações de Newton nas leis de Kepler permite estimar as __distâncias__ dos planetas se satélites estiverem orbitando em torno deles.
12. Um eclipse do Sol não ocorre toda a Lua nova porque __existe uma diferença de 5.2º entre a órbita da Lua em torno da Terra e a órbita da Terra em torno do Sol (eclíptica)__.
13. Existe uma face da Lua que nunca vemos pois a mesma __apresenta movimento síncrono em torno da Terra__.
14. O eclipse do Sol só pode ocorrer durante a Lua __nova__.
15. Considerando a elipticidade da órbita da Terra, o ponto em que a mesma se aproxima mais do Sol se chama __periélio__.

#### B) Problemas
**1) Suponha que um observador esteja na Lua, e olha para a Terra e vê ela em fase cheia. Qual a fase lunar que as pessoas observariam na Terra? E nas outras fases, Terra nova, crescente e minguante? Faça um desenho mostrando a geometria.**

A fase cheia ocorre quando um astro (como a Terra) se encontra na direção diametralmente oposta ao Sol em relação ao astro em que se encontra o observador (no caso, a Lua). A diferença entre a observação na Terra e na Lua pode ser descrita pela seguinte tabela:

  Fase |   Terra   |    Lua    |
-------|-----------|-----------|
   A   | Nova      | Cheia     |
   B   | Crescente | Minguante |
   C   | Cheia     | Nova      |
   D   | Minguante | Crescente |

**Fase A**
```
 .
  \
 S \                .   
 O	|             .` `.      ()
 L /               `.`    Lua cheia
  /             Terra nova
 '
```
**Fase B**
```
 .
  \
 S \                .   
 O	|             .` `.
 L /               `.`    
  /           Terra crescente
 '
                   ()
               Lua minguante
```
**Fase C**
```
 .
  \
 S \                .   
 O	|      ()     .` `.
 L /    Lua nova   `.`
  /            Terra cheia
 '
```
**Fase D**
```
                    ()
 .             Lua crescente
  \
 S \                .   
 O	|             .` `.
 L /               `.`    
  /           Terra minguante
 '
```

**2) Quantos graus (º), minutos de arco (’) e segundos de arco(”) a lua se move no céu em 1 hora? Quanto tempo leva a lua para se mover no céu uma distância igual ao seu próprio diâmetro (diâmetro angular da lua ~ 30’)?(dia lunar = 24h50min28s).**

Considerando que 1 dia lunar `= 24h50min28s = 89,428s` e `360º = 126900"`, temos:
```
360º = 126900" ----- 24h50min28s = 89,428s
      x        -----         3600s
→ x = 52171.58" ≅ 14º29'31"
```
Assim, a Lua se move `14º29'31"` em 1h.

Para que a Lua se mova ~30' no céu (seu diâmetro angular), temos:
```
360º = 126900" ----- 24h50min28s = 89,428s
 30' = 1800"   -----         xs
→ x = 124.20" ≅ 2 min 4.2 s
```
Assim, a Lua demora `2 min 4.2 s` para se mover ~301 no céu.

**3) Compare a força de maré exercida sobre a Terra por Júpiter e pelo Sol.**



**4) Qual é a velocidade orbital do Space Shuttle na órbita terrestre baixa (300 km acima da superfície terrestre)?**

Se um ônibus espacial está em órbita baixa ao redor da Terra, então a força centrípeta aplicada sobre a espaçonave é igual à força gravitacional aplicada sobre ele:
```
mv²/r = GmM/r² → v = √(GM/r)
```
Tomando `r = 6371km + 300km = 6.671 * 10^6 m` o raio orbital do ônibus espacial, `G = 6.67 * 10^-11 N m^2/kg^2` a constante de gravitação em torno do Sol e `M = 5.972 × 10^24 kg` a massa da Terra, obtemos:
```
v = √(GM/r) = √((6.67 * 10^-11 * 5,972 × 10^24)/(6.671 * 10^6)) → v ≅ 7727.29 m/s ≅ 7.72729 km/s
```

**5) Se alguém pesa 56 kgf na Terra, quantos kgf pesará em Marte?**

Considerando que a aceleração da gravidade na Terra seja ~10m/s², podemos deduzir o peso de uma pessoa com 56 kgf na Terra como sendo:
```
a_Terra = 1 kgf/kg ------- 10 m/s²
a_Marte = x kgf/kg ------- 3,7 m/s²
→ a_Marte = 0.37 kgf/kg

P_Terra = m * g
56 kgf = m * 1 kgf/kg
→ m = 56 kg

P_Marte = m * g
P_Marte = 56 kg * 0.37 kgf/kg
→ P_Marte = 20.72 kgf
```

**6) Qual é o valor máximo da força gravitacional exercida na Terra por Júpiter? Considere as aproximações Terra-Júpiter que ocorrem no periélio e afélio (qual destas aproximações ocorre o valor máximo da força gravitacional?).**

Segundo a equação da gravitação universal de Newton, a força de atração entre dois corpos diminui com o quadrado da distância entre seus centros de massa. Por esse motivo, a atração entre a Terra e Júpiter será maior durante o periélio.

Considerando a distância Terra-Júpiter no periélio como sendo`d = 5.88 * 10^8 km = 5.88 * 10^11 m`,  `G = 6.67 * 10^-11 N m^2/kg^2` a constante de gravitação em torno do Sol, `m = 5.972 × 10^24 kg` a massa da Terra, `M = 1.898 × 10^27 kg` a massa da Júpiter, temos:
```
F = GmM/r² = (6.67 * 10^-11 * 5.972 × 10^24 *  1.898 × 10^27)/(5.88 * 10^8)²
→ F ≅ 2.1866 * 10^24
```

**8) Estimar a massa do Sol usando a 3ª lei de Kepler rederivada por Newton.**

Para calcular a massa do Sol, podemos utilizar a 3ª lei de Kepler rederivada por Newton: `M_sol = (4*π²/G)*(a³/P²)`.

Considerando `a = 1 UA ≅ 149597870700m = 1.5 * 10^11m` a distância Terra-Sol, e `P = 1 ano terrestre ≅ 31536000s = 3.15*10^7s` o período de rotação da Terra, obtemos:
```
M_sol = (4*π²/(6.67*10^-11))*((3.375*10^33)/(9.9225*10^14)) ≅ 2*10^30 kg
```

**10) Qual a velocidade mínima requerida para a Apolo 11 deixar a Terra (km/s)?**

Se a nave Apollo 11, a energia cinética requerida para escapar da Terra (chegar com velocidade 0 no infinito) será
```
mv²/2 = GmM/r → v = √(2GM/r)
```
Tomando `r = 6371km = 6.671 * 10^6 m` o raio da Terra, `G = 6.67 * 10^-11 N m^2/kg^2` a constante de gravitação em torno do Sol e `M = 5.972 × 10^24 kg` a massa da Terra, obtemos:
```
v = √(2GM/r) = √((2 * 6.67 * 10^-11 * 5,972 × 10^24)/(6.371 * 10^6)) → v ≅ 11182.4 m/s ≅ 11.182 km/s
```

**11) A massa da lua é 7,4x10^22 kg e seu raio é 1700 km. Qual é a velocidade de uma nave que se move em órbita circular imediatamente acima da superfície lunar? Qual é a velocidade de escape da lua (km/s)?**

Podemos calcular a velocidade orbital e de escape de uma nave imediatamente acima da superfície lunar como sendo:
```
(m*v_orb²)/r = GmM/r² → v_orb = √(GM/r)
(m*v_esc²)/2 = GmM/r → v_esc = √(2GM/r) ≅ √2 * v_orb
```
Tomando `r = 1700 km = 1.7 * 10^6 m` o raio da Terra, `G = 6.67 * 10^-11 N m^2/kg^2` a constante de gravitação em torno do Sol e `M = 7.4 * 10^22 kg` a massa da Terra, obtemos:
```
v_orb = √(GM/r) = √((6.67 * 10^-11 * 7.4 * 10^22)/(1.7 * 10^6)) → v ≅ 1703.94 m/s ≅ 1.703 km/s
v_esc = √2 * 1.703 = 2.40841 km/s
```

