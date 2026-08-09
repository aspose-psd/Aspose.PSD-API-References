---
title: "VibAResource.Vibrance"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "VibAResource-Eigenschaft. Gibt den Vibranzwert zurück oder setzt ihn"
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibrance/
---
{{< psd/tize >}}
## VibAResource.Vibrance property

Liest oder schreibt den Vibranzwert

```csharp
public int Vibrance { get; set; }
```

## Beispiele

Das folgende Codebeispiel demonstriert die Unterstützung der VibAResource-Ressource.

```csharp
[C#]

// Beispiel für die Unterstützung des Lesens und Schreibens der Vibrationsressource zur Laufzeit.
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### Siehe auch

* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


