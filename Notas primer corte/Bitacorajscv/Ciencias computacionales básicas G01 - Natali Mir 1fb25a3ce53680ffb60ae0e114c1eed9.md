# Ciencias computacionales básicas G01 - Natali Miranda Acosta

Métodos para solucionar problemas que requieren uso de computación con razonamiento y lógica.

# Lógica

→ Estudio del razonamiento correcto

→ Relación de afirmaciones y no el contenido

*“Todos los matemáticos están locos”*

*“Cualquier loco es matemático”*

*→ Por lo tanto cualquier matemático es loco*

Las afirmaciones de la línea 1 y 2 proporcionan las premisas del argumento y la línea 3 proporciona una conclusión. Tan pronto como las premisas sean aceptadas, las concluyentes también deben aceptarse y el argumento es válido.

Las afirmaciones que son proposiciones pueden convertirse en sentencias matemáticas, pero se debe distinguir entre argumentos válidos y argumentos no válidos.

Los argumentos constan de ciertas proposiciones que no pueden subdividirse

→ Estas proposiciones atómicas se unen mediante conexiones lógicas

*“Si la demanda crece, entonces las compañías se expanden”*

→ Si la demanda crece: Proposición atómica.

→ “Entonces”: Conexión lógica

Proposiciones pueden ser oraciones, enunciados que sean afirmaciones y pueden tener un valor de verdadero o falso.

Ejemplo:

1. *“La tierra es plana”* → Proposición
2. “$3+6=8$” → Proposición
3. *“La temperatura interna del sol es de 6000° centígrados”* → Proposición
4. “$x+y=2y$” → Oración 
5. *“¿Desayunaron?”* → Pregunta
6. *“Tome la medicina”* → Orden
7. *“La selección Colombia ganará el partido de hoy”* → Proposición

## Clasificación de proposiciones

→ Símbolos

→ Elementos

Símbolos lógicos

→ P, Q, R

→ Usado para proposiciones atómicas o simples: Una sola oración

→ *“La tierra es plana”*

*→ “Hoy es viernes”*

*→ “El cielo es azul”*

Operadores lógicos

→ ^, v, →, ↔, **⊕, ¬**

→ Usados en proposiciones moleculares o compuestas: 2 o más proposiciones simples

→ “*Si la tierra es plana → la gravedad no existe”*

→ “*El cielo es azul v es verde”*

P: Pitágoras era griego

Q: Pitágoras era matemático

“*Pitágoras era griego y era matemático” →* “P ^ Q”

G: Colombia gana el partido

A: Brasil gana el partido

“*Colombia gana el partido y Brasil no gano” → “*G ^ ¬A”

“*Colombia no gano el partido y Brasil gano” →* “¬G ^ A”

## Operadores lógicos

### Negación y doble negación

→ Se usa para negar una proposición simple

**Tabla de verdad negación y doble negación**

| P | ¬P |
| --- | --- |
| V | F |
| F | V |

| P | ¬(¬P) |
| --- | --- |
| V | V |
| F | F |

Ejemplo

- P: El acusado dice la verdad
- ¬P: El acusado no dice la verdad
- ¬(¬P): No es cierto que el acusado no diga la verdad

### Conjunción

→ 2 afirmaciones verdaderas

→ P ^ Q son verdaderas solo si ambas son verdaderas

**Tabla de verdad conjunción**

| P | Q | P ^ Q |
| --- | --- | --- |
| V | V | V |
| V | F | F |
| F | V | F |
| F | F | F |

| P | Q | P ^ Q |
| --- | --- | --- |
| 1 | 1 | 1 |
| 1 | 0 | 1 |
| 0 | 1 | 0 |
| 0 | 0 | 0 |

Ejemplo

- *“Él gana más de 2 millones, pero menos que 4 millones”*
- “*Él gana más de 2 millones y menos que 4 millones”*

### Disyunción

→ 2 proposiciones por aparte “o”

→ Inclusiva “v”: P v Q es falsa solo si ambas son falsas

→ Exclusiva “**⊕”**: P v Q es falsa cuando ambas tienen el mismo valor

**Tabla de verdad disyunción**

| P | Q | P v Q |
| --- | --- | --- |
| V | V | V |
| V | F | V |
| F | V | V |
| F | F | F |

| P | Q | P **⊕** Q |
| --- | --- | --- |
| V | V | F |
| V | F | V |
| F | V | V |
| F | F | F |

| P | Q | P v Q |
| --- | --- | --- |
| 1 | 1 | 1 |
| 1 | 0 | 1 |
| 0 | 1 | 1 |
| 0 | 0 | 0 |

| P | Q | P **⊕** Q |
| --- | --- | --- |
| 1 | 1 | 0 |
| 1 | 0 | 1 |
| 0 | 1 | 1 |
| 0 | 0 | 0 |

Ejemplo

- “*Mañana salgo a bailar o descansare todo el día”*

### Condicional

→ Implicación

→ (P → Q) es falso si P es verdadero y Q es Falso

→ (P → Q) es desigual a (Q → P)

**Tabla de verdad condicional**

| P | Q | P →Q |
| --- | --- | --- |
| V | V | V |
| V | F | F |
| F | V | V |
| F | F | V |

| P | Q | P → Q |
| --- | --- | --- |
| 1 | 1 | 1 |
| 1 | 0 | 0 |
| 0 | 1 | 1 |
| 0 | 0 | 1 |

Ejemplo

- “*Si salgo de viaje temprano entonces llegare rápido a mi destino”*

### Bicondicional

→ P es equivalente a Q por lo que hay igualdad

**Tabla de verdad bicondicional**

| P | Q | P ↔ Q |
| --- | --- | --- |
| V | V | V |
| V | F | F |
| F | V | F |
| F | F | V |

| P | Q | P ↔ Q |
| --- | --- | --- |
| 1 | 1 | 1 |
| 1 | 0 | 0 |
| 0 | 1 | 0 |
| 0 | 0 | 1 |

Ejemplo

- “*Podré descansar temprano si solo si termino mis tareas temprano”*

### Ejercicios

1. Hacer una tabla de verdad que me muestre a partir de P y Q los operadores lógicos

| P | Q | ¬P | ¬Q | P ^ Q | P v Q | **P ⊕ Q** | P → Q | P ↔ Q | ¬(¬P) | ¬(¬Q) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| V | V | F | F | V | V | F | V | V | V | V |
| V | F | F | V | F | V | V | F | F | V | F |
| F | V | V | F | F | V | V | V | F | F | V |
| F | F | V | V | F | F | F | V | V | F | F |

| P | Q | ¬P | ¬Q | P ^ Q | P v Q | **P ⊕ Q** | P → Q | P ↔ Q | ¬(¬P) | ¬(¬Q) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | 1 | 0 | 0 | 1 | 1 | 0 | 1 | 1 | 1 | 1 |
| 1 | 0 | 0 | 1 | 0 | 1 | 1 | 0 | 0 | 1 | 0 |
| 0 | 1 | 1 | 0 | 0 | 1 | 1 | 1 | 0 | 0 | 1 |
| 0 | 0 | 1 | 1 | 0 | 0 | 0 | 1 | 1 | 0 | 0 |

1. Determine si cada oración es proposición y si lo es entonces escribir su negación
    1. 2 + 5 = 19  (P + Q = R)
        1. Proposición
        2. Negación: 2 + 5 ≠ 19  (P + Q = ¬R)
    2. Todo entero par, mayor que 4 es la suma de 2 primos (P ^ Q → R)
        1. Proposición
        2. Negación: No todos los números enteros pares mayores que 4 son la suma de 2 primos.  (¬P ^ Q → R)
2. Determine si las siguientes proposiciones moleculares son verdaderas o falsas en base a los valores iniciales 
    
    P: F     Q: V      R: F
    
    1. P ^ Q
        1. F^V = F
    2. ¬P v Q
        1. V ^ V= V
    3. ¬P v ¬(Q ^ R)
        1. V v ¬(F) 
        2. V v V 
        3.  V
    4. (P v ¬R) ^ ¬((Q v R) v (R vP))
        1. (V) ^ ¬((V) v (F)) 
        2. (V) ^ ¬(V)
        3. F
3. Tabla de verdad de cada proposición
    1. P ^ ¬Q
    
    | P | Q | ¬Q | P ^ ¬Q |
    | --- | --- | --- | --- |
    | V | V | F | F |
    | V | F | V | V |
    | F | V | F | F |
    | F | F | V | F |
    
     b. ¬(P ^ Q) v (R ^ ¬P)
    
    | P | ¬P | Q | ¬Q | R | P ^ Q | R ^ ¬P | ¬(P ^ Q) v (R ^ ¬P) |
    | --- | --- | --- | --- | --- | --- | --- | --- |
    | V | F | V | F | V | V | F | F |
    | V | F | V | F | F | V | F | F |
    | V | F | F | V | V | F | F | V |
    | V | F | F | V | F | F | F | V |
    | F | V | V | F | V | F | F | V |
    | F | V | V | F | F | F | F | V |
    | F | V | F | V | V | F | V | V |
    | F | V | F | V | F | F | F | V |
    
     c. (P v Q) ^ (¬P v Q) ^ (P v ¬Q) ^ (¬P v ¬Q)
    
    | P | Q | P v Q | ¬P v Q | P v ¬Q | ¬P v ¬Q |  (P v Q) ^ (¬P v Q) ^ (P v ¬Q) ^ (¬P v ¬Q) |
    | --- | --- | --- | --- | --- | --- | --- |
    | V | V | V | V | V | F | F |
    | V | F | V | F | V | V | F |
    | F | V | V | V | F | V | F |
    | F | F | F | V | V | V | F |
4. Construir la tabla de verdad
    - “Mi tío no vino a dormir y no fue a trabajar”
        - Identificar símbolos lógicos en la proposición
        
        → P: Mi tío no vino a dormir
        
        → Q: No fue a trabajar
        
        - Traducción lógica (negativos)
        
        → ¬P y ¬Q
        
        - Definir cuantas posibles variables
        
        → P, Q: $2^2$
        
        → P, Q, R: $2^3$
        
        - Definir la tabla de verdad para las proposiciones y para la combinación
        
        | P | Q | ¬P | ¬Q | ¬P ^ ¬Q |
        | --- | --- | --- | --- | --- |
        | V | V | F | F | F |
        | V | F | F | V | F |
        | F | V | V | F | F |
        | F | F | V | V | V |
        
    
    ## Premisas y conclusiones
    
    Lógica → Estudiar la validez de los argumentos
    
    → Argumento → Número de proposiciones o premisas → 1 premisa = Conclusión
    

                           ↓

        → Validez

Proposición 1, Proposición 2 **∴** Conclusión  → Premisas

 

Ejemplo

“Si Alfredo es elegido presidente de la junta de acción comunal entonces Carmelo es elegido vicepresidente y Martin es elegido tesorero, Carmelo no es elegido vicepresidente por lo tanto Alfredo no es elegido presidente de la junta de acción comunal”

1. Premisas:
    1. Premisa 1: “Si Alfredo es elegido presidente de la junta de acción comunal entonces Carmelo es elegido vicepresidente y Martin es elegido tesorero”
    2. Premisa 2: “Carmelo no es elegido vicepresidente”
    3. Conclusión: “Por lo tanto Alfredo no es elegido presidente de la junta de acción comunal”
2. Proposiciones
    1. A = Alfredo es elegido presidente de la junta de acción comunal
    2. B = Carmelo es elegido vicepresidente
    3. C = Martin es elegido tesorero
3. Traducción lógica
    1. (A → B) ^ C        - Proposición 1
    2. ¬B                        - Proposición 2
    3. ∴  ¬A                   - Conclusión

## Reglas de inferencia y clasificación de argumento

Reglas → Tautología

Inferencia → Contradicción

Clasificación → Contingencia

### Tautología

→ Una proposición es verdadera para todas las proposiciones que sean verdaderas

| P | P ↔ P |
| --- | --- |
| V | V |
| F | V |

### Contradicción

→ Si la proposición ofrece un resultado de valor de verdad entonces será falso

| P | ¬P | P ^ ¬P |
| --- | --- | --- |
| V | F | F |
| F | V | F |

### Contingencia

→ Puede ser verdadero y falso dependiendo del valor de verdad de los componentes simples

| P | Q | ¬P | ¬P v Q |
| --- | --- | --- | --- |
| V | V | F | V |
| V | F | F | F |
| F | V | V | V |
| F | F | V | V |

Ejemplo

1. Verificación de validez

{[(A → B) ^ C] ^ ¬B} ∴  A

| A | B | C | ¬A | ¬B | (A→B) | (A→B)^C | [(A→B)^C]^¬B | {[(A → B) ^ C] ^ ¬B} ∴  A |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| V | V | V | F | F | V | V | F | V |
| V | V | F | F | F | V | F | F | V |
| V | F | V | F | V | F | F | F | V |
| V | F | F | F | V | F | F | F | V |
| F | V | V | V | F | V | V | F | V |
| F | V | F | V | F | V | F | F | V |
| F | F | V | V | V | V | V | V | F |
| F | F | F | V | V | V | F | F | V |
1. “Si Jorge estudia entonces aprobará ciencias computacionales básicas y pensamiento algorítmico, Jorge no aprobó ciencias computacionales básicas, en consecuencia, Jorge no estudio ni aprobó pensamiento algorítmico”
    1. Premisa 1: Si Jorge estudia entonces aprobará ciencias computacionales básicas y pensamiento algorítmico
    2. Premisa 2: Jorge no aprobó ciencias computacionales básicas
    3. Conclusión: En consecuencia, Jorge no estudio ni aprobó pensamiento algorítmico
        1. P - Proposición 1: Jorge estudia
        2. Q - Proposición 2: Jorge aprueba ciencias computacionales básicas
        3. R - Proposición 3: Jorge aprueba pensamiento algorítmico
    
    - (P → Q) ^ R
    - ¬Q
    - ∴  ¬P ^¬R
        
        {[(P → Q) ^ R] ^ ¬Q} ∴  (¬P ^ ¬R)
        
        | P | Q | R | ¬P | ¬Q | ¬R | (Q^R) | [P→(Q^R) | {[(P → Q) ^ R] ^ ¬Q}  | (¬P^¬R) | {[(P → Q) ^ R] ^ ¬Q} ∴  (¬P ^ ¬R) |
        | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
        | V | V | V | F | F | F | V | V | F | F | V |
        | V | V | F | F | F | V | F | F | F | F | V |
        | V | F | V | F | V | F | F | F | F | F | V |
        | V | F | F | F | V | V | F | F | F | F | V |
        | F | V | V | V | F | F | V | V | F | F | V |
        | F | V | F | V | F | V | F | V | F | V | V |
        | F | F | V | V | V | F | F | V | V | F | F |
        | F | F | F | V | V | V | F | V | V | V | V |
    
    ## Reglas de inferencia
    
    → Permiten definir la validez o la no validez de las premisas de los argumentos con simplificaciones cuando se tienen 3 o mas premisas
    
    ### Modus Ponen (MP)
    
    → Eliminar el antecedente siempre que la segunda premisa haga parte de la primera
    
    1. P → Q
    2. P
    3. ∴ Q
    
    ### Modus Tollens (MT)
    
    → Eliminar el consecuente siempre que se encuentre negado
    
    1. P → Q
    2. ¬Q
    3. ∴ ¬P
    
    ### Silogismo Disyuntivo (SD)
    
    → Eliminar una de las disyunciones siempre que en la segunda premisa este negado
    
    1. P v Q
    2. ¬P
    3. ∴ Q
    
    ### Silogismo Hipotético (SH)
    
    → Eliminar de la primera premisa el consecuente siempre que sean iguales
    
    1. P → Q
    2. Q → R
    3. ∴  P → R
    
    ### Adición
    
    → Sumar variables proposicionales a las premisas
    
    1. P
    2. ∴  P v Q
    
    ### Simplificación
    
    → Eliminar proposiciones en las premisas que no se necesitan
    
    1. P ^Q
    2. ∴ P
    
    ### Conjunción
    
    → Unión de 2 premisas
    
    1. P
    2. Q
    3. ∴ P ^ Q
    
    ### Dilema Constructivo
    
    → Eliminar antecedentes, da como resultado una disyunción
    
    1. (P→ Q) ^ (R → S)
    2. P v R
    3. ∴ Q v S
    
    ### Dilema Destructivo
    
    → Eliminar antecedentes siempre y cuando estén vinculados a través de una relación y negación de los consecuentes
    
    1. (P → Q) ^ (R → S)
    2. ¬Q → ¬ S
    3. ∴ ¬P → ¬R
    
    ## Reglas de reemplazo/equivalencias
    
    → Sustituir una parte del argumento para confirmar validez o no
    
    ### Leyes de Morgan
    
    → De disyunción a conjunción
    
    1. ¬(P v Q) ≡ ¬P ^ ¬Q
    2. ¬(P ^ Q) ≡ ¬P v ¬Q
    
    ### Conmutación
    
    → Establecer y cambiar el orden lógico de la proposición
    
    1. (P v Q) ≡ (Q v P)
    2. (P ^ Q) ≡ (Q ^ P)
    3. (P ↔ Q) ≡ (Q ↔ P)
    
    ### Doble negación
    
    → Si tenemos una negación que se vuelve a negar es afirmación
    
    1. ¬(¬P) ≡ P
    
    ### Distribución
    
    → Se opera dentro de paréntesis y se distribuye fuera de los mismos
    
    1. P ^ (Q v R) ≡ (P ^ Q) v (P ^ R)
    2. P v (Q ^ R) ≡ (P v Q) ^ (P v R) 
    
    ### Tautología
    
    → Unir 2 proposiciones en una sola
    
    1. (P ^ Q) ≡ P
    2. (P v P) ≡ P
    
    ### Asociación
    
    → Aplica si tenemos el mismo operador lógico
    
    1. P ^ (Q ^ R) ≡ (P ^ Q) ^ R
    2. P v (Q v R) ≡ (P v Q) v R
    
    ### Implicación Material
    
    → Implica a disyunción o conclusión
    
    1. P → Q ≡ ¬P v Q
    
    ### Transposición
    
    → Tener una negación del consecuente implica que se niega el antecedente también
    
    1. P → Q ≡ ¬Q → ¬P
    
    ### Exportación
    
    → Cambiar conjunción a una implicación
    
    1. [(P ^ Q) → R] ≡ [P → (Q → R)]
    
    ### Equivalencia material
    
    → Si tenemos una relación con doble implicación es igual a la conjunción/disyunción de sus implicaciones
    
    1. (P ↔ Q) ≡ (P → Q) ^ (Q → P)
    2. (P ↔ Q) ≡ (P ^ Q) v (¬P → ¬Q)
    
    ## Prueba Formal de Validez
    
    1. Asignar a las proposiciones un símbolo lógico (P, Q, R, A, entre otros)
    2. Traducir las proposiciones a premisas lógicas
    3. Organizar el argumento de forma vertical separando una de la otra
    4. Usar reglas de inferencia/remplazo que puedan conducir a nuevas premisas para simplificar
    5. Obtener el resultado o conclusión
    
    Ejemplo
    
    “Si la ley no fue aprobada entonces la constitución del país queda sin modificaciones, si la constitución del país quedan sin modificaciones no se pueden elegir nuevos diputados o se eligen nuevos diputados o el informe del presidente del país se retrasará, el informe no se atrasó un mes por lo que la ley fue aprobada”
    
    1. Asignar símbolos lógicos a las proposiciones
        1. L: “La ley fue aprobada”
        2. C: “La constitución quedó sin modificaciones”
        3. D: “Se elijen nuevos diputados”
        4. I: El informe del presidente se atrasó un mes
    2. Traducir a proposiciones lógicas en formato vertical
        1. (¬L → C)
        2. (C → ¬D)
        3. (D v I)
        4. ¬ I
        5. ∴  L
    3. Usar reglas de inferencia/remplazo para crear nuevas premisas
        1. SD en a y b = D
        2. MT en b y  a2 = ¬C
        3. MT en a1 y b2 = L
    4. Obtuvimos el resultado o conclusión “L” por lo que confirmamos que es un argumento válido.
    
    Ejemplo
    
    “Si el tiempo es agradable entonces el cielo esta despejado si el cielo esta despejado entonces iré de día de campo, si el tiempo es agradable entonces iré de día de campo implica que si el cielo esta despejado entonces nadaré en el rio, si el tiempo es agradable entonces nadare en el rio implica que me broncearé por lo tanto me broncearé todo el cuerpo”
    
    1. -
        1. T: “El tiempo es agradable”
        2. D: “El cielo esta despejado”
        3. C: “Iré de día de campo”
        4. N: “Nadaré en el rio”
        5. B: “Me broncearé todo el cuerpo”
    2. -
        1. T → D
        2. D → C
        3. (T → C) → (D → N)
        4. (T → N) → B
        5. ∴ B
    3. -
        1. SH en a y b = T → C
        2. MP en a2 y c = D → N
        3. SH en a1 y b2 = T → N
        4. SH en c2 y d= B
    
     
    
    Ejemplo
    
    1. (¬H v I) → (J → K)
    2. (¬L ^ M) → (K → N)
    3. (H → L) ^ (L → H)
    4. (¬L ^ ¬M) ^ ¬I
    
    ∴  J → N
    
    1. ¬L ^ ¬M - *Simplificación 4*
    2. ¬L - *Simplificación 5*
    3. H → L - *Simplificación 3*
    4. K → N - *MP 2 y 5*
    5. ¬H -*MT 7 y 6*
    6. ¬H v I - *Adición* 
    7. J → K - *MP 1 y 10*
    8. J → N - *SH 11 y 8*
    
    ## Prueba de invalidez
    
    1. Asignar a las proposiciones un símbolo lógico (P, Q, R, A, entre otros)
    2. Traducir las proposiciones a premisas lógicas
    3. Organizar el argumento de forma horizontal
    4. Aplicar valores de verdad a la conclusión para que el resultado sea falso siempre
    5. Como la conclusión es falsa las premisas deben de tener un valor de verdadero resolviendo operaciones lógicas
    
    Ejemplo
    
    “Si llueve entonces me mojo si sale el sol entonces me pongo ropa ligera me mojo o sale el sol por lo tanto llueve o me pongo ropa ligera”
    
    1. Asignar símbolos lógicos
        1. L: “Llueve”
        2. M: “Me mojo”
        3. S: “Sale el sol”
        4. R: “Me pongo ropa ligera”
    2. Traducir a premisas lógicas organizadas de forma horizontal
        1. {[(L → M) ^ (S → R)] ^ (M v S)} ∴ (L v R)
        
        ```mermaid
        graph TD
            %% Nodos principales para las operaciones
            A["L → M (F,V)"] --> E["V"]
            B["S → R (F,F)"] --> F["V"]
            C["M v S (V,F)"] --> G["V"]
            D["L v R (F,F)"] --> H["F"]
        
            %% Uniones de resultados
            E --> I["V"]
            F --> I
            I --> J["V"]
            G --> J
            J --> K["F"]
            H --> K
        
            %% Estilo y colores
            style A fill:##f2d5f2,stroke:#333
            style B fill:##f2d5f2,stroke:#333
            style C fill:##f2d5f2,stroke:#333
            style D fill:##f2d5f2,stroke:#333
            style K fill:##f2d5f2,stroke:#333
        ```
        
    
    Ejemplo
    
    1. A → (B → C)
    2. B → (¬C → D)
    3. (C v D) → E
    4. ∴  A → E
    
    {[(A → (B → C)) ^ (B → (¬C → D)) ^ ((C v D) → E)]} ∴ (A → E)
    
    ```mermaid
    graph TD
        %% Nodos principales para las operaciones
        A["A → (B → C) (V,F,F)"] --> E["V"]
        B["B → (¬C → D) (F,V,F)"] --> F["V"]
        C["(C v D) → E (F,F,F)"] --> G["V"]
        D["A → E (F,F)"] --> H["F"]
    
        %% Uniones de resultados
        E --> I["V"]
        F --> I
        I --> J["V"]
        G --> J
        J --> K["F"]
        H --> K
    
        %% Estilo y colores
        style A fill:##f2d5f2,stroke:#333
        style B fill:##f2d5f2,stroke:#333
        style C fill:##f2d5f2,stroke:#333
        style D fill:##f2d5f2,stroke:#333
        style K fill:##f2d5f2,stroke:#333
    ```
    
    Ejercicios
    
    Realice la prueba de invalidez en los siguientes argumentos
    
    1. 
        1. A ↔ B
        2. C → D
        3. B ↔ C
        4. ∴ A ^ D
        
        {[(A ↔ B) ^ (C → D)] ^ (B ↔ C)} ∴ A ^ D
        
        ```mermaid
        graph TD
            %% Nodos principales para las operaciones lógicas
            A["A ↔ B (F,F)"] --> E["V"]
            B["C → D (F,V)"] --> F["V"]
            C["B ↔ C (F,F)"] --> G["V"]
            D["A ^ D (F,V)"] --> H["F"]
        
            %% Uniones de resultados
            E --> I["V"]
            F --> I
            I --> J["V"]
            G --> J
            J --> K["F"]
            H --> K
        
            %% Estilo y colores
            style A fill:##f2d5f2,stroke:#333
            style B fill:##f2d5f2,stroke:#333
            style C fill:##f2d5f2,stroke:#333
            style D fill:##f2d5f2,stroke:#333
            style K fill:##f2d5f2,stroke:#333
        ```
        
    2. 
        1. H → (I v J)
        2. J → (S ^ X)
        3. ¬S
        4. ∴ H → X
    
    {[(H → (I v J)) ^ (J → (S ^ X))] ^ ¬S} ∴ H → X
    
    ```mermaid
    graph TD
        %% Nodos principales para las operaciones lógicas
        A["H → (I v J) (V,V,F)"] --> E["V"]
        B["J → (S ^ X) (F,F,F)"] --> F["V"]
        C["¬S (V)"] --> G["V"]
        D["H → X (F,V)"] --> H["F"]
    
        %% Uniones de resultados
        E --> I["V"]
        F --> I
        I --> J["V"]
        G --> J
        J --> K["F"]
        H --> K
    
        %% Estilo y colores
        style A fill:##f2d5f2,stroke:#333
        style B fill:##f2d5f2,stroke:#333
        style C fill:##f2d5f2,stroke:#333
        style D fill:##f2d5f2,stroke:#333
        style K fill:##f2d5f2,stroke:#333
    ```
    
    ## Prueba Condicional
    
    → Para revisar la validez del argumento y de la conclusión
    
    1. Asignar a las proposiciones un símbolo lógico (P, Q, R, A, entre otros)
    2. Traducir las proposiciones a premisas lógicas
    3. Organizar el argumento de forma vertical
    4. Cuando el antecedente de la conclusión es una implicación se toma como una premisa mas
    5. Consecuente de la conclusión como la conclusión final
    6. Usar prueba de validez hasta llegar a el resultado/conclusión
    
     
    
    Ejemplo
    
    Demostrar la validez por medio de prueba condicional
    
    “Si salgo temprano de trabajar entonces iré a la fiesta si voy a la fiesta entonces vere a la chica que me gusta si veo a la chica que me gusta entonces bailare toda la noche por lo que si salgo temprano de trabajar bailare toda la noche”
    
    1. 
        1. T: “Salgo temprano”
        2. F: “Iré a la fiesta”
        3. C: “Veré a la chica que me gusta”
        4. B: “Bailaré toda la noche”
    2. 
        1. T → F
        2. F → C
        3. C → B
        4. ∴ T → B
    3.         ↓
        1. T → F
        2. F → C
        3. C → B
        4. T
        5. ∴ B
    4. 
        1. F - *MP a y d*
        2. C - *MP b y a2*
        3. B - *MP a y b2*
    5. Como llegamos a la conclusión podemos confirmar la validez del argumento
    
    Ejercicio
    
    “Si estudio implica que si apruebo ciencias básicas entonces pasare el semestre, por lo tanto, si estudio entonces aprobare ciencias básicas implica que si estudio pasare el semestre”
    
    1. 
        1. E: “Estudio”
        2. S: “Pasaré el semestre”
        3. C: “Apruebo ciencias básicas”
    2. 
        1. E → (C → S)
        2. ∴ (E → C) → (E → S)
    3.         ↓
        1. E → (C → S)
        2. (E → C)
        3. ∴ (E → S)
    4.        ↓
        1. E → (C → S)
        2. (E → C)
        3. E
        4. ∴ S
    5. 
        1. C - *MP b y c*
        2. C → S - *MP a y c*
        3. S - *MP a2 y b2*
    
    Ejercicio
    
    1. Si P y Q son falsas y R y S son verdaderas cual es el valor de verdad de las siguientes premisas:
        1. ¬(P ^ R)
            1. Verdadero
        2. ¬(P v ¬R)
            1. Verdadero
        3. ¬(¬P v ¬Q) → S
            1. Verdadero
        4. ¬(¬(¬P) ^ ¬(¬Q))
            1. Verdadero
    2. Teniendo en cuenta las siguientes proposiciones, traduzca a lenguaje natural
        1. F: “Como frutas y verduras”
        2. S: “Estoy Sano”
            1. F ^ S: “Como frutas y estoy sano”
            2. ¬F: “No como fruta”
            3. ¬(¬F): “No es verdad que no como frutas”
            4. ¬(F → S): “No es cierto que si como frutas estaré sano”
            5. (F → ¬S): “Como frutas entonces no estoy sano”
            6. ¬(F ↔ S): “No es cierto que si solo si como frutas estaré sano”
    
    ## Primer Principio de inducción matemática
    
    → En las proposiciones tecnico-matematico que tienen la siguiente construcción:
    
    → Base propositiva Pn → V
    
    → Base inductiva P(n+1) → V
    
    Si Pn (base propositiva) es verdadera P(n+1) (base inductiva) es verdadera siempre que Pn sea verdadera
    
    Pn → Pn+1 → Para todo n que pertenezca a los números positivos 
    
    ∑ → suma referenciada dentro de una cota
    
    $n∑(k=1) K² = (1)²+(2)²+(3)³+(n)²$
    
    Ejemplo 
    
    Demostrar la sumatoria $3∑(k=1) (3k-2) = 1/2(3n²-n) |∀ n ∈+$
    
    Pn extender a $n=k | k ∈+$
    
    $Pn= 1/2 (3 (1)² - 1) = 1 →(3 (1) - 2) = 1$
    
    → Comprobar que $K→ 3∑(k=1)(3k-2)$ es igual a $n→1/2(3 (1)² - 1)$ si da el mismo número es valido
    
    $Pm [m∑(k=1) (3k-2)=1/2 (3 m² - m)]$ → Hipótesis
    
     
    
    Se quiere comprobar que P(m+1) sea verdadera
    
    $m+1∑(k=1)(3k-2) = 1/2(3(m+1)^2 -(m+1))$
    
    → Desarrollamos el lado izquierdo
    
     $m∑(k=1)(3k-2) = m∑(k=1)(3k-2)+(3(m+1)-2)$
    
    → Usamos la hipotesis
    
    $= 1/2(3m^2 - m) + (3m + 3 - 2) = = 1/2 (3m^2 - m) + (3m+1)$
    
    → $(3m^2 + 5m +2)/(2)$
    
    → Desarrollamos el lado derecho
    
    = $1/2 (3(m+1)^2 - (m + 1))$ 
    
    = $1/2(3(m^2 + 2m +1) - m - 1)$
    
    = $1/2(3m^2 +5m +2)$
    
    → Comparamos el resultado de ambos lados
    
    $(3m^2 + 5m +2)/(2) = (3m^2 + 5m +2)/(2)$
    
    → Como ambos lados son iguales podemos concluir que la fórmula es válida para $n=m+1$
    
    Ejercicio
    
    1. Caso base n=1, evaluar para ambos lados los valores
        1. $P(n) = 1+2+3+…+n = (n(n+1)/(2)$
            
            → Reemplazamos las incógnitas con el número de caso base
            
        2. $1 = 1(1+1)/2 → 1 = 1$
            
            → Se cumple el caso base
            
    2. Plantear la hipótesis de inducción: Suponer verdadero que n=k
        1. $P(k) = 1+2+3+…+k = k(k+1)/(2)$
            
            → Suponemos valida
            
    3. Inductivo la formula sea válida para n=k+1
        1. $P(k+1) = 1+2+3+…+k+(k+1) = k+1(k+2)/2$
            
            → Usamos hipótesis de inducción
            
        2. $P(k+1) = P(k) + k+1$
        3. $P(k+1) = k(k+1)/(2) + (k+1)$
            
            → $k(k+1)+(2k+2)/(2)$
            
            →$k^2 + k+2k+2/2$
            
            →$k^2 +3k+2/2$
            
            →$(k+1)(k+2)/2$
            
    4. Comparamos
        1. $k+1(k+2)/(2) = (k+1)(k+2)/(2)$
