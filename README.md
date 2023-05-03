# Teste-Back
Teste Destinado aos Interessados para Vaga Back End .Net Core
# Serão Três Etapas
<ol type="1">
<li>Criar Projetos:</li>
<ol type="A">
<li>Site MVC.<br>O site desenvolvido em MVC, necessariamente precisa fazer a comunicação com a base de dados através do consumo das APIS, que devem ser construídas.</li>
<li>Projeto .netCore (swagger e arquitetura em camadas)</li>
</ol>
<li>Api Login (Autorization Bearer)<br>
2.1. Utilizar Mock.</li>
<li>Api Crud de Clientes (Criar / Listar (todos ou por id) / Alterar / Excluir).<br>3.1. Gerar scripts de tabelas – não usar entity framework.</li>
</ol>

# Login:
• Solicitar usuário e senha e gerar token jwt.
• Validar se usuário e senha existem ou estão corretos.

# Cadastro de Clientes
<strong>Os campos necessários são apresentados a seguir.</strong>

<p>Cliente:</p>
•	CPF – String <br>
•	Nome – String <br>
•	RG – String <br>
•	Data Expedição – Datetime <br>
•	Órgão Expedição – String <br>
•	UF – String <br>
•	Data de nascimento – Datetime <br>
•	Sexo – String <br>
•	Estado Civil – String <br><br>

<p>Endereço Cliente:</p>
•	CEP – String (buscar em sites online) <br>
•	Logradouro – String <br>
•	Número – String <br>
•	Complemento – String <br>
•	Bairro – String <br>
•	Cidade – String <br>
•	UF – String <br>

# Desejável

(Será considerado um diferencial)<br>
Criar cobertura de testes unitários para as principais funcionalidades, não precisa ser nada muito complexo ou extenso, basta ser objetivo e assertivo.<br>
Configurar o Swagger para termos acesso a documentação da API.<br>

# Método de Avaliação

Seu código estará sob análise do time de Front. O que vamos procurar:<br>
•	Boas práticas e padrões<br>
•	Código e estrutura de pastas<br>
•	Componentização e fluxo de dados<br>

# Como Entregar
Subir seu código no git e preencher o form:
https://forms.gle/52HeyfxnjVqwDL1g8
