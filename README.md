
# Proyecto HTML + CSS - KARIO Media

Este proyecto consiste en un sistema de autenticación y visualización de indicadores, desarrollado con HTML y CSS. Está compuesto por varias páginas, de las cuales tres son la estructura base del sitio: una pantalla de inicio de sesión, una página de bienvenida tras el login y un panel principal donde se visualizan indicadores de desempeño.

| Tabla de contenidos |
|--------------------|
| [¿Cómo ejecutar este archivo?](#Ejecucion) |
| [Funcionamiento del programa](#Funcionamiento) |

<a name="Ejecucion"></a>

## ¿Cómo ejecutar este archivo?

Puede visualizar las páginas del proyecto de las siguientes maneras:

1. Accediendo directamente a través del siguiente link:

    [https://sxntiagojp.github.io/Proyecto_HTML_S1_SalamancaDante-JaimesSantiago/](https://sxntiagojp.github.io/Proyecto_HTML_S1_SalamancaDante-JaimesSantiago/)

2. Clonando el repositorio desde una terminal:
   ```git clone https://github.com/SxntiagoJP/Proyecto_HTML_S1_SalamancaDante-JaimesSantiago```
   Luego puede acceder al archivo index.html y abrirlo con el navegador web de su preferencia.

<a name="Funcionamiento"></a>

## Funcionamiento del programa

El proyecto está estructurado en tres componentes principales, de los cuales derivan todos los demás:

### 1. Página de login (`index.html`)

Es la página principal del sistema, donde los usuarios ingresan sus credenciales para acceder al panel. Utiliza formularios HTML con campos para nombre de usuario y contraseña. El diseño es simple pero funcional, centrado y con estilos personalizados para resaltar la marca KARIO Media.

### 2. Página de bienvenida (`welcome.html`)

Tras un inicio de sesión exitoso, esta página da la bienvenida al usuario mostrando su nombre y rol en el sistema. Es una página estática que refuerza la identidad del usuario y puede servir como transición hacia el panel principal.

### 3. Panel de indicadores (`home.html`)

Esta es la página más completa del sistema. Permite visualizar un conjunto de indicadores asociados a diferentes áreas de trabajo. Se estructura en forma de tabla con columnas como:

- Nombre del indicador
- Descripción
- Categoría
- Fechas de inicio y finalización
- Fórmula
- Frecuencia
- Porcentaje de cumplimiento
- Área correspondiente

El diseño permite al usuario interactuar con botones para añadir, actualizar o eliminar indicadores. Aunque no incluye scripts para lógica dinámica, la estructura está preparada para futuras funcionalidades.
