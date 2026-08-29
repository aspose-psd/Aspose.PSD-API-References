---
title: "Klasse PdfOptions"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.ImageOptions.PdfOptions class. Die PDF-Optionen"
type: docs
weight: 5360
url: /de/net/aspose.psd.imageoptions/pdfoptions/
---
{{< psd/tize >}}
## PdfOptions class

Die PDF-Optionen.

```csharp
public class PdfOptions : ImageOptionsBase
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PdfOptions](pdfoptions/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | Liest oder setzt die standardmäßige Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen-Schriftart in der PSD-Datei im System nicht vorhanden ist). Um den korrekten Namen der Standardschriftart zu erhalten, kann das folgende Code‑Snippet verwendet werden: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Liest einen Wert, der angibt, ob diese Instanz freigegeben wurde. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | Die Mehrseitenoptionen |
| [PageSize](../../aspose.psd.imageoptions/pdfoptions/pagesize/) { get; set; } | Liest oder setzt die Größe der Seite. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | Liest oder setzt die Farbpalette. |
| [PdfCoreOptions](../../aspose.psd.imageoptions/pdfoptions/pdfcoreoptions/) { get; set; } | Die PDF-Kernoptionen |
| [PdfDocumentInfo](../../aspose.psd.imageoptions/pdfoptions/pdfdocumentinfo/) { get; set; } | Liest oder setzt Metadaten für das Dokument. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | Liest oder setzt den Fortschritts-Event-Handler. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | Liest oder setzt die Auflösungseinstellungen. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | Liest oder setzt den XMP‑Metadaten‑Container. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | Klonen Sie diese Instanz. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Gibt die aktuelle Instanz frei. |

## Beispiele

Das folgende Beispiel zeigt, wie Sie Adobe Illustrator‑Dateien mit Aspose.PSD in das PDF‑Format exportieren können.

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Das folgende Beispiel demonstriert, dass AsposePSD den Export von PSB‑Dateien in das PSD‑Format unterstützt.

```csharp
[C#]

// Unterstützt das Speichern von PSB als PDF
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Der folgende Code speichert PsdImage als PDF‑Dokument mit auswählbarem Text.

```csharp
[C#]

// Das Speichern von PSD in PDF liefert keinen auswählbaren Text.
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Das folgende Beispiel demonstriert die Unterstützung des Exports von PsdImage in das PDF‑Format.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"1.psd",
    @"little.psb",
    @"psb3.psb",
    @"inRgb16.psd",
    @"ALotOfElementTypes.psd",
    @"ColorOverlayAndShadowAndMask.psd",
    @"ThreeRegularLayersSemiTransparent.psd"
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string sourceFileName = sourcesFiles[i];
    using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
    {
        string outFileName = "PsdToPdf" + i + ".pdf";
        image.Save(outFileName, new PdfOptions());
    }
}
```

### Siehe auch

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


