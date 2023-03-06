---
title: PsdOptions.PsdVersion
second_title: Aspose.PSD voor .NET API-referentie
description: PsdOptions eigendom. Haalt de versie van het bestandsformaat op of stelt deze in. Het kan PSD of PSB zijn.
type: docs
weight: 60
url: /nl/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
## PsdOptions.PsdVersion property

Haalt de versie van het bestandsformaat op of stelt deze in. Het kan PSD of PSB zijn.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Eigendoms-waarde

De versie van het bestandsformaat.

### Voorbeelden

Het volgende voorbeeld toont de mogelijkheid om PSD-bestanden naar PSB te converteren en vice versa.

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

### Zie ook

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* naamruimte [Aspose.PSD.ImageOptions](../../psdoptions/)
* montage [Aspose.PSD](../../../)


