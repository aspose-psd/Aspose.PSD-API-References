---
title: "RasterCachedImage.Resize"
second_title: "Aspose.PSD for .NET API Referansı"
description: "RasterCachedImage metodu. Görüntüyü yeniden boyutlandırır"
type: docs
weight: 120
url: /tr/net/aspose.psd/rastercachedimage/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

Görüntüyü yeniden boyutlandırır.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| newHeight | Int32 | Yeni yükseklik. |
| resizeType | ResizeType | Yeniden boyutlandırma türü. |

## Örnekler

İşte aşağıdaki kod, yeni SinC yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

İşte aşağıdaki kod, yeni Bell yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

İşte aşağıdaki kod, yeni Mitchell yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

İşte aşağıdaki kod, yeni CatmullRom yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

İşte aşağıdaki kod, yeni CubicBSpline yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

İşte aşağıdaki kod, yeni CubicConvolution yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Ayrıca Bakınız

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Görüntüyü yeniden boyutlandırır.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| newHeight | Int32 | Yeni yükseklik. |
| ayarlar | ImageResizeSettings | Yeniden boyutlandırma ayarları. |

### Ayrıca Bakınız

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


