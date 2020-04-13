<p align="center">
  <span>Portugues</span> |
  <a href="https://github.com/hitecnologia/cov19/tree/master/docs/lang/en-us#cov19">English</a>
</p>

<p align="center">
  <img src="../../docs/assets/banner.jpeg">
</p>

# VPE - Um ventilador pulmonar emergencial, para ajudar as v�timas do v�rus corona

Ventilador pulmonar projetado pela equipe de engenharia e parceiros da HI Tecnologia, 
com o objetivo de ajudar a salvar vidas durante a pandemia do v�rus corona.

Deve ser observado que, apesar de atuarmos nos setor de automa��o industrial 
por v�rios anos e termos obtido orienta��o e ajuda de v�rios profissionais de 
sa�de, n�o temos expertise em equipamentos m�dicos e portanto, 
podem ser necess�rias funcionalidades ou ajustes no projeto corrente.

Toda documenta��o e o reposit�rio do projeto podem ser usados sem limita��es.


## VPE - Projeto eletr�nico

<p align="center">
  <img src="../../project/electronic/front_f1.png" height="350">
  <img src="../../project/electronic/back_f1.png" height="350">
</p>

O hardware desenvolvido possui os seguintes recursos:

 - Alimenta��o principal de 12 volts DC (10.5 .. 14VDC) com previs�o para conex�o
   de bateria para manter o equipamento funcionando em caso de falta de energia.
 - Processador ARM-CORTEX-M0 com 256Kb de Flash e 32Kb de RAM.
 - 2 Entradas digitais para monitorar 2 chaves (limit switchs) para sincroniza��o e seguran�a do movimento.
 - 4 entradas digitais associadas a 4 chaves para opera�ao do equipamento
 - 3 Sa�das digitais para controle do driver de step-motor (pulso, dire��o e habilita��o)
 - 1 Sa�da digital para controle de uma sinalizador sonoro para alarme
 - 5 Sa�das digitais para acionamento de 5 led's de sinalizacao da interface
 - 1 Entrada anal�gica conectada a um sensor de press�o (faixa de 0..10Kpa)
 - 1 Entrada anal�gica monitorar a tens�o de alimenta��o do equipamento
 - 1 Entrada anal�gica reserva (0..5Vdc)
 - 1 interface serial (TX/RX em barra de pinos)
 - 1 conector para carga do firmware/aplica��o via programador JTAG


## Detalhes do Projeto:

 - **<a href="https://github.com/hitecnologia/cov19/tree/master/project/electronic/BOM_PartType-PDE921000100.htm">Lista de materiais</a>**
 - **<a href="https://github.com/hitecnologia/cov19/tree/master/project/electronic/COV19_STL.zip">Arquivos Geber</a>**
 - **<a href="https://github.com/hitecnologia/cov19/tree/master/project/electronic/PDE921000100.pdf">Documenta��o eletr�nica</a>**


**Links:**
 - [HI Tecnologia Site](https://www.hitecnologia.com.br/)


---

