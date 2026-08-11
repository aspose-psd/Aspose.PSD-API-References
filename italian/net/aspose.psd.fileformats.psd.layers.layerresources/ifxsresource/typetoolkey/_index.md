---
title: "IfxsResource.TypeToolKey"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "IfxsResource campo. La chiave delle informazioni dello strumento di tipo"
type: docs
weight: 20
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

La chiave delle informazioni dello strumento di tipo.

```csharp
public const int TypeToolKey;
```

## Esempi

Il codice seguente dimostra il supporto di IfxsResource.

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
    // L'esempio ha 2 gruppi di livelli con effetti
    // Gruppo di livello con un effetto
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // Gruppo di livello con molti effetti
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // Ottieni il numero di effetti e verifica la loro quantità
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // Un effetto nel gruppo di livello è nella risorsa 'IfxsResource'
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // Due o più effetti in un gruppo di livello sono nella risorsa 'ImfxResource'
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // Aggiungi una terza ombra a un gruppo di livello con effetti multipli
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### Vedi anche

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


