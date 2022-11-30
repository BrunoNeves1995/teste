# Repositorio de configuração
Esse repositorio serve apenas como demo para criação e configuração.

## Comando uteis do GitHub

Logando no github via terminal

	 gh auth login

Clonando um repositorio

	git clone UrlAquiProjeto NovoNomeDoProjeto

configuções antes de iniciar o repositorio

	git config --global init.defaultBranch main	
	git config --global user.name "Seu Nome"
	git config --global user.email "seu Email do git"

Inicia um novo repositório

	git init
	
Mostra os estatus dos arquivos

	git status

Adicionar todos os arquivos
	
	git add .
	git add NomeArquivo
  git add NomeArquivo


Salvando as informações com a mensagem

	git commit -m "mensagem do seu commit"


Associar ao meu repositório, ao meu endereço local
	
	git remote add origin UrlDoseuRepositorio


Enviando os arquivos para nuvem
	
	git push origin main
