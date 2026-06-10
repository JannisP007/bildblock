# Bild-Block (Phase 6) — EEG-Stimulus-Runner

Selbst-timende Stimulus-Seite für den Bild-Block einer explorativen EEG-Pilotstudie
(Bachelorarbeit, HTW Berlin). Zeigt 11 Bilder in fester Reihenfolge je 6 s, mit
gejitterten Washout-Pausen (grauer Schirm + Fixationskreuz) und protokolliert jeden
Onset/Offset in `epoch_ms` (Wall-Clock) für die Synchronisation mit dem EEG-Export.

**Aufruf:** Die Seite wird über GitHub Pages per HTTPS bereitgestellt. Start per
Leertaste oder Button; am Ende lädt automatisch eine Marker-CSV herunter.

## Bildmaterial — Herkunft & Lizenz

- **Affektive/neutrale Bilder (p6_01–p6_07):** Open Affective Standardized Image Set
  (**OASIS**) — Kurdi, Lozano und Banaji (2017), Behavior Research Methods.
  Lizenz: **CC BY-NC-SA 4.0** (nicht-kommerzielle wissenschaftliche Nutzung mit
  Namensnennung und Weitergabe unter gleichen Bedingungen). OSF: <https://osf.io/6pnd7/>
- **Konsum-Bilder (p6_08–p6_11):** Pexels — kostenlose Nutzung gemäß **Pexels-Lizenz**
  (inkl. Weitergabe), keine Namensnennungspflicht.

Die Bilder werden ausschließlich zu nicht-kommerziellen Forschungs- und
Lehrzwecken bereitgestellt.

## Technik

Reine statische Seite (HTML/JS, keine Build-Tools, kein Tracking, keine Server-Logik).
Es werden **keine personenbezogenen Daten** erhoben oder übertragen; die Marker-CSV
entsteht lokal im Browser und wird lokal heruntergeladen.
