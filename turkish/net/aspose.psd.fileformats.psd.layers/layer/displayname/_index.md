---
title: Layer.DisplayName
second_title: Aspose.PSD for .NET API Referansı
description: Layer mülk. Katmanın görünen adını alır veya ayarlar.
type: docs
weight: 100
url: /tr/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
## Layer.DisplayName property

Katmanın görünen adını alır veya ayarlar.

```csharp
public string DisplayName { get; set; }
```

### Mülk değeri

Katmanın görünen adı.

### Örnekler

Aşağıdaki örnek, katman adının doğru görüntülenmesinde DisplayName değerini ayarlama becerisini gösterir.

```csharp
[C#]

// katman adlarında değişiklikler yapın ve kaydedin
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // DisplayName özelliğine yeni değer ayarla
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### Ayrıca bakınız

* class [Layer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* toplantı [Aspose.PSD](../../../)


