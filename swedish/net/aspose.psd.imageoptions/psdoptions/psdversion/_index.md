---
title: PsdOptions.PsdVersion
second_title: Aspose.PSD för .NET API-referens
description: PsdOptions fast egendom. Hämtar eller ställer in filformatsversionen. Det kan vara PSD eller PSB.
type: docs
weight: 60
url: /sv/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
## PsdOptions.PsdVersion property

Hämtar eller ställer in filformatsversionen. Det kan vara PSD eller PSB.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Fastighetsvärde

Filformatets version.

### Exempel

Följande exempel visar möjligheten att konvertera PSD-fil till PSB och vice versa.

```csharp
[C#]

string sourceFilePathPsb = "2layers.psb";
string outputFilePathPsd = "ConvertFromPsb.psd";
using (Image img = Image.Load(sourceFilePathPsb))
{
    var options = new PsdOptions((PsdImage)img) { PsdVersion = PsdVersion.Psd };
    img.Save(outputFilePathPsd, options);
}

string sourceFilePathPsd = "2layers.psd";
string outputFilePathPsb = "ConvertFromPsd.psb";
using (Image img = Image.Load(sourceFilePathPsd))
{
    var options = new PsdOptions((PsdImage)img) { PsdVersion = PsdVersion.Psb };
    img.Save(outputFilePathPsb, options);
}
```

### Se även

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* namnutrymme [Aspose.PSD.ImageOptions](../../psdoptions/)
* hopsättning [Aspose.PSD](../../../)


