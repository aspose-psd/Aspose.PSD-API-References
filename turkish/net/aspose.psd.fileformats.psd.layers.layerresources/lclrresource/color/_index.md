---
title: LclrResource.Color
second_title: Aspose.PSD for .NET API Referansı
description: LclrResource mülk. Katmanın rengini alır veya ayarlar.
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/
---
## LclrResource.Color property

Katmanın rengini alır veya ayarlar.

```csharp
public SheetColorHighlightEnum Color { get; set; }
```

### Mülk değeri

Renk.

### Örnekler

Aşağıdaki örnek, Aspose.PSD'de (Sayfa rengi ayarı) Sheet Color Highlight'ı nasıl değiştirebileceğinizi gösterir.

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// Dosyada katmanların vurgulama renkleri bu sıradadır.
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

// Katman Sayfası Rengi, katmanları görsel olarak vurgulamak için kullanılır. 
// Örneğin, PSD'de bazı katmanları güncelleyebilir ve ardından dikkat çekmek istediğiniz katmanı renklendirerek vurgulayabilirsiniz.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // Renkler ters çevrilmeli
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
            // lcrl kaynağı her zaman psd dosyası kaynak listesinde bulunur.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Stil sayfası renklerinin tersi. Katman rengi vurgulamasının ayarlanması.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Ayrıca bakınız

* enum [SheetColorHighlightEnum](../../sheetcolorhighlightenum/)
* class [LclrResource](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../lclrresource/)
* toplantı [Aspose.PSD](../../../)


