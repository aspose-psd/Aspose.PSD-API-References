---
title: Class LinkedLayersManager
second_title: Aspose.PSD for .NET API Referansı
description: Aspose.PSD.FileFormats.Psd.Layers.LinkedLayersManager sınıf. Bağlantılı katmanlar yöneticisi sınıfı.
type: docs
weight: 3400
url: /tr/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---
## LinkedLayersManager class

Bağlantılı katmanlar yöneticisi sınıfı.

```csharp
public sealed class LinkedLayersManager
```

## yöntemler

| İsim | Tanım |
| --- | --- |
| [GetLayersByLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/)(short) | Bağlantı grubu kimliğine göre katmanları alır. |
| [GetLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/)(Layer) | Katmanla ilişkili bağlantı grubu kimliğini alır. |
| [LinkLayers](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/)(Layer[]) | Giriş katmanlarını birbirine bağlar ve LingGroupId. döndürür. |
| [UnlinkLayer](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/)(Layer) | Katmanın bağlantısını kaldırır.. |

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

* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* toplantı [Aspose.PSD](../../)


