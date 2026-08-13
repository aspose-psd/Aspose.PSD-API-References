---
title: "Sınıf LinkedLayersManager"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LinkedLayersManager sınıfı. Bağlantılı katman yöneticisi sınıfı"
type: docs
weight: 3800
url: /tr/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/
---
{{< psd/tize >}}
## LinkedLayersManager class

Bağlantılı katmanlar yöneticisi sınıfı.

```csharp
public sealed class LinkedLayersManager
```

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetLayersByLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/)(short) | Katmanları bağlantı grup kimliğine göre alır. |
| [GetLinkGroupId](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlinkgroupid/)(Layer) | Katmanla ilişkili bağlantı grup kimliğini alır. |
| [LinkLayers](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/)(Layer[]) | Girdi katmanlarını bağlar ve LinkGroupId döndürür. |
| [UnlinkLayer](../../aspose.psd.fileformats.psd.layers/linkedlayersmanager/unlinklayer/)(Layer) | Katmanın bağlantısını kaldırır.. |

## Örnekler

Aşağıdaki örnek, Aspose.PSD içinde Bağlantılı Katmanları nasıl manipüle edebileceğinizi gösterir

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Mevcut bir görüntüyü PsdImage sınıfının bir örneğine yükle
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // Tüm katmanları tek bir bağlantılı grupta bağla
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // Bir katman için kimlik alır
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // Bağlantı grup kimliğine göre tüm bağlantılı katmanları alır.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // Her katmanın gruptaki bağlantısını kaldır
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // Grup içinde katman olmayan bir bağlantı grup kimliği için NULL döndürür.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### Ayrıca Bakınız

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


