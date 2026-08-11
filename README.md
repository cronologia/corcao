# Cronologia — Gustavo Corção

An open, source-referenced chronology of **Gustavo Corção (1896–1978)**:
Brazilian Catholic writer, engineer and polemicist — adult convert (1939),
columnist of the major Rio papers for over three decades, founder of the
association, revista and editora **Permanência** (1968) — his life and works,
the Centro Dom Vital years, the disputes of the 1960s–70s, and his posthumous
reception, including a small reception thread in the COF lecture-transcription
corpus.

**Site:** <https://cronologia.github.io/corcao/> · part of the
[Cronologia](https://cronologia.github.io/) project family.

## Method

- `data/chronology.json` is the single source of truth; every fact and event
  carries `sources[]`; contested characterizations are attributed to their
  authors, never asserted in the site's own voice. See `AGENTS.md` for the
  subject-specific rules (the corrected TFP premise, the regime thread carried
  both directions, the REQUIRES-AUDIO rule for corpus quotes) and `context.md`
  for orientation.
- The build is a zero-dependency Node compiler from
  [cronologia/core](https://github.com/cronologia/core)'s template:
  `node scripts/validate-data.js && node build.js && node --test`.
- English is authoritative; `es`/`pt` are pre-authored translation caches with
  a visible disclaimer. **The caches are not yet authored** — the i18n
  completeness tests fail by design until they are.

## Status

Dataset authored 2026-08-11 from the compiled research report (verified-live
fetches of that date, access modes recorded). Live: 39 events, 11 facts, 11
figures, 8 organizations, 4 disambiguation items, 17 references across the
perspective spectrum (academic-critical, institutional, continuator-sympathetic,
testimony, corpus). Thread lanes declared (5, each with its basis); chronology
spine and swimlanes on.

Open items:

- **Translation caches** (`data/i18n/{pt,es}.json`) are empty — author them and
  the two failing i18n tests go green.
- **Press pages pending Brazilian capture**: the 1978 obituaries
  (JB / O Globo, 07/07/1978) and the O Globo Permanência launch report
  (19/08/1968) are attested via Jalles de Paula's scholarship; the Hemeroteca
  Digital (`memoria.bn.gov.br`) is geo-blocked outside Brazil
  (`memoria.bn.br` no longer resolves).
- **Olavo de Carvalho's written texts on Corção** await Wayback or print
  capture — `olavodecarvalho.org` now serves hijacked e-commerce content
  (observed 2026-08-11); the COF corpus loci are the documented vehicle.
- **Vide Editorial complete-works reedition**: attested via retail listings;
  publisher pages bot-walled — verify out-of-band.
- **Jalles de Paula's 2007 IUPERJ thesis**: attested via search results only;
  no repository copy located, so it is not yet in `references[]`.
- **Fratres in Unum interview with Dom Lourenço Fleichman (2008)**: origin
  server unreachable this session (HTTP 522) and the deep URL was not captured
  — retry and archive before citing.
- **Wayback snapshots** for the references (`scripts/archive-refs.js`) not yet
  run.
