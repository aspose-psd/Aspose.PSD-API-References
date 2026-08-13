---
title: "SheetColorHighlightEnum enum'ı"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.SheetColorHighlightEnum enum. Sayfa renk ayarının olası renkleri. PS'deki katman listesinde katmanın UI dekoratif rengi."
type: docs
weight: 3320
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/
---
{{< psd/tize >}}
## SheetColorHighlightEnum enumeration

Sayfa renk ayarının olası renkleri. PS'deki katmanların listesinde katmanın UI süsleme rengi.

```csharp
public enum SheetColorHighlightEnum : short
```

### Değerler

| Ad | Değer | Açıklama |
| --- | --- | --- |
| NoColor | `0` | Renk belirtilmemiştir. |
| Red | `1` | Kırmızı renk. |
| Orange | `2` | Turuncu renk. |
| Yellow | `3` | Sarı renk. |
| Green | `4` | Yeşil renk. |
| Blue | `5` | Mavi renk. |
| Violet | `6` | Mor renk. |
| Gray | `7` | Gri renk. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


