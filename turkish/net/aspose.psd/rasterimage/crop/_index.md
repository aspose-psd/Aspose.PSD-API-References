---
title: RasterImage.Crop
second_title: Aspose.PSD for .NET API Referansı
description: RasterImage yöntem. Belirtilen dikdörtgeni kırpar.
type: docs
weight: 240
url: /tr/net/aspose.psd/rasterimage/crop/
---
## Crop(Rectangle) {#crop}

Belirtilen dikdörtgeni kırpar.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rectangle | Rectangle | dikdörtgen. |

### Örnekler

Aşağıdaki kod örneği, bir görüntünün nasıl kırpılacağını ve kaydedileceğini gösterir.

```csharp
[C#]

// PSD dosyaları için doğru Kırpma yöntemini uygulayın.
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

### Ayrıca bakınız

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* ad alanı [Aspose.PSD](../../rasterimage/)
* toplantı [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Resmi kaydırarak kırpın.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| leftShift | Int32 | Sola kayma. |
| rightShift | Int32 | Doğru vardiya. |
| topShift | Int32 | Üst vardiya. |
| bottomShift | Int32 | Alt vardiya. |

### Ayrıca bakınız

* class [RasterImage](../)
* ad alanı [Aspose.PSD](../../rasterimage/)
* toplantı [Aspose.PSD](../../../)


