---
title: "Layer.BlendClippedElements"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Layer ιδιότητα. Λαμβάνει ή ορίζει την ανάμειξη του περικομμένου στοιχείου"
type: docs
weight: 30
url: /el/net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

Λαμβάνει ή ορίζει τη συγχώνευση του περικομμένου στοιχείου.

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

Η ανάμειξη του περικομμένου στοιχείου.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της ιδιότητας BlendClippedElements.

```csharp
[C#]

string sourceFile = "example_source.psd";
string outputPsd = "example_output.psd";
string outputPng = "example_output.png";

using (var image = (PsdImage)Image.Load(sourceFile))
{
    image.Layers[1].BlendClippedElements = false;
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Δείτε επίσης

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


