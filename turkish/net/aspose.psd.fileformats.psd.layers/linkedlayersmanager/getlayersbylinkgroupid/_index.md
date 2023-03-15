---
title: LinkedLayersManager.GetLayersByLinkGroupId
second_title: Aspose.PSD for .NET API Referansı
description: LinkedLayersManager yöntem. Bağlantı grubu kimliğine göre katmanları alır.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/
---
## LinkedLayersManager.GetLayersByLinkGroupId method

Bağlantı grubu kimliğine göre katmanları alır.

```csharp
public Layer[] GetLayersByLinkGroupId(short linkGroupId)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| linkGroupId | Int16 | Bağlantı grubu kimliği. |

### Geri dönüş değeri

Katmanlar dizisi.

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


