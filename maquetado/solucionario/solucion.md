# 📘 Ejercicios Resueltos de Maquetación Web HTML5 + CSS3 + JS

## Ejercicio 1: Blog personal

### 🧱 index.html

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Mi Blog</title>
    <link rel="stylesheet" href="estilos.css" />
  </head>
  <body>
    <header>
      <h1>Mi Blog</h1>
      <nav>
        <ul class="menu">
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Sección</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section class="intro">
        <h2>Bienvenido a nuestro Blog personal</h2>
        <p>Comparte ideas, experiencias y noticias con el mundo.</p>
        <a href="#" class="btn">Leer más</a>
      </section>
    </main>

    <footer>
      <p>&copy; 2025 Mi Blog. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
  </body>
</html>
```

### 🎨 estilos.css

```css
* {{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}}

body {{
  font-family: 'Segoe UI', sans-serif;
  background-color: #f0f0f0;
  color: #333;
}}

header {{
  background-color: #2c3e50;
  padding: 1rem 2rem;
  color: white;
}}

.menu {{
  display: flex;
  gap: 1rem;
  list-style: none;
}}

.menu li a {{
  color: white;
  text-decoration: none;
}}

.intro {{
  padding: 2rem;
  background-color: #ecf0f1;
  text-align: center;
}}

.btn {{
  display: inline-block;
  margin-top: 1rem;
  padding: 0.75rem 1.5rem;
  background-color: #3498db;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}}

.btn:hover {{
  background-color: #2980b9;
}}

footer {{
  background-color: #2c3e50;
  color: white;
  padding: 1rem;
  text-align: center;
}}
```

### 🧠 script.js

```javascript
document.addEventListener("DOMContentLoaded", () => {
  const btn = document.querySelector(".btn");
  if (btn) {
    btn.addEventListener("click", () => {
      alert("Gracias por interactuar con esta demo.");
    });
  }
});
```

---

## Ejercicio 2: Tienda online

### 🧱 index.html

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tienda Moderna</title>
    <link rel="stylesheet" href="estilos.css" />
  </head>
  <body>
    <header>
      <h1>Tienda Moderna</h1>
      <nav>
        <ul class="menu">
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Sección</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section class="intro">
        <h2>Bienvenido a nuestro Tienda online</h2>
        <p>Compra los mejores productos al mejor precio.</p>
        <a href="#" class="btn">Ver productos</a>
      </section>
    </main>

    <footer>
      <p>&copy; 2025 Tienda Moderna. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
  </body>
</html>
```

### 🎨 estilos.css

```css
* {{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}}

body {{
  font-family: 'Segoe UI', sans-serif;
  background-color: #f0f0f0;
  color: #333;
}}

header {{
  background-color: #2c3e50;
  padding: 1rem 2rem;
  color: white;
}}

.menu {{
  display: flex;
  gap: 1rem;
  list-style: none;
}}

.menu li a {{
  color: white;
  text-decoration: none;
}}

.intro {{
  padding: 2rem;
  background-color: #ecf0f1;
  text-align: center;
}}

.btn {{
  display: inline-block;
  margin-top: 1rem;
  padding: 0.75rem 1.5rem;
  background-color: #3498db;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}}

.btn:hover {{
  background-color: #2980b9;
}}

footer {{
  background-color: #2c3e50;
  color: white;
  padding: 1rem;
  text-align: center;
}}
```

### 🧠 script.js

```javascript
document.addEventListener("DOMContentLoaded", () => {
  const btn = document.querySelector(".btn");
  if (btn) {
    btn.addEventListener("click", () => {
      alert("Gracias por interactuar con esta demo.");
    });
  }
});
```

---

## Ejercicio 3: Landing page de producto

### 🧱 index.html

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Lanzamiento X</title>
    <link rel="stylesheet" href="estilos.css" />
  </head>
  <body>
    <header>
      <h1>Lanzamiento X</h1>
      <nav>
        <ul class="menu">
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Sección</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section class="intro">
        <h2>Bienvenido a nuestro Landing page de producto</h2>
        <p>Descubre el nuevo producto que revolucionará tu día a día.</p>
        <a href="#" class="btn">Conocer más</a>
      </section>
    </main>

    <footer>
      <p>&copy; 2025 Lanzamiento X. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
  </body>
</html>
```

### 🎨 estilos.css

```css
* {{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}}

body {{
  font-family: 'Segoe UI', sans-serif;
  background-color: #f0f0f0;
  color: #333;
}}

header {{
  background-color: #2c3e50;
  padding: 1rem 2rem;
  color: white;
}}

.menu {{
  display: flex;
  gap: 1rem;
  list-style: none;
}}

.menu li a {{
  color: white;
  text-decoration: none;
}}

.intro {{
  padding: 2rem;
  background-color: #ecf0f1;
  text-align: center;
}}

.btn {{
  display: inline-block;
  margin-top: 1rem;
  padding: 0.75rem 1.5rem;
  background-color: #3498db;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}}

.btn:hover {{
  background-color: #2980b9;
}}

footer {{
  background-color: #2c3e50;
  color: white;
  padding: 1rem;
  text-align: center;
}}
```

### 🧠 script.js

```javascript
document.addEventListener("DOMContentLoaded", () => {
  const btn = document.querySelector(".btn");
  if (btn) {
    btn.addEventListener("click", () => {
      alert("Gracias por interactuar con esta demo.");
    });
  }
});
```

---

## Ejercicio 4: Portafolio

### 🧱 index.html

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Portafolio Creativo</title>
    <link rel="stylesheet" href="estilos.css" />
  </head>
  <body>
    <header>
      <h1>Portafolio Creativo</h1>
      <nav>
        <ul class="menu">
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Sección</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section class="intro">
        <h2>Bienvenido a nuestro Portafolio</h2>
        <p>Muestra tus mejores trabajos de diseño y desarrollo.</p>
        <a href="#" class="btn">Ver trabajos</a>
      </section>
    </main>

    <footer>
      <p>&copy; 2025 Portafolio Creativo. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
  </body>
</html>
```

### 🎨 estilos.css

```css
* {{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}}

body {{
  font-family: 'Segoe UI', sans-serif;
  background-color: #f0f0f0;
  color: #333;
}}

header {{
  background-color: #2c3e50;
  padding: 1rem 2rem;
  color: white;
}}

.menu {{
  display: flex;
  gap: 1rem;
  list-style: none;
}}

.menu li a {{
  color: white;
  text-decoration: none;
}}

.intro {{
  padding: 2rem;
  background-color: #ecf0f1;
  text-align: center;
}}

.btn {{
  display: inline-block;
  margin-top: 1rem;
  padding: 0.75rem 1.5rem;
  background-color: #3498db;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}}

.btn:hover {{
  background-color: #2980b9;
}}

footer {{
  background-color: #2c3e50;
  color: white;
  padding: 1rem;
  text-align: center;
}}
```

### 🧠 script.js

```javascript
document.addEventListener("DOMContentLoaded", () => {
  const btn = document.querySelector(".btn");
  if (btn) {
    btn.addEventListener("click", () => {
      alert("Gracias por interactuar con esta demo.");
    });
  }
});
```

---

## Ejercicio 5: Sitio universitario

### 🧱 index.html

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Universidad Global</title>
    <link rel="stylesheet" href="estilos.css" />
  </head>
  <body>
    <header>
      <h1>Universidad Global</h1>
      <nav>
        <ul class="menu">
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Sección</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section class="intro">
        <h2>Bienvenido a nuestro Sitio universitario</h2>
        <p>Conoce nuestra oferta académica e inscríbete ahora.</p>
        <a href="#" class="btn">Ver carreras</a>
      </section>
    </main>

    <footer>
      <p>&copy; 2025 Universidad Global. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
  </body>
</html>
```

### 🎨 estilos.css

```css
* {{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}}

body {{
  font-family: 'Segoe UI', sans-serif;
  background-color: #f0f0f0;
  color: #333;
}}

header {{
  background-color: #2c3e50;
  padding: 1rem 2rem;
  color: white;
}}

.menu {{
  display: flex;
  gap: 1rem;
  list-style: none;
}}

.menu li a {{
  color: white;
  text-decoration: none;
}}

.intro {{
  padding: 2rem;
  background-color: #ecf0f1;
  text-align: center;
}}

.btn {{
  display: inline-block;
  margin-top: 1rem;
  padding: 0.75rem 1.5rem;
  background-color: #3498db;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}}

.btn:hover {{
  background-color: #2980b9;
}}

footer {{
  background-color: #2c3e50;
  color: white;
  padding: 1rem;
  text-align: center;
}}
```

### 🧠 script.js

```javascript
document.addEventListener("DOMContentLoaded", () => {
  const btn = document.querySelector(".btn");
  if (btn) {
    btn.addEventListener("click", () => {
      alert("Gracias por interactuar con esta demo.");
    });
  }
});
```

---

## Ejercicio 6: Web de restaurante

### 🧱 index.html

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sabor Colonial</title>
    <link rel="stylesheet" href="estilos.css" />
  </head>
  <body>
    <header>
      <h1>Sabor Colonial</h1>
      <nav>
        <ul class="menu">
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Sección</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section class="intro">
        <h2>Bienvenido a nuestro Web de restaurante</h2>
        <p>Explora nuestro menú y reserva tu mesa online.</p>
        <a href="#" class="btn">Ver menú</a>
      </section>
    </main>

    <footer>
      <p>&copy; 2025 Sabor Colonial. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
  </body>
</html>
```

### 🎨 estilos.css

```css
* {{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}}

body {{
  font-family: 'Segoe UI', sans-serif;
  background-color: #f0f0f0;
  color: #333;
}}

header {{
  background-color: #2c3e50;
  padding: 1rem 2rem;
  color: white;
}}

.menu {{
  display: flex;
  gap: 1rem;
  list-style: none;
}}

.menu li a {{
  color: white;
  text-decoration: none;
}}

.intro {{
  padding: 2rem;
  background-color: #ecf0f1;
  text-align: center;
}}

.btn {{
  display: inline-block;
  margin-top: 1rem;
  padding: 0.75rem 1.5rem;
  background-color: #3498db;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}}

.btn:hover {{
  background-color: #2980b9;
}}

footer {{
  background-color: #2c3e50;
  color: white;
  padding: 1rem;
  text-align: center;
}}
```

### 🧠 script.js

```javascript
document.addEventListener("DOMContentLoaded", () => {
  const btn = document.querySelector(".btn");
  if (btn) {
    btn.addEventListener("click", () => {
      alert("Gracias por interactuar con esta demo.");
    });
  }
});
```

---

## Ejercicio 7: Agencia de marketing

### 🧱 index.html

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Impulsa Agency</title>
    <link rel="stylesheet" href="estilos.css" />
  </head>
  <body>
    <header>
      <h1>Impulsa Agency</h1>
      <nav>
        <ul class="menu">
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Sección</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section class="intro">
        <h2>Bienvenido a nuestro Agencia de marketing</h2>
        <p>Transformamos ideas en resultados digitales.</p>
        <a href="#" class="btn">Solicitar demo</a>
      </section>
    </main>

    <footer>
      <p>&copy; 2025 Impulsa Agency. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
  </body>
</html>
```

### 🎨 estilos.css

```css
* {{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}}

body {{
  font-family: 'Segoe UI', sans-serif;
  background-color: #f0f0f0;
  color: #333;
}}

header {{
  background-color: #2c3e50;
  padding: 1rem 2rem;
  color: white;
}}

.menu {{
  display: flex;
  gap: 1rem;
  list-style: none;
}}

.menu li a {{
  color: white;
  text-decoration: none;
}}

.intro {{
  padding: 2rem;
  background-color: #ecf0f1;
  text-align: center;
}}

.btn {{
  display: inline-block;
  margin-top: 1rem;
  padding: 0.75rem 1.5rem;
  background-color: #3498db;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}}

.btn:hover {{
  background-color: #2980b9;
}}

footer {{
  background-color: #2c3e50;
  color: white;
  padding: 1rem;
  text-align: center;
}}
```

### 🧠 script.js

```javascript
document.addEventListener("DOMContentLoaded", () => {
  const btn = document.querySelector(".btn");
  if (btn) {
    btn.addEventListener("click", () => {
      alert("Gracias por interactuar con esta demo.");
    });
  }
});
```

---

## Ejercicio 8: Página de app

### 🧱 index.html

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>MiApp Móvil</title>
    <link rel="stylesheet" href="estilos.css" />
  </head>
  <body>
    <header>
      <h1>MiApp Móvil</h1>
      <nav>
        <ul class="menu">
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Sección</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section class="intro">
        <h2>Bienvenido a nuestro Página de app</h2>
        <p>Tu app favorita para organizar tu día.</p>
        <a href="#" class="btn">Descargar ahora</a>
      </section>
    </main>

    <footer>
      <p>&copy; 2025 MiApp Móvil. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
  </body>
</html>
```

### 🎨 estilos.css

```css
* {{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}}

body {{
  font-family: 'Segoe UI', sans-serif;
  background-color: #f0f0f0;
  color: #333;
}}

header {{
  background-color: #2c3e50;
  padding: 1rem 2rem;
  color: white;
}}

.menu {{
  display: flex;
  gap: 1rem;
  list-style: none;
}}

.menu li a {{
  color: white;
  text-decoration: none;
}}

.intro {{
  padding: 2rem;
  background-color: #ecf0f1;
  text-align: center;
}}

.btn {{
  display: inline-block;
  margin-top: 1rem;
  padding: 0.75rem 1.5rem;
  background-color: #3498db;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}}

.btn:hover {{
  background-color: #2980b9;
}}

footer {{
  background-color: #2c3e50;
  color: white;
  padding: 1rem;
  text-align: center;
}}
```

### 🧠 script.js

```javascript
document.addEventListener("DOMContentLoaded", () => {
  const btn = document.querySelector(".btn");
  if (btn) {
    btn.addEventListener("click", () => {
      alert("Gracias por interactuar con esta demo.");
    });
  }
});
```

---

## Ejercicio 9: Noticias tecnológicas

### 🧱 index.html

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>TechNow</title>
    <link rel="stylesheet" href="estilos.css" />
  </head>
  <body>
    <header>
      <h1>TechNow</h1>
      <nav>
        <ul class="menu">
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Sección</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section class="intro">
        <h2>Bienvenido a nuestro Noticias tecnológicas</h2>
        <p>
          Las últimas noticias del mundo tecnológico, actualizadas a diario.
        </p>
        <a href="#" class="btn">Leer noticias</a>
      </section>
    </main>

    <footer>
      <p>&copy; 2025 TechNow. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
  </body>
</html>
```

### 🎨 estilos.css

```css
* {{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}}

body {{
  font-family: 'Segoe UI', sans-serif;
  background-color: #f0f0f0;
  color: #333;
}}

header {{
  background-color: #2c3e50;
  padding: 1rem 2rem;
  color: white;
}}

.menu {{
  display: flex;
  gap: 1rem;
  list-style: none;
}}

.menu li a {{
  color: white;
  text-decoration: none;
}}

.intro {{
  padding: 2rem;
  background-color: #ecf0f1;
  text-align: center;
}}

.btn {{
  display: inline-block;
  margin-top: 1rem;
  padding: 0.75rem 1.5rem;
  background-color: #3498db;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}}

.btn:hover {{
  background-color: #2980b9;
}}

footer {{
  background-color: #2c3e50;
  color: white;
  padding: 1rem;
  text-align: center;
}}
```

### 🧠 script.js

```javascript
document.addEventListener("DOMContentLoaded", () => {
  const btn = document.querySelector(".btn");
  if (btn) {
    btn.addEventListener("click", () => {
      alert("Gracias por interactuar con esta demo.");
    });
  }
});
```

---

## Ejercicio 10: Formulario de evento

### 🧱 index.html

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Evento Pro 2025</title>
    <link rel="stylesheet" href="estilos.css" />
  </head>
  <body>
    <header>
      <h1>Evento Pro 2025</h1>
      <nav>
        <ul class="menu">
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Sección</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>
      </nav>
    </header>

    <main>
      <section class="intro">
        <h2>Bienvenido a nuestro Formulario de evento</h2>
        <p>Inscríbete al evento del año en tecnología.</p>
        <a href="#" class="btn">Registrarme</a>
      </section>
    </main>

    <footer>
      <p>&copy; 2025 Evento Pro 2025. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
  </body>
</html>
```

### 🎨 estilos.css

```css
* {{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}}

body {{
  font-family: 'Segoe UI', sans-serif;
  background-color: #f0f0f0;
  color: #333;
}}

header {{
  background-color: #2c3e50;
  padding: 1rem 2rem;
  color: white;
}}

.menu {{
  display: flex;
  gap: 1rem;
  list-style: none;
}}

.menu li a {{
  color: white;
  text-decoration: none;
}}

.intro {{
  padding: 2rem;
  background-color: #ecf0f1;
  text-align: center;
}}

.btn {{
  display: inline-block;
  margin-top: 1rem;
  padding: 0.75rem 1.5rem;
  background-color: #3498db;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}}

.btn:hover {{
  background-color: #2980b9;
}}

footer {{
  background-color: #2c3e50;
  color: white;
  padding: 1rem;
  text-align: center;
}}
```

### 🧠 script.js

```javascript
document.addEventListener("DOMContentLoaded", () => {
  const btn = document.querySelector(".btn");
  if (btn) {
    btn.addEventListener("click", () => {
      alert("Gracias por interactuar con esta demo.");
    });
  }
});
```

---
