---
title: "IfxsResource.TypeToolKey"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "IfxsResource Feld. Der Typwerkzeug-Info-Schlüssel"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

Der Typwerkzeug-Info-Schlüssel.

```csharp
public const int TypeToolKey;
```

## Beispiele

Der folgende Code demonstriert die Unterstützung von IfxsResource.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // Beispiel enthält 2 Gruppenebenen mit Effekten
    // Gruppenebene mit einem Effekt
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // Gruppenebene mit vielen Effekten
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // Ermitteln Sie die Anzahl der Effekte und überprüfen Sie deren Menge
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // Ein Effekt in der Gruppenebene befindet sich in der Ressource 'IfxsResource'
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // Zwei oder mehr Effekte in einer Gruppenebene befinden sich in der Ressource 'ImfxResource'
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // Fügen Sie einer Gruppenebene mit mehreren Effekten einen dritten Schatten hinzu
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### Siehe auch

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


