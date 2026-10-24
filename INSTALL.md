# Installationsanleitung für Claude

Diese Datei ist für Claude geschrieben. Ein Nutzer hat dich gebeten, die 9 Depot-Skills aus diesem Repo zu installieren. Geh so vor, wie es zu deiner Umgebung passt, und erklär dem Nutzer jeden Schritt in einfachem Deutsch.

## Die Skills

Jeder Skill ist ein Ordner mit einer Datei `SKILL.md`:

| Skill | SKILL.md (Rohdatei) |
|---|---|
| depot-check | https://raw.githubusercontent.com/finanzlenny-ui/claude-depot-skills/main/skills/depot-check/SKILL.md |
| sparplan-optimierer | https://raw.githubusercontent.com/finanzlenny-ui/claude-depot-skills/main/skills/sparplan-optimierer/SKILL.md |
| aktien-check | https://raw.githubusercontent.com/finanzlenny-ui/claude-depot-skills/main/skills/aktien-check/SKILL.md |
| politiker-tracker | https://raw.githubusercontent.com/finanzlenny-ui/claude-depot-skills/main/skills/politiker-tracker/SKILL.md |
| insider-radar | https://raw.githubusercontent.com/finanzlenny-ui/claude-depot-skills/main/skills/insider-radar/SKILL.md |
| earnings-analyst | https://raw.githubusercontent.com/finanzlenny-ui/claude-depot-skills/main/skills/earnings-analyst/SKILL.md |
| klumpen-finder | https://raw.githubusercontent.com/finanzlenny-ui/claude-depot-skills/main/skills/klumpen-finder/SKILL.md |
| copy-trader-check | https://raw.githubusercontent.com/finanzlenny-ui/claude-depot-skills/main/skills/copy-trader-check/SKILL.md |
| wochen-ritual | https://raw.githubusercontent.com/finanzlenny-ui/claude-depot-skills/main/skills/wochen-ritual/SKILL.md |

Alle 9 als fertige ZIP-Dateien (je Skill eine ZIP darin): https://github.com/finanzlenny-ui/claude-depot-skills/raw/main/download/alle-9-skills.zip

Übernimm die Inhalte der SKILL.md-Dateien unverändert.

## Fall A: Claude Code oder eine andere Umgebung mit Terminal

Führe diese zwei Befehle aus:

```
claude plugin marketplace add finanzlenny-ui/claude-depot-skills
claude plugin install depot-skills@lenny-investiert
```

Klappt das nicht, kopiere die 9 Ordner aus `skills/` nach `~/.claude/skills/`. Sag dem Nutzer danach, dass er Claude Code neu startet (oder `/reload-plugins` eingibt) und die Skills z. B. mit „Mach einen Depot-Check“ startet.

## Fall B: Claude-App (claude.ai, Desktop oder Handy)

Du kannst Skills in der App nicht selbst ins Konto des Nutzers schreiben. Bereite sie so vor, dass er sie mit wenigen Klicks übernimmt:

1. Hol die 9 Skills: Lade `alle-9-skills.zip` herunter und entpacke sie. Geht das nicht, lies die 9 SKILL.md-Dateien über die Links oben.
2. Pack jeden Skill als eigene Datei: ein Ordner mit dem Skill-Namen, darin die `SKILL.md`, als ZIP gepackt und mit der Endung `.skill` (z. B. `depot-check.skill`).
3. Gib dem Nutzer die 9 Dateien zum Speichern. Zeigt die App bei einer Datei einen Knopf zum Speichern als Skill, sag ihm, dass er den bei jeder Datei drückt. Sonst erkläre das Hochladen: **Einstellungen → Capabilities → Skills → Skill hochladen**, eine Datei nach der anderen. Nimmt der Dialog keine `.skill`-Datei an, gib ihm dieselben Dateien mit der Endung `.zip`.
4. Erinnere ihn daran, dass unter **Einstellungen → Capabilities** die Code-Ausführung und die Websuche eingeschaltet sein müssen.

Hast du keine Code-Ausführung und kannst keine Dateien erstellen: Lies die SKILL.md-Dateien über die Links und schick dem Nutzer den Link zur ZIP-Datei oben. Er kann die einzelnen ZIP-Dateien direkt hochladen.

## Zum Schluss

Bestätige dem Nutzer, welche Skills eingerichtet sind, und gib ihm drei Beispiele zum Starten:

- „Mach einen Depot-Check“ (mit Kontoauszug oder Screenshot)
- „Aktien-Check für Nvidia“
- „Starte mein Wochen-Ritual“

Und den Hinweis: Die Skills sind keine Anlageberatung. Er entscheidet selbst.
