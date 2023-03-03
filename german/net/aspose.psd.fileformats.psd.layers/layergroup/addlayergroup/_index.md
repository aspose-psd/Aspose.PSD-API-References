---
title: LayerGroup.AddLayerGroup
second_title: Aspose.PSD für .NET-API-Referenz
description: LayerGroup methode. Fügt die Ebenengruppe hinzu.
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
## LayerGroup.AddLayerGroup method

Fügt die Ebenengruppe hinzu.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| groupName | String | Name der Gruppe. |
| index | Int32 | Der Index der Ebene, nach der eingefügt werden soll. |

### Rückgabewert

Gruppenebene öffnen

### Beispiele

Das folgende Beispiel zeigt das Hinzufügen von LayerGroup zu einer anderen LayerGroup.

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// Ebenenhierarchie wie folgt erstellen:
// -Gruppe 1
// --Ebene 1
// --Gruppe 2
// ---Schicht 2
// ---Schicht 3
// --Schicht 4

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

### Siehe auch

* class [LayerGroup](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* Montage [Aspose.PSD](../../../)


