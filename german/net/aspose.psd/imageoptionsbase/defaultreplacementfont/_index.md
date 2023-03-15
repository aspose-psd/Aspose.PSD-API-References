---
title: ImageOptionsBase.DefaultReplacementFont
second_title: Aspose.PSD für .NET-API-Referenz
description: ImageOptionsBase eigendom. Ruft die StandardErsatzschriftart ab oder legt sie fest Schriftart die zum Zeichnen von Text beim Exportieren in Raster verwendet wird wenn die vorhandene LayerSchriftart in der PSDDatei nicht im System angezeigt wird. Um den richtigen Namen der Standardschriftart zu übernehmen kann das nächste CodeSnippet verwendet werden  System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily Familie  col.Families string defaultFontName  Familie0.Name PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName 
type: docs
weight: 20
url: /de/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
## ImageOptionsBase.DefaultReplacementFont property

Ruft die Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Exportieren in Raster verwendet wird, wenn die vorhandene Layer-Schriftart in der PSD-Datei nicht im System angezeigt wird). Um den richtigen Namen der Standardschriftart zu übernehmen, kann das nächste Code-Snippet verwendet werden : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] Familie = col.Families; string defaultFontName = Familie[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### Eigentumswert

Die standardmäßige Ersatzschriftart.

### Beispiele

Das folgende Beispiel zeigt, wie die DefaultReplacementFont-Eigenschaft verwendet wird, um die standardmäßige Ersatzschriftart zu ändern.

```csharp
[C#]

// Bitte installieren Sie Konstanting Font nicht, da dieser Test nicht installierte Schriftarten ersetzen soll
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    // Auf diese Weise können Sie verschiedene Schriftarten für verschiedene Ausgaben verwenden 
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### Siehe auch

* class [ImageOptionsBase](../)
* namensraum [Aspose.PSD](../../imageoptionsbase/)
* Montage [Aspose.PSD](../../../)


