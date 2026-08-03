
# 🐾 RefugioPet - Frontend con React

## Descripción

RefugioPet es una aplicación web desarrollada con React que busca facilitar el proceso de adopción de mascotas. La plataforma permite a los usuarios conocer información sobre la adopción, registrarse, iniciar sesión y acceder a las diferentes funcionalidades del sistema.

---

## Tecnologías utilizadas

- React
- Vite
- React Router DOM
- HTML5
- CSS3
- JavaScript

---

## Cambios realizados

Durante el desarrollo del proyecto se realizaron las siguientes modificaciones:

- Se migró el frontend de HTML y CSS a React.
- Se creó el proyecto utilizando Vite.
- Se instaló y configuró React Router DOM para la navegación entre páginas.
- Se organizaron las páginas dentro de la carpeta `pages`.
- Se configuraron las rutas principales:
  - Inicio
  - Iniciar sesión
  - Registro
- Se migró la página principal (`inicio.html`) a un componente React (`inicio.jsx`).
- Se importaron correctamente los archivos CSS en cada componente.
- Se reorganizaron las imágenes dentro de la carpeta `src/assets`.
- Se configuró la navegación mediante `Link` de React Router.
- Se corrigieron errores relacionados con las importaciones y las exportaciones de componentes.
- Se preparó la estructura para continuar con el desarrollo del proyecto.

---

## Estructura del proyecto

```
src/
│
├── assets/
│   ├── logo.png
│   └── carrusel/
│
├── pages/
│   ├── inicio.jsx
│   ├── iniciosesion.jsx
│   └── registrar.jsx
│
├── App.jsx
├── main.jsx
├── ini.css
├── inisesion.css
└── registrar.css
```

---

## Instalación

Clonar el repositorio

```bash
git clone https://github.com/alejandrovelasco6831/proyecto-react.git
```

Entrar al proyecto

```bash
cd proyecto-react
```

Instalar dependencias

```bash
npm install
```

Ejecutar el proyecto

```bash
npm run dev
```

---

## Funcionalidades actuales

- Página de inicio.
- Navegación mediante React Router.
- Página de inicio de sesión.
- Página de registro.
- Organización de componentes.
- Integración de estilos CSS.

---

## Autor

**José Alejandro Velasco Saavedra**

Tecnólogo en Análisis y Desarrollo de Software (ADSO) - SENA
