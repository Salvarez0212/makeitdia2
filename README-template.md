# Make It Real - NAME OF THE PROJECT

This is a solution to the HTML 2 Make It Real - Stats preview card component- top27 project of the Make It Real course.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Su desafío es construir este componente de la tarjeta y lograr que se parezca lo más posible al diseño.

Puedes usar cualquier herramienta que te guste para ayudarte a completar el desafío. Entonces, si tienes algo que te gustaría practicar, no dudes en intentarlo.

Tus usuarios deberían poder:

Ver el diseño óptimo para el componente según el tamaño de pantalla de su dispositivo

### Screenshot
Vista mobile 375px
![image](https://user-images.githubusercontent.com/102271918/215847138-4446b28c-9542-45f9-ad51-02a9ef975fcd.png)

Vista desktop 1440px
![image](https://user-images.githubusercontent.com/102271918/215847393-a0e88811-f229-490b-a61b-9525ab77e521.png)




## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

- El uso de las propiedades de posicion absoluta y relativa para superponer el color de la imagen.
- El manejo de los "div" para organizacion de la informacion tanto de texto como imagen.

HTML para filtro de imagen

 <picture class="img_container">
       <div class="img_filter"></div>
       <img src="./assets/image-header-desktop.jpg" alt="">
 </picture>

CSS para filtro de imagen

.img_container img{
    width: 100%;
    display: block;
    border-radius: 10px 10px 0 0;
}

.img_filter {
    width: 100%;
    height: 100%;
    position: absolute;
    background-color: rgb(138 15 155 / 40%);
    border-radius: 10px 10px 0 0;
}



### Continued development

El desarrollo de aplicaciones para trabajo no solo en pc, sino que sean funcionales para tablets o smartphones, que tengan una interfaz amigable y con la estructura necesaria.

### Useful resources

- [Example resource 1](https://www.example.com)](https://developer.mozilla.org/es/docs/Web/CSS/:nth-child) - Recurso usado para referirse a una etiqueta comun en un grupo de hermanos
- [Example resource 2](https://www.example.com)](https://htmlcolorcodes.com/es/) - Usado para encontrar el color del filtro de imagen
- [Example resource 3](https://developer.mozilla.org/es/docs/Web/HTML/Element/b) - Se utilizó la documentación para cambiar la propiedad de una palabra dentro del texto

## Author

- [Sebastian Alvarez and Oscar Nuñez]


