---
title: PdfOptions
second_title: Aspose.PSD für .NET-API-Referenz
description: Die PDFOptionen.
type: docs
weight: 4800
url: /de/net/aspose.psd.imageoptions/pdfoptions/
---
## PdfOptions class

Die PDF-Optionen.

```csharp
public class PdfOptions : ImageOptionsBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PdfOptions](pdfoptions)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont) { get; set; } | Ruft die Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Exportieren in Raster verwendet wird, wenn die vorhandene Layer-Schriftart in der PSD-Datei nicht im System angezeigt wird). Um den richtigen Namen der Standardschriftart zu übernehmen, kann das nächste Code-Snippet verwendet werden : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] Familie = col.Families; string defaultFontName = Familie[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Vollbild]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions) { get; set; } | Die mehrseitigen Optionen |
| [PageSize](../../aspose.psd.imageoptions/pdfoptions/pagesize) { get; set; } | Ruft die Größe der Seite ab oder legt sie fest. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. |
| [PdfCoreOptions](../../aspose.psd.imageoptions/pdfoptions/pdfcoreoptions) { get; set; } | Die PDF-Kernoptionen |
| [PdfDocumentInfo](../../aspose.psd.imageoptions/pdfoptions/pdfdocumentinfo) { get; set; } | Ruft Metadaten für das Dokument ab oder legt sie fest. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler) { get; set; } | Ruft den Fortschrittsereignishandler ab oder legt ihn fest. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings) { get; set; } | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [Source](../../aspose.psd/imageoptionsbase/source) { get; set; } | Ruft die Quelle zum Erstellen des Bildes ab oder legt sie fest. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ruft die Optionen für die Vektorrasterung ab oder legt sie fest. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata) { get; set; } | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone)() | Klont diese Instanz. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |

### Beispiele

Das folgende Beispiel zeigt, wie Sie Adobe Illustrator-Dateien in das PDF-Format in Aspose.PSD exportieren können

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

Das folgende Beispiel zeigt, dass AsposePSD den Export von PSB-Dateien in ein PSD-Format unterstützt.

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

Der folgende Code speichert PsdImage als PDF-Dokument mit auswählbarem Text.

```csharp
[C#]

// Beim Speichern von PSD in PDF wird kein auswählbarer Text bereitgestellt
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

Das folgende Beispiel demonstriert die Unterstützung des Exports von PsdImage in das PDF-Format.

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

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase)
* namensraum [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
