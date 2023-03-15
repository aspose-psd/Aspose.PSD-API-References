---
title: Layer.IsVisible
second_title: Aspose.PSD for .NET API Referansı
description: Layer mülk. Katmanın görünür olup olmadığını belirten bir değer alır veya ayarlar
type: docs
weight: 170
url: /tr/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
## Layer.IsVisible property

Katmanın görünür olup olmadığını belirten bir değer alır veya ayarlar

```csharp
public bool IsVisible { get; set; }
```

### Mülk değeri

`doğru` bu örnek görünüyorsa; aksi takdirde,`YANLIŞ` .

### Örnekler

Aşağıdaki örnek, Aspose.PSD'de LayerGroup görünürlüğünü nasıl değiştirebileceğinizi göstermektedir.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// katman adlarında değişiklikler yapın ve kaydedin
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Grup içindeki her şeyi kapat
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### Ayrıca bakınız

* class [Layer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* toplantı [Aspose.PSD](../../../)


