```
o ══════════════════════════════════════════════════════════════════ o
o                                                                    o
o    ENRIQUE RIOS CHYRNIA                                            o
o    Backend · APIs & Integration · Cloud systems                    o
o                                                                    o
o    JOB   PROFILE.PRT              USER   E.CHYRNIA                 o
o    AREA  BACKEND · CLOUD          FROM   ASUNCIÓN, PARAGUAY        o
o                                                                    o
o ══════════════════════════════════════════════════════════════════ o
```

I write backend for web systems in Java and Spring Boot: REST APIs, PostgreSQL,
integrations with external services, and getting things deployed and running in
the cloud. I work API-first — contract first, code second — and I write down
technical decisions with their trade-offs.

Since January 2026 I've been in charge of backend and technical infrastructure
at a private company in the digital services industry: an operational platform
with apps for users, providers and an internal team.

### Why this profile looks emptier than my work

The systems I'd want you to look at are private. Two are my own products still
in development, and my day job belongs to my employer. So instead of pushing
code I can't publish, I documented the engineering — the decisions, the
trade-offs, and how each defense was actually tested.

**→ [portfolio.fil-grama.com](https://portfolio.fil-grama.com)**

```
o ────────────────────────────────────────────────────────────────── o
o   CASE                           STATUS  WHERE IT STANDS           o
o ────────────────────────────────────────────────────────────────── o
o   Ryguasu ...................... [ OK ]  backend in production     o
o   Fil-Grama .................... [PEND]  in development            o
o   Work experience .............. [ OK ]  anonymized case study     o
o ────────────────────────────────────────────────────────────────── o
```

**[Ryguasu](https://portfolio.fil-grama.com/ryguasu)** — multi-tenant SaaS for
inventory, sales and point of sale, for small retail in Paraguay. Tenant
isolation with PostgreSQL Row Level Security that fails closed (42/42 adversarial
endpoints return 403), encrypted backups with a restore verified against real
data, and 49 technical decisions written down with their reasoning. The page is
seven threat→defense cards — including the four iterations it took me to get a
backup I'd actually trust.

**[Fil-Grama](https://portfolio.fil-grama.com/fil-grama-report)** — social media
analytics for agencies. The networks only return about a month of account
metrics, so a daily job saves that history into its own database before it's
gone. TikTok and Meta integrations, 167+ tests, Java backend and React frontend.

**[Work experience](https://portfolio.fil-grama.com/experiencia-backend-plataforma)**
— backend and cloud infrastructure, provider registration with identity checks,
and the internal review panel. Presented anonymized: no names, no code, no real
topology.

### Stack

```
Backend .......... Java · Spring Boot · REST APIs · OpenAPI
Data ............. PostgreSQL · PostGIS (geo) · Flyway · Redis (cache)
Cloud ............ AWS (at work) · Fly.io · Vultr VPS · Cloudflare Pages/R2
Infra ............ Docker · Terraform · Caddy · CI/CD · encrypted backups
Testing .......... JUnit · Testcontainers against a real Postgres
Practices ........ API-first · written decisions · signed webhooks
```

Three systems on three different providers: AWS at work, Fly.io for Ryguasu, a
Vultr VPS for Fil-Grama. I provisioned the last two myself and I pay their bills
— around USD 50 a month for Ryguasu, which is part of why the architecture looks
the way it does.

I'm still studying computer engineering. What I know comes from building and
running real systems, and from the ones that broke first.

```
o ══════════════════════════════════════════════════════════════════ o
o               *** *** ***   END OF JOB   *** *** ***               o
o ══════════════════════════════════════════════════════════════════ o
```

📫 www.enririos@gmail.com · [LinkedIn](https://www.linkedin.com/in/enrique-rios4/) · [portfolio.fil-grama.com](https://portfolio.fil-grama.com)
