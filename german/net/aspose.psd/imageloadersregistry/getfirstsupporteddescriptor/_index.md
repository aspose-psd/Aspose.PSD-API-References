---
title: ImageLoadersRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD für .NET-API-Referenz
description: ImageLoadersRegistry methode. Ruft den ersten gefundenen unterstützten Deskriptor ab der für den angegebenen geeignet iststream und optional dieloadOptions .
type: docs
weight: 40
url: /de/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Ruft den ersten gefundenen unterstützten Deskriptor ab, der für den angegebenen geeignet ist*stream* und optional die*loadOptions* .

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Strom. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Rückgabewert

Der Loader-Deskriptor, der die angegebenen unterstützt*stream* Und*loadOptions* oder null, wenn kein solcher Deskriptor gefunden wird.

### Bemerkungen

Der erste Loader-Deskriptor ist tatsächlich der letzte registrierte.

### Siehe auch

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namensraum [Aspose.PSD](../../imageloadersregistry/)
* Montage [Aspose.PSD](../../../)


