
### **Nome: Renato Cordeiro Ferreira** - NUSP: 7990933

#### A) VERDADEIRO OU FALSO

01. **(F)** A luz do sol é absorvida pela superfície da Terra e reemitida sob forma de radiação UV.
02. **(V)** O campo magnético da Terra se originou do seu núcleo externo de ferro metálico.
03. **(F)** A temperatura média em Vênus é menor do que em Mercúrio.
04. **(F)** Crateras como as da Lua foram formadas por atividades vulcânicas.
05. **(V)** Vênus possui movimento de rotação retrógrado em torno do seu próprio eixo.
06. **(V)** A poeira presente na atmosfera de Marte é o que dá o seu tom avermelhado.
07. **(F)** Marte observada da Terra apresenta fases como Vênus.
08. **(V)** Phobos e Deimos são provavelmente núcleos de cometa capturados por Marte.
09. **(V)** Júpiter tem aproximadamente 2  a massa de todos os outros planetas do sistema solar combinados.
10. **(V)** Júpiter irradia no espaço cerca de 2  a energia que recebe do Sol.
11. **(V)** Se Júpiter tivesse o suficiente de massa se tornaria uma estrela.
12. **(F)** Os anéis de Júpiter são formados por pedras de gelo.
13. **(F)** Saturno é o único planeta a possuir anéis.
14. **(V)** Urano e Netuno são similares em massa e tamanho.
15. **(F)** As inclinações dos eixos de rotação de Júpiter e Saturno são similares.
16. **(V)** Os anéis sempre são aproximadamente perpendiculares ao eixo de rotação do planeta.

#### B) COMPLETAR O QUE FALTA

1. Um dia em Mercúrio (nascer e por do Sol) equivale a __2/3__ (número) órbita(s) completa(s) sua em torno do Sol.
2. A pressão atmosférica em Vênus é __maior__ (maior/menor) do que a pressão atmosférica na Terra.
3. A temperatura média de Vênus é __maior__ (maior/menor) do que em Mercúrio por causa do __efeito estufa__.
4. Albedo é o grau de __reflexão__ da luz na superfície de um planeta.
5. O hemisfério mais jovem de Marte é o __norte__.
6. A grande mancha vermelha em Júpiter corresponde a um __ciclone__.
7. O satélite que possui maior probabilidade de existência de vida chama-se __Europa__ e é um satélite de __Júpiter__.
8. O único satélite que possui atmosfera mais densa do que a da Terra é __Titã__e é um satélite de __Saturno__.
9. O maior satélite do sistema solar chama-se __Ganymedes__ e é um satélite de __Júpiter__.
10. O planeta menos denso do sistema solar é __Saturno__.
11. Os núcleos dos planetas internos contêm __Fe e Ni__ e os dos planetas externos contêm __H e He__.
12. Os anéis de Urano e Netuno são formados principalmente por __gelo__.

#### C) PROBLEMAS

**1. Comparar o espalhamento relativo da luz azul (400 nm) e da luz vermelha (800 nm) por moléculas e por poeira.**

O espalhamento de uma dada frequência de luz por moléculas é causado pelo espalhamento Rayleigh, e é proporcional a 1/λ⁴ (λ o comprimento da onda). Dessa maneira, o espalhamento da luz azul E\_azul ∝ 1/λ⁴ = 1/400⁴ e o espalhamento da luz vermelha E\_vermelha ∝ 1/800⁴ = 1/(2⁴ * 400⁴) = 1/2⁴ * 1/400⁴ = 1/16 * Ε_azul. Logo, o E\_azul = 16 * E\_vermelha.

O espalhamento de uma dada frequência de luz por poeira, por sua vez, é proporcional a 1/λ (λ o comprimento da onda). Assim, o espalhamento da luz azul E\_azul ∝ 1/λ = 1/400 e o espalhamento da luz vermelha E\_vermelha ∝ 1/800 = 1/(2 * 400) = 1/2 * 1/400 = 1/16 * Ε_azul. Logo, o E\_azul = 2 * E\_vermelha.

**2. Qual o diâmetro angular do Sol visto de Mercúrio no seu afélio e no seu periélio?**

Podemos calcular o diâmetro do Sol utilizando a seguinte equação:
```
φ = 2arctag(r/D)
```
Sendo `r` o raio do planeta e `D` o diâmetro. Como r >> D, podemos aproximar o ângulo sem o arcotangente :
```
φ = 2*(r/D) = 2*((d/2)/D) = 2*(d/2D) = d/D
```
Com `d` sendo o diâmetro do planeta. Podemos calcular, então, a distância do afélio e do periélio:
```
D_af  = (1+e)*a = (1+0.206)*0.387 = 0.466722 UA
D_per = (1-e)*a = (1-0.206)*0.387 = 0.307278 UA
```
E, por fim, calcular o diâmetro angular:
```
φ_af  = d⊙/D⊙-☿_af  = 0.009304/0.466722 = 0.01993477916 rad = 1.14217871º
φ_per = d⊙/D⊙-☿_per = 0.009304/0.307278 = 0.03027877036 rad = 1.73484575º
```
Logo, o Sol é visto de Mercúrio com ~1.15º no afélio e ~1.73º no periélio.

**3. Assuma que um planeta deva perder toda a sua atmosfera inicial no tempo presente, se a velocidade média molecular exceder 1/6 da sua velocidade de escape. Qual massa Mercúrio deveria ter para conter ainda nitrogênio em sua atmosfera? (peso molecular do N =28).**

Para que as partículas de Nitrogênio não escapem de Mercúrio, elas não devem escapar mesmo sob a maior temperatura superficial no planeta (`427ºC = 700K`). Sob esta temperatura, a velocidade molecular média das partículas é dada por:
```
v_N = 0.157 * √(700/28) = 0.157 * √(25) = 0.157 * 5 = 0.785 km/s
```
Para que o Nitrogênio se mantenha na atmosfera, é necessário que a velocidade de escape seja `v_N < 1/6 * v_es`. Assim:
```
v_es > 6 * v_N = 6 * 0.785 = 4.71 km/s
```
Aplicando, então, a equação da velocidade de escape para km/s, temos:
```
v_es = 11.2 * √(M☿/R☿) = 11.2 * √(M☿/0.38Rⴲ) > 4.71
→ √M☿ = 4.71*√(0.38)/11.2 = 0.25923562458 Mⴲ
→ M☿ = 0.25923562458² = 0.06720310905 Mⴲ = 4.01349736 × 10^23 kg
```

**4. A massa da atmosfera marciana é cerca de 1/150 da massa da atmosfera da Terra e é composta basicamente de 95% de CO2. Considerando a massa da atmosfera da Terra como sendo ~ 5×10^18 kg, estimar a massa total de CO2 na atmosfera de Marte. Compare com a massa de CO2 congelado (gelo seco) no polo sul marciano em seu tamanho maior de 3000 km de diâmetro e espessura 1m. Considere o formato da calota circular e densidade de gelo seco de 1600 kg/m³.**

Considerando a massa da atmosfera de Marte como sendo 1/150 a massa da atmosfera terrestre, temos que a massa de CO2 em marte é dada por:
```
M_CO2atm_♂ = (M_atm_ⴲ/150) * 0.95 = (5*10^18/150) * 0.95 ≅ 3.17 * 10^16 kg
```

Assumindo que a calota marciana tenha formato circular, temos que a massa de CO2 presente nele é dada por:
```
V_polar_♂ = πr²h = π * (1.5*10^6)^2 * 1 ≅ 7.06 * 10^12
M_CO2polar_♂ = V_polar_♂ * d_gelo)seco = 7.06 * 10^12 * 1.6 * 10^3 kg/m³
→ M_CO2polar_♂ = 1.1296 * 10^16 kg
```
Desse modo, a massa do CO2 congelada no polo sul de Marte é cerca de 1/3 a quantidade de CO2 na atmosfera.

**5. Utilizando os dados das tabelas dadas em aula, demonstre que os pesos em Júpiter e Urano são respectivamente ~2,6ⴲ (peso da Terra) e ~ 0,9ⴲ (peso da Terra).**

Podemos calcular o peso de um planeta igualando a definição da 2ª lei de Newton igualada com a lei da gravitação de Newton:
```
m*a = m*g = G*m*M/r² → g = GM/r²
```
Considerando a massa de Júpiter `M♃ = 318Mⴲ` e o raio de Júpiter `r♃ = 11rⴲ`, temos:
```
g♃ = G*M♃/r♃² = G * (318Mⴲ) / (11rⴲ)² = (GMⴲ/rⴲ²)*(318/121) ≅ gⴲ * 2.628 ≅ 2.6gⴲ
```
Considerando a massa de Urano `M♅ = 14Mⴲ` e o raio de Júpiter `r♅ = 4rⴲ`, temos:
```
g♅ = G*M♅/r♅² = G * (14Mⴲ) / (4rⴲ)² = (GMⴲ/rⴲ²)*(14/16) ≅ gⴲ * 0.875 ≅ 0.9gⴲ
```
Assim, os pesos em Júpiter e em Uranos são, respectivamente, ~2.6ⴲ (peso da Terra) e ~0.9ⴲ (peso da Terra).

**6. Qual seria a massa de Saturno se ele fosse composto inteiramente de Hidrogênio a uma densidade de 0,08 kg/m³ (densidade de H a nível do mar na Terra)? Assumir por simplicidade que Saturno é esférico. Comparar a resposta com a massa real estimada de Saturno e com a massa da Terra.**

Podemos calcular a massa de Saturno baseado na sua densidade (se formado apenas de H) e em seu volume. Considerando o `r♄ = 9.5 rⴲ ≅ 6.06 * 10^7m` e que Saturno tem formato aproximadamente esférica, temos:
```
V♄ = 4πr♄³/3 = 4π*(6.06*10^7)^3/3 = 9.3219438 * 10^23 m³
```
Considerando que Saturno fosse feita apenas de Hidrogênio, a massa M♄H seria:
```
d♄ = M♄H/V♄
→ M♄H = d♄ * v♄ = (0.08) * (9.3219438 * 10^23) ≅ 7.457555 * 10^22 kg
→ M♄H ≅ 0.012 Mⴲ = 1.2% Mⴲ
→ M♄H ≅ 0.00013 M♄ = 0.013% M♄
```
Logo, a massa de Júpiter, composto apenas por Hidrogênio, seria cerca de 1.2% a massa da Terra e 0.013% da massa de Júpiter.

**7. Com base no que foi exposto em aula sobre a retenção atmosférica dos planetas, como Tritão reteve sua atmosfera? Considerar atmosfera de N somente e temperatura superficial de Tritão ~37 K e os dados da tabela abaixo.**

Para verificarmos porque Tritão manteve sua atmosfera, podemos calcular a velocidade de escape do Hidrogênio em sua superfície e verificar qual a gravidade sobre o planeta.

Para a velocidade de escape, considerando `M_tritão = 0.292 * 7.4 * 10^22 km ≅ 0.0036Mⴲ` e `r_tritão = 1355 km ≅ 0.2127rⴲ`:
```
v_es = 11.2 * √(M_tritão/r_tritão) ≅ 11.2 * √(0.0036/0.2127) ≅ 11.2 * √0.017
→ v_es ≅ 11.2 * 0.13 ≅ 1.456 km/s
```

Para a velocidade média do Nitrogênio, consideremos a massa molecular do Nitrogênio como sendo `u=28` e a temperatura superficial de Tritão como sendo `T = ~37K`:
```
v_N = 0.157 * √(T/u) = 0.157 * √(37/28) ≅ 0.18 km/s
```

Como a velocidade média do gás nitrogênio é de cerca de 12% da velocidade de escape, menor que 1/6 usualmente necessário para que o gás escape, temos que a atmosfera de nitrogênio de Tritão se preserva.