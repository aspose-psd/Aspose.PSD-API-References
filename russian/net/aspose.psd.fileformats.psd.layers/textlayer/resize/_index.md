---
title: "TextLayer.Resize"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод TextLayer. Изменяет размер изображения. По умолчанию используется LeftTopToLeftTop"
type: docs
weight: 100
url: /ru/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
{{< psd/tize >}}
## TextLayer.Resize method

Изменяет размер изображения. Используется значение по умолчанию LeftTopToLeftTop.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | Int32 | Новая ширина. |
| newHeight | Int32 | Новая высота. |
| resizeType | ResizeType | Тип преобразования изменения размера [`ResizeType`](../../../aspose.psd/resizetype/) |

## Примеры

Следующий код демонстрирует функцию TextLayer.Resize с параметром, позволяющим выбрать механизм изменения размера.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // Устанавливает новый размер текстового слоя
    const int NewWidth = 250;
    const int NewHeight = 250;

    // Устанавливает механизм того, как функция изменения размера будет изменять слой (значение по умолчанию)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // Новый механизм изменения размера для текстового слоя, используемый здесь
    // Будут изменены не только слой, но и матрица преобразования текстового слоя.
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // Причина дельты — другой шрифт по умолчанию
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // Все в порядке
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### См. также

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


