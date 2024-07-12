# Curso Git e GitHub

Inicializar o Git
```sh
git init
```
Referências de configuração Git: [Configurações iniciais do Git](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Configura%C3%A7%C3%A3o-Inicial-do-Git)
```sh
git config --global user.name "Fulano de Tal"
git config --global user.email fulanodetal@exemplo.br
```
Referências de configuração Git: [Configurações básicas de branch](https://git-scm.com/book/en/v2/Git-Branching-Branch-Management)

Trocando o nome do branch principal para main
```sh
git branch --move master main
```
Referências de configuração Git: [Obtendo repositório Git](https://git-scm.com/book/pt-br/v2/Fundamentos-de-Git-Obtendo-um-Reposit%C3%B3rio-Git)

Clonar um repositório do GitHub

```sh
git clone endereço-da-url-do-repositório-a-ser-clonado
```

Referências de configuração Git: [Gravando alterações](https://git-scm.com/book/pt-br/v2/Fundamentos-de-Git-Gravando-Altera%C3%A7%C3%B5es-em-Seu-Reposit%C3%B3rio)

Adicionar todos arquivos para commit

```sh
git add .
```
Realizar um commit

```sh
git commit -m "texto para identificar o commit"
```
