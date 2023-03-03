---
title: TextLayer.Resize
second_title: Aspose.PSD για Αναφορά API .NET
description: TextLayer μέθοδος. Αλλάζει το μέγεθος της εικόνας. Η προεπιλεγμένηLeftTopToLeftTopχρησιμοποιείται.
type: docs
weight: 90
url: /el/net/aspose.psd.fileformats.psd.layers/textlayer/resize/
---
## TextLayer.Resize method

Αλλάζει το μέγεθος της εικόνας. Η προεπιλεγμένηLeftTopToLeftTopχρησιμοποιείται.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | Int32 | Το νέο πλάτος. |
| newHeight | Int32 | Το νέο ύψος. |
| resizeType | ResizeType | Ο τύπος μετασχηματισμού αλλαγής μεγέθους[`ResizeType`](../../../aspose.psd/resizetype/) |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη συνάρτηση TextLayer.Resize με την παράμετρο για να επιλέξετε τον μηχανισμό αλλαγής μεγέθους.

```csharp
[C#]

string sourceFileName = "TextLayer.psd";
string outputFile = "TextLayerResized_output.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    TextLayer textLayer = (TextLayer)image.Layers[1];

    // Ορίζει νέο μέγεθος του επιπέδου κειμένου
    const int NewWidth = 250;
    const int NewHeight = 250;

    // Ορίζει τον μηχανισμό για τον τρόπο με τον οποίο η συνάρτηση αλλαγής μεγέθους θα αλλάξει το μέγεθος του επιπέδου (προεπιλεγμένη τιμή)
    ResizeType resizeType = ResizeType.NearestNeighbourResample;

    // Νέος μηχανισμός αλλαγής μεγέθους για επίπεδο κειμένου χρησιμοποιώντας εδώ
    // Όχι μόνο το επίπεδο αλλά και ο πίνακας μετασχηματισμού του επιπέδου κειμένου θα αλλάξει
    textLayer.Resize(NewWidth, NewHeight, resizeType);

    image.Save(outputFile, new PsdOptions(image));
}

using (PsdImage image = (PsdImage)Image.Load(outputFile, new PsdLoadOptions()))
{
    TextLayer txtLayer = (TextLayer)image.Layers[1];

    // Ο λόγος του delta είναι διαφορετική προεπιλεγμένη γραμματοσειρά
    if (txtLayer.TransformMatrix[4] >= 65 
        && txtLayer.TransformMatrix[4] <= 67
        && txtLayer.TransformMatrix[5] >= 234
        && txtLayer.TransformMatrix[5] <= 237)
    {
        // Ολα είναι εντάξει
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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../textlayer/)
* συνέλευση [Aspose.PSD](../../../)


