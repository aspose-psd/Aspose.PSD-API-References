---
title: "Διεπαφή IPathShape"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.IPathShape διεπαφή. Το σχήμα από τους κόμβους της καμπύλης Bezier."
type: docs
weight: 2810
url: /el/net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/
---
{{< psd/tize >}}
## IPathShape interface

Το Σχήμα από τους κόμβους της καμπύλης Bezier.

```csharp
public interface IPathShape
```

## Ιδιότητες

| Όνομα | Περιγραφή |
| --- | --- |
| [IsClosed](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/isclosed/) { get; set; } | Αποκτά ή ορίζει την ιδιότητα που καθορίζει αν το Shape είναι κλειστό. |
| [PathOperations](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/pathoperations/) { get; set; } | Οι λειτουργίες για τον συνδυασμό των σχημάτων διαδρομής (Boolean operations). |

## Μέθοδοι

| Όνομα | Περιγραφή |
| --- | --- |
| [GetItems](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/getitems/)() | Λαμβάνει τον πίνακα των κόμβων Bezier. |
| [SetItems](../../aspose.psd.fileformats.psd.layers.layerresources/ipathshape/setitems/)(BezierKnotRecord[]) | Αναθέτει πίνακα κόμβων Bexier. |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τα αντικείμενα διαδρομής από τους πόρους vsms ή vmsk για το ShapeLayer.

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

    // Αφαίρεση ενός σχήματος
    shapes.RemoveAt(1);

    // Αποθήκευση των τροποποιημένων δεδομένων στον πόρο
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

// Έλεγχος των τροποποιημένων τιμών στο αποθηκευμένο αρχείο
using (PsdImage image = (PsdImage)Image.Load(
    outFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // Το αποθηκευμένο αρχείο πρέπει να έχει 1 σχήμα
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

### Δείτε επίσης

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


