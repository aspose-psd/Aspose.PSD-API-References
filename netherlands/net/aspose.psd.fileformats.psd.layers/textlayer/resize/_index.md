---
title: TextLayer.Resize
second_title: Aspose.PSD voor .NET API-referentie
description: TextLayer methode. Wijzigt de grootte van de afbeelding. De standaardLeftTopToLeftTopwordt gebruikt.
type: docs
weight: 90
url: /nl/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
## TextLayer.Resize method

Wijzigt de grootte van de afbeelding. De standaardLeftTopToLeftTopwordt gebruikt.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | Int32 | De nieuwe breedte. |
| newHeight | Int32 | De nieuwe hoogte. |
| resizeType | ResizeType | Het type formaatwijzigingstransformatie[`ResizeType`](../../../aspose.psd/resizetype/) |

### Voorbeelden

De volgende code demonstreert de functie TextLayer.Resize met de parameter om het mechanisme voor het wijzigen van de grootte te kiezen.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // Het stelt een nieuwe grootte van de tekstlaag in
    const int NewWidth = 250;
    const int NewHeight = 250;

    // Het stelt het mechanisme in voor hoe de formaatwijzigingsfunctie het formaat van de laag zal wijzigen (standaardwaarde)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // Nieuw mechanisme voor het wijzigen van de grootte van de tekstlaag hier
    // Niet alleen de laag maar ook de transformatiematrix van de tekstlaag wordt gewijzigd
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // Reden van delta is een ander standaardlettertype
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // Alles is oke
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### Zie ook

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* montage [Aspose.PSD](../../../)


