---
title: TextLayer.Resize
second_title: Aspose.PSD für .NET-API-Referenz
description: TextLayer methode. Ändert die Bildgröße. Der StandardLeftTopToLeftTopwird verwendet.
type: docs
weight: 90
url: /de/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
## TextLayer.Resize method

Ändert die Bildgröße. Der StandardLeftTopToLeftTopwird verwendet.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | Int32 | Die neue Breite. |
| newHeight | Int32 | Die neue Höhe. |
| resizeType | ResizeType | Der Typ der Transformation zur Größenänderung[`ResizeType`](../../../aspose.psd/resizetype/) |

### Beispiele

Der folgende Code veranschaulicht die TextLayer.Resize-Funktion mit dem Parameter zum Auswählen des Mechanismus zum Ändern der Größe.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // Es setzt die neue Größe der Textebene
    const int NewWidth = 250;
    const int NewHeight = 250;

    // Es legt den Mechanismus fest, wie die Größenänderungsfunktion die Größe der Ebene ändert (Standardwert)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // Neuer Mechanismus zur Größenänderung für die Textebene, der hier verwendet wird
    // Nicht nur die Ebene, sondern auch die Transformationsmatrix der Textebene wird geändert
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // Grund für Delta ist eine andere Standardschriftart
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // Alles ist ok
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
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* Montage [Aspose.PSD](../../../)


