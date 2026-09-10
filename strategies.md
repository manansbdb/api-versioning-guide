# Versioning Strategies / Estratégias de Versionamento

## English

| Strategy | Pros | Cons |
|----------|------|------|
| Path `/v1` | Clear, easy routing | URL churn on major bumps |
| Header | Clean URLs | Harder to test in browser |
| Query | Simple to adopt | Easy to forget; weak caching |

**Breaking change examples:** removing fields, changing types, renaming endpoints.
**Non-breaking:** adding optional fields, new endpoints, additive enums.

## Português

| Estratégia | Prós | Contras |
|------------|------|---------|
| Path `/v1` | Claro, routing fácil | URLs mudam em majors |
| Header | URLs limpos | Mais difícil testar no browser |
| Query | Simples de adotar | Fácil esquecer; cache fraco |

**Exemplos breaking:** remover campos, mudar tipos, renomear endpoints.
**Não-breaking:** campos opcionais, novos endpoints, enums aditivos.
