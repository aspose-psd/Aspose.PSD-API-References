---
title: ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat
second_title: Aspose.PSD für .NET-API-Referenz
description: ImageLoadersRegistry methode. Ruft das erste unterstützte Dateiformat anhand seines Typnamens ab.
type: docs
weight: 50
url: /de/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat method

Ruft das erste unterstützte Dateiformat anhand seines Typnamens ab.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptorByFileFormat(FileFormat fileFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileFormat | FileFormat | Das unterstützte Deskriptordateiformat. |

### Rückgabewert

Der erste gefundene Lader-Deskriptor oder null, wenn kein solcher Deskriptor gefunden wird.

### Bemerkungen

Der erste Lader-Deskriptor wird tatsächlich der letzte registrierte sein.

### Siehe auch

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* enum [FileFormat](../../fileformat/)
* class [ImageLoadersRegistry](../)
* namensraum [Aspose.PSD](../../imageloadersregistry/)
* Montage [Aspose.PSD](../../../)


