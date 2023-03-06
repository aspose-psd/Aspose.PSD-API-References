---
title: TextLayer.TransformMatrix
second_title: Aspose.PSD for .NET API Referansı
description: TextLayer mülk. Dönüşüm matrisini alır veya ayarlar
type: docs
weight: 70
url: /tr/net/aspose.psd.fileformats.psd.layers/textlayer/transformmatrix/
---
## TextLayer.TransformMatrix property

Dönüşüm matrisini alır veya ayarlar

```csharp
public double[] TransformMatrix { get; set; }
```

### Mülk değeri

Dönüşüm matrisi

### Örnekler

Aşağıdaki kod, metin katmanındaki herhangi bir metin bölümü için yazı tipi boyutunun nasıl alınacağını gösterir.

```csharp
[C#]

// Yanlış Font boyutu çıkartıldı 
string filePath = "直播+电商.psd";

var tolerance = 0.001;
using (var image = Image.Load(filePath))
{
    int layerIndex = 22;

    // Eski API (İlk paragraf yazı tipi kullanılarak)
    PsdImage psdImage = image as PsdImage;
    double[] matrix = ((TextLayer)psdImage.Layers[layerIndex]).TransformMatrix;
    double baseFontSize = ((TextLayer)psdImage.Layers[layerIndex]).Font.Size;
    double fontSize = matrix[0] * baseFontSize;

    // Temel yazı tipi boyutunu kontrol etme
    if (Math.Abs(100.0 - baseFontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Gerçek yazı tipi boyutunu kontrol etme
    if (Math.Abs(88.425 - fontSize) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }

    // Yeni API (Bir metin katmanı herhangi bir miktarda yazı tipi boyutu içerebilir)
    ITextPortion[] portions = ((TextLayer)psdImage.Layers[layerIndex]).TextData.Items;
    ITextStyle style = portions[0].Style;
    double fontSizeOfPortion = matrix[0] * style.FontSize;

    // Taban kısmı yazı tipi boyutunun kontrol edilmesi
    if (Math.Abs(100.0 - style.FontSize) > tolerance)
    {
        throw new Exception("Font size was read incorrect");
    }

    // Gerçek kısım yazı tipi boyutunu kontrol etme
    if (Math.Abs(88.425 - fontSizeOfPortion) > tolerance)
    {
        throw new Exception("TransformMatrix was read incorrect");
    }
}
```

### Ayrıca bakınız

* class [TextLayer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* toplantı [Aspose.PSD](../../../)


