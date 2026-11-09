# CloudNimble

We build **[EasyAF](https://easyaf.nimbleapps.cloud)** — The Application Framework That's Easy As F\*ck.

We started by making it easy as f\*ck to build applications on .NET. Now we're making it easy as f\*ck to build for Super Intelligence on .NET, too.

Founded by [Robert McLaws](https://github.com/robertmclaws).

## Back-end

| Product | What it is |
| --- | --- |
| [Core](https://www.nuget.org/packages/EasyAF.Core/) | Observables, identity, intervals, and the shared primitives everything else sits on. |
| [Data](https://www.nuget.org/packages/EasyAF.Data.EFCore/) | EF Core and EF6 helpers that keep change-tracking fields out of the store and the model honest. |
| [EntityDesigner](https://github.com/CloudNimble/EasyAF.EntityDesigner) | Microsoft's EDMX designer, rebuilt for VS2022/VS2026, SDK-style projects, and .NET 10. |
| [Business Logic](https://www.nuget.org/packages/EasyAF.Business.EFCore/) | Entity managers with CRUD, audit, lifecycle hooks, and state machines. |
| [Async](https://github.com/CloudNimble/SimpleMessageBus) ([SimpleMessageBus](https://github.com/CloudNimble/SimpleMessageBus)) | Reliable, distributed event processing. File system, Azure queues, IndexedDB, HTTP. |

## Web

| Product | What it is |
| --- | --- |
| Utilities | [EasyAF.Http](https://www.nuget.org/packages/EasyAF.Http/) plus serialization helpers for OData clients and HttpClient factories. |
| Web APIs | [EasyAF.Restier](https://www.nuget.org/packages/EasyAF.Restier/) and [Restier](https://github.com/OData/RESTier) — OData v4 APIs from your EF model. |
| UI | [BlazorEssentials](https://github.com/CloudNimble/BlazorEssentials) — MVVM, app state, IndexedDB, and the rest of a real Blazor app. |

## Shipping bulletproof apps

| Product | What it is |
| --- | --- |
| Testing | [Breakdance](https://github.com/CloudNimble/Breakdance) — surface tests that break *your* build before they break your customers. |
| Documentation | [DotNetDocs](https://github.com/CloudNimble/DotNetDocs) — docs that ship with the code, powered by Mintlify. |

## Super Intelligence

| Product | What it is |
| --- | --- |
| MCP Servers | [McpEssentials](https://www.nuget.org/packages/McpEssentials.Core/) — authenticated task stores, form elicitation, durable EF / Redis / Cosmos / PostgreSQL backends. |
| Claude Hooks | [ClaudeEssentials](https://github.com/CloudNimble/ClaudeEssentials) — AOT-ready C# models for every Claude Code hook. |
| MCP-enabled APIs | [Microsoft OData for Super Intelligence](https://github.com/OData/MCP) — turn an OData service into MCP tools. Local server or in-process middleware. |

## One-off utilities

| Product | What it is |
| --- | --- |
| [Mintlify.Core](https://www.nuget.org/packages/Mintlify.Core/) | .NET models for Mintlify `docs.json`. Lives in [DotNetDocs](https://github.com/CloudNimble/DotNetDocs). |
| [PortableRest](https://github.com/CloudNimble/PortableRest) | A PCL-era REST client, still shipping. Partially drop-in compatible with RestSharp. |
| [Zlib](https://github.com/CloudNimble/Zlib.Portable) | A portable zlib, from the PCL years. |
| [Base36](https://www.nuget.org/packages/Base36/) | Base36 encoding. |
| [SendGridPlus](https://www.nuget.org/packages/SendGridPlus/) | SendGrid Mail and Event APIs, including batched events. |
| [TypeLitePlus](https://github.com/CloudNimble/TypeLitePlus) | Generate TypeScript from .NET classes. |

## Find us

- Docs: [easyaf.nimbleapps.cloud](https://easyaf.nimbleapps.cloud)
- NuGet: [CloudNimble](https://www.nuget.org/profiles/CloudNimble)
- X: [@robertmclaws](https://x.com/robertmclaws)
