---
title: "LengthRecord.BezierKnotRecordsCount"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство LengthRecord. Возвращает или задает количество записей узлов Bezier."
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.core.vectorpaths/lengthrecord/bezierknotrecordscount/
---
{{< psd/tize >}}
## LengthRecord.BezierKnotRecordsCount property

Возвращает или задает количество записей узлов Безье.

```csharp
public int BezierKnotRecordsCount { get; set; }
```

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

* class [LengthRecord](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


