---
title: LayerGroup.AddLayerGroup
second_title: Aspose.PSD per riferimento API .NET
description: LayerGroup metodo. Aggiunge il gruppo di livelli.
type: docs
weight: 70
url: /it/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
## LayerGroup.AddLayerGroup method

Aggiunge il gruppo di livelli.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| groupName | String | Nome del gruppo. |
| index | Int32 | L'indice del livello da inserire dopo. |

### Valore di ritorno

Apertura del livello di gruppo

### Esempi

L'esempio seguente mostra l'aggiunta di LayerGroup in un altro LayerGroup.

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// creare una gerarchia dei livelli come questa:
// -Gruppo 1
// --Livello 1
// --Gruppo 2
// ---Livello 2
// ---Livello 3
// --Livello 4

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

### Guarda anche

* class [LayerGroup](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../layergroup/)
* assemblea [Aspose.PSD](../../../)


