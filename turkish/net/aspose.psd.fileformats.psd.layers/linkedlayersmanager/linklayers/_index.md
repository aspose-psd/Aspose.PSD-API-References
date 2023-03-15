---
title: LinkedLayersManager.LinkLayers
second_title: Aspose.PSD for .NET API Referansı
description: LinkedLayersManager yöntem. Giriş katmanlarını birbirine bağlar ve LingGroupId. döndürür.
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/
---
## LinkedLayersManager.LinkLayers method

Giriş katmanlarını birbirine bağlar ve LingGroupId. döndürür.

```csharp
public short LinkLayers(Layer[] layers)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| layers | Layer[] | katmanlar |

### Geri dönüş değeri

Bağlantı grubu kimliği.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Katmanlar boş. |
| ArgumentException | Katman sayısı 1'den büyük olmalıdır. |
| ArgumentException | Her katmanın kabı, geçerli PsdImage ile aynı olmalıdır. |

### Örnekler

Aşağıdaki örnek, Aspose.PSD'de Bağlantılı Katmanları nasıl değiştirebileceğinizi göstermektedir.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Varolan bir görüntüyü PsdImage sınıfının bir örneğine yükleyin
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // tüm katmanları tek bir bağlantılı grupta birleştirin
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // bir katman için kimlik alır
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // tüm bağlantılı katmanları bağlantı grubu kimliğine göre alır.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // gruptan her katmanın bağlantısını kaldır
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // grupta katman olmayan bir bağlantı grubu kimliği için NULL değerini alır.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### Ayrıca bakınız

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../linkedlayersmanager/)
* toplantı [Aspose.PSD](../../../)


