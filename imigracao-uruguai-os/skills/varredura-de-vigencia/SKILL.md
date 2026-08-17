---
name: varredura-de-vigencia
description: "GATE 1 — relê IMPO + página DNM/CORE/DNIC no dia e devolve data + conflito. Frentes 👤💼⚖️. Travas T2,T7. Uruguai — Ley 18.250 + DNM/Interior + Decreto 45/023. Zero número operacional hardcoded; URL oficial + data. Use em: vigência, atualizou, IMPO, DNM, Decreto 45/023."
---

> **🖱️ Escolhas = botões:** nas listas fechadas use **AskUserQuestion** (máx. 4 opções; se houver mais, divida).

# VARREDURA DE VIGENCIA

> **Camada C1** · Frentes: 👤 imigrante · 💼 comercial · ⚖️ advogado  
> Plugin: `imigracao-uruguai-os` · Régua: `context/anexo-travas-uruguai.md` (7 travas)

## Papel
GATE 1 — relê IMPO + página DNM/CORE/DNIC no dia e devolve data + conflito

## Anexos
`context/anexo-travas-uruguai.md`, `context/anexo-lei-migracao-e-regulamento.md`

## Travas aplicáveis
- **T2:** Desde **17/02/2023** a residência permanente MERCOSUL/vínculo é do **Interior/DNM**, não do MRREE. Consulado recebe/remete; não decide.
- **T7:** Prazo legal (art. 33) **não é SLA**. Silêncio ≠ aprovação. Suspensão não é universal. Sem ato/notificação não se conta prazo. Primeira instância anulatória = Juzgados Letrados, não TCA direto.

## Disclaimer (uma linha)
Não substitui profissional habilitado no Uruguai nem garante residência, cédula, Carta ou passaporte. IMPO e páginas oficiais vencem a memória do modelo.


## Como rodar o GATE 1

Para cada afirmação operacional (checklist, taxa, prazo, canal, programa):

1. Abrir o texto no **IMPO**.
2. Abrir a **página viva** da DNM / CORE / DNIC / Corte Electoral / consulado.
3. Registrar **URL + data/hora**.
4. Classificar: `CONFIRMADO` · `TRANSICAO` · `CONFLITO` · `NAO-PROVADO`.
5. Conflito (apostila tratado × DNM) **permanece visível**.

### ⛔ Recusar de memória
MRREE decide permanente · temporária obrigatória para brasileiro · zero apostila absoluto · cédula = residência · Carta = nacionalidade · arraigo aberto · visto nômade / talento · prazo legal = SLA.


## URLs de topo (sempre preferir estas)
- IMPO Ley 18.250: https://www.impo.com.uy/bases/leyes/18250-2008
- Permanente MERCOSUL DNM: https://www.gub.uy/tramites/residencia-legal-permanente-mercosur
- IMPO Constitución art. 75: https://www.impo.com.uy/bases/constitucion/1967-1967/75
- Carta de Ciudadanía: https://www.gub.uy/tramites/carta-ciudadania
- Ley 18.076 refúgio: https://www.impo.com.uy/bases/leyes/18076-2006
- Ley 20.333 CCA: https://www.impo.com.uy/bases/codigo-contencioso-administrativo/20333-2024
- Reválida MEC: https://www.gub.uy/tramites/solicitud-reconocimientos-revalidas-titulos-terciarios

## Saída esperada
1. Frente + fase + nacionalidade + rota + **data do ato** usada.  
2. Regime jurídico (dispositivo + URL + data de leitura).  
3. O que fazer agora / o que não fazer (⛔).  
4. Lacunas `NAO-PROVADO` / conflitos oficiais declarados.  
5. Próxima skill ou referral (letrado UY / DNM / CORE / DNIC / Corte Electoral).

## Guard
- Zero taxa/cota/SLA hardcoded.  
- Zero promessa de resultado ou prazo de aprovação.  
- Zero copiar trava de EUA, Portugal, Espanha ou Paraguai.  
- Byte cap: manter este arquivo ≤ 11.000 B.
