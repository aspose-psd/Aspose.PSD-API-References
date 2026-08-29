---
title: "BackgroundColorResource.MinimalVersion"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "BackgroundColorResource-Eigenschaft. Gibt die minimal erforderliche PSD-Version zurück"
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/
---
{{< psd/tize >}}
## BackgroundColorResource.MinimalVersion property

Ruft die minimal erforderliche PSD-Version ab.

```csharp
public override int MinimalVersion { get; }
```

### Property Value

Die minimale PSD-Version.

## Beispiele

Das folgende Beispiel demonstriert die Unterstützung der BackgroundColorResource-Ressource.

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
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


