---
title: "LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "LayerResourcesRegistry-Methode. Lädt LayerResource mit dem zuerst gefundenen geeigneten Öffner für den angegebenen Stream"
type: docs
weight: 40
url: /de/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor method

Lädt [`LayerResource`](../../layerresource/) mit dem zuerst gefundenen geeigneten Öffner für den angegebenen *Stream*.

```csharp
public static LayerResource LoadResourceByFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Stream | Der Stream. |
| psdVersion | Int32 | Die PSD-Version. |

### Rückgabewert

Das geladene [`LayerResource`](../../layerresource/) oder null, wenn kein Öffner gefunden wird.

## Hinweise

Der erste Opener wird tatsächlich der zuletzt registrierte sein.

### Siehe auch

* class [LayerResource](../../layerresource/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


