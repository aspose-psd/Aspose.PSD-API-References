---
title: "Layer.DisplayName"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Layer özelliği. Katmanın görüntüleme adını alır veya ayarlar"
type: docs
weight: 110
url: /tr/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
{{< psd/tize >}}
## Layer.DisplayName property

Katmanın görüntülenen adını alır veya ayarlar.

```csharp
public string DisplayName { get; set; }
```

### Property Value

Katmanın görüntüleme adı.

## Örnekler

Aşağıdaki örnek, DisplayName değerini ayarlama yeteneğini gösterir, böylece katman adı doğru görüntülenir.

```csharp
[C#]

// katman adlarında değişiklik yapın ve kaydedin
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

### Ayrıca Bakınız

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


