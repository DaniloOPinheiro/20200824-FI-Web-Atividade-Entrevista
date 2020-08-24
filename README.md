# FUNÇÃO INFORMÁTICA
## PROCESSO SELETIVO TESTE PRÁTICO - JÚNIOR

1. Qual o objetivo do teste:
* Avaliar o conhecimento técnico e a lógica de desenvolvimento à vaga de desenvolvedor júnior.

2. O que é preciso para o teste:
* Solution

		OBS : Arquivo da solution particular

* Visual Studio 2017

		Disponível em: https://docs.microsoft.com/pt-br/visualstudio/install/install-visual-studio Obs: A Microsoft disponibiliza versão trial do produto, que pode ser utilizado a realização do teste

* Framework 4.6.2

		Disponível em: https://www.microsoft.com/pt-br/download/details.aspx?id=53344

	* Fique atento: 

	Na instalação do Visual Studio inclua o opcional “SQL Server Express 2016 LocalDB”.

3. Por onde começar:

	Após providenciar os requisitos necessários conforme listados no item 2, descompacte o ZIP “FI.WebAtividadeEntrevista-Junior.zip”, onde haverá a Solution “FI.WebAtividadeEntrevista.sln” que se refere a um sistema de manutenção dos dados básicos de clientes.

	Ao executar o sistema, na aba “Clientes” está a página principal de manutenção de clientes, onde é permitida a inclusão de um novo cliente através do botão “Novo Cliente”.

4. O que deve ser feito:

	Na tela de cadastramento/alteração de clientes, incluir um novo campo denominado CPF, que permitirá o cadastramento do CPF do cliente.

* Pontos relevantes:

	* O novo campo deverá seguir o padrão visual dos demais campos da tela
	* O cadastramento do CPF será obrigatório
	* Deverá possuir a formatação padrão de CPF (999.999.999-99)
	* Deverá consistir se o dado informado é um CPF válido (conforme o cálculo padrão de verificação do dígito verificador de CPF)
	* Não permitir o cadastramento de um CPF já existente no banco de dados, ou seja, não é permitida a existência de um CPF duplicado

	A aplicação possui um banco de dados interno, que se encontra no caminho “~\FI.WebAtividadeEntrevista\App_Data”, onde será necessária a criação do novo campo no banco de dados, para gravação do valor do CPF.

* Pontos relevantes:

	* Tabela que deverá armazenar o novo campo de CPF: “CLIENTES”
	* O novo campo deverá ser nomeado como “CPF”