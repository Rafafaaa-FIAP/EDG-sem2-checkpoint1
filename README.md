<h1 align="center">Ano 1 - Semestre 2 - Checkpoint 1 - 1ESPR</h1>

<hr/>

<p align="center">
  <a href="#pushpin-Introdução">Introdução</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#bulb-Desafio">Desafio</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#hammer_and_wrench-Tecnologias-e-Ferramentas">Tecnologias e Ferramentas</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#floppy_disk-Solução">Solução</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#gear-Como-Utilizar">Como Utilizar</a>
</p>

<hr/>

## :pushpin: Introdução
Neste Checkpoint teve como objetivo avaliar a compreensão acerca da interação com o [Node-RED](https://nodered.org/).

## :bulb: Desafio
Construção de uma solução de IoT que abrange todas os conceitos de comunicação entre sensores e o [Node-RED](https://nodered.org/).
A solução deve conter a leitura de três sensores a cada 3000ms, disponibilizando as leituras na porta serial, no formato JSON {"":, "":}, os nomes dos sensores, e os valores lidos, respectivamente no DEBUG.
Além disso, deve haver Dashboards no [Node-RED](https://nodered.org/), cuja interface gráfica demonstre o funcionamento de todas os sensores.

## :hammer_and_wrench: Tecnologias e Ferramentas
Este projeto utilizou as seguintes tecnologias e ferramentas:
* [Node-RED](https://nodered.org/)
* [C++](https://pt.wikipedia.org/wiki/C%2B%2B)

## :floppy_disk: Solução
### Circuito
<table>
  <tr>
    <td>
      <img src="https://github.com/studies2023-FIAP-ES-553521-ano1-05-EDG/sem2-checkpoint1/blob/main/images/circuit-1.jpg" alt="circuit 1" width="300" />
    </td>
    <td>
      <img src="https://github.com/studies2023-FIAP-ES-553521-ano1-05-EDG/sem2-checkpoint1/blob/main/images/circuit-2.jpg" alt="circuit 2" width="300" />
    </td>
    <td>
      <img src="https://github.com/studies2023-FIAP-ES-553521-ano1-05-EDG/sem2-checkpoint1/blob/main/images/circuit-3.jpg" alt="circuit 3" width="300" />
    </td>
    <td>
      <img src="https://github.com/studies2023-FIAP-ES-553521-ano1-05-EDG/sem2-checkpoint1/blob/main/images/circuit-4.jpg" alt="circuit 4" width="300" />
    </td>
    <td>
      <img src="https://github.com/studies2023-FIAP-ES-553521-ano1-05-EDG/sem2-checkpoint1/blob/main/images/circuit-5.jpg" alt="circuit 5" width="300" />
    </td>
  </tr>
</table>

### Fluxo

### Dashboard

## :gear: Como Utilizar
1. Instalar o [Node-RED](https://nodered.org/);
2. Baixar o código da solução;
3. Montar o circuito;
4. Conectar o Arduino no computador e fazer upload do código para o Arduino;
5. Iniciar o [Node-RED](https://nodered.org/) no computador;
6. Importar o fluxo no [Node-RED](https://nodered.org/) no computador e dar o deploy.
