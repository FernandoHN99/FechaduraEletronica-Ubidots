<h1>Gerenciamento da Fechadura Eletrônica via Node-RED</h1>

Este é um projeto focado no gerenciamento de uma fechadura eletrônica feita com o Raspberry Pi Pico. 
O guia para construção da fechadura eletrônica além de suas funcionalidades e códigos-fonte estão localizados em: [🔗 Fechadura Eletrônica com Raspberry Pi Pico](https://github.com/FernandoHN99/FechaduraEletronica-RaspberryPico). Portanto para uma correta implementação nesta fase do gerenciamento da fechadura é necessário ter seguido todos os passos prévios mencionados.

https://github.com/FernandoHN99/FechaduraEletronica-Node-Red/assets/86134291/a0a0fde2-0bac-45c4-be40-ba9766ca2e57

<h2>⚙️ Funcionalidades do Sistema</h2>

<h4>🕺🏼 Monitoramento de check-in e check-out dos clientes e seus respectivos acessos.</h4>
<h4>✅ Liberação de acesso.</h4>
<h4>🔄 Reset da fechadura.</h4>
<h4>💳 Gerenciamento de cartões autorizado.</h4>
<h4>🚪 Exibição de aviso de porta aberta.</h4>
<h4>🚨 Exibição de aviso de invasão.</h4>

<h2>🎬 Começando...</h2>

Essas instruções permitirão que você consiga realizar uma cópia do projeto em operação em seu Node-RED para fins de desenvolvimento e teste.
<h3>🧑🏻‍💻 Softwares Utilizados</h3>

 * [🔗 Node-RED](https://nodered.org/)

<h3>🕹️ Hardwares Utilizados</h3>

* [🔗 Raspberry Pi](
https://www.raspberrypi.com/products/raspberry-pi-3-model-b-plus/)

<h2>🚀 Instalação</h2>

<ul>
  <li>
    <h3 id="secao-diagrama-blocos">Diagrama De Blocos</h3>
    <img width="1116" alt="DiagramaDeBlocos" src="https://github.com/FernandoHN99/FechaduraEletronica-Node-Red/assets/86134291/e87a5274-b0b3-4bff-9908-8ec7d0853c8c">
  </li>
</ul>

> **Observação:** Para um maior entendimento dos periféricos utilizados no Raspberry Pi Pico, acesse o [🔗 Projeto da Fechadura Eletrônica com Raspberry Pi Pico](https://github.com/FernandoHN99/FechaduraEletronica-RaspberryPico).

<h2>📦 Implementação</h2>

1. Implementação da fechadura Eletrônica: [🔗 Fechadura Eletrônica com Raspberry Pi Pico](https://github.com/FernandoHN99/FechaduraEletronica-RaspberryPico)

2.  Fazer a substituição completa do código no Raspberry Pi Pico com o apresentado neste repositório, sem necessidade da cópia do arquivo flows.json (Necessário implementação correta do passo 1)

3.  Conectar-se ao Node-RED instalado em sua máquina e instalar nele os seguintes módulos:
    - node-red
    - node-red-dashboard
    - node-red-node-ui-table
    - node-red-node-serialport

4. Importar o arquivo flows.json 

<h2>✒️ Autores</h2>

* Fernando Henriques Neto &nbsp;18.00931-0 
* Guilherme Sanches Rossi &nbsp;&nbsp;19.02404-5 
* Luiz Fernando Rodrigues &nbsp;&nbsp;&nbsp;19.01358-2 
* Matheus Coelho Rocha  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;20.00391-9 
* Pedro Henrique S.Hein &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;20.00134-7 


<h2>🎁 Expressões de gratidão</h2>

Agradecimentos aos professores [🔗 Sergio Ribeiro Augusto](https://br.linkedin.com/in/sergio-ribeiro-augusto-258a9ba0) e [🔗 Rodrigo de Marca Franca](https://br.linkedin.com/in/rodrigo-frança-847872b1) por todo suporte para a conclusão do Projeto.

---
