# CloudNimble

We build **[EasyAF](https://easyaf.nimbleapps.cloud)** — The Application Framework That's Easy As F\*ck.

We started by making it easy as fuck to build applications on .NET. Now we're making it easy as fuck to build for Super Intelligence on .NET, too.

Founded by [Robert McLaws](https://github.com/robertmclaws).

## Back-end

| Product | Packages | Docs | Purpose |
| --- | --- | --- | --- |
| [Core](https://github.com/CloudNimble/EasyAF) | [![EasyAF.Core](https://img.shields.io/nuget/vpre/EasyAF.Core?logo=nuget&label=EasyAF.Core)](https://www.nuget.org/packages/EasyAF.Core) | [Observable Objects](https://easyaf.nimbleapps.cloud/guides/observable-objects) | Observables, identity, intervals, and the shared primitives everything else sits on. |
| [Data](https://github.com/CloudNimble/EasyAF) | [![EasyAF.Data.EFCore](https://img.shields.io/nuget/vpre/EasyAF.Data.EFCore?logo=nuget&label=EasyAF.Data.EFCore)](https://www.nuget.org/packages/EasyAF.Data.EFCore)<br>[![EasyAF.Data.EF6](https://img.shields.io/nuget/vpre/EasyAF.Data.EF6?logo=nuget&label=EasyAF.Data.EF6)](https://www.nuget.org/packages/EasyAF.Data.EF6) | [Table Design](https://easyaf.nimbleapps.cloud/guides/table-design) | EF Core and EF6 helpers that keep change-tracking fields out of the store and the model honest. |
| [EntityDesigner](https://github.com/CloudNimble/EasyAF.EntityDesigner) | [![EasyAF.Edmx.DiagramTools](https://img.shields.io/nuget/vpre/EasyAF.Edmx.DiagramTools?logo=nuget&label=EasyAF.Edmx.DiagramTools)](https://www.nuget.org/packages/EasyAF.Edmx.DiagramTools) | [Entity Designer](https://github.com/CloudNimble/EasyAF.EntityDesigner#readme) | Microsoft's EDMX designer, rebuilt for VS2022/VS2026, SDK-style projects, and .NET 10. |
| [Business Logic](https://github.com/CloudNimble/EasyAF) | [![EasyAF.Business.EFCore](https://img.shields.io/nuget/vpre/EasyAF.Business.EFCore?logo=nuget&label=EasyAF.Business.EFCore)](https://www.nuget.org/packages/EasyAF.Business.EFCore)<br>[![EasyAF.Business.EF6](https://img.shields.io/nuget/vpre/EasyAF.Business.EF6?logo=nuget&label=EasyAF.Business.EF6)](https://www.nuget.org/packages/EasyAF.Business.EF6) | [Business Layer](https://easyaf.nimbleapps.cloud/guides/business-layer) | Entity managers with CRUD, audit, lifecycle hooks, and state machines. |
| [Async](https://github.com/CloudNimble/SimpleMessageBus) | [![SimpleMessageBus.Core](https://img.shields.io/nuget/vpre/SimpleMessageBus.Core?logo=nuget&label=SimpleMessageBus.Core)](https://www.nuget.org/packages/SimpleMessageBus.Core) | [SimpleMessageBus](https://easyaf.nimbleapps.cloud/simplemessagebus) | Reliable, distributed event processing. File system, Azure queues, IndexedDB, HTTP. |

## Web

| Product | Packages | Docs | Purpose |
| --- | --- | --- | --- |
| [Utilities](https://github.com/CloudNimble/EasyAF) | [![EasyAF.Http](https://img.shields.io/nuget/vpre/EasyAF.Http?logo=nuget&label=EasyAF.Http)](https://www.nuget.org/packages/EasyAF.Http)<br>[![EasyAF.Http.SystemTextJson](https://img.shields.io/nuget/vpre/EasyAF.Http.SystemTextJson?logo=nuget&label=EasyAF.Http.SystemTextJson)](https://www.nuget.org/packages/EasyAF.Http.SystemTextJson) | [Dual HttpContexts](https://easyaf.nimbleapps.cloud/guides/dual-httpcontexts) | HttpClient factories, OData URI builders, and serialization helpers. |
| [Web APIs](https://github.com/OData/RESTier) | [![EasyAF.Restier](https://img.shields.io/nuget/vpre/EasyAF.Restier?logo=nuget&label=EasyAF.Restier)](https://www.nuget.org/packages/EasyAF.Restier)<br>[![Microsoft.Restier.AspNetCore](https://img.shields.io/nuget/vpre/Microsoft.Restier.AspNetCore?logo=nuget&label=Microsoft.Restier.AspNetCore)](https://www.nuget.org/packages/Microsoft.Restier.AspNetCore) | [Restier](https://easyaf.nimbleapps.cloud/restier) | OData v4 APIs from your EF model. EasyAF.Restier plus Restier. |
| [UI](https://github.com/CloudNimble/BlazorEssentials) | [![BlazorEssentials](https://img.shields.io/nuget/vpre/BlazorEssentials?logo=nuget&label=BlazorEssentials)](https://www.nuget.org/packages/BlazorEssentials) | [BlazorEssentials](https://easyaf.nimbleapps.cloud/blazoressentials) | MVVM, app state, IndexedDB, and the rest of a real Blazor app. |

## Shipping bulletproof apps

| Product | Packages | Docs | Purpose |
| --- | --- | --- | --- |
| [Testing](https://github.com/CloudNimble/Breakdance) | [![Breakdance.Assemblies](https://img.shields.io/nuget/vpre/Breakdance.Assemblies?logo=nuget&label=Breakdance.Assemblies)](https://www.nuget.org/packages/Breakdance.Assemblies) | [Breakdance](https://easyaf.nimbleapps.cloud/breakdance) | Surface tests that break *your* build before they break your customers. |
| [Documentation](https://github.com/CloudNimble/DotNetDocs) | [![DotNetDocs](https://img.shields.io/nuget/vpre/DotNetDocs?logo=nuget&label=DotNetDocs)](https://www.nuget.org/packages/DotNetDocs) | [DotNetDocs](https://dotnetdocs.com) | Docs that ship with the code, powered by Mintlify. |

## Super Intelligence

| Product | Packages | Docs | Purpose |
| --- | --- | --- | --- |
| [MCP Servers](https://github.com/CloudNimble/McpEssentials) | [![McpEssentials.Core](https://img.shields.io/nuget/vpre/McpEssentials.Core?logo=nuget&label=McpEssentials.Core)](https://www.nuget.org/packages/McpEssentials.Core) | [McpEssentials](https://easyaf.dev/mcpessentials) | Authenticated task stores, form elicitation, durable EF / Redis / Cosmos / PostgreSQL backends. |
| [Claude Hooks](https://github.com/CloudNimble/ClaudeEssentials) | [![ClaudeEssentials](https://img.shields.io/nuget/vpre/ClaudeEssentials?logo=nuget&label=ClaudeEssentials)](https://www.nuget.org/packages/ClaudeEssentials) | [ClaudeEssentials](https://ai.easyaf.dev/claudeessentials) | AOT-ready C# models for every Claude Code hook. |
| [MCP-enabled APIs](https://github.com/OData/MCP) | [![Microsoft.OData.Mcp.Core](https://img.shields.io/nuget/vpre/Microsoft.OData.Mcp.Core?logo=nuget&label=Microsoft.OData.Mcp.Core)](https://www.nuget.org/packages/Microsoft.OData.Mcp.Core) | [OData for AI](https://github.com/OData/MCP#readme) | Turn an OData service into MCP tools. Local server or in-process middleware. |

## One-off utilities

| Product | Packages | Docs | Purpose |
| --- | --- | --- | --- |
| [Mintlify.Core](https://github.com/CloudNimble/DotNetDocs) | [![Mintlify.Core](https://img.shields.io/nuget/vpre/Mintlify.Core?logo=nuget&label=Mintlify.Core)](https://www.nuget.org/packages/Mintlify.Core) | [.NET Library for Mintlify](https://dotnetdocs.com/providers/mintlify/dotnet-library) | .NET models for Mintlify `docs.json`. Lives in DotNetDocs. |
| [PortableRest](https://github.com/CloudNimble/PortableRest) | [![PortableRest](https://img.shields.io/nuget/vpre/PortableRest?logo=nuget&label=PortableRest)](https://www.nuget.org/packages/PortableRest) | [README](https://github.com/CloudNimble/PortableRest#readme) | A PCL-era REST client, still shipping. Partially drop-in compatible with RestSharp. |
| [Zlib](https://github.com/CloudNimble/Zlib.Portable) | [![Zlib.Portable](https://img.shields.io/nuget/vpre/Zlib.Portable?logo=nuget&label=Zlib.Portable)](https://www.nuget.org/packages/Zlib.Portable) | [README](https://github.com/CloudNimble/Zlib.Portable#readme) | A portable zlib, from the PCL years. |
| Base36 | [![Base36](https://img.shields.io/nuget/vpre/Base36?logo=nuget&label=Base36)](https://www.nuget.org/packages/Base36) | [NuGet](https://www.nuget.org/packages/Base36) | Base36 encoding. |
| [SendGridPlus](https://github.com/advancedrei/sendgrid-csharp) | [![SendGridPlus](https://img.shields.io/nuget/vpre/SendGridPlus?logo=nuget&label=SendGridPlus)](https://www.nuget.org/packages/SendGridPlus) | [README](https://github.com/advancedrei/sendgrid-csharp#readme) | SendGrid Mail and Event APIs, including batched events. |
| [TypeLitePlus](https://github.com/CloudNimble/TypeLitePlus) | [![TypeLitePlus](https://img.shields.io/nuget/vpre/TypeLitePlus?logo=nuget&label=TypeLitePlus)](https://www.nuget.org/packages/TypeLitePlus) | [README](https://github.com/CloudNimble/TypeLitePlus#readme) | Generate TypeScript from .NET classes. |

## Find us

- Docs: [easyaf.nimbleapps.cloud](https://easyaf.nimbleapps.cloud)
- NuGet: [CloudNimble](https://www.nuget.org/profiles/CloudNimble)
- X: [@robertmclaws](https://x.com/robertmclaws)
