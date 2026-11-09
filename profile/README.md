<p align="center">
  <a href="https://orionis-framework.com/">
    <img src="https://orionis-framework.com/favicon.svg" alt="Orionis Framework" width="140" />
  </a>
</p>

<h1 align="center">Orionis Framework</h1>

<h3 align="center">Menos ensamblar. Más construir.</h3>

<p align="center">
  Python asíncrono para conectar cada parte de tu aplicación.
  <br />
  <strong>HTTP &middot; Tiempo real &middot; Datos &middot; Automatización &middot; MCP</strong>
</p>

<p align="center">
  <a href="https://pypi.org/project/orionis/">
    <img src="https://img.shields.io/pypi/v/orionis?style=for-the-badge&amp;color=007f8b" alt="Versión de Orionis en PyPI" />
  </a>
  <a href="https://www.python.org/downloads/">
    <img src="https://img.shields.io/badge/Python-3.14%2B-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" alt="Python 3.14 o superior" />
  </a>
  <a href="https://github.com/orionis-framework/framework">
    <img src="https://img.shields.io/badge/HTTP-ASGI%20%7C%20RSGI-7C3AED?style=for-the-badge" alt="HTTP con ASGI y RSGI" />
  </a>
  <a href="https://github.com/orionis-framework/framework/blob/1.x/LICENCE">
    <img src="https://img.shields.io/badge/Licencia_del_n%C3%BAcleo-MIT-16803D?style=for-the-badge" alt="Núcleo bajo licencia MIT" />
  </a>
</p>

<p align="center">
  <a href="https://docs.orionis-framework.com/"><strong>Documentación</strong></a>
  &nbsp;&bull;&nbsp;
  <a href="https://orionis-framework.com/"><strong>Sitio web</strong></a>
  &nbsp;&bull;&nbsp;
  <a href="https://github.com/orionis-framework/framework"><strong>Código fuente</strong></a>
  &nbsp;&bull;&nbsp;
  <a href="https://github.com/orgs/orionis-framework/discussions"><strong>Comunidad</strong></a>
</p>

---

## ✨ Tu aplicación es más que sus endpoints

Una aplicación no termina en una ruta HTTP. También necesita datos, identidad,
archivos, trabajo en segundo plano y una forma clara de organizar su código.

**Orionis reúne esas piezas en un framework Python diseñado alrededor de
`async/await`, contratos explícitos y servicios integrados.**

Empieza por una API, una aplicación web o un servidor MCP. Comparte una misma
base de servicios y extiéndela con las piezas que necesites.

> **Tu lógica de negocio en el centro. Una arquitectura que conecta el resto.**

## 🧩 Una base común para cada capa

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🌐 HTTP y tiempo real</h3>
      <p>Rutas, controladores y middleware con soporte ASGI y RSGI.
      WebSockets y eventos del servidor para experiencias conectadas.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🏗️ Arquitectura extensible</h3>
      <p>Inyección de dependencias, servicios por contexto,
      proveedores y facades para separar responsabilidades.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🗃️ Datos con una API expresiva</h3>
      <p>ORM asíncrono, modelos, relaciones y consultas fluidas.
      Migraciones, transacciones y herramientas para preparar datos.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🔐 Identidad y permisos</h3>
      <p>Autenticación con sesiones y tokens de API.
      Roles, permisos y políticas para definir quién puede hacer qué.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚙️ Trabajo fuera de la petición</h3>
      <p>Colas con base de datos o Redis, procesamiento con
      reintentos y programación de comandos recurrentes.</p>
    </td>
    <td width="50%" valign="top">
      <h3>☁️ Archivos, aquí o en la nube</h3>
      <p>Una API de almacenamiento para archivos locales,
      Amazon S3, Azure Blob Storage y Google Cloud Storage.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 Servidores MCP</h3>
      <p>Expón herramientas, recursos y prompts a clientes de IA
      mediante Model Context Protocol, con HTTP y STDIO.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🛠️ Herramientas para desarrollar</h3>
      <p>Reactor CLI, generadores de código y pruebas asíncronas
      con acceso a los servicios de tu aplicación.</p>
    </td>
  </tr>
</table>

**Y las piezas del día a día:** caché, correo, validación tipada, sesiones,
plantillas Jinja2, traducciones, registros y manejo de excepciones.

Consulta en la documentación la configuración y las dependencias opcionales
de cada integración.

## 🚀 De la idea a tu primera aplicación

Prepara [uv](https://docs.astral.sh/uv/getting-started/installation/) y
[Git](https://git-scm.com/downloads). Orionis utiliza **Python 3.14 o superior**.

Para crear una API con la plantilla `slim_api`:

```bash
uvx --python 3.14 --from orionis-installer orionis new mi-api --stack slim_api
```

Completa el asistente y, cuando termine correctamente, inicia el servidor
de desarrollo desde la carpeta creada:

```bash
cd mi-api
uv run python -B reactor serve
```

Abre la dirección que muestre la consola.

**¿Otro tipo de aplicación?** Ejecuta el instalador sin `--stack` para elegir
una de las plantillas disponibles.

[Consulta la guía de instalación →](https://docs.orionis-framework.com/en/getting-started/installation/)

## 🪐 Explora el ecosistema

| Proyecto | Qué encontrarás |
| :--- | :--- |
| [**Framework**](https://github.com/orionis-framework/framework) | El núcleo de Orionis y sus componentes. |
| [**Skeleton**](https://github.com/orionis-framework/skeleton) | Las bases de proyecto para crear aplicaciones. |
| [**Installer**](https://github.com/orionis-framework/installer) | El asistente para preparar una nueva aplicación. |
| [**Docs**](https://github.com/orionis-framework/docs) | Las guías y el sitio de documentación. |
| [**Web**](https://github.com/orionis-framework/web) | El sitio público del proyecto. |

[Ver todos los repositorios →](https://github.com/orgs/orionis-framework/repositories)

## 🤝 La siguiente mejora puede empezar contigo

Prueba Orionis, comparte lo que construyes y ayúdanos a mejorar la experiencia
de desarrollar con Python.

**¿Encontraste un problema?** Abre un
[issue](https://github.com/orionis-framework/framework/issues)
con los pasos para reproducirlo y las versiones utilizadas.

**¿Tienes una pregunta o una propuesta?** Conversemos en
[Discussions](https://github.com/orgs/orionis-framework/discussions).

Las contribuciones de código, documentación, ejemplos y pruebas son bienvenidas.
Para cambios amplios, comparte primero la propuesta.

---

<p align="center">
  <strong>Una idea merece convertirse en una aplicación.</strong>
  <br />
  Construye la tuya con Orionis.
</p>

<p align="center">
  <a href="https://github.com/orionis-framework/framework">⭐ Apoya el proyecto con una estrella</a>
  &nbsp;&bull;&nbsp;
  <a href="https://github.com/sponsors/rmunate">💜 Patrocina su desarrollo</a>
</p>

<p align="center">
  <sub>
    El núcleo de Orionis se distribuye bajo licencia
    <a href="https://github.com/orionis-framework/framework/blob/1.x/LICENCE">MIT</a>.
    Consulta la licencia de cada repositorio para sus propios archivos.
  </sub>
</p>