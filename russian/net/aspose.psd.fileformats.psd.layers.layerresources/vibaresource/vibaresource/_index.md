---
title: "VibAResource.VibAResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Конструктор VibAResource. Инициализирует новый экземпляр класса VibAResource."
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibaresource/
---
{{< psd/tize >}}
## VibAResource constructor

Инициализирует новый экземпляр класса [`VibAResource`](../).

```csharp
public VibAResource()
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


