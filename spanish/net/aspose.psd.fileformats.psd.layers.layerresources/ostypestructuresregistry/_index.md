---
title: "Clase OSTypeStructuresRegistry"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructuresRegistry. Representa el registro de recursos OSTypeStructure"
type: docs
weight: 3200
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/
---
{{< psd/tize >}}
## OSTypeStructuresRegistry class

Representa el registro de recursos [`OSTypeStructure`](../ostypestructure/).

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
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/getfirstsupporteddescriptorbytypename/)(string) | Obtiene el primer descriptor compatible por su nombre de tipo. |
| static [LoadResourceByFirstSupportedDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/loadresourcebyfirstsupporteddescriptor/)(Stream) | Carga [`OSTypeStructure`](../ostypestructure/) usando el primer abridor encontrado adecuado para el *stream* especificado. |
| static [RegisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/registeropener/)(IOSTypeStructureLoader) | Registra el abridor. |
| static [UnregisterOpener](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/unregisteropener/)(IOSTypeStructureLoader) | Desregistra el abridor. |

### Ver también

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


