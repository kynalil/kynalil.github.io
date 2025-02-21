# Taller Desarrollo Web

## 1. ¿Qué es HTML y cuál es su función en la web?

HTML (HyperText Markup Language) es el lenguaje que usan los navegadores para mostrar las páginas web. Se encarga de organizar el contenido como textos, imágenes, enlaces o botones para que el navegador pueda presentarlo de forma ordenada. Sin embargo, HTML solo proporciona la estructura; para el diseño y la interactividad se utilizan CSS y JavaScript.

---

## 2. ¿Qué es una etiqueta HTML y menciona las etiquetas más comunes?

Una etiqueta HTML es una instrucción que le dice al navegador cómo mostrar el contenido. Se escriben entre `< >` y suelen tener una etiqueta de apertura y otra de cierre.

Ejemplo:
```html
<p>Este es un párrafo</p>
```

**Etiquetas comunes:**
- `<html>`: Contenedor principal de la página.
- `<head>`: Contiene metadatos y enlaces a estilos o scripts.
- `<title>`: Define el título de la pestaña del navegador.
- `<body>`: Contiene todo el contenido visible.
- `<h1>`, `<h2>`, `<h3>`: Encabezados jerárquicos.
- `<p>`: Define un párrafo.
- `<a>`: Crea enlaces.
- `<img>`: Inserta imágenes.
- `<ul>` y `<ol>`: Listas no ordenadas y ordenadas.
- `<li>`: Elemento de lista.

---

## 3. ¿Qué es un atributo de una etiqueta HTML y menciona los más comunes?

Los atributos proporcionan información adicional a las etiquetas.

**Atributos comunes:**
- `href`: Define la URL de un enlace.
- `src`: Especifica la fuente de una imagen.
- `alt`: Texto alternativo para imágenes.
- `class`: Asigna una clase para estilos.
- `id`: Identificador único.
- `style`: Aplica estilos en línea.
- `target`: Controla dónde se abre un enlace.
- `type`: Define el tipo de un input o botón.

Ejemplo:
```html
<a href="https://www.example.com" target="_blank">Visitar página</a>
```

---

## 4. ¿Qué es CSS y cómo se utiliza para el diseño web?

CSS (Cascading Style Sheets) permite estilizar páginas web, controlando colores, fuentes, márgenes y más. Se puede aplicar de tres maneras:
- **Inline**: Dentro de la etiqueta (`style="color: red;"`).
- **Interno**: Dentro de la etiqueta `<style>` en el `<head>`.
- **Externo**: En un archivo `.css` enlazado con `<link>`.

---

## 5. ¿Qué es una propiedad en CSS y menciona las propiedades más comunes?

Una propiedad en CSS define un aspecto del diseño.

**Propiedades comunes:**
- `color`: Color del texto.
- `background-color`: Color de fondo.
- `font-size`: Tamaño del texto.
- `margin`: Espacio externo.
- `padding`: Espacio interno.

Ejemplo:
```css
p {
  color: blue;
  font-size: 16px;
}
```

---

## 6. ¿Qué es un selector en CSS y cuáles tipos existen?

Un selector define a qué elementos se aplicará un estilo.

**Tipos de selectores:**
- **Tipo**: Aplica a todas las etiquetas (`p {}` para todos los `<p>`).
- **Clase**: Aplica a elementos con una clase (`.mi-clase {}`).
- **ID**: Aplica a un único elemento (`#mi-id {}`).
- **Universal**: Aplica a todos los elementos (`* {}`).

---

## 7. ¿Qué es JavaScript y cómo añade interactividad a las páginas web?

JavaScript es un lenguaje de programación que permite crear interactividad en las páginas web. Gracias a él, se pueden realizar acciones como validar formularios, cambiar el contenido dinámicamente y responder a eventos de usuario.

---

## 8. ¿Cuáles son los tipos de datos primitivos en JavaScript?

Los tipos de datos primitivos en JavaScript son:
- `Number`: Números (`7`, `3.14`).
- `String`: Cadenas de texto (`"Hola"`).
- `Boolean`: `true` o `false`.
- `Undefined`: Variable sin valor.
- `Null`: Ausencia de valor.
- `Symbol`: Valores únicos.
- `BigInt`: Números grandes.

---

## 9. ¿Cómo funcionan las estructuras de control de flujo en JavaScript?

Las estructuras de control permiten tomar decisiones y repetir acciones.

**Condicionales:**
```javascript
if (temperatura > 30) {
  console.log("Hace calor");
} else {
  console.log("Hace frío");
}
```

**Switch:**
```javascript
switch (dia) {
  case "Lunes":
    console.log("Inicio de semana");
    break;
  default:
    console.log("Otro día");
}
```

**Bucles:**
```javascript
for (let i = 0; i < 3; i++) {
  console.log("Iteración " + i);
}
```

---

## 10. ¿Por qué es importante usar nombres significativos para variables y métodos?

Usar nombres claros mejora la legibilidad y mantenimiento del código.

Ejemplo:
```javascript
let totalPrecio = 350; // Claro
let x = 350; // Confuso
```

---

## 11. ¿Qué es una variable de entorno y por qué es importante?

Una variable de entorno es un valor configurado fuera del código, como claves API o configuraciones.

**Importancia:**
- **Seguridad**: Mantiene datos sensibles fuera del código.
- **Flexibilidad**: Permite cambios sin modificar el código.
- **Portabilidad**: Facilita el uso en distintos entornos.

---

## 12. ¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas?

Las DevTools permiten inspeccionar y depurar páginas web.

**Acceso:**
- Clic derecho → "Inspeccionar".
- Atajo: `Ctrl + Shift + I` (Windows) o `Cmd + Option + I` (Mac).

---

## 13. ¿Qué se puede hacer en el panel "Elements" de DevTools?

- Ver y editar HTML.
- Modificar CSS en tiempo real.
- Añadir/eliminar clases.

---

## 14. ¿Cómo se usa el panel "Console" y para qué es útil?

La consola muestra errores, advertencias y permite ejecutar código JavaScript.

**Usos:**
- Ver errores.
- Probar código.
- Depuración con `console.log()`.

---

## 15. ¿Qué información se obtiene del panel "Network" y por qué es importante?

- **Solicitudes HTTP**: Recursos cargados.
- **Tiempo de carga**: Optimización del rendimiento.
- **Códigos de estado**: Como `200 OK`, `404 Not Found`.
- **Contenido de respuesta**: Datos recibidos de APIs.
