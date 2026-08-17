---
name: carta-de-ciudadania
description: "requisitos, prova contínua, espanhol funcional, testemunhas e ato da Corte Electoral. Frentes 👤💼⚖️. Travas T5,T7. Uruguai — Ley 18.250 + DNM/Interior + Decreto 45/023. Zero número operacional hardcoded; URL oficial + data. Use em: Carta de Ciudadanía, ciudadanía legal, Corte Electoral."
---

> **🖱️ Escolhas = botões:** nas listas fechadas use **AskUserQuestion** (máx. 4 opções; se houver mais, divida).

# CARTA DE CIUDADANIA

> **Camada C5** · Frentes: 👤 imigrante · 💼 comercial · ⚖️ advogado  
> Plugin: `imigracao-uruguai-os` · Régua: `context/anexo-travas-uruguai.md` (7 travas)

## Papel
requisitos, prova contínua, espanhol funcional, testemunhas e ato da Corte Electoral

## Anexos
`context/anexo-ciudadania-e-identidade.md`, `context/anexo-travas-uruguai.md`

## Travas aplicáveis
- **T5:** Residência ≠ cédula ≠ **ciudadanía legal** ≠ nacionalidad ≠ passaporte. Carta não é naturalização. Ausência da Carta ≠ ausência que cancela permanente.
- **T7:** Prazo legal (art. 33) **não é SLA**. Silêncio ≠ aprovação. Suspensão não é universal. Sem ato/notificação não se conta prazo. Primeira instância anulatória = Juzgados Letrados, não TCA direto.

## Disclaimer (uma linha)
Não substitui profissional habilitado no Uruguai nem garante residência, cédula, Carta ou passaporte. IMPO e páginas oficiais vencem a memória do modelo.


## Como operar esta skill

1. Confirmar frente e se os gates já rodaram; se não, chamar `varredura-de-vigencia` e `trava-de-representacao`.
2. Pedir fatos mínimos: nacionalidade, onde está, objetivo, status atual, datas de ingresso/protocolo/notificação.
3. Classificar a rota (permanente MERCOSUL direta / temporária / HIP / fronteira / vínculo / comum / refúgio / Carta) **antes** do checklist.
4. Mapear finalidade → dispositivo (18.250 / Decreto 45/023 / bilateral / 18.076) → página DNM viva → órgão.
5. Profundidade: 👤 checklist honesto · 💼 escopo e o que não vender · ⚖️ matriz norma→prova→remédio com referral ao letrado UY.
6. Toda afirmação operacional: **URL oficial + data**. Sem fonte → `NAO-PROVADO`.
7. Fechar com `validador-imigratorio-uruguai`.


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
