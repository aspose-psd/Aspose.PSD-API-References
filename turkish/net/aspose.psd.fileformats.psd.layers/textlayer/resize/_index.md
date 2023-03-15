---
title: TextLayer.Resize
second_title: Aspose.PSD for .NET API Referansı
description: TextLayer yöntem. Görüntüyü yeniden boyutlandırır. VarsayılanLeftTopToLeftTopkullanılır.
type: docs
weight: 90
url: /tr/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
## TextLayer.Resize method

Görüntüyü yeniden boyutlandırır. VarsayılanLeftTopToLeftTopkullanılır.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| newHeight | Int32 | Yeni yükseklik. |
| resizeType | ResizeType | Yeniden boyutlandırma dönüşümünün türü[`ResizeType`](../../../aspose.psd/resizetype/) |

### Örnekler

Aşağıdaki kod, yeniden boyutlandırma mekanizmasını seçmek için parametreyle birlikte TextLayer.Resize işlevini gösterir.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // Metin katmanının yeni boyutunu ayarlar
    const int NewWidth = 250;
    const int NewHeight = 250;

    // Yeniden boyutlandırma işlevinin katmanı nasıl yeniden boyutlandıracağına ilişkin mekanizmayı ayarlar (varsayılan değer)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // Burada kullanılan metin katmanı için yeni yeniden boyutlandırma mekanizması
    // Sadece katman değil, metin katmanının dönüşüm matrisi de değişecek
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // Delta'nın nedeni farklı varsayılan yazı tipi
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // Her şey yolunda
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### Ayrıca bakınız

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* toplantı [Aspose.PSD](../../../)


