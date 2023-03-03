---
title: Enum PsdVersion
second_title: Aspose.PSD untuk Referensi .NET API
description: Aspose.PSD.FileFormats.Psd.PsdVersion enum. Format file versi
type: docs
weight: 3600
url: /id/net/aspose.psd.fileformats.psd/psdversion/
---
## PsdVersion enumeration

Format file versi

```csharp
public enum PsdVersion : byte
```

### Nilai

| Nama | Nilai | Keterangan |
| --- | --- | --- |
| Psd | `1` | Versi PSD default. |
| Psb | `2` | Versi PSB. |

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

* ruang nama [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* perakitan [Aspose.PSD](../../)


