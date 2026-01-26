# Quarto OER-Template: Übung

Dieses Repository stellt ein **Quarto-Template für Übungen** als FAIRedelte Open Educational Resources (OER) bereit.  

Es eignet sich für textzentrierte Übungen, die konkrete Anwendungsbeispiele auf Grundlage von [Skripten](https://github.com/nfdi4objects/oer-template-skript/) bieten.

## Voraussetzungen

[Quarto ab Version 1.8](https://quarto.org)

## Nutzung als Template (empfohlen)

Erstellen Sie ein lokales Verzeichnis und generieren Sie ein neues Quarto-Projekt auf Basis dieses Repositories mit:

```bash
quarto use template nfdi4objects/oer-template-uebung
```

Quarto legt ein neues Projektverzeichnis an und kopiert alle benötigten Dateien.

## Fork oder Template?

Die Nutzung des Templates ist empfohlen, wenn Sie ein eigene Übung erstellen möchten.

Forks sind sinnvoll, wenn Sie am Template selbst mitarbeiten oder es weiterentwickeln möchten.

## Erste Schritte

1. Angaben zu Autor:innen in `_autor_innen.yml` anpassen.

2. Metadaten in `_oer_metadata.yml` anpassen

3. Inhalte in `index.qmd` anpassen

Rendern mit:

```bash
quarto render
```

Das Ergebnis ist eine HTML-Datei im automatisch erstellten Unter-Verzeichnis `_site`.

## Hinweise

Alle Dateien sind im Quelltext ausführlich kommentiert.

Das Template ist auf die Ausgabe als HTML ausgelegt. Weitere Ausgabeformate werden noch nicht unterstützt.

## Dokumentation

Die [Dokumentation der FAIR-OER-Templates](https://nfdi4objects.github.io/n4o_oer-template-dokumentation/) liefert ausführliche Hinweise für Lehrende, Praktiker:innen und interessierte Entwickler:innen.

## Lizenz

Dieses Material steht unter der Lizenz [Creative Commons Attribution 4.0 International (CC BY 4.0)]().

Die Templates in diesem Repository stehen unter der Lizenz **[Creative Commons Attribution–ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/legalcode.de)**.

Die Lizenz ist bewusst gewählt, da die Templates keine Software im engeren Sinne sind, sondern **Struktur-, Konfigurations- und Textvorlagen** für Lehr- und Lernmaterialien.

Mit der Lizenz wird die Offenheit der Templates nicht nur ermöglicht, sondern **dauerhaft gesichert**.
 
## Förderung 

Die Materialien entstanden in dem von der DFG geförderten Projekt "[NFDI4Objects - Forschungsdateninfrastruktur für die materiellen Hinterlassenschaften der Menschheitsgeschichte](https://gepris.dfg.de/gepris/projekt/501836407) und wurden von der Task Area 6 an der [Hochschule Mainz](https://www.hs-mainz.de/) entwickelt.

<p align="center">
  <img src="https://www.dfg.de/resource/image/192702/16x9/858/483/8813c508271c12712973e1955ffdc082/86E5C6B4E28AAD65D48521A7A7498BF2/logo-gefoerdert-415.png" alt="Gefördert durch die DFG" width="250">
</p>