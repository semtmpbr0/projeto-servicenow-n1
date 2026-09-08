# Projeto ServiceNow N1

Sistema de Gestão de Chamados com categorização automática, SLA visual 
e dashboard de performance — inspirado no dia a dia de um Analista de 
Suporte N1.

## 🎯 Objetivo
Simular, na ServiceNow, uma solução para duas dores reais do dia a dia de 
suporte N1: a categorização manual lenta/inconsistente dos chamados e o 
retrabalho gerado quando eles são direcionados ao grupo errado. O projeto 
implementa categorização e atribuição automáticas, com SLA visual e um 
dashboard de performance, para tornar a triagem mais rápida e confiável.

## 🗺️ Roadmap
- [x] Fase 0 — Preparação
- [x] Fase 1 — Escopo e modelagem do problema
- [ ] Fase 2 — Modelagem de dados
- [ ] Fase 3 — Automação de categorização
- [ ] Fase 4 — SLA visual
- [ ] Fase 5 — Dashboard de performance
- [ ] Fase 6 — Portal simplificado (opcional)
- [ ] Fase 7 — Documentação e publicação

## 📁 Estrutura do repositório
- `assets/` — prints e gravações de cada fase
- `docs/` — anotações e decisões técnicas por fase

## 📝 Diário de bordo
### Fase 0 — Preparação
- PDI criada em developer.servicenow.com
- Versão utilizada: [Zurich]
### Fase 1 — Escopo e Modelagem do Problema
- Objetivo definido: reduzir tempo/inconsistência da triagem manual e eliminar 
  retrabalho por chamados mal direcionados
- Problema identificado a partir da vivência real como Analista N1: categorização 
  manual lenta/inconsistente, que gera retrabalho quando o chamado vai pro grupo errado
- Personas mapeadas: Analista N1, Grupo especializado, Gestor/Coordenador, Usuário final
- Fluxo simplificado desenhado (abertura → categorização → atribuição → resolução)
- Detalhamento completo em [`docs/0-fase-1-escopo.md`](./docs/0-fase-1-escopo.md)
- Observação: no primeiro commit os arquivos .md subiram em branco por esquecimento 
  de salvar — corrigido em commit seguinte
