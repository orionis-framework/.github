<p align="center">
  <a href="https://orionis-framework.com/">
    <img src="https://orionis-framework.com/favicon.svg" alt="Orionis Framework" width="140" />
  </a>
</p>

<h1 align="center">Orionis Framework</h1>

<h3 align="center">Less wiring. More building.</h3>

<p align="center">
  Async Python that connects every part of your application.
  <br />
  <strong>HTTP &middot; Real-time &middot; Data &middot; Automation &middot; MCP</strong>
</p>

<p align="center">
  <a href="https://pypi.org/project/orionis/">
    <img src="https://img.shields.io/pypi/v/orionis?style=for-the-badge&amp;color=007f8b" alt="Orionis version on PyPI" />
  </a>
  <a href="https://www.python.org/downloads/">
    <img src="https://img.shields.io/badge/Python-3.14%2B-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" alt="Python 3.14 or later" />
  </a>
  <a href="https://github.com/orionis-framework/framework">
    <img src="https://img.shields.io/badge/HTTP-ASGI%20%7C%20RSGI-7C3AED?style=for-the-badge" alt="HTTP with ASGI and RSGI" />
  </a>
  <a href="https://github.com/orionis-framework/framework/blob/1.x/LICENCE">
    <img src="https://img.shields.io/badge/Core_License-MIT-16803D?style=for-the-badge" alt="MIT-licensed core" />
  </a>
</p>

<p align="center">
  <a href="https://docs.orionis-framework.com/"><strong>Documentation</strong></a>
  &nbsp;&bull;&nbsp;
  <a href="https://orionis-framework.com/"><strong>Website</strong></a>
  &nbsp;&bull;&nbsp;
  <a href="https://github.com/orionis-framework/framework"><strong>Source code</strong></a>
  &nbsp;&bull;&nbsp;
  <a href="https://github.com/orgs/orionis-framework/discussions"><strong>Community</strong></a>
</p>

---

## ✨ Your application is more than its endpoints

An application needs more than an HTTP route. It also needs data, identity,
file storage, background jobs, and a clear way to organize its code.

**Orionis brings these pieces together in a Python framework built around
`async/await`, explicit contracts, and integrated services.**

Start with an API, a web application, or an MCP server. Build on a shared
foundation of services and extend it with the components you need.

> **Your business logic at the center. An architecture that connects everything else.**

## 🧩 A shared foundation for every layer

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🌐 HTTP and real-time communication</h3>
      <p>Routes, controllers, and middleware with ASGI and RSGI support.
      WebSockets and server-sent events for connected experiences.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🏗️ Extensible architecture</h3>
      <p>Dependency injection, context-scoped services,
      service providers, and facades for a clear separation of concerns.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🗃️ An expressive data API</h3>
      <p>An async ORM with models, relationships, and fluent queries.
      Migrations, transactions, and data preparation tools.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🔐 Identity and access control</h3>
      <p>Authentication with sessions and API tokens.
      Roles, permissions, and policies to define who can do what.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚙️ Background processing</h3>
      <p>Database- or Redis-backed queues, job processing with
      retries, and recurring command scheduling.</p>
    </td>
    <td width="50%" valign="top">
      <h3>☁️ Local and cloud storage</h3>
      <p>A single storage API for local files,
      Amazon S3, Azure Blob Storage, and Google Cloud Storage.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🤖 MCP servers</h3>
      <p>Expose tools, resources, and prompts to AI clients
      using the Model Context Protocol over HTTP and STDIO.</p>
    </td>
    <td width="50%" valign="top">
      <h3>🛠️ Developer tools</h3>
      <p>Reactor CLI, code generators, and async testing
      with access to your application's services.</p>
    </td>
  </tr>
</table>

**And the everyday essentials:** caching, email, typed validation, sessions,
Jinja2 templates, translations, logging, and exception handling.

See the documentation for each integration's configuration and optional
dependencies.

## 🚀 From idea to your first application

Install [uv](https://docs.astral.sh/uv/getting-started/installation/) and
[Git](https://git-scm.com/downloads). Orionis requires **Python 3.14 or later**.

To create an API using the `slim_api` template:

```bash
uvx --python 3.14 --from orionis-installer orionis new my-api --stack slim_api
```

Complete the setup wizard. Once it finishes successfully, start the development
server from the new project directory:

```bash
cd my-api
uv run python -B reactor serve
```

Open the URL shown in your terminal.

**Building something else?** Run the installer without `--stack` to choose
from the available templates.

[Read the installation guide →](https://docs.orionis-framework.com/en/getting-started/installation/)

## 🪐 Explore the ecosystem

| Project | What you'll find |
| :--- | :--- |
| [**Framework**](https://github.com/orionis-framework/framework) | The Orionis core and its components. |
| [**Skeleton**](https://github.com/orionis-framework/skeleton) | Starter templates for new applications. |
| [**Installer**](https://github.com/orionis-framework/installer) | The setup wizard for new applications. |
| [**Docs**](https://github.com/orionis-framework/docs) | Guides and the documentation site. |
| [**Web**](https://github.com/orionis-framework/web) | The project's public website. |

[Browse all repositories →](https://github.com/orgs/orionis-framework/repositories)

## 🤝 The next improvement could start with you

Try Orionis, share what you build, and help us improve the experience
of building with Python.

**Found a problem?** Open an
[issue](https://github.com/orionis-framework/framework/issues)
with steps to reproduce it and the versions you used.

**Have a question or an idea?** Join the conversation in
[Discussions](https://github.com/orgs/orionis-framework/discussions).

We welcome contributions to code, documentation, examples, and tests.
For larger changes, please share your proposal first.

---

<p align="center">
  <strong>Your idea deserves to become an application.</strong>
  <br />
  Build it with Orionis.
</p>

<p align="center">
  <a href="https://github.com/orionis-framework/framework">⭐ Support the project with a star</a>
  &nbsp;&bull;&nbsp;
  <a href="https://github.com/sponsors/rmunate">💜 Sponsor its development</a>
</p>

<p align="center">
  <sub>
    The Orionis core is distributed under the
    <a href="https://github.com/orionis-framework/framework/blob/1.x/LICENCE">MIT</a> license.
    Check each repository's license for the terms that apply to its files.
  </sub>
</p>