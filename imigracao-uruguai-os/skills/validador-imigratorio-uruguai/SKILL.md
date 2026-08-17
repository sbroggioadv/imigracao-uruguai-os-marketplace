---
name: validador-imigratorio-uruguai
description: "bloqueia número congelado, equivalência de status, autoridade antiga, URL ausente e extrapolação de gap. Frentes 👤💼⚖️. Travas T1-T7. Uruguai — Ley 18.250 + DNM/Interior + Decreto 45/023. Zero número operacional hardcoded; URL oficial + data. Use em: validar, checar fonte, URL, alucinação, MRREE, arraigo, nômade."
---

> **🖱️ Escolhas = botões:** nas listas fechadas use **AskUserQuestion** (máx. 4 opções; se houver mais, divida).

# VALIDADOR IMIGRATORIO URUGUAI

> **Camada C0** · Frentes: 👤 imigrante · 💼 comercial · ⚖️ advogado  
> Plugin: `imigracao-uruguai-os` · Régua: `context/anexo-travas-uruguai.md` (7 travas)

## Papel
bloqueia número congelado, equivalência de status, autoridade antiga, URL ausente e extrapolação de gap

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


## Checklist de bloqueio

1. Afirmação operacional sem **URL oficial + data**.
2. MRREE como decisor da permanente (pós-17/02/2023).
3. Temporária obrigatória para brasileiro pedir permanente MERCOSUL.
4. Renda/`carné de salud` importados da permanente comum para a MERCOSUL.
5. “Zero apostila” ou “apostila em tudo” sem consulta à DNM.
6. Cédula/Carta/passaporte tratados como residência ou nacionalidade.
7. Arraigo, visto nômade ou visto de talento como rota aberta.
8. Prazo legal vendido como SLA ou silêncio como aprovação.
9. Recurso com suspensão universal ou TCA como primeira instância de ato particular.
10. Cópia de trava de EUA, PT, ES ou PY.

Saída: `PASS` · `CONCERNS` · `FAIL` + item violado.


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
