---
title: ImageLoadersRegistry.CreateFirstSupportedLoader
second_title: Aspose.PSD für .NET-API-Referenz
description: ImageLoadersRegistry methode. Erstellt den ersten gefundenen Lader der für die angegebenen geeignet iststream und optional dieloadOptions .
type: docs
weight: 30
url: /de/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Erstellt den ersten gefundenen Lader, der für die angegebenen geeignet ist*stream* und optional die*loadOptions* .

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Strom. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Rückgabewert

Der Lader, der die angegebenen unterstützt*stream* Und*loadOptions* oder null, wenn kein solcher Loader gefunden wird.

### Bemerkungen

Der erste Lader wird tatsächlich der letzte registrierte sein.

### Siehe auch

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namensraum [Aspose.PSD](../../imageloadersregistry/)
* Montage [Aspose.PSD](../../../)


