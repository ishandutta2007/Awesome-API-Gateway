<p align="center">
  <img src="./assets/banner.svg" alt="Awesome API Gateway" width="100%" />
</p>

# 🚪 Awesome API Gateway & Management Platforms

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-API-Gateway/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-API-Gateway?style=flat-square&logo=github&color=gold" alt="Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-API-Gateway/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-API-Gateway?style=flat-square&logo=github&color=blue" alt="Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-API-Gateway/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-API-Gateway?style=flat-square&color=green" alt="License"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-API-Gateway/commits/main"><img src="https://img.shields.io/github/last-commit/ishandutta2007/Awesome-API-Gateway?style=flat-square" alt="Last Commit"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

> 🚀 A curated list of **API Gateways, API Management platforms, cloud API gateways, Kubernetes Gateway API ingress controllers, high-performance edge proxies, and open-source API gateway software** for routing, securing, governing, observing, and scaling microservices and AI workloads.

An API Gateway sits at the edge of an application or microservices platform and commonly provides:

* 🚦 **Request routing & load balancing**
* 🔐 **Authentication and authorization (OAuth2, OIDC, JWT, mTLS)**
* 🛡️ **TLS termination & Web Application Firewall (WAF)**
* ⏱️ **Rate limiting, throttling & quotas**
* 🔑 **API keys & consumer management**
* 🔄 **Traffic transformation & request/response mutation**
* ⚡ **Response caching & edge acceleration**
* ⚡ **Circuit breaking & fault tolerance**
* 🎯 **Canary releases, blue/green deployments & traffic mirroring**
* 🏷️ **API versioning & deprecation lifecycle**
* 📊 **Observability (OpenTelemetry, Prometheus, distributed tracing)**
* 📖 **Developer portals & interactive API catalogs**
* 📜 **API policies, validation & schema enforcement**
* 💳 **API monetization & subscription billing**
* 🔍 **Service discovery & dynamic backends**
* 🔌 **WebSocket, gRPC & HTTP/3 support**
* ☸️ **Kubernetes Ingress & Gateway API integration**
* 🤖 **AI / LLM traffic management, prompt routing & token rate limiting**

This repository focuses primarily on **open-source and self-hostable API gateways**, while maintaining a comprehensive, transparent guide of hosted and commercial platforms such as Kong Konnect, Google Apigee, Tyk Cloud, Gravitee, MuleSoft, Azure API Management, AWS API Gateway, IBM API Connect and WSO2.

> 💡 **Important distinction:** An API Gateway is not necessarily the same thing as a complete API Management platform. A gateway primarily handles runtime traffic, while API management can additionally include API design, lifecycle management, developer portals, analytics, governance, monetization and organizational workflows.

---

## 📑 Table of Contents

* [☁️ SaaS/Hosted Platforms](#️-saashosted-platforms)
* [🌍 Open-Source](#-open-source)
* [🚪 Open-Source API Gateways](#-open-source-api-gateways)
* [☸️ Kubernetes & Cloud-Native API Gateways](#️-kubernetes--cloud-native-api-gateways)
* [⚡ High-Performance API Gateways](#-high-performance-api-gateways)
* [🔀 API Gateway & Reverse Proxy Software](#-api-gateway--reverse-proxy-software)
* [🧩 Service Mesh & Programmable Proxies](#-service-mesh--programmable-proxies)
* [🔐 Open-Source API Security](#-open-source-api-security)
* [🚦 Open-Source Traffic Management](#-open-source-traffic-management)
* [📊 Open-Source API Gateway Observability](#-open-source-api-gateway-observability)
* [🛠️ Open-Source API Gateway Control Planes](#️-open-source-api-gateway-control-planes)
* [🤖 Open-Source AI Gateways](#-open-source-ai-gateways)
* [🧩 Commercial Platform → Open-Source Equivalent](#-commercial-platform--open-source-equivalent)
* [🏗️ API Gateway Architecture](#️-api-gateway-architecture)
* [🔄 Open-Source API Gateway Architecture](#-open-source-api-gateway-architecture)
* [☸️ Kubernetes API Gateway Architecture](#️-kubernetes-api-gateway-architecture)
* [🔐 API Security Architecture](#-api-security-architecture)
* [📊 API Gateway Technology Comparison](#-api-gateway-technology-comparison)
* [⚖️ Commercial vs Open-Source](#️-commercial-vs-open-source)
* [🚀 Recommended Open-Source Stacks](#-recommended-open-source-stacks)
* [🎯 Recommended Projects by Use Case](#-recommended-projects-by-use-case)
* [🏢 Building a Kong Alternative](#-building-a-kong-alternative)
* [🏗️ Building an Apigee Alternative](#️-building-an-apigee-alternative)
* [🌐 Open-Source API Gateway Landscape](#-open-source-api-gateway-landscape)
* [🧠 API Gateway Layers](#-api-gateway-layers)
* [🔥 Why Open-Source API Gateways Matter](#-why-open-source-api-gateways-matter)
* [❓ Frequently Asked Questions (FAQ)](#-frequently-asked-questions-faq)
* [📈 Star History](#-star-history)
* [🤝 Contributing](#-contributing)
* [⚠️ Disclaimer](#️-disclaimer)

---

# ☁️ SaaS/Hosted Platforms

Commercial and managed API gateway platforms combine runtime traffic management with varying degrees of API lifecycle management, analytics, governance and developer tooling.

> 🌐 **Market Overview & Industry Structure:** The global API Management & Gateway market size was estimated at **$5.1B – $6.2B in 2024–2025** and is projected to reach **$15.2B+ by 2030** (growing at a ~28–31% CAGR). The sector is **moderately fragmented**: while hyperscale cloud providers (Microsoft, Google Cloud, AWS) and legacy enterprise integration incumbents (Salesforce MuleSoft, IBM) command large enterprise market share, specialized high-performance vendors (Kong, Tyk, Traefik, Gravitee, Solo.io) and vibrant open-source ecosystems prevent a winner-take-all monopoly, driving intense multi-cloud competition.

| Platform | Company | Company Size (Valuation / Market Cap) | Primary Focus | Key Capabilities | Starting Pricing | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| [Azure API Management](https://azure.microsoft.com/products/api-management/) | Microsoft | ~$3.1T Market Cap | Cloud API Management | Gateway, policies, developer portal, analytics and hybrid deployment | Consumption: $3.50 per 1M calls (first 1M free); Developer tier: $48.04/month; Basic v2: $146/month; Standard v2: $730/month | Free forever: Consumption tier includes 1,000,000 free calls/month per subscription (no SLA); plus 30-day $200 Azure trial credits |
| [Azure Application Gateway](https://azure.microsoft.com/products/application-gateway/) | Microsoft | ~$3.1T Market Cap | Application gateway | L7 routing, TLS termination, WAF and load balancing | Standard v2 starts at $0.246/hour (~$180/month) + $0.008/Capacity Unit-hour; WAF v2 starts at $0.443/hour (~$323/month) | 30-day free trial via $200 Azure trial credits (no permanent free tier for Application Gateway) |
| [Google Apigee](https://cloud.google.com/apigee) | Google Cloud | ~$2.1T Market Cap | Enterprise API Management | Gateway, policies, analytics, developer portals, monetization and lifecycle management | Pay-as-you-go starts at $0.50/environment-hour (~$365/month per region) + $20 per 1M standard proxy calls ($100/1M extensible proxy calls) | 60-day free trial (evaluation organization) with full enterprise capabilities and analytics + $300 Google Cloud 90-day trial credits |
| [Amazon API Gateway](https://aws.amazon.com/api-gateway/) | AWS | ~$1.9T Market Cap | Managed cloud gateway | REST, HTTP, WebSocket APIs, throttling and AWS integration | HTTP APIs: $1.00 per 1M calls; REST APIs: $3.50 per 1M calls; WebSocket APIs: $1.00 per 1M messages + $0.25/million connection-minutes | AWS Free Tier: 1,000,000 HTTP calls, 1,000,000 REST calls, and 1,000,000 WebSocket messages (+ 750,000 connection-mins)/month for first 12 months |
| [AWS AppSync](https://aws.amazon.com/appsync/) | AWS | ~$1.9T Market Cap | GraphQL API layer | Managed GraphQL gateway and API integration | $4.00 per 1M GraphQL query/mutation operations; $2.00 per 1M real-time update messages + $0.08 per 1M connection-minutes | AWS Free Tier: 250,000 query/mutation operations, 250,000 real-time updates, and 600,000 connection-minutes/month for first 12 months |
| [MuleSoft Anypoint API Manager](https://www.mulesoft.com/platform/api) | Salesforce | ~$280B Market Cap | Enterprise integration + API Management | Gateway, policies, lifecycle, analytics and integration | Integration Starter / Base packages start at ~$55,000/year (~$4,583/month) for core flows/messages; tiered volume pricing | 30-day free trial of Anypoint Platform with full API design, mock, and management capabilities (evaluation sandbox, non-production) |
| [IBM API Connect](https://www.ibm.com/products/api-connect) | IBM | ~$210B Market Cap | Enterprise API Management | Gateway, lifecycle, security, analytics and developer portal | Pay-as-you-go SaaS on AWS / IBM Cloud starts at $100/month (includes base calls; additional calls from ~$0.0015/call); Reserved from ~$3,000/month | 30-day free trial limited to 100,000 API calls and 1 service instance (no credit card required, non-production) |
| [Cloudflare API Gateway](https://www.cloudflare.com/application-services/products/api-gateway/) | Cloudflare | ~$35B Market Cap | Edge API security | API discovery, security, rate limiting and edge traffic management | Enterprise add-on starting at ~$2,000/month (base Cloudflare Enterprise contracts start at ~$3,000–$5,000/month) | 30-day Enterprise POC / trial upon sales consultation; Cloudflare Free plan includes basic edge proxy/DNS/DDoS and 100,000 Worker requests/day |
| [NGINX Plus](https://www.nginx.com/products/nginx/) | F5 | ~$14B Market Cap | High-performance gateway | Reverse proxy, load balancing, API gateway and security | Starts at $2,500 per instance/year (~$208/month); NGINXaaS on cloud starts at ~$0.08/NCU-hour; App Protect WAF is +$2,000/instance/year | 30-day free trial with unrestricted access to NGINX Plus features and support (or $100 cloud credit); NGINX OSS is free forever |
| [Kong Konnect](https://konghq.com/products/kong-konnect) | Kong | ~$2.0B Valuation | Cloud API platform | API Gateway, service connectivity, governance, analytics and AI Gateway | Plus tier starts at $250/month (includes 1M requests/mo, 5 Serverless Gateways, 2 Dev Portals; $200 per additional 1M requests up to 10M) | 30-day free trial with full enterprise functionality, up to 5 serverless gateways, and no credit card required; Kong OSS is free forever self-hosted |
| [Gloo Gateway](https://www.solo.io/products/gloo-gateway) | Solo.io | ~$1.0B Valuation | Kubernetes API Gateway | Envoy-based gateway, Gateway API and enterprise management | Commercial enterprise cluster subscriptions start at ~$15,000/year (~$1,250/month) for small production clusters | 30-day free trial evaluation license key with full enterprise features (WAF, portal, OIDC); kgateway (Gloo OSS) is free forever under Apache 2.0 |
| [WSO2 API Manager](https://wso2.com/api-manager/) | WSO2 | ~$600M Valuation | Full API lifecycle | Gateway, lifecycle, security, analytics and developer portal | Choreo Pay-As-You-Go starts at $150/component/month; Enterprise Managed Cloud starts at ~$1,500/month; WSO2 API Manager OSS is free self-hosted | Free forever: Choreo Free tier includes 1 project, 5 components (APIs), $100/mo infrastructure credits, 2M calls/mo, and 10 Dev Portal apps |
| [Gravitee](https://www.gravitee.io/) | Gravitee | ~$300M+ Valuation | API Management | REST, event APIs, security, gateway, portal and governance | Planet tier starts at $2,500/month (includes 1 production gateway, unlimited APIs and users); Event Management starts at $1,250/month | 14-day free trial for Enterprise Edition (Cockpit access, advanced security policies, no credit card required); Community Edition is free forever open source |
| [Traefik Hub](https://traefik.io/traefik-hub/) | Traefik | ~$150M+ Valuation | Cloud-native API management | Kubernetes gateway, ingress, API management and observability | Commercial gateway & management tiers start at ~$1,000/month (instance/cluster-based pricing); Traefik Proxy OSS is free | 30-day free trial for Traefik Hub API Gateway / Management with full features and no credit card required; Traefik Proxy is free forever under MIT |
| [Tyk Cloud](https://tyk.io/) | Tyk | ~$100M+ Valuation | API Management | Gateway, API management, GraphQL, analytics and developer portal | Cloud Core starts at $600/month (includes up to 5 APIs and 10 million monthly calls; scaling to $3,800/mo for 100M calls); Self-Managed custom quoted | 48-hour free trial for Tyk Cloud SaaS with full platform access (or 14-day free trial for self-managed enterprise); Tyk Gateway OSS is free forever under MPL-2.0 |
| [KrakenD Enterprise](https://www.krakend.io/) | KrakenD | ~$15M+ Valuation | API Gateway / API Aggregation | High-performance gateway, aggregation, security and enterprise management | Flat-rate enterprise subscription starting at ~$1,500/month (~$18,000/year) per cluster with unlimited throughput; managed hosting from ~$11/mo on cloud partners | 2-month (60-day) free trial of KrakenD Enterprise with full feature access (gRPC, WebSockets, FIPS, multi-IdP); Community Edition is free forever open source with no call limits |

The current API gateway landscape spans gateway-first products such as Kong, Tyk and APISIX, full API-management platforms such as Apigee and WSO2, and cloud-native gateways such as Gloo Gateway.



---



# 🌍 Open-Source



The open-source API gateway ecosystem is unusually strong.



Instead of buying a complete proprietary platform, organizations can assemble an API platform from:



```text

                         OPEN-SOURCE API PLATFORM

                                    │

             ┌──────────────────────┼──────────────────────┐

             │                      │                      │

             ▼                      ▼                      ▼

       API Gateway             Control Plane          Developer Portal

             │                      │                      │

             ▼                      ▼                      ▼

       APISIX / Kong            etcd / GitOps       Backstage / Docs

       Tyk / Gravitee           Kubernetes          Custom Portal

       Envoy / Traefik

             │

             ▼

      Security + Policies

             │

             ▼

      Observability + Analytics

```



The strongest open-source projects include:

* 🛡️ **Caddy** – Automatic HTTPS reverse proxy & edge server
* 🚦 **Traefik Proxy** – Modern cloud-native dynamic reverse proxy & ingress
* 🦍 **Kong Gateway** – Scalable NGINX/Lua API gateway with extensive plugin ecosystem
* 🕸️ **Istio Ingress Gateway** – Industry-standard service mesh & gateway
* ⚡ **Envoy Proxy** – High-performance programmable C++ proxy
* 🌐 **NGINX** – High-performance reverse proxy & web foundation
* 🤖 **LiteLLM Gateway** – Universal AI / LLM proxy & router
* 🐝 **Cilium** – eBPF-native Kubernetes Gateway API & service mesh
* 🥇 **Apache APISIX** – Dynamic, high-throughput cloud-native API gateway
* 🍿 **Zuul** – Netflix JVM-based edge gateway & filter engine
* 🐍 **Tyk Gateway** – High-performance Go gateway with GraphQL support
* 🔷 **Ocelot** – Lightweight .NET microservice API gateway
* 🐙 **KrakenD** – Ultra-fast stateless API aggregator & gateway
* 🌊 **OpenResty** – Full-fledged web platform integrating NGINX & LuaJIT
* 🚀 **BFE** – Industrial-grade layer 7 routing & proxy engine
* 🎯 **Easegress** – Traffic orchestration & resilience reverse proxy
* ⚖️ **HAProxy** – World-renowned TCP/HTTP load balancer & proxy
* 🍃 **Spring Cloud Gateway** – Reactive Spring Boot 3 API routing architecture
* ☁️ **Higress** – Next-gen cloud-native gateway based on Envoy & Istio
* 🚪 **Emissary-Ingress** – CNCF Envoy-based ingress controller & gateway
* 🔮 **Apache ShenYu** – Asynchronous multi-protocol Java API gateway
* 🗺️ **Contour** – High-performance Envoy ingress controller for Kubernetes
* ⚡ **Express Gateway** – Microservices API gateway built on Express.js
* 🌊 **Gravitee** – Event-native and REST API management platform
* ☸️ **Envoy Gateway** – Official CNCF Kubernetes Gateway API controller
* 🛠️ **Gloo Gateway / kgateway** – Kubernetes Gateway API control plane

---

# 🚪 Open-Source API Gateways

| Project | GitHub Stars | Language / Foundation | Primary Strength | License |
| :--- | :---: | :--- | :--- | :--- |
| [Caddy](https://github.com/caddyserver/caddy) | [![GitHub stars](https://img.shields.io/github/stars/caddyserver/caddy?style=social&color=white)](https://github.com/caddyserver/caddy/stargazers) | Go | Modern reverse proxy with automatic HTTPS & TLS lifecycle | Apache-2.0 |
| [Traefik Proxy](https://github.com/traefik/traefik) | [![GitHub stars](https://img.shields.io/github/stars/traefik/traefik?style=social&color=white)](https://github.com/traefik/traefik/stargazers) | Go | Cloud-native ingress, automatic service discovery & middleware | MIT |
| [Kong Gateway](https://github.com/Kong/kong) | [![GitHub stars](https://img.shields.io/github/stars/Kong/kong?style=social&color=white)](https://github.com/Kong/kong/stargazers) | Lua / OpenResty | Mature plugin ecosystem, DB & DB-less modes, enterprise adoption | Apache-2.0 core |
| [Istio](https://github.com/istio/istio) | [![GitHub stars](https://img.shields.io/github/stars/istio/istio?style=social&color=white)](https://github.com/istio/istio/stargazers) | Go / C++ / CNCF | Enterprise service mesh ingress & dynamic L4/L7 traffic policies | Apache-2.0 |
| [Envoy Proxy](https://github.com/envoyproxy/envoy) | [![GitHub stars](https://img.shields.io/github/stars/envoyproxy/envoy?style=social&color=white)](https://github.com/envoyproxy/envoy/stargazers) | C++ / CNCF | Ultra high-performance programmable L4/L7 data plane | Apache-2.0 |
| [NGINX](https://github.com/nginx/nginx) | [![GitHub stars](https://img.shields.io/github/stars/nginx/nginx?style=social&color=white)](https://github.com/nginx/nginx/stargazers) | C | High-performance reverse proxy, load balancer & web server | BSD-2-Clause |
| [LiteLLM Gateway](https://github.com/BerriAI/litellm) | [![GitHub stars](https://img.shields.io/github/stars/BerriAI/litellm?style=social&color=white)](https://github.com/BerriAI/litellm/stargazers) | Python | Universal AI/LLM API gateway proxy with 100+ model routing & budgets | Apache-2.0 |
| [Cilium](https://github.com/cilium/cilium) | [![GitHub stars](https://img.shields.io/github/stars/cilium/cilium?style=social&color=white)](https://github.com/cilium/cilium/stargazers) | Go / C / eBPF / CNCF | Kernel-level eBPF networking, Ingress & Gateway API enforcement | Apache-2.0 |
| [Apache APISIX](https://github.com/apache/apisix) | [![GitHub stars](https://img.shields.io/github/stars/apache/apisix?style=social&color=white)](https://github.com/apache/apisix/stargazers) | Lua / NGINX / etcd / ASF | Dynamic routing, 100+ hot-reloadable plugins & low latency | Apache-2.0 |
| [Zuul](https://github.com/Netflix/zuul) | [![GitHub stars](https://img.shields.io/github/stars/Netflix/zuul?style=social&color=white)](https://github.com/Netflix/zuul/stargazers) | Java | Battle-tested JVM edge service gateway for routing & resilience | Apache-2.0 |
| [Tyk Gateway](https://github.com/TykTechnologies/tyk) | [![GitHub stars](https://img.shields.io/github/stars/TykTechnologies/tyk?style=social&color=white)](https://github.com/TykTechnologies/tyk/stargazers) | Go | Fast API gateway with Universal GraphQL engine & middleware | MPL-2.0 |
| [Ocelot](https://github.com/ThreeMammals/Ocelot) | [![GitHub stars](https://img.shields.io/github/stars/ThreeMammals/Ocelot?style=social&color=white)](https://github.com/ThreeMammals/Ocelot/stargazers) | C# / .NET | Lightweight .NET-native microservice API gateway | MIT |
| [KrakenD Community Edition](https://github.com/krakendio/krakend-ce) | [![GitHub stars](https://img.shields.io/github/stars/krakendio/krakend-ce?style=social&color=white)](https://github.com/krakendio/krakend-ce/stargazers) | Go | Stateless high-throughput API gateway & endpoint aggregator | Apache-2.0 |
| [OpenResty](https://github.com/openresty/openresty) | [![GitHub stars](https://img.shields.io/github/stars/openresty/openresty?style=social&color=white)](https://github.com/openresty/openresty/stargazers) | C / LuaJIT | Fast web & gateway platform integrating NGINX with LuaJIT | BSD-2-Clause |
| [BFE](https://github.com/bfenetworks/bfe) | [![GitHub stars](https://img.shields.io/github/stars/bfenetworks/bfe?style=social&color=white)](https://github.com/bfenetworks/bfe/stargazers) | Go / CNCF | Enterprise-grade layer 7 routing engine & load balancer | Apache-2.0 |
| [Easegress](https://github.com/megaease/easegress) | [![GitHub stars](https://img.shields.io/github/stars/megaease/easegress?style=social&color=white)](https://github.com/megaease/easegress/stargazers) | Go | Traffic orchestration & high availability resilience gateway | Apache-2.0 |
| [HAProxy](https://github.com/haproxy/haproxy) | [![GitHub stars](https://img.shields.io/github/stars/haproxy/haproxy?style=social&color=white)](https://github.com/haproxy/haproxy/stargazers) | C | Industry-standard high-performance TCP/HTTP proxy & balancer | GPL-2.0 |
| [Spring Cloud Gateway](https://github.com/spring-cloud/spring-cloud-gateway) | [![GitHub stars](https://img.shields.io/github/stars/spring-cloud/spring-cloud-gateway?style=social&color=white)](https://github.com/spring-cloud/spring-cloud-gateway/stargazers) | Java / Spring Boot | Non-blocking reactive API routing layer for Spring microservices | Apache-2.0 |
| [Higress](https://github.com/alibaba/higress) | [![GitHub stars](https://img.shields.io/github/stars/alibaba/higress?style=social&color=white)](https://github.com/alibaba/higress/stargazers) | Go / C++ / Envoy | Cloud-native Gateway API & AI gateway controller | Apache-2.0 |
| [Emissary-Ingress](https://github.com/emissary-ingress/emissary) | [![GitHub stars](https://img.shields.io/github/stars/emissary-ingress/emissary?style=social&color=white)](https://github.com/emissary-ingress/emissary/stargazers) | Go / Python / CNCF | Envoy-based Kubernetes ingress controller & API gateway | Apache-2.0 |
| [Apache ShenYu](https://github.com/apache/shenyu) | [![GitHub stars](https://img.shields.io/github/stars/apache/shenyu?style=social&color=white)](https://github.com/apache/shenyu/stargazers) | Java / ASF | Extensible asynchronous multi-protocol gateway (Dubbo, gRPC) | Apache-2.0 |
| [Contour](https://github.com/projectcontour/contour) | [![GitHub stars](https://img.shields.io/github/stars/projectcontour/contour?style=social&color=white)](https://github.com/projectcontour/contour/stargazers) | Go / CNCF | Ingress controller & dynamic Envoy control plane for Kubernetes | Apache-2.0 |
| [Express Gateway](https://github.com/ExpressGateway/express-gateway) | [![GitHub stars](https://img.shields.io/github/stars/ExpressGateway/express-gateway?style=social&color=white)](https://github.com/ExpressGateway/express-gateway/stargazers) | JavaScript / Node.js | Microservices API gateway built completely on Express.js | Apache-2.0 |
| [Gravitee](https://github.com/gravitee-io/gravitee-api-management) | [![GitHub stars](https://img.shields.io/github/stars/gravitee-io/gravitee-api-management?style=social&color=white)](https://github.com/gravitee-io/gravitee-api-management/stargazers) | Java | Event-native and REST API management platform & gateway | Apache-2.0 core |
| [Envoy Gateway](https://github.com/envoyproxy/gateway) | [![GitHub stars](https://img.shields.io/github/stars/envoyproxy/gateway?style=social&color=white)](https://github.com/envoyproxy/gateway/stargazers) | Go / Envoy / CNCF | Standardized CNCF implementation of Kubernetes Gateway API | Apache-2.0 |
| [Gloo Gateway / kgateway](https://github.com/kgateway-dev/kgateway) | [![GitHub stars](https://img.shields.io/github/stars/kgateway-dev/kgateway?style=social&color=white)](https://github.com/kgateway-dev/kgateway/stargazers) | Go / Envoy | Next-generation Kubernetes Gateway API controller & Envoy proxy | Apache-2.0 |

Apache APISIX, Kong, Envoy and Traefik are among the major open-source gateway choices, with materially different configuration, extension and deployment models.



Apache APISIX is an Apache Software Foundation top-level project built on NGINX and etcd, with dynamic routing and a large plugin ecosystem. Its current project site describes more than 100 open-source plugins and support for Kubernetes, authentication, rate limiting, observability and AI gateway workloads.



---



# 🥇 Apache APISIX



[Apache APISIX](https://github.com/apache/apisix) is one of the strongest fully open-source choices for organizations seeking a high-performance API gateway.



```text

                    Client

                      │

                      ▼

                Apache APISIX

                      │

          ┌───────────┼───────────┐

          ▼           ▼           ▼

       Auth        Routing     Rate Limit

          │           │           │

          └───────────┼───────────┘

                      ▼

                 Upstream

```



Key capabilities include:



* Dynamic routing

* Authentication

* Rate limiting

* Load balancing

* Circuit breaking

* Request transformation

* gRPC

* WebSocket

* OpenID Connect

* Prometheus

* OpenTelemetry

* Kubernetes

* Service discovery

* AI / LLM gateway capabilities



APISIX uses etcd for dynamic configuration and supports hot-loading plugins without gateway restarts.



---



# 🦍 Kong Gateway



[Kong Gateway](https://github.com/Kong/kong) is one of the most mature API gateway ecosystems.



```text

                       Kong Gateway

                            │

        ┌───────────────────┼───────────────────┐

        │                   │                   │

        ▼                   ▼                   ▼

 Authentication        Rate Limiting       Transformations

        │                   │                   │

        └───────────────────┼───────────────────┘

                            ▼

                       Microservices

```



Kong supports:



* DB-backed configuration

* DB-less mode

* Hybrid deployment

* Kubernetes

* Plugins

* Authentication

* Rate limiting

* Observability

* GraphQL

* gRPC

* WebSocket

* AI gateway workloads



Kong and APISIX share an NGINX/LuaJIT heritage, but differ in control-plane architecture, ecosystem and operational models.



> **Licensing note:** Kong's open-source gateway core should be distinguished from Kong's commercial Enterprise/Konnect capabilities and plugins.



---



# 🐍 Tyk Gateway



[Tyk](https://github.com/TykTechnologies/tyk) is a Go-based open-source API gateway with strong API management capabilities.



Key capabilities:



* REST

* GraphQL

* gRPC

* WebSockets

* Authentication

* Rate limiting

* Quotas

* API transformation

* Middleware

* Analytics

* API versioning



The Tyk Gateway is open source, while some broader API-management functionality is provided through licensed components and hosted offerings.



---



# 🌊 Gravitee



[Gravitee](https://github.com/gravitee-io/gravitee-api-management) combines API management with event-driven capabilities.



Useful for:



* REST APIs

* Event APIs

* Kafka

* MQTT

* AsyncAPI

* API policies

* Developer portals

* Authentication

* Analytics



Gravitee's open-source core is Apache-2.0 licensed, while enterprise and cloud capabilities extend the platform.



---



# ☸️ Kubernetes & Cloud-Native API Gateways



Kubernetes has changed the API gateway landscape considerably.



| Project                 | Kubernetes |     Gateway API    | Envoy-Based | Primary Strength         |

| ----------------------- | :--------: | :----------------: | :---------: | ------------------------ |

| Apache APISIX           |      ✅     |          ✅         |      ❌      | High-performance gateway |

| Kong                    |      ✅     |          ✅         |      ❌      | API management           |

| Envoy Gateway           |      ✅     |          ✅         |      ✅      | Kubernetes-native Envoy  |

| Gloo Gateway / kgateway |      ✅     |          ✅         |      ✅      | Envoy + Kubernetes       |

| Traefik                 |      ✅     |          ✅         |      ❌      | Auto-discovery           |

| Gravitee                |      ✅     | Partial / evolving |      ❌      | API + event management   |

| Tyk                     |      ✅     |          ✅         |      ❌      | API management           |

| Higress                 |      ✅     |          ✅         |      ✅      | Cloud-native gateway     |

| KrakenD                 |      ✅     |   Via deployment   |      ❌      | Aggregation              |

| Istio Ingress Gateway   |      ✅     |          ✅         |      ✅      | Service mesh             |

| HAProxy                 |      ✅     |  Via integrations  |      ❌      | High-performance proxy   |



Gateway API is increasingly important for Kubernetes-native gateway deployments, while Envoy functions primarily as a programmable proxy that needs a control plane or gateway layer around it.



---



# ⚡ High-Performance API Gateways



| Project       | Primary Strength                    |

| ------------- | ----------------------------------- |

| Apache APISIX | Dynamic high-performance routing    |

| Envoy         | High-performance programmable proxy |

| HAProxy       | Extremely mature L4/L7 proxy        |

| NGINX         | High-performance reverse proxy      |

| KrakenD       | API aggregation / low overhead      |

| Kong          | High-performance API gateway        |

| Traefik       | Cloud-native routing                |

| Higress       | Cloud-native gateway                |

| Caddy         | Simple high-performance proxy       |



APISIX's current documentation describes a dynamic architecture based on NGINX and etcd, while KrakenD focuses strongly on API aggregation and performance.



---



# 🔀 API Gateway & Reverse Proxy Software



Some projects are not full API-management platforms but are extremely useful gateway building blocks.



| Project                                                          | Role                              |

| ---------------------------------------------------------------- | --------------------------------- |

| [NGINX](https://github.com/nginx/nginx)                          | Reverse proxy / load balancer     |

| [HAProxy](https://github.com/haproxy/haproxy)                    | L4/L7 proxy                       |

| [Caddy](https://github.com/caddyserver/caddy)                    | Modern web server / reverse proxy |

| [Envoy](https://github.com/envoyproxy/envoy)                     | Programmable L4/L7 proxy          |

| [Apache Traffic Server](https://github.com/apache/trafficserver) | Proxy / caching                   |

| [Varnish](https://github.com/varnishcache/varnish-cache)         | HTTP accelerator                  |

| [OpenResty](https://github.com/openresty/openresty)              | NGINX + Lua platform              |



These projects can form the runtime foundation for a custom API gateway.



---



# 🧩 Service Mesh & Programmable Proxies



| Project                                        | Description                            |

| ---------------------------------------------- | -------------------------------------- |

| [Envoy](https://github.com/envoyproxy/envoy)   | Programmable L4/L7 proxy               |

| [Istio](https://github.com/istio/istio)        | Service mesh + traffic management      |

| [Linkerd](https://github.com/linkerd/linkerd2) | Kubernetes service mesh                |

| [Consul](https://github.com/hashicorp/consul)  | Service networking                     |

| [Cilium](https://github.com/cilium/cilium)     | eBPF networking + gateway capabilities |

| [NGINX](https://github.com/nginx/nginx)        | Proxy infrastructure                   |

| [HAProxy](https://github.com/haproxy/haproxy)  | L4/L7 proxy                            |



A useful distinction is:



```text

API Gateway

     │

     └── North-South Traffic



Service Mesh

     │

     └── East-West Traffic

```



A modern platform may use both.



---



# 🔐 Open-Source API Security



API gateways commonly serve as the first enforcement point for API security.



```text

                         Request

                            │

                            ▼

                    ┌──────────────┐

                    │ API Gateway  │

                    └──────┬───────┘

                           │

             ┌─────────────┼─────────────┐

             ▼             ▼             ▼

          API Key         JWT           mTLS

             │             │             │

             └─────────────┼─────────────┘

                           ▼

                    Authorization

                           │

                           ▼

                       Backend

```



Useful open-source security components include:



| Project                                                         | Security Role            |

| --------------------------------------------------------------- | ------------------------ |

| [Keycloak](https://github.com/keycloak/keycloak)                | OAuth2 / OIDC / identity |

| [Open Policy Agent](https://github.com/open-policy-agent/opa)   | Policy engine            |

| [Casbin](https://github.com/casbin/casbin)                      | Authorization            |

| [ModSecurity](https://github.com/owasp-modsecurity/ModSecurity) | WAF engine               |

| [Coraza](https://github.com/corazawaf/coraza)                   | WAF                      |

| [CrowdSec](https://github.com/crowdsecurity/crowdsec)           | Threat detection         |

| [Authelia](https://github.com/authelia/authelia)                | Authentication / SSO     |

| [oauth2-proxy](https://github.com/oauth2-proxy/oauth2-proxy)    | OAuth reverse proxy      |



---



# 🚦 Open-Source Traffic Management



API gateways are frequently used to enforce:



* Rate limits

* Quotas

* Circuit breakers

* Retries

* Timeouts

* Load balancing

* Canary deployments

* Traffic splitting

* Header transformation

* Request transformation

* Caching

* Failover



| Project       | Traffic Management |

| ------------- | ------------------ |

| Apache APISIX | Excellent          |

| Kong          | Excellent          |

| Envoy         | Excellent          |

| Traefik       | Strong             |

| Tyk           | Strong             |

| Gravitee      | Strong             |

| KrakenD       | Strong             |

| HAProxy       | Excellent          |

| NGINX         | Excellent          |

| Caddy         | Good               |



---



# 📊 Open-Source API Gateway Observability



A production gateway should expose:



```text

Requests

Latency

Errors

Status Codes

Traffic

Rate Limits

Upstream Health

Authentication Failures

Consumer Usage

API Versions

```



Recommended open-source stack:



```text

API Gateway

     │

     ├── OpenTelemetry

     │

     ├── Prometheus

     │

     ├── Grafana

     │

     ├── Loki

     │

     └── Tempo / Jaeger

```



| Project                                                                    | Role                |

| -------------------------------------------------------------------------- | ------------------- |

| [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-collector) | Telemetry           |

| [Prometheus](https://github.com/prometheus/prometheus)                     | Metrics             |

| [Grafana](https://github.com/grafana/grafana)                              | Dashboards          |

| [Loki](https://github.com/grafana/loki)                                    | Logs                |

| [Tempo](https://github.com/grafana/tempo)                                  | Traces              |

| [Jaeger](https://github.com/jaegertracing/jaeger)                          | Distributed tracing |

| [ClickHouse](https://github.com/ClickHouse/ClickHouse)                     | Analytics           |



Apache APISIX currently documents integrations with Prometheus, Grafana, OpenTelemetry, Zipkin, SkyWalking, Kafka, ClickHouse and other observability systems.



---



# 🛠️ Open-Source API Gateway Control Planes



A gateway data plane can be separated from its control plane.



```text

                    CONTROL PLANE

                         │

        ┌────────────────┼────────────────┐

        ▼                ▼                ▼

   Configuration     Policies         Certificates

        │                │                │

        └────────────────┼────────────────┘

                         ▼

                    DATA PLANE

                         │

                         ▼

                    API Traffic

```



Useful control-plane technologies include:



| Project           | Role                         |

| ----------------- | ---------------------------- |

| etcd              | Distributed configuration    |

| Kubernetes        | Gateway orchestration        |

| Git               | Declarative configuration    |

| Argo CD           | GitOps                       |

| Flux              | GitOps                       |

| Crossplane        | Infrastructure control plane |

| Backstage         | Developer portal             |

| Open Policy Agent | Policy management            |



---



# 🤖 Open-Source AI Gateways



Modern API gateways increasingly handle AI/LLM traffic.



Important capabilities include:



* LLM routing

* Provider abstraction

* API key management

* Token rate limiting

* Model routing

* Fallback

* Retry

* Cost tracking

* Prompt filtering

* Guardrails

* Model observability

* MCP traffic management



| Project                                                      | AI Gateway Capability         |

| ------------------------------------------------------------ | ----------------------------- |

| [Apache APISIX](https://github.com/apache/apisix)            | AI Gateway / LLM routing      |

| [Kong AI Gateway](https://github.com/Kong/kong)              | LLM traffic management        |

| [LiteLLM](https://github.com/BerriAI/litellm)                | LLM gateway / proxy           |

| [Envoy AI Gateway](https://github.com/envoyproxy/ai-gateway) | Kubernetes / Envoy AI gateway |

| [Portkey Gateway](https://github.com/Portkey-AI/gateway)     | LLM gateway                   |

| [Higress](https://github.com/alibaba/higress)                | AI gateway capabilities       |

| [LLM Gateway](https://github.com/berriai/litellm)            | Unified model API             |

| [Helicone](https://github.com/Helicone/helicone)             | LLM observability / gateway   |



Apache APISIX now explicitly positions its gateway as an AI Gateway capable of routing across multiple LLM providers, load balancing, fallback, token rate limiting, prompt security and MCP traffic.



---



# 🧩 Commercial Platform → Open-Source Equivalent



| Commercial Platform               | Open-Source Equivalent / Building Blocks                |

| --------------------------------- | ------------------------------------------------------- |

| **Kong Konnect**                  | Kong Gateway + Kubernetes + GitOps + Prometheus/Grafana |

| **Google Apigee**                 | Apache APISIX / WSO2 + Backstage + OpenTelemetry        |

| **Tyk**                           | Tyk Gateway + custom control plane / Kubernetes         |

| **Gravitee**                      | Gravitee OSS + Kubernetes + Kafka                       |

| **MuleSoft Anypoint API Manager** | Apache APISIX + Apache Camel + Backstage                |

| **Azure API Management**          | APISIX / Kong + Kubernetes + Keycloak + OPA             |

| **Amazon API Gateway**            | APISIX / Envoy / Kong + Kubernetes                      |

| **IBM API Connect**               | WSO2 API Manager / APISIX + Backstage                   |

| **WSO2 API Manager**              | WSO2 API Manager itself + ecosystem components          |

| **Traefik Hub**                   | Traefik Proxy + Kubernetes + Gateway API                |

| **NGINX API Gateway**             | NGINX / OpenResty + Lua + OPA                           |

| **KrakenD Enterprise**            | KrakenD Community Edition                               |

| **MuleSoft API Gateway**          | APISIX + Apache Camel                                   |

| **Google Apigee X**               | APISIX + OPA + OpenTelemetry + Backstage                |

| **AWS API Gateway**               | Envoy Gateway / APISIX / Kong                           |

| **Enterprise API Gateway**        | APISIX + Keycloak + OPA + Prometheus + Grafana          |

| **Cloud-Native API Gateway**      | Envoy Gateway + Kubernetes Gateway API                  |

| **AI API Gateway**                | APISIX / Envoy AI Gateway + LiteLLM                     |



---



# 🏗️ API Gateway Architecture



The basic architecture is:



```text

                         Internet

                            │

                            ▼

                    ┌───────────────┐

                    │ API Gateway   │

                    └───────┬───────┘

                            │

             ┌──────────────┼──────────────┐

             │              │              │

             ▼              ▼              ▼

         Authentication   Routing      Rate Limit

             │              │              │

             └──────────────┼──────────────┘

                            ▼

                       Load Balancer

                            │

             ┌──────────────┼──────────────┐

             ▼              ▼              ▼

          Service A      Service B      Service C

```



---



# 🔄 Open-Source API Gateway Architecture



```mermaid

flowchart TD



    A[Internet / Clients] --> B[DNS / CDN]



    B --> C[Load Balancer]



    C --> D[API Gateway]



    D --> E[Authentication]

    D --> F[Authorization]

    D --> G[Rate Limiting]

    D --> H[Routing]

    D --> I[Transformation]

    D --> J[Caching]



    H --> K[Service A]

    H --> L[Service B]

    H --> M[Service C]



    D --> N[OpenTelemetry]



    N --> O[Prometheus]

    N --> P[Grafana]

    N --> Q[Jaeger / Tempo]



    D --> R[Control Plane]



    R --> S[etcd / Kubernetes / GitOps]

```



---



# ☸️ Kubernetes API Gateway Architecture



```mermaid

flowchart TB



    A[Internet] --> B[Cloud Load Balancer]



    B --> C[API Gateway]



    C --> D[Gateway API]



    D --> E[Service A]

    D --> F[Service B]

    D --> G[Service C]



    H[Kubernetes API] --> C



    I[GitOps] --> H



    J[Prometheus] --> C

    K[OpenTelemetry] --> C

    L[Grafana] --> J

```



Typical choices:



```text

Kubernetes

     │

     ├── Apache APISIX

     ├── Kong

     ├── Envoy Gateway

     ├── Gloo Gateway

     ├── Traefik

     ├── Tyk

     ├── Higress

     └── Gravitee

```



---



# 🔐 API Security Architecture



```mermaid

flowchart LR



    A[Client] --> B[API Gateway]



    B --> C[TLS]



    C --> D[API Key / OAuth2 / OIDC]



    D --> E[JWT Validation]



    E --> F[OPA / RBAC]



    F --> G[Rate Limiting]



    G --> H[WAF]



    H --> I[Backend Service]

```



A common open-source security stack is:



```text

API Gateway

    +

Keycloak

    +

Open Policy Agent

    +

ModSecurity / Coraza

    +

mTLS

    +

OpenTelemetry

```



---



# 📊 API Gateway Technology Comparison



| Gateway              | Language    | Open Source | Kubernetes |   Dynamic Config   | Plugin / Extension Model | API Management | AI Gateway |

| -------------------- | ----------- | :---------: | :--------: | :----------------: | :----------------------: | :------------: | :--------: |

| Apache APISIX        | Lua / NGINX |      ✅      |      ✅     |          ✅         |         Excellent        |       ⚠️       |      ✅     |

| Kong Gateway         | Lua / NGINX |      ✅*     |      ✅     |          ✅         |         Excellent        |       ✅*       |      ✅     |

| Tyk                  | Go          |      ✅*     |      ✅     |          ✅         |         Excellent        |       ✅*       |     ⚠️     |

| Gravitee             | Java        |      ✅*     |      ✅     |          ✅         |          Strong          |        ✅       |     ⚠️     |

| Traefik              | Go          |      ✅      |      ✅     |          ✅         |        Middleware        |       ⚠️       |     ⚠️     |

| Envoy                | C++         |      ✅      |      ✅     |          ✅         |         Excellent        |        ❌       |     ⚠️     |

| Envoy Gateway        | Go / Envoy  |      ✅      |      ✅     |          ✅         |         Excellent        |       ⚠️       |      ✅     |

| Gloo Gateway         | Go / Envoy  |      ✅*     |      ✅     |          ✅         |         Excellent        |       ✅*       |      ✅     |

| KrakenD CE           | Go          |      ✅      |      ✅     |    Configuration   |          Plugins         |       ⚠️       |     ⚠️     |

| Apache ShenYu        | Java        |      ✅      |      ✅     |          ✅         |          Plugin          |        ✅       |     ⚠️     |

| Higress              | Go / Envoy  |      ✅      |      ✅     |          ✅         |          Plugin          |        ✅       |      ✅     |

| HAProxy              | C           |      ✅      |      ✅     |       Dynamic      |          Modules         |        ❌       |      ❌     |

| NGINX                | C           |      ✅      |      ✅     |    Configuration   |          Modules         |       ⚠️       |     ⚠️     |

| Caddy                | Go          |      ✅      |      ✅     |       Dynamic      |          Modules         |        ❌       |      ❌     |

| Spring Cloud Gateway | Java        |      ✅      |      ✅     | Application-driven |          Filters         |       ⚠️       |      ❌     |

| Istio Gateway        | Envoy       |      ✅      |      ✅     |         xDS        |     Envoy extensions     |       ⚠️       |     ⚠️     |



> `*` indicates that the project has both open-source and commercial/enterprise components. Always check the exact component and license before deployment.



---



# ⚖️ Commercial vs Open-Source



| Capability             | Commercial Gateway | Open-Source Gateway |

| ---------------------- | ------------------ | ------------------- |

| API Routing            | ✅                  | ✅                   |

| Load Balancing         | ✅                  | ✅                   |

| Authentication         | ✅                  | ✅                   |

| OAuth / OIDC           | ✅                  | ✅                   |

| Rate Limiting          | ✅                  | ✅                   |

| API Keys               | ✅                  | ✅                   |

| TLS / mTLS             | ✅                  | ✅                   |

| Request Transformation | ✅                  | ✅                   |

| Caching                | ✅                  | ✅                   |

| Circuit Breaking       | ✅                  | ✅                   |

| Kubernetes             | ✅                  | ✅                   |

| Developer Portal       | ✅                  | Build / integrate   |

| API Analytics          | ✅                  | Build / integrate   |

| API Monetization       | ✅                  | Build / integrate   |

| API Lifecycle          | ✅                  | Build / integrate   |

| Governance             | ✅                  | Build / integrate   |

| Enterprise Support     | ✅                  | Community / vendors |

| Managed Control Plane  | ✅                  | Optional            |

| Self Hosting           | Some               | ✅                   |

| Source Code            | Usually no         | ✅                   |

| Custom Plugins         | Varies             | ✅                   |

| Vendor Lock-In         | Higher             | Lower               |

| Air-Gapped Deployment  | Varies             | ✅                   |

| Cloud Independence     | Lower              | Higher              |

| Operational Burden     | Lower              | Higher              |

| Customization          | Medium             | Very High           |



---



# 🚀 Recommended Open-Source Stacks



## 🏆 1. Best General-Purpose Open-Source Gateway



```text

Apache APISIX

+

etcd

+

Keycloak

+

OpenTelemetry

+

Prometheus

+

Grafana

+

Kubernetes

```



A strong default for organizations prioritizing a fully open-source gateway and dynamic configuration.



---



## 🏢 2. Enterprise API Management



```text

WSO2 API Manager

+

Keycloak

+

PostgreSQL

+

Kubernetes

+

OpenTelemetry

+

Prometheus

+

Grafana

```



WSO2 is particularly interesting when a **full API lifecycle platform** is required rather than only a runtime gateway. Current comparisons describe WSO2 API Manager as a fully open-source API management suite.



---



## ☸️ 3. Kubernetes-Native Gateway



```text

Envoy Gateway

+

Kubernetes Gateway API

+

cert-manager

+

OpenTelemetry

+

Prometheus

+

Grafana

```



Best when the infrastructure is heavily Kubernetes-oriented.



---



## ⚡ 4. High-Performance Gateway



```text

Apache APISIX

+

etcd

+

Kubernetes

+

OpenTelemetry

+

Prometheus

```



APISIX is designed around NGINX and etcd and provides dynamic routing and hot-loaded plugins.



---



## 🐳 5. Simple Containerized Gateway



```text

Traefik

+

Docker / Kubernetes

+

Let's Encrypt

+

Prometheus

+

Grafana

```



A particularly approachable option for container-heavy environments.



---



## 🔥 6. API Aggregation



```text

KrakenD

+

Redis

+

OpenTelemetry

+

Prometheus

+

Kubernetes

```



Useful when a single public API needs to aggregate multiple backend services.



---



## 🧩 7. Full Open-Source API Platform



```text

                 API PLATFORM

                      │

          ┌───────────┼───────────┐

          ▼           ▼           ▼

       APISIX       WSO2       Backstage

          │           │           │

          └───────────┼───────────┘

                      ▼

                  Keycloak

                      │

                      ▼

                    OPA

                      │

                      ▼

               OpenTelemetry

                      │

          ┌───────────┼───────────┐

          ▼           ▼           ▼

     Prometheus     Grafana      Loki

```



---



# 🎯 Recommended Projects by Use Case



| Use Case                           | Recommended Starting Point               |

| ---------------------------------- | ---------------------------------------- |

| Best fully open-source API gateway | **Apache APISIX**                        |

| Mature gateway ecosystem           | **Kong Gateway**                         |

| Go-based API gateway               | **Tyk**                                  |

| API + event management             | **Gravitee**                             |

| Kubernetes Gateway API             | **Envoy Gateway**                        |

| Kubernetes auto-discovery          | **Traefik**                              |

| API aggregation                    | **KrakenD**                              |

| Full API management                | **WSO2 API Manager**                     |

| Envoy-based enterprise gateway     | **Gloo Gateway**                         |

| High-performance proxy             | **HAProxy / NGINX**                      |

| Simple reverse proxy               | **Caddy**                                |

| Dynamic NGINX-based gateway        | **APISIX**                               |

| Java ecosystem                     | **Spring Cloud Gateway**                 |

| Java API management                | **Apache ShenYu / Gravitee**             |

| Event-driven API management        | **Gravitee**                             |

| Service mesh gateway               | **Envoy / Istio**                        |

| AI gateway                         | **APISIX / Envoy AI Gateway / LiteLLM**  |

| API security                       | **APISIX + Keycloak + OPA**              |

| API observability                  | **OpenTelemetry + Prometheus + Grafana** |

| GitOps gateway                     | **APISIX/Kong + Kubernetes + Argo CD**   |

| Fully self-hosted API platform     | **APISIX + Keycloak + OPA + Backstage**  |



---



# 🏢 Building a Kong Alternative



A production-grade Kong-like platform can be assembled from:



```text

                        CLIENTS

                           │

                           ▼

                    Apache APISIX

                           │

          ┌────────────────┼────────────────┐

          ▼                ▼                ▼

      Keycloak            OPA          Rate Limiting

          │                │                │

          └────────────────┼────────────────┘

                           ▼

                     Microservices

                           │

                           ▼

                    OpenTelemetry

                           │

             ┌─────────────┼─────────────┐

             ▼             ▼             ▼

         Prometheus      Grafana        Loki

                           │

                           ▼

                        etcd

```



Potential control plane:



```text

Git

 │

 ▼

Argo CD

 │

 ▼

Kubernetes

 │

 ▼

APISIX

 │

 ▼

API Traffic

```



---



# 🏗️ Building an Apigee Alternative



Apigee includes significantly more than an API proxy, so an open-source equivalent should be thought of as a collection of services.



```text

                 API MANAGEMENT PLATFORM

                           │

        ┌──────────────────┼──────────────────┐

        │                  │                  │

        ▼                  ▼                  ▼

     Gateway          API Lifecycle      Developer Portal

        │                  │                  │

        ▼                  ▼                  ▼

      APISIX            Git / CI          Backstage

        │

        ▼

    Keycloak

        │

        ▼

       OPA

        │

        ▼

 OpenTelemetry

        │

   ┌────┼────┐

   ▼    ▼    ▼

Prom  Grafana Loki

```



Additional components can provide:



```text

API Monetization

      +

API Catalog

      +

Subscriptions

      +

Consumer Management

      +

Analytics

      +

Governance

```



This is one of the key differences between a **gateway replacement** and a **complete API-management replacement**.



---



# 🧱 API Gateway Layers



```text

┌──────────────────────────────────────────────┐

│              DEVELOPER PORTAL                │

│       Documentation • Keys • Catalog         │

└───────────────────────┬──────────────────────┘

                        │

┌───────────────────────▼──────────────────────┐

│              API MANAGEMENT                  │

│ Lifecycle • Policies • Governance • Plans    │

└───────────────────────┬──────────────────────┘

                        │

┌───────────────────────▼──────────────────────┐

│                CONTROL PLANE                 │

│   Config • Discovery • Certificates • GitOps │

└───────────────────────┬──────────────────────┘

                        │

┌───────────────────────▼──────────────────────┐

│                 API GATEWAY                  │

│ Routing • Auth • Rate Limits • Transformation│

└───────────────────────┬──────────────────────┘

                        │

┌───────────────────────▼──────────────────────┐

│                 DATA PLANE                   │

│             Microservices / APIs             │

└──────────────────────────────────────────────┘

```



---



# 🔥 API Gateway vs API Management



| Capability                  | API Gateway | API Management |

| --------------------------- | :---------: | :------------: |

| Request Routing             |      ✅      |        ✅       |

| Load Balancing              |      ✅      |        ✅       |

| Authentication              |      ✅      |        ✅       |

| Rate Limiting               |      ✅      |        ✅       |

| Traffic Transformation      |      ✅      |        ✅       |

| API Policies                |      ✅      |        ✅       |

| API Analytics               |      ⚠️     |        ✅       |

| API Catalog                 |      ❌      |        ✅       |

| Developer Portal            |      ❌      |        ✅       |

| API Lifecycle               |      ❌      |        ✅       |

| API Monetization            |      ❌      |        ✅       |

| API Subscription Management |      ❌      |        ✅       |

| Governance                  |      ⚠️     |        ✅       |

| API Discovery               |      ❌      |        ✅       |

| API Product Management      |      ❌      |        ✅       |



This distinction is important when comparing projects such as APISIX, Envoy or NGINX against Apigee, MuleSoft, WSO2 or Azure API Management. API gateways and API management platforms overlap heavily, but they are not identical categories.



---



# 🌐 Open-Source API Gateway Landscape



```mermaid

mindmap

  root((API Gateway))

    Full API Management

      WSO2

      Gravitee

      Tyk

      Kong

    High Performance

      Apache APISIX

      Kong

      Envoy

      HAProxy

      NGINX

    Kubernetes

      Envoy Gateway

      Gloo Gateway

      Traefik

      APISIX

      Kong

      Tyk

      Higress

    API Aggregation

      KrakenD

      Kong

      APISIX

    Reverse Proxy

      NGINX

      HAProxy

      Caddy

      Envoy

    Service Mesh

      Istio

      Linkerd

      Envoy

      Cilium

    Security

      Keycloak

      OPA

      Casbin

      ModSecurity

      Coraza

    Observability

      OpenTelemetry

      Prometheus

      Grafana

      Loki

      Jaeger

      Tempo

    AI Gateway

      APISIX

      Envoy AI Gateway

      LiteLLM

      Higress

      Kong

```



---



# 🧠 Why Open-Source API Gateways Matter



API gateways become a critical infrastructure layer as organizations move from:



```text

Monolith

   │

   ▼

Microservices

   │

   ▼

Public APIs

   │

   ▼

Partner APIs

   │

   ▼

API Ecosystem

```



Without a gateway, every service may independently implement:



```text

Authentication

Rate Limiting

TLS

Authorization

Logging

Tracing

Retries

Circuit Breaking

Traffic Policies

```



A gateway centralizes those concerns:



```text

                     API Gateway

                          │

       ┌──────────────────┼──────────────────┐

       │                  │                  │

       ▼                  ▼                  ▼

 Authentication       Traffic            Observability

       │              Management               │

       ▼                  ▼                    ▼

   Keycloak          Rate Limit          OpenTelemetry

   OAuth2            Routing             Prometheus

   OIDC              Retries              Grafana

   JWT               Caching              Loki

```



Open-source gateways therefore allow organizations to own a strategically important infrastructure layer rather than making every service independently implement edge concerns.



---



# 🏆 Suggested Open-Source Reference Architecture



For a modern enterprise:



```text

                        INTERNET

                           │

                           ▼

                     Cloud / CDN

                           │

                           ▼

                   Apache APISIX

                           │

          ┌────────────────┼────────────────┐

          │                │                │

          ▼                ▼                ▼

      Keycloak            OPA          Rate Limiting

          │                │                │

          └────────────────┼────────────────┘

                           ▼

                     Kubernetes

                           │

            ┌──────────────┼──────────────┐

            ▼              ▼              ▼

        Service A      Service B      Service C

                           │

                           ▼

                    OpenTelemetry

                           │

          ┌────────────────┼────────────────┐

          ▼                ▼                ▼

     Prometheus          Grafana           Loki

```



Recommended additions:



```text

API Gateway       → Apache APISIX

Identity          → Keycloak

Authorization     → Open Policy Agent

Orchestration     → Kubernetes

GitOps            → Argo CD

Metrics           → Prometheus

Dashboards        → Grafana

Logs              → Loki

Tracing           → Tempo / Jaeger

Telemetry         → OpenTelemetry

Secrets           → HashiCorp Vault

Developer Portal  → Backstage

Policy            → OPA

```



---



# 🧩 Commercial Gateway → OSS Stack



```text

Kong Konnect

      │

      ▼

Kong Gateway / APISIX

+

Kubernetes

+

GitOps

+

OpenTelemetry





Google Apigee

      │

      ▼

APISIX / WSO2

+

Keycloak

+

OPA

+

Backstage

+

OpenTelemetry





AWS API Gateway

      │

      ▼

Envoy Gateway / APISIX

+

Kubernetes

+

Prometheus





Azure API Management

      │

      ▼

APISIX

+

Keycloak

+

OPA

+

Backstage





MuleSoft

      │

      ▼

APISIX

+

Apache Camel

+

Backstage

+

OpenTelemetry





Traefik Hub

      │

      ▼

Traefik Proxy

+

Kubernetes Gateway API

+

Prometheus





NGINX API Gateway

      │

      ▼

NGINX / OpenResty

+

Lua

+

OPA

+

Keycloak





KrakenD Enterprise

      │

      ▼

KrakenD Community Edition

+

Kubernetes

+

OpenTelemetry

```



---



# 🚀 Minimal Self-Hosted API Gateway



For a simple production-oriented starting point:



```text

Apache APISIX

+

etcd

+

Keycloak

+

Prometheus

+

Grafana

+

OpenTelemetry

+

Kubernetes

```



For a more complete API-management platform:



```text

Apache APISIX

+

Keycloak

+

OPA

+

Backstage

+

Kubernetes

+

Argo CD

+

OpenTelemetry

+

Prometheus

+

Grafana

+

Loki

```



For a Kubernetes-first platform:



```text

Envoy Gateway

+

Gateway API

+

cert-manager

+

Keycloak

+

OpenTelemetry

+

Prometheus

+

Grafana

```



---



# 🤝 Contributing



Contributions are welcome!



Please consider adding:



* Open-source API gateways

* Kubernetes API gateways

* Gateway API implementations

* API management platforms

* Reverse proxies

* Service mesh gateways

* API security projects

* Authentication integrations

* Authorization engines

* WAFs

* Rate-limiting systems

* API observability tools

* API analytics systems

* Developer portals

* API lifecycle tools

* API policy engines

* API aggregation systems

* AI gateways

* LLM gateways

* Gateway plugins

* Gateway benchmarking tools

* GitOps integrations



When adding a project, please distinguish between:



* **Fully open-source**

* **Open-core**

* **Source available**

* **Commercial gateway with OSS components**

* **Hosted service**

* **Open-source gateway with proprietary control plane**



Do not classify a proprietary API management platform as open source merely because it uses an open-source proxy or exposes an API.



---



# ⚠️ Disclaimer



This repository is an independent technical curation and is **not affiliated with or endorsed by any company or project listed here**.



API gateway capabilities, licensing and product packaging change frequently.



A project may have:



* An open-source gateway

* A proprietary control plane

* Commercial plugins

* Enterprise-only features

* Hosted functionality

* Separate licensing for certain modules



Always verify the current license and the exact component being deployed before commercial use.



Performance comparisons are also highly workload-dependent. Gateway performance can vary according to:



* Request size

* TLS configuration

* Authentication

* Number of plugins

* Logging

* Observability

* Rate limiting

* Upstream latency

* Protocol

* Hardware

* Kubernetes configuration

* Network topology

* Configuration storage



Therefore, benchmark gateways using your **actual workload and deployment topology** rather than relying exclusively on published benchmarks.



---

# ❓ Frequently Asked Questions (FAQ)

### 📌 What is an API Gateway and why do I need one in a microservices architecture?
An **API Gateway** acts as the single entry point (reverse proxy) for all incoming client traffic into a backend microservices system. Instead of clients directly calling dozens of decoupled services, the gateway manages cross-cutting concerns such as request routing, SSL/TLS termination, authentication (JWT, OAuth2, API Keys), rate limiting, traffic shadowing, and protocol mediation (e.g. REST to gRPC). This centralizes security, reduces backend complexity, and protects upstream services from traffic surges and malicious requests.

### ⚖️ What is the difference between an API Gateway and a Service Mesh?
* **API Gateway (North-South Traffic):** Manages requests flowing into your infrastructure from external consumers, web browsers, mobile apps, and third-party partners. It emphasizes edge security, API monetization, authentication, rate limits, and developer portals.
* **Service Mesh (East-West Traffic):** Manages communication between internal services within the private network or Kubernetes cluster (e.g., Service A talking to Service B). It focuses on service discovery, mTLS mutual encryption, circuit breaking, observability, and fine-grained traffic shifting (e.g., Istio, Linkerd).

### 🚀 When should I choose an Open-Source API Gateway over a Managed SaaS Gateway?
* **Choose Open-Source (APISIX, Kong Gateway OSS, Envoy, Traefik, Caddy):** When you require zero vendor lock-in, low egress/runtime latency, complete on-prem or multi-cloud deployment autonomy, compliance with strict data residency regulations, and no per-call or per-seat licensing fees.
* **Choose Managed SaaS (Kong Konnect, Google Apigee, AWS API Gateway, Azure APIM):** When your team lacks dedicated infrastructure/DevOps engineers to operate 24/7 gateway clusters, or when you require turnkey developer portals, built-in global billing/monetization, and out-of-the-box cloud ecosystem integrations.

### ☸️ How does the Kubernetes Gateway API differ from the traditional Ingress API?
The standard Kubernetes `Ingress` resource suffered from fragmentation, requiring dozens of vendor-specific annotations for basic features like URL rewrites, canary weighting, and header matching. The **Kubernetes Gateway API** is a modern, expressive, role-oriented standard that decouples infrastructure provisioning (`GatewayClass`), gateway deployment (`Gateway`), and application routing (`HTTPRoute`, `GRPCRoute`, `TCPRoute`). It is natively supported by Envoy Gateway, Traefik, Kong, APISIX, Cilium, and Higress.

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-API-Gateway&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-API-Gateway&type=date&legend=top-left)

---

## ⭐ Star This Repository

If you find this curated API Gateway landscape guide helpful, consider giving this repository a ⭐ **Star** on GitHub and sharing it with colleagues!

Contributions, corrections, and new project submissions are always welcome. Please see [Contributing](#-contributing) to submit a pull request.

---

**Last updated: September 2026**

