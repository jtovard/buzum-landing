# buzum-landing

Landing page para `buzum.io` y `buzum.net` — single-file HTML servido como Cloudflare Workers Static Assets.

## Estructura

```
.
├── public/
│   └── index.html       ← landing
├── wrangler.toml        ← config workers static assets
└── README.md
```

## Deploy

Conectado a Cloudflare Workers vía GitHub. Cada push a `main` re-deploya automáticamente.

Deploy manual desde local:

```bash
npx wrangler deploy
```

(requiere autenticación previa: `npx wrangler login`)
