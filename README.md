# MUNARI — Backup & Recupero

Questa repository contiene **solo i file di backup e recupero** del progetto
Unreal Engine MUNARI, non l'intero progetto (che è troppo grande per git).

## Contenuto

- `Saved/Autosaves/` — dati di recupero automatico di Unreal (crash recovery)
- `Saved/Config/`    — configurazioni editor e crash report client
- `Saved/Logs/`      — log ed eventuali `*-backup-*.log`
- `Saved/AutoScreenshot.png` — screenshot automatico

## Cosa NON è incluso

Il progetto Unreal vero e proprio (`Content/`, `Config/`, `.uproject`,
`Intermediate/`, `DerivedDataCache/`, cache webcache e ShaderDebugInfo)
è escluso: sono file enormi e/o rigenerabili.
