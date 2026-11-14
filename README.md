# Profesor ETTI — Anul III-IV

Profesor virtual AI pentru studenții de la ETTI (UPB), anii III–IV, toate cele 5 specializări (ELA, TST, RST, MON, INF).
Construit cu Streamlit + Supabase + Gemini, derivat din [Profesor-ETTI-v2](https://github.com/lennorx/Profesor-ETTI-v2) (anii I–II).

**Stare:** în lucru — disciplinele se completează treptat (13 din 63 au conținut complet; restul au meniu, dar răspund generic).

## Fișier principal
`profesor_etti_specializari.py`

## Deploy (Streamlit Community Cloud)
Main file: `profesor_etti_specializari.py`. Secrets:

```toml
SUPABASE_URL = "..."
SUPABASE_KEY = "..."
APP_INSTANCE_ID = "profesor_specializari"   # diferit de aplicația pentru anii I-II
GOOGLE_API_KEYS = ["...", "..."]
```
