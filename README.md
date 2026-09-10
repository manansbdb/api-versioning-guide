# API Versioning Guide / Guia de Versionamento de APIs

Practical notes on API versioning strategies.

Notas práticas sobre estratégias de versionamento de APIs.

## English

### Common strategies
1. **URI path** — `/v1/users` (explicit, cache-friendly)
2. **Header** — `Accept: application/vnd.example.v1+json`
3. **Query** — `/users?version=1` (easy, less clean)

### Recommendations
- Prefer path versioning for public HTTP APIs.
- Keep backward-compatible changes unversioned when possible.
- Publish a deprecation policy (sunset date + migration notes).

## Português

### Estratégias comuns
1. **Caminho URI** — `/v1/users` (explícito, amigo de cache)
2. **Header** — `Accept: application/vnd.example.v1+json`
3. **Query** — `/users?version=1` (fácil, menos limpo)

### Recomendações
- Prefira versionamento por path em APIs HTTP públicas.
- Mantenha mudanças retrocompatíveis sem nova versão quando possível.
- Publique política de depreciação (data de sunset + notas de migração).

## Files / Ficheiros
- `strategies.md` — comparison / comparação
- `deprecation-policy.md` — sample policy / política de exemplo

## License / Licença
MIT © 2026 manansbdb

## Support / Apoio
See [SUPPORT.md](SUPPORT.md).
