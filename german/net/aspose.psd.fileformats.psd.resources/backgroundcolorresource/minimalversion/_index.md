---
title: BackgroundColorResource.MinimalVersion
second_title: Aspose.PSD für .NET-API-Referenz
description: BackgroundColorResource eigendom. Ruft die minimal erforderliche PSDVersion ab.
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
## BackgroundColorResource.MinimalVersion property

Ruft die minimal erforderliche PSD-Version ab.

```csharp
public override int MinimalVersion { get; }
```

### Eigentumswert

Die minimale PSD-Version.

### Beispiele

Das folgende Beispiel veranschaulicht die Unterstützung der BackgroundColorResource-Ressource.

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

    // BackgroundColorResource aktualisieren
    backgroundColorResource.Color = Color.DarkRed;

    image.Save(outputFilePath);
}
```

### Siehe auch

* class [BackgroundColorResource](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Resources](../../backgroundcolorresource/)
* Montage [Aspose.PSD](../../../)


