---
title: ImageOptionsBase.DefaultReplacementFont
second_title: Aspose.PSD för .NET API-referens
description: ImageOptionsBase fast egendom. Hämtar eller ställer in standardersättningsteckensnittet teckensnitt som kommer att användas för att rita text vid export till raster om befintligt lagerteckensnitt i PSDfilen inte presenteras i systemet. För att ta korrekt namn på standardteckensnitt kan nästa kodavsnitt användas  System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily familjer  col.Families sträng defaultFontName  familjer0. PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName 
type: docs
weight: 20
url: /sv/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
## ImageOptionsBase.DefaultReplacementFont property

Hämtar eller ställer in standardersättningsteckensnittet (teckensnitt som kommer att användas för att rita text vid export till raster, om befintligt lagerteckensnitt i PSD-filen inte presenteras i systemet). För att ta korrekt namn på standardteckensnitt kan nästa kodavsnitt användas : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] familjer = col.Families; sträng defaultFontName = familjer[0]. PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### Fastighetsvärde

Standardersättningsteckensnittet.

### Exempel

Följande exempel visar hur du använder egenskapen DefaultReplacementFont för att ändra standardersättningsteckensnittet.

```csharp
[C#]

// Snälla, installera inte Konstanting Font, eftersom detta test bör ersätta teckensnitt som inte är installerat
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    // På så sätt kan du använda olika typsnitt för olika utdata 
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### Se även

* class [ImageOptionsBase](../)
* namnutrymme [Aspose.PSD](../../imageoptionsbase/)
* hopsättning [Aspose.PSD](../../../)


