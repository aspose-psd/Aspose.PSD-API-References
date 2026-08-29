---
title: "ImageOptionsBase.DefaultReplacementFont"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ImageOptionsBase-Eigenschaft. Gibt die standardmäßige Ersatzschriftart zurück oder legt sie fest, die verwendet wird, um Text beim Export in Raster zu zeichnen, wenn die Schriftart der vorhandenen Ebene in der PSD-Datei im System nicht vorhanden ist. Um den korrekten Namen der Standardschriftart zu erhalten, kann der folgende Code‑Snippet verwendet werden System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily families  col.Families string defaultFontName  families0.Name PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName"
type: docs
weight: 20
url: /de/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
{{< psd/tize >}}
## ImageOptionsBase.DefaultReplacementFont property

Liest oder setzt die standardmäßige Ersatzschriftart (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen-Schriftart in der PSD-Datei im System nicht vorhanden ist). Um den korrekten Namen der Standardschriftart zu erhalten, kann das folgende Code‑Snippet verwendet werden: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### Property Value

Die standardmäßige Ersatzschriftart.

## Beispiele

Das folgende Beispiel zeigt, wie man die DefaultReplacementFont‑Eigenschaft verwendet, um die standardmäßige Ersatzschriftart zu ändern.

```csharp
[C#]

// Bitte installieren Sie nicht die Konstanting‑Schriftart, da dieser Test eine Schriftart ersetzen soll, die nicht installiert ist.
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions() { AllowNonChangedLayerRepaint = true }))
{
    // Auf diese Weise können Sie verschiedene Schriftarten für unterschiedliche Ausgaben verwenden.
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### Siehe auch

* class [ImageOptionsBase](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


