---
title: "Enum PsdVersion"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Aspose.PSD.FileFormats.Psd.PsdVersion enum. Versi format file"
type: docs
weight: 4060
url: /id/net/aspose.psd.fileformats.psd/psdversion/
---
{{< psd/tize >}}
## PsdVersion enumeration

Versi format file

```csharp
public enum PsdVersion : byte
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Psd | `1` | Versi PSD default. |
| Psb | `2` | Versi PSB. |

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

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


