---
title: "LayerResourcesRegistry.GetFirstSupportedDescriptor"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método LayerResourcesRegistry. Obtiene el primer descriptor de apertura compatible."
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

Obtiene el primer descriptor de apertura compatible.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo. |
| psdVersion | Int32 | La versión PSD. |

### Valor devuelto

El descriptor cargador de recursos de capa o null si no hay descriptor cargador compatible para dicho flujo.

## Observaciones

El primer cargador será en realidad el último registrado.

### Ver también

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


