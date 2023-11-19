# 🍞 Le Pain Artisan 🌾

Sistema desenvolvido com o objetivo de auxiliar o controle de estoque dos produtos alimentícios de uma padaria.

## 🚀 Começando

Essas instruções permitirão que você obtenha uma cópia do projeto em operação na sua máquina local para fins apresentativos.


### 📋 Pré-requisitos

Alguns programas necessarios para rodar nosso sistema:

* 📁Padaria - "Padaria.zip" que iremos disponibilizar o download.
* [Xampp](https://www.apachefriends.org/) - conexao com o banco de dados criando ambiente local.


### 🔧 Instalação

Siga o passo a passa para instalar e abrir o programa:

1 - Baixar a pasta "Padaria" e o "Xampp" na maquina. Localizar pasta "xampp" dentro do DISCO LOCAL (C:) (ou outro local que o usuario escolheu para instalar o Xampp), seguir o caminho: 📁xampp >> 📁htdocs >> 📁Padaria (colar a pasta "Padaria" e excluir todos os demais arquivos). Após a instalação do Xampp, abri-lo e selecionar "start" no Apache e MySQL.

2 - Abrir o Xampp e clicar no ADMIN do MySQL. Vai abrir uma pagina WEB do painel de gerenciamento. Clique em NOVO na esquerda do navegador, BANCO DE DADOS na parte superior do navegador, coloque o nome da estrutura como "padaria". Seleciona a estrutura "padaria", vai em IMPORTAR no canto superior do site e selecione IMPORTAR ARQUIVO, fazendo o caminho 📁xampp >> 📁htdocs >> 📁Padaria >> 🗃️padaria (tipo do arquivo: ARQUIVO FONTE SQL). Após isso basta descer a pagina até o final e selecionar o botao IMPORTAR.

3 - Dentro do Xampp clicar no ADMIN do Apache. Vai abrir o endereço de site "localhost" no navegador padrão. Siga o caminho dentro do navegador: 📁Padaria >> 📁pages/ >> Site do sistema irá abrir.

💻 PROGRAMA ABERTO E PRONTO PARA USO!

## ⚙️ Possibilidades dentro do sistema

Após a instalação, na [tela inicial](http://localhost/Padaria/pages/) do sistema é possível ver 4 ícones interativos:

- [cadastro](http://localhost/Padaria/pages/?page=cadastro) - onde é possível cadastrar produtos dentro do sistema 
- [estoque](http://localhost/Padaria/pages/index.php?page=listar) - onde mostra o estoque cadastrado
- [contato](http://localhost/Padaria/pages/contato.html) - informações para contato da padaria
- [sobre](http://localhost/Padaria/pages/sobreNos.html) - informaçõe contando sobre a padaria e seus colaboradores


## 📦 Implantação

É um programa simples que atende a necessidade de gerenciar o estoque de uma padaria ou algum outro ambiente que tenha um estoque alimentício. Ressaltando que é possível adicionar ou remover "tipos" de produtos (como salgado, doce ou bebida) abrindo a possibilidade de levar o sistema para empresas de outras áreas alimentícias.

## 🛠️ Construído com

Mencione as ferramentas que você usou para criar seu projeto

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - O framework web usado
* [Maven](https://maven.apache.org/) - Gerente de Dependência
* [ROME](https://rometools.github.io/rome/) - Usada para gerar RSS

## 🖇️ Colaborando

Por favor, leia o [COLABORACAO.md](https://gist.github.com/usuario/linkParaInfoSobreContribuicoes) para obter detalhes sobre o nosso código de conduta e o processo para nos enviar pedidos de solicitação.

## 📌 Versão

Nós usamos [SemVer](http://semver.org/) para controle de versão. Para as versões disponíveis, observe as [tags neste repositório](https://github.com/suas/tags/do/projeto). 

## ✒️ Autores

Mencione todos aqueles que ajudaram a levantar o projeto desde o seu início

* **Um desenvolvedor** - *Trabalho Inicial* - [umdesenvolvedor](https://github.com/linkParaPerfil)
* **Fulano De Tal** - *Documentação* - [fulanodetal](https://github.com/linkParaPerfil)

Você também pode ver a lista de todos os [colaboradores](https://github.com/usuario/projeto/colaboradores) que participaram deste projeto.

## 📄 Licença

Este projeto está sob a licença (sua licença) - veja o arquivo [LICENSE.md](https://github.com/usuario/projeto/licenca) para detalhes.

## 🎁 Expressões de gratidão

* Conte a outras pessoas sobre este projeto 📢;
* Convide alguém da equipe para uma cerveja 🍺;
* Um agradecimento publicamente 🫂;
* etc.


---
