# Isa Onepager – PRD

## 1. Überblick

Ein einseitiger, ruhiger Webauftritt für **Isa – Mentaltrainerin, Energetikerin und Autorin**.  
Ziel: Menschen emotional abholen, Vertrauen aufbauen und sie dazu einladen, mit Isa in Kontakt zu treten oder über Bücher & Podcast in ihre Welt einzutauchen.

Technologie: **Statisches HTML**, **Tailwind CSS via CDN**, **Alpine.js via CDN**, keine Build-Tools, keine Frameworks.

## 2. Ziele

- Isa als authentische, warme und klare Begleiterin sichtbar machen.
- Einfache Möglichkeit bieten, Kontakt aufzunehmen.
- Bücher und Podcast als vertiefende Berührungspunkte anbieten.
- Auf allen Geräten (mobile first) eine gut lesbare, ruhige Erfahrung bieten.

## 3. Zielgruppe

- Menschen, die nach mentaler Unterstützung, Energiearbeit und ehrlicher Begleitung suchen.
- Eltern und Kinder (für Kinderbücher).
- Erwachsene Leser:innen, die sich für Themen wie Liebe, Seelenpartner, Herzverbindungen interessieren.
- Podcast-Hörer:innen, die Impulse zu Mut, Selbstvertrauen und innerer Wahrheit suchen.

## 4. Seiten & Sektionen (Onepager)

Der Auftritt besteht aus **einer HTML-Seite** mit folgenden Sektionen:

1. **Header / Navigation (Sticky)**
   - Logo/Name: "Isa" (typografisches Logo, kein Bild notwendig).
   - Navigation mit Anker-Links: Home, Über mich, Bücher & Podcast, Kontakt.

2. **HOME – Die Einladung (`#home`)**

   Inhalt (Text vorgegeben):

   > Ich begleite Menschen in ihre Kraft, in ihre Wahrheit und in den Mut, sich selbst zu leben.  
   > Meine Arbeit verbindet Energie, Herz und klare Worte, die wirken.  
   >  
   > Schön, dass du hier bist.

   Elemente:
   - Headline / Claim.
   - kurzer Intro-Text (wie oben).
   - Primäre CTA: Button „Jetzt Kontakt aufnehmen“ → scrollt zu `#contact`.
   - Optional subtile zweite CTA: „Mehr über mich“.

3. **Über mich – „Wer ich wirklich bin“ (`#about`)**

   Kernbotschaft:

   > „Ich öffne Räume, in denen Mut entsteht, Herzen heilen und Geschichten beginnen.“  
   >  
   > Ich bin Isa, Mentaltrainerin, Energetikerin und Autorin.  
   > Und meine Aufgabe ist es, Räume zu öffnen, in denen Menschen sich selbst wiederfinden.

   Unterabschnitte:
   - **Wer ich bin** – kurzer Fließtext.
   - **Was mich bewegt** – Text aus dem Dokument verwenden.
   - **Warum ich tue, was ich tue** – Text aus dem Dokument verwenden.
   - Zwei Listen:
     - *Was du bei mir findest* – Bulletpoints:
       - Ehrlichkeit, die sanft ist und trotzdem klar
       - Räume, die dich wachsen lassen
       - Worte, die fühlen
       - Energiearbeit, die dich stärkt
       - Mut, der ansteckt
       - Tiefe statt Oberfläche
       - Leichtigkeit, die dich durch schwere Momente trägt
     - *Was du bei mir nicht findest* – Bulletpoints:
       - Esoterik ohne Boden
       - Versprechen, die dir die Verantwortung nehmen
       - Oberflächliche Motivation
       - Bewertungen oder Schubladen
       - Schnelllösungen ohne Tiefe
       - Masken, Rollen oder künstliche Perfektion

4. **Bücher & Podcast (`#media`)**

   Intro-Text:

   > Worte, die wirken. Geschichten, die bleiben.  
   > Manchmal braucht es nur einen Satz, um etwas in uns zu bewegen.  
   > Hier findest du meine Bücher und meinen Podcast – zwei Wege, wie ich Menschen begleite.

   ### Bücher

   - **„Lotti & Luki“ – Magische Kinderbücher voller Mut, Freundschaft und Fantasie**
     - Kurzbeschreibung: Für Kinder, Eltern, magische Momente.
     - Button: „Zu den Büchern auf Amazon“ (Platzhalter-Link).

   - **„Herzverbindung“ – Ein Buch über Liebe, Seelenpartner & die Kraft unserer Geschichten**
     - Kurzbeschreibung: Tiefes, ehrliches Werk für Erwachsene.
     - Button: „Herzverbindung auf Amazon“ (Platzhalter-Link).

   ### Podcast

   - Titel: „Mein Podcast – Herzensworte für deine Frequenz“
   - Kurzbeschreibung:
     - Impulse, Energie, Mut und Klarheit
     - Worte, die erinnern, stärken, zurück in die Wahrheit führen
   - Button: „Zum Podcast“ (Platzhalter-Link).

5. **Kontakt – Komm näher (`#contact`)**

   Einleitung:

   > „Manchmal beginnt alles mit einer Nachricht.  
   > Wenn du spürst, dass meine Worte oder meine Energie dich berühren, dann schreib mir gerne.“

   Elemente:
   - Kontaktformular mit Feldern:
     - Name (Pflicht)
     - E-Mail (Pflicht, `type="email"`)
     - Telefon (optional)
     - Nachricht (Pflicht, Textarea)
   - Kontaktdaten:
     - E-Mail: Platzhalter `mail@beispiel.at`
     - Telefon: Platzhalter `+43 ...`
   - Optional: Link zu Instagram (Platzhalter-URL).

6. **Footer**

   - Copyright: `© {Jahr} Isa – Mentaltraining, Energiearbeit & Worte, die wirken.`
   - Links: „Impressum“, „Datenschutz“ (Platzhalter).

## 5. UX / UI Anforderungen

- **Look & Feel:** ruhig, weich, viel Weißraum, zarte Farben, inspiriert vom bereitgestellten Hintergrund (Blätter) und dem Beispiel-Onepager.
- **Farben:** 
  - Hintergrund: sehr helles Off-White.
  - Akzent: zartes Salbei-Grün, gedecktes Gold/Beige.
  - Text: dunkles, warmes Anthrazit.
- **Typografie:**
  - Headline-Font: Serif (elegant, leicht kalligrafisch).
  - Body-Font: Sans-Serif, gut lesbar.
- **Layout:**
  - Maximalbreite Content: 900–1000px, mittig.
  - Mobile zuerst: Einspaltig, auf Desktop zweispaltige Abschnitte möglich (z. B. Text + Deko).
- **Interaktionen:**
  - Sanftes Scrollen zu Ankern.
  - Hover-State für Links/Buttons (z. B. leichte Farb- oder Schattenänderung).
- **Accessibility:**
  - Ausreichender Kontrast.
  - Fokuszustände sichtbar.
  - Semantische HTML-Tags (`<header>`, `<main>`, `<section>`, `<footer>`).

## 6. Technische Anforderungen

- Einzelne Datei `index.html` mit eingebettetem Tailwind (über CDN) und Alpine.js (ebenfalls über CDN).
- Kein Build-Prozess, keine Frameworks.
- Optionales JS in `/assets/js/main.js` für z. B. Smooth Scroll, Mobile-Nav.
- Leicht anpassbare Klassen und Struktur, damit der Inhalt später erweitert werden kann.
- SEO-Basics:
  - Sinnvoller `<title>`.
  - `<meta name="description">` mit kurzer Zusammenfassung.
  - Open-Graph-Platzhalter (`og:title`, `og:description`, `og:image`).

## 7. Nicht im Scope

- Backend oder Formular-Processing.
- CMS-Anbindung.
- Mehrsprachigkeit.
- Blog oder dynamische Inhalte.

## 8. Akzeptanzkriterien

- Seite lädt ohne Build-Prozess (nur HTML-Datei im Browser öffnen).
- Layout funktioniert und ist gut lesbar auf Mobil, Tablet und Desktop.
- Alle Navigationseinträge scrollen zum richtigen Abschnitt.
- Kontaktformular ist vollständig und validiert grundlegende Pflichtfelder im Browser.
- Design entspricht grob den beschriebenen Farben, Typografie und Stimmung.
