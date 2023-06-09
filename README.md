<h1 align="center">Eureka Server - Empresa de Software</h1>
<p align="center"><i>Repositório que armazena o discovery server de toda uma estrutura de microserviços para uma empresa de software ficticia.</i></p>

##  Sobre esse projeto

Este é o primeiro projeto que deve ser rodado ao inciarmos nossa arquitetura de microserviços, como discovery server, este repositório contém toda a estrutura para que nossos microserviços consigam se conectar e comunicar-se entre si.

### Tecnologias
<p display="inline-block">
 <p>Java</p>
 <p>Spring Boot</p>
 <p>Spring Cloud</p>
 <p>Eureka Server</p>
 <p>Docker</p>
 <p>RabbitMQ</p>
</p>
                                                                                                   
<h1>Como usar</h1>

<h2>Prerequisitos</h2>
<p>Deve ser ter instalado em sua máquina o Docker e dentro dele ter uma imagem do RabbitMQ que pode ser adquirida neste <a href="https://www.rabbitmq.com/download.html">link</a>. A senha de uso é username: guest e password:guest. O rabbitMQ precisa estar rodando quando as instancias dos serviços levantarem para que as filas possam ser criadas com sucesso!</p>

<p>Após isso, clone ou baixe o repositório e start ele através de sua IDE de preferência rodando o método main da classe principal na pasta raíz da aplicação, feito isso, basta deixar a aplicação rodando para que os microserviços que virão a serem subidos possam se conectar :)</p>

<h1>Outros repositórios em ordem de inicialização após o Eureka Server estar rodando</h1></br>
1 -> <a href="https://github.com/ValterGabriell/bank-system-msaccount">Microserviço responsável por criar contas bancárias dos usuários</a></br>
2 -> <a href="https://github.com/ValterGabriell/bank-system-mscards">Microserviço responsável por criar cartões para os usuários</a></br>
3 -> <a href="https://github.com/ValterGabriell/bank-system-mscreditappraiser">Microserviço responsável verificar o crédito que o usuário terá e solicitar a emissão de cartão</a></br>
4 -> <a href="https://github.com/ValterGabriell/software-company-mslead">Microserviço responsável pela criação dos líderes das squads</a></br>
5 -> <a href="https://github.com/ValterGabriell/software-company-mscolaborators">Microserviço responsável pela criação dos colaboradores das squads</a></br>
6 -> <a href="https://github.com/ValterGabriell/software-company-msjobs">Microserviço responsável pela criação dos trabalhos dos colaboradores</a></br>
7 -> <a href="https://github.com/ValterGabriell/bank-system-gateway">Gateway para fazer o loadbalancer dos microserviços</a></br>
7 -> <a href="https://github.com/ValterGabriell/software-company-msshopping">Micro serviço responsável por gerenciar as compras dos clientes.</a></br>



<h1>Credits</h1>

---

<a href="https://www.linkedin.com/in/valter-gabriel">
  <img style="border-radius: 50%;" src="https://user-images.githubusercontent.com/63808405/171045850-84caf881-ee10-4782-9016-ea1682c4731d.jpeg" width="100px;" alt=""/>
  <br />
  <sub><b>Valter Gabriel</b></sub></a> <a href="https://www.linkedin.com/in/valter-gabriel" title="Linkedin">🚀</ a>
 
Made by Valter Gabriel 👋🏽 Get in touch!

[![Linkedin Badge](https://img.shields.io/badge/-Gabriel-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/valter-gabriel/ )](https://www.linkedin.com/in/valter-gabriel/)

