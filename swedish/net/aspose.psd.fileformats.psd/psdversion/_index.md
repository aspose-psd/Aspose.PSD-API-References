---
title: Enum PsdVersion
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.PsdVersion uppräkning. Filformat version
type: docs
weight: 3600
url: /sv/net/aspose.psd.fileformats.psd/psdversion/
---
## PsdVersion enumeration

Filformat version

```csharp
public enum PsdVersion : byte
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| Psd | `1` | Standardversionen av PSD. |
| Psb | `2` | PSB-versionen. |

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

* namnutrymme [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* hopsättning [Aspose.PSD](../../)


