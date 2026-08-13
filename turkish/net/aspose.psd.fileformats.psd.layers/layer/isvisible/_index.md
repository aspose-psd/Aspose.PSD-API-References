---
title: "Layer.IsVisible"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Layer özelliği. Katmanın görünür olup olmadığını gösteren bir değeri alır veya ayarlar"
type: docs
weight: 180
url: /tr/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
{{< psd/tize >}}
## Layer.IsVisible property

Katmanın görünür olup olmadığını gösteren bir değeri alır veya ayarlar

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` eğer bu örnek görünürse; aksi takdirde `false`.

## Örnekler

Aşağıdaki örnek, Aspose.PSD içinde LayerGroup görünürlüğünü nasıl değiştirebileceğinizi gösterir.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// katman adlarında değişiklik yapın ve kaydedin
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Bir grup içindeki her şeyi kapat
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### Ayrıca Bakınız

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


