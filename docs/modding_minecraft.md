# Modding Minecraft con Forge

## Introducción
En esta guía, aprenderás cómo empezar a crear mods para Minecraft utilizando Forge, una de las herramientas más populares para la creación de mods en Minecraft.

## Requisitos
Para poder comenzar, necesitarás tener instalados los siguientes programas:
- **Java Development Kit (JDK)**: Necesario para compilar el código de tus mods.
- **Minecraft**: Por supuesto, necesitarás Minecraft para probar tus mods.
- **Forge**: El framework para crear mods.

## Instalación de Forge
1. **Descargar Forge**: Dirígete al sitio oficial de [Forge](https://files.minecraftforge.net/).
2. **Seleccionar la versión de Minecraft**: Elige la versión de Minecraft para la que deseas crear el mod.
3. **Instalar el cliente o el servidor**: Descarga e instala el cliente de Forge en tu Minecraft.

## Crear tu primer mod
### Paso 1: Configurar el entorno de desarrollo
Para crear mods, es recomendable utilizar un **IDE** como **IntelliJ IDEA** o **Eclipse**. A continuación, configuraremos un proyecto básico de Forge.

1. Descarga el archivo **MDK** (Mod Developer Kit) desde la página de Forge.
2. Extrae el archivo en una carpeta de tu elección.
3. Abre la terminal o línea de comandos en esa carpeta.
4. Ejecuta el siguiente comando para importar el proyecto a tu IDE (para IntelliJ IDEA):

   ```bash
   ./gradlew genEclipseRuns
