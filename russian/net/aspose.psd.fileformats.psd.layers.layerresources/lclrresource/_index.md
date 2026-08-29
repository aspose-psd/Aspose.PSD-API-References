---
title: "Класс LclrResource"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource класс. Класс LclrResource. Этот ресурс содержит информацию о цвете слоя в списке слоёв PS. Только"
type: docs
weight: 2930
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
{{< psd/tize >}}
## LclrResource class

Класс LclrResource. Этот ресурс содержит информацию о цвете слоя в списке слоёв PS. Это только

```csharp
public class LclrResource : LayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | Инициализирует новый экземпляр класса `LclrResource`. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | Инициализирует новый экземпляр класса `LclrResource`. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | Инициализирует новый экземпляр класса `LclrResource`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | Получает или задаёт цвет слоя. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 указывает на отсутствие ограничений. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Получает подпись. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Возвращает строку, представляющую этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | Ключ информации о типе инструмента. |

## Примеры

Следующий пример демонстрирует, как можно изменить выделение цвета листа в Aspose.PSD (настройка цвета листа).

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// В файле цвета выделения слоёв идут в следующем порядке
SheetColorHighlightEnum[] sheetColorsArr = new SheetColorHighlightEnum[] {
    SheetColorHighlightEnum.Red,
    SheetColorHighlightEnum.Orange,
    SheetColorHighlightEnum.Yellow,
    SheetColorHighlightEnum.Green,
    SheetColorHighlightEnum.Blue,
    SheetColorHighlightEnum.Violet,
    SheetColorHighlightEnum.Gray,
    SheetColorHighlightEnum.NoColor
};

// Цвет листа слоя используется для визуального выделения слоёв.
// Например, вы можете обновить некоторые слои в PSD, а затем выделить цветом слой, на который хотите обратить внимание.
using (PsdImage img = (PsdImage)Image.Load(sourceFilePath))
{
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
    img.Save(outputFilePath, new PsdOptions());
}

using (PsdImage img = (PsdImage)Image.Load(outputFilePath))
{
    // Цвета должны быть инвертированы
    Array.Reverse(sheetColorsArr);
    CheckSheetColorsAndRerverse(sheetColorsArr, img);
}

void CheckSheetColorsAndRerverse(SheetColorHighlightEnum[] sheetColors, PsdImage img)
{
    int layersCount = img.Layers.Length;
    for (int layerIndex = 0; layerIndex < layersCount; layerIndex++)
    {
        Layer layer = img.Layers[layerIndex];
        LayerResource[] resources = layer.Resources;
        foreach (LayerResource layerResource in resources)
        {
            // Ресурс lcrl всегда присутствует в списке ресурсов PSD‑файла.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Обратные цвета таблицы стилей. Настройка выделения цвета слоя.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### См. также

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


