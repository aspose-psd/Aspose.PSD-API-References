---
title: "Enum PsdVersion"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.FileFormats.Psd.PsdVersion enum. Filformatversion"
type: docs
weight: 4060
url: /sv/net/aspose.psd.fileformats.psd/psdversion/
---
{{< psd/tize >}}
## PsdVersion enumeration

Filformatversion

```csharp
public enum PsdVersion : byte
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Psd | `1` | Standard‑PSD‑versionen. |
| Psb | `2` | PSB‑versionen. |

## Exempel

Följande exempel visar möjligheten att konvertera PSD‑fil till PSB och vice versa.

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

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


