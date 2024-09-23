# 🎬 Netflix Clone

Este repositorio contiene un clon de la página de inicio de Netflix, desarrollado con **Astro** para el front-end y **Spring Boot** para el back-end. El proyecto está diseñado para practicar habilidades en desarrollo web full-stack y la integración de tecnologías front-end y back-end.

## 📊 Descripción

El clon de Netflix incluye una barra de navegación, un banner de presentación de una película destacada, y varias filas de películas organizadas por categorías. Las categorías y los detalles de las películas están simulados mediante datos ficticios.

El objetivo del proyecto es construir un clon simple de la interfaz de usuario de Netflix, conectando el front-end desarrollado con **Astro** al back-end de **Spring Boot** para manejar las API y los datos.

## ✅ Requisitos

- Desarrollar el front-end utilizando Astro.
- Integrar el back-end con Spring Boot para servir los datos.
- Mostrar una página de inicio que incluya una barra de navegación, un banner, y filas de películas.

## 🔩 Funcionamiento

### 🚀 Front-end (Astro)

El front-end está desarrollado con Astro, utilizando datos ficticios para simular películas y categorías de Netflix. Incluye componentes reutilizables como botones e íconos.

### 💻 Back-end (Spring Boot)

El back-end está desarrollado con Spring Boot, encargándose de proporcionar las API REST que el front-end consume para obtener datos de películas y categorías. Las APIs responden con datos simulados en formato JSON.

## 💻 Ejecución del proyecto

1. Clona este repositorio:

   ```sh
   git clone https://github.com/tu-usuario/netflix-clone.git
   ```

2. Dirígete a la carpeta del proyecto para el **front-end** y ejecuta los siguientes comandos para instalar las dependencias y ejecutar el servidor de desarrollo:

   ```sh
   cd front-end
   pnpm install
   pnpm dev
   ```

3. Para el **back-end**, asegúrate de tener **Java** y **Maven** instalados, luego dirígete a la carpeta del back-end y ejecuta:

   ```sh
   cd back-end
   mvn spring-boot:run
   ```

4. Abre el navegador en `http://localhost:3000` para ver el front-end en acción.

## 🧠 Funcionalidades

- Barra de navegación simple con un logotipo de Netflix y enlaces.
- Un banner principal que muestra la película destacada.
- Varias categorías de películas con filas deslizables de imágenes.

## 🚀 Tecnologías utilizadas

- **Astro**: Para el desarrollo del front-end.
- **Spring Boot**: Para el desarrollo del back-end y manejo de APIs.
- **Tailwind CSS** (opcional): Para el estilo del front-end (puedes eliminarlo si decides no usar estilos).
- **Java** y **Maven**: Para el desarrollo y gestión del back-end.
- **Node.js** y **pnpm**: Para la gestión de paquetes en el front-end.

## 📂 Estructura del proyecto

```bash
netflix-clone/
├── front-end/   # Proyecto Astro para el front-end
├── back-end/    # Proyecto Spring Boot para el back-end
```

## 🥸 Autor

Created with ❤ by Diego Villagran

<a href="https://linkedin.com/in/dvillagrans" target="_blank">
<img src="https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" style="margin-bottom: 5px;" />
</a>
<a href="https://github.com/dvillagrans" target="_blank">
<img src="https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white" alt="github" style="margin-bottom: 5px;" />
</a>
