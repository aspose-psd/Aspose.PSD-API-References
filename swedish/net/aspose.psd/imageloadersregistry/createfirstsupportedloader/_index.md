---
title: ImageLoadersRegistry.CreateFirstSupportedLoader
second_title: Aspose.PSD för .NET API-referens
description: ImageLoadersRegistry metod. Skapar den första hittade laddaren som är lämplig för den specificeradestream och valfrittloadOptions .
type: docs
weight: 30
url: /sv/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Skapar den första hittade laddaren som är lämplig för den specificerade*stream* och valfritt*loadOptions* .

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen. |
| loadOptions | LoadOptions | Lastalternativen. |

### Returvärde

Laddaren som stöder det angivna*stream* och*loadOptions* eller null om ingen sådan laddare hittas.

### Anmärkningar

Den första laddaren kommer faktiskt att vara den senast registrerade.

### Se även

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namnutrymme [Aspose.PSD](../../imageloadersregistry/)
* hopsättning [Aspose.PSD](../../../)


