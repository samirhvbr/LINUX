# LINUX

## 🔄 Antes de comecar: `git pull`

**SEMPRE** verifique atualizacoes remotas antes de escrever ou alterar qualquer coisa neste repositorio:

```bash
git pull          # ja esta pre-autorizado (allow)
```

Trabalhar sobre uma base desatualizada gera conflitos. Puxe primeiro, sempre. Para so inspecionar antes: `git fetch && git status`.

## Pontos criticos

- **Versao:** `version.md` e a versao do nosso trabalho (hoje `0.0.2`); `__version__=1.2.15` (em `shvterm/__init__.py`) e a base do fork upstream — congelado para rastrear merges. Detalhes em [AGENTS.md](AGENTS.md).
- **Commits (OBRIGATORIO, sempre):** formato `versao - comentario` (ex.: `0.0.3 - Adiciona flag --json ao comando host list`). A versao vem do `version.md`; faca o bump **no mesmo commit** da mudanca. Mensagem **em portugues**, descritiva o suficiente para pesquisa futura. Nunca use a linhagem congelada `1.2.x`. Detalhes em [AGENTS.md](AGENTS.md#34-formato-do-commit).

