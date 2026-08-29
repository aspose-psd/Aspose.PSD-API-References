---
title: "LayerGroup.AddLayerGroup"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método LayerGroup. Añade el grupo de capas"
type: docs
weight: 70
url: /es/net/aspose.psd.fileformats.psd.layers/layergroup/addlayergroup/
---
{{< psd/tize >}}
## LayerGroup.AddLayerGroup method

Agrega el grupo de capas.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| groupName | String | Nombre del grupo. |
| index | Int32 | El índice de la capa después de la cual insertar. |

### Valor devuelto

Abriendo capa de grupo

## Ejemplos

El siguiente ejemplo muestra cómo agregar LayerGroup dentro de otro LayerGroup.

```csharp
[C#]

string sourceFileName = "psdnet190_test.psd";

// creando una jerarquía de capas como esta:
// -Grupo 1
// --Capa 1
// --Grupo 2
// ---Capa 2
// ---Capa 3
// --Capa 4

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

### Ver también

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


