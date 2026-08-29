---
title: "Klasse NvrtResource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.NvrtResource Klasse. Klasse NvrtResource. Ressource der Invert-Anpassungsebene"
type: docs
weight: 3180
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/
---
{{< psd/tize >}}
## NvrtResource class

Klasse NvrtResource. Ressource der Invert-Anpassungsebene.

```csharp
public class NvrtResource : AdjustmentLayerResource
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [NvrtResource](nvrtresource/#constructor)() | Initialisiert eine neue Instanz der `NvrtResource`-Klasse. |
| [NvrtResource](nvrtresource/#constructor_1)(byte[]) | Initialisiert eine neue Instanz der `NvrtResource`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Liest den Schichtressourcen-Schlüssel. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/length/) { get; } | Liest die Länge der Schichtressource in Bytes. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Liest die minimale PSD-Version, die für die Schichtressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Liest die Signatur. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/save/)(StreamContainer, int) | Speichert die Ressource in den angegebenen Stream-Container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Gibt einen String zurück, der diese Instanz darstellt. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/typetoolkey/) | Der Typwerkzeug-Info-Schlüssel. |

## Beispiele

Das folgende Beispiel demonstriert, wie man NvrtResource erhält.

```csharp
[C#]

string sourceFilePath = "InvertAdjustmentLayer.psd";
NvrtResource resource = null;
using (PsdImage psdImage = (PsdImage)Image.Load(sourceFilePath))
{
    foreach (Aspose.PSD.FileFormats.Psd.Layers.Layer layer in psdImage.Layers)
    {
        if (layer is InvertAdjustmentLayer)
        {
            foreach (Aspose.PSD.FileFormats.Psd.Layers.LayerResource layerResource in layer.Resources)
            {
                if (layerResource is NvrtResource)
                {
                    // NvrtResource wird unterstützt.
                    resource = (NvrtResource)layerResource;
                    break;
                }
            }
        }
    }
}
```

### Siehe auch

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


