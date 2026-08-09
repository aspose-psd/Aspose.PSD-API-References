---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ImageLoadersRegistry-Methode. Gibt den zuerst gefundenen unterstützten Deskriptor zurück, der für den angegebenen *stream* und optional die *loadOptions* geeignet ist."
type: docs
weight: 40
url: /de/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Ruft den zuerst gefundenen unterstützten Deskriptor ab, der für den angegebenen *stream* geeignet ist und optional die *loadOptions*.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Stream | Der Stream. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Rückgabewert

Der Loader-Deskriptor, der den angegebenen *stream* und die *loadOptions* unterstützt, oder null, wenn kein solcher Deskriptor gefunden wird.

## Hinweise

Der erste Loader-Deskriptor ist tatsächlich der zuletzt registrierte.

### Siehe auch

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


