# GOMS
<div class="line"></div>
<br>
<p text-align="justify">&emsp;&emsp;Goals, Operators, Methods and Selection Rules (GOMS) é uma família de modelos para análise de tarefas, proposto em 1983 por Card et al.
<br>
&emsp;&emsp;Tem como objetivo predizer o impacto de decisões de projeto no desempenho competente do usuário, descrevem uma tarefa e o conhecimento do usuário sobre como executá-la em termos de: Objetivos, Operadores, Métodos e Regras de Seleção.
<br>
&emsp;&emsp;Será utilizado o modelo CMN GOMS.</p>

## Participantes
- Eduardo Lima
- Samuel Pereira

## Versões

<table class="versions">
	<tr>
		<th class="version_header">Versão</th>
		<th>Detalhes</th>
		<th>Data</th>
	</tr>
  <tr>
		<td>1.0</td>
		<td>Adição de registro</td>
		<td>12/11/2019</td>
	</tr>
	<tr>
		<td>1.1</td>
		<td>Adição de definir foto de perfil</td>
		<td>12/11/2019</td>
	</tr>
	<tr>
		<td>1.2</td>
		<td>Adição de criar projeto</td>
		<td>12/11/2019</td>
	</tr>
	<tr>
		<td>1.3</td>
		<td>Adição de Encontrar projeto específico</td>
		<td>12/11/2019</td>
	</tr>
	<tr>
		<td>1.4</td>
		<td>Adição de Exclusão de conta e padronização</td>
		<td>13/11/2019</td>
	</tr>
</table>

## Registro

<p>
<b>GOAL 0</b>: Criar uma conta
<br>&emsp;<b>GOAL 1</b>: Acessar a página de cadastro
<br>&emsp;&emsp;<b>OP 1.1</b>: Deslocar o cursor do mouse para o link "Clique aqui e cadastre-se."
<br>&emsp;&emsp;<b>OP 1.2</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;&emsp;
<br>&emsp;<b>GOAL 2</b>: Preencher as informações cadastrais
<br>&emsp;&emsp;<b>OP 2.1</b>: Preencher o campo Nome
<br>&emsp;&emsp;<b>OP 2.2</b>: Preencher o campo E-mail
<br>&emsp;&emsp;<b>OP 2.3</b>: Preencher o campo Senha
<br>&emsp;&emsp;<b>OP 2.4</b>: Clicar no botão "Criar conta"
</p>



## Definir foto de perfil

<p>
<b>GOAL 0</b>: Definir uma foto de perfil
<br>&emsp;<b>GOAL 1</b>: Entrar no perfil de usuário
<br>&emsp;&emsp;<b>OP 1.1</b>: Deslocar o cursor do mouse para o menu de usuário no canto superior direto
<br>&emsp;&emsp;<b>OP 1.2</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;&emsp;<b>OP 1.3</b>: Deslocar o cursor do mouse para opção "Meu Perfil"
<br>&emsp;&emsp;<b>OP 1.4</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;&emsp;
<br>&emsp;<b>GOAL 2</b>: Entrar na página de edição de perfil
<br>&emsp;&emsp;<b>OP 2.1</b>: Deslocar o cursor do mouse para o botão Editar Perfil
<br>&emsp;&emsp;<b>OP 2.2</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;&emsp;
<br>&emsp;<b>GOAL 3</b>: Enviar imagem
<br>&emsp;&emsp;<b>GOAL 3.1</b>: Escolher arquivo
<br>&emsp;&emsp;&emsp;<b>METHOD 3.A</b>: Através da caixa de procura de arquivo
<br>&emsp;&emsp;&emsp;(SEL. RULE: usuário não possui a localidade do arquivo aberta em uma outra janela ou preferência do usuário)
<br>&emsp;&emsp;&emsp;&emsp;<b>OP 3.A.1</b>: Deslocar o cursor do mouse para o botão "Escolher arquivo"
<br>&emsp;&emsp;&emsp;&emsp;<b>OP 3.A.2</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;&emsp;&emsp;&emsp;<b>OP 3.A.3</b>: Localizar o arquivo
<br>&emsp;&emsp;&emsp;&emsp;<b>OP 3.A.4</b>: Selecionar o arquivo
<br>&emsp;&emsp;&emsp;&emsp;
<br>&emsp;&emsp;&emsp;<b>METHOD 3.B</b>: Arrastando arquivo
<br>&emsp;&emsp;&emsp;(SEL. RULE: usuário possui a localidade do arquivo aberta em uma outra janela ou preferência do usuário)
<br>&emsp;&emsp;&emsp;&emsp;<b>OP 3.B.1</b>: Deslocar o cursor do mouse para o arquivo em outra janela
<br>&emsp;&emsp;&emsp;&emsp;<b>OP 3.B.2</b>: Clicar e segurar o botão esquerdo do mouse
<br>&emsp;&emsp;&emsp;&emsp;<b>OP 3.B.3</b>: Deslocar o mouse até a caixa de diálogo de "Escolher arquivo"
<br>&emsp;&emsp;&emsp;&emsp;<b>OP 3.B.4</b>: Soltar o botão esquerdo do mouse
<br>&emsp;&emsp;&emsp;
<br>&emsp;&emsp;<b>GOAL 3.2</b>: Submeter arquivo
<br>&emsp;&emsp;&emsp;<b>GOAL 3.2.1</b>: Preencher campos obrigatórios
<br>&emsp;&emsp;&emsp;&emsp;<b>OP 3.2.1.1</b>: Deslocar o cursor do mouse para o campo telefone
<br>&emsp;&emsp;&emsp;&emsp;<b>OP 3.2.1.2</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;&emsp;&emsp;&emsp;<b>OP 3.2.1.2</b>: Digitar informação
<br>&emsp;&emsp;&emsp;<b>OP 3.2.2</b>: Deslocar o cursor do mouse para o botão "Salvar"
<br>&emsp;&emsp;&emsp;<b>OP 3.2.3</b>: Clicar com o botão esquerdo do mouse
</p>

## Criar projeto

<p>
<b>GOAL 0</b>: Criar um projeto
<br>&emsp;<b>GOAL 1</b>: Acessar a página de criação de projeto
<br>&emsp;&emsp;<b>OP 1.1</b>: Deslocar o cursor do mouse para o botão "Criar projeto."
<br>&emsp;&emsp;<b>OP 1.2</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;&emsp;
<br>&emsp;<b>GOAL 2</b>: Preencher as informações do novo projeto
<br>&emsp;&emsp;<b>OP 2.1</b>: Selecionar o campo "Nome do projeto"
<br>&emsp;&emsp;<b>OP 2.2</b>: Preencher o nome do projeto
<br>&emsp;&emsp;<b>OP 2.3</b>: Selecionar o campo "Descrição"
<br>&emsp;&emsp;<b>OP 2.4</b>: Preencher a descrição do projeto
<br>&emsp;&emsp;<b>OP 2.5</b>: Selecionar o campo "Próximos passos"
<br>&emsp;&emsp;<b>OP 2.6</b>: Preencher os próximos passos do projeto
<br>&emsp;&emsp;<b>OP 2.7</b>: Selecionar o campo "Palavras-chave"
<br>&emsp;&emsp;<b>OP 2.8</b>: Preencher as palavras-chave do projeto
<br>&emsp;&emsp;<b>OP 2.9</b>: Selecionar o campo "Palavras-chave"
<br>&emsp;&emsp;<b>OP 2.10</b>: Escolher o tipo de ajuda dentre as opções disponíveis
<br>&emsp;&emsp;<b>OP 2.11</b>: Clicar no botão "Criar"
</p>

## Encontrar projeto específico

<p>
<b>GOAL 0</b>: Encontrar projeto específico
<br>&emsp;<b>GOAL 1</b>: Pesquisar por projeto
<br>&emsp;&emsp;<b>OP 1.1</b>: Deslocar o cursor do mouse para a caixa de pesquisa
<br>&emsp;&emsp;<b>OP 1.2</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;&emsp;<b>OP 1.3</b>: Digitar tags relacionadas a um projeto
<br>&emsp;&emsp;<b>GOAL 1.4</b>: Confirmar pesquisa
<br>&emsp;&emsp;&emsp;<b>METHOD 1.4.A</b>: Através de botão
<br>&emsp;&emsp;&emsp;(SEL. RULE</b>: usuário está a utilizar o mouse ou preferência do usuário)
<br>&emsp;&emsp;&emsp;&emsp;<b>OP 1.4.A.1</b>: Deslocar o cursor do mouse para o botão "Buscar
<br>&emsp;&emsp;&emsp;&emsp;<b>OP 1.4.A.2</b>: Clicar com o botão esquerdo
<br>&emsp;&emsp;&emsp;&emsp;
<br>&emsp;&emsp;&emsp;<b>METHOD 1.4.B</b>: Através do teclado
<br>&emsp;&emsp;&emsp;(SEL. RULE</b>: usuário está a utilizar o teclado ou preferência do usuário)
<br>&emsp;&emsp;&emsp;&emsp;<b>OP 1.4.B.1</b>: Apertar a tecla Enter
<br>&emsp;&emsp;
<br>&emsp;<b>GOAL 2</b>: Escolher algum resultado
<br>&emsp;&emsp;<b>METHOD 2.A</b>: Utilizando o título
<br>&emsp;&emsp;(SEL. RULE</b>: preferência do usuário)
<br>&emsp;&emsp;&emsp;<b>OP 2.A.1</b>: Deslocar o cursor do mouse para o título de um cartão
<br>&emsp;&emsp;&emsp;<b>OP 2.A.2</b>: Clicar com o botão esquerdo
<br>&emsp;&emsp;&emsp;
<br>&emsp;&emsp;<b>METHOD 2.B</b>: Utilizando a descrição
<br>&emsp;&emsp;(SEL. RULE</b>: preferência do usuário)
<br>&emsp;&emsp;&emsp;<b>OP 2.B.1</b>: Deslocar o cursor do mouse para a descrição de um cartão
<br>&emsp;&emsp;&emsp;<b>OP 2.B.2</b>: Clicar com o botão esquerdo
<br>&emsp;&emsp;&emsp;
<br>&emsp;&emsp;<b>METHOD 2.C</b>: Utilizando "Saiba Mais"
<br>&emsp;&emsp;(SEL. RULE</b>: preferência do usuário)
<br>&emsp;&emsp;&emsp;<b>OP 2.C.1</b>: Deslocar o cursor do mouse para o hipertexto "SAIBA MAIS"
<br>&emsp;&emsp;&emsp;<b>OP 2.C.2</b>: Clicar com o botão esquerdo
</p>

## Exclusão de conta
<p>
<b>GOAL 0</b>: Excluir conta
<br>&emsp;<b>GOAL 1</b>: Entrar na página de edição de conta
<br>&emsp;&emsp;<b>OP 1.1</b>: Deslocar o cursor do mouse para o menu de usuário no canto superior direto
<br>&emsp;&emsp;<b>OP 1.2</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;&emsp;<b>OP 1.3</b>: Deslocar o cursor do mouse para opção "Minha conta"
<br>&emsp;&emsp;<b>OP 1.4</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;
<br>&emsp;<b>GOAL 2</b>: Realizar exclusão de conta
<br>&emsp;&emsp;<b>OP 2.1</b>: Deslocar o cursor do mouse para o hipertexto "Excluir conta"
<br>&emsp;&emsp;<b>OP 2.2</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;&emsp;<b>OP 2.3</b>: Deslocar o cursor do mouse para a opção "SIM"
<br>&emsp;&emsp;<b>OP 2.4</b>: Clicar com o botão esquerdo do mouse
</p>

# Referências
<div class="line"></div>
<p text-align="justify">&emsp;&emsp;Prof. Alberto Raposo, Análise e Modelos de tarefas - PUC Rio. Disponível em: <a href=https://webserver2.tecgraf.puc-rio.br/~abraposo/inf1403/INF1403_13_tarefas.pdf>https://webserver2.tecgraf.puc-rio.br/~abraposo/inf1403/INF1403_13_tarefas.pdf</a>. Acesso em: 12 nov. 2019.</p>