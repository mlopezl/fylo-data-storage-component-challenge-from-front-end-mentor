# Frontend Mentor - Solución del Componente de Almacenamiento de Fylo

Esta es mi solución al desafío **Fylo Data Storage Component** de Frontend Mentor. Este reto me permitió practicar la creación de un componente de interfaz responsivo utilizando HTML semántico y técnicas modernas de CSS, siguiendo de forma precisa el diseño proporcionado.

## Tabla de contenidos
- [Descripción general](#descripción-general)
- [El desafío](#el-desafío)
- [Diseño](#diseño)
- [Enlaces](#enlaces)
- [Mi proceso](#mi-proceso)
- [Tecnologías utilizadas](#tecnologías-utilizadas)
- [Lo que aprendí](#lo-que-aprendí)

## Descripción general
Este proyecto consiste en un componente de almacenamiento de datos responsivo que muestra cuánto espacio ha sido utilizado y cuánto queda disponible. El componente se adapta a diferentes tamaños de pantalla e incluye una barra de progreso personalizada, elementos decorativos y una interfaz limpia y moderna inspirada en el diseño original de Fylo.

El objetivo fue replicar el diseño con la mayor fidelidad posible, manteniendo un código limpio, legible y fácil de mantener.

## El desafío
Los usuarios deben poder:
- Ver el diseño óptimo según el tamaño de pantalla de su dispositivo.
- Visualizar el uso del almacenamiento mediante una barra de progreso.
- Leer claramente la información de almacenamiento tanto en escritorio como en dispositivos móviles.
- Experimentar un diseño que se acerque fielmente al proporcionado por Frontend Mentor.

## Diseño

- Diseño de escritorio

<img src="./design/desktop-design.jpg" alt="Vista previa en escritorio" width="600">

- Diseño móvil

<img src="./design/mobile-design.jpg" alt="Vista previa en móvil" width="150">

## Enlaces
- URL de la solución: [Repositorio en GitHub](https://github.com/mlopezl/fylo-data-storage-component-challenge-from-front-end-mentor)
- URL del sitio en vivo: [Demo en vivo](https://mlopezl.github.io/fylo-data-storage-component-challenge-from-front-end-mentor/)

## Mi proceso
- Estructuré el layout utilizando **HTML5 semántico**.
- Utilicé **Flexbox** para alinear y distribuir el contenido dentro de los componentes principales.
- Estilicé el proyecto usando **propiedades personalizadas de CSS (variables)** para mantener una paleta de colores consistente y reutilizar gradientes.
- Personalicé el elemento nativo `<progress>` para que coincidiera con el diseño, incluyendo estilos específicos por navegador.
- Apliqué **posicionamiento absoluto** para elementos decorativos como el indicador de almacenamiento y la figura triangular.
- Implementé **diseño responsivo** mediante media queries para adaptar el layout a pantallas de escritorio y móviles.
- Seguí la **metodología BEM** para el nombrado de clases, manteniendo el CSS organizado y escalable.

## Tecnologías utilizadas
- HTML5
- CSS3
- Flexbox
- Propiedades personalizadas de CSS (variables)
- Principios de diseño responsivo
- Metodología BEM

## Lo que aprendí
- Cómo personalizar elementos HTML nativos como `<progress>` para lograr una interfaz más pulida.
- Manejar layouts con **Flexbox** manteniendo los componentes modulares y reutilizables.
- Usar **variables CSS** de forma efectiva para colores, gradientes y consistencia visual.
- Crear elementos decorativos de interfaz utilizando solo CSS (`border-radius`, `clip-path`, `position`).
- Mejorar layouts responsivos mediante media queries y posicionamiento adaptativo.
- Escribir CSS más limpio y mantenible siguiendo las **convenciones BEM**.
