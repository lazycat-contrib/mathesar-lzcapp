# mathesar-lzcapp

Mathesar for LazyCat — community package.

- upstream: https://github.com/mathesar-foundation/mathesar (GPL-3.0)
- images: `mathesar/mathesar`, `mathesar/mathesar-caddy`, `library/postgres`
- three containers: app (Django, 8000) + PostgreSQL 17 + Caddy front (80)
- first visit runs the installer wizard to create the admin account -> `public_path`
