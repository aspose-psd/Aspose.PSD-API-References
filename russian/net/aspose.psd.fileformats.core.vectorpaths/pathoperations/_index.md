---
title: "Перечисление PathOperations"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.PathOperations перечисление. Операции для комбинирования форм пути с использованием булевых операций"
type: docs
weight: 1400
url: /ru/net/aspose.psd.fileformats.core.vectorpaths/pathoperations/
---
{{< psd/tize >}}
## PathOperations enumeration

Операции объединения форм пути (логические операции).

```csharp
public enum PathOperations
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| ExcludeOverlappingShapes | `0` | Исключить перекрывающиеся формы (операция XOR). |
| CombineShapes | `1` | Объединить формы (операция OR). Это значение по умолчанию в Photoshop. |
| SubtractFrontShape | `2` | Вычесть переднюю форму (операция NOT). |
| IntersectShapeAreas | `3` | Пересечь области форм (операция AND). |

## Примеры

Следующий пример кода демонстрирует поддержку новых свойств LengthRecord, PathOperations (булевые операции), ShapeIndex и BezierKnotRecordsCount.

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

    // Здесь мы меняем способ комбинирования между формами.
    lengthRecord0.PathOperations = PathOperations.ExcludeOverlappingShapes;
    lengthRecord1.PathOperations = PathOperations.IntersectShapeAreas;
    lengthRecord2.PathOperations = PathOperations.SubtractFrontShape;

    im.Save(outputFilePath);
}
```

### См. также

* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


