---
title: "ImageLoadersRegistry.CreateFirstSupportedLoader"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ImageLoadersRegistry-metoden. Skapar den första hittade laddaren som är lämplig för den angivna strömmen och eventuellt loadOptions."
type: docs
weight: 30
url: /sv/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
{{< psd/tize >}}
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Skapar den första hittade laddaren som är lämplig för den angivna *stream* och eventuellt *loadOptions*.

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Strömmen. |
| loadOptions | LoadOptions | Laddningsalternativen. |

### Returvärde

Laddaren som stöder den angivna *stream* och *loadOptions* eller null om ingen sådan laddare hittas.

## Anmärkningar

Den första laddaren kommer faktiskt att vara den sist registrerade.

### Se även

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


