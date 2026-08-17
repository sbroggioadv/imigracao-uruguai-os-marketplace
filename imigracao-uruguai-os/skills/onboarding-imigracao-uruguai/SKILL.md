---
name: onboarding-imigracao-uruguai
description: "coleta nacionalidade, residência anterior, objetivo, família, antecedentes, urgência e papel do usuário. Frentes 👤💼⚖️. Travas T1,T3,T5. Uruguai — Ley 18.250 + DNM/Interior + Decreto 45/023. Zero número operacional hardcoded; URL oficial + data. Use em: /start-imigracao-uruguai, configurar, primeira vez, onboarding."
---

> **🖱️ Escolhas = botões:** nas listas fechadas use **AskUserQuestion** (máx. 4 opções; se houver mais, divida).

# ONBOARDING IMIGRACAO URUGUAI

> **Camada C0** · Frentes: 👤 imigrante · 💼 comercial · ⚖️ advogado  
> Plugin: `imigracao-uruguai-os` · Régua: `context/anexo-travas-uruguai.md` (7 travas)

## Papel
coleta nacionalidade, residência anterior, objetivo, família, antecedentes, urgência e papel do usuário

## Anexos
`context/anexo-travas-uruguai.md`

## Travas aplicáveis
- **T1:** Início **pessoal** na DNM. Representante só **pós-início**, no mandato aceito. Firma letrada (Ley 20.333 art. 52) e advocacia (Ley 15.750) exigem habilitação UY. OAB/MERCOSUL/contrato não bastam.
- **T3:** Brasileiro pode pedir **permanente MERCOSUL direta** (Ley 18.250 art. 33). Temporária não é degrau. Requisitos não migram entre rotas. HIP ≠ visto nômade. Sem job seeker/rentista confirmados. Arraigo encerrado. Incentivo de talento ≠ visto.
- **T5:** Residência ≠ cédula ≠ **ciudadanía legal** ≠ nacionalidad ≠ passaporte. Carta não é naturalização. Ausência da Carta ≠ ausência que cancela permanente.

## Disclaimer (uma linha)
Não substitui profissional habilitado no Uruguai nem garante residência, cédula, Carta ou passaporte. IMPO e páginas oficiais vencem a memória do modelo.


## Fluxo (botões AskUserQuestion)

1. **Frente:** 👤 Imigrante · 💼 Comercial · ⚖️ Advogado · Só estudar o plugin.
2. **Objetivo:** entrar · permanente MERCOSUL · temporária · HIP/remoto · cédula · Carta · refúgio · já tenho processo · não sei.
3. **Nacionalidade:** brasileiro · outro MERCOSUL · outro.
4. **Onde está:** Brasil · UY com residência · UY sem título · fronteira · outro.
5. **Papel (se 💼/⚖️):** só OAB · habilitado UY · correspondente · não se aplica.

### ⛔ Se pedir “temporária obrigatória antes da permanente”
Aplicar T3: brasileiro pode permanente MERCOSUL **direta**.

### ⛔ Se pedir arraigo / visto nômade / visto de talento
Aplicar T3: arraigo encerrado; HIP ≠ visto nômade; incentivo fiscal ≠ visto.

Grave o perfil e devolva ao `imigracao-master`.


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
