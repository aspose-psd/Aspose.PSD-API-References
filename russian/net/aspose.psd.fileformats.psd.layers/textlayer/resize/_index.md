---
title: TextLayer.Resize
second_title: Справочник по Aspose.PSD для .NET API
description: TextLayer метод. Изменяет размер изображения. По умолчаниюLeftTopToLeftTopиспользуется.
type: docs
weight: 90
url: /ru/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
## TextLayer.Resize method

Изменяет размер изображения. По умолчаниюLeftTopToLeftTopиспользуется.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | Int32 | Новая ширина. |
| newHeight | Int32 | Новая высота. |
| resizeType | ResizeType | Тип преобразования размера[`ResizeType`](../../../aspose.psd/resizetype/) |

### Примеры

Следующий код демонстрирует функцию TextLayer.Resize с параметром для выбора механизма изменения размера.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // Он устанавливает новый размер текстового слоя
    const int NewWidth = 250;
    const int NewHeight = 250;

    // Он устанавливает механизм того, как функция изменения размера будет изменять размер слоя (значение по умолчанию)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // Здесь используется новый механизм изменения размера текстового слоя
    // Будет изменен не только слой, но и матрица преобразования текстового слоя
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

### Смотрите также

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* сборка [Aspose.PSD](../../../)


