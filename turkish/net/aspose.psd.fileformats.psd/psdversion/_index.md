---
title: "Enum PsdVersion"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.PsdVersion enum. Dosya formatı sürümü"
type: docs
weight: 4090
url: /tr/net/aspose.psd.fileformats.psd/psdversion/
---
{{< psd/tize >}}
## PsdVersion enumeration

Dosya formatı sürümü

```csharp
public enum PsdVersion : byte
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| Psd | `1` | Varsayılan PSD sürümü. |
| Psb | `2` | PSB sürümü. |

## Örnekler

Aşağıdaki örnek, PSD dosyasını PSB'ye ve tersine dönüştürme yeteneğini gösterir.

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

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


