---
title: "Layer.ApplyLayerMask"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος Layer. Εφαρμόζει τη μάσκα στρώματος στο στρώμα και στη συνέχεια διαγράφει τη μάσκα"
type: docs
weight: 350
url: /el/net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

Εφαρμόζει τη μάσκα στρώσης στο στρώμα, στη συνέχεια διαγράφει τη μάσκα.

```csharp
public void ApplyLayerMask()
```

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα εφαρμογής μάσκας στο στρώμα.

```csharp
[C#]

var sourceFile = "example.psd";
var outFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    psdImage.Layers[1].ApplyLayerMask();

    psdImage.Save(outFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Δείτε επίσης

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


