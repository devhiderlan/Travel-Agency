# Travel-Agency

## Visão Geral

### Projeto de um Website simulando uma agência de viagens.
#

![](./Assets/images/travel.png)

#
## Construido com:
- HTML
- CSS 
- SASS
- JavaScript

## Bibliotecas utilizadas:
- [Font Awesome cdn link](https://cdnjs.com/libraries/font-awesome)
- [AOS Animate On Scroll Library](https://michalsnik.github.io/aos/) 
#
## Funcionalidades
- Site interativo de uma Agência de Viagens.
- Menu de navegação responsivo.
#
## O que eu aprendi:

- Estilização com o SASS

```css
.destination .box-container {
   @include grid(27rem);

   .box {
      border-radius: 1rem;
      overflow: hidden;
      background: $bg-color;

      &:hover img {
         transform: scale(1.1);
      }

      .image {
         height: 20rem;
         overflow: hidden;
         width: 100%;

         img {
            height: 100%;
            width: 100%;
            object-fit: cover;
         }
      }

      .content {
         padding: 2rem;
         text-align: center;

         h3 {
            font-size: 2rem;
            color: $white;
         }

         p {
            padding: 1rem 0;
            font-size: 1.4rem;
            color: $light-color;
            line-height: 2;
         }

         a {
            font-size: 1.7rem;
            color: $blue;

            &:hover i {
               padding-left: 1rem;
            }

            i {
               padding-right: 0.7rem;
            }
         }
      }
   }
}


```

- Manipulação do DOM com:
```js
  document.querySelector('.main-container')
  document.querySelectorAll('.btn')
  document.getElementById('submit')
```

- Eventos no DOM
```js
let navbar = document.querySelector('.header .navbar')

document.querySelector('#menu-btn').onclick = () => {
  navbar.classList.toggle('active')
}

window.onscroll = () => {
  navbar.classList.remove('active')
}
```
- Boas práticas com JavaScript

## Link

Veja o resultado do projeto [clicando aqui 🔍](https://devhiderlan.github.io/Travel-Agency/) 

## Autor

Hiderlan Santana: [Linkedin](https://www.linkedin.com/in/hiderlan-santana/)