---
title: "OSTypeStructuresRegistry.GetFirstSupportedDescriptor"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "OSTypeStructuresRegistry método. Obtiene el primer descriptor de abridor compatible"
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## OSTypeStructuresRegistry.GetFirstSupportedDescriptor method

Obtiene el primer descriptor de apertura compatible.

```csharp
public static IOSTypeStructureLoader GetFirstSupportedDescriptor(Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo. |

### Valor devuelto

El descriptor cargador de recursos de capa o null si no hay descriptor cargador compatible para dicho flujo.

## Observaciones

El primer cargador será en realidad el último registrado.

### Ver también

* interface [IOSTypeStructureLoader](../../iostypestructureloader/)
* class [OSTypeStructuresRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


