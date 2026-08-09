---
title: "VibAResource.Length"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "VibAResource-Eigenschaft. Gibt die Länge der Ebenenressource in Bytes zurück"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/length/
---
{{< psd/tize >}}
## VibAResource.Length property

Liest die Länge der Schichtressource in Bytes.

```csharp
public override int Length { get; }
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


