---
title: "Layer.IsVisible"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Layer-Eigenschaft. Gibt einen Wert zurück oder legt ihn fest, der angibt, ob die Ebene sichtbar ist"
type: docs
weight: 180
url: /de/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
{{< psd/tize >}}
## Layer.IsVisible property

Liefert oder setzt einen Wert, der angibt, ob die Ebene sichtbar ist

```csharp
public bool IsVisible { get; set; }
```

### Property Value

`true` wenn diese Instanz sichtbar ist; andernfalls `false`.

## Beispiele

Das folgende Beispiel zeigt, wie Sie die Sichtbarkeit von LayerGroup in Aspose.PSD ändern können

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// Nehmen Sie Änderungen an Ebenennamen vor und speichern Sie sie
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Schalten Sie alles innerhalb einer Gruppe aus
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### Siehe auch

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


