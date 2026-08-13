---
title: "PsdLoadOptions.AllowNonChangedLayerRepaint"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PsdLoadOptions özelliği. Katman değiştirilmemişse, render sırasında orijinal katman piksellerinin korunup korunmayacağını alır veya ayarlar"
type: docs
weight: 20
url: /tr/net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

Katman değiştirilmemişse, render sırasında orijinal katman piksellerinin korunup korunmayacağını alır veya ayarlar.

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true` değişmemiş katmanların orijinal piksellerini korumak için; aksi takdirde `false`.

## Örnekler

Aşağıdaki kod, katmanların değişikliklerden önce otomatik yeniden boyanmasını önleyen yeni davranışı gösterir.

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

### Ayrıca Bakınız

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


