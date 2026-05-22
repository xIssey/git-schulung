# Git Schulung — Branching & Merge Workflow

## Deine Aufgabe
1. Eigenen Branch erstellen (`feature/vorname-nachname`)
2. `teilnehmer.md` bearbeiten — deinen Namen eintragen
3. Änderungen committen und Branch pushen
4. Pull Request auf GitHub erstellen

---

## Wichtige Befehle

| Was | Befehl |
|-----|--------|
| Branch erstellen & wechseln | `git checkout -b feature/...` |
| Status prüfen | `git status` |
| Änderungen stagen | `git add .` |
| Commit erstellen | `git commit -m "..."` |
| Branch pushen | `git push origin feature/...` |
| Log anzeigen | `git log --oneline` |

---

## Ablauf auf GitHub
- Nach dem Push erscheint oben ein gelber Banner → **"Compare & pull request"** klicken
- Titel eintragen, kurze Beschreibung, dann **"Create pull request"**

---

## Nicht weiterkommen?
- `git status` zeigt immer den aktuellen Zustand
- Fehlermeldung beim Push? → prüfen ob Branch-Name mit `git branch` stimmt
- Merge Conflict? → Vortragende fragen