# Initialize WEB

Todos os arquivos ou pastas que iniciem com `_` não servirá para publicação do projeto.

A pasta `_docs` é para ser colocada os arquivos que usará no projeto ex: layout.jpg, briefing.jpg.

Usamos as seguintes worflow
* Sass / Compass
* GULP
<<<<<<< HEAD
* Moderniz
=======
>>>>>>> FETCH_HEAD

Bibliottecas
* Moderniz Configure para deixar apenas o necessário http://modernizr.com/download/

Para metologia de organização adotamos :
* Atomic Design


## GULP
	
Módulos excessiais para criação do projeto dos módulos.

### Instalação

```js
npm install -g gulp

npm install gulp --save-dev
npm install gulp-util --save-dev
npm install gulp-uglify --save-dev
npm install gulp-watch --save-dev
npm install gulp-compass --save-dev
npm install gulp-jshint --save-dev
npm install gulp-plumber --save-dev
npm install gulp-imports --save-dev
npm install gulp-imagemin --save-dev
npm install beeps -g
npm install beep
npm install --save-dev gulp-livereload
```

## Compass
Usamos pois gostamos bastante da diagramação mas
### Variáveis padrões do compass que usamos


## SEO
Caso o projeto seja One Page Altere as seguintes linhas do google annalytic  

### OLD

```js
ga('create', 'UA-XXX-X', 'website.org');
ga('send', 'pageview');
```
### NEW:

```js
ga('create', 'UA-XXX-X', {'allowAnchor': true});
ga('send', 'pageview', { 'page': location.pathname + location.search + locat
```

## META TAGS

Caso necessite acrescentar novas metagas seja  no Head onde achar mais confortável mas recomendamos logo abaixo das metatags
Caso seja um site normal

```html 
<meta property="og:type" content="website">
```html

Caso seja um artigo

```html
<meta property="og:type" content="article">
<meta property="article:author" content="Autor do artigo">
<meta property="article:section" content="Seção do artigo">
<meta property="article:tag" content="Tags do artigo">
<meta property="article:published_time" content="date_time">
```html

### Compartilhamento

#### Facebook
	
## APP Manifest

Um manifesto de aplicativo contém informação necessário para que o navegador web interaja com um aplicativo. Ele provê tanto elementos para serem lidos por humanos (um nome, um conjunto de ícones, uma descrição; possivelmente em várias línguas) quanto elementos para serem lidos por máquinas, que permite ao navegador exibir e executar aplicativos

Saiba mais em : Developer Mozila Manifest https://developer.mozilla.org/pt-BR/Apps/Manifest
