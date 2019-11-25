# Análise Hierárquica de Tarefas
<div class="line"></div>
<br>
<p text-align="justify">&emsp;&emsp;A Análise Hierárquica de Tarefas, abreviada como AHT, foi desenvolvida na década de 1960, tendo como intuito inicial de identificar as necessidades de treinamento.
<br>
&emsp;&emsp;A ideia básica desta análise é relacionar o que as pessoas fazem - sendo essas as tarefas - com o por que elas fazem e as suas consequências, em caso de erros.  O ponto de partida desta análise são os objetivos do usuário, onde são identificadas as principais tarefas e subtarefas associadas à conclusão desse objetivo.
<br>
&emsp;&emsp;Será utilizada a representação AHT encontrada em Barbosa e Silva, 2010.</p>

## Versões

<table class="versions">
	<tr>
		<th class="version_header">Versão</th>
		<th>Detalhes</th>
		<th>Data</th>
	</tr>
	<tr>
		<td>1.0</td>
		<td>Versão inicial: Criação de projeto, busca de projeto e registro</td>
		<td>05/11/2019</td>
	</tr>
	<tr>
		<td>1.1</td>
		<td>Adição de exclusão de conta e correção de versionamento</td>
		<td>05/11/2019</td>
	</tr>
	<tr>
		<td>1.2</td>
		<td>Adição de referências</td>
		<td>05/11/2019</td>
	</tr>
	<tr>
		<td>1.3</td>
		<td>Correção de erros nos diagramas</td>
		<td>05/11/2019</td>
	</tr>
	<tr>
		<td>1.4</td>
		<td>Tabela de Encontrar Projeto Específico</td>
		<td>05/11/2019</td>
	</tr>	
	<tr>
		<td>1.5</td>
		<td>Tabela de Remoção de Conta.</td>
		<td>05/11/2019</td>
	</tr>
	<tr>
		<td>1.6</td>
		<td>Adição da tabela de Criação de projeto</td>
		<td>05/11/2019</td>
	</tr>
	<tr>
		<td>1.7</td>
		<td>Adição da tabela de Registro</td>
		<td>05/11/2019</td>
	</tr>
</table>

## Participantes
- Eduardo Lima
- Luís Henrique
- Samuel Pereira


## Registro
<img src="../assets/aht/Registro.png">
<br>

<table class="tarefa">
	<tr>
		<th class="tarefa_header">Operações</th>
		<th>Problemas e recomendações</th>
	</tr>
	<tr>
		<td>0. Registrar no Meraki 1>2</td>
		<td>Input: Nome, E-mail e Senha.
		Feedback: Acesso à nova conta e página de Editar perfil.
		<br>
		Plano: Criar nova conta com os dados informados.
		<br>
		Problema: Falta de verificação das informações e confirmação da criação.</td>
	</tr>	
	<tr>
		<td>1. Entrar no site Meraki</td>
		<td>Plano: Acessar a página inicial do site.</td>
	</tr>	
	<tr>
		<td>2. Clicar no link para cadastro</td>
		<td>Plano: Acessar página de cadastro.</td>
	</tr>	
	<tr>
		<td>3. Inserir informações de cadastro 1/2</td>
		<td>Plano: Informar as informações de cadastro</td>
	</tr>	
	<tr>
		<td>3.1. Inserir nome</td>
		<td>Plano: Informar o nome da nova conta.</td>
	</tr>	
	<tr>
		<td>3.2. Inserir E-mail </td>
		<td>Plano: Informar o E-mail da nova conta.</td>
	</tr>	
	<tr>
		<td>3.3. Inserir senha</td>
		<td>Plano: Definir senha da nova conta.</td>
	</tr>	
	<tr>
		<td>4. Confirmar cadastro 1/2</td>
		<td>Plano: Efetuar a criação da nova conta.</td>
	</tr>	
	<tr>
		<td>4.1. Apertar em botão de criar conta</td>
		<td>Plano: Criar nova conta com as informações informadas</td>
	</tr>	
	<tr>
		<td>4.2. Apertar Enter</td>
		<td>Feedback: Acessar a página de editar perfil.
		<br>
		Plano: Finalizar cadastro.
		<br>
		</td>
	</tr>	
</table>


## Encontrar projeto específico
<img src="../assets/aht/AcharProjeto.png">
<br>

<table class="tarefa">
	<tr>
		<th class="tarefa_header">Operações</th>
		<th>Problemas e recomendações</th>
	</tr>
	<tr>
		<td>0. Encontrar projeto específico 1>2</td>
		<td>Input: Especificações do projeto desejado, como autor ou nome.<br>
		Feedback: Acesso ao projeto desejado.<br>
		Plano: Navegar pelos projetos ate chegar no desejado.<br>
		Recomendação: Encontrar o projeto desejado o mais eficientemente possivel.</td>
	</tr>	
	<tr>
		<td>1. Entrar no site do Meraki</td>
		<td>Input: URL do site.</td>
	</tr>	
	<tr>
		<td>2. Ir a aba Achar Projeto</td>
		<td>Plano: Especificar projeto desejado.</td>
	</tr>	
	<tr>
		<td>3. Encontrar projeto 1/2</td>
		<td>Input: Especificações do projeto.</td>
	</tr>	
	<tr>
		<td>3.1. Através de projetos recentes</td>
		<td>Input: Atividade recente no site.<br>
		Plano: Encontrar um projeto que foi visualizado recentemente.</td>
	</tr>	
	<tr>
		<td>3.2. Através de busca 1>2</td>
		<td>Plano: Especificar projeto desejado.<br>
		Recomendação: Especificar as caracteristicas mais importantes somente, para ganhar tempo.</td>
	</tr>	
	<tr>
		<td>3.2.1. Digitar palavras chave</td>
		<td>Input: Palavras chave do projeto.</td>
	</tr>	
	<tr>
		<td>3.2.2. Confirmar busca 1/2</td>
		<td>Plano: Obter projetos de acordo com as especicacoes.</td>
	</tr>	
	<tr>
		<td>3.2.2.1. Apertar botao Buscar</td>
		<td>Feedback: Vizualizar todos os cards que condizem com as especificacoes.</td>
	</tr>	
	<tr>
		<td>3.2.2.2. Apertar botao Enter</td>
		<td>Feedback: Vizualizar todos os cards que condizem com as especificacoes.</td>
	</tr>	
	<tr>
		<td>4. Clicar sibre o card do projeto</td>
		<td>Plano: Encontrar o card procurado.</td>
	</tr>	
</table>

## Criar um novo projeto
<img src="../assets/aht/CriarProjeto.png">

<table class="tarefa">
	<tr>
		<th class="tarefa_header">Operações</th>
		<th>Problemas e recomendações</th>
	</tr>
	<tr>
		<td>0. Criar um novo projeto 1>2</td>
		<td>Input: nome do projeto, descrição, próximos passos, palavras-chave e tipo de ajuda.
		Feedback: Tela de criação de novo projeto aparece.
		<br>
		Plano: Informar dados e criar projeto com os dados enviados.
		<br>
		Problema: Ao criar projeto, não possui feedback do processo.
		<br>
		Recomendação: Redirecionar o usuário à página de Meus projetos.
</td>
	</tr>	
	<tr>
		<td>1. Entrar no site Meraki</td>
		<td>Plano: Informar credenciais e entrar na respectiva conta.</td>
	</tr>	
	<tr>
		<td>2. Ir à página de criação de projeto 1/2</td>
		<td>Plano: Navegar até a página de criação de projeto.</td>
	</tr>	
	<tr>
		<td>2.1 Através da aba Meus projetos</td>
		<td>Plano: Acessar a aba de Meus projetos.</td>
	</tr>	
	<tr>
		<td>2.2 Através da aba Criar Projeto</td>
		<td>Plano: Acessar diretamente a aba Criar projeto.</td>
	</tr>	
	<tr>
		<td>3. Preencher informações do projeto 1>2</td>
		<td>Plano: Informar as informações do novo projeto</td>
	</tr>	
	<tr>
		<td>3.1 Digitar nome do projeto</td>
		<td>Plano: Informar nome do projeto.</td>
	</tr>	
	<tr>
		<td>3.2 Digitar descrição do projeto</td>
		<td>Plano: Informar a descrição do novo projeto.</td>
	</tr>	
	<tr>
		<td>3.3 Digitar próximos passos</td>
		<td>Plano: Informar os próximos passos do novo projeto.</td>
	</tr>	
	<tr>
		<td>3.4 Digitar palavras-chave</td>
		<td>Plano: Informar as palavras-chave do novo projeto.</td>
	</tr>	
	<tr>
		<td>3.5 Escolher tipo de ajuda 1/2</td>
		<td>Plano: Informar o tipo de ajuda desejada.</td>
	</tr>
	<tr>
		<td>3.5.1 Escolher todos</td>
		<td>Plano: Definir tipo de ajuda do projeto como “todos”.</td>
	</tr>
	<tr>
		<td>3.5.2 Escolher Criação</td>
		<td>Plano: Definir tipo de ajuda do projeto como “Criação”.
		<br>
				Recomendação: Informar ao usuário o significado de “Criação”.
		<br>
</td>
	</tr>
	<tr>
		<td>3.5.3 Escolher Consultoria</td>
		<td>Plano: Definir tipo de ajuda do projeto como “Consultoria”.
		<br>
 				Recomendação: Informar ao usuário o significado de “Consultoria”.
		<br>
</td>
	</tr>
	<tr>
		<td>4. Clicar em criar</td>
		<td>Plano: Efetivar criação do novo projeto</td>
	</tr>
</table>

## Exclusão de conta
<img src="../assets/aht/ExcluirConta.png">
<br>

<table class="tarefa">
	<tr>
		<th class="tarefa_header">Operações</th>
		<th>Problemas e recomendações</th>
	</tr>
	<tr>
		<td>0. Excluir conta 1>2</td>
		<td>Feedback: Não ter uma conta no site.<br>
		Plano: Retirar seus dados do Meraki.<br>
		Recomendação: Previnir remoções acedentais de conta.</td>
	</tr>	
	<tr>
		<td>1. Entrar no site do Meraki</td>
		<td>Input: URL do site.</td>
	</tr>	
	<tr>
		<td>2. Clicar sobre o usuário</td>
		<td>Problema: Não encontrar o botão de usuário.</td>
	</tr>	
	<tr>
		<td>3. Clicar em minha conta</td>
		<td>Plano: Acessar a conta que será removida.</td>
	</tr>	
	<tr>
		<td>3. Clicar em excluir conta</td>
		<td>Problema: Chegar nessa página sem intenção.<br>
		Recomendação: Não tornar fácil para o usuário confirmar a exclusão de uma conta.</td>
	</tr>	
	<tr>
		<td>4. Clicar em sim</td>
		<td>Plano: Apagar todos os seus dados permanentemente.<br>
		Feedback: A inexistência de sua conta.</td>
	</tr>
</table>

## Referências <div class="line"></div>
<p text-align="justify">&emsp;&emsp;CAIADO, Márcio Sequeira. Análise de Tarefas. Análise Hierárquica de Tarefas. DOCPLAYER, 2019. Disponível em: <a href=https://docplayer.com.br/13376795-Analise-de-tarefas-analise-hierarquica-de-tarefas.html>https://docplayer.com.br/13376795-Analise-de-tarefas-analise-hierarquica-de-tarefas.html</a>. Acesso em: 5 nov. 2019.</p>
