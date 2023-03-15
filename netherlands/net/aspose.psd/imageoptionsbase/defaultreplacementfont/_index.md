---
title: ImageOptionsBase.DefaultReplacementFont
second_title: Aspose.PSD voor .NET API-referentie
description: ImageOptionsBase eigendom. Haalt het standaardvervangende lettertype op of stelt het in lettertype dat zal worden gebruikt om tekst te tekenen bij het exporteren naar raster als het bestaande laaglettertype in het PSDbestand niet in het systeem wordt gepresenteerd. Om de juiste naam van het standaardlettertype te gebruiken kan het volgende codefragment worden gebruikt  System.Drawing.Text.InstalledFontCollection col  nieuw System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily families  col.Families string defaultFontName  families0.Name PsdLoadOptions psdLoadOptions  nieuwe PsdLoadOptions  DefaultReplacementFont  defaultFontName 
type: docs
weight: 20
url: /nl/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
## ImageOptionsBase.DefaultReplacementFont property

Haalt het standaardvervangende lettertype op of stelt het in (lettertype dat zal worden gebruikt om tekst te tekenen bij het exporteren naar raster, als het bestaande laaglettertype in het PSD-bestand niet in het systeem wordt gepresenteerd). Om de juiste naam van het standaardlettertype te gebruiken, kan het volgende codefragment worden gebruikt : System.Drawing.Text.InstalledFontCollection col = nieuw System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = nieuwe PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### Eigendoms-waarde

Het standaard vervangende lettertype.

### Voorbeelden

In het volgende voorbeeld ziet u hoe u de eigenschap DefaultReplacementFont gebruikt om het standaard vervangende lettertype te wijzigen.

```csharp
[C#]

// Installeer Konstanting Font alsjeblieft niet, want deze test zou het lettertype moeten vervangen dat niet is geïnstalleerd
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    // Op deze manier kunt u verschillende lettertypen gebruiken voor verschillende uitvoer 
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### Zie ook

* class [ImageOptionsBase](../)
* naamruimte [Aspose.PSD](../../imageoptionsbase/)
* montage [Aspose.PSD](../../../)


