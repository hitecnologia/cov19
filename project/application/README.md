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


## VPE - Aplica��o

A aplica��o desenvolvida ser� liberada em um arquivo juntamente com o firmware do m�dulo **<a href="https://github.com/hitecnologia/cov19/tree/master/project/electronic">COD19-R0</a>**.

As informa��es e links a seguir s�o necess�rias caso seja necess�rio ou de interesse
ver o programa de aplica��o ou modifica-lo para adequa��es ou melhorias.

As aplica��es presentes a seguir foram desenvolvidas em **linguagem ST** utilizando o ambiente de 
desenvolvimento **HIstudio** da HI Tecnologia. 

<p align="center">
  <img src="../../project/application/histudio.png" height="400">
</p>

Para este projeto, foi customizada uma vers�o do **HIstudio** (vers�o 19.0.0) 
que suporta o m�dulo de hardware desenvolvido denominado de **COV19**.
Esta vers�o pode ser obtida gratuitamente no link abaixo:

 - **<a href="https://www.hitecnologia.com.br/media/uploads/box/installhistudio19.0.00.exe">HIstudio Ver 19.0.0</a>** 

Para se comunicar com o m�dulo � necess�rio um canal serial (ou conversor usb/serial) 
visto que foi disponibilizado apenas os pinos TX/RX para esta fun��o. Deve-se utilizar um driver TTL/RS232-C 
para esta comunica��o. Este m�dulo � facilmente encontrado no mercado.

Por exemplo:
   https://produto.mercadolivre.com.br/MLB-1306467688-modulo-conversor-rs232-ttl-max232-db9-0408-_JM

ou outro similar.

Para permitir a comunica��o do **HIstudio** com o m�dulo ser� necess�rio a utiliza��o do servidor de comunica��o **MPL Server**. 
Este servidor (OPC Server) foi desenvolvido pela HI Tecnologia e pode ser baixado gratuitamente no <a href="https://www.hitecnologia.com.br">nosso site</a>,
ou diretamente no link abaixo. 
 
 - **<a href="https://www.hitecnologia.com.br/downloads/installmplserver1.0.15.exe">Servidor OPC MPL Server</a>**
 
**Obs:** Ser� necess�rio um cadastro pr�vio para baixar este aplicativo. 
            
Com estes 2 ambientes instalados � poss�vel abrir a aplica��o disponibilizada a seguir.


### Items da aplica��o

 - **<a href="https://github.com/hitecnologia/cov19/tree/master/project/application/VPE19_1000.dpk">Aplica��o VPE19_1000</a>**. Compat�vel com o **<a href="https://github.com/hitecnologia/cov19/tree/master/project/firmware">Firmware VPE19-1-G5PLC_CV19_ST-0097</a>** 


**OBS:** Estamos trabalhando em elaborar o manual simples da interface e t�o logo esteja conclu�do estaremos disponibilizando o mesmo. 



**Links:**
 - [HI Tecnologia Site](https://www.hitecnologia.com.br/)

---


