---
title: VibAResource.TypeToolKey
second_title: Référence de l'API Aspose.PSD pour .NET
description: VibAResource champ. La clé dinformations sur loutil de type.
type: docs
weight: 80
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/typetoolkey/
---
## VibAResource.TypeToolKey field

La clé d'informations sur l'outil de type.

```csharp
public const int TypeToolKey;
```

### Exemples

L'exemple de code suivant illustre la prise en charge de la ressource VibAResource.

```csharp
[C#]

// Exemple de prise en charge de la lecture et de l'écriture de Vibration Resource lors de l'exécution.
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

### Voir également

* class [VibAResource](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* Assemblée [Aspose.PSD](../../../)


