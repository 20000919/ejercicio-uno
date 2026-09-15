# Layout Ejercicio Uno

La estructura de la página ocupa el **100% de ancho** y **100vh de alto**. Ahora está maquetada **exclusivamente usando Flexbox y Box Model**.

## Medidas y Proporciones:

- **Contenedor Principal (body):**
  - Ancho: `100%`
  - Alto: `100vh`
  - Comportamiento: `display: flex; flex-wrap: wrap;`

- **Header:**
  - Ancho: `100%`
  - Alto: `10%` (equivale a `10vh`)

- **Aside:**
  - Ancho: `20%`
  - Alto: `80%` (equivale a `80vh`)

- **Main:**
  - Ancho: `80%`
  - Alto: `80%` (equivale a `80vh`)
  - Comportamiento: `display: flex; flex-direction: column;`
  
  *El `main` contiene dos secciones divididas verticalmente (flexbox):*
  - **Sección de Imagen (mitad superior):**
    - Ancho: `100%` (del ancho de main)
    - Alto: `50%` (del alto de main, equivale a `40vh`)
    - *Nota: la imagen ocupa un `60%` del ancho de la sección y el texto acompaña a su lado ocupando el `40%`, sin usar position.*
  - **Sección de Galería (mitad inferior):**
    - Ancho: `100%` (del ancho de main)
    - Alto: `50%` (del alto de main, equivale a `40vh`)

- **Footer:**
  - Ancho: `100%`
  - Alto: `10%` (equivale a `10vh`)
