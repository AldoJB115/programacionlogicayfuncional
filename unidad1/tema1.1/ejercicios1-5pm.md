# Ejercicios 1 — Introducción a Erlang (Grupo 5pm)

10 ejercicios introductorios de Erlang por estudiante, para practicarse en el shell `erl` de una instancia Ubuntu de AWS Academy EC2. Cada estudiante tiene valores personalizados (semilla = número de lista) para evitar que las soluciones sean copiables entre compañeros.

> **Nota:** El nombre #18 (JESUS CRUZ, TAFOYA) aparece con el orden invertido en el tabulador PDF original; verificar contra el gradebook antes de publicar.

### 1. AGUILAR AGUILAR, LUIS DANIEL

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(101 * 7) + 25` y `101 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, luis, 1, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {6, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(101)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (101 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (101 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(101)`. |
| 10 | Módulo propio | Crea el módulo `aguilar.erl` con `-module(aguilar).` y `-export([saludo/0]).`, compílalo con `c(aguilar).` y ejecuta `aguilar:saludo()`. |

### 2. ALVARADO SOTO, ADRIAN ERNESTO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(102 * 7) + 25` y `102 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, adrian, 2, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {7, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(102)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (102 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (102 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(102)`. |
| 10 | Módulo propio | Crea el módulo `alvarado.erl` con `-module(alvarado).` y `-export([saludo/0]).`, compílalo con `c(alvarado).` y ejecuta `alvarado:saludo()`. |

### 3. ARCE BENITEZ, MIGUEL ANGEL

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(103 * 7) + 25` y `103 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, miguel, 3, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {8, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(103)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (103 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (103 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `0`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(103)`. |
| 10 | Módulo propio | Crea el módulo `arce.erl` con `-module(arce).` y `-export([saludo/0]).`, compílalo con `c(arce).` y ejecuta `arce:saludo()`. |

### 4. BALLESTEROS CRUZ, ALDO JUVENTINO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(104 * 7) + 25` y `104 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, aldo, 4, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {9, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(104)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (104 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (104 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(104)`. |
| 10 | Módulo propio | Crea el módulo `ballesteros.erl` con `-module(ballesteros).` y `-export([saludo/0]).`, compílalo con `c(ballesteros).` y ejecuta `ballesteros:saludo()`. |

### 5. BARRAZA SANCHEZ, LUZ DEL CARMEN

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(105 * 7) + 25` y `105 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, luz, 5, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {3, 4}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(105)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(5)` (5 + (105 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5]` (longitud = 5 + (105 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(105)`. |
| 10 | Módulo propio | Crea el módulo `barraza.erl` con `-module(barraza).` y `-export([saludo/0]).`, compílalo con `c(barraza).` y ejecuta `barraza:saludo()`. |

### 6. BERNAL LOPEZ, DONALDO MANRIQUE

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(106 * 7) + 25` y `106 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, donaldo, 6, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {4, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(106)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (106 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (106 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `0`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(106)`. |
| 10 | Módulo propio | Crea el módulo `bernal.erl` con `-module(bernal).` y `-export([saludo/0]).`, compílalo con `c(bernal).` y ejecuta `bernal:saludo()`. |

### 7. BOJORQUEZ VALDEZ, VICTOR MANUEL

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(107 * 7) + 25` y `107 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, victor, 7, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {5, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(107)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (107 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (107 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(107)`. |
| 10 | Módulo propio | Crea el módulo `bojorquez.erl` con `-module(bojorquez).` y `-export([saludo/0]).`, compílalo con `c(bojorquez).` y ejecuta `bojorquez:saludo()`. |

### 8. CANALES CALDERON, JOEL JUNIOR

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(108 * 7) + 25` y `108 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, joel, 8, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {6, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(108)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (108 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (108 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(108)`. |
| 10 | Módulo propio | Crea el módulo `canales.erl` con `-module(canales).` y `-export([saludo/0]).`, compílalo con `c(canales).` y ejecuta `canales:saludo()`. |

### 9. CARRASCO SERNA, JOSE LUIS

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(109 * 7) + 25` y `109 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, jose, 9, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {7, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(109)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (109 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (109 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `0`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(109)`. |
| 10 | Módulo propio | Crea el módulo `carrasco.erl` con `-module(carrasco).` y `-export([saludo/0]).`, compílalo con `c(carrasco).` y ejecuta `carrasco:saludo()`. |

### 10. CARRILLO ESTRADA, ASHLEY

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(110 * 7) + 25` y `110 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, ashley, 10, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {8, 4}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(110)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(5)` (5 + (110 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5]` (longitud = 5 + (110 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(110)`. |
| 10 | Módulo propio | Crea el módulo `carrillo.erl` con `-module(carrillo).` y `-export([saludo/0]).`, compílalo con `c(carrillo).` y ejecuta `carrillo:saludo()`. |

### 11. CASILLAS XOLALPA, ANGELO MISAEL

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(111 * 7) + 25` y `111 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, angelo, 11, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {9, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(111)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (111 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (111 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(111)`. |
| 10 | Módulo propio | Crea el módulo `casillas.erl` con `-module(casillas).` y `-export([saludo/0]).`, compílalo con `c(casillas).` y ejecuta `casillas:saludo()`. |

### 12. CHAVEZ GOMEZ, MARIANA ALEJANDRA

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(112 * 7) + 25` y `112 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, mariana, 12, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {3, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(112)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (112 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (112 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `0`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(112)`. |
| 10 | Módulo propio | Crea el módulo `chavez.erl` con `-module(chavez).` y `-export([saludo/0]).`, compílalo con `c(chavez).` y ejecuta `chavez:saludo()`. |

### 13. DANIELS CEBALLOS, AXEL

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(113 * 7) + 25` y `113 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, axel, 13, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {4, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(113)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (113 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (113 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(113)`. |
| 10 | Módulo propio | Crea el módulo `daniels.erl` con `-module(daniels).` y `-export([saludo/0]).`, compílalo con `c(daniels).` y ejecuta `daniels:saludo()`. |

### 14. DURAN PONCE, LUIS ADAO LEONEL

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(114 * 7) + 25` y `114 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, luis, 14, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {5, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(114)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (114 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (114 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(114)`. |
| 10 | Módulo propio | Crea el módulo `duran.erl` con `-module(duran).` y `-export([saludo/0]).`, compílalo con `c(duran).` y ejecuta `duran:saludo()`. |

### 15. GARCIA ALVARADO, BRAYAN OSWALDO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(115 * 7) + 25` y `115 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, brayan, 15, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {6, 4}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(115)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(5)` (5 + (115 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5]` (longitud = 5 + (115 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `0`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(115)`. |
| 10 | Módulo propio | Crea el módulo `garcia.erl` con `-module(garcia).` y `-export([saludo/0]).`, compílalo con `c(garcia).` y ejecuta `garcia:saludo()`. |

### 16. GRANDE ORTEGA, MAIXIMILIANO ALBERTO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(116 * 7) + 25` y `116 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, maiximiliano, 16, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {7, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(116)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (116 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (116 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(116)`. |
| 10 | Módulo propio | Crea el módulo `grande.erl` con `-module(grande).` y `-export([saludo/0]).`, compílalo con `c(grande).` y ejecuta `grande:saludo()`. |

### 17. GUZMAN OCHOA, ERICK JUNIOR

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(117 * 7) + 25` y `117 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, erick, 17, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {8, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(117)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (117 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (117 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(117)`. |
| 10 | Módulo propio | Crea el módulo `guzman.erl` con `-module(guzman).` y `-export([saludo/0]).`, compílalo con `c(guzman).` y ejecuta `guzman:saludo()`. |

### 18. JESUS CRUZ, TAFOYA

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(118 * 7) + 25` y `118 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, tafoya, 18, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {9, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(118)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (118 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (118 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `0`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(118)`. |
| 10 | Módulo propio | Crea el módulo `jesus.erl` con `-module(jesus).` y `-export([saludo/0]).`, compílalo con `c(jesus).` y ejecuta `jesus:saludo()`. |

### 19. JIMENEZ BARRERA, JESUS ALONSO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(119 * 7) + 25` y `119 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, jesus, 19, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {3, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(119)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (119 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (119 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(119)`. |
| 10 | Módulo propio | Crea el módulo `jimenez.erl` con `-module(jimenez).` y `-export([saludo/0]).`, compílalo con `c(jimenez).` y ejecuta `jimenez:saludo()`. |

### 20. LEANDRO RODRIGUEZ, ANTONIO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(120 * 7) + 25` y `120 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, antonio, 20, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {4, 4}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(120)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(5)` (5 + (120 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5]` (longitud = 5 + (120 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(120)`. |
| 10 | Módulo propio | Crea el módulo `leandro.erl` con `-module(leandro).` y `-export([saludo/0]).`, compílalo con `c(leandro).` y ejecuta `leandro:saludo()`. |

### 21. LEDESMA VALENZUELA, RENATA NICTE

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(121 * 7) + 25` y `121 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, renata, 21, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {5, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(121)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (121 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (121 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `0`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(121)`. |
| 10 | Módulo propio | Crea el módulo `ledesma.erl` con `-module(ledesma).` y `-export([saludo/0]).`, compílalo con `c(ledesma).` y ejecuta `ledesma:saludo()`. |

### 22. LIZARRAGA FIGUEROA, SAMANTA

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(122 * 7) + 25` y `122 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, samanta, 22, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {6, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(122)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (122 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (122 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(122)`. |
| 10 | Módulo propio | Crea el módulo `lizarraga.erl` con `-module(lizarraga).` y `-export([saludo/0]).`, compílalo con `c(lizarraga).` y ejecuta `lizarraga:saludo()`. |

### 23. LOPEZ MOLGADO, JORGE LUIS

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(123 * 7) + 25` y `123 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, jorge, 23, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {7, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(123)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (123 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (123 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(123)`. |
| 10 | Módulo propio | Crea el módulo `lopez.erl` con `-module(lopez).` y `-export([saludo/0]).`, compílalo con `c(lopez).` y ejecuta `lopez:saludo()`. |

### 24. MARTINEZ TORRES, KAREN ARLETTE

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(124 * 7) + 25` y `124 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, karen, 24, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {8, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(124)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (124 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (124 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `0`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(124)`. |
| 10 | Módulo propio | Crea el módulo `martinez.erl` con `-module(martinez).` y `-export([saludo/0]).`, compílalo con `c(martinez).` y ejecuta `martinez:saludo()`. |

### 25. MEJIA SALINAS, AXEL JOSE

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(125 * 7) + 25` y `125 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, axel, 25, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {9, 4}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(125)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(5)` (5 + (125 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5]` (longitud = 5 + (125 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(125)`. |
| 10 | Módulo propio | Crea el módulo `mejia.erl` con `-module(mejia).` y `-export([saludo/0]).`, compílalo con `c(mejia).` y ejecuta `mejia:saludo()`. |

### 26. MOGUEL BENITEZ, DAFNE JAEL

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(126 * 7) + 25` y `126 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, dafne, 26, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {3, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(126)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (126 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (126 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(126)`. |
| 10 | Módulo propio | Crea el módulo `moguel.erl` con `-module(moguel).` y `-export([saludo/0]).`, compílalo con `c(moguel).` y ejecuta `moguel:saludo()`. |

### 27. MONTES SANTILLAN, OMAR ALEJANDRO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(127 * 7) + 25` y `127 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, omar, 27, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {4, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(127)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (127 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (127 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `0`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(127)`. |
| 10 | Módulo propio | Crea el módulo `montes.erl` con `-module(montes).` y `-export([saludo/0]).`, compílalo con `c(montes).` y ejecuta `montes:saludo()`. |

### 28. NAVARRO GONZALEZ, CYNTHIA YALID

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(128 * 7) + 25` y `128 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, cynthia, 28, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {5, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(128)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (128 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (128 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(128)`. |
| 10 | Módulo propio | Crea el módulo `navarro.erl` con `-module(navarro).` y `-export([saludo/0]).`, compílalo con `c(navarro).` y ejecuta `navarro:saludo()`. |

### 29. PARRA ESPINOZA, HERIB ARTURO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(129 * 7) + 25` y `129 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, herib, 29, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {6, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(129)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (129 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (129 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(129)`. |
| 10 | Módulo propio | Crea el módulo `parra.erl` con `-module(parra).` y `-export([saludo/0]).`, compílalo con `c(parra).` y ejecuta `parra:saludo()`. |

### 30. PRECIADO RAMOS, DANIEL

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(130 * 7) + 25` y `130 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, daniel, 30, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {7, 4}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(130)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(5)` (5 + (130 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5]` (longitud = 5 + (130 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `0`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(130)`. |
| 10 | Módulo propio | Crea el módulo `preciado.erl` con `-module(preciado).` y `-export([saludo/0]).`, compílalo con `c(preciado).` y ejecuta `preciado:saludo()`. |

### 31. REYES MADRIGAL, DIANA MARIA

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(131 * 7) + 25` y `131 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, diana, 31, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {8, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(131)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (131 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (131 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(131)`. |
| 10 | Módulo propio | Crea el módulo `reyes.erl` con `-module(reyes).` y `-export([saludo/0]).`, compílalo con `c(reyes).` y ejecuta `reyes:saludo()`. |

### 32. RODRIGUEZ CAMARENA, JOSHUA NEZIB

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(132 * 7) + 25` y `132 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, joshua, 32, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {9, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(132)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (132 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (132 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(132)`. |
| 10 | Módulo propio | Crea el módulo `rodriguez.erl` con `-module(rodriguez).` y `-export([saludo/0]).`, compílalo con `c(rodriguez).` y ejecuta `rodriguez:saludo()`. |

### 33. RODRIGUEZ MENDIVIL, FABIAN OSVALDO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(133 * 7) + 25` y `133 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, fabian, 33, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {3, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(133)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (133 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (133 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `0`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(133)`. |
| 10 | Módulo propio | Crea el módulo `rodriguez2.erl` con `-module(rodriguez2).` y `-export([saludo/0]).`, compílalo con `c(rodriguez2).` y ejecuta `rodriguez2:saludo()`. |

### 34. ROSAS CRUZ, CARLOS DANIEL

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(134 * 7) + 25` y `134 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, carlos, 34, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {4, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(134)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (134 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (134 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(134)`. |
| 10 | Módulo propio | Crea el módulo `rosas.erl` con `-module(rosas).` y `-export([saludo/0]).`, compílalo con `c(rosas).` y ejecuta `rosas:saludo()`. |

### 35. SANCHEZ RESENDIZ, BRAULIO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(135 * 7) + 25` y `135 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, braulio, 35, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {5, 4}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(135)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(5)` (5 + (135 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5]` (longitud = 5 + (135 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(135)`. |
| 10 | Módulo propio | Crea el módulo `sanchez.erl` con `-module(sanchez).` y `-export([saludo/0]).`, compílalo con `c(sanchez).` y ejecuta `sanchez:saludo()`. |

### 36. SANTIAGO SIQUEIROS, CRISTOFER JOEL

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(136 * 7) + 25` y `136 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, cristofer, 36, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {6, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(136)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (136 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (136 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `0`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(136)`. |
| 10 | Módulo propio | Crea el módulo `santiago.erl` con `-module(santiago).` y `-export([saludo/0]).`, compílalo con `c(santiago).` y ejecuta `santiago:saludo()`. |

### 37. TELLEZ RUIZ, MARIA REBECA

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(137 * 7) + 25` y `137 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, maria, 37, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {7, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(137)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (137 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (137 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(137)`. |
| 10 | Módulo propio | Crea el módulo `tellez.erl` con `-module(tellez).` y `-export([saludo/0]).`, compílalo con `c(tellez).` y ejecuta `tellez:saludo()`. |

### 38. URREA RAMIREZ, JUAN PABLO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(138 * 7) + 25` y `138 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, juan, 38, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {8, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(138)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (138 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (138 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(138)`. |
| 10 | Módulo propio | Crea el módulo `urrea.erl` con `-module(urrea).` y `-export([saludo/0]).`, compílalo con `c(urrea).` y ejecuta `urrea:saludo()`. |

### 39. VELARDE LOPEZ, MIGUEL ANGEL DE JESUS

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(139 * 7) + 25` y `139 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, miguel, 39, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {9, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(139)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (139 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (139 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `0`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(139)`. |
| 10 | Módulo propio | Crea el módulo `velarde.erl` con `-module(velarde).` y `-export([saludo/0]).`, compílalo con `c(velarde).` y ejecuta `velarde:saludo()`. |

### 40. VELAZQUEZ MONTIEL, JOSE ALBERTO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(140 * 7) + 25` y `140 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, jose, 40, "5pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1`. |
| 4 | Pattern matching | Dada `Punto = {3, 4}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(140)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(5)` (5 + (140 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5]` (longitud = 5 + (140 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `1`. |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(140)`. |
| 10 | Módulo propio | Crea el módulo `velazquez.erl` con `-module(velazquez).` y `-export([saludo/0]).`, compílalo con `c(velazquez).` y ejecuta `velazquez:saludo()`. |
