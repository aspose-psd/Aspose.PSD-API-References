---
title: "TextLayer.Resize"
second_title: "Aspose.PSD for .NET API Referansı"
description: "TextLayer yöntemi. Görüntüyü yeniden boyutlandırır. Varsayılan LeftTopToLeftTop kullanılır"
type: docs
weight: 100
url: /tr/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
{{< psd/tize >}}
## TextLayer.Resize method

Görüntünün boyutunu değiştirir. Varsayılan LeftTopToLeftTop kullanılır.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | Int32 | Yeni genişlik. |
| newHeight | Int32 | Yeni yükseklik. |
| resizeType | ResizeType | Yeniden boyutlandırma dönüşümünün türü [`ResizeType`](../../../aspose.psd/resizetype/) |

## Örnekler

Aşağıdaki kod, yeniden boyutlandırma mekanizmasını seçmek için parametreyle TextLayer.Resize işlevini gösterir.

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

    // Yeniden boyutlandırma işlevinin katmanı nasıl yeniden boyutlandıracağını belirleyen mekanizmayı ayarlar (varsayılan değer)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // Metin katmanı için burada kullanılan yeni yeniden boyutlandırma mekanizması
    // Sadece katman değil, aynı zamanda metin katmanının dönüşüm matrisi de değiştirilecektir
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // Delta'nın nedeni farklı varsayılan yazı tipidir.
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // Her şey tamam
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### Ayrıca Bakınız

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


