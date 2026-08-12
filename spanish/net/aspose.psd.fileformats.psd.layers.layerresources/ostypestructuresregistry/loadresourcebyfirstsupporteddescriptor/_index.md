---
title: "OSTypeStructuresRegistry.LoadResourceByFirstSupportedDescriptor"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "OSTypeStructuresRegistry método. Carga OSTypeStructure usando el primer abridor encontrado adecuado para el flujo especificado"
type: docs
weight: 40
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/loadresourcebyfirstsupporteddescriptor/
---
{{< psd/tize >}}
## OSTypeStructuresRegistry.LoadResourceByFirstSupportedDescriptor method

Carga [`OSTypeStructure`](../../ostypestructure/) usando el primer abridor encontrado adecuado para el *stream* especificado.

```csharp
public static OSTypeStructure LoadResourceByFirstSupportedDescriptor(Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo. |

### Valor devuelto

El [`LayerResource`](../../../aspose.psd.fileformats.psd.layers/layerresource/) cargado o null si no se encuentra ningún abridor.

## Observaciones

El primer descriptor de apertura será en realidad el último registrado.

### Ver también

* class [OSTypeStructure](../../ostypestructure/)
* class [OSTypeStructuresRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


