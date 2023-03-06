---
title: LayerGroup.AddLayerGroup
second_title: Aspose.PSD voor .NET API-referentie
description: LayerGroup methode. Voegt de laaggroep toe.
type: docs
weight: 70
url: /nl/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
## LayerGroup.AddLayerGroup method

Voegt de laaggroep toe.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| groupName | String | Naam van de groep. |
| index | Int32 | De index van de laag die daarna moet worden ingevoegd. |

### Winstwaarde

Groepslaag openen

### Voorbeelden

Het volgende voorbeeld demonstreert het toevoegen van LayerGroup aan een andere LayerGroup.

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// lagenhiërarchie als volgt maken:
// -Groep 1
// --Laag 1
// --Groep 2
// --- Laag 2
// --- Laag 3
// --Laag 4

var createOptions = new PsdOptions();
createOptions.Source = new FileCreateSource(sourceFileName, false);
createOptions.Palette = new PsdColorPalette(new Color[] { Color.Green });

using (var psdImage = (PsdImage)Image.Create(createOptions, 500, 500))
{
    LayerGroup group1 = psdImage.AddLayerGroup("Group 1", 0, false);

    Layer layer1 = new Layer(psdImage);
    layer1.Name = "Layer 1";
    group1.AddLayer(layer1);

    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);

    Layer layer2 = new Layer(psdImage);
    layer2.Name = "Layer 2";
    group2.AddLayer(layer2);

    Layer layer3 = new Layer(psdImage);
    layer3.Name = "Layer 3";
    group2.AddLayer(layer3);

    Layer layer4 = new Layer(psdImage);
    layer4.Name = "Layer 4";
    group1.AddLayer(layer4);

    psdImage.Save();
}
```

### Zie ook

* class [LayerGroup](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* montage [Aspose.PSD](../../../)


