---
title: "TextLayer.Resize"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "TextLayer μέθοδος. Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλογή LeftTopToLeftTop"
type: docs
weight: 100
url: /el/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
{{< psd/tize >}}
## TextLayer.Resize method

Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλογή LeftTopToLeftTop.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | Int32 | Το νέο πλάτος. |
| newHeight | Int32 | Το νέο ύψος. |
| resizeType | ResizeType | Ο τύπος της μετασχηματισμού αλλαγής μεγέθους [`ResizeType`](../../../aspose.psd/resizetype/) |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη λειτουργία TextLayer.Resize με την παράμετρο για επιλογή του μηχανισμού αλλαγής μεγέθους.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // Ορίζει νέο μέγεθος της στρώσης κειμένου
    const int NewWidth = 250;
    const int NewHeight = 250;

    // Ορίζει τον μηχανισμό για το πώς η λειτουργία αλλαγής μεγέθους θα αλλάξει το μέγεθος της στρώσης (προεπιλεγμένη τιμή)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // Νέος μηχανισμός αλλαγής μεγέθους για τη στρώση κειμένου που χρησιμοποιείται εδώ
    // Δεν θα αλλάξει μόνο η στρώση, αλλά και ο πίνακας μετασχηματισμού της στρώσης κειμένου
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // Η αιτία του delta είναι διαφορετική προεπιλεγμένη γραμματοσειρά.
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // Όλα είναι εντάξει
    }
    else
    {
        throw new Exception("Location point is wrong");
    }
}
```

### Δείτε επίσης

* enum [ResizeType](../../../aspose.psd/resizetype/)
* class [TextLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


