---
title: BackgroundColorResource.Color
second_title: Aspose.PSD per riferimento API .NET
description: BackgroundColorResource proprietà. Ottiene o imposta il colore di sfondo.
type: docs
weight: 20
url: /it/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/
---
## BackgroundColorResource.Color property

Ottiene o imposta il colore di sfondo.

```csharp
public Color Color { get; set; }
```

### Esempi

L'esempio seguente dimostra il supporto della risorsa BackgroundColorResource.

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

    // aggiorna BackgroundColorResource
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Guarda anche

* struct [Color](../../../aspose.psd/color/)
* class [BackgroundColorResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* assemblea [Aspose.PSD](../../../)


