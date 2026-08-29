---
title: "SectionDividerLayer.GetRelatedLayerGroup"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método SectionDividerLayer. Obtiene el LayerGroup que está relacionado con esta instancia de SectionDividerLayer"
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/getrelatedlayergroup/
---
{{< psd/tize >}}
## SectionDividerLayer.GetRelatedLayerGroup method

Obtiene el [`LayerGroup`](../../layergroup/) que está relacionado con esta instancia de [`SectionDividerLayer`](../).

```csharp
public LayerGroup GetRelatedLayerGroup()
```

### Valor devuelto

La instancia de [`LayerGroup`](../../layergroup/).

## Ejemplos

El siguiente código demuestra capas SectionDividerLayer y cómo obtener el LayerGroup relacionado con ellas.

```csharp
[C#]

// El siguiente código demuestra capas SectionDividerLayer y cómo obtener el LayerGroup relacionado con ellas.

// Jerarquía de capas
//    [0]: '</Layer group>' SectionDividerLayer para el Grupo 1
//    [1]: 'Layer 1' Capa regular
//    [2]: '</Layer group>' SectionDividerLayer para el Grupo 2
//    [3]: '</Layer group>' SectionDividerLayer para el Grupo 3
//    [4]: 'Group 3' GroupLayer
//    [5]: 'Group 2' GroupLayer
//    [6]: 'Group 1' GroupLayer

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

using (var image = new PsdImage(100, 100))
{
    // Creando la jerarquía de capas
    // Agregar el LayerGroup 'Group 1'
    LayerGroup group1 = image.AddLayerGroup("Group 1", 0, true);
    // Agregar capa regular
    Layer layer1 = new Layer();
    layer1.DisplayName = "Layer 1";
    group1.AddLayer(layer1);
    // Agregar el LayerGroup 'Group 2'
    LayerGroup group2 = group1.AddLayerGroup("Group 2", 1);
    // Agregar el LayerGroup 'Group 3'
    LayerGroup group3 = group2.AddLayerGroup("Group 3", 0);

    // Obtiene el SectionDividerLayer
    SectionDividerLayer divider1 = (SectionDividerLayer)image.Layers[0];
    SectionDividerLayer divider2 = (SectionDividerLayer)image.Layers[2];
    SectionDividerLayer divider3 = (SectionDividerLayer)image.Layers[3];

    // usando el método SectionDividerLayer.GetRelatedLayerGroup(), obtiene la instancia de LayerGroup relacionada.
    AssertAreEqual(group1.DisplayName, divider1.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group2.DisplayName, divider2.GetRelatedLayerGroup().DisplayName); // the same LayerGroup
    AssertAreEqual(group3.DisplayName, divider3.GetRelatedLayerGroup().DisplayName); // the same LayerGroup

    LayerGroup folder1 = divider1.GetRelatedLayerGroup();
    AssertAreEqual(5, folder1.Layers.Length); // 'Group 1' contains 5 layers
}
```

### Ver también

* class [LayerGroup](../../layergroup/)
* class [SectionDividerLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


