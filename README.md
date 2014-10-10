#Init WEB

Todos os arquivos ou pastas que iniciem com `_` não é usado para publicação do projeto.


Usamos as seguintes bibliotecas

* Sass
* Compass
* GULP
* Moderniz


Para metologia de organização adotamos :
* Atomic Design

A pasta `_docs` é para ser colocada os arquivos que usará no projeto ex: layout.jpg, briefing.jpg,

## GULP

Módulos excessiais para criação dos módulos.

###Instalação

```js
npm install gulp gulp-jshint gulp-uglify gulp-concat gulp-rename --save-dev
```

## Compass
Usamos pois gostamos bastante da diagramação mas
### Variáveis padrões do compass que usamos


##SEO
Caso o projeto seja One Page Altere as seguintes linhas do google annalytic  

###OLD
```js
ga('create', 'UA-XXX-X', 'website.org');
ga('send', 'pageview');
```
###NEW:
```js
ga('create', 'UA-XXX-X', {'allowAnchor': true});
ga('send', 'pageview', { 'page': location.pathname + location.search + locat
```

## META TAGS
Caso necessite acrescentar novas metatags seja  no Head onde achar mais confortável mas recomendamos logo abaixo das metatags

###Compartilhamento
####Facebook
	
	Caso seja um site normal
	
	```html 
	<meta property="og:type" content="website">
	```
	
	Caso seja um artigo
	
	```html
	<meta property="og:type" content="article">
	<meta property="article:author" content="Autor do artigo">
	<meta property="article:section" content="Seção do artigo">
	<meta property="article:tag" content="Tags do artigo">
	<meta property="article:published_time" content="date_time">
	```

##APP Manifest
Um manifesto de aplicativo contém informação necessário para que o navegador web interaja com um aplicativo. Ele provê tanto elementos para serem lidos por humanos (um nome, um conjunto de ícones, uma descrição; possivelmente em várias línguas) quanto elementos para serem lidos por máquinas, que permite ao navegador exibir e executar aplicativos

Saiba mais em : Developer Mozila Manifest https://developer.mozilla.org/pt-BR/Apps/Manifest