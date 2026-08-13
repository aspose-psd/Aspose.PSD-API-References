---
title: "Sınıf AiLayerSection"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Ai.AiLayerSection sınıfı. Ai formatı Katman Bölümü"
type: docs
weight: 1280
url: /tr/net/aspose.psd.fileformats.ai/ailayersection/
---
{{< psd/tize >}}
## AiLayerSection class

Ai formatı Katman Bölümü

```csharp
public sealed class AiLayerSection : AiDataSection
```

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue/) { get; set; } | Mavi renk bileşenini alır veya ayarlar. |
| [ColorIndex](../../aspose.psd.fileformats.ai/ailayersection/colorindex/) { get; set; } | Renk dizinini alır veya ayarlar. Bu argüman –1 ile 26 arasında değer alabilir. Her tam sayı, kullanıcı tanımlama amaçları için katmana atanabilecek bir rengi temsil eder. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber/) { get; set; } | Renk numarasını alır veya ayarlar. -1, Kırmızı, Yeşil, Mavi özelliklerinden gelen özel renk değeridir. Katmanın renk ayarını belirtir. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue/) { get; set; } | Karartma değerini yüzde olarak alır veya ayarlar. Katmanda bulunan bağlı görüntülerin ve bitmap görüntülerin yoğunluğunu belirtilen yüzdeye düşürür. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green/) { get; set; } | Yeşil renk bileşenini alır veya ayarlar. |
| [HasMultiLayerMasks](../../aspose.psd.fileformats.ai/ailayersection/hasmultilayermasks/) { get; set; } | Bu örneğin çok katmanlı maskeleri olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed/) { get; set; } | Bu katmanın karartılıp karartılmadığını gösteren bir değeri alır veya ayarlar. Katmanda bulunan bağlı görüntülerin ve bitmap görüntülerin yoğunluğunu azaltır. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked/) { get; set; } | Bu katmanın kilitli olup olmadığını gösteren bir değeri alır veya ayarlar. Öğeye yapılan değişiklikleri engeller. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview/) { get; set; } | Bu katmanın önizleme olup olmadığını gösteren bir değeri alır veya ayarlar. Katmanda bulunan sanat eserini hatlar yerine renkli olarak gösterir. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted/) { get; set; } | Bu katmanın yazdırılıp yazdırılmayacağını gösteren bir değeri alır veya ayarlar. Doğruysa katmandaki sanat eserini yazdırılabilir yapar. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown/) { get; set; } | Bu katmanın gösterilip gösterilmeyeceğini gösteren bir değeri alır veya ayarlar. Doğruysa katmandaki tüm sanat eserini çalışma tahtasında gösterir. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate/) { get; set; } | Bu katmanın şablon katmanı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name/) { get; set; } | Katman adını alır veya ayarlar. Öğenin Katmanlar panelinde göründüğü adı belirtir. |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages/) { get; } | Raster görüntüleri alır. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red/) { get; set; } | Kırmızı renk bileşenini alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage/)(AiRasterImageSection) | Raster görüntüyü ekler. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Mevcut örneği serbest bırakır. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata/)() | Dize verisini alır. |

## Örnekler

Aşağıdaki kod, AI Format Dosyalarındaki Raster Görüntü ayarlarının nasıl yükleneceğini gösterir.

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

### Ayrıca Bakınız

* class [AiDataSection](../aidatasection/)
* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)


