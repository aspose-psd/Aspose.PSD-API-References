---
title: "Класс NvrtResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.NvrtResource class. Класс NvrtResource. Ресурс слоя корректировки Инвертировать."
type: docs
weight: 3180
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/
---
{{< psd/tize >}}
## NvrtResource class

Класс NvrtResource. Ресурс слоя коррекции Invert.

```csharp
public class NvrtResource : AdjustmentLayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [NvrtResource](nvrtresource/#constructor)() | Инициализирует новый экземпляр класса `NvrtResource`. |
| [NvrtResource](nvrtresource/#constructor_1)(byte[]) | Инициализирует новый экземпляр класса `NvrtResource`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 указывает на отсутствие ограничений. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Получает подпись. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/save/)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/typetoolkey/) | Ключ информации о типе инструмента. |

## Примеры

Следующий пример демонстрирует, как получить NvrtResource.

```csharp
[C#]

string sourceFilePath = "InvertAdjustmentLayer.psd";
NvrtResource resource = null;
using (PsdImage psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    foreach (Aspose.PSD.FileFormats.Psd.Layers.Layer layer in psdImage.Layers)
    {
        if (layer is InvertAdjustmentLayer)
        {
            foreach (Aspose.PSD.FileFormats.Psd.Layers.LayerResource layerResource in layer.Resources)
            {
                if (layerResource is NvrtResource)
                {
                    // NvrtResource поддерживается.
                    resource = (NvrtResource)layerResource;
                    break;
                }
            }
        }
    }
}
```

### См. также

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


