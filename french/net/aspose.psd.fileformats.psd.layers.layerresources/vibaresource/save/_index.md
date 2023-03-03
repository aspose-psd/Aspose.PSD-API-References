---
title: VibAResource.Save
second_title: Référence de l'API Aspose.PSD pour .NET
description: VibAResource méthode. Enregistre la ressource dans le conteneur de flux spécifié.
type: docs
weight: 70
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
## VibAResource.Save method

Enregistre la ressource dans le conteneur de flux spécifié.

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| streamContainer | StreamContainer | Le conteneur de flux dans lequel enregistrer. |
| psdVersion | Int32 | La version PSD. |

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

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../vibaresource/)
* Assemblée [Aspose.PSD](../../../)


