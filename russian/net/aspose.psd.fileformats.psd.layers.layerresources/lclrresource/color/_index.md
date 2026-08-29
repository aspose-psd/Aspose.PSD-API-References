---
title: "LclrResource.Color"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство LclrResource. Получает или задаёт цвет слоя"
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/color/
---
{{< psd/tize >}}
## LclrResource.Color property

Получает или задаёт цвет слоя.

```csharp
public SheetColorHighlightEnum Color { get; set; }
```

### Property Value

Цвет.

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

* enum [SheetColorHighlightEnum](../../sheetcolorhighlightenum/)
* class [LclrResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


