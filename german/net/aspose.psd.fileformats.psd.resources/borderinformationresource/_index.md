---
title: Class BorderInformationResource
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Resources.BorderInformationResource klas. Die Ressource mit Randinformationen der Bilddruckeinstellungen.
type: docs
weight: 3650
url: /de/net/aspose.psd.fileformats.psd.resources/borderinformationresource/
---
## BorderInformationResource class

Die Ressource mit Randinformationen der Bilddruckeinstellungen.

```csharp
public sealed class BorderInformationResource : ResourceBlock
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [BorderInformationResource](borderinformationresource/)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/borderinformationresource/datasize/) { get; } | Ruft die Ressourcendatengröße in Byte ab. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Ruft die eindeutige Kennung für die Ressource ab oder legt sie fest. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/borderinformationresource/minimalversion/) { get; } | Ruft die minimal erforderliche PSD-Version ab. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Ruft den Ressourcennamen ab oder legt ihn fest. Pascal-String, aufgefüllt, um die Größe gleichmäßig zu machen (ein Nullname besteht aus zwei Bytes von 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Ruft die Ressourcensignatur ab. Sollte immer '8BIM' sein. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Ruft die Ressourcenblockgröße in Byte ab, einschließlich seiner Daten. |
| [Unit](../../aspose.psd.fileformats.psd.resources/borderinformationresource/unit/) { get; set; } | Ruft die Grenzeinheiten ab oder legt sie fest. |
| [Width](../../aspose.psd.fileformats.psd.resources/borderinformationresource/width/) { get; set; } | Ruft die Rahmenbreite ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Speichert den Ressourcenblock im angegebenen Stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validiert die Ressourcenwerte. |

### Beispiele

Das folgende Beispiel veranschaulicht die Unterstützung der BorderInformationResource-Ressource.

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namensraum [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* Montage [Aspose.PSD](../../)


