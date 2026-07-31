---
"@vinext/cloudflare": patch
"create-vinext-app": patch
"vinext": patch
---

- fix(app-router): honor cacheLife stale on the client router (#2708)
- fix(create-vinext-app): generate next env on first run (#2768)
- fix(server): evaluate lazy route modules outside the request context (#2740)
- fix(app-router): reject Route Handlers as interception source routes (#2732)
- fix(pages-router): stream piped API responses with backpressure (#2735)
- fix(router): minimize client rewrite manifests (#2734)
- fix(build): exclude filtered require.context modules (#2736)
- fix(server): transfer request bodies into NextRequest instead of teeing (#2741)
- fix(middleware): preserve headers for empty override value (#2767)
- fix(middleware): stop restoring credentials middleware deleted before external rewrites (#2739)
- fix(cache): bypass shared "use cache" entries in draft mode (#2744)
- fix(app-router): preserve page result render ordering (#2760)
- fix(pages): refresh next/head tags when regenerating ISR HTML (#2729)
- fix(document): HTML-escape NextScript.getInlineScriptSource output (#2727)
- fix(app-router): render pages before consuming layouts (#2751)
- fix(build): recognize Vite dist client aliases (#2750)
- fix(server): support Node production entry contracts (#2749)
- fix(build): support dynamic package subpath imports (#2746)
- fix(server): reject unsupported static asset methods (#2714)
- fix(build): skip unhelpful precompressed variants (#2712)
- fix(navigation): reuse router.prefetch payloads during navigation (#2709)
- fix(server): honor static freshness validators (#2715)
- fix(server): use weak comparison for If-None-Match (#2710)
- fix(server): serve static assets with standard MIME types (#2713)
- fix(metadata): preserve Content-Length for fully buffered responses (#2703)
- fix(image): match Next.js 16 default image sizes (#2704)
