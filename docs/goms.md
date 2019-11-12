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
</table>

## Registro

<p>
<b>GOAL 0</b>: Criar uma conta
<br>&emsp;<b>GOAL 1</b>: Acessar a página de cadastro
<br>&emsp;&emsp;<b>OP.1.1</b>: Deslocar o cursor do mouse para o link "Clique aqui e cadastre-se."
<br>&emsp;&emsp;<b>OP.1.2</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;&emsp;
<br>&emsp;<b>GOAL 2</b>: Preencher as informações cadastrais
<br>&emsp;&emsp;<b>OP.2.1</b>: Preencher o campo Nome
<br>&emsp;&emsp;<b>OP.2.2</b>: Preencher o campo E-mail
<br>&emsp;&emsp;<b>OP.2.3</b>: Preencher o campo Senha
<br>&emsp;&emsp;<b>OP.2.4</b>: Clicar no botão "Criar conta"
</p>



## Definir foto de perfil

<p>
<b>GOAL 0</b>: Definir uma foto de perfil
<br>&emsp;<b>GOAL 1</b>: Entrar no perfil de usuário
<br>&emsp;&emsp;<b>OP.1.1</b>: Deslocar o cursor do mouse para o menu de usuário no canto superior direto
<br>&emsp;&emsp;<b>OP.1.2</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;&emsp;<b>OP.1.3</b>: Deslocar o cursor do mouse para opção "Meu Perfil"
<br>&emsp;&emsp;<b>OP.1.4</b>: Clicar com o botão esquerdo do mouse
<br>&emsp;&emsp;
<br>&emsp;<b>GOAL 2</b>: Entrar na página de edição de perfil
<br>&emsp;&emsp;<b>OP.2.1</b>: Deslocar o cursor do mouse para o botão Editar Perfil
<br>&emsp;&emsp;<b>OP.2.2</b>: Clicar com o botão esquerdo do mouse
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

# Referências <div class="line"></div>
<p text-align="justify">&emsp;&emsp;Prof. Alberto Raposo, Análise e Modelos de tarefas - PUC Rio. Disponível em: <a href=https://webserver2.tecgraf.puc-rio.br/~abraposo/inf1403/INF1403_13_tarefas.pdf>https://webserver2.tecgraf.puc-rio.br/~abraposo/inf1403/INF1403_13_tarefas.pdf</a>. Acesso em: 12 nov. 2019.</p>