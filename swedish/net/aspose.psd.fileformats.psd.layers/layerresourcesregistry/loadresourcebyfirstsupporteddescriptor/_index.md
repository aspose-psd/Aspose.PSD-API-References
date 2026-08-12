---
title: "LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor"
second_title: "Aspose.PSD för .NET API‑referens"
description: "LayerResourcesRegistry metod. Laddar LayerResource med hjälp av den första funna öppnaren som är lämplig för den angivna strömmen"
type: docs
weight: 40
url: /sv/net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/loadresourcebyfirstsupporteddescriptor/
---
{{< psd/tize >}}
## LayerResourcesRegistry.LoadResourceByFirstSupportedDescriptor method

Laddar [`LayerResource`](../../layerresource/) med hjälp av den första funna öppnaren som är lämplig för den angivna *strömmen*.

```csharp
public static LayerResource LoadResourceByFirstSupportedDescriptor(Stream stream, int psdVersion)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Strömmen. |
| psdVersion | Int32 | PSD-versionen. |

### Returvärde

Den laddade [`LayerResource`](../../layerresource/) eller null om ingen öppnare hittas.

## Anmärkningar

Den första öppnaren kommer faktiskt att vara den sist registrerade.

### Se även

* class [LayerResource](../../layerresource/)
* class [LayerResourcesRegistry](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


