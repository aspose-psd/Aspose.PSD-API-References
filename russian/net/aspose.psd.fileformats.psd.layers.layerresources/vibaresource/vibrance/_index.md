---
title: "VibAResource.Vibrance"
second_title: "Справочник API Aspose.PSD для .NET"
description: "VibAResource свойство. Получает или задает значение яркости"
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibrance/
---
{{< psd/tize >}}
## VibAResource.Vibrance property

Получает или задает значение вибранса

```csharp
public int Vibrance { get; set; }
```

## Примеры

Следующий пример кода демонстрирует поддержку ресурса VibAResource.

```csharp
[C#]

// Пример поддержки чтения и записи ресурса вибрации во время выполнения.
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### См. также

* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


