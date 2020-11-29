# Introducció:

## Tipus de Software:

Hi ha tres tipus de software:

- **De sistema** (sistema operatiu, drivers)
- **De aplicació** (Suite ofimàtic, Navegador, Edició de imatge, ...)
- **De desenvolupament** (Editors, copiladors, interpretes,...)

## Relació Hardware-Software:

- **Disc Dur:** guarda informació de forma permanent als arxius executables i els arxius de dades.

- **Memòria RAM:** emmagatzema de forma temporal el codi binari dels arxius executables i els arxius de dades necessaries.

- **CPU:**  Llegeix i executa instruccions emmagatzamades en memòria RAM.

- **E/S:** Agafa noves dades desde la entrada, es mostra els resultats, es llegeixen / guarden a disc...

## Tipus de Codi:

- **Codi font:** Arxiu de text llegible escrit en un llenguatge de programació.
- **Codi objecte:** (intermedi) Arxiu binari no executable.
- **Codi executable:** Arxiu binari executable.

# Cicle de vida del software:

## Ingeniería de software:

Disciplina que estudia els principis i metodologías per el desenvolupament i manteniment de sistema software.

- Alguns autors consideran que **desenvolupament de software** és un termini més apropiat que **ingeniería de software**.

## Desenvolupament de Software:

- **ANÀLISI**

    Es determina i defineix la necessitat del client i s'especifica els requisits que s'han de cumplir.

  - Ha de ser completa i sense omisions.
  - Ser concisa i sense trivialitats.
  - Ser entedible per el client
  - Separar requisits funcionals i no funcionals
  - Fixar criteris de validació


- **DISENY**

  - Es descompon i s'organitza el sistema en elements components que poden ser desenvolupats per separat.

  - Les activitats habituals són les següents:

  - Diseny arquitectónic
  - Diseny detallat
  - Diseny de dades
  - Diseny de interfície

- **CODIFICACIÓ**

  - S'escriu el codi font de cada component.
  - Poden utilitzar-se diferents llenguatges informàtics:
    - **LLenguatges de programació:** C, C++, Java, Javascript, ...
    - **LLenguatges d'un altre tipus:** HTML, XML, JSON, ...

- **PROVAS**

  - El principal objectiu de les proves te que ser conseguir que el programa funcioni incorrectement i que es descubreixin defectes.

  - Tenim que sometre el programa al màxim número de situacions diferents.

- **MANTENIMENT**

  - Durant l'explotació del sistema software es necessari realitzar canvis ocasionals.

  - Per això s'ha de tornar a fer part del treball realitzat en las fases previas.

  - Tipus de manteniment:
    - **Correctiu:** Es correigeixen defectes.
    - **Perfectiu:** Es millora la funcionalitat.
    - **Evolutiu:** S'afageix funcionalitats novas.
    - **Adaptatiu:** S'adapta a nous entorns.

## Models de desenvolupament de software:

- **Models clàssics (predicatius):**
  - Model en cascada
  - Model en V
- **Model de construcció de prototips**
- **Model evolutius o incrementals**
  - Model en espiral(iteratius)
  - Metodologías ágils (adaptatius)

### Model en cascada:

![](assets/cascada.png)
- Model de major atiguitat.
- Identifica las fases principals del desenvolupament de software.
- Las fases han de realitzar-se en el ordre correcte.
- El resultat de una fase en l'entrada de la següent fase.
- És un model bastant rígid que s'adapta malament al canvi continu de especificacions.
- Existeixen diferents variants amb major o menor cantitat d'activitats.

### Model en V:

![](assets/v.png)
- Model molt semblant al model cascada.
- Visió jerarquica amb diferents nivells.
- Els nivells superiors indican major abstracció.
- Els nivells inferiors indican major nivell de detall.
- El resultat de una fase es la entrada de la següent fase.
- existeixen diferents variants amb major o menor cantitat d'activitats.

### Prototips:

- Sobint els requisits no estàn especificats clarament:
  - per no existir experiència prèvia.
  - per omisió o falta de concreació del usuari/client
![](assets/prototips.png)

- Procés:
  - Es crea un prototip durant la **fase d'anàlisi** i es prova per l'usuari/client per refinar els requisits del software a desenvolupar.
  - Es repeteix el pas anterior las vegades necessaries.

- Tipus de prototips:
  - **Prototips ràpids**
    - El prototip pot estar desenvolupat utilitzan un altre llenguatge i/o eines.
  - **Prototips evolutius**
    - El prototip està dissenyat en el mateix llenguatge i eines del projecte.
    - El prototip s'utilitza com a base per a desenvolupar el projecte.


### Model en espiral:

- Desenvolupat per Boehm en 1988.
- L'activitat **d'ingeniería**correspon a las fases dels models clàssics: anàlisi, diseny, codificació,...
![](assets/espiral.png)

**APLICAT A LA PROGRAMACIÓ ORIENTADA A OBJECTES**

- En l'activitat de **ingeniería** es dona gran importància a la reutilització de codi.
![](assets/espiral2.png)

### Metodologías àgils

- Són mètodes de ingeniería del software basats en el desenvolupament iteratiu e incremental.
- El treball es realitza mitjançant la col·laboració d'equips organitzats i disciplinats.
- Les metodologías més conegudes són:
  - Kanban
  - Scrum
  - XP (eXtreme Programming)

#### KANBAN:

- Tambè conegut per sistema de tarjes.
- Desenvolupat per Toyota per la industria de fabricació de productes.
- enfocat a entregar el màxim valor per els clients.
![](assets/kanban.png)

#### SCRUM:

- Model de desenvolupament incremental.
- Iteracions **(sprint) regulars** cada 2, 3 o 4 semanas.
- Al finalizar cada iteració s'obté una **entrega parcial utilizable por el client**.

![](assets/scrum.png)

### ROLES PRINCIPALES:

**Product Owner** Es "la voz del cliente". Define criterios de aceptación y asegura de que se cumplan.

**Scrum Master** Asegura que se sigue la metodología Scrum. Motiva y facilita el trabajo del equipo.

**Team** Equipo de desarrollo auto-organizado y multifuncional. Entre 6 y 10 miembros.

## XP (PROGRAMACIÓN EXTREMA):

### VALORES:

- Simplicidad
- Comunicación
- Retroalimentación
- Valentía o coraje
- Respeto o humildad

### CARACTERÍSTIQUES:

- Diseño sencillo
- Pequeñas mejoras continuas
- Pruebas y refactorización
- Integración continua
- **Programación por parejas**
- **El cliente se integra en el equipo de desarrollo**
- Propiedad del código compartida
- Estándares de codificación
- 40 horas semanales

### LLENGUATGE DE PROGRAMACIÓ:

Para obtener código binario ejecutable tenemos 2 opciones:

- Compilar
- Interpretar

### PROCESO DE COPILACIÓN / INTERPRETACIÓN

La compilación/interpretación del código fuente se lleva a cabo en dos fases:
- Análisis léxico
- Análisis sintáctico
- Si no existen errores, se genera el código objeto correspondiente.
- Un código fuente correctamente escrito no significa que funcione según lo deseado.
- No se realiza un análisis semántico.

### LENGUAJES COMPILADOS


- Ejemplos: C, C++
- Principal ventaja: Ejecución muy eficiente.
- Principal desventaja: Es necesario compilar cada vez que el código fuente es modificado.

### LENGUAJES INTERPRETADOS

- Ejemplos: PHP, Javascript
- Principal ventaja: El código fuente se interpreta directamente.
- Principal desventaja: Ejecución menos eficiente.

### JAVA

- Lenguajes compilado e interpretado.
- El código fuente Java se compila y se obtiene un código binario intermedio denominado **bytcode.**
- Despúes este **bytcode** se interpreta para ejecutarlo.

### JAVA (II)

- Ventajas:
  - Estructurado y orientado a objetos
  - Relativamente fácil de aprender
  - Buena documentación y base de usuarios

- Desventajas
  - Menos eficiente que los lenguajes copilados

### TIPOS

- Según la forma en la que operan:
  - **Declarativos:** indicamos el resultado
  - **Imperativos:** idicamos los pasos a seguir para obtener un resultado.

### TIPOS (II)

- Tipos de **lenguajes declarativos**:
  - **Lógicos:** Utilizan reglas. EJ: Prolog.
  - **Funcionales:** Utilizan funciones. Ej: Lisp, Haskell
  - **Algebraicos:** Utilizan sentencias. Ej: SQL
- Normalmente son lenguajes interpretados.

### TIPOS (III)

- Tipos de lenguajes imperativos:
  - Estructurados: C
  - Orientados a objetos: Java
  - Multiparadigma: C++, Javascript
- Los lenguajes orientados a objetos son también lenguajes estructurados.
- Muchos de estos lenguajes son compilados.

### TIPOS (IV)

- Tipos de lenguajes según nivel de abstracción:
 - Bajo nivel: ensamblador
 - Medio nivel: C
 - Alto nivel: C++, Java

### EVOLUCIÓN

- Código binario
- Ensamblador
- Lenguajes estructurados
- Lenguajes orientados a objetos

### HISTORIA

![](assets/historia.png)

### CRITERIOS PARA LA SELECCIÓN DE UN LENGUAJES

- Campo de aplicación
- Experiencia previa
- Herramientas de desarrollo
- Documentación disponible
- Base de usuarios
- Reusabilidad
- Portabilidad
- Imposición del cliente
