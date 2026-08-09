---
title: "Layer.DisplayName"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Layer-Eigenschaft. Gibt den Anzeigenamen der Ebene zurück oder legt ihn fest"
type: docs
weight: 110
url: /de/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
{{< psd/tize >}}
## Layer.DisplayName property

Liest oder setzt den Anzeigenamen der Ebene.

```csharp
public string DisplayName { get; set; }
```

### Property Value

Der Anzeigename der Ebene.

## Beispiele

Das folgende Beispiel demonstriert die Möglichkeit, den DisplayName-Wert zu setzen, sodass der Ebenenname korrekt angezeigt wird.

```csharp
[C#]

// Nehmen Sie Änderungen an Ebenennamen vor und speichern Sie sie
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // neuen Wert in die DisplayName-Eigenschaft setzen
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### Siehe auch

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


