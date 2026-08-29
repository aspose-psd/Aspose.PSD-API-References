---
title: "AiLayerSection.ColorIndex"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα AiLayerSection. Λαμβάνει ή ορίζει τον δείκτη του χρώματος. Αυτό το όρισμα μπορεί να έχει τιμές μεταξύ 1 και 26. Κάθε ακέραιος αντιπροσωπεύει ένα χρώμα που μπορεί να ανατεθεί στο στρώμα για σκοπούς ταυτοποίησης χρήστη."
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.ai/ailayersection/colorindex/
---
{{< psd/tize >}}
## AiLayerSection.ColorIndex property

Λαμβάνει ή ορίζει τον δείκτη του χρώματος. Αυτό το όρισμα μπορεί να πάρει τιμές μεταξύ –1 και 26. Κάθε ακέραιος αντιπροσωπεύει ένα χρώμα που μπορεί να ανατεθεί στο στρώμα για σκοπούς ταυτοποίησης χρήστη.

```csharp
public int ColorIndex { get; set; }
```

### Property Value

Ο δείκτης του χρώματος.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη των ιδιοτήτων HasMultiLayerMasks και ColorIndex στην AiLayerSection.

```csharp
[C#]

string sourceFile = "example.ai";
string outputFilePath = "example.png";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AssertAreEqual(image.Layers.Length, 2);
    AssertAreEqual(image.Layers[0].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[0].ColorIndex, -1);
    AssertAreEqual(image.Layers[1].HasMultiLayerMasks, false);
    AssertAreEqual(image.Layers[1].ColorIndex, -1);

    image.Save(outputFilePath, new PngOptions());
}
```

### Δείτε επίσης

* class [AiLayerSection](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


