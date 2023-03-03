---
title: LayerResourcesRegistry.GetFirstSupportedDescriptor
second_title: Referencia de API de Aspose.PSD para .NET
description: LayerResourcesRegistry método. Obtiene el primer descriptor de apertura compatible.
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/getfirstsupporteddescriptor/
---
## LayerResourcesRegistry.GetFirstSupportedDescriptor method

Obtiene el primer descriptor de apertura compatible.

```csharp
public static ILayerResourceLoader GetFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La corriente. |
| psdVersion | Int32 | La versión PSD. |

### Valor_devuelto

El descriptor del cargador de recursos de la capa o nulo si no se admite ningún descriptor del cargador para dicha secuencia.

### Observaciones

El primer cargador será en realidad el último registrado.

### Ver también

* interface [ILayerResourceLoader](../../ilayerresourceloader/)
* class [LayerResourcesRegistry](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers](../../layerresourcesregistry/)
* asamblea [Aspose.PSD](../../../)


