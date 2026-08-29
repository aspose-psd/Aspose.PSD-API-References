---
title: "BackgroundColorResource.DataSize"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "BackgroundColorResource-Eigenschaft. Gibt die Ressourcendatengröße in Bytes zurück"
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/
---
{{< psd/tize >}}
## BackgroundColorResource.DataSize property

Ruft die Größe der Ressourcendaten in Bytes ab.

```csharp
public override int DataSize { get; }
```

### Property Value

Die Größe der Ressourcendaten.

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


