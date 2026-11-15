# Currículo Aprovado - Skill de currículo para IA

Uma skill que ensina a IA (Claude, ChatGPT, Gemini e outras) a escrever currículos em português no padrão **Currículo Aprovado**: uma coluna, sem foto, atividades no formato STAR com números e as palavras-chave da vaga escritas exatamente como no anúncio, para passar nos filtros ATS (Gupy, Workday, LinkedIn e afins) e chamar a atenção do recrutador.

Criada por **Joseph Santos**, especialista em recrutamento e seleção.

## O que a skill faz

1. Pede seu currículo atual e a vaga que você quer.
2. Faz um diagnóstico em 4 pontos: objetivo, experiências, competências e formação.
3. Extrai as palavras-chave da vaga.
4. Reescreve o currículo no padrão (resumo, habilidades, experiência, formação, idiomas, certificações).
5. Ajusta a linguagem ao seu nível: estágio, júnior, pleno ou sênior.
6. Entrega o texto pronto, a lista de palavras-chave usadas e o que você precisa confirmar.

**Ela nunca inventa experiência, número ou resultado.** Quando falta informação, ela pergunta ou marca o trecho entre [colchetes].

## Como usar

### Claude Code
Baixe esta pasta para dentro de `~/.claude/skills/`:
```bash
git clone https://github.com/joseeph-cv/curriculo-aprovado-skill ~/.claude/skills/curriculo-aprovado
```
Depois é só pedir: *"Adapta meu currículo para esta vaga"* e colar o currículo e o anúncio.

### Claude.ai (site ou app)
Em **Configurações > Capacidades > Skills**, envie esta pasta compactada em `.zip`.

### ChatGPT, Gemini e outras IAs
Abra o arquivo [SKILL.md](SKILL.md), copie todo o conteúdo e cole como instrução (nas instruções personalizadas, em um GPT/Gem próprio ou no começo da conversa). Depois envie seu currículo e a vaga.

## Arquivos

| Arquivo | Para que serve |
|---|---|
| [SKILL.md](SKILL.md) | As instruções da skill (o "cérebro") |
| [docs/FORMATACAO_WORD.md](docs/FORMATACAO_WORD.md) | Como formatar o currículo no Word |

## Privacidade

Currículos têm dados pessoais. Antes de colar o seu em qualquer IA, confira a política de privacidade da ferramenta. Se preferir, troque telefone e e-mail por dados fictícios e coloque os reais só no arquivo final.

## Licença

[MIT](LICENSE): use, adapte e compartilhe à vontade, mantendo o crédito.
