# Use Both â€” Claude + Codex Workflow Kit

**ðŸ‡§ðŸ‡· [PortuguÃªs](README.md) Â· ðŸ‡ºðŸ‡¸ [English](README.en.md) Â· ðŸ‡ªðŸ‡¸ [EspaÃ±ol](README.es.md)**

[![Use Both](guia/assets/banner.jpg)](https://inematds.github.io/use-both-claude-codex/guia/)

**Planeje com um. Desafie com o outro. Mantenha o projeto andando.**

Kit gratuito para usar Claude e Codex juntos: seis fluxos, prompts prontos, templates, um guia em PDF e duas skills (`handoff` e `prime`) para trocar de assistente sem reexplicar o projeto.

## ðŸ“– Guia de uso

Guia completo (landing + passo a passo): **https://inematds.github.io/use-both-claude-codex/guia/**

## Origem e licenÃ§a

Este repositÃ³rio espelha o kit **Use Both: Claude + Codex Workflow Kit v1.0.0**, de Prompt Advisers (Mark Kashef), publicado sob licenÃ§a MIT em
[earlyaidopters/gumroad-resources](https://github.com/earlyaidopters/gumroad-resources/tree/main/resources/use-both-claude-codex-workflow-kit) (commit `860b383`, baixado em 27/09/2026).
O INEMA acrescentou o guia trilÃ­ngue (`guia/`), a capa (`capa/`) e os READMEs em PT e ES. Os documentos do kit (`GUIDE.md`, `PROMPTS.md`, `START-HERE.md`, `docs/`, `skills/`, `templates/`) estÃ£o no original em **inglÃªs**. Veja [LICENSE](LICENSE) e [ASSET-NOTICE.md](ASSET-NOTICE.md).

## Os seis nÃ­veis

1. **Deixe discutirem:** um assistente escreve, o outro critica o mesmo artefato. No mÃ¡ximo duas rodadas.
2. **Gerar imagem:** sÃ³ com a ferramenta disponÃ­vel na sessÃ£o e sabendo como ela cobra; o entregÃ¡vel Ã© o arquivo.
3. **Dividir o trabalho:** um constrÃ³i numa branch, o outro revisa o diff. Testes e sua aprovaÃ§Ã£o decidem.
4. **Computer use supervisionado:** senha, pagamento e envios com consequÃªncia ficam com vocÃª.
5. **Linha de chegada:** meta mensurÃ¡vel e condiÃ§Ã£o de parada.
6. **Handoff:** o estado vai para um arquivo portÃ¡til, e o prÃ³ximo assistente lÃª e confere antes de continuar.

## ComeÃ§o rÃ¡pido

```bash
python3 -m unittest discover -s tests -v
python3 examples/task-board/test_task_board.py

# prÃ©via (nada muda) e depois aplicar num projeto seu
python3 scripts/install_skills.py --project /caminho/do/projeto --target both
python3 scripts/install_skills.py --project /caminho/do/projeto --target both --apply
```

No Claude Code: `/handoff` no fim da sessÃ£o e `/prime` na prÃ³xima. No Codex: `$handoff` e `$prime`.

## O vÃ­deo

Resumo do vÃ­deo "Use Both" e o que ele acrescenta ao kit (conexÃ£o por CLI, custo do `/goal`, imagem pela assinatura do Codex, onde seguimos o kit e nÃ£o o vÃ­deo): [docs/RESUMO-VIDEO.md](docs/RESUMO-VIDEO.md).

## Relacionados no INEMA

- [agente-claude-codex](https://inematds.github.io/agente-claude-codex/guia/): migrar do Claude para o Codex ou ficar agnÃ³stico
- [Curso Claude â†’ Codex](https://inematds.github.io/curso-claude-codex/)
- [Ãrea Codex + Claude no INEMA Eventos](https://eventos.inema.pro/claude-codex/)

Material educacional independente, sem vÃ­nculo com a OpenAI nem com a Anthropic.

---

Projeto adaptado da comunidade INEMA TDS - Marca Arckhe