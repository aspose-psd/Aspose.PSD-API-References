---
title: LayerGroup.IsOpen
second_title: Aspose.PSD for .NET API Referansı
description: LayerGroup mülk. Alır veya ayarlar klasörü açılır olarak ayarlanırsadoğru grup başlangıçta açık durumda aksi takdirde küçültülmüş durumda olacaktır.
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
## LayerGroup.IsOpen property

Alır veya ayarlar klasörü açılır olarak ayarlanırsa`doğru` grup başlangıçta açık durumda, aksi takdirde küçültülmüş durumda olacaktır.

```csharp
public bool IsOpen { get; set; }
```

### Örnekler

Aşağıdaki kod, IsOpen özelliği kullanılarak LayerGroup'un (Klasör) nasıl açılıp kapatılacağını gösterir.

```csharp
[C#]

// Çalışma zamanında IsOpen özelliğini okuma ve yazma örneği.
string sourceFileName = "LayerGroupOpenClose.psd";
string outputFileName = "OutputLayerGroupOpenClose.psd";

using (var image = (PsdImage) Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        if (layer is LayerGroup && layer.Name == "Group 1")
        {
            bool isOpenedGroup1 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup1;
        }

        if (layer is LayerGroup && layer.Name == "Group 2")
        {
            bool isOpenedGroup2 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup2;
        }
    }

    image.Save(outputFileName);
}
```

### Ayrıca bakınız

* class [LayerGroup](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* toplantı [Aspose.PSD](../../../)


