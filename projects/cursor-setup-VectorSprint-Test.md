# Cursor Setup: VectorSprint Test

> VectorSprint v3 · 2025-12-29

## Projektbeskrivning

Användare har svårt att planera och estimera AI-sprint-projekt.

**Målgrupp:** Solo-utvecklare och små team som bygger med AI-verktyg.

---

## Teknisk approach

Iterativ utveckling med fasvis leverans.

### Standarder
- accessibility-focus
- mobile-first

---

## Arbetsordning


### 1. Foundation & Setup

Grundläggande projektstruktur och Supabase-koppling.

```
Tasks:
  - [new_component] Setup Vite + React + Tailwind
  - [integration] Konfigurera Supabase-klient
```

Estimerad tid: ~30 min


### 2. Sprint Flow MVP

Chat-baserat WHY/WHAT/HOW-flöde med fasplan-generering.

```
Tasks:
  - [logic] useSprintFlow hook
  - [new_flow] ChatPage UI
```

Estimerad tid: ~90 min


### 3. Export & Handoff

PDR-export, GitHub-integration och handoff-filer.

```
Tasks:
  - [new_component] PDRExportDialog
  - [integration] GitHub Export Service
```

Estimerad tid: ~60 min


---

## Designsystem


### Färgpalett
- Primary: `#FF8A3C`
- Secondary: `#1E242B`
- Accent: `#FF8A3C`
- Background: `#0B0B0F`

### Typografi
- Rubriker: Inter
- Brödtext: Inter

### Ton & röst
Formalitet: neutral
Personlighet: standard


---

## Cursor-specifika instruktioner

1. Öppna projektet i Cursor
2. Läs igenom PDR.md för fullständig kontext
3. Arbeta fas för fas enligt ordningen ovan
4. Använd phases-*.json för strukturerad task-data
5. Referera till brandlab-*.json för designbeslut

---

## Scope-begränsningar

PWA-first, max 50 Lovable-credits för MVP


### MVP-scope
1. WHY/WHAT/HOW-flöde för projektdefinition
2. Fasplan-generator med credit-estimat
3. PDR-export till Markdown och GitHub


---

*Genererad av VectorSprint v3*
