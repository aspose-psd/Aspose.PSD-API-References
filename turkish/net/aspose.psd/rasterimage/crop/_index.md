---
title: "RasterImage.Crop"
second_title: "Aspose.PSD for .NET API Referansı"
description: "RasterImage yöntemi. Belirtilen dikdörtgeni kırpar"
type: docs
weight: 240
url: /tr/net/aspose.psd/rasterimage/crop/
---
{{< psd/tize >}}
## Crop(Rectangle) {#crop}

Belirtilen dikdörtgeni kırpar.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dikdörtgen | Rectangle | Dikdörtgen. |

## Örnekler

Aşağıdaki kod örneği, bir görüntüyü nasıl kırpıp kaydedeceğinizi gösterir.

```csharp
[C#]

// PSD dosyaları için doğru Crop yöntemini uygulayın.
string sourceFileName = "1.psd";
string exportPathPsd = "CropTest.psd";
string exportPathPng = "CropTest.png";
using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Crop(new Rectangle(10, 30, 100, 100));
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Ayrıca Bakınız

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Kaydırmalarla görüntüyü kırp.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| leftShift | Int32 | Sol kaydırma. |
| rightShift | Int32 | Sağ kaydırma. |
| topShift | Int32 | Üst kaydırma. |
| bottomShift | Int32 | Alt kaydırma. |

### Ayrıca Bakınız

* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


