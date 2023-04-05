# Sitio Freelancer (Responsive)

Este proyecto es una página web adaptable a dispositivos de distintos tamaños (este tipo de sitio web se conoce en inglés como "responsive").

El propósito de esta página web es que puedas tener una base para armar un portafolio con tus proyectos para que, mediante un formulario, se puedan comunicar contigo.

Las secciones de **Inicio**, **Sobre mí**, **Clientes** y **Contacto** deberán ser agregadas. Aquí solo está la base sobre la cual se podrán trabajar. 

Los iconos se pueden reemplazar de forma fácil, aquí un ejemplo de uno de los iconos utilizados:

```html
<div class="iconos">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-palette" width="40" height="40" viewBox="0 0 24 24" stroke-width="1.5" stroke="#000000" fill="none" stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none"/>
                        <path d="M12 21a9 9 0 1 1 0 -18a9 8 0 0 1 9 8a4.5 4 0 0 1 -4.5 4h-2.5a2 2 0 0 0 -1 3.75a1.3 1.3 0 0 1 -1 2.25" />
                        <circle cx="7.5" cy="10.5" r=".5" fill="currentColor" />
                        <circle cx="12" cy="7.5" r=".5" fill="currentColor" />
                        <circle cx="16.5" cy="10.5" r=".5" fill="currentColor" />
                    </svg>
                </div>
```
Y la paleta de colores también se puede personalizar desde aquí:

```css
:root {
    --blanco: #FFFFFF;
    --oscuro: #212121;
    --primario: #FD6574;
    --secundario: #6C8A9B;
    --gris: #E6E6E4;
    --grisClaro: #F9F5EF;

    --fuente-principal: 3.8rem;
}
```

##Funcionamiento
Aquí puedes ver cómo luce el diseño :)
[Sitio Freelancer](https://neon-kleicha-13e7a5.netlify.app/)

## Tecnologías
- HTML
- CSS

Además, se incluyeron **Google Fonts** para personalizar la fuente y **Tabler Icons** para incorporar íconos.
