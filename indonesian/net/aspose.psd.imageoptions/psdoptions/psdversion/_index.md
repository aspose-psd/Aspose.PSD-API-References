---
title: PsdOptions.PsdVersion
second_title: Aspose.PSD untuk Referensi .NET API
description: PsdOptions Properti. Mendapat atau menyetel versi format file. Bisa PSD atau PSB.
type: docs
weight: 60
url: /id/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
## PsdOptions.PsdVersion property

Mendapat atau menyetel versi format file. Bisa PSD atau PSB.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Nilai properti

Versi format file.

### Contoh

Contoh berikut menunjukkan kemampuan untuk mengkonversi file PSD ke PSB dan sebaliknya.

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

### Lihat juga

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* ruang nama [Aspose.PSD.ImageOptions](../../psdoptions/)
* perakitan [Aspose.PSD](../../../)


