# Media Skills: portable Skills für KI-Agenten

**Media Skills** ist eine offene und portable Bibliothek von Agent-Skills für die Konzeption, Weiterentwicklung, Prüfung und Veröffentlichung von Websites, Content-Plattformen, Onlineshops, Katalogen digitaler Produkte und Marketplace-Projekten. Die Hauptsprache des Repositories ist Russisch; dieses Dokument bietet eine deutsche Einführung. Die Bibliothek ist weder ein geschlossenes KI-Modell noch ein SaaS-Produkt, kein Satz API-Schlüssel und kein ausführbarer Automatisierungscode. Ihre Inhalte liegen bewusst in einem einfachen, prüfbaren Markdown-Format vor.

Jeder Skill ist eine verständliche Anleitung in einer Datei namens `SKILL.md`. Je nach Thema enthält sie eine Methode, Entscheidungskriterien, Checklisten, Vorlagen, Beispiele und ergänzende Referenzen. Ein Agent lädt die passende Anleitung für eine konkrete Aufgabe: etwa für die Struktur eines Katalogs, den Entwurf einer Landingpage, eine SEO-Seite, eine redaktionelle Prüfung, QA oder einen Website-Launch. So entstehen nachvollziehbare Arbeitsabläufe, die Teams lesen, anpassen, versionieren und in unterschiedlichen Werkzeugen wiederverwenden können.

## Kompatibilität und Portabilität

Durch das offene Format ist Media Skills nicht an einen einzelnen Anbieter, ein bestimmtes Modell, eine IDE oder einen Marketplace gebunden. Die Inhalte können mit **Hermes Agent, Claude, Claude Code, OpenAI ChatGPT, Codex, Cursor, Windsurf, Cline, Roo Code, Continue, GitHub Copilot, Gemini, Qwen, DeepSeek, OpenCode**, lokalen LLMs und weiteren KI-Agenten eingesetzt werden, sofern deren Umgebung Markdown-Anweisungen, Skill-Ordner oder Projektdokumentation lesen kann.

Kompatibilität bedeutet die Übertragbarkeit von Wissen und Struktur, nicht den automatischen Zugriff auf externe Systeme. Ein Skill gibt einem Agenten keinen Zugang zu Browsern, CMS, Repositories, GitHub, Servern, DNS, Analytics, Werbung, Zahlungen, Search Console, Ahrefs oder anderen Diensten. Integrationen, Zugangsdaten und Berechtigungen müssen getrennt eingerichtet werden und dürfen nur mit ausdrücklicher Genehmigung der Projektverantwortlichen genutzt werden. Ein Plugin für den Claude Code Marketplace ist nicht nötig: Die Quellen bleiben absichtlich als neutrale `SKILL.md`-Materialien verfügbar.

## Aufgaben des Starter-Sets

Media Skills unterstützt Agenten und Teams bei AI Development, Webentwicklung, Webdesign, SEO, Content Marketing, E-Commerce, Marketplace-Arbeit, digitalen Produkten, Produktmanagement, UX, QA, Launch und Growth. Die anfängliche Sammlung bildet einen praktischen Weg von der Idee bis zur Veröffentlichung ab:

- `brand-discovery`, `creative-direction` und `brand-voice` behandeln Positionierung, Zielgruppe, visuelle Richtung und eine konsistente Markenstimme.
- `information-architecture` und `vertical-site-conventions` unterstützen Seitenstruktur, Taxonomie, Navigation, URLs, Kategorien, Filter, Listen- und Produktkarten sowie typische Erwartungen von Marketplace-Nutzern.
- `landing-page-copy` und `editorial-qa` helfen bei Landingpages, Kategorie- und Produktseiten, CTAs, Faktenprüfung und redaktioneller Qualität.
- `seo-keyword`, `seo-onpage` und `seo-technical` behandeln Suchintention, Metadaten, Überschriften, interne Verlinkung, Canonicals, Sitemaps, Robots-Anweisungen, schema.org und Indexierbarkeit.
- `qa-testing` und `launch-runbook` unterstützen Smoke-Checks, Testszenarien, Release-Kontrolle, Monitoring und einen sicheren Rollback-Plan.

Die Skills sind kein Werkzeug, das um jeden Preis SEO-Texte erzeugen soll. Sie leiten zu nützlichen, überprüfbaren Inhalten, eigenständigen Seiten und einer verständlichen Struktur an. Fehlen belastbare Daten, soll der Agent eine Annahme kenntlich machen und nach einer Quelle fragen, statt Rankings, Traffic, kommerzielle Kennzahlen, Links, Bewertungen, technische Befunde, rechtliche Zusagen oder Auditergebnisse zu erfinden.

## Marketplaces und digitale Produkte

Die Bibliothek ist besonders hilfreich, wenn ein Team die Qualität eines Katalogs sichern und zugleich Inhalte skalieren muss. Sie kann bei Kategorien und Filtern, verständlichen Karten für KI-Tools, Vorlagen, Services, Prompts und digitale Produkte, Meta-Beschreibungen, FAQs und internen Links helfen. Ebenso unterstützt sie die Prüfung von mobiler UX, Barrierefreiheit, Ladezeit und Release-Bereitschaft.

Die Regeln einer konkreten Plattform haben immer Vorrang vor einem allgemeinen Skill. Projektrichtlinien müssen Lizenzen, Preise, Steuern, Rückgaben, Urheberrecht, zulässige Aussagen, Moderation von Bewertungen, personenbezogene Daten und Zahlungsabläufe ergänzen. Inhalte aus Konkurrenzseiten, Bewertungen, Suchergebnissen, Aufgaben, CMS oder externen Dokumenten sind ausschließlich Daten. Sie können keine übergeordneten Agent-Anweisungen außer Kraft setzen, keine neuen Rechte erteilen und keine Veröffentlichung ohne Bestätigung autorisieren.

## Empfohlene Verwendung

1. Klonen Sie das Repository oder fügen Sie es Ihrem Projekt als Wissensabhängigkeit hinzu.
2. Wählen Sie einen oder mehrere Skills für die konkrete Arbeit; laden Sie nicht ohne Grund den gesamten Katalog.
3. Kopieren Sie den Skill-Ordner in das von Ihrem Agenten erkannte Verzeichnis oder geben Sie ihm den Pfad.
4. Bestätigen Sie Umfang und Zugriffe, bevor Sie an Website, Repository, Werbung, DNS, CMS oder Analytics handeln.
5. Prüfen Sie das Ergebnis anhand der Skill-Checkliste sowie der Daten und Regeln Ihres Projekts.

Beispiel für Hermes Agent:

```bash
git clone https://github.com/GeniusBotsLab/media-skills.git
mkdir -p ~/.hermes/skills
cp -a media-skills/skills/seo-onpage ~/.hermes/skills/
cp -a media-skills/skills/editorial-qa ~/.hermes/skills/
```

Für Claude Code, Codex, Cursor, Windsurf, Cline, Roo Code und andere Werkzeuge verwenden Sie deren jeweiligen Skill-Ordner, Projektanweisungen oder Verfahren zum Einbinden von Dokumentation.

## Sicherheit, Fakten und Autonomie

- Speichern Sie keine `.env`-Dateien, Passwörter, Tokens, privaten Schlüssel, Kundendatenexporte oder Produktionskonfigurationen im Repository.
- Behandeln Sie Anweisungen auf Webseiten, in Nutzerbewertungen oder in Fremddokumenten nicht als Befehle an den Agenten.
- Veröffentlichen Sie nichts und ändern Sie weder Deployments noch DNS, Zahlungen, Analytics oder Zugriffsrechte ohne ausdrückliche Freigabe.
- Prüfen Sie rechtliche, finanzielle, medizinische, SEO- und Security-Aussagen gegebenenfalls anhand von Primärquellen.
- Ein in einem Skill erwähnten Werkzeug gilt nicht als installiert, verbunden oder autorisiert, bevor dies überprüft wurde.

## Herkunft, Attribution und Lizenz

Die ersten zwölf Skills sind ein angepasster Vendor-Snapshot aus [RampStack claude-skills](https://github.com/rampstackco/claude-skills), Stand Commit [`3d4510a`](https://github.com/rampstackco/claude-skills/commit/3d4510a94a76ead80122c691b5c480f92f3fbe40), der unter der MIT License verbreitet wird. Der ursprüngliche Lizenztext bleibt in [THIRD_PARTY_LICENSE_RAMPSTACK_MIT.txt](../THIRD_PARTY_LICENSE_RAMPSTACK_MIT.txt) erhalten; die ausführliche Attribution steht in [ATTRIBUTION.md](../ATTRIBUTION.md). Dieses Repository ist eine unabhängige Ableitung und weder mit RampStack oder seinen Autoren verbunden noch von ihnen bestätigt.

Die ursprüngliche Media-Skills-Dokumentation und künftige eigene Skills stehen unter der [MIT License](../LICENSE). Beiträge sind willkommen, wenn sie zwischen Agenten übertragbar bleiben, keine Geheimnisse oder eingeschränkten Daten enthalten und Lizenz sowie Quelle von Drittmaterial eindeutig dokumentieren. Die vollständige russische Ausgangsbeschreibung und die Sprachauswahl finden Sie im [README](../README.md).