# siega
CONTROLE DE VERSÃO:
	rastreabilidade.

REPOSITORIO:
	
	LOCAL:
		pode ser acessado somente na sua maquina;
 
	REMOTO:
		será acessível em qualquer maquina;
		pode se ver os commit

COMMIT:
	é como um checkpoint ele vai salvando o seu código como se tivesse fazendo uma "fotografia" e vai salvar
	as alterações com uma mensagem, porque se o seu código quebrar vc vai poder voltar até o ´ponto que você
	salvou por isso "checkpoint".

LOG:
	salva o commit feito
	registro do que foi feito

BRANCH:
	vai permitir que varias pessoas trabalhem ao mesmo tempo no mesmo projeto.
	
	se pode criar linhas paralelas mas não necessariamente vai alterar o projeto principal desde que estejam 
	isoladas, para que as vezes tentando corrigir o erro acabe criando mais no projeto principal mas não vai
	quebrar os códigos dos outros.

PULL:
	vai baixar as alterações que estão no repositório remoto (ex: GitHub) e vai atualizar o local.

git init:
	Inicia um repositório Git local na pasta do seu projeto. Cria a estrutura para controlar versões.

git status:
	Mostra o estado atual dos arquivos no repositório: quais foram modificados, adicionados ou ainda não estão sendo monitorados.

git add [arquivo]:
	Adiciona o arquivo para a "área de stage", ou seja, prepara ele para o próximo commit.

git commit -m "mensagem":
	Salva as alterações que foram adicionadas com git add, criando um checkpoint com uma mensagem explicando o que foi feito.

git log:
	Exibe o histórico dos commits feitos, mostrando as mensagens e os códigos identificadores.

git branch:
	Mostra as ramificações (branches) do projeto, ou cria uma nova linha de desenvolvimento paralela.

git checkout [branch/nome]:
	Troca para outra branch, para trabalhar em outra linha do projeto.

git pull:
	Puxa (baixa) as atualizações do repositório remoto (ex: GitHub) para o seu repositório local, atualizando o código.

git push:
	Envia os commits feitos localmente para o repositório remoto, compartilhando suas alterações.

