---
title: "PsdImage.AddLayerGroup"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método PsdImage. Añade el grupo de capas"
type: docs
weight: 400
url: /es/net/aspose.psd.fileformats.psd/psdimage/addlayergroup/
---
{{< psd/tize >}}
## PsdImage.AddLayerGroup method

Agrega el grupo de capas.

```csharp
public LayerGroup AddLayerGroup(string groupName, int index, bool startBehaviour)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| groupName | String | Nombre del grupo. |
| index | Int32 | El índice de la capa después de la cual insertar. |
| startBehaviour | Boolean | si se establece en `true` [start behaviour] entonces el grupo estará en estado abierto al iniciar, de lo contrario en estado minimizado. |

### Valor devuelto

Abriendo capa de grupo

### Excepciones

| excepción | condición |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | El índice debe estar dentro de los límites del recuento de capas |

### Ver también

* class [LayerGroup](../../../aspose.psd.fileformats.psd.layers/layergroup/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


