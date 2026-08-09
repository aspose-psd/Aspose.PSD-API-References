---
title: "VibAResource.VibAResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur VibAResource. Initialise une nouvelle instance de la classe VibAResource"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibaresource/
---
{{< psd/tize >}}
## VibAResource constructor

Initialise une nouvelle instance de la classe [`VibAResource`](../).

```csharp
public VibAResource()
```

## Exemples

L'exemple de code suivant montre la prise en charge de la ressource VibAResource.

```csharp
[C#]

// Exemple de prise en charge de la lecture et de l'écriture de la ressource Vibration à l'exécution.
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

### Voir aussi

* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


