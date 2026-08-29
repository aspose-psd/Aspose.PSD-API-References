---
title: "Klasse PostResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PostResource Klasse. Klasse PostResource. Einstellungen für die Posterize‑Ebene."
type: docs
weight: 3300
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/postresource/
---
{{< psd/tize >}}
## PostResource class

Klasse PostResource. Posterisierebenen-Einstellungen.

```csharp
public class PostResource : AdjustmentLayerResource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PostResource](postresource/)() | Der Standardkonstruktor. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/length/) { get; } | Liest die Länge der Schichtressource in Bytes. |
| [Levels](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/levels/) { get; set; } | Stufen der Posterize Ebene. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/save/)(StreamContainer, int) | Speichert die Ressource in den angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/postresource/typetoolkey/) | Der Typwerkzeug-Info-Schlüssel. |

## Beispiele

Der folgende Code demonstriert die Fähigkeit zur Manipulation von PostResource.

```csharp
[C#]

string sourceFile = "zendeya_posterize.psd";
string outputFile = "zendeya_posterize_10.psd";

using (var image = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    Layer layer = image.Layers[1];

    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is PostResource)
        {
            ((PostResource)resource).Levels = 10;
            image.Save(outputFile);

            break;
        }
    }
}
```

### Siehe auch

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


