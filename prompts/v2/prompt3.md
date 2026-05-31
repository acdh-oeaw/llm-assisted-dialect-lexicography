## Semantische Analyse
Analysiere die Liste aller extrahierten Bedeutungen hinsichtlich ihrer semantischen Beziehungen:

1. **Semantische Relationen zwischen den Bedeutungen:**
- Welche Bedeutungen stehen in einem Ableitungsverhältnis (z.B. wörtlich -> metaphorisch)?
- Welche Bedeutungen sind Spezialisierungen oder Verallgemeinerungen anderer?
- Gibt es metonymische Verschiebungen?
- Gibt es Bedeutungen, die nur in bestimmten Kontexten/Registern auftreten (fachsprachlich, derb, kindersprachlich etc.)?
2. **Semantische Felder:**
- Welchen übergeordneten Bedeutungsbereichen lassen sich die Einzelbedeutungen zuordnen?
- Gibt es erkennbare Cluster verwandter Bedeutungen?
3. **Frequenz und Zentralität:**
- Welche Bedeutung ist am häufigsten belegt?
- Welche Bedeutung erscheint als die zentrale/prototypische?
- Welche Bedeutungen sind peripher oder regional begrenzt?
4. **Regionale Differenzierung:**
- Gibt es Bedeutungen, die nur in bestimmten Regionen vorkommen?
- Gibt es regionale Bedeutungsvarianten?

## Erstellung des Wörterbuchartikels

**Aufgabe:**
Fasse die extrahierten Bedeutungen anhand der Semantischen Analyse zusammen und ordne sie für einen Wörterbuchartikel nach dem folgenden Schema an.

**Angabe der Bedeutungen:**
- Bevorzuge flache Bedeutungshierarchien mit möglichst wenigen Einbettungsebenen.
- Vermeide zu kleinteilige Unterbedeutungen oder Varianten: Fasse semantisch ähnliche Einzelbelege zusammen, anstatt für jeden Sonderfall eine eigene Unterbedeutung anzulegen.
- Gib an ob es sich bei der Bedeutung um den Typ Hauptbedeutung, Unterbedeutung oder Bedeutungsvariante handelt.
- Ordne zusammenhängede Beudeutungen, Unterbedeutungen und Bedeutungsvariante den vorgegebenen Gruppierungen (Bedeutung, differenzierte Bedeutung, weitere Bedetutung 1 usw.) zu. Jede Gruppe hat entweder eine Haupbedeutung, mehrere Unterbedeutungen oder mehere Bedeutungsvarianten.

**Anordnungsprinzipien:**
- Häufigste/zentralste Bedeutung zuerst
- Wörtliche Bedeutungen vor übertragenen
- Allgemeine Bedeutungen vor spezialisierten
- Bei gleicher Relevanz: alphabetisch oder nach regionaler Verbreitung (weiter verbreitet zuerst)

**pseudo schema**
```
- Bedeutungsphrase: [Bedeutungsparaphrase]
- Typ: [Typ]
- Gruppierung: [Gruppierung]
- Regionen: [Liste der Großregionen]
- Belegsatz: {id: [ID], Belegsatz: [Belegsatz], Herkunftsort: [Herkunftsort]}
- Belege: [Liste aller zugeordneten IDs]
```

**Abschluss**
Verwende ausschließlich Informationen, die in den Daten vorhanden sind. 
Wenn Informationen fehlen, dann gibt den vorgegeben null Wert zurück.