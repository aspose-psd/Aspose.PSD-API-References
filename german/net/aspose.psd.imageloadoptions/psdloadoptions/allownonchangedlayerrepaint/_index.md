---
title: "PsdLoadOptions.AllowNonChangedLayerRepaint"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdLoadOptions‑Eigenschaft. Gibt an bzw. legt fest, ob die ursprünglichen Pixeldaten der Ebene beim Rendern erhalten bleiben sollen, wenn die Ebene nicht geändert wurde."
type: docs
weight: 20
url: /de/net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

Liest oder setzt, ob die ursprünglichen Ebenenpixel beim Rendern erhalten bleiben sollen, wenn die Ebene nicht verändert wurde.

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true` um die Originalpixel unveränderter Ebenen zu behalten; andernfalls `false`.

## Beispiele

Der folgende Code demonstriert das neue Verhalten, das das automatische Neuzeichnen von Ebenen vor Änderungen verhindert.

```csharp
[C#]

string srcFile = "psdnet2400.psd";
string output1 = "unchanged-2400.png";
string output2 = "updated-2400.png";

using (var psdImage = (PsdImage)Image.Load(srcFile,
new PsdLoadOptions() { AllowNonChangedLayerRepaint = false /* The new default behaviour */ }))
{
    psdImage.Save(output1, new PngOptions());

    ((TextLayer)psdImage.Layers[1]).TextData.UpdateLayerData();

    psdImage.Save(output2, new PngOptions());
}
```

### Siehe auch

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


