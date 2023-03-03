---
title: Class OSTypeStructuresRegistry
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructuresRegistry clase. Representa elOSTypeStructure registro de recursos.
type: docs
weight: 2860
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---
## OSTypeStructuresRegistry class

Representa el[`OSTypeStructure`](../ostypestructure/) registro de recursos.

```csharp
public static class OSTypeStructuresRegistry
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registereddescriptors/) { get; } | Obtiene los descriptores registrados. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [GetFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptor/)(Stream) | Obtiene el primer descriptor de apertura compatible. |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptorbytypename/)(string) | Obtiene el primer descriptor admitido por su nombre de tipo. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/loadresourcebyfirstsupporteddescriptor/)(Stream) | Cargas[`OSTypeStructure`](../ostypestructure/) usando el primer abridor encontrado adecuado para el especificado*stream* . |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registeropener/)(IOSTypeStructureLoader) | Registra el abridor. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/unregisteropener/)(IOSTypeStructureLoader) | Da de baja al abridor. |

### Ver también

* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* asamblea [Aspose.PSD](../../)


