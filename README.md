# Desafio 06 | Anáhuac

- [Desafio 06 | Anáhuac](#desafio-06--anáhuac)
  - [1. Sobre a Anáhuac](#1-sobre-a-anáhuac)
  - [2. Problema de negócio](#2-problema-de-negócio)
  - [3. Objetivo](#3-objetivo)
  - [4. Desenvolvendo a solução](#4-desenvolvendo-a-solução)
  - [Licença](#licença)


## 1. Sobre a Anáhuac

A Universidade Anáhuac está comprometida com a excelência educacional e procura fazer a maior contribuição possível para o mundo educacional. Neste esforço, a Rede Universitária tem 56 bacharelados, 50 mestrados, 33 especializações e 17 doutoramentos oferecidos na modalidade presencial. Na modalidade on-line, existem 117 programas de educação continuada, 18 mestrados e 7 especializações, com um total de quase 6000 alunos. Atualmente, foram identificados os três desafios seguintes no setor educacional do México:

Garantir o acesso à educação, a fim de permitir a todas as pessoas de diferentes estratos sociais o direito a uma educação digna.
2. manutenção de uma alta qualidade de educação. Dentro deste ponto, a Universidade Anáhuac procura não apenas desenvolver uma educação com alta qualidade profissional, mas também formar estudantes com alta qualidade ética e social.
3. maximizar o sucesso acadêmico dos estudantes, ou seja, dentro dos estudantes que acessam os diferentes níveis educacionais, a taxa de estudantes que completam seus programas é alta.

## 2. Problema de negócio

A Universidade Anahuac procura aumentar o sucesso acadêmico dos estudantes através de diferentes estratégias acadêmicas e da geração de diferentes planos de apoio social e emocional para seus estudantes. No entanto, eles acreditam que ainda podem fazer mais para garantir o sucesso acadêmico de seus alunos.

No que diz respeito à educação on-line, um dos principais desafios é evitar o abandono escolar. Para conseguir isso, é importante conhecer os estudantes e seu comportamento; entretanto, o problema se torna ainda mais complexo quando se deseja dar um acompanhamento personalizado a mais de 6.000 estudantes on-line com recursos financeiros e de tempo limitados. Hoje é essencial ajudar os estudantes que estão mais propensos a desistir através de várias estratégias que podem começar com atividades simples como agendar uma chamada telefônica ou implementar um sistema de aconselhamento mais personalizado.

Anahuac tem muitas informações relacionadas ao desempenho e à atividade dos estudantes, o desafio é identificar as variáveis que têm maior impacto sobre o abandono escolar e construir um bom modelo para tomar medidas rápidas e eficientes.

## 3. Objetivo

Anahuac tem uma enorme quantidade de informações sobre o comportamento dos estudantes nos diferentes programas on-line. O participante deve desenvolver um algoritmo ou um modelo de Machine Learning que seja capaz de prever quais alunos passarão com sucesso no programa de pós-graduação em que estão matriculados e quais irão desistir.

A idéia essencial do Desafio 6 é criar um modelo baseado na aprendizagem da máquina capaz de identificar a probabilidade de sucesso ou desistência do aluno, permitindo que a Universidade tome medidas oportunas.

## 4. Desenvolvendo a solução

A idéia essencial do Desafio 6 é criar um modelo baseado na aprendizagem de máquinas capaz de prever o sucesso ou a desistência do aluno. O participante trabalhará com um conjunto de dados sintéticos fornecidos e criará um modelo que fará a previsão e produzirá um arquivo csv com os resultados.


<div align="center">
  <h3>Bases de dados:</h3>
  <table class="tg">
  <thead>
    <tr>
      <th class="tg-c3ow">ArchivoEnrollments</th>
      <th class="tg-c3ow">Descrição</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="tg-c3ow">OrdenMaterias.csv</td>
      <td class="tg-c3ow">29  Colunas:  reducido,  e  28  colunas  que  correspondem  aos diferentes instantes em que se podem iniciar as materias (com a ordem em que cursariam)</td>
    </tr>
    <tr>
      <td class="tg-c3ow">TablaConexiones.csv</td>
      <td class="tg-c3ow">5 Colunas: studentId, ciclo, Dias_Conectado, Minutos_Promedio, Minutos_Total</td>
    </tr>
    <tr>
      <td class="tg-c3ow">TablaTareas.csv</td>
      <td class="tg-c3ow"> 7 Colunas: studentId, ciclo, Calificacion_Promedio, Tareas_Puntuales, Tareas_No_Entregadas, Tareas_Retrasadas, Total_Tareas </td>
    </tr>
    <tr>
      <td class="tg-c3ow">ForTraining.csv</td>
      <td class="tg-c3ow"> O arquivo contém a informação dos alunos. 3  variáveis  para  realizar  a  união  com  as  outras variáveis  que serão usadas para predizer: studentId, reducido y ciclo. 1 variable objetivo: Graduado. </td>
    </tr>
    <tr>
      <td class="tg-c3ow">ToBePredicted.csv </td>
      <td class="tg-c3ow"> O arquivo contém a informação dos estudantes para avaliar. 3 variaveis para realizar a predicão: studentId, reducido y ciclo. </td>
    </tr>    
  </tbody>
  </table>
</div>

- reducido: É o nome do curso ou carreira cursada.
- ciclo: Periodo em que se cursou a materia ou curso.
- studentId: Id unico do estudante.

## Licença

Copyright 2020 Maratona Behind the Code

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
