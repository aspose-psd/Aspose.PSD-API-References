---
title: ImageLoadersRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD för .NET API-referens
description: ImageLoadersRegistry metod. Får den näve som stöds beskrivaren som är lämplig för den angivnastream och valfrittloadOptions .
type: docs
weight: 40
url: /sv/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Får den näve som stöds beskrivaren som är lämplig för den angivna*stream* och valfritt*loadOptions* .

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen. |
| loadOptions | LoadOptions | Lastalternativen. |

### Returvärde

Lastarbeskrivningen som stöder det angivna*stream* och*loadOptions* eller null om ingen sådan beskrivning hittas.

### Anmärkningar

Den första laddarbeskrivningen kommer faktiskt att vara den senast registrerade.

### Se även

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namnutrymme [Aspose.PSD](../../imageloadersregistry/)
* hopsättning [Aspose.PSD](../../../)


