---
title: RasterCachedImage.Resize
second_title: Aspose.PSD for .NET API Referansı
description: RasterCachedImage yöntem. Görüntüyü yeniden boyutlandırır.
type: docs
weight: 120
url: /tr/net/aspose.psd/rastercachedimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Görüntüyü yeniden boyutlandırır.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| newHeight | Int32 | Yeni yükseklik. |
| resizeType | ResizeType | Yeniden boyutlandırma türü. |

### Örnekler

Aşağıdaki kod, yeni bir SinC yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

Aşağıdaki kod, bir görüntünün yeni bir Bell yeniden boyutlandırma türüyle nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

Aşağıdaki kod, yeni bir Mitchell yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

Aşağıdaki kod, yeni bir CatmullRom yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Aşağıdaki kod, yeni bir CubicBSpline yeniden boyutlandırma türüyle bir görüntünün nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Aşağıdaki kod, bir görüntünün yeni bir CubicConvolution yeniden boyutlandırma türüyle nasıl yeniden boyutlandırılacağını gösterir.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Ayrıca bakınız

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* ad alanı [Aspose.PSD](../../rastercachedimage/)
* toplantı [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Görüntüyü yeniden boyutlandırır.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| newHeight | Int32 | Yeni yükseklik. |
| settings | ImageResizeSettings | Yeniden boyutlandırma ayarları. |

### Ayrıca bakınız

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* ad alanı [Aspose.PSD](../../rastercachedimage/)
* toplantı [Aspose.PSD](../../../)


