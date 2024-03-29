---
title: BackgroundColorResource.MinimalVersion
second_title: Référence de l'API Aspose.PSD pour .NET
description: BackgroundColorResource propriété. Obtient la version PSD minimale requise.
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
## BackgroundColorResource.MinimalVersion property

Obtient la version PSD minimale requise.

```csharp
public override int MinimalVersion { get; }
```

### Valeur de la propriété

La version PSD minimale.

### Exemples

L'exemple suivant illustre la prise en charge de la ressource BackgroundColorResource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BackgroundColorResource backgroundColorResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BackgroundColorResource)
        {
            backgroundColorResource = (BackgroundColorResource)imageResource;
            break;
        }
    }

    // met à jour BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Voir également

* class [BackgroundColorResource](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* Assemblée [Aspose.PSD](../../../)


