<h1 align="center"> Como criar e personalizar o Readme dos seus projetos </h1>

:wink: Neste artigo você aprenderá como personalizar o readme dos seus projetos no github. <br>

Mais o que seria README (ou leia-me)? Bem, é um arquivo com extensão .md, 
ou seja ele é escrito em Markdown Syntax que é uma sintaxe usada para padronizar e facilitar a formatação de texto na web.


##  :bulb: Porque é importante? 
Bem, depois de desenvolver seu projeto e subir no  github você vai documentar o seu trabalho para que quem visite seu repositório saiba do que se trata.
E podemos fazer isso por meio do README, que é o primeiro arquivo a ser visto, ou seja, é a porta de entrada para o seu projeto! 
- :rocket: Além disso, algumas pessoas utilizam o perfil GitHub como portfólio, se esse for o seu caso, é interessante apostar em arquivos README para deixar seus projetos mais atrativos até mesmo para recrutadores.
<br>

## Alguns exemplos do que ter no README
- Título e Imagem de capa;
- Badges;
- Índice;
- Descrição do Projeto;
- Status do Projeto;
- Funcionalidades e Demonstração da Aplicação;
- Acesso ao Projeto;
- Tecnologias utilizadas;
- Pessoas Contribuidoras;
- Pessoas Desenvolvedoras do Projeto;
- Licença.


## :pushpin: Título e Imagem de capa:
Você pode colocá-lo dessa maneira:

```Markdown
# Título 
```
<br>
Ou, caso queira colocar ele centralizado, você pode utilizar tags do HTML que funcionam normalmente, dessa forma:

```HTML
<h1 align="center"> Seu título aqui </h1>
```
>Obs: Feito isso, caso queira, você pode fazer uma capa ou logo do projeto para colocar após o título. 
<br>

## :pushpin: Badges:
Seus objetivos são indicar o estado atual do projeto, licença (caso tenha), versões, dependências, testes, dentre outros.
Caso queira fazer suas badges, você pode utilizar o [Shields.io](https://shields.io/), ele fornece na página principal diversos exemplos de Badges e, 
além disso, nele você pode colar o link do seu repositório do GitHub na caixa de texto inicial, assim automaticamente ele irá sugerir algumas Badges 
para você utilizar no seu projeto, fornecendo o link da Badge para copiar e colar no seu README.

Exemplo: 

![status](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

Caso queira deixar centralizado, pode utilizar a tag align do HTML também, dessa forma:

```HTML
<p align="center"><img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/></p>
```
<br>

## :pushpin: Índice: 
O GitHub gera automaticamente um índice para arquivos README, tendo como base os títulos de seção. Para visualizá-lo, selecione o ícone de menu no canto superior 
esquerdo do arquivo. É uma ferramenta excelente para navegar pelo documento, pois redireciona o usuário para o tópico selecionado.
Entretanto, caso você tenha interesse em fazer seu próprio índice para ser visualizado no arquivo, também é possível fazer em Markdown.
Exemplo:

```Markdown
## Índice 
* [Título e Imagem de capa](#Título-e-Imagem-de-capa)
* [Badges](#badges)
* [Índice](#índice)
* [Descrição do Projeto](#descrição-do-projeto)
* [Status do Projeto](#status-do-Projeto)
* [Funcionalidades e Demonstração da Aplicação](#funcionalidades-e-demonstração-da-aplicação)
* [Acesso ao Projeto](#acesso-ao-projeto)
* [Tecnologias utilizadas](#tecnologias-utilizadas)
* [Pessoas Contribuidoras](#pessoas-contribuidoras)
* [Pessoas Desenvolvedoras do Projeto](#pessoas-desenvolvedoras)
* [Licença](#licença)* [Conclusão](#conclusão)
```
<br>

## :pushpin: Descrição do Projeto:
Como é um objetivo do arquivo README descrever o projeto, é legal que você apresente logo após o título ou imagem de capa e/ou Badges caso tenha, uma breve explicação do seu projeto com seu objetivo principal.
<br>

## :pushpin: Status do Projeto:
Caso você opte por não utilizar Badges sobre o status do projeto, é interessante que você coloque essa informação no próprio texto mesmo. 
Exemplo:

```Markdown
> :construction: Projeto em construção :construction:
```

Caso queira centralizar:

```HTML
<h4 align="center">    
 :construction:  Projeto em construção  :construction:
</h4>
```

>Nesse exemplo foi utilizado o emoji :construction:, mas você pode utilizar em qualquer lugar do arquivo, como antes dos subtítulos. Nesse [Gist do Rafael Xavier de Souza](https://gist.github.com/rxaviers/7360908), você pode encontrar uma variedade de emojis para utilizar no seu README e deixá-lo mais descontraído.

<br>

## :pushpin: Funcionalidades e Demonstração da Aplicação:
Você pode listar as funcionalidades do seu projeto para facilitar o entendimento do usuário. 

Para isso, você pode fazer dessa maneira:
```Markdown
# :hammer: Funcionalidades do projeto
- `Funcionalidade 1`: descrição da funcionalidade 1
- `Funcionalidade 2`: descrição da funcionalidade 2
- `Funcionalidade 2a`: descrição da funcionalidade 2a relacionada à funcionalidade 2
- `Funcionalidade 3`: descrição da funcionalidade 3
```

Além disso, se for possível, é interessante apresentar as funcionalidades com um exemplo visual do projeto, como gif, imagens ou vídeo.
>Obs.: Lembrando que o procedimento para colocar gif é o mesmo adotado para imagens e você pode gravar gifs com gravadores de tela, como o [Acethinker](https://www.acethinker.com/).
<br>

## :pushpin: Acesso ao projeto:
Caso o seu projeto esteja no ar com algum serviço de hospedagem, você pode disponibilizar o link para o mesmo. Caso contrário, você pode apostar em gifs e imagens, 
como citado anteriormente, bem como indicar como o usuário pode baixar o projeto, abrir e executar.

Isso pode ser feito em Markdown:

```Markdown
## 📁 Acesso ao projeto
**Indique como é possível baixar ou acessar o código fonte do projeto, seja projeto inicial ou final**
## 🛠️ Abrir e rodar o projeto
**Apresente as instruções necessárias para abrir e executar o projeto**
```
<br>

## :pushpin: Tecnologias utilizadas:
Você também pode citar as tecnologias utilizadas no projeto, é uma ótima forma de demonstrar o que você anda estudando nesse mar que é a tecnologia.

![readme](https://user-images.githubusercontent.com/100203503/167860481-9f2cb8bf-2bc2-4454-a8d7-9c7c26dd5f4a.png)

<br>

Ou colocar os ícones das tecnologias utilizadas: 

![docmreadme PNG](https://user-images.githubusercontent.com/100203503/167860788-72093b39-19bd-40f7-991b-6ef9188128cf.png)

<br>

## :pushpin: Pessoas Contribuidoras: 
Caso o seu projeto tenha contribuidores, é bacana adicionar eles no README. Um exemplo fantástico disso é o Docusaurus, onde se tem as fotos de todos
os contribuidores e um link para outro documento markdown com recados importantes para quem deseja contribuir também.
<br>

## :pushpin: Pessoas Desenvolvedoras do Projeto:
E agora entra você! É importante que você coloque sua foto também, caso não goste de fotos, vale o user padrão do GitHub ou fazer seu próprio Octocat. Além disso,
você pode linkar seu usuário, para caso algum usuário queira entrar em contato ou reportar algo.

```HTML
# Autores
| [<img src="https://avatars.githubusercontent.com/u/37356058?v=4" width=115><br><sub>Camila Fernanda Alves</sub>](https://github.com/camilafernanda) |  [<img src="https://avatars.githubusercontent.com/u/30351153?v=4" width=115><br><sub>Guilherme Lima</sub>](https://github.com/guilhermeonrails) |  [<img src="https://avatars.githubusercontent.com/u/8989346?v=4" width=115><br><sub>Alex Felipe</sub>](https://github.com/alexfelipe) |
| :---: | :---: | :---: |
```

<br>

## :pushpin: Licença:
Geralmente, os repositórios públicos no GitHub são utilizados para compartilhar softwares de código aberto. Porém, para que um repositório seja realmente de código 
aberto, ele precisa ter uma licença dando aos outros usuários a liberdade de usar, alterar e distribuir o software.
Portanto, caso seu repositório tenha uma licença, é essencial que você coloque ela no seu README. 

![licenciareadme](https://user-images.githubusercontent.com/100203503/167861625-7edfe705-2ee2-456d-9744-de94dcc59941.png)

<br>

## :pencil: Documentação e informação extra:
- https://gist.github.com/reginadiana/e044fe93ed81aa04a10361cb841c0409
- https://github.com/othneildrew/Best-README-Template
- https://www.alura.com.br/artigos/escrever-bom-readme
- https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open

## 🧰 Recursos úteis

Você pode encontrar algumas dessas ideias na ferramenta [README Creator](https://readmecreator.herokuapp.com/), site simples que reúne alguns recursos úteis para criação de READMEs de projetos, assim como para perfis. Após preencher os campos adequados e explorar os recursos, ele gerará um README no formato HTML/MD que você poderá continuar editando e adaptando.

### Ferramentas extra
- https://readme.so/pt
- https://www.readme-templates.com/
- https://github.com/Ileriayo/markdown-badges

