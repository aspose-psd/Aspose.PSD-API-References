---
title: "Sınıf LclrResource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource sınıfı. Sınıf LclrResource. Bu kaynak, PS katman listesindeki katmanın rengi hakkında bilgi içerir. Sadece"
type: docs
weight: 2930
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
{{< psd/tize >}}
## LclrResource class

Sınıf LclrResource. Bu kaynak, katmanların listesinde PS olan katmanın rengi hakkında bilgi içerir. Sadece

```csharp
public class LclrResource : LayerResource
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | `LclrResource` sınıfının yeni bir örneğini başlatır. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | `LclrResource` sınıfının yeni bir örneğini başlatır. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | `LclrResource` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | Katmanın rengini alır veya ayarlar. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Katman kaynağı anahtarını alır. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Katman kaynağı için gereken minimum psd sürümünü alır. 0, sınırlama olmadığını gösterir. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | İmzayı alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | Kaynağı belirtilen akış konteynerine kaydeder. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Bu örneği temsil eden bir String döndürür. |

## Alanlar

| Ad | Açıklama |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | Tip aracı bilgi anahtarı. |

## Örnekler

Aşağıdaki örnek, Aspose.PSD'de Sayfa Renk Vurgusunu (Sayfa renk ayarı) nasıl değiştirebileceğinizi gösterir.

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// Dosyada katmanların vurgulama renkleri bu sıradadır
SheetColorHighlightEnum[] sheetColorsArr = new SheetColorHighlightEnum[] {
    SheetColorHighlightEnum.Red,
    SheetColorHighlightEnum.Orange,
    SheetColorHighlightEnum.Yellow,
    SheetColorHighlightEnum.Green,
    SheetColorHighlightEnum.Blue,
    SheetColorHighlightEnum.Violet,
    SheetColorHighlightEnum.Gray,
    SheetColorHighlightEnum.NoColor
};

// Katman Sayfa Rengi, katmanları görsel olarak vurgulamak için kullanılır.
// Örneğin, PSD'de bazı katmanları güncelleyebilir ve ardından dikkat çekmek istediğiniz katmanı renk ile vurgulayabilirsiniz.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // Renkler ters çevrilmelidir
    Array.Reverse(sheetColorsArr);
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
}

void CheckSheetColorsAndRerverse(SheetColorHighlightEnum[] sheetColors, PsdImage img)
{
    int layersCount = img.Layers.Length;
    for (int layerIndex = 0; layerIndex < layersCount; layerIndex++)
    {
        Layer layer = img.Layers[layerIndex];
        LayerResource[] resources = layer.Resources;
        foreach (LayerResource layerResource in resources)
        {
            // lcrl kaynağı her zaman psd dosya kaynak listesinde bulunur.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Stil sayfası renklerinin ters çevrilmesi. Katman renk vurgusunun ayarlanması.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Ayrıca Bakınız

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


