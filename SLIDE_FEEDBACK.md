# Slide Feedback - All Changes Required

## Global Changes
1. Use "og" instead of "&" everywhere
2. Remove "Del N" labels from section dividers, keep only titles
3. Remove "ca. X minutter" from section dividers

## Slide-by-Slide Changes

### Slide 1 (Cover)
- Remove "Trykk space for å starte" button
- Use "og" instead of "&"

### Slide 2 (Hvem er vi)
- Use "og" instead of "&"

### Slide 3 (Section: Lynkurs)
- Remove "Del 2" label
- Remove "ca. 3 minutter"
- Keep only "Lynkurs: LangChain, agenter og samtaledesign"

### Slide 4 (Hva er LangChain)
- Fix "LLM-abstraksjoner" (add dash)

### Slide 5 (Hva er en agent)
- No changes needed

### Slide 6 (Samtaledesign for agenter)
- DELETE THIS SLIDE ENTIRELY

### Slide 7 (Tre nøkkelprinsipper)
- No changes needed

### Slide 8 (Hvordan koble på LangChain)
- Overflows on Y axis - needs compression

### Slide 9 (Hva bør man se etter og benchmarke)
- Each card should appear one at a time (not all at once)
- Cards are too tall, compress them
- Overflows outside screen

### Slide 10 (Section: Hva bygger vi)
- Remove "Del 3"
- Remove minutes
- Keep only "Hva bygger vi?"

### Slide 11 (Hei, huset!)
- Overflows on Y axis - too much text

### Slide 12 (Chat med kontekst)
- No changes noted

### Slide 13 (Dokumentanalyse med AI)
- No changes noted

### Slide 14 (Varsler og forbedringsplaner)
- No changes noted

### Slide 15 (Teknisk arkitektur)
- Diagram overflows screen - needs scaling down

### Slide 16 (Section: Observabilitet)
- Remove "Del 4"
- Remove minutes
- Keep only "Observabilitet og sporbarhet"

### Slide 17 (Hvorfor er observabilitet viktig)
- No changes noted

### Slide 18 (MLflow UI - Traces-oversikten)
- Remove bullet points entirely
- Keep only screenshot placeholder

### Slide 19 (Slik setter vi opp MLflow-tracing)
- Remove green callout at end
- Keep only code snippets

### Slide 20 (Hva tracer vi - Chat-agent graf)
- Diagram overflows on X axis - needs scaling

### Slide 21 (MLflow UI - Utvidet trace)
- Remove bullet points
- Keep screenshot only

### Slide 22 (Agenttilstanden)
- Remove line-by-line click highlighting
- Just show code snippet + blue callout

### Slide 23 (Ekstraheringsagenten - Deep Agents)
- Overflows massively on Y axis
- Remove per-line code highlighting

### Slide 24 (Ekstraheringsagent - Arbeidsflyt)
- DELETE THIS SLIDE
- Bake purple callout ("because Deep Agents builds on LangChain, automatic tracing") into slide 23

### Slide 25 (MLflow UI - Ekstraheringsagent trace)
- Keep screenshot
- Remove bullet point text

### Slide 26+27 (Evaluering + Custom scorers)
- MERGE these two slides into one

### Slide 28 (GroundednessScorer kodeeksempel)
- Overflows on Y axis
- Control font size to fit

### Slide 29 (Kjøre evalueringer - CLI)
- No changes noted

### Slide 30 (Kjøre evalueringer - Kode)
- DELETE THIS SLIDE ENTIRELY

### Slide 31 (MLflow UI - Evaluation results)
- Keep screenshot
- Remove bullet points

### Slide 32 (Kurerte testdatasett)
- Remove line highlighting, just show code
- Blue callout overflows on Y axis - control font size

### Slide 33 (Produksjons-traces -> Evaluering)
- Overflows on Y axis

### Slide 34 (Produksjons-traces -> Evaluering - Flyt)
- Mermaid diagram + green callout are redundant (same info)
- Remove the green callout, keep only diagram

### Slide 35 (Section: Utvikling og hosting)
- Remove "Del 5"
- Remove minutes
- Keep only "Utvikling og hosting"

### Slide 36 (Lokal utvikling - Docker Compose)
- Overflows on Y axis

### Slide 37 (Lokal utvikling - Live demo)
- DELETE THIS SLIDE ENTIRELY

### Slide 38 (Produksjon - Databricks)
- Under alternatives list, remove the "Databricks" entry (it's implicit)

### Slide 39 (Section: Oppsummering)
- Remove "Del 6"
- Remove minutes
- Keep only "Oppsummering og veien videre"

### Slide 40 (Den store idéen)
- No changes noted

### Slide 41 (Feedback-loopen)
- Mermaid diagram overflows on Y axis

### Slide 42 (Oppsummert)
- Green callout overflows on Y axis

### Slide 43 (Takk for oppmerksomheten)
- Use "og" instead of "&"

## Summary of Deleted Slides
1. Slide 6 (Samtaledesign for agenter)
2. Slide 24 (Ekstraheringsagent - Arbeidsflyt)
3. Slide 30 (Kjøre evalueringer - Kode)
4. Slide 37 (Lokal utvikling - Live demo)

## Summary of Merged Slides
1. Slides 26+27 (Evaluering + Custom scorers) → single slide

## Verification
- After all changes, use Playwright to click through every slide
- Verify no overflow on any slide
- Verify all content is visible and readable
