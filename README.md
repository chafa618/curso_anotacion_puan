{% include head.html %}

## Requerimientos técnicos

En la cursada vamos a utilizar diversos recursos computacionales, ......
## Cronograma de clases y materiales

<table>
  <tr>
    <th>Clase</th>
    <th>Fecha</th>
    <th>Temas</th>
    <th>Materiales</th>
  </tr>
  <tr>
    <td><a href="./Clase1/index.md">01</a></td>
    <td>22/03/25</td>
    <td>
        <ul>
            <li>Presentación del seminario.</li>
            <li>Dinámica de clases.</li>
            <li>1. la inteligencia artificial</li>
            <li>2. programación clásica vs. el aprendizaje automático (machine learning).</li>
            <li>3. Procesamiento del lenguaje natural: definición, tareas y enfoques;</li>
            <li>4. lenguaje de programación Python en Google Colab (tipos de datos, variables, sintaxis básica)</li>
        </ul>
    </td>
    <td>
        <ul>
            <li><a href="https://forms.gle/aogRG9iQtLSGnf3q9">Form de presentación</a></li>
            <li><a href="./Instructivos/github_user.md">Nuevo Instructivo</a></li>
            <li><a href="./Instructivos/tutorialmv.pdf">Otro Recurso especifico</a></li>
        </ul>
    </td>
  </tr>
  <tr>
    <td><a href="./Clase2/index.md">02</a></td>
    <td>29/03/25</td>
    <td>
        <ul>
            <li>A completar.</li>
            <li>A completar...</li>
            <li>Introducción a Python.</li>
        </ul>
    </td>
    <td>
      <ul>
        <li><a href="./Clase-02/git-basics.md">Apunte sobre git</a></li>
        <li><a href="./TPs/tp1.md">TP #1</a></li>
        <li><a href="./Clase-02/handout.pdf">Apuntes sobre formalización</a></li>
        <li><a href="./Clase-02/intro-python.md">Notebook sobre Python</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><a href="./Clase-03/index.md">03</a></td>
    <td>12/04/22</td>
    <td>
        <ul>
            <li>Jerarquía de lenguajes formales. Gramáticas, autómatas y lenguajes. Equivalencia débil y equivalencia fuerte; teoría de la complejidad.</li>
        </ul>
    </td>
    <td>
    <ul>
    	<li><a href="./Clase-03/handout.pdf">Apunte sobre jerarquía de Chomsky</a></li>
    	<li><a href="./Clase-03/Clase-03-jupyter.md">Notebook sobre librería re</a></li>
    </ul>
    </td>
  </tr>
  <tr>
    <td><a href="./Clase-04/index.md">04</a></td>
    <td>19/04/22</td>
    <td>
      <ul>
        <li>Gramáticas Independientes de contexto. Definición; axiomas de dominancia y de precedencia. Algunas limitaciones.</li>
        <li>Parsers: RecursiveDescentParser (NLTK), Shift-ReduceParser (NLTK), ChartParser (NLTK).</li>
      </ul>
    </td>
    <td>
      <ul>
      	<li><a href="./Clase-04/handout.pdf">Apunte sobre CFG</a></li>
        <li><a href="./Clase-04/Clase-04-jupyter.md">Notebook sobre CFG</a></li>	
        <li><a href="./TPs/tp2.md">TP #2</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><a href="./Clase-05/index.md">05</a></td>
    <td>26/04/22</td>
    <td>
      <ul>
        <li>Diferenciación entre reglas de precedencia lineal y reglas de dominancia inmediata, metarreglas, postulados de significado. Principios: la convención de Rasgo Nuclear (Head Feature Convention), principio del rasgo Foot (Foot Feature Principle), principio del control de la concordancia, Restricciones de Coaparición de Rasgos, reglas léxicas.</li>
        <li>El declive de GPSG: insuficiencia del poder restrictivo de las gramáticas independientes de contexto, complejidad computacional de GPSG.</li>
      </ul>
    </td>
    <td>
      <ul>
    <li><a href="./Clase-05/handout.pdf">Apunte sobre GPSG</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><a href="./Clase-06/index.md">06</a></td>
    <td>03/05/22</td>
    <td>
      <ul>
        <li>Repaso de la gramática generativa. El minimalismo. Operaciones básicas: ensamble interno, ensamble externo, agree. Teoría de X'. Teoría de la frase desnuda. Estructura básica de la cláusula.</li>
        <li>Gramáticas minimalistas (Minimalist grammars). Las operaciones de selección, ensamble (Merge), el léxico y los ítems léxicos.</li>
        <li>Implementación en Prolog: mgpx parser.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="./Clase-06/handout.pdf">Apunte sobre Gramáticas Minimalistas</a></li>
        <li><a href="./Clase-06/ParserMinimalistaStabler1/instructions.md">Instrucciones para correr un parser minimalista en Prolog</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><a href="./Clase-07/index.md">07</a></td>
    <td>10/05/22</td>
    <td>
      <ul>
        <li>Gramáticas minimalistas con ensamble interno (movimiento de remanentes, movimiento de núcleos).</li>
        <li>Implementación en Prolog y Python: mghapx parser e implementación del minimalismo de <a href="https://github.com/alexwarstadt/minimalism">Alex Warstadt</a>.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="./Clase-07/ParserMinimalistaStabler2/instructions.md">Instrucciones para correr un parser minimalista en Prolog</a></li>
        <li><a href="./Clase-07/handout.pdf">Apunte sobre Gramáticas Minimalistas</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><a href="./Clase-08/index.md">08</a></td>
    <td>17/05/22</td>
    <td>
      <ul>
        <li>Gramática minimalista. Adjunción, los operadores >> y << </li>
        <li>Nociones básicas de las gramáticas de unificación y rasgos: matrices de rasgos, rasgos simples y complejos, unificación y subsunción.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="./Clase-08/ho-minimalismo3.pdf">Apunte sobre Gramáticas Minimalistas</a></li>
        <li><a href="./TPs/tp3.pdf">TP #3</a></li>
        <li><a href="./Clase-08/handout-fcfg.pdf">Apunte sobre FCFG</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><a href="./Clase-09/index.md">09</a></td>
    <td>24/05/22</td>
    <td>
      <ul>
        <li>Gramáticas de unificación y rasgos. Implementación mediante Feature-based grammars en NLTK</li>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="./Clase-09/fcfg.md">Notebook sobre FCFG</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><a href="./Clase-10/index.md">10</a></td>
    <td>31/05/22</td>
    <td>
      <ul>
        <li>LFG: estructura-c, estructura-f, estructura-a, ecuación funcional y descripción funcional.</li>
        <li>Implementaciones computacionales: XLE (demo).</li>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="./Clase-10/handout.pdf">Apunte sobre LFG</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><a href="./Clase-11/index.md">11</a></td>
    <td>07/06/22</td>
    <td>
      <ul>
        <li>Gramáticas de dependencias. La noción de dependencia. Motivaciones para las gramáticas de dependencias. Tipos de dependencias: semánticas, sintácticas y morfológicas.</li>
        <li>Definición formal. Axiomas de las Gramáticas de dependencias: condición de raíz única, conectividad, no multidominancia, proyectividad.</li>
        <li>Implementación computacional; Spacy, MaltParser, parser de dependencias de Freeling, PyStanford Dependencies.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="./Clase-11/handout.pdf">Apunte sobre Gramáticas de Dependencias</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><a href="./Clase-12/index.md">12</a></td>
    <td>14/06/22</td>
    <td>
      <ul>
        <li>Gramática de dependencias como cuádrupla: relaciones, terminales, categorías, funciones de asignación.</li>
        <li>Implementación computacional: ProjectiveDependencyParser de NLTK en Python.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="./Clase-12/handout.pdf">Apunte sobre DG como cuádrupla</a></li>
        <li><a href="./Clase-12/dependency-parsers.md">Notebook sobre DP</a></li>
        <li><a href="./Clase-12/spacy-intro.md">Notebook sobre spaCy</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><a href="./Clase-13/index.md">13</a></td>
    <td>21/06/22</td>
    <td>
      <ul>
        <li>Gramáticas categoriales: Conectivas. Reglas: aplicación, asociatividad, composición, ascenso/Regla de Geech, división. Representación de la estructura sintáctica en términos de funciones y argumentos.</li>
        <li>Implementación de una gramática categorial clásica con el parser NLTK. CCG en Python. Proyecto OpenCCG.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="./Clase-13/Clase-13-jupyter.md">Visualización de Notebook</a></li>
        <li><a href="./Clase-13/handout.pdf">Apunte de introducción a gramáticas categoriales</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><a href="./Clase-14/index.md">14</a></td>
    <td>28/06/22</td>
    <td>
      <ul>
        <li>Notación lambda. Paralelismo entre la sintaxis y la semántica. Reglas léxicas.</li>
        <li>Gramáticas categoriales generalizadas. Implementación en NLTK y CCG.</li>
      </ul>
    </td>
    <td>
      <ul>
        <li><a href="./Clase-14/handout.pdf">Apunte sobre gramáticas categoriales generalizadas</a></li>
        <li><a href="./Clase-14/Clase-14-jupyter.md">Visualización de Notebook</a></li>
        <li><a href="./TPs/tp4.pdf">TP4</a></li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><a href="./Clase-15/index.md">15</a></td>
    <td>05/07/22</td>
    <td>
      <ul>
        <li>Cierre de cursada.</li>
        <li>Presentación del <a href="./TPs/trabajo-final.pdf">trabajo final</a>.</li>
      </ul>
    </td>
    <td></td>
  </tr>
</table>

{% include change_href.html %}

{% include additional_content.html %}
