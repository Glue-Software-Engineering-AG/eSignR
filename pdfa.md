---
layout: default
---

# PDF/A
## eSignR sagt, dass mein Dokument keinen der PDF/A Standards erfüllt. Ist das schlimm?

Sie können diesen Hinweis ignorieren, wenn für die von Ihnen signierten Dokumente keine Formvorschriften existieren. 
Falls Sie Dokumente archivieren wollen, empfehlen wir Ihnen, Ihre Dokumente in einen der
[PDF/A-Standards](https://de.wikipedia.org/wiki/PDF/A) zu speichern und in einen der PDF/A-Standards zu konvertieren.

## eSignR sagt, dass mein Dokument keinen der PDF/A Standards erfüllt. Ich bin anderer Ansicht



## Wie konvertiere ich meine PDF-Dateien auf PDF/A?

Wenn die von Ihnen verwendete Software keine PDF/A-Dateien erzeugen kann oder nicht standardkonformes PDF/A erzeugt, 
können Sie kostenfrei PDF-Dokumente unter Windows, macOS und Linux mit [LibreOffice Writer](https://www.libreoffice.org/) 
konvertieren. 

Installieren Sie LibreOffice, starten Sie LibreOffice Writer, öffnen Sie die zu konvertierende PDF-Datei und wählen 
Sie im Menu “Datei > Exportieren als > Als PDF exportieren”. In den PDF-Optionen können Sie die gewünschte PDF/A-Version 
auswählen.

Unter Linux können Sie Dokumente direkt auf der Kommandozeile konvertieren: 

```bash
soffice –headless –convert-to ‘pdf:writer_pdf_Export:{“SelectPdfVersion”:{“type”:”long”,”value”:”1″}}’ \
  FILE.pdf –outdir /tmp
```
