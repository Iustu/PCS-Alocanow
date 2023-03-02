
# AlocaNOW 💻:white_check_mark:
*Uma plataforma para a  gestão de alocação de profissionais a projetos.*

## [BSI - UNIRIO - Projeto e Construção de Sistemas - 2022.2](https://github.com/Projeto-e-Construcao-de-Sistemas-2022-2)
## Grupo 2
* _[Frederico Mussi](https://github.com/fredmussi)_
* _[João Gabriel Oliveira](https://github.com/Oliveira1390)_
* _[João Pedro Ribeiro](https://github.com/Iustu)_
* _[Márcio Lopes](https://github.com/marciohesteveslopes)_
* _[Priscilla Souza](https://github.com/priscillasz)_

## Versão 3.0

> A versão atual do sistema contém implementações de 21 casos de uso, tratando as diversas especificações requisitadas, além de conter integrações com ViaCEP, Gmail e Abstract API.
> * Acesse o vídeo de demonstração da versão atual do sistema [aqui](https://www.youtube.com/watch?v=koPVJVbDhAw).
> * Acesse a documentação atualizada do sistema [aqui](https://github.com/Projeto-e-Construcao-de-Sistemas-2022-2/Grupo-2-AlocaNow/blob/priscilla-entrega4/Documentação/Apresentações/%5BENTREGA%20FINAL%204%5D%20AlocaNOW%20-%20Grupo%202%20-%20PCS%202022.2.pdf).

## Diretórios
* **AlocaNOW-ProjetoPCS**
	* **src**
		* **main**
			* **java/net/codejava:** classes utilizadas para estruturar o sistema
			* **resources**
				* ***static:*** imagens utilizadas, scripts e stylesheets
				* ***templates:*** código html das páginas
				* ***application.properties:*** configurações de acesso ao banco de dados e integrações
* **Documentação**
	* ***Apresentações***
	* ***Diagramas de Caso de Uso***
	* ***Diagramas de Classe***
* ***Outros***

## Protótipo
Acesse o protótipo [aqui.](https://balsamiq.cloud/setrdgt/pbac6tx/r0A28)

## Arquitetura
-   Sistema hospedado em servidor local
-   Linguagem de implementação: Java
-   **Back-end:** Spring Boot
	- Spring Security: Segurança, autenticação e autorização de privilégios
	-   ***JPA (Java Persistance API):*** fornece um mecanismo para gerenciar a persistência e mapeamento relacional de objeto e funções para as especificações de EJB.
	-   ***Hibernate:*** fornece uma estrutura para mapear um modelo de domínio orientado a objetos para um banco de dados relacional.
	- ***Integração com banco de dados:*** MySQL
-   **Front-end:**
	-   ***Thymeleaf:*** Template engine que facilita a criação de páginas: traduz o código Java e incorpora à página HTML;
	-   HTML5/CSS3/JavaScript;
	-   ***Bootstrap:*** framework front-end que fornece estruturas de CSS para a criação de sites e aplicações responsivas de forma rápida e simples;
	-   ***JQuery:*** biblioteca livre que contém funções da linguagem de programação JavaScript que interage com páginas em HTML.
