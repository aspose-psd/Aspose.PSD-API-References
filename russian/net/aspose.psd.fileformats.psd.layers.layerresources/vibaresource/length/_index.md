---
title: VibAResource.Length
second_title: Справочник по Aspose.PSD для .NET API
description: VibAResource свойство. Получает длину ресурса слоя в байтах.
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length/
---
## VibAResource.Length property

Получает длину ресурса слоя в байтах.

```csharp
public override int Length { get; }
```

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

* class [VibAResource](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* сборка [Aspose.PSD](../../../)


