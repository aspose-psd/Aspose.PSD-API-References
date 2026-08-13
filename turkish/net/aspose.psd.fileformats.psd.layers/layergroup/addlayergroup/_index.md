---
title: "LayerGroup.AddLayerGroup"
second_title: "Aspose.PSD for .NET API Referansı"
description: "LayerGroup yöntemi. Katman grubunu ekler."
type: docs
weight: 70
url: /tr/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
{{< psd/tize >}}
## LayerGroup.AddLayerGroup method

Katman grubunu ekler.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| groupName | String | Grubun adı. |
| index | Int32 | Sonra eklenecek katmanın indeksi. |

### Dönüş Değeri

Grup katmanını açma

## Örnekler

Aşağıdaki örnek, LayerGroup'u başka bir LayerGroup içine eklemeyi gösterir.

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// katman hiyerarşisini şu şekilde oluşturma:
// -Grup 1
// --Katman 1
// --Grup 2
// ---Katman 2
// ---Katman 3
// --Katman 4

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

### Ayrıca Bakınız

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


