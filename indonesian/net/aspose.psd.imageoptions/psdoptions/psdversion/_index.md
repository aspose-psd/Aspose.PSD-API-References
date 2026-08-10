---
title: "PsdOptions.PsdVersion"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti PsdOptions. Mendapatkan atau mengatur versi format file. Bisa berupa PSD atau PSB."
type: docs
weight: 70
url: /id/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
{{< psd/tize >}}
## PsdOptions.PsdVersion property

Mendapatkan atau mengatur versi format file. Bisa berupa PSD atau PSB.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Property Value

Versi format file.

## Contoh

Contoh berikut menunjukkan kemampuan mengonversi file PSD ke PSB dan sebaliknya.

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

### Lihat Juga

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


