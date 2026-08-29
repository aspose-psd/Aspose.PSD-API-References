---
title: "ImageLoadersRegistry.CreateFirstSupportedLoader"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ImageLoadersRegistry Methode. Erstellt den ersten gefundenen Loader, der für den angegebenen *stream* geeignet ist und optional die *loadOptions*."
type: docs
weight: 30
url: /de/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
{{< psd/tize >}}
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Erstellt den zuerst gefundenen Loader, der für den angegebenen *stream* geeignet ist und optional die *loadOptions*.

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Stream | Der Stream. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Rückgabewert

Der Loader, der den angegebenen *stream* und die *loadOptions* unterstützt, oder null, wenn kein solcher Loader gefunden wird.

## Hinweise

Der erste Loader ist tatsächlich der zuletzt registrierte.

### Siehe auch

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


