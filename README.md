# IPSEC Consultoria e Tecnologia — Landing Page

Landing page institucional da iniciativa de portfólio de capacidades (Rodrigo, Carlos e
terceiro sócio). **O nome "IPSEC Consultoria e Tecnologia" é temporário.**

Publicação temporária (com `noindex`): https://rodrigoimmaginario.github.io/ipsec-site/

## Objetivo

Vender consultoria e produtos para empresas do ES, com linguagem de autoridade,
competência e experiência — e uma oferta de entrada clara.

## Estrutura (v2)

1. **Hero** — headline centrada na oferta de entrada + mockup de relatório executivo
   (rotulado como exemplo ilustrativo)
2. **Barra de prova** — 30+ anos · 2 décadas de reconhecimentos Microsoft · CISSP · 3 produtos
3. **Faixa de especialidades** — texto (sem logos oficiais Microsoft — ver decisões)
4. **Citação** — recomendação pública de Principal TPM da Microsoft (só cargo, sem nome)
5. **Diagnóstico Executivo de Ambiente** — oferta de entrada: 4 etapas + entregáveis
6. **Consultoria em 3 frentes** — Segurança e redes · Nuvem, M365 e custos · IA com governança
7. **Jornada de IA** — com tela real do ShadowAIGuard (custo de IA)
8. **Produtos** — telas reais + links: RansomGuard, ShadowAIGuard, Pulso (acesso antecipado)
9. **Quem somos** — 3 sócios por função (sem nomes e sem fotos) + credenciais
10. **Artigos** — 4 destaques + 4 arquivo, todos no LinkedIn
11. **Contato** — CTA "Solicitar diagnóstico" (mailto placeholder) + CTA fixo no mobile

## Decisões

- **Sem foto do Rodrigo** — decisão dele; não reabrir.
- **Sem cases Microsoft (2005–2015)** — removidos por serem antigos; podem sugerir
  experiência datada.
- **Sem logos oficiais Microsoft/MVP/RD** — diretrizes de marca e títulos de períodos já
  encerrados; usar apenas texto.
- **Telas de produto** — somente imagens já publicadas nos sites públicos dos produtos.
  O relatório do Pulso não foi usado porque mostra domínio e URLs que aparentam ser reais.
- Tipografia Inter (corpo) + Sora (títulos) via Google Fonts, com fallback de sistema.
- Acento âmbar exclusivo para CTAs.

## Pendências (dependem dos sócios)

- [ ] **Oferta de entrada**: confirmar nome, prazo, entregáveis, gratuito ou pago
- [ ] E-mail real e **número de WhatsApp** (consenso dos 4 modelos consultados: prioritário)
- [ ] Calendly ou equivalente para agendamento
- [ ] Nomes dos sócios: exibir ou não
- [ ] Isca digital (ex.: checklist de riscos em Azure/M365/IA)
- [ ] Analytics (GA4 ou Plausible)
- [ ] Nome definitivo, domínio e remoção do `noindex`

## Consultas

Notas de consulta a modelos externos ficam em `docs/consultas/` — **local apenas, no
`.gitignore`** (repositório é público).

## Técnica

HTML/CSS estático, sem JavaScript. Imagens em `assets/shots/` (WebP). Responsivo,
verificado em 1440px e 390px sem overflow horizontal.
