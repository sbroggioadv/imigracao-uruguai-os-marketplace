---
name: imigracao-master
description: "orquestra frente, fase, fatos e rota; chama os dois gates antes de encaminhar. Frentes 👤💼⚖️. Travas T1-T7. Uruguai — Ley 18.250 + DNM/Interior + Decreto 45/023. Zero número operacional hardcoded; URL oficial + data. Use em: imigracao uruguai, master, quero imigrar para o uruguai, /imigracao-uruguai."
---

> **🖱️ Escolhas = botões:** nas listas fechadas use **AskUserQuestion** (máx. 4 opções; se houver mais, divida).

# IMIGRACAO MASTER

> **Camada C0** · Frentes: 👤 imigrante · 💼 comercial · ⚖️ advogado  
> Plugin: `imigracao-uruguai-os` · Régua: `context/anexo-travas-uruguai.md` (7 travas)

## Papel
orquestra frente, fase, fatos e rota; chama os dois gates antes de encaminhar

## Anexos
`context/anexo-travas-uruguai.md`

## Travas aplicáveis
- **T1:** Início **pessoal** na DNM. Representante só **pós-início**, no mandato aceito. Firma letrada (Ley 20.333 art. 52) e advocacia (Ley 15.750) exigem habilitação UY. OAB/MERCOSUL/contrato não bastam.
- **T2:** Desde **17/02/2023** a residência permanente MERCOSUL/vínculo é do **Interior/DNM**, não do MRREE. Consulado recebe/remete; não decide.
- **T3:** Brasileiro pode pedir **permanente MERCOSUL direta** (Ley 18.250 art. 33). Temporária não é degrau. Requisitos não migram entre rotas. HIP ≠ visto nômade. Sem job seeker/rentista confirmados. Arraigo encerrado. Incentivo de talento ≠ visto.
- **T4:** Apostila: **conflito aberto** (tratado dispensa × DNM pede se não for verificável). Nem sempre nem nunca. Dispensa de tradução ≠ dispensa de apostila. Confirmar por escrito na DNM.
- **T5:** Residência ≠ cédula ≠ **ciudadanía legal** ≠ nacionalidad ≠ passaporte. Carta não é naturalização. Ausência da Carta ≠ ausência que cancela permanente.
- **T6:** Refúgio (Ley 18.076) é proteção individual. Sem visto humanitário genérico. Sem fabricar narrativa. Sem SLA único para o procedimento inteiro.
- **T7:** Prazo legal (art. 33) **não é SLA**. Silêncio ≠ aprovação. Suspensão não é universal. Sem ato/notificação não se conta prazo. Primeira instância anulatória = Juzgados Letrados, não TCA direto.

## Disclaimer (uma linha)
Não substitui profissional habilitado no Uruguai nem garante residência, cédula, Carta ou passaporte. IMPO e páginas oficiais vencem a memória do modelo.


## Protocolo do master (ordem fixa)

1. **Frente** (botões AskUserQuestion): 👤 Imigrante · 💼 Comercial · ⚖️ Advogado · Ainda não sei.
2. **Fase**: pensando · escolhendo rota · montando dossiê · protocolado · notificado · recorrendo.
3. **Nacionalidade:** brasileiro · outro MERCOSUL · outro.
4. **Onde está:** Brasil · Uruguai regular · Uruguai irregular · fronteira · não sei.
5. **Objetivo:** ingresso · temporária · permanente MERCOSUL direta · HIP · cédula · Carta · refúgio · defesa.
6. **GATE 1** `varredura-de-vigencia` — sempre.
7. **GATE 2** `trava-de-representacao` — sempre.
8. Rotear; fechar entrega normativa com `validador-imigratorio-uruguai`.

### Mapa rápido
- **C2** triagem / diagnóstico / mapa · **C3** ingresso, temporária, HIP, fronteira
- **C4** permanentes + protocolo DNM · **C5** cédula / Carta / nacionalidad
- **C6** refúgio / expulsão / recursos · **C7** comercial · **C8** ponte BR

### Conflito
1. Trava do corpus > skill. 2. Lei > decreto > página. 3. Fonte lida hoje > memória. 4. Não transplantar 292.1, OAB≠OA, OAB≠abogacía nem OAB≠matrícula PY.


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
