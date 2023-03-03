---
title: VibAResource.Save
second_title: Справочник по Aspose.PSD для .NET API
description: VibAResource метод. Сохраняет ресурс в указанный контейнер потока.
type: docs
weight: 70
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
## VibAResource.Save method

Сохраняет ресурс в указанный контейнер потока.

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | StreamContainer | Контейнер потока для сохранения. |
| psdVersion | Int32 | Версия PSD. |

### Примеры

В следующем примере кода демонстрируется поддержка ресурса VibAResource.

```csharp
[C#]

// Пример поддержки чтения и записи Vibration Resource во время выполнения.
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

### Смотрите также

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* сборка [Aspose.PSD](../../../)


