---
title: "TextLayer.Resize"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "TextLayer-Methode. Ändert die Größe des Bildes. Der Standardwert LeftTopToLeftTop wird verwendet"
type: docs
weight: 100
url: /de/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
{{< psd/tize >}}
## TextLayer.Resize method

Skaliert das Bild. Der Standard LeftTopToLeftTop wird verwendet.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |
| resizeType | ResizeType | Der Typ der Größenänderungs-Transformation [`ResizeType`](../../../aspose.psd/resizetype/) |

## Beispiele

Der folgende Code demonstriert die TextLayer.Resize-Funktion mit dem Parameter zur Auswahl des Resizing-Mechanismus.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // Sie legt die neue Größe der Textebene fest
    const int NewWidth = 250;
    const int NewHeight = 250;

    // Sie legt den Mechanismus fest, wie die Resize-Funktion die Ebene skalieren soll (Standardwert)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // Neuer Mechanismus zum Ändern der Größe für die Textebene, der hier verwendet wird
    // Nicht nur die Ebene, sondern auch die Transformationsmatrix der Textebene wird geändert
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // Der Grund für das Delta ist eine andere Standardschriftart
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // Alles ist in Ordnung
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### Siehe auch

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


