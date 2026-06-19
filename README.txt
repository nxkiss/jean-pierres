==========================================================================
 JEAN PIERRE'S GENUSSATELIER — WEBSITE (Release-Paket)
 Statische Website · mehrseitig · DSGVO-orientiert · SEO-optimiert
==========================================================================

INHALT DES PAKETS
--------------------------------------------------------------------------
  index.html        Die komplette Website (alle Seiten in einer Datei,
                    Navigation per JavaScript)
  fonts.css         Lokale Schriftarten-Definitionen (kein Google-CDN)
  fonts/            24 Schriftdateien (Cormorant Garamond, Karla,
                    IBM Plex Mono) — lokal gehostet
  images/           Alle Bilder der Website
  robots.txt        Suchmaschinen-Anweisungen
  sitemap.xml       Sitemap für Google Search Console
  README.txt        Diese Datei


SO WIRD DIE SEITE VERÖFFENTLICHT (Hosting)
--------------------------------------------------------------------------
1. Alle Dateien UND Ordner (index.html, fonts.css, fonts/, images/,
   robots.txt, sitemap.xml) unverändert in das Web-Stammverzeichnis
   ("public_html" / "htdocs" / Web-Root) hochladen. Die Ordnerstruktur
   muss erhalten bleiben.
2. HTTPS aktivieren (bei fast allen Hostern kostenlos per Let's Encrypt).
   Das ist Pflicht — die Seite verweist auf eine TLS-Verschlüsselung und
   Google bevorzugt HTTPS.
3. Fertig — die Seite läuft ohne Datenbank, ohne PHP, ohne Cookies.


!!! VOR DEM LIVE-GANG UNBEDINGT ERLEDIGEN !!!
--------------------------------------------------------------------------
A) PLATZHALTER-DOMAIN ERSETZEN
   Überall ist die Beispiel-Domain  www.genussatelier-kaufbeuren.de
   eingetragen. Diese durch die echte Domain ersetzen in:
     - index.html  -> <link rel="canonical">, og:url, og:image,
                       twitter:image und im JSON-LD-Block (url, image)
     - robots.txt  -> Sitemap-Zeile
     - sitemap.xml -> <loc>

B) RECHTLICHE ANGABEN VERVOLLSTÄNDIGEN  (auf der Seite GOLD markiert)
   Impressum:
     - Vollständigen Namen / Rechtsform des Inhabers bestätigen
     - USt-IdNr. (§ 27a UStG) eintragen ODER Kleinunternehmer-Hinweis
       (§ 19 UStG) setzen
     - Zuständige Aufsichtsbehörde (Gewerbe-/Ordnungsamt Kaufbeuren)
       bestätigen
   Datenschutzerklärung:
     - Hosting-Anbieter (Name/Anschrift) ergänzen, ggf. AV-Vertrag
       (Art. 28 DSGVO) abschließen
     - "Stand: Monat/Jahr" eintragen

C) ÖFFNUNGSZEITEN PRÜFEN
   Die hinterlegten Zeiten (Di–Sa, 11–15 & 17–21 Uhr, So+Mo geschlossen)
   bitte bestätigen/anpassen — an ZWEI Stellen in index.html:
     1. Sichtbarer Bereich auf der Seite "Reservierung & Kontakt"
     2. JSON-LD-Block (openingHoursSpecification) im <head>

D) FOTOS IN HÖHERER AUFLÖSUNG (empfohlen)
   Die Gerichtsfotos stammen aus niedrig aufgelösten Quellen (~512 px).
   Für beste Qualität bitte die Originaldateien direkt vom Handy /
   Instagram einsetzen (gleiche Dateinamen behalten):
     images/35bd096b-...jpg  = Entenbrust, Erbsen-Risotto
     images/bb523f37-...jpg  = Oktopus, Linguine
     images/52022ed5-...jpg  = Jakobsmuscheln & Garnelen
     images/2228b329-...jpg  = Schweinebäuchlein
     images/7909a044-...jpg  = Gebratener Saibling
     images/fecbacc2-...jpg  = Dessert-Variation
     images/2e345e64-...jpg  = Kaffee (bereits hochauflösend)
     images/ace3b2e6-...jpg  = Hero-Bild (KI-generiert — austauschbar)
     images/a2351f3a-...jpg  = Ambiente (KI-generiert)
     images/7c1baf19-...jpg  = Gedeckter Tisch (KI-generiert)


DATENSCHUTZ / RECHTLICHES — WAS BEREITS ERLEDIGT IST
--------------------------------------------------------------------------
  - Schriftarten LOKAL gehostet -> keine Verbindung zu Google Fonts
    (vermeidet die bekannte Google-Fonts-Abmahnproblematik).
  - KEINE Cookies, KEIN Tracking, KEINE Analyse-Tools -> kein Cookie-
    Banner nötig.
  - Google Maps ist nur als Link eingebunden (keine eingebettete Karte) ->
    es werden erst beim Klick Daten an Google übertragen.
  - Reservierungsformular sendet nichts an einen Server, sondern öffnet
    eine vorausgefüllte E-Mail.
  - Impressum & Datenschutzerklärung sind über den Footer jeder Seite
    erreichbar.

  WICHTIG: Diese Texte wurden sorgfältig als Entwurf erstellt, sind
  jedoch KEINE Rechtsberatung. Bitte vor der Veröffentlichung von einer
  fachkundigen Person / einem Anwalt prüfen lassen.


SEO — NÄCHSTE SCHRITTE
--------------------------------------------------------------------------
  - Google Unternehmensprofil (Google Business Profile) anlegen/pflegen —
    der wichtigste Hebel für lokale Sichtbarkeit eines Restaurants.
  - In der Google Search Console die Domain verifizieren und sitemap.xml
    einreichen.
  - Bereits enthalten: Meta-Titel/Beschreibung, Open-Graph- & Twitter-
    Tags, Geo-Tags, sprechende Überschriften und strukturierte Daten
    (Schema.org "Restaurant" inkl. Adresse, Öffnungszeiten, Bewertung).

Erstellt als Entwurf — bitte Inhalte/Angaben vor dem Live-Gang prüfen.
