
### **Nome: Renato Cordeiro Ferreira** - NUSP: 7990933

#### A) Falso ou verdadeiro

01. **(F)** Novas sempre ocorrem em sistemas binários cerrados.
02. **(F)** O espectro de uma supernova de tipo II não apresenta evidências de H.
03. **(V)** C pode fusionar mais facilmente com o He do que com outro C porque existe mais He do que C em estrelas.
04. **(F)** Processos-S é processo no qual todos os elementos pesados a partir do Si são formados.
05. **(V)** Processos-R ocorrem somente nos primeiros 15 minutos da explosão da supernova de tipo II.
06. **(V)** Para que ocorra um evento supernova tipo Ia num sistema binário cerrado, é necessário que a massa da anã branca exceda o limite de 1,4 M☉ enquanto agrega massa de sua companheira.
07. **(V)** Nucleossíntese estelar pode explicar a existência de todos os elementos, exceto H e He.
08. **(F)** Como resultado de sua alta massa e pequeno tamanho, uma estrela de nêutrons possui uma fraca força gravitacional.
09. **(V)** Estrelas de nêutrons recém formadas tem intenso campo magnético.
10. **(F)** Como ocorre em todos os pulsares, a estrela de nêutrons da nebulosa do Caranguejo somente pulsa em rádio.
11. **(F)** Todas as estrelas de nêutrons são pulsares, mas nem todos os pulsares são estrelas de nêutrons.
12. **(F)** Somente a matéria sofre efeitos da gravidade.
13. **(F)** Luz visível não pode escapar de um buraco negro, mas radiação de alta energia como raios gama pode.
14. **(V)** A “superfície” de um buraco negro é o seu horizonte de eventos.

#### B) Preencha o que falta

01. Uma supernova de tipo II é o estágio final de evolução de __uma estrela massiva__ e uma supernova de tipo Ia é um possível estágio final de evolução de __um sistema binário__.
02. Os dois tipos de supernova podem ser distinguidos através de seus espectros e suas __curvas de luz__.
03. Elementos de número de massa múltiplos de 4, tais como C, O, Ne e Si são produzidos em estrelas principalmente por __captura de Hélio (He)__.
04. Considerando-se a nucleossíntese estelar, pode-se esperar que o espectro de estrelas mais velhas mostrem __mais__ (menos/mais) elementos pesados nas suas atmosferas do que as mais jovens.
05. Nenhuma remanescente central é formada depois da explosão de uma supernova de tipo __Ia__.
06. Uma estrela de nêutrons típica tem algumas __dezenas__ (dezenas/centenas/milhares) de km em diâmetro.
07. A __pressão de degenerescência dos elétrons__ sustenta uma anã branca contra o colapso gravitacional, enquanto uma estrela de nêutrons é sustentada pela __pressão de degenerescência dos nêutrons__.
08. A nebulosa do Caranguejo e seu pulsar foram produzidos por uma supernova de tipo __II__.
09. De acordo com a teoria da relatividade geral o espaço é curvado pela __massa__.
10. Se o Sol “magicamente” se tornar um buraco negro de mesma massa, a órbita da Terra __permanecerá intacta__.
11. Se o buraco negro absorver massa, seu horizonte de eventos __aumentará__ (aumentará/diminuirá).
12. Na presença de um campo gravitacional forte a luz é __defletida__.
13. Cygnus-X1 é um candidato a __buraco negro__.

#### C) PROBLEMAS

**1. Demonstre que se um objeto chegar a velocidade da luz, o seu comprimento medido por um observador externo tende a zero, assim como a medida de seu tempo pelo mesmo observador tende ao infinito.**

Segundo a relatividade geral especial (RGE), o comprimento `L` de um objeto medido por um observador com velocidade `V` (próxima da da luz) com relação ao seu comprimento `l` medido em repouso é dada pela seguinte transformada de Lorentz:
```
L = l * √(1-V²/c²)
```
Quando `V → c`, temos:
```
L = lim(V→c)                l * √(1-V²/c²)
L = lim(V/c→1)              l * √(1-V²/c²)
L = lim(V²/c²→1)            l * √(1-V²/c²)
L = lim((1-V²/c²) → 0)      l * √(1-V²/c²)
L = lim(√(1-V²/c²) → 0)     l * √(1-V²/c²)
L = lim(√(1-V²/c²) → 0)     l * √(1-V²/c²)
L = lim(l * √(1-V²/c²) → 0) l * √(1-V²/c²)
∴ L = 0
```
Logo, quando a velocidade do objeto tende à velocidade da luz, seu comprimento medido tende à zero.

Considerando agora o tempo `τ` medido em um relógio em repouso com relação ao tempo `t` medido numa velocidade `V` próxima da luz, temos a seguinte transformada de Lorentz:
```
t = τ / √(1-V²/c²)
```
Novamente, aplicando `V → c`, obtemos:
```
t = lim(V→c)                τ / √(1-V²/c²)
t = lim(V/c→1)              τ / √(1-V²/c²)
t = lim(V²/c²→1)            τ / √(1-V²/c²)
t = lim((1-V²/c²) → 0)      τ / √(1-V²/c²)
t = lim(√(1-V²/c²) → 0)     τ / √(1-V²/c²)
t = lim(√(1-V²/c²) → 0)     τ / √(1-V²/c²)
t = lim(1 / √(1-V²/c²) → 0) τ / √(1-V²/c²)
t = lim(τ / √(1-V²/c²) → ∞) τ / √(1-V²/c²)
∴ L = ∞
```
Assim, o tempo medido de um objeto à velocidade da luz tende ao infinito.

**2. Múons são partículas elementares instáveis que possuem um tempo de decaimento de 2µs quando medido em seu referencial de repouso. Entretanto, quando produzidos por choques de raios cósmicos com a atmosfera superior da Terra, eles podem alcançar velocidade relativísticas de cerca de 99% a velocidade da luz. Qual o tempo de decaimento dos Múons neste caso?**

Considerando o tempo de decaimento dos múons em repouso como sendo `τ_dec = 2µs = 2 * 10^-6 s` e a velocidade deles em raios cósmicos como sendo `V = 0.99c`, podemos aplicar a transformação de Lorentz para obter o tempo de decaimento nessa velocidade como sendo:
```
t_dec = τ_dec / √(1-V²/c²)
t_dec = 2*10^-6 / √(1-(0.99c)²/c²)
t_dec = 2*10^-6 / √(1-0.99²)
t_dec = 2*10^-6 / √(0.0199)
t_dec = 2*10^-6 / 0.14106736
∴ t_dec = 14.17 * 10^-6s = 14.17µs 
```
Logo, os múons demoram 14.17µs para decaírem próximos da velocidade da luz.

**3. Se a Terra for substituída por um buraco negro de 1 Mⴲ, o que acontecerá com a lua? A lua seria dragada pelo buraco negro?**

Se a Terra fosse substituída por um buraco negro de mesma massa, o seu raio de Schwartzchild seria:
```
r_s = 2GMⴲ/c²
r_s = 2 * (6.67408 * 10^-11) * (5.97219 * 10^24) / (3 * 10^8)²
r_s = 2 * (6.67408 * 5.97219 / 3²) * 10^-3
r_s = 2 * 4.4287 * 10^-3
r_s = 8.8574 * 10^-3 m
∴ r_s = 8.8574 mm
```
Logo, o raio de Schwartzchild de um buraco negro com tamanho de uma massa solar teria pouco menos de 9mm - muito menor que a distância do centro da Terra ao centro da Lua. Como a Lua estaria muito distante do horizonte de eventos do buraco negro, sua órbita se manteria intacta (e os efeitos de maré sobre o satélite seriam reduzidos).

**4. Todo objeto tem seu horizonte de eventos. Define-se buraco negro como sendo um objeto que tem um tamanho igual ao seu próprio horizonte de eventos. O quanto pequeno você deve ficar para se tornar um buraco negro? Como se compara o tamanho obtido com o tamanho de um núcleo atômico (raio = 10^-15 m)?**

O raio de Schwartzchild (limite do horizonte de eventos de um corpo com uma dada massa) pode ser calculado pela equação:
```
r_s = 2Gm/c²
```
Considerando um ser humano com massa m ≅ 100 kg = 10^2 k, o seu raio de Schwartzchild será:
```
r_s = 2 * (6.67408 * 10^-11) * 10^2 / (3 * 10^8)²
r_s = (2 * 6.67408 / 3²) * 10^-25
∴ r_s = 1.48 * 10^-25 m
```
Logo, o horizonte de eventos de um homem com massa de aproximadamente 100 kg será aproximadamente 1.5 * 10^-25 m, cerca de 10^10 vezes menor que um núcleo atômico.