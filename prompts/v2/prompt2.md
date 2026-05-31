## Extraktion und Kategorisierung der Bedeutungen

**Aufgabe:**
Extrahiere sämtliche Bedeutungen des Lemmas aus den Belegen und analysiere sie umfassend. Ziel ist eine vollständige semantische Bestandsaufnahme, die als Grundlage für die spätere Artikelstrukturierung dient.

**Informationsquellen (in dieser Rangfolge priorisieren):**
1. Bedeutung der Lautung
2. Bedeutung des Kontexts
3. Belegsatz
4. Fragebogennummer
5. Großregion
6. Herkunftsort
5. Weitere relevante Kategorien (falls vorhanden)

## Bedeutungsextraktion

**Semantische Kategorisierung:**
Extrahiere jede distinkte Bedeutung, die in den Belegen vorkommt. Fasse dabei semantisch identische oder sehr ähnliche Bedeutungsangaben zusammen, auch wenn sie unterschiedlich formuliert sind.

**Sonderregeln:**
- **Tautologische Bedeutungen:** Wenn eine Bedeutungsangabe tautologisch ist (z.B. Lemma „Köder" bedeutet ‚Köder'), ordne sie der Hauptbedeutung des Wortes zu.
- **Irrelevante Belege:** Belege ohne Bedeutungsangabe oder mit unverständlicher Bedeutungsangabe werden nicht berücksichtigt. Dokumentiere die Anzahl dieser Belege am Ende.

**Schema**
```
- Bedeutungsphrase: [Bedeutungsparaphrase]
- Originalformulierungen: [Originalformulierungen]
- Regionen: [Liste der Großregionen]
- Belegsatz: [id: [ID], Belegsatz: [Belegsatz], Herkunftsort: [Herkunftsort]]
- Belege: [Liste aller zugeordneten IDs]
- Belegsanzahl: [n]
```

**Abschluss:**
Verwende ausschließlich Informationen, die in den Daten vorhanden sind. 
Wenn Informationen fehlen, dann gibt den vorgegeben null Wert zurück.
Sortiere die Bedeutungen absteigend anhand der Anzahl von Belegen.