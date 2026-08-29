---
title: "LinkedLayersManager.GetLayersByLinkGroupId"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método LinkedLayersManager. Obtiene capas por id de grupo de enlace"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/getlayersbylinkgroupid/
---
{{< psd/tize >}}
## LinkedLayersManager.GetLayersByLinkGroupId method

Obtiene capas por ID de grupo de enlace.

```csharp
public Layer[] GetLayersByLinkGroupId(short linkGroupId)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| linkGroupId | Int16 | El id del grupo de enlace. |

### Valor devuelto

La matriz de capas.

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


