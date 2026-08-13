---
title: "Sınıf GrdmResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.GrdmResource sınıfı. Sınıf GrdmResource. GradientMap katmanı hakkında bilgi içerir."
type: docs
weight: 2770
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---
{{< psd/tize >}}
## GrdmResource class

Sınıf GrdmResource. Gradient-Map katmanı hakkında bilgi içerir.

```csharp
public class GrdmResource : AdjustmentLayerResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [GrdmResource](grdmresource/)(int) | Yeni bir `GrdmResource` sınıfı örneği başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ColorModel](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colormodel/) { get; set; } | Renk Modeli. 'Gradient type' = 'Noise' olduğunda, 'Color Model' değerini RGB/SHB/LAB (3/4/6) olarak atayabiliriz. |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/colorpoints/) { get; set; } | Renk noktalarını alır veya ayarlar. |
| [Dither](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/dither/) { get; set; } | Gradyan tütsülenmiş mi. |
| [ExpansionCount](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/expansioncount/) { get; set; } | Genişleme sayısı (Photoshop 6.0 için = 2). |
| [GradientMode](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientmode/) { get; set; } | Bu gradyan için mod, 'Gradient Type' = 'Solid/Noise' (0/1) belirler. |
| [GradientName](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/gradientname/) { get; set; } | Gradyanın adı: Unicode dizesi, doldurulmuş. |
| [Interpolation](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/interpolation/) { get; set; } | Enterpolasyon. 'Gradient Type' = 'Solid' (GradientMode = 0) olduğunda Pürüzsüzlüğü belirler. |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/interpolationmethod/) { get; set; } | Degrade için ara değerleme yöntemini alır veya ayarlar. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [MaximumColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/maximumcolor/) { get; set; } | PixelDataFormat.Rgba64Bpp formatının maksimum rengi. Renk ARGB kanallarına sahiptir, her kanal 16 bit'tir. |
| [MinimumColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/minimumcolor/) { get; set; } | PixelDataFormat.Rgba64Bpp formatının minimum rengi. Renk ARGB kanallarına sahiptir, her kanal 16 bit'tir. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/psdversion/) { get; } | Bu kaynak için gereken minimum PSD sürümünü alır. Enterpolasyon yöntemi açıkça depolandığında sürüm 3 gereklidir. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/reverse/) { get; set; } | Gradyan ters mi. |
| [RndNumberSeed](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/rndnumberseed/) { get; set; } | Gürültü gradyanı için renkleri oluşturmakta kullanılan rastgele sayı tohumu. |
| [Roughness](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/roughness/) { get; set; } | Pürüz faktörü. 'Gradient type' = 'Noise' olduğunda, 'Roughness' (0 - 2048) değerini atayabiliriz. |
| [ShowTransparency](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/showtransparency/) { get; set; } | Şeffaflığı gösterme bayrağı. 'Gradient type' = 'Noise' olduğunda, 'Add transparency' değerini true olarak atayabiliriz. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/transparencypoints/) { get; set; } | Şeffaflık noktalarını alır veya ayarlar. |
| [UseVectorColor](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/usevectorcolor/) { get; set; } | Vektör rengini kullanma bayrağı. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/save/)(StreamContainer, int) | Kaynak verilerini belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/grdmresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

## Örnekler

Aşağıdaki kod, GrdmResource kaynağının desteğini gösterir.

```csharp
[C#]

string sourceFile = "gradient_map_default.psd";
string outputFile = "gradient_map_res.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
            
    // geçerli değerleri kontrol et
    AssertAreEqual(false, grdmResource.Reverse);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)65535, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
            
            
    grdmResource.Reverse = true;
    // İkinci degrade renk noktası için kırmızı renk
    grdmResource.ColorPoints[1].RawColor.Components[1].Value = ushort.MaxValue;
    grdmResource.ColorPoints[1].RawColor.Components[2].Value = 0;
    grdmResource.ColorPoints[1].RawColor.Components[3].Value = 0;

    image.Save(outputFile, new PsdOptions());
}

using (var image = (PsdImage)Image.Load(outputFile))
{
    Layer layer = image.Layers[1];
    GrdmResource grdmResource = (GrdmResource)layer.Resources[0];
    
    // değiştirilen değerleri kontrol et
    AssertAreEqual(true, grdmResource.Reverse);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[2].Value);
    AssertAreEqual((ulong)0, grdmResource.ColorPoints[1].RawColor.Components[3].Value);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### Ayrıca Bakınız

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


