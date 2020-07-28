
<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio 04: Conceitos do React Native
</h3>

<blockquote align="center">“Sucesso não é o resultado de um jogo, mas o destino de uma jornada”!</blockquote>

<p align="center">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
</p>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## :rocket: Sobre o desafio

Nesse desafio, você deve criar uma aplicação para treinar o que você aprendeu até agora no React Native!

Agora você deve continuar desenvolvendo a aplicação que irá armazenar repositórios do seu portfólio, que você já desenvolveu o backend utilizando o Node.js, e no último desafio em ReactJS.

## :hammer: Tecnologias

 - [React Native](https://reactnative.dev/) 
 - [TypeScript](https://www.typescriptlang.org/)
 - [Axios](https://www.npmjs.com/package/axios)
 

## :key: Como rodar esse projeto.

Para clonar e executar este aplicativo, você precisará de  [Git](https://git-scm.com/),  [NodeJs](https://nodejs.org/)  Instalado em seu computador.

O projeto é composto por duas aplicações:

1.  Back-End ([Link do Repositório](https://github.com/LuizSerra/GoStack-ConceitosNodeJS))

💡  E preciso efetuar o clone e seguir os passos de instalação do  [Repositório da API](https://github.com/LuizSerra/GoStack-ConceitosNodeJS)

💡 A aplicação precisa que o Back-End esteja sendo executado na porta 3333 para funcionar.

### :sheep: Clonando o repositório.
```
# Clone este repositório
$ git clone https://github.com/LuizSerra/GoStack-ConceitosReactNative.git

# Acesse a pasta do projeto no terminal/cmd
$ cd goStack-ConceitosReactNative
```
### :computer: Rodando a aplicação.

```console

# Instale as dependências
$ yarn

# Instale as dependências IOS (somente se for usar IOS)
$ cd ios
$ pod install

# Execute a Aplicação Android (somente se for usar Android)
$ yarn android

# Execute a Aplicação IOS (somente se for usar IOS)
$ yarn ios
```

### Funcionalidades da aplicação

Agora que você já está com o template clonado, e pronto para continuar, você deve abrir o arquivo **src/App.js**, e completar onde não possui código com o código para atingir os objetivos de cada funcionalidade.

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista de todos os repositórios que estão cadastrados na sua API com os campos **title**, **techs** e número de curtidas seguindo o padrão `${repository.likes} curtidas`, apenas alterando o número para ser dinâmico.

- **`Curtir um repositório listado da API`**: Deve ser capaz de curtir um item na sua API através de um botão com o texto **Curtir** e deve atualizar o número de likes na listagem no mobile.

### Específicação dos testes

Em cada teste, tem uma breve descrição no que sua aplicação deve cumprir para que o teste passe.

Caso você tenha dúvidas quanto ao que são os testes, e como interpretá-los, dé uma olhada em **[nosso FAQ](https://github.com/Rocketseat/bootcamp-gostack-desafios/tree/master/faq-desafios).**

Para esse desafio temos os seguintes testes:

- **`should add a like to the like counter of the repository`**: Para que esse teste passe, sua aplicação deve permitir ao clicar no botão `Curtir`, um like seja adicionado ao repositório listado, e que essa atualização possa ser visualizada na tela.

## :computer: Quer contribuir com o Projeto? Saiba como:

-   Faça um  **fork**  do projeto;
-   Crie uma nova branch com as suas alterações:  `git checkout -b my-feature`
-   Salve as alterações e crie uma mensagem de commit contando o que você fez:`git commit -m "feature: My new feature"`
-   Envie as suas alterações:  `git push origin my-feature`

> Caso tenha alguma dúvida confira este [guia de como contribuir no GitHub](https://github.com/firstcontributions/first-contributions)


## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

Feito com dedicação por Luiz Serra 👋🏽 [Entre em contato](https://www.linkedin.com/in/luizserra)!

