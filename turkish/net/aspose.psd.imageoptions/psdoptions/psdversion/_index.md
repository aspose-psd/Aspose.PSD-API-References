---
title: PsdOptions.PsdVersion
second_title: Aspose.PSD for .NET API Referansı
description: PsdOptions mülk. Dosya biçimi sürümünü alır veya ayarlar. PSD veya PSB. olabilir
type: docs
weight: 60
url: /tr/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
## PsdOptions.PsdVersion property

Dosya biçimi sürümünü alır veya ayarlar. PSD veya PSB. olabilir

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Mülk değeri

Dosya biçimi sürümü.

### Örnekler

Aşağıdaki örnek, PSD dosyasını PSB'ye ve tersini dönüştürme yeteneğini gösterir.

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

### Ayrıca bakınız

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* ad alanı [Aspose.PSD.ImageOptions](../../psdoptions/)
* toplantı [Aspose.PSD](../../../)


