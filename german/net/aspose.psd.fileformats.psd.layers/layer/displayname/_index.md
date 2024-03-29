---
title: Layer.DisplayName
second_title: Aspose.PSD für .NET-API-Referenz
description: Layer eigendom. Ruft den Anzeigenamen der Ebene ab oder legt ihn fest.
type: docs
weight: 100
url: /de/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
## Layer.DisplayName property

Ruft den Anzeigenamen der Ebene ab oder legt ihn fest.

```csharp
public string DisplayName { get; set; }
```

### Eigentumswert

Der Anzeigename der Ebene.

### Beispiele

Das folgende Beispiel zeigt die Möglichkeit, den DisplayName-Wert festzulegen, in dem der Layer-Name korrekt angezeigt wird.

```csharp
[C#]

// Änderungen an den Ebenennamen vornehmen und speichern
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // Neuen Wert in DisplayName-Eigenschaft setzen
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### Siehe auch

* class [Layer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* Montage [Aspose.PSD](../../../)


