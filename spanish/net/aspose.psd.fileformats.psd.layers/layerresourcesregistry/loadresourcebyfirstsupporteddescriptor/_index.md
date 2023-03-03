---
title: LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor
second_title: Referencia de API de Aspose.PSD para .NET
description: LayerResourcesRegistry método. CargasLayerResource usando el primer abridor encontrado adecuado para el especificadostream .
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/
---
## LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor method

Cargas[`LayerResource`](../../layerresource/) usando el primer abridor encontrado adecuado para el especificado*stream* .

```csharp
public static LayerResource LoadResourceByFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La corriente. |
| psdVersion | Int32 | La versión PSD. |

### Valor_devuelto

El cargado[`LayerResource`](../../layerresource/) o nulo si no se encuentra ningún abridor.

### Observaciones

El primer abridor será en realidad el último registrado.

### Ver también

* class [LayerResource](../../layerresource/)
* class [LayerResourcesRegistry](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers](../../layerresourcesregistry/)
* asamblea [Aspose.PSD](../../../)


