# 🦄 C# BLAZOR WEB ASSEMBLY 5 CHAT

[![Github][github-shield]][github-url]
[![Kofi][kofi-shield]][kofi-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Khanakat][khanakat-shield]][khanakat-url]

## 📔 TABLA DE CONTENIDO

* [Acerca del proyecto](#acerca-del-proyecto)
* [Características](#características)
* [Instalación](#instalación)
* [Dependencias](#dependencias)
* [Licencia](#licencia)

## 🔥 ACERCA DEL PROYECTO

Este proyecto es una muestra de una aplicación web con chat en tiempo real. Se utilizo ``Blazor Web Assembly`` con C# + Identity + SignalR + MudBlazor.

## ✔️ CARACTERÍSTICAS

- [x] Blazor WebAssembly 5.0 with ASP.NET Core Hosted Model.
- [x] MudBlazor Integrations – Super cool UI.
- [x] SignalR Integrations – Real-time Messaging with Hubs.
- [x] Cascade Parameters.
- [x] Chat with Registered Users.
- [x] Chats get stored to Database via EFCore.
- [x] Notification Popup for new messages.
- [x] Notification Tone for new messages.

## ⚙️ INSTALACIÓN

Clonar el repositorio.

```bash
gh repo clone FernandoCalmet/CS-Blazor-Chat
```

Actualizar los paquetes actuales

```bash
update-package
```

Crear la migración de base de datos

```bash
update-database
```

Ejecutar aplicación.

```bash
dotnet run
```

## 📥 DEPENDENCIAS

- [Microsoft.AspNetCore.Components.WebAssembly](https://www.nuget.org/packages/Microsoft.AspNetCore.Components.WebAssembly/) : Cree aplicaciones de una sola página (SPA) del lado del cliente con Blazor ejecutándose en WebAssembly.
- [Microsoft.AspNetCore.Components.WebAssembly.Authentication](https://www.nuget.org/packages/Microsoft.AspNetCore.Components.WebAssembly.Authentication/) : Cree autenticación del lado del cliente para aplicaciones de una sola página (SPA).
- [Microsoft.AspNetCore.Components.WebAssembly.DevServer](https://www.nuget.org/packages/Microsoft.AspNetCore.Components.WebAssembly.DevServer/) : Servidor de desarrollo para usar al crear aplicaciones Blazor.
- [Microsoft.AspNetCore.SignalR.Client](https://www.nuget.org/packages/Microsoft.AspNetCore.SignalR.Client/) : Cliente para ASP.NET Core SignalR.
- [Microsoft.Extensions.Http](https://www.nuget.org/packages/Microsoft.Extensions.Http/) : La fábrica HttpClient es un patrón para configurar y recuperar HttpClients con nombre de forma componible. La fábrica HttpClient proporciona extensibilidad para conectar DelegatingHandlers que abordan preocupaciones transversales como la ubicación del servicio, el equilibrio de carga y la confiabilidad. La fábrica HttpClient predeterminada proporciona diagnósticos y registros integrados y administra la vida útil de las conexiones de manera eficaz.
- [MudBlazor](https://www.nuget.org/packages/MudBlazor/) : MudBlazor es un ambicioso marco de componentes de Material Design para Blazor con énfasis en la facilidad de uso y la estructura clara. Es perfecto para los desarrolladores de .NET que desean crear rápidamente aplicaciones web sin tener que luchar con CSS y Javascript. MudBlazor, al estar escrito íntegramente en C #, les permite adaptar, arreglar o ampliar el marco y la multitud de ejemplos en la documentación hace que aprender MudBlazor sea muy fácil.
- [System.Net.Http.Json](https://www.nuget.org/packages/System.Net.Http.Json/) : Proporciona métodos de extensión para System.Net.Http.HttpClient y System.Net.Http.HttpContent que realizan la serialización y deserialización automáticas mediante System.Text.Json.
- [Microsoft.AspNetCore.ApiAuthorization.IdentityServer](https://www.nuget.org/packages/Microsoft.AspNetCore.ApiAuthorization.IdentityServer/) : Paquete de autorización de la API de ASP.NET Core con tecnología de Identity Server.
- [Microsoft.AspNetCore.Components.WebAssembly.Server](https://www.nuget.org/packages/Microsoft.AspNetCore.Components.WebAssembly.Server/) : Características del servidor en tiempo de ejecución para aplicaciones ASP.NET Core Blazor.
- [Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore](https://www.nuget.org/packages/Microsoft.AspNetCore.Diagnostics.EntityFrameworkCore/) : Middleware ASP.NET Core para páginas de error de Entity Framework Core. Utilice este middleware para detectar y diagnosticar errores con las migraciones de Entity Framework Core.
- [Microsoft.AspNetCore.Identity.EntityFrameworkCore](https://www.nuget.org/packages/Microsoft.AspNetCore.Identity.EntityFrameworkCore/) : Proveedor de identidad ASP.NET Core que usa Entity Framework Core.
- [Microsoft.AspNetCore.Identity.UI](https://www.nuget.org/packages/Microsoft.AspNetCore.Identity.UI/) : La interfaz de usuario de identidad de ASP.NET Core es la interfaz de usuario integrada de Razor Pages predeterminada para el marco de identidad de ASP.NET Core.
- [Microsoft.EntityFrameworkCore.Tools](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Tools/) : Entity Framework Core Tools para la consola del administrador de paquetes NuGet en Visual Studio.

## 📄 LICENCIA

Este proyecto está bajo la Licencia (Licencia MIT) - mire el archivo [LICENSE](LICENSE) para más detalles.

## ⭐️ DAME UNA ESTRELLA

Si esta Implementación le resultó útil o la utilizó en sus Proyectos, déle una estrella. ¡Gracias! O, si te sientes realmente generoso, [¡Apoye el proyecto con una pequeña contribución!](https://ko-fi.com/fernandocalmet).

<!--- reference style links --->
[github-shield]: https://img.shields.io/badge/-@fernandocalmet-%23181717?style=flat-square&logo=github
[github-url]: https://github.com/fernandocalmet
[kofi-shield]: https://img.shields.io/badge/-@fernandocalmet-%231DA1F2?style=flat-square&logo=kofi&logoColor=ff5f5f
[kofi-url]: https://ko-fi.com/fernandocalmet
[linkedin-shield]: https://img.shields.io/badge/-fernandocalmet-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/fernandocalmet
[linkedin-url]: https://www.linkedin.com/in/fernandocalmet
[khanakat-shield]: https://img.shields.io/badge/khanakat.com-brightgreen?style=flat-square
[khanakat-url]: https://khanakat.com