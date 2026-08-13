---
title: "PsdOptions.PsdVersion"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PsdOptions özelliği. Dosya formatı sürümünü alır veya ayarlar. PSD veya PSB olabilir"
type: docs
weight: 70
url: /tr/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
{{< psd/tize >}}
## PsdOptions.PsdVersion property

Dosya formatı sürümünü alır veya ayarlar. PSD veya PSB olabilir.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Property Value

Dosya formatı sürümü.

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

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


