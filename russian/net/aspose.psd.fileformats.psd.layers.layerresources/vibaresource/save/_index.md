---
title: "VibAResource.Save"
second_title: "Справочник API Aspose.PSD для .NET"
description: "VibAResource метод. Сохраняет ресурс в указанный потоковый контейнер"
type: docs
weight: 50
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
{{< psd/tize >}}
## VibAResource.Save method

Сохраняет ресурс в указанный контейнер потока.

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | StreamContainer | Контейнер потока, в который будет сохраняться. |
| psdVersion | Int32 | Версия PSD. |

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

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


