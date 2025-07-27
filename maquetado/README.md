# Proyecto de Maquetado Web HTML5 + CSS3 + JavaScript

Este archivo documenta paso a paso el proceso de maquetación de una interfaz web basada en los diseños proporcionados.

---

## 1. Estructura HTML5

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Nombre del Proyecto</title>
    <link rel="stylesheet" href="estilos.css" />
  </head>
  <body>
    <header>
      <div class="logo">LOGO</div>
      <nav>
        <ul class="menu">
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Servicios</a></li>
          <li><a href="#">Proyectos</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section class="hero">
        <h1>Título principal</h1>
        <p>Descripción atractiva o llamada a la acción.</p>
        <a href="#" class="btn">¡Comenzar!</a>
      </section>

      <section class="cards">
        <article class="card">
          <h2>Título 1</h2>
          <p>Descripción breve.</p>
        </article>
        <article class="card">
          <h2>Título 2</h2>
          <p>Descripción breve.</p>
        </article>
        <article class="card">
          <h2>Título 3</h2>
          <p>Descripción breve.</p>
        </article>
      </section>
    </main>

    <footer>
      <p>&copy; 2025 - Todos los derechos reservados</p>
    </footer>

    <script src="script.js"></script>
  </body>
</html>
```

---

## 2. Estilos CSS3 (estilos.css)

```css
/* Reset básico */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Segoe UI", sans-serif;
  line-height: 1.6;
  background-color: #f4f4f4;
  color: #333;
}

header {
  background-color: #1e1e2f;
  color: #fff;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  font-size: 1.5rem;
  font-weight: bold;
}

.menu {
  list-style: none;
  display: flex;
  gap: 1.5rem;
}

.menu li a {
  color: #fff;
  text-decoration: none;
  transition: color 0.3s ease;
}

.menu li a:hover {
  color: #00bcd4;
}

.hero {
  padding: 4rem 2rem;
  text-align: center;
  background: linear-gradient(to right, #00bcd4, #2196f3);
  color: white;
}

.hero .btn {
  margin-top: 1rem;
  display: inline-block;
  padding: 0.75rem 1.5rem;
  background-color: #fff;
  color: #2196f3;
  border-radius: 5px;
  text-decoration: none;
  font-weight: bold;
  transition: background-color 0.3s ease;
}

.hero .btn:hover {
  background-color: #e0f7fa;
}

.cards {
  display: flex;
  gap: 2rem;
  justify-content: center;
  padding: 2rem;
  flex-wrap: wrap;
}

.card {
  background-color: white;
  padding: 2rem;
  border-radius: 10px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  width: 300px;
  text-align: center;
}

/* Responsividad */
@media (max-width: 768px) {
  .cards {
    flex-direction: column;
    align-items: center;
  }
}
```

---

## 3. Interactividad con JavaScript (script.js)

```javascript
document.addEventListener("DOMContentLoaded", () => {
  const button = document.querySelector(".btn");
  button.addEventListener("click", () => {
    alert("¡Gracias por visitar nuestra web!");
  });
});
```

---

## 4. Consideraciones de Diseño

- Se utilizaron etiquetas semánticas (`header`, `main`, `section`, `article`, `footer`).
- Se implementó diseño responsivo con `flexbox` y `media queries`.
- El JavaScript añade una interacción básica al botón principal.

---

Este es un punto de partida funcional para construir las interfaces observadas en las imágenes adjuntas. Se pueden crear variantes modificando el contenido y la distribución en el HTML, así como los estilos.

---
