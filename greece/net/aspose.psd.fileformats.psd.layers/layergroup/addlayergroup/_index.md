---
title: LayerGroup.AddLayerGroup
second_title: Aspose.PSD για Αναφορά API .NET
description: LayerGroup μέθοδος. Προσθέτει την ομάδα επιπέδων.
type: docs
weight: 70
url: /el/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
## LayerGroup.AddLayerGroup method

Προσθέτει την ομάδα επιπέδων.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| groupName | String | Όνομα της ομάδας. |
| index | Int32 | Ο δείκτης του στρώματος που θα εισαγάγετε μετά. |

### Επιστρεφόμενη Αξία

Άνοιγμα επιπέδου ομάδας

### Παραδείγματα

Το ακόλουθο παράδειγμα δείχνει την προσθήκη LayerGroup σε μια άλλη LayerGroup.

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// Δημιουργία ιεραρχίας επιπέδων ως εξής:
// -Ομάδα 1
// --Επίπεδο 1
// -- Ομάδα 2
// ---Επίπεδο 2
// ---Επίπεδο 3
// --Επίπεδο 4

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

### Δείτε επίσης

* class [LayerGroup](../)
* χώρος ονομάτων [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* συνέλευση [Aspose.PSD](../../../)


