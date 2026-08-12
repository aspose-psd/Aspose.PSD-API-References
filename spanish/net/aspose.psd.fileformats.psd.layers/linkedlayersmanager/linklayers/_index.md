---
title: "LinkedLayersManager.LinkLayers"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método LinkedLayersManager. Enlaza las capas de entrada y devuelve LingGroupId"
type: docs
weight: 30
url: /es/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/linklayers/
---
{{< psd/tize >}}
## LinkedLayersManager.LinkLayers method

Vincula las capas de entrada y devuelve LingGroupId.

```csharp
public short LinkLayers(Layer[] layers)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| layers | Layer[] | Las capas. |

### Valor devuelto

El id del grupo de enlace.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Las capas son nulas. |
| ArgumentException | El número de capas debe ser mayor que 1. |
| ArgumentException | El contenedor de cada capa debe ser el mismo que el PsdImage actual. |

## Ejemplos

El siguiente ejemplo demuestra cómo puedes manipular capas vinculadas en Aspose.PSD

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "psdnet11_output.psd";

// Cargar una imagen existente en una instancia de la clase PsdImage
using (var psd = (PsdImage)Image.Load(sourceFile))
{
    Layer[] layers = psd.Layers;

    // vincula todas las capas en un grupo vinculado
    short layersLinkGroupId = psd.LinkedLayersManager.LinkLayers(layers);

    // obtiene el id de una capa
    short linkGroupId = psd.LinkedLayersManager.GetLinkGroupId(layers[0]);
    if (layersLinkGroupId != linkGroupId)
    {
        throw new Exception("layersLinkGroupId and linkGroupId are not equal.");
    }

    // obtiene todas las capas vinculadas por ID de grupo de enlace.
    Layer[] linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);

    // desvincula cada capa del grupo
    foreach (var linkedLayer in linkedLayers)
    {
        psd.LinkedLayersManager.UnlinkLayer(linkedLayer);
    }

    // devuelve NULL para un ID de grupo de enlace que no tiene capas en el grupo.
    linkedLayers = psd.LinkedLayersManager.GetLayersByLinkGroupId(linkGroupId);
    if (linkedLayers != null)
    {
        throw new Exception("The linkedLayers field is not NULL.");
    }
    psd.Save(outputFile);
}
```

### Ver también

* class [Layer](../../layer/)
* class [LinkedLayersManager](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


