# Architektur

## Bestätigter Ist-Zustand
Das Repository war vor diesem Schritt leer. Diese Grundlage enthält ausschließlich Projektdokumentation. Es gibt noch keinen Anwendungscode, keine Abhängigkeiten, Datenbank, Modellintegration oder Bereitstellung.

| Pfad | Verantwortung |
| --- | --- |
| ../AGENTS.md | Arbeitsregeln und Einstieg für Agenten |
| CURRICULUM.md | Lernziele, Übungen und Nachweise |
| DECISIONS.md | Bestätigte Entscheidungen, Vorschläge und offene Fragen |
| ARCHITECTURE.md | Tatsächlicher Aufbau und klar markierte Entwurfsideen |

Verbindliche Entscheidungen stehen in [DECISIONS.md](DECISIONS.md).

## Fachlicher Entwurf – Vorschlag P-001
Ein möglicher erster Ablauf:

Stellenanzeige manuell eingeben → Informationen mit Quellenbezug erfassen → Ergebnis prüfen und korrigieren → Rechercheeintrag ansehen.

Dies beschreibt Verantwortlichkeiten, keine bereits beschlossenen Komponenten oder Dienste. Diese Schritte könnten zunächst in einer einzigen kleinen Anwendung stattfinden. Automatisches Sammeln, Ranking, Benutzerkonten und Bewerbungsversand gehören nicht zu diesem Vorschlag.

Mögliche Informationen eines Rechercheeintrags: Titel, Unternehmen, Quelle, Erfassungsdatum und eigene Notizen. Pflichtfelder, Speicherung und die Rolle eines Modells sind noch offen. Unbekannte Angaben sollen als unbekannt sichtbar bleiben, statt ergänzt zu werden.

## Entscheidungen vor dem ersten Code
1. Einen konkreten Nutzerablauf samt Erfolgskriterium und Nicht-Zielen festlegen.
2. An einem Beispiel prüfen, ob manuelle Erfassung genügt oder ein Modell sinnvoll hilft.
3. Erst dann die einfachste passende Oberfläche, Speicherung und technische Umsetzung vergleichen und begründet auswählen.

## Prüfidee – noch kein implementierter Test
Für einen späteren Durchstich sollen wir eine fiktive Anzeige durch den gesamten vereinbarten Ablauf führen können. Erfasste Aussagen müssen zur Quelle passen; fehlende Werte bleiben erkennbar; Korrekturen müssen möglich sein. Externe Anzeigentexte dürfen keine Arbeitsregeln überschreiben.

## Bewusst offen
Kein Framework, Hosting, Datenbanksystem oder Agentenframework ist ausgewählt. Keine Entscheidung für Microservices, Vektordatenbank oder mehrere Agenten ist getroffen. Zusätzliche Bausteine benötigen ein konkretes Problem und eine erklärte Abwägung.
