---
title: "PsdLoadOptions.AllowWarpRepaint"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti PsdLoadOptions. Mendapatkan atau mengatur apakah menyimpan dengan gambar yang dirender dengan atau tanpa transformasi warp"
type: docs
weight: 30
url: /id/net/aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowWarpRepaint property

Mendapatkan atau mengatur apakah menyimpan dengan gambar yang dirender, dengan atau tanpa transformasi warp.

```csharp
public bool AllowWarpRepaint { get; set; }
```

### Property Value

`true` render gambar dengan transformasi warp `false`.

## Contoh

Kode berikut menunjukkan rendering efek Warp.

```csharp
[C#]

string sourceFile = "source.psd";
string pngWarpedExport = "warped.png";
string psdWarpedExport = "warpFile.psd";

var warpLoadOptions = new PsdLoadOptions() { AllowWarpRepaint = true };

using (var image = (PsdImage)Image.Load(sourceFile, warpLoadOptions))
{
    image.Save(pngWarpedExport, new PngOptions());
    image.Save(psdWarpedExport, new PsdOptions());
}
```

### Lihat Juga

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


