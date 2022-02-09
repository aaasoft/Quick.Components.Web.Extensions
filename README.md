# Quick.Components.Web.Extensions
[![NuGet Version](http://img.shields.io/nuget/v/Quick.AspNetCore.Components.Web.Extensions.svg?style=flat)](https://www.nuget.org/packages/Quick.AspNetCore.Components.Web.Extensions/)
A collection of Blazor components for the web.
Fork from https://github.com/aspnet/AspLabs


## Installation
**1. Add the nuget package in your Blazor project**
```
> dotnet add package Quick.Components.Web.Extensions

OR

PM> Install-Package Quick.Components.Web.Extensions
```

**2. Add the following line in your `_Imports.razor`**
```csharp
@using Microsoft.AspNetCore.Components.Web.Extensions.Head
```

**3. Reference the static files**

Add the following static file references in your `_Host.cshtml` (server-side blazor) or in your `index.html` (client-side blazor). 
Make sure that there is a call to `app.UseStaticFiles();` in your server project's `Startup.cs`.

```html
<script type="module" src="_content/Quick.AspNetCore.Components.Web.Extensions/headManager.js"></script>
```

## Basic usage(*.razor)

```xml

<Title Value="Page title to be set"></Title>

```