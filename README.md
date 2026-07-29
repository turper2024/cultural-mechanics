# Culture Mechanics ChatGPT Workflows

## Instructions for participants

The following sections are written to be copied and sent to people who have no
prior knowledge of this repository or of Culture Mechanics.

### English

You can use the files provided with these instructions to apply Culture Mechanics
to a historical, social, political, organizational, or personal phenomenon, or to
help refine the theory itself. You do not need to know the framework's terminology,
and you may write in your preferred language and at an ordinary level of detail.

There are two ways to work: an ordinary standalone ChatGPT chat or a reusable
ChatGPT Project. The flexible instruction profile works with either. The structured
two-pass profile is designed for a Project.

The screenshots show the English ChatGPT interface available when this package was
created. They apply to the Project option. Labels, language, or layout may change as
the interface evolves.

#### Option 1 — Ordinary standalone chat

1. Start a new ordinary ChatGPT chat.
2. Choose a source setup:
   - For the simplest full-source setup, attach
     `build/md/0000-culture-mechanics.all.md`.
   - For modular source selection, attach
     `0000-culture-mechanics.guide.md` and
     `build/md/0000-culture-mechanics.core.md`. Add an individual optional Markdown
     source from `build/md/` later when the question needs it.
3. Open `0000-culture-mechanics.project-instructions.1.md`, copy its complete
   contents, and paste them into the opening message.
4. Add your question naturally. You can write, for example: “Please analyze the
   following question through Culture Mechanics: …” For theory development, say
   what you want to clarify, criticize, compare, or refine.
5. If ChatGPT identifies a materially needed source that is not attached, add the
   named file and ask it to continue. If the named file is unavailable, do not ask
   ChatGPT to invent its contents.
6. Near the end of a theory-development conversation, you may open
   `0000-culture-mechanics.theory-development-review-prompt.md`, copy its complete
   contents, and paste them into the current chat. It asks for a structured
   inventory of candidates for later human review.

#### Option 2 — ChatGPT Project

1. Select **Projects** in the ChatGPT sidebar
   ([screenshot](docs/10-project-selection.png)).
2. On the Projects page, select **New**
   ([screenshot](docs/20-new-project.png)). Enter a descriptive
   project name, such as `culture-mechanics-questions`, keep **Default memory**
   unless you have a reason to choose another setting, and select **Create project**
   ([screenshot](docs/30-create-project.png)).
3. Choose one instruction profile:
   - `0000-culture-mechanics.project-instructions.1.md` gives direct, flexible
     application or theory-refinement responses without a mandatory two-pass
     exchange.
   - `0000-culture-mechanics.project-instructions.2.md` uses a structured
     relevance-assessment and explanation workflow.
4. In the new Project, open the three-dot menu at the upper right
   ([screenshot](docs/40-settings-and-sources.png)) to open
   **Project settings**. Copy the complete contents of the chosen instruction file,
   paste them into the **Instructions** field, and close the settings window
   ([screenshot](docs/50-settings.png)).
5. Select **Sources**, then **Add sources**, and upload
   `0000-culture-mechanics.guide.md` and
   `build/md/0000-culture-mechanics.core.md`. Confirm that both appear in the source
   list ([screenshot](docs/60-sources.png)). The screenshot shows
   `guide(1).md` because that local copy had acquired a duplicate-file suffix; use
   the `0000-culture-mechanics.guide.md` supplied in this package.
6. Return to **Chats**, start a chat in the Project, and ask your question naturally.
   With profile `.1`, ChatGPT should normally answer directly. With profile `.2`,
   it should first return a relevance assessment. Check whether the question and
   proposed theory sections were understood; then reply “continue” when suitable.
7. If ChatGPT names a supplementary source, find the individual Markdown file
   under `build/md/`, add it to the Project sources, and ask ChatGPT to continue. If
   the named file is unavailable, do not ask ChatGPT to invent its contents.
8. Near the end of a theory-development conversation, you may paste the complete
   terminal review prompt into the current chat. Do not put that prompt into the
   Project instructions or add it as a theory source.

If your question asks for the exact practical method of implementing a culture and
ChatGPT names *Systems Leadership: Creating Positive Organisations*, that is an
external book not included in this package. Read the book rather than asking
ChatGPT to reconstruct its method from the supplied theory files.

One optional file is
`build/md/0050-culture-mechanics-analogies.semantic-inventory.md`. ChatGPT may request
it even when your question does not mention an analogy, if a controlled comparison
can clarify a mechanism, expose a boundary, or suggest a possible test. It also
contains explicitly labelled mappings to selected neighbouring theories, including
Julian Jaynes and Joscha Bach, and the discourse theory of Torfing, Laclau, and
Mouffe, together with Venkatesh Rao's account of script unraveling. It should
pair the inventory with the primary theory source and must not treat resemblance as
evidence.

Another optional file is
`build/md/0060-culture-program-ecology.semantic-definition.md`. Add it for questions
about Culture Programs, Culture Strategy versus Pure-Ideology, Culture-Embedded
Strategy, reality testing, mixed cultural braids, program competition, fanatic or
fatal offspring, Culture Program capture, program disharmony, objective
substitution, gradual or glacial capture, Culture Program carrying structure,
money flows, teaching or recruitment infrastructure, organizational
countermeasures, program-derived alignment metrics, the Self-Attribution
Presumption (“believe a serious actor proclamation first, then test its causal
scope”), hostile third-party labels versus self-attribution, the cross-audience
self-description audit, secret-program scale and fidelity, internal contestation,
staged capture inference, catastrophic hazard, entrusted power, pluralism,
classical liberalism, the systemic skeleton and living cultural body, adaptive
constitutional search, the Lifted-Order Capacity Dashboard (Speak, Own, Refuse,
Exit, Appeal, Correct, Cooperate, Build, Choose), Secure Homestead Rate,
constitutional sentinels, SGD variants, scorecards, soft secession, bounded
reversed legal priority (*umgekehrte Maßgeblichkeit*), *Abstimmung mit den
Füßen*, Mises's secession argument, “stroke of the pen” implementation,
distributed jurisdictions as bounded capture-failure domains, democracy as
*Schutzbalken gegen die Macht*, public or private power,
democratic purpose versus elections and other implementations, the bounded
protector, constitutional risk management for *ideologische Macht*,
*Machtpolitik* and *Willkürherrschaft*, the typed Ideological-Power Hazard
Diagnostic, Cipolla--Bonhoeffer--normopathy--ponerology, AI as a speculative
queen-bee or common-mode cultural-control stress test, the
critical-constructivist candidate application, *Hegung*, Conflict-Finders,
cultural capital, awe, or sublimated rivalry.
Keep the capacities separate. Treat SGD as an analogy, metrics as gameable, foot
voting as costly but causally opaque, staying as non-consent, effective homestead
as more than nominal title, sentinels as non-compensable but
non-self-authenticating, and local priority as bounded by the common
person-protecting shell. Treat power as necessary but dangerous when it becomes
unbounded, unanswerable, self-certifying, or inescapable; do not collapse state
coercion and private leverage or exempt the protector from review. Preserve
Mises as a co-origin, not the author of the project mechanism; legal-priority
change is not effortless implementation, and decentralization is not capture
immunity. Separate the document's analytical typology, problem and hazard
diagnosis, and candidate solution design; accepting one does not automatically
establish the next. Keep ideological-power capability, capture,
*Machtpolitik* as a possible objective, *Willkürherrschaft* as a possible
endpoint, and *Schutzbalken* as defensive architecture distinct. Treat the
hazard diagnostic as a typed profile rather than a scalar score, the
critical-constructivist umbrella as an originating candidate application, and
the AI queen bee as speculation. Scenario-level preparation does not prove
conspiracy, intent, guilt, or grounds for person-directed coercion. Its charged
examples are framed application hypotheses, not proof by inclusion.

The package also contains
`build/pdf/0500-culture-mechanics-speculative-history.pdf`. This is optional background
reading for human participants. It presents a deliberately speculative historical
narrative, is not an authoritative theory source, and is not part of the ChatGPT
inference workflow. **Do not attach or upload this PDF as a ChatGPT source.**

The package also contains `build/pdf/0500-culture-mechanics-origin-story.pdf`. This is
optional background reading for human participants who want to understand how the
theory grew from problems of business strategy, company culture, material
production, and reality testing. It is not an authoritative theory source and is
not part of the ChatGPT inference workflow. **Do not attach or upload this PDF as a
ChatGPT source.**

The answer should distinguish claims made by the theory from external facts,
case-specific inferences, and candidate refinements, and should state limitations
or alternative interpretations. With profile `.2`, these appear in the second
response after the relevance assessment. For a substantially different question,
start a new chat so that source selection and interpretation begin afresh.

### Deutsch

Mit den zusammen mit dieser Anleitung bereitgestellten Dateien können Sie ChatGPT
bitten, die Kulturmechanik auf ein historisches, gesellschaftliches, politisches,
organisatorisches oder persönliches Phänomen anzuwenden oder an der
Weiterentwicklung der Theorie mitzuwirken. Sie müssen die Fachbegriffe der Theorie
nicht kennen und können in Ihrer bevorzugten Sprache und in einer alltäglichen Form
schreiben.

Es gibt zwei Arbeitsweisen: einen gewöhnlichen, eigenständigen ChatGPT-Chat oder ein
wiederverwendbares ChatGPT-Projekt. Das flexible Anweisungsprofil funktioniert mit
beiden. Das strukturierte zweistufige Profil ist für ein Projekt vorgesehen.

Die Bildschirmfotos zeigen die englische ChatGPT-Benutzeroberfläche zum Zeitpunkt
der Paketerstellung. Sie gelten für die Projektvariante. Beschriftung, Sprache oder
Anordnung können sich mit der Benutzeroberfläche ändern.

#### Möglichkeit 1 — Gewöhnlicher eigenständiger Chat

1. Beginnen Sie einen neuen gewöhnlichen ChatGPT-Chat.
2. Wählen Sie eine Quellenausstattung:
   - Für die einfachste Ausstattung mit allen Quellen hängen Sie
     `build/md/0000-culture-mechanics.all.md` an.
   - Für eine modulare Quellenauswahl hängen Sie
     `0000-culture-mechanics.guide.md` und
     `build/md/0000-culture-mechanics.core.md` an. Fügen Sie später bei Bedarf eine
     einzelne optionale Markdown-Quelle aus `build/md/` hinzu.
3. Öffnen Sie `0000-culture-mechanics.project-instructions.1.md`, kopieren Sie den
   vollständigen Inhalt und fügen Sie ihn in die erste Nachricht ein.
4. Ergänzen Sie Ihre Frage in natürlicher Sprache. Sie können zum Beispiel
   schreiben: „Bitte analysiere die folgende Frage mithilfe der Kulturmechanik:
   …“ Wenn Sie die Theorie weiterentwickeln möchten, beschreiben Sie, was Sie
   klären, kritisieren, vergleichen oder verfeinern möchten.
5. Falls ChatGPT eine wesentlich benötigte, aber nicht angehängte Quelle nennt,
   fügen Sie die genannte Datei hinzu und bitten Sie ChatGPT fortzufahren. Falls die
   Datei nicht verfügbar ist, bitten Sie ChatGPT nicht, ihren Inhalt zu erfinden.
6. Gegen Ende eines Gesprächs zur Theorieentwicklung können Sie
   `0000-culture-mechanics.theory-development-review-prompt.md` öffnen, den
   vollständigen Inhalt kopieren und in den laufenden Chat einfügen. Der Text
   fordert ein strukturiertes Inventar von Kandidaten für eine spätere menschliche
   Prüfung an.

#### Möglichkeit 2 — ChatGPT-Projekt

1. Wählen Sie in der ChatGPT-Seitenleiste **Projects** (Projekte)
   ([Bildschirmfoto](docs/10-project-selection.png)).
2. Wählen Sie auf der Projektseite **New** (Neu)
   ([Bildschirmfoto](docs/20-new-project.png)). Geben Sie einen
   aussagekräftigen Projektnamen ein, zum Beispiel `culture-mechanics-questions`,
   behalten Sie **Default memory** (Standardspeicher) bei, sofern Sie keinen Grund
   für eine andere Einstellung haben, und wählen Sie **Create project** (Projekt
   erstellen)
   ([Bildschirmfoto](docs/30-create-project.png)).
3. Wählen Sie ein Anweisungsprofil:
   - `0000-culture-mechanics.project-instructions.1.md` ermöglicht unmittelbare,
     flexible Antworten zur Anwendung oder Theorieentwicklung ohne verpflichtenden
     zweistufigen Austausch.
   - `0000-culture-mechanics.project-instructions.2.md` verwendet ein strukturiertes
     Verfahren aus Relevanzprüfung und Erklärung.
4. Öffnen Sie im neuen Projekt über das Dreipunktmenü oben rechts
   ([Bildschirmfoto](docs/40-settings-and-sources.png)) die
   **Project settings** (Projekteinstellungen). Kopieren Sie den vollständigen
   Inhalt der gewählten Anweisungsdatei, fügen Sie ihn in das Feld
   **Instructions** (Anweisungen) ein und schließen Sie das Einstellungsfenster
   ([Bildschirmfoto](docs/50-settings.png)).
5. Wählen Sie **Sources** (Quellen) und danach **Add sources** (Quellen hinzufügen).
   Laden Sie `0000-culture-mechanics.guide.md` und
   `build/md/0000-culture-mechanics.core.md` hoch. Prüfen Sie, ob beide in der
   Quellenliste erscheinen
   ([Bildschirmfoto](docs/60-sources.png)). Im Bildschirmfoto
   erscheint `guide(1).md`, weil diese lokale Kopie bereits einen Namenszusatz für
   eine Dateidublette erhalten hatte. Verwenden Sie die in diesem Paket enthaltene
   Datei `0000-culture-mechanics.guide.md`.
6. Kehren Sie zu **Chats** zurück, beginnen Sie im Projekt einen Chat und stellen
   Sie Ihre Frage in natürlicher Sprache. Mit Profil `.1` sollte ChatGPT
   normalerweise direkt antworten. Mit Profil `.2` sollte es zuerst eine
   Relevanzprüfung liefern. Prüfen Sie, ob die Frage und die vorgeschlagenen
   Theorieabschnitte richtig verstanden wurden, und antworten Sie danach
   gegebenenfalls mit „weiter“.
7. Falls ChatGPT eine ergänzende Quelle nennt, suchen Sie die einzelne
   Markdown-Datei unter `build/md/`, fügen Sie sie den Projektquellen hinzu und bitten
   Sie ChatGPT fortzufahren. Falls die Datei nicht verfügbar ist, bitten Sie
   ChatGPT nicht, ihren Inhalt zu erfinden.
8. Gegen Ende eines Gesprächs zur Theorieentwicklung können Sie den vollständigen
   abschließenden Prüftext in den laufenden Chat einfügen. Übernehmen Sie diesen
   Text weder in die Projektanweisungen noch in die Theoriequellen.

Wenn Ihre Frage nach dem genauen praktischen Verfahren zur Umsetzung einer Kultur
fragt und ChatGPT *Systems Leadership: Creating Positive Organisations* nennt,
handelt es sich um ein externes Buch, das nicht in diesem Paket enthalten ist.
Lesen Sie das Buch, statt ChatGPT aufzufordern, seine Methode aus den
bereitgestellten Theoriedateien zu rekonstruieren.

Eine der optionalen Dateien ist
`build/md/0050-culture-mechanics-analogies.semantic-inventory.md`. ChatGPT kann diese
Datei auch dann anfordern, wenn Ihre Frage keine Analogie erwähnt, sofern ein
kontrollierter Vergleich einen Mechanismus verdeutlichen, eine Grenze aufzeigen
oder einen möglichen Test nahelegen kann. Sie enthält außerdem ausdrücklich als
solche gekennzeichnete Zuordnungen zu ausgewählten benachbarten Theorien, darunter
Julian Jaynes und Joscha Bach sowie die Diskurstheorie von Torfing, Laclau und
Mouffe und Venkatesh Raos Darstellung des Zerfalls von Skripten. Das
Analogieninventar soll zusammen mit
der primären Theoriequelle verwendet werden; Ähnlichkeit gilt nicht als Beleg.

Eine weitere optionale Datei ist
`build/md/0060-culture-program-ecology.semantic-definition.md`. Fügen Sie sie bei
Fragen zu Kulturprogrammen, Kulturstrategie im Unterschied zu
Pure-Ideology, Culture-Embedded Strategy, Realitätsprüfung, gemischten kulturellen
Geflechten, Programmkonkurrenz, fanatischen oder tödlichen Nachkommen, Culture
Program Capture (Übernahme eines Kulturprogramms), Programmdisharmonie,
Zielsubstitution, schrittweiser oder „glazialer“ Übernahme, aus dem Programm
abgeleiteten Übereinstimmungsmetriken, der Culture Program Carrying Structure
(organisatorischen und materiellen Trägerstruktur), Geldflüssen, Lehr- oder
Rekrutierungsinfrastruktur, organisatorischen Gegenmaßnahmen, der
Self-Attribution Presumption („einer ernsthaften Selbstzuschreibung des
Handelnden zuerst glauben und danach ihre kausale Reichweite prüfen“), feindlichen
Fremdzuschreibungen im Unterschied zur Selbstzuschreibung, der
zielgruppenübergreifenden Prüfung von Selbstbeschreibungen, dem Zusammenhang von
Geheimhaltung mit Reichweite und Übertragungstreue, interner Bestreitung,
stufenweiser Übernahmeinferenz, katastrophalen Gefahren, anvertrauter Macht,
Pluralismus, klassischem Liberalismus, dem systemischen Skelett und dem lebendigen
kulturellen Körper, adaptiver Verfassungssuche, dem Lifted-Order Capacity
Dashboard (Speak, Own, Refuse, Exit, Appeal, Correct, Cooperate, Build, Choose),
der Secure Homestead Rate, verfassungsrechtlichen Sentinel-Ereignissen,
SGD-Varianten, Kennzahlensystemen, weicher Sezession, begrenzter umgekehrter
Maßgeblichkeit, *Abstimmung mit den Füßen*, Demokratie als *Schutzbalken gegen
die Macht*, Mises' Sezessionsgedanken, der Implementierung „mit einem
Federstrich“, verteilten Zuständigkeiten als begrenzten Fehlerdomänen gegen
Übernahme, öffentlicher oder privater Macht, dem Zweck der Demokratie im
Unterschied zu Wahlen und anderen Implementierungen, dem begrenzten
Schutzakteur, verfassungsbezogenem Risikomanagement für *ideologische Macht*,
*Machtpolitik* und *Willkürherrschaft*, dem typisierten
Ideological-Power-Hazard-Diagnostic, der Verbindung von Cipolla, Bonhoeffer,
Normopathie und Ponerologie, KI als spekulativem Bienenkönigin- oder
Common-Mode-Stresstest kultureller Steuerung, der
kritisch-konstruktivistischen Kandidatenanwendung, *Hegung*, Konfliktfindern,
kulturellem Kapital, Ehrfurcht oder sublimierter Rivalität hinzu. Halten Sie die
Fähigkeiten
getrennt. Behandeln Sie SGD als Analogie, Kennzahlen als manipulierbar und
Abstimmung mit den Füßen als kostspielig, aber kausal mehrdeutig; Bleiben ist
keine Zustimmung, effektiver Grundbesitz ist mehr als ein nomineller Titel,
Sentinel-Ereignisse sind nicht kompensierbar, beweisen sich aber nicht selbst, und
lokale Maßgeblichkeit bleibt durch die gemeinsame personenschützende Ordnung
begrenzt. Macht ist notwendig, wird aber gefährlich, wenn sie unbegrenzt, nicht
rechenschaftspflichtig, selbstbeglaubigend oder praktisch unausweichlich wird;
staatlicher Zwang und private Abhängigkeit sind nicht gleichzusetzen, und auch
der Schutzakteur bleibt überprüfbar. Mises bleibt ein Mitursprung und nicht der
Urheber des Projektmechanismus; die Änderung des Rechtsvorrangs bedeutet keine
mühelose Umsetzung, und Dezentralisierung schafft keine Immunität gegen
Übernahme. Trennen Sie die analytische Typologie, die Problem- und
Gefahrendiagnose und den vorgeschlagenen Lösungsentwurf des Dokuments;
die Zustimmung zu einer Ebene begründet nicht automatisch die nächste.
Halten Sie ideologische Macht als kulturelle Fähigkeit, Übernahme oder
Ausnutzung, *Machtpolitik* als mögliches Ziel, *Willkürherrschaft* als möglichen
Endzustand und *Schutzbalken* als Verteidigungsarchitektur auseinander.
Behandeln Sie das Gefahrendiagnostikum als typisiertes Profil statt als
Skalarwert, den kritisch-konstruktivistischen Oberbegriff als ursprüngliche
Kandidatenanwendung und die KI-Bienenkönigin als Spekulation. Vorsorge auf
Szenarioebene beweist weder Verschwörung, Absicht oder Schuld noch eine Grundlage
für personenbezogenen Zwang.
Ihre politisch aufgeladenen Beispiele sind
eingerahmte Anwendungshypothesen und keine Belege allein durch ihre Aufnahme.

Das Paket enthält außerdem
`build/pdf/0500-culture-mechanics-speculative-history.pdf`. Diese Datei ist ein
freiwilliger Hintergrundtext ausschließlich für menschliche Teilnehmer. Sie stellt
eine bewusst spekulative historische Erzählung dar, ist keine maßgebliche
Theoriequelle und gehört nicht zum ChatGPT-Inferenzverfahren. **Laden Sie diese
PDF-Datei weder als Anhang noch als ChatGPT-Quelle hoch.**

Das Paket enthält außerdem
`build/pdf/0500-culture-mechanics-origin-story.pdf`. Diese Datei ist ein freiwilliger
Hintergrundtext ausschließlich für menschliche Teilnehmer, die nachvollziehen
möchten, wie die Theorie aus Fragen zu Unternehmensstrategie, Unternehmenskultur,
materieller Produktion und Realitätsprüfung hervorging. Sie ist keine maßgebliche
Theoriequelle und gehört nicht zum ChatGPT-Inferenzverfahren. **Laden Sie diese
PDF-Datei weder als Anhang noch als ChatGPT-Quelle hoch.**

Die Antwort sollte Aussagen der Theorie von externen Tatsachen, fallspezifischen
Schlussfolgerungen und vorgeschlagenen Theorieänderungen unterscheiden sowie
Grenzen oder alternative Deutungen nennen. Mit Profil `.2` erscheinen diese Punkte
in der zweiten Antwort nach der Relevanzprüfung. Beginnen Sie für eine wesentlich
andere Frage einen neuen Chat, damit Quellenauswahl und Deutung von Neuem beginnen.
