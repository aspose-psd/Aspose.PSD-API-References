---
title: Enum PathOperations
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations перечисление. Операции для объединения фигур пути логические операции.
type: docs
weight: 1390
url: /ru/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
## PathOperations enumeration

Операции для объединения фигур пути (логические операции).

```csharp
public enum PathOperations
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Исключить перекрывающиеся фигуры (операция XOR). |
| CombineShapes | `1` | Объединить фигуры (операция ИЛИ). Это значение по умолчанию в Photoshop. |
| SubtractFrontShape | `2` | Вычесть переднюю форму (НЕ операция). |
| IntersectShapeAreas | `3` | Пересечение областей формы (операция И). |

### Примеры

В следующем примере кода демонстрируется поддержка новых свойств LengthRecord, PathOperations (логические операции), ShapeIndex и BezierKnotRecordsCount.

```csharp
[C#]

string sourceFilePath = "PathOperationsShape.psd";
string outputFilePath = "out_PathOperationsShape.psd";

using (var im = (PsdImage)Image.Load(sourceFilePath))
{
    VsmsResource resource = null;
    foreach (var layerResource in im.Layers[1].Resources)
    {
        if (layerResource is VsmsResource)
        {
            resource = (VsmsResource)layerResource;
            break;
        }
    }

    LengthRecord lengthRecord0 = (LengthRecord)resource.Paths[2];
    LengthRecord lengthRecord1 = (LengthRecord)resource.Paths[7];
    LengthRecord lengthRecord2 = (LengthRecord)resource.Paths[11];

    // Здесь мы меняем способ объединения фигур.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### Смотрите также

* пространство имен [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* сборка [Aspose.PSD](../../)


