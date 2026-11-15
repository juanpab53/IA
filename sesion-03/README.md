# Sesión 03 - Pixel Perfect Match

## Descripción

Esta sesión consiste en la creación de una plataforma web tipo marketplace para contratar desarrolladores de software, llamada "Pixel Perfect Match".

El proyecto fue generado con Lovable a partir de un prompt que definía una landing page moderna, con experiencia de usuario enfocada en empresas que buscan talento tecnológico y en desarrolladores que desean mostrar su perfil profesional.

## Proyecto principal

La implementación funcional se encuentra en la carpeta:

- `sesion-03/ejercicio/`

Dentro de esa carpeta se desarrolla una aplicación React con arquitectura moderna basada en:

- Vite
- React
- TypeScript
- Tailwind CSS
- shadcn/ui
- TanStack Router
- i18n para español e inglés

## Objetivo del ejercicio

Construir una plataforma que permita:

- explorar desarrolladores por especialidad,
- comparar perfiles,
- ver información detallada de cada profesional,
- filtrar por skills y categorías,
- guardar favoritos,
- consultar planes de precios,
- y contactar con la empresa a través de un formulario.

## Funcionalidades principales

La aplicación incluye las siguientes secciones y capacidades:

- Hero section animada con estilo visual moderno
- Catálogo de developers con filtros por especialidad
- Perfiles individuales con experiencia, proyectos y rating
- Comparación de perfiles lado a lado
- Páginas para empresas y desarrolladores
- Sección “How it Works” con el flujo del servicio
- Página de pricing con planes
- Formulario de contacto
- Sistema de favoritos
- Carrusel de desarrolladores destacados
- Soporte de internacionalización (español/inglés)
- Diseño responsive y dark theme

## Estructura del proyecto

Algunas carpetas relevantes del proyecto son:

- `src/routes/`: páginas y rutas de la aplicación
- `src/components/`: componentes reutilizables de interfaz
- `src/data/`: información de desarrolladores, especialidades y proyectos
- `src/i18n/`: archivos de traducción en inglés y español
- `src/lib/`: utilidades y funciones auxiliares
- `src/styles.css`: estilos globales de la aplicación

## Archivo de prompt

En la raíz de la sesión se encuentra el archivo:

- `Prompt.md`

Este documento contiene la instrucción exacta que se utilizó para generar la plataforma con Lovable.

## Cómo ejecutar el proyecto

Desde la carpeta `sesion-03/ejercicio`, usa los siguientes comandos:

```bash
npm install
npm run dev
```

Esto levantará la aplicación localmente en el puerto por defecto de Vite.

Para construir la versión de producción:

```bash
npm run build
```

## Conclusión

La sesión 03 corresponde a un ejercicio de prototipo web orientado a una aplicación realista de contratación de talento tecnológico. El resultado refleja una interfaz moderna, un catálogo de perfiles, filtros, comparaciones y una experiencia de compra/contratación enfocada en el mercado de desarrolladores.

Este proyecto sirve como ejemplo de cómo una herramienta de IA puede transformar una idea de negocio en un MVP visual y funcional con arquitectura moderna de front-end.
