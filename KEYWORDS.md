# KEYWORDS.md — finding aid for searching sources about this subject

Naming variants and known search traps. **Listing a term is not asserting it**
(sourcing-rules): this file exists so the next search doesn't rediscover these
the hard way. Seeded from the COF-corpus sweep of 2026-08-11 (index over 1,027
files: cof 589, olavo-video 237, transcripts 201) and the web-research session
of the same date.

## The subject

- "Gustavo Corção"; full name "Gustavo Corção Braga" (the DHBB verbete is
  filed under "gustavo-corcao-braga").
- Benedictine oblate name: **Paulo** — searches of monastic sources may carry
  it.
- Pen context: crônicas signed in Diário de Notícias, Tribuna da Imprensa,
  O Estado de S. Paulo, O Globo; article titles are search routes ("Dialogando
  com o meu Pastor", "Colégios católicos que se fecham", "Quinta-feira
  Santa").
- Accent trap (family-wide rule): use literal accented strings ("Corção",
  "Lições de Abismo"); wildcard-per-character patterns silently zero in one
  engine or the other.

## ASR/OCR manglings observed in the vaulted corpora (sweep 2026-08-11)

| Actual | Appears as | Where |
|---|---|---|
| Gustavo Corção | **Gustavo Corsão** | COF291 (undated, revisao_pendente) — recommends "obras do Gustavo Corsão, Lições de Abismo, a Descoberta do Outro, etc." |
| Rio (in "grupo católico tradicionalista do Rio") | **Rilhub** (OCR garble) | COF363 (undated, revisao_pendente) — the Permanência-naming passage; verify on audio |
| Júlio Fleichman | **Jo Flashman** | olavo-video to-008 (2007-02-05, unverified), to-075 (2008-06-09, unverified) — "se converteu ao catolicismo por influência do seu amigo Gustavo Corção" |

## Corção loci in the vault, with trust levels (sweep 2026-08-11)

- **COF279** [2015-01-17, revisada, @3300]: discussion of Corção's works; the
  "morreu doido" family claim in Olavo's telling — double-attribute, and
  REQUIRES-AUDIO before any quotation.
- **COF291** [undated, revisao_pendente, @57200]: book recommendations (the
  "Corsão" mangling above).
- **COF363** [undated, revisao_pendente, @31900]: the traditionalist group of
  Rio naming its revista "Permanência" (the "Rilhub" garble above).
- **COF138** [2012-01-21, revisada, @62700]: Dom Lourenço Fleichman's response
  to Olavo in revista Permanência — reception both directions.
- **transcripts/palestra-do-livro-o-jardim-das-aflicoes** [undated, captured,
  @13200]: "Gustavo Corção foi expelido do corpo de colaboradores do…" —
  Olavo's account of a rupture, **truncated snippet: read the full context
  before using**; do not guess which body is meant from the fragment.
- **olavo-video to-008 / to-075** [2007/2008, unverified]: the Fleichman
  conversion-by-friendship claim (as "Jo Flashman").

Positive control for the sweep: "Gustavo Corção" — 3 hits across 2
collections, same index and method.

## Known-zero routes (verified zeros, with their scope)

- **"Século do Nada" as a phrase** — zero as a title phrase across the index;
  only generic "século" noise. Search the book through Corção's name, not the
  title.
- **"Três Alqueires"** — only via a Chesterton joke in olavo-video to-035;
  not a route to Corção discussion.

**Caveat on every zero above:** 32 indexed files are incomplete (archive#37) —
these zeros are leads, not proof of absence. Record the collection any new
zero was measured in.

## Web-access traps (session of 2026-08-11; register also in context.md)

- `scielo.br` — UA-filtered: 403 to fetch tools, 200 with a browser UA (the
  Jalles RBH 2012 article; ScienceOpen record is the metadata backup).
- `memoria.bn.br` — DNS dead (BN moved to .gov.br); `memoria.bn.gov.br` — 403
  even with a browser UA, likely geo-gated: JB / O Globo pages (obituaries
  07/07/1978, launch report 19/08/1968) need out-of-band Brazilian capture.
- `olavodecarvalho.org` — **hijacked** (e-commerce spam observed 2026-08-11);
  its indexed Corção tag page ("SAPIENTIAM AUTEM NON VINCIT MALITIA") and the
  "leitor e admirador" texts must come from Wayback or print, never live.
- `videeditorial.com.br`, `kirion.com.br`, `jornalopcao.com.br` — bot-walled
  (403 / challenge pages).
- `fratresinunum.com` — HTTP 522 twice (origin down); the 2008 Dom Lourenço
  Fleichman interview is unconfirmed — retry, then archive.
- `pliniocorreadeoliveira.info` — reachable; hosts mirrors of the EdUFMT book
  and the BN Revista do Livro PDF (label the hosting when citing). Its
  Zanotto TFP text excerpt: **0 hits for "Corção"** — part of the no-rupture
  evidence trail.

## Search-method notes specific to this subject

- The TFP-rupture question was swept (pt) as Corção + TFP/Plinio +
  ruptura/rompimento/polêmica across web search, the pro-Plinio archive,
  Jalles's three texts, the DHBB and Permanência's pages; **positive
  controls: the same sweeps found the Alceu rupture and the Benedictine
  rupture immediately.** A future claim of a TFP rupture needs a primary
  document (O Globo / Catolicismo files are the suggested hunting ground),
  not a repetition of the sweep.
- Book years: expect discordance, not typos — four sources give four years
  for *As Fronteiras da Técnica* (1951/1952/1953/1954). Record which source
  says which; do not "correct" one to another.
