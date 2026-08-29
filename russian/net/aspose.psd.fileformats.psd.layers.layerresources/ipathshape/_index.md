---
title: "Интерфейс IPathShape"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IPathShape интерфейс. Фигура из узлов кривой Безье"
type: docs
weight: 2810
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---
{{< psd/tize >}}
## IPathShape interface

Фигура, полученная из узлов кривой Безье.

```csharp
public interface IPathShape
```

## Свойства

| Имя | Описание |
| --- | --- |
| [IsClosed](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/isclosed/) { get; set; } | Получает или задает свойство, определяющее, закрыта ли Фигура. |
| [PathOperations](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/pathoperations/) { get; set; } | Операции объединения форм пути (логические операции). |

## Методы

| Имя | Описание |
| --- | --- |
| [GetItems](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/getitems/)() | Получает массив узлов Безье. |
| [SetItems](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/setitems/)(BezierKnotRecord[]) | Назначает массив узлов Bexier. |

## Примеры

Следующий код демонстрирует объекты пути из ресурсов vsms или vmsk для ShapeLayer.

```csharp
[C#]

string srcFile = "ShapeLayerTest.psd";
string outFile = "ShapeLayerTest-out.psd";

using (PsdImage image = (PsdImage)Image.Load(
    srcFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // Удалить одну фигуру
    shapes.RemoveAt(1);

    // Сохранить изменённые данные в ресурс
    List<VectorPathRecord> path = new List<VectorPathRecord>();
    path.Add(new PathFillRuleRecord(null));
    path.Add(new InitialFillRuleRecord(isFillStartsWithAllPixels));

    for (ushort i = 0; i < shapes.Count; i++)
    {
        PathShape shape = (PathShape)shapes[i];
        shape.ShapeIndex = i;
        path.AddRange(shape.ToVectorPathRecords());
    }

    vectorPathDataResource.Paths = path.ToArray();

    image.Save(outFile);
}

// Проверьте изменённые значения в сохранённом файле
using (PsdImage image = (PsdImage)Image.Load(
    outFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // Сохранённый файл должен содержать 1 фигуру
    AssertAreEqual(1, shapes.Count);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

List<IPathShape> GetShapesFromResource(
    VectorPathDataResource vectorPathDataResource,
    out bool isFillStartsWithAllPixels)
{
    List<IPathShape> shapes = new List<IPathShape>();
    LengthRecord lengthRecord = null;
    isFillStartsWithAllPixels = false;
    List<BezierKnotRecord> bezierKnotRecords = new List<BezierKnotRecord>();

    foreach (var pathRecord in vectorPathDataResource.Paths)
    {
        if (pathRecord is LengthRecord)
        {
            if (bezierKnotRecords.Count > 0)
            {
                shapes.Add(new PathShape(lengthRecord, bezierKnotRecords.ToArray()));
                lengthRecord = null;
                bezierKnotRecords.Clear();
            }

            lengthRecord = (LengthRecord)pathRecord;
        }
        else if (pathRecord is BezierKnotRecord)
        {
            bezierKnotRecords.Add((BezierKnotRecord)pathRecord);
        }
        else if (pathRecord is InitialFillRuleRecord)
        {
            InitialFillRuleRecord initialFillRuleRecord = (InitialFillRuleRecord)pathRecord;
            isFillStartsWithAllPixels = initialFillRuleRecord.IsFillStartsWithAllPixels;
        }
    }

    if (bezierKnotRecords.Count > 0)
    {
        shapes.Add(new PathShape(lengthRecord, bezierKnotRecords.ToArray()));
        lengthRecord = null;
        bezierKnotRecords.Clear();
    }

    return shapes;
}
```

### См. также

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


