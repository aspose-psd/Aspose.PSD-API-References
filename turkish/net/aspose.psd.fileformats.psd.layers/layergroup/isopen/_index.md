---
title: "LayerGroup.IsOpen"
second_title: "Aspose.PSD for .NET API Referansı"
description: "LayerGroup özelliği. Klasörün açık olup olmadığını alır veya ayarlar; true olarak ayarlanırsa grup başlangıçta açık durumda olur, aksi takdirde küçültülmüş durumda olur."
type: docs
weight: 30
url: /tr/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
{{< psd/tize >}}
## LayerGroup.IsOpen property

Klasörün açık olup olmadığını alır veya ayarlar; `true` olarak ayarlanırsa grup başlangıçta açık durumda olur, aksi takdirde küçültülmüş durumda.

```csharp
public bool IsOpen { get; set; }
```

## Örnekler

Aşağıdaki kod, IsOpen özelliğini kullanarak LayerGroup (Klasör) nasıl açıp kapatılacağını gösterir.

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

### Ayrıca Bakınız

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


