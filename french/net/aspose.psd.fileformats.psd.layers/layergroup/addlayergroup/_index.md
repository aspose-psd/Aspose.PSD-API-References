---
title: "LayerGroup.AddLayerGroup"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode LayerGroup. Ajoute le groupe de calques"
type: docs
weight: 70
url: /fr/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
{{< psd/tize >}}
## LayerGroup.AddLayerGroup method

Ajoute le groupe de calques.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| groupName | String | Nom du groupe. |
| index | Int32 | L'index du calque après lequel insérer. |

### Valeur de retour

Ouverture du groupe de calques

## Exemples

L'exemple suivant montre l'ajout d'un LayerGroup dans un autre LayerGroup.

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// création d'une hiérarchie de calques comme suit:
// -Groupe 1
// --Calque 1
// --Groupe 2
// ---Calque 2
// ---Calque 3
// --Calque 4

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

### Voir aussi

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


