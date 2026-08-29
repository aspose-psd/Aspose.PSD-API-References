---
title: "LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método LayerResourcesRegistry. Carga LayerResource usando el primer descriptor de apertura encontrado adecuado para el flujo especificado."
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor method

Carga [`LayerResource`](../../layerresource/) usando el primer descriptor de apertura encontrado adecuado para el *flujo* especificado.

```csharp
public static LayerResource LoadResourceByFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo. |
| psdVersion | Int32 | La versión PSD. |

### Valor devuelto

El [`LayerResource`](../../layerresource/) cargado o null si no se encuentra ningún descriptor de apertura.

## Observaciones

El primer descriptor de apertura será en realidad el último registrado.

### Ver también

* class [LayerResource](../../layerresource/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


