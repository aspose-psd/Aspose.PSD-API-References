---
title: "BorderInformationResource.MinimalVersion"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "BorderInformationResource-Eigenschaft. Gibt die minimal erforderliche PSD-Version zurück"
type: docs
weight: 30
url: /de/net/aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/
---
{{< psd/tize >}}
## BorderInformationResource.MinimalVersion property

Ruft die minimal erforderliche PSD-Version ab.

```csharp
public override int MinimalVersion { get; }
```

### Property Value

Die minimale PSD-Version.

## Beispiele

Das folgende Beispiel demonstriert die Unterstützung der BorderInformationResource‑Ressource.

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    ResourceBlock[] imageResources = image.ImageResources;
    BorderInformationResource borderInfoResource = null;
    foreach (var imageResource in imageResources)
    {
        if (imageResource is BorderInformationResource)
        {
            borderInfoResource = (BorderInformationResource)imageResource;
            break;
        }
    }

    // BorderInformationResource aktualisieren
    borderInfoResource.Width = 0.1;
    borderInfoResource.Unit = PhysicalUnit.Inches;

    image.Save(outputFilePath);
}
```

### Siehe auch

* class [BorderInformationResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../../)


