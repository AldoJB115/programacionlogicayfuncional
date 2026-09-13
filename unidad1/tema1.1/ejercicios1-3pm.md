# Ejercicios 1 — Introducción a Erlang (Grupo 3pm)

10 ejercicios introductorios de Erlang por estudiante, para practicarse en el shell `erl` de una instancia Ubuntu de AWS Academy EC2. Cada estudiante tiene valores personalizados (semilla = número de lista) para evitar que las soluciones sean copiables entre compañeros.

> **Nota:** Los nombres #10 (GALLEGOS HERNANDEZ) y #12 (GUARNEROS VILLANUEVA) aparecieron incompletos en el tabulador PDF original (falta el nombre de pila); verificar contra el gradebook antes de publicar.

### 1. AGUIRRE LOPEZ, JAIME NAEL

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(1 * 7) + 25` y `1 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, jaime, 1, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml", "Haskell"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {4, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(1)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (1 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (1 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-19` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(1)`. |
| 10 | Módulo propio | Crea el módulo `aguirre.erl` con `-module(aguirre).` y `-export([saludo/0]).`, compílalo con `c(aguirre).` y ejecuta `aguirre:saludo()`. |

### 2. ANTONIO ALBAÑIL, JASON JARIB

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(2 * 7) + 25` y `2 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, jason, 2, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Prolog", "OCaml", "Haskell", "Clojure", "Elixir"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {5, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(2)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (2 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (2 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-18` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(2)`. |
| 10 | Módulo propio | Crea el módulo `antonio.erl` con `-module(antonio).` y `-export([saludo/0]).`, compílalo con `c(antonio).` y ejecuta `antonio:saludo()`. |

### 3. ARAOZ SIERRA, RICARDO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(3 * 7) + 25` y `3 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, ricardo, 3, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["OCaml", "Haskell", "Clojure", "Elixir", "Scala", "Gleam"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {6, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(3)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (3 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (3 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-17` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(3)`. |
| 10 | Módulo propio | Crea el módulo `araoz.erl` con `-module(araoz).` y `-export([saludo/0]).`, compílalo con `c(araoz).` y ejecuta `araoz:saludo()`. |

### 4. CAB PIÑON, ISURY MICHELLE

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(4 * 7) + 25` y `4 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, isury, 4, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Haskell", "Clojure", "Elixir"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {7, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(4)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (4 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (4 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-16` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(4)`. |
| 10 | Módulo propio | Crea el módulo `cab.erl` con `-module(cab).` y `-export([saludo/0]).`, compílalo con `c(cab).` y ejecuta `cab:saludo()`. |

### 5. CAMACHO TORRES, ADRIAN

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(5 * 7) + 25` y `5 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, adrian, 5, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Clojure", "Elixir", "Scala", "Gleam"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {8, 4}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(5)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(5)` (5 + (5 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5]` (longitud = 5 + (5 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-15` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(5)`. |
| 10 | Módulo propio | Crea el módulo `camacho.erl` con `-module(camacho).` y `-export([saludo/0]).`, compílalo con `c(camacho).` y ejecuta `camacho:saludo()`. |

### 6. CARRERA AGUIRRE, JOEL

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(6 * 7) + 25` y `6 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, joel, 6, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Elixir", "Scala", "Gleam", "FSharp", "Racket"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {9, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(6)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (6 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (6 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-14` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(6)`. |
| 10 | Módulo propio | Crea el módulo `carrera.erl` con `-module(carrera).` y `-export([saludo/0]).`, compílalo con `c(carrera).` y ejecuta `carrera:saludo()`. |

### 7. CASAS RAMIREZ, ALVARO GABINO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(7 * 7) + 25` y `7 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, alvaro, 7, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Scala", "Gleam", "FSharp", "Racket", "Scheme", "Datalog"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {3, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(7)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (7 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (7 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-13` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(7)`. |
| 10 | Módulo propio | Crea el módulo `casas.erl` con `-module(casas).` y `-export([saludo/0]).`, compílalo con `c(casas).` y ejecuta `casas:saludo()`. |

### 8. CORTES HUERTA, ANGEL EDUARDO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(8 * 7) + 25` y `8 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, angel, 8, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Gleam", "FSharp", "Racket"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {4, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(8)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (8 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (8 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-12` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(8)`. |
| 10 | Módulo propio | Crea el módulo `cortes.erl` con `-module(cortes).` y `-export([saludo/0]).`, compílalo con `c(cortes).` y ejecuta `cortes:saludo()`. |

### 9. FLORES REYES, JOLIET IVET

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(9 * 7) + 25` y `9 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, joliet, 9, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["FSharp", "Racket", "Scheme", "Datalog"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {5, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(9)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (9 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (9 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-11` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(9)`. |
| 10 | Módulo propio | Crea el módulo `flores.erl` con `-module(flores).` y `-export([saludo/0]).`, compílalo con `c(flores).` y ejecuta `flores:saludo()`. |

### 10. GALLEGOS HERNANDEZ, ESTUDIANTE

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(10 * 7) + 25` y `10 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, estudiante, 10, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Racket", "Scheme", "Datalog", "Clingo", "Erlang"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {6, 4}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(10)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(5)` (5 + (10 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5]` (longitud = 5 + (10 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-10` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(10)`. |
| 10 | Módulo propio | Crea el módulo `gallegos.erl` con `-module(gallegos).` y `-export([saludo/0]).`, compílalo con `c(gallegos).` y ejecuta `gallegos:saludo()`. |

### 11. GARCIA PASCENCIA, LUIS FELIPE

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(11 * 7) + 25` y `11 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, luis, 11, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Scheme", "Datalog", "Clingo", "Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {7, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(11)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (11 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (11 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-9` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(11)`. |
| 10 | Módulo propio | Crea el módulo `garcia.erl` con `-module(garcia).` y `-export([saludo/0]).`, compílalo con `c(garcia).` y ejecuta `garcia:saludo()`. |

### 12. GUARNEROS VILLANUEVA, ESTUDIANTE

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(12 * 7) + 25` y `12 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, estudiante, 12, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Datalog", "Clingo", "Erlang"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {8, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(12)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (12 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (12 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-8` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(12)`. |
| 10 | Módulo propio | Crea el módulo `guarneros.erl` con `-module(guarneros).` y `-export([saludo/0]).`, compílalo con `c(guarneros).` y ejecuta `guarneros:saludo()`. |

### 13. GUERRA HABANA, JOSE GUSTAVO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(13 * 7) + 25` y `13 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, jose, 13, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Clingo", "Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {9, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(13)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (13 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (13 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-7` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(13)`. |
| 10 | Módulo propio | Crea el módulo `guerra.erl` con `-module(guerra).` y `-export([saludo/0]).`, compílalo con `c(guerra).` y ejecuta `guerra:saludo()`. |

### 14. JARDIN GRACIA, JOSE ALBERTO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(14 * 7) + 25` y `14 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, jose, 14, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml", "Haskell", "Clojure"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {3, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(14)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (14 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (14 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-6` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(14)`. |
| 10 | Módulo propio | Crea el módulo `jardin.erl` con `-module(jardin).` y `-export([saludo/0]).`, compílalo con `c(jardin).` y ejecuta `jardin:saludo()`. |

### 15. JOVEL CUEN, MARIO ALEJANDRO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(15 * 7) + 25` y `15 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, mario, 15, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Prolog", "OCaml", "Haskell", "Clojure", "Elixir", "Scala"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {4, 4}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(15)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(5)` (5 + (15 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5]` (longitud = 5 + (15 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-5` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(15)`. |
| 10 | Módulo propio | Crea el módulo `jovel.erl` con `-module(jovel).` y `-export([saludo/0]).`, compílalo con `c(jovel).` y ejecuta `jovel:saludo()`. |

### 16. LARA FERNANDEZ DE LARA, JOSHUA

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(16 * 7) + 25` y `16 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, joshua, 16, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["OCaml", "Haskell", "Clojure"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {5, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(16)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (16 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (16 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-4` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(16)`. |
| 10 | Módulo propio | Crea el módulo `lara.erl` con `-module(lara).` y `-export([saludo/0]).`, compílalo con `c(lara).` y ejecuta `lara:saludo()`. |

### 17. LARES MENA, ANGEL FERNANDO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(17 * 7) + 25` y `17 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, angel, 17, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Haskell", "Clojure", "Elixir", "Scala"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {6, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(17)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (17 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (17 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-3` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(17)`. |
| 10 | Módulo propio | Crea el módulo `lares.erl` con `-module(lares).` y `-export([saludo/0]).`, compílalo con `c(lares).` y ejecuta `lares:saludo()`. |

### 18. LUIS JUAN CAMACHO, CESAR ADRIAN

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(18 * 7) + 25` y `18 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, cesar, 18, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Clojure", "Elixir", "Scala", "Gleam", "FSharp"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {7, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(18)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (18 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (18 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-2` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(18)`. |
| 10 | Módulo propio | Crea el módulo `luis.erl` con `-module(luis).` y `-export([saludo/0]).`, compílalo con `c(luis).` y ejecuta `luis:saludo()`. |

### 19. MENDOZA VELAZQUEZ, HECTOR

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(19 * 7) + 25` y `19 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, hector, 19, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Elixir", "Scala", "Gleam", "FSharp", "Racket", "Scheme"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {8, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(19)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (19 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (19 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `-1` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(19)`. |
| 10 | Módulo propio | Crea el módulo `mendoza.erl` con `-module(mendoza).` y `-export([saludo/0]).`, compílalo con `c(mendoza).` y ejecuta `mendoza:saludo()`. |

### 20. MUÑOZ GUZMAN, LEONARDO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(20 * 7) + 25` y `20 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, leonardo, 20, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Scala", "Gleam", "FSharp"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {9, 4}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(20)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(5)` (5 + (20 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5]` (longitud = 5 + (20 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `0` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(20)`. |
| 10 | Módulo propio | Crea el módulo `munoz.erl` con `-module(munoz).` y `-export([saludo/0]).`, compílalo con `c(munoz).` y ejecuta `munoz:saludo()`. |

### 21. MURUA RAMIREZ, ANGEL GERARDO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(21 * 7) + 25` y `21 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, angel, 21, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Gleam", "FSharp", "Racket", "Scheme"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {3, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(21)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (21 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (21 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `1` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(21)`. |
| 10 | Módulo propio | Crea el módulo `murua.erl` con `-module(murua).` y `-export([saludo/0]).`, compílalo con `c(murua).` y ejecuta `murua:saludo()`. |

### 22. NAVARRO JIMENEZ, ANGEL IVAN

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(22 * 7) + 25` y `22 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, angel, 22, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["FSharp", "Racket", "Scheme", "Datalog", "Clingo"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {4, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(22)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (22 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (22 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `2` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(22)`. |
| 10 | Módulo propio | Crea el módulo `navarro.erl` con `-module(navarro).` y `-export([saludo/0]).`, compílalo con `c(navarro).` y ejecuta `navarro:saludo()`. |

### 23. ORTEGA UNZUETA, ERNESTO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(23 * 7) + 25` y `23 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, ernesto, 23, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Racket", "Scheme", "Datalog", "Clingo", "Erlang", "Prolog"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {5, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(23)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (23 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (23 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `3` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(23)`. |
| 10 | Módulo propio | Crea el módulo `ortega.erl` con `-module(ortega).` y `-export([saludo/0]).`, compílalo con `c(ortega).` y ejecuta `ortega:saludo()`. |

### 24. PEÑA GONZALEZ, ISAAC HILARIO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(24 * 7) + 25` y `24 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, isaac, 24, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Scheme", "Datalog", "Clingo"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {6, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(24)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (24 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (24 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `4` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(24)`. |
| 10 | Módulo propio | Crea el módulo `pena.erl` con `-module(pena).` y `-export([saludo/0]).`, compílalo con `c(pena).` y ejecuta `pena:saludo()`. |

### 25. PEREZ RAMIREZ, UBER MAURICIO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(25 * 7) + 25` y `25 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, uber, 25, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Datalog", "Clingo", "Erlang", "Prolog"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {7, 4}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(25)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(5)` (5 + (25 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5]` (longitud = 5 + (25 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `5` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(25)`. |
| 10 | Módulo propio | Crea el módulo `perez.erl` con `-module(perez).` y `-export([saludo/0]).`, compílalo con `c(perez).` y ejecuta `perez:saludo()`. |

### 26. PLATA CRUZ, KEVIN JAHIR

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(26 * 7) + 25` y `26 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, kevin, 26, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Clingo", "Erlang", "Prolog", "OCaml", "Haskell"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {8, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(26)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (26 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (26 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `6` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(26)`. |
| 10 | Módulo propio | Crea el módulo `plata.erl` con `-module(plata).` y `-export([saludo/0]).`, compílalo con `c(plata).` y ejecuta `plata:saludo()`. |

### 27. RAYGOZA TOLEDO, BRANDON EMILIO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(27 * 7) + 25` y `27 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, brandon, 27, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Erlang", "Prolog", "OCaml", "Haskell", "Clojure", "Elixir"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {9, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(27)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (27 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (27 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `7` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(27)`. |
| 10 | Módulo propio | Crea el módulo `raygoza.erl` con `-module(raygoza).` y `-export([saludo/0]).`, compílalo con `c(raygoza).` y ejecuta `raygoza:saludo()`. |

### 28. RODRIGUEZ PERAZA, CARLOS ELIAB

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(28 * 7) + 25` y `28 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, carlos, 28, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Prolog", "OCaml", "Haskell"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {3, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(28)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (28 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (28 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `8` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(28)`. |
| 10 | Módulo propio | Crea el módulo `rodriguez.erl` con `-module(rodriguez).` y `-export([saludo/0]).`, compílalo con `c(rodriguez).` y ejecuta `rodriguez:saludo()`. |

### 29. ROMERO GARCIA, FRANCISCO YAMIL

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(29 * 7) + 25` y `29 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, francisco, 29, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["OCaml", "Haskell", "Clojure", "Elixir"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {4, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(29)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (29 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (29 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `9` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(29)`. |
| 10 | Módulo propio | Crea el módulo `romero.erl` con `-module(romero).` y `-export([saludo/0]).`, compílalo con `c(romero).` y ejecuta `romero:saludo()`. |

### 30. ROSALES X, MAILEN GISELL

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(30 * 7) + 25` y `30 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, mailen, 30, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Haskell", "Clojure", "Elixir", "Scala", "Gleam"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {5, 4}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(30)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(5)` (5 + (30 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5]` (longitud = 5 + (30 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `10` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(30)`. |
| 10 | Módulo propio | Crea el módulo `rosales.erl` con `-module(rosales).` y `-export([saludo/0]).`, compílalo con `c(rosales).` y ejecuta `rosales:saludo()`. |

### 31. RUAN LOPEZ, TAI PING ALEJANDRA

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(31 * 7) + 25` y `31 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, tai, 31, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Clojure", "Elixir", "Scala", "Gleam", "FSharp", "Racket"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {6, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(31)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (31 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (31 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `11` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(31)`. |
| 10 | Módulo propio | Crea el módulo `ruan.erl` con `-module(ruan).` y `-export([saludo/0]).`, compílalo con `c(ruan).` y ejecuta `ruan:saludo()`. |

### 32. RUIZ SANCHEZ, JOSE MANUEL

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(32 * 7) + 25` y `32 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, jose, 32, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Elixir", "Scala", "Gleam"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {7, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(32)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (32 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (32 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `12` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(32)`. |
| 10 | Módulo propio | Crea el módulo `ruiz.erl` con `-module(ruiz).` y `-export([saludo/0]).`, compílalo con `c(ruiz).` y ejecuta `ruiz:saludo()`. |

### 33. SAINZ MONTOYA, EARVIN ALEJANDRO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(33 * 7) + 25` y `33 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, earvin, 33, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Scala", "Gleam", "FSharp", "Racket"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {8, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(33)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (33 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (33 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `13` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(33)`. |
| 10 | Módulo propio | Crea el módulo `sainz.erl` con `-module(sainz).` y `-export([saludo/0]).`, compílalo con `c(sainz).` y ejecuta `sainz:saludo()`. |

### 34. TAVERA ALANIS, TANIA LIZETH

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(34 * 7) + 25` y `34 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, tania, 34, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Gleam", "FSharp", "Racket", "Scheme", "Datalog"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {9, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(34)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (34 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (34 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `14` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(34)`. |
| 10 | Módulo propio | Crea el módulo `tavera.erl` con `-module(tavera).` y `-export([saludo/0]).`, compílalo con `c(tavera).` y ejecuta `tavera:saludo()`. |

### 35. URQUIZA HERRERA, MARIO ALBERTO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(35 * 7) + 25` y `35 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, mario, 35, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["FSharp", "Racket", "Scheme", "Datalog", "Clingo", "Erlang"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {3, 4}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(35)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(5)` (5 + (35 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5]` (longitud = 5 + (35 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `15` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(35)`. |
| 10 | Módulo propio | Crea el módulo `urquiza.erl` con `-module(urquiza).` y `-export([saludo/0]).`, compílalo con `c(urquiza).` y ejecuta `urquiza:saludo()`. |

### 36. VALDEZ AMPARO, RICARDO DAVID

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(36 * 7) + 25` y `36 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, ricardo, 36, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Racket", "Scheme", "Datalog"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {4, 5}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(36)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(6)` (5 + (36 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6]` (longitud = 5 + (36 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `16` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(36)`. |
| 10 | Módulo propio | Crea el módulo `valdez.erl` con `-module(valdez).` y `-export([saludo/0]).`, compílalo con `c(valdez).` y ejecuta `valdez:saludo()`. |

### 37. VALDEZ GARCIA, DIEGO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(37 * 7) + 25` y `37 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, diego, 37, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Scheme", "Datalog", "Clingo", "Erlang"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {5, 6}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(37)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(7)` (5 + (37 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7]` (longitud = 5 + (37 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `17` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(37)`. |
| 10 | Módulo propio | Crea el módulo `valdez2.erl` con `-module(valdez2).` y `-export([saludo/0]).`, compílalo con `c(valdez2).` y ejecuta `valdez2:saludo()`. |

### 38. VAZQUEZ SANCHEZ, CESAR RICARDO

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(38 * 7) + 25` y `38 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, cesar, 38, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Datalog", "Clingo", "Erlang", "Prolog", "OCaml"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {6, 7}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(38)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(8)` (5 + (38 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8]` (longitud = 5 + (38 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `18` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(38)`. |
| 10 | Módulo propio | Crea el módulo `vazquez.erl` con `-module(vazquez).` y `-export([saludo/0]).`, compílalo con `c(vazquez).` y ejecuta `vazquez:saludo()`. |

### 39. YAÑEZ AGUILAR, ADAN

| # | Ejercicio | Enunciado |
|---|---|---|
| 1 | Aritmética en el shell | Calcula `(39 * 7) + 25` y `39 rem 4` usando el shell interactivo `erl`. |
| 2 | Átomos y tuplas | Crea la tupla `{alumno, adan, 39, "3pm"}` y extrae el nombre con pattern matching. |
| 3 | Listas | Define `Materias = ["Clingo", "Erlang", "Prolog", "OCaml", "Haskell", "Clojure"]` y obtén el primer y último elemento con `hd/1` y `lists:last/1` (longitud = 3 + (N rem 4), rotación con inicio N rem 13). |
| 4 | Pattern matching | Dada `Punto = {7, 8}`, escribe una función que extraiga `X` y `Y` y calcule `X*X + Y*Y`. |
| 5 | Función simple | Escribe `duplicar(N) -> N * 2.` y pruébala con `duplicar(39)`. |
| 6 | Recursión — factorial | Implementa `factorial/1` (recursivo) y evalúa `factorial(9)` (5 + (39 rem 5)). |
| 7 | Recursión sobre listas | Implementa `suma_lista/1` que sume los elementos de `[1, 2, 3, 4, 5, 6, 7, 8, 9]` (longitud = 5 + (39 rem 5)). |
| 8 | Expresión `case` | Escribe una función `clasifica(N)` que use `case` para decir si `N` es `positivo`, `negativo` o `cero`; pruébala con `19` (V = N - 20). |
| 9 | Guards | Escribe `es_par(N)` con guards (`when N rem 2 =:= 0`) y evalúa `es_par(39)`. |
| 10 | Módulo propio | Crea el módulo `yanez.erl` con `-module(yanez).` y `-export([saludo/0]).`, compílalo con `c(yanez).` y ejecuta `yanez:saludo()`. |
