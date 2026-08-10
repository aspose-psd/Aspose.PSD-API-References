---
title: "PsdLoadOptions.AllowNonChangedLayerRepaint"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti PsdLoadOptions. Mendapatkan atau mengatur apakah mempertahankan piksel lapisan asli selama rendering jika lapisan tidak dimodifikasi."
type: docs
weight: 20
url: /id/net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

Mendapatkan atau mengatur apakah mempertahankan piksel lapisan asli selama rendering jika lapisan tidak dimodifikasi.

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true` untuk mempertahankan piksel asli dari lapisan yang tidak berubah; selainnya, `false`.

## Contoh

Kode berikut menunjukkan perilaku baru yang mencegah repaint otomatis lapisan sebelum perubahan.

```csharp
[C#]

string srcFile = "psdnet2400.psd";
string output1 = "unchanged-2400.png";
string output2 = "updated-2400.png";

using (var psdImage = (PsdImage)Image.Load(srcFile,
new PsdLoadOptions() { AllowNonChangedLayerRepaint = false /* The new default behaviour */ }))
{
    psdImage.Save(output1, new PngOptions());

    ((TextLayer)psdImage.Layers[1]).TextData.UpdateLayerData();

    psdImage.Save(output2, new PngOptions());
}
```

### Lihat Juga

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


