---
title: Class LclrResource
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LclrResource сорт. Класс LclrResource. Этот ресурс содержит информацию о цвете слоя в списке слоев PS. Это только
type: docs
weight: 2620
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/
---
## LclrResource class

Класс LclrResource. Этот ресурс содержит информацию о цвете слоя в списке слоев PS. Это только

```csharp
public class LclrResource : LayerResource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LclrResource](lclrresource/#constructor)() | Инициализирует новый экземпляр`LclrResource` класс. |
| [LclrResource](lclrresource/#constructor_2)(byte[]) | Инициализирует новый экземпляр`LclrResource` класс. |
| [LclrResource](lclrresource/#constructor_1)(SheetColorHighlightEnum) | Инициализирует новый экземпляр`LclrResource` класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/) { get; set; } | Получает или задает цвет слоя. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/key/) { get; } | Получает ключ ресурса слоя. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/length/) { get; } | Получает длину ресурса слоя в байтах. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/psdversion/) { get; } | Получает версию psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/signature/) { get; } | Получает подпись. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/save/)(StreamContainer, int) | Сохраняет ресурс в указанный контейнер потока. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | ВозвращаетString который представляет этот экземпляр. |

## Поля

| Имя | Описание |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/lclrresource/typetoolkey/) | Информационный ключ типа инструмента. |

### Примеры

В следующем примере показано, как можно изменить выделение цветом листа в Aspose.PSD (настройка цвета листа).

```csharp
[C#]

string sourceFilePath = "AllLclrResourceColors.psd";
string outputFilePath = "AllLclrResourceColorsReversed.psd";

// В файле цвета выделения слоев идут в таком порядке
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

// Цвет листа слоя используется для визуального выделения слоев. 
// Например, вы можете обновить некоторые слои в PSD, а затем выделить цветом слой, который вы хотите привлечь внимание.
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
            // Ресурс lcrl всегда присутствует в списке ресурсов файла psd.
            LclrResource resource = layerResource as LclrResource;
            if (resource != null)
            {
                if (resource.Color != sheetColors[layerIndex])
                {
                    throw new Exception("Sheet Color has been read wrong");
                }

                // Инверсия цветов таблицы стилей. Настройка выделения цветом слоя.
                resource.Color = sheetColors[layersCount - layerIndex - 1];
                break;
            }
        }
    }
}
```

### Смотрите также

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* сборка [Aspose.PSD](../../)


