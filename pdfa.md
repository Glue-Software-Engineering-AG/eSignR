---
layout: default
---

# PDF/A
## eSignR sagt, dass mein Dokument keinen der PDF/A Standards erfüllt. Ist das schlimm?

Sie können diesen Hinweis ignorieren, wenn für die von Ihnen signierten Dokumente keine Formvorschriften existieren. 
Falls Sie Dokumente archivieren wollen, empfehlen wir Ihnen, Ihre Dokumente in einen der
[PDF/A-Standards](https://de.wikipedia.org/wiki/PDF/A) zu speichern und in einen der PDF/A-Standards zu konvertieren.

## eSignR sagt, dass mein Dokument keinen der PDF/A Standards erfüllt. Ich bin anderer Ansicht!

eSignR verwendet die Open Source Bibliothek veraPDF des [veraPDF Consortiums](https://verapdf.org/), um 
PDF-Dokumente auf Ihre PDF/A-Konformität zu prüfen. Es kann durchaus sein, dass die Bibliothek in ihrer Beurteilung 
falsch liegt. Sie können die folgenden kostenfreien Online-Tools nutzen, um PDF-Dokument auf Ihre PDF/A-Konformität 
zu prüfen. Beachten Sie aber, dass Sie Ihr Dokument für die Prüfung auf einen Online-Dienst hochladen müssen!

* 3-HEIGHTS™ [PDF Validator Online Tool](https://www.pdf-online.com/osa/validate.aspx) der 
[PDF Tools AG](https://www.pdf-tools.com/)
* veraPDF [PDF/A Validation](https://demo.verapdf.org/) 

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
