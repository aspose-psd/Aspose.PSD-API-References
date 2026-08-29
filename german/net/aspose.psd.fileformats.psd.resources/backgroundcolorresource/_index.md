---
title: "Klasse BackgroundColorResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Resources.BackgroundColorResource Klasse. Die Ressource mit Randinformationen der Bildeinstellungen für den Druck"
type: docs
weight: 4100
url: /de/net/aspose.psd.fileformats.psd.resources/backgroundcolorresource/
---
{{< psd/tize >}}
## BackgroundColorResource class

Die Ressource mit Randinformationen der Bilddruckeinstellungen.

```csharp
public sealed class BackgroundColorResource : ResourceBlock
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [BackgroundColorResource](backgroundcolorresource/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Color](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/color/) { get; set; } | Liest oder setzt die Hintergrundfarbe. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/datasize/) { get; } | Ruft die Größe der Ressourcendaten in Bytes ab. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Ruft die eindeutige Kennung der Ressource ab oder legt sie fest. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/backgroundcolorresource/minimalversion/) { get; } | Ruft die minimal erforderliche PSD-Version ab. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Ruft den Ressourcennamen ab oder legt ihn fest. Pascal-Zeichenkette, aufgefüllt, um die Größe gerade zu machen (ein Null-Name besteht aus zwei Bytes von 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Ruft die Ressourcensignatur ab. Sollte immer '8BIM' sein. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Ruft die Größe des Ressourcenblocks in Bytes einschließlich seiner Daten ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Speichert den Ressourcenblock in den angegebenen Stream. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Validiert die Ressourcenwerte. |

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

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


