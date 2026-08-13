---
title: "LinkedLayersManager.LinkLayers"
second_title: "Aspose.PSD for .NET API Referansı"
description: "LinkedLayersManager yöntemi. Girdi katmanlarını bağlar ve LingGroupId döndürür"
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/
---
{{< psd/tize >}}
## LinkedLayersManager.LinkLayers method

Girdi katmanlarını bağlar ve LinkGroupId döndürür.

```csharp
public short LinkLayers(Layer[] layers)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| katmanlar | Layer[] | Katmanlar. |

### Dönüş Değeri

Link grup kimliği.

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | Katmanlar null. |
| ArgumentException | Katman sayısı 1'den büyük olmalıdır. |
| ArgumentException | Her katmanın konteyneri mevcut PsdImage ile aynı olmalıdır. |

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

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


