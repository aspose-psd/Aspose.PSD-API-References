---
title: VibAResource.PsdVersion
second_title: Aspose.PSD für .NET-API-Referenz
description: VibAResource eigendom. Ruft die PSDVersion ab.
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/psdversion/
---
## VibAResource.PsdVersion property

Ruft die PSD-Version ab.

```csharp
public override int PsdVersion { get; }
```

### Beispiele

Das folgende Codebeispiel demonstriert die Unterstützung der VibAResource-Ressource.

```csharp
[C#]

// Beispiel für die Unterstützung des Lesens und Schreibens von Vibrationsressourcen zur Laufzeit.
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
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* Montage [Aspose.PSD](../../../)


