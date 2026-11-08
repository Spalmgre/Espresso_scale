# Espresso_scale

## Pakollinen alustus (tee aina ennen työn aloittamista)

1. Hae knowledgebase-päivitykset: `cd "C:\TYO\GitHub Local\dev-knowledgebase" && git pull origin main`
2. Lue: `01-workflows/SYSTEM_INSTRUCTIONS.md`, `01-workflows/workflow-rules.md`, `03-configs/devin/ide-setup.md`, `03-configs/documentation-standard.md`

## Dokumentaatiokäytännöt (knowledgebase-standardi)

Päivitetään aina samassa commitissa merkittävän muutoksen kanssa:

- **Versio** nostetaan jokaisessa deployssa (VERSION-vakio koodissa / package.json) ja merkitään HANDOVER.md:hen
- **AGENTS.md** (lähin taso) päivitetään jokaisen featuren valmistuttua
- **HANDOVER.md** juuressa: nykytila, korjatut bugit, tunnetut rajoitteet, seuraavat askeleet
- **docs/dumps/ARCHITECTURE_DUMP.md** + **UI_UX_DUMP.md** päivitetään jokaisen versionnoston yhteydessä

Nimeämisstandardi: dump-kansio `docs/dumps/` (monikko), agenttiohje `AGENTS.md` (isoilla).
