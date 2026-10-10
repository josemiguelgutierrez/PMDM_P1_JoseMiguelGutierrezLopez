# Recetas rápidas

Práctica 1 de **Programación Multimedia y Dispositivos Móviles** (2.º DAM, MEDAC) · José Miguel Gutiérrez López

## Descripción

**Recetas rápidas** es una app Android pensada para estudiantes que tienen poco tiempo para cocinar. Ofrece recetas que se preparan en menos de 30 minutos, con pocos ingredientes y pasos cortos.

En esta práctica no se programa la funcionalidad completa: el objetivo es analizar y especificar la app, preparar el entorno de desarrollo y dejar la pantalla principal montada con todos los recursos (textos, imágenes, colores, estilos e icono) bien organizados en `res/values` y `res/drawable`.

## Capturas

**Móvil (español e inglés)**

<img width="351" height="781" alt="appEspañol" src="https://github.com/user-attachments/assets/b4897c6a-f833-4dd0-8b63-9283fb10d791" />

<img width="350" height="779" alt="appInglés" src="https://github.com/user-attachments/assets/44f4a3a4-54ee-475c-a829-74d5fe884007" />


**Tablet**

<img width="650" height="823" alt="ejecuciónEnTablet" src="https://github.com/user-attachments/assets/561021f5-849d-4ad2-aac2-ce732fe2d1e7" />


**Icono propio en el lanzador**

<img width="171" height="162" alt="iconoEnLanzador" src="https://github.com/user-attachments/assets/a2586915-3bbd-4341-8737-7c757fdfe494" />


## Qué se ha hecho

- **Proyecto:** Android Studio, plantilla *Empty Views Activity*, Java con vistas XML, API mínima 24 (Android 7.0).
- **Dos dispositivos virtuales:** un móvil y una tablet, con ejecución probada en ambos.
- **Textos e idiomas:** todos los textos en `strings.xml` (con un `string-array` y un texto con parámetro) y traducción completa al inglés en `values-en`.
- **Colores, estilos y tema:** paleta propia con nombres por función, estilos reutilizables y tema personalizado. Medidas en `dp` y textos en `sp`.
- **Imágenes e icono:** una imagen vectorial, una foto de mapa de bits y un icono adaptativo propio aplicado en el Manifest.

## Cómo ejecutarla

1. Clona el repositorio:
   ```
   git clone https://github.com/TU_USUARIO/PMDM_P1_JoseMiguelGutierrezLopez.git
   ```
2. Abre la carpeta del proyecto con una versión reciente de **Android Studio** (el proyecto usa un plugin de Gradle actual).
3. Espera a que termine la sincronización de Gradle.
4. Elige un emulador (API 24 o superior) o un móvil físico con depuración USB.
5. Pulsa **Run ▶** (Mayús+F10).

Para ver la traducción, cambia el idioma del dispositivo a inglés en *Ajustes → Sistema → Idiomas*.

## Memoria

Toda la documentación (análisis del desarrollo móvil, especificación de la app, entorno de desarrollo, recursos y conclusión personal) está en la memoria: [`docs/Memoria.pdf`](docs/Memoria.pdf).
