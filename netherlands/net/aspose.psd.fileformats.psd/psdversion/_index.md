---
title: Enum PsdVersion
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.FileFormats.Psd.PsdVersion opsomming. Bestandsformaat versie
type: docs
weight: 3600
url: /nl/net/aspose.psd.fileformats.psd/psdversion/
---
## PsdVersion enumeration

Bestandsformaat versie

```csharp
public enum PsdVersion : byte
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Psd | `1` | De standaard PSD-versie. |
| Psb | `2` | De PSB-versie. |

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

* naamruimte [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* montage [Aspose.PSD](../../)


