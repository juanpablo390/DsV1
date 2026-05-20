## ❔ "Por qué"

Moodle suele tener una interfaz monótona que puede afectar la retención del estudiante. Este proyecto fue creado para incrustarse o funcionar en paralelo con la academia, ofreciendo a los alumnos tarjetas interactivas, animaciones de estado fluido y un modo oscuro que facilita las sesiones de estudio nocturnas.

## 🛠️ Cómo usar el Filtro de Secciones por URL

El proyecto incluye una funcionalidad que permite visualizar una **única sección a la vez**.

Para filtrar, añade el parámetro `?seccion=` seguido del nombre de la sección al final de la URL:

* **Sintaxis:** `index.html?seccion=nombre_de_la_seccion`
* **Comportamiento:** Al usar el filtro, la cabecera desaparece y el contenido se ajusta para enfocar solo el bloque seleccionado.

---

## 📊 Secciones Disponibles

A continuación, se listan los IDs que puedes utilizar en la URL. 
> **Nota:** Por configuración del script, los IDs deben escribirse en **minúsculas**.

| ID de Sección | Contenido de la Sección |
| :--- | :--- |
| `cabecera` | Clase y titulo. |
| `bienvenida` | Introducción y analogía del "cerebro". |
| `definicion` | Concepto de "La Caja Mágica" y memoria. |
| `componentes` | Nombre, Valor, Tipo de dato y Alcance. |
| `tipos` | Explicación de Números, Texto y Booleanos. |
| `makecode` | Tutorial paso a paso en el editor de bloques. |
| `manipulacion` | Lógica de operadores y cambio de valores. |
| `practica` | Reto guiado: El Contador de Clics. |
| `final` | Resumen, reflexión y cierre. |

### Ejemplos rápidos:
* Para ver la práctica: `tu-url.com/?seccion=practica`
* Para ver los tipos de datos: `tu-url.com/?seccion=tipos`

---

## 🎨 Características del Proyecto

* **Diseño:** Construido con **Tailwind CSS** y efectos de *Glassmorphism*.
* **Modo Oscuro:** Incluye un toggle que guarda la preferencia del usuario en el navegador.
* **Responsivo:** Optimizado para pantallas de móviles, tablets y PCs.
* **Interactivo:** Uso de `URLSearchParams` para manipulación del DOM en tiempo real.

---

## 📂 Estructura del Código
El proyecto utiliza una estructura limpia donde:
1.  **HTML/Tailwind:** Define la jerarquía visual.
2.  **JavaScript:** Gestiona el cambio de tema y el filtrado por URL.
3.  **CSS Personalizado:** Define los degradados y animaciones de las tarjetas.
