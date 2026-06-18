# MindMode

MindMode ist eine Android-App fuer bewusste Handy-Pausen.

Claim:

> Offline gehen, ohne jemanden zu ignorieren.

## Idee

Viele Menschen wollen ihr Handy bewusst weglegen, haben aber Angst, etwas Wichtiges zu verpassen oder unhoeflich zu wirken. MindMode loest nicht nur Ablenkung, sondern die soziale Erwartung permanenter Erreichbarkeit.

MindMode ist ein Offline-Modus mit sozialer Rueckversicherung: Der Nutzer ist bewusst nicht am Handy, kann aber eine klare automatische Antwort vorbereiten und fuer echte Dringlichkeit ein Signal wie WICHTIG erlauben.

## MVP

- Pause mit Dauer starten und beenden
- Endzeit sichtbar anzeigen
- Aktive Session lokal speichern
- Auto-Antwort mit Endzeit vorbereiten
- SMS-Auto-Reply vorbereiten
- Rueckruf-SMS bei Anrufen vorbereiten
- WICHTIG-Erkennung als Kernregel

## Roadmap

Die Produkt- und Technikplanung steht in [ROADMAP.md](ROADMAP.md).

## Release-Stand

Aktueller Release Candidate: `0.3.0`.

Vor einer oeffentlichen Veroeffentlichung muessen die Google-Play-Angaben, die Datenschutzseite und die Permission Declaration fuer SMS-/Anrufberechtigungen final ausgefuellt werden. Eine vorbereitete Checkliste steht in [PLAY_STORE_RELEASE.md](PLAY_STORE_RELEASE.md).

## Naechste Schritte

1. Projekt in Android Studio oeffnen.
2. Gradle Sync ausfuehren.
3. App auf einem Android-Geraet testen.
4. Permission-Flow fuer SMS, Anrufe und Benachrichtigungen vorbereiten.
5. SMS- und Anruf-Funktionen schrittweise anbinden.
