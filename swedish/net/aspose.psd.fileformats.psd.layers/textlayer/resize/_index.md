---
title: "TextLayer.Resize"
second_title: "Aspose.PSD för .NET API‑referens"
description: "TextLayer-metod. Ändrar storlek på bilden. Standardvärdet LeftTopToLeftTop används"
type: docs
weight: 100
url: /sv/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
{{< psd/tize >}}
## TextLayer.Resize method

Ändrar storlek på bilden. Standardvärdet LeftTopToLeftTop används.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | Int32 | Den nya bredden. |
| newHeight | Int32 | Den nya höjden. |
| resizeType | ResizeType | Typen av storleksändringstransformation [`ResizeType`](../../../aspose.psd/resizetype/) |

## Exempel

Följande kod visar TextLayer.Resize-funktionen med parametern för att välja mekanismen för storleksändring.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // Den anger ny storlek för textlagret
    const int NewWidth = 250;
    const int NewHeight = 250;

    // Den anger mekanismen för hur resize-funktionen kommer att ändra storlek på lagret (standardvärde)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // Ny mekanism för storleksändring av textlager som används här
    // Inte bara lagret utan även transformationsmatrisen för textlagret kommer att ändras
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // Anledningen till delta är ett annat standardteckensnitt
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // Allt är OK
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### Se även

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


