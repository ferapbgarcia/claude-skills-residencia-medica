# 🩺 Claude Skills — Residência Médica

Skills interativas de casos clínicos para preparação para **residência médica brasileira**.
Desenvolvidas para o Claude (claude.ai) com suporte a slash commands.

## Skills disponíveis

| Arquivo | Área | Comandos |
|---|---|---|
| `caso-clinica-medica.zip` | Clínica Médica | `/caso-clinica` + 13 subespecialidades |
| `caso-cirurgia.zip` | Cirurgia | `/caso-cirurgia` + 11 subespecialidades |
| `caso-go.zip` | Ginecologia e Obstetrícia | `/caso-go` + 10 subespecialidades |
| `caso-pediatria.zip` | Pediatria | `/caso-pediatria` + 12 subespecialidades |
| `caso-preventiva.zip` | Medicina Preventiva | `/caso-preventiva` + 10 formatos |
| `caso-clinico-neurologia.zip` | Neurologia | `/caso-clinico` + 9 subespecialidades |

## Como instalar

1. Baixe o ZIP na aba [Releases](../../releases)
2. No Claude: **Customize → Skills → "+" → "Upload a skill"**
3. Ative o toggle da skill instalada
4. Use os comandos listados em [BIBLIOTECA.md](BIBLIOTECA.md)

## Formato dos casos

Cada caso segue **3 etapas progressivas** que aguardam sua resposta antes de continuar:
- **Etapa 1** — Apresentação clínica + exame físico → você pede exames
- **Etapa 2** — Resultados dos exames → você dá diagnóstico e conduta
- **Etapa 3** — Gabarito com nota (0–10), discussão e referências atualizadas

## Licença

MIT — livre para usar, modificar e compartilhar.
