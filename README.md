<h1 align="center">
    Parallax Landing Page
</h1>

<p align="center">	
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/yuripalacio/parallax-landing-page">

  <a href="https://www.linkedin.com/in/yuripalacio/">
    <img alt="Made by yuripalacio" src="https://img.shields.io/badge/made%20by-Yuri%20Palacio-%2304D361">
  </a>
  
  <a href="https://github.com/yuripalacio/parallax-landing-page/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/yuripalacio/parallax-landing-page">
  </a>
  
  <a href="https://github.com/yuripalacio/mychat/blob/master/LICENSE">
    <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">
  </a>
</p>

<p align="center">
  <a href="#sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#parallax">Parallax</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#referências">Referências</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#licença">Licença</a>
</p>

# Sobre

Projeto tem o objetivo de explorar um pouco o uso do [Rellax.js](https://www.npmjs.com/package/rellax) e com isso criar uma landing page utilizando o efeito Parallax.

<h1 align="center">
    <img alt="LandingPage" title="#LandingPage" src=".github/main.png" width="1000px" />
</h1>

# Parallax

De uma forma geral, o segredo está em incluir o Rellax e aplicar suas funcionalidades.

```html
<script>
  let rellax = new Rellax('.rellax');
</script>
```
Dessa forma, todas as nossas classes `rellax` está aptas a ter os efeitos da biblioteca Rellax.js.
Por meio da propriedade `html data-rellax-speed` podemos definir a velocidade que queremos e ver todo o efeito acontecendo.

``` html 
<div class="rellax" data-rellax-speed="4" data-rellax-xs-speed="3">
  <i class="fas fa-users fa-3x secondary-text"></i>
  <h2>Share<span class="secondary-text dot">.</span></h2>
  <p>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore et
      dicta consectetur incidunt omnis nam quis quidem nisi ipsa deserunt.
  </p>
</div>
```
# Tecnologias

- HTML
- CSS
- [Rellax.js](https://www.npmjs.com/package/rellax)

# Referências

<p>
https://www.youtube.com/watch?v=aAxt0Z7IXIo

## Licença

Esse projeto está sob a licença MIT. Veja o arquivo <a href="https://github.com/nathaliacristina20/gorestaurant/blob/master/LICENSE">LICENSE</a> para mais detalhes.

<hr />

By [Yuri Palacio](https://www.linkedin.com/in/yuri-palacio/) :wave:
