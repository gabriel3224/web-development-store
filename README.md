# Projeto de Introdução ao Desenvolvimento Web (SCC0219) - Barão das Skins

Diogo Castanho Emídio - 11297274

Gabriel Monteiro Ferracioli - 11219129

Paulo Henrique Sebastião de Moura - 10310471

# 1. Introdução

## 1.1 Sobre o projeto

O presente projeto é um site de uma loja online que vende *skins* de diversos jogos. Àqueles que não sabem, *skins* são visuais alternativos a elementos de um jogo, podendo ser de personagens (como roupas) ou de itens (designs diferentes para armas, por exemplo). No caso, este site é exclusivo para compras de *skins* de personagens dos seguintes jogos:
* Overwatch;
* Fortnite;
* League of Legends;
* Valorant;
* Among Us.

O site possui 2 (dois) tipos de usuários:
* Administrador (Admin): responsável por registrar/gerenciar administradores, usuários e *skins*. Tem registrado: nome, id, e-mail, telefone e senha (o id e a senha são **admin**);
* Cliente: usuário padrão, que acessa o site para comprar *skins*. Tem registrado: nome, id, e-mail, endereço, telefone e senha.

As *skins*, por sua vez, são registradas com: nome, id, jogo a que pertence, imagem, *spotlight* (animação de como fica no jogo, sendo essa a funcionalidade específica do site), descrição, quantidades vendida e em estoque e preço.

## 1.2 Como instalar

1. Fazer o download do projeto (através do botão _Code_);
2. Clicar duas vezes no arquivo **index.html**, dentro da pasta **frontend**.

O uso é intuitivo, porém o diagrama pode ser útil caso haja dificuldades na navegação (ver seção **Navegação**, em **Descrição do Software**).

# 2. Descrição do Software

## 2.1 Navegação

![Diagrama](https://github.com/gabriel3224/web-development-store/blob/main/documentation/diagrama.png)

Funcionalidades:
* [Página inicial](https://github.com/gabriel3224/web-development-store/blob/main/documentation/telas/p%C3%A1gina%20inicial.png): descrição do site;
* [Entrar](https://github.com/gabriel3224/web-development-store/blob/main/documentation/telas/entrar.png): fazer login;
* [Cadastrar](https://github.com/gabriel3224/web-development-store/blob/main/documentation/telas/cadastrar.png): fazer cadastro;
* Administrador:
  - [Área de usuário](https://github.com/gabriel3224/web-development-store/blob/main/documentation/telas/%C3%A1rea%20de%20usu%C3%A1rio%20(admin).png): escolher ação;
  - [Buscar produtos](https://github.com/gabriel3224/web-development-store/blob/main/documentation/telas/buscar%20produtos%20(admin).png): procurar e excluir produtos;
  - [Produto](https://github.com/gabriel3224/web-development-store/blob/main/documentation/telas/produto%20(admin).png): ver e editar produto (imagem, *spotlight* e informações);
  - [Adicionar produto](https://github.com/gabriel3224/web-development-store/blob/main/documentation/telas/adicionar%20produto.png): criar produto;
  - [Editar perfil](https://github.com/gabriel3224/web-development-store/blob/main/documentation/telas/editar%20perfil%20(admin).png): alterar informações próprias;
  - [Buscar usuários](https://github.com/gabriel3224/web-development-store/blob/main/documentation/telas/buscar%20usu%C3%A1rios.png): ver, editar (conceder ou remover permissão de administrador) e excluir usuários.
* Cliente:
  - [Área de usuário](https://github.com/gabriel3224/web-development-store/blob/main/documentation/telas/%C3%A1rea%20de%20usu%C3%A1rio%20(cliente).png): escolher ação;
  - [Buscar produtos](https://github.com/gabriel3224/web-development-store/blob/main/documentation/telas/buscar%20produtos%20(cliente).png): procurar e adicionar produtos ao carrinho;
  - [Produto](https://github.com/gabriel3224/web-development-store/blob/main/documentation/telas/produto%20(cliente).png): ver (imagem, *spotlight* e informações) e adicionar produto ao carrinho;
  - [Carrinho](https://github.com/gabriel3224/web-development-store/blob/main/documentation/telas/carrinho.png): comprar produto(s);
  - [Editar perfil](https://github.com/gabriel3224/web-development-store/blob/main/documentation/telas/editar%20perfil%20(cliente).png): alterar informações próprias.

Uma observação a ser feita: todas as telas levam à página inicial e à respectiva área de usuário, porém isso não foi incluído no diagrama para não poluir a imagem.

## 2.2 Testes

### 2.2.1 Plano de teste

Pretende-se usar o [Postman](https://www.postman.com/) para testes de *backend*.

### 2.2.2 Resultados



### 2.3 Comentários

Pretende-se implementar ainda um carrossel na página inicial, para mostrar mais de uma imagem, confirmação de compra por e-mail e o *spotlight*.

# 3. Problemas

Por ter sido cobrado somente o HTML5 e o CSS3, não foi possível implementar o carrossel de imagens na página inicial ou o estilo de aplicativo de página única, que são feitos através de JavaScript. Ademais, o [Marvel](https://marvelapp.com/) não é muito intuitivo nem gera o código do site modelado.

# 4. Conclusões


