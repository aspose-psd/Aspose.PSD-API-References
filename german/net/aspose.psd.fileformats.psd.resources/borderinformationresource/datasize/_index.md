---
title: "BorderInformationResource.DataSize"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "BorderInformationResource-Eigenschaft. Gibt die Größe der Ressourcendaten in Bytes zurück"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/
---
{{< psd/tize >}}
## BorderInformationResource.DataSize property

Ruft die Größe der Ressourcendaten in Bytes ab.

```csharp
public override int DataSize { get; }
```

### Property Value

Die Größe der Ressourcendaten.

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


