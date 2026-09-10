<p align="center">
  <img src="docs/banner.svg" alt="API Versioning Guide banner" width="100%" />
</p>

<h1 align="center">api-versioning-guide</h1>

<p align="center">
  <strong>EN</strong> Strategies & deprecation notes for versioning HTTP APIs<br/>
  <strong>PT</strong> Estratégias e notas de depreciação para versionar APIs HTTP
</p>

<p align="center">
  <a href="https://github.com/manansbdb/api-versioning-guide/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/topic-API-0ea5e9?style=for-the-badge" alt="API" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| Notes on **API versioning strategies** (URI, header, media type) and a deprecation policy sketch. | Notas sobre **estratégias de versionamento de APIs** (URI, header, media type) e esboço de política de depreciação. |
| Copy into your docs folder when designing public APIs. | Copia para a pasta de docs ao desenhar APIs públicas. |

```mermaid
flowchart LR
  A["📌 Choose strategy"] --> B["📄 strategies.md"]
  B --> C["⏳ deprecation-policy.md"]
  C --> D["🚀 Stable public API"]
  style A fill:#0284c7,stroke:#0369a1,color:#fff
  style B fill:#6366f1,stroke:#4338ca,color:#fff
  style C fill:#f59e0b,stroke:#b45309,color:#fff
  style D fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/api-versioning-guide.git
cd api-versioning-guide
```

### 2) Copy into your docs / Copia para a documentação

```bash
mkdir -p docs/api
cp strategies.md docs/api/versioning-strategies.md
cp deprecation-policy.md docs/api/deprecation-policy.md
```

### Requirements / Requisitos

- `git`
- Markdown-friendly docs site (optional)

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/api-versioning-guide.git
cd api-versioning-guide
# read strategies.md → pick URI vs header → adapt deprecation-policy.md
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `strategies.md` | Versioning approaches |
| `deprecation-policy.md` | Sunset / deprecation notes |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
api-versioning-guide/
├── docs/banner.svg
├── strategies.md
├── deprecation-policy.md
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
