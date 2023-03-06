---
title: Class AiLayerSection
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Ai.AiLayerSection sınıf. Ai biçimi Katman Bölümü
type: docs
weight: 1270
url: /tr/net/aspose.psd.fileformats.ai/ailayersection/
---
## AiLayerSection class

Ai biçimi Katman Bölümü

```csharp
public sealed class AiLayerSection : AiDataSection
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | Mavi renk bileşenini alır veya ayarlar. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | Renk numarasını alır veya ayarlar. -1, Red, Green, Blue özelliklerinden gelen özel renk değeridir. Katmanın renk ayarını belirtir. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | Loş değerini yüzde olarak alır veya ayarlar. Katmanda bulunan bağlantılı görüntülerin ve bitmap görüntülerinin yoğunluğunu belirtilen yüzdeye düşürür. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | Yeşil renk bileşenini alır veya ayarlar. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | Bu katmanın soluk olup olmadığını belirten bir değer alır veya ayarlar. Katmanda bulunan bağlantılı görüntülerin ve bitmap görüntülerinin yoğunluğunu azaltır. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | Bu katmanın kilitli olup olmadığını gösteren bir değer alır veya ayarlar. Öğede değişiklik yapılmasını önler. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | Bu katmanın önizleme olup olmadığını belirten bir değer alır veya ayarlar. Katmanda bulunan resmi ana hatlar yerine renkli olarak görüntüler. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | Bu katmanın yazdırılıp yazdırılmadığını gösteren bir değer alır veya ayarlar. Doğruysa, katmanda bulunan resmi yazdırılabilir yapar. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | Bu katmanın gösterilip gösterilmediğini belirten bir değer alır veya ayarlar. Doğruysa, katmanda bulunan tüm resimleri çalışma yüzeyinde görüntüler. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | Bu katmanın şablon katmanı olup olmadığını gösteren bir değer alır veya ayarlar. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | Katman adını alır veya ayarlar. Katmanlar panelinde göründüğü şekliyle öğenin adını belirtir. |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | Raster görüntüleri alır. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | Kırmızı renk bileşenini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | Tarama görüntüsünü ekler. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Geçerli örneği ortadan kaldırır. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | Dizi verilerini alır. |

### Örnekler

Aşağıdaki kod, Raster Görüntü ayarlarının AI Format Dosyalarında nasıl yükleneceğini gösterir.

```csharp
[C#]

const double DefaultTolerance = 1e-6;

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

string sourceFile = "sample.ai";
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AiLayerSection layer = image.Layers[0];

    AssertIsTrue(layer.RasterImages != null, "RasterImages property should be not null");
    AssertIsTrue(layer.RasterImages.Length == 1, "RasterImages property should contain exactly one item");

    AiRasterImageSection rasterImage = layer.RasterImages[0];
    AssertIsTrue(rasterImage.Pixels != null, "rasterImage.Pixels property should be not null");
    AssertIsTrue(rasterImage.Pixels.Length == 100, "rasterImage.Pixels property should contain exactly 100 items");
    AssertIsTrue((uint)rasterImage.Pixels[99] == 0xFFB21616, "rasterImage.Pixels[99] should be 0xFFB21616");
    AssertIsTrue((uint)rasterImage.Pixels[19] == 0xFF00FF00, "rasterImage.Pixels[19] should be 0xFF00FF00");
    AssertIsTrue((uint)rasterImage.Pixels[10] == 0xFF01FD00, "rasterImage.Pixels[10] should be 0xFF01FD00");
    AssertIsTrue((uint)rasterImage.Pixels[0] == 0xFF0000FF, "rasterImage.Pixels[0] should be 0xFF0000FF");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Width) < DefaultTolerance, "rasterImage.Width should be 0.99987");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Height) < DefaultTolerance, "rasterImage.Height should be 0.99987");
    AssertIsTrue(Math.Abs(387 - rasterImage.OffsetX) < DefaultTolerance, "rasterImage.OffsetX should be 387");
    AssertIsTrue(Math.Abs(379 - rasterImage.OffsetY) < DefaultTolerance, "rasterImage.OffsetY should be 379");
    AssertIsTrue(Math.Abs(0 - rasterImage.Angle) < DefaultTolerance, "rasterImage.Angle should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.LeftBottomShift) < DefaultTolerance, "rasterImage.LeftBottomShift should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.X) < DefaultTolerance, "rasterImage.ImageRectangle.X should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.Y) < DefaultTolerance, "rasterImage.ImageRectangle.Y should be 0");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Width) < DefaultTolerance, "rasterImage.ImageRectangle.Width should be 10");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Height) < DefaultTolerance, "rasterImage.ImageRectangle.Height should be 10");
}
```

### Ayrıca bakınız

* class [AiDataSection](../aidatasection/)
* ad alanı [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* toplantı [Aspose.PSD](../../)


