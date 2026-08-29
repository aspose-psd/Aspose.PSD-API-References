---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ImageLoadersRegistry-metod. Hämtar den först hittade stödjade beskrivaren som är lämplig för den angivna strömmen och eventuellt loadOptions."
type: docs
weight: 40
url: /sv/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Hämtar den första hittade stödjade beskrivaren som är lämplig för den angivna *stream* och eventuellt *loadOptions*.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Strömmen. |
| loadOptions | LoadOptions | Laddningsalternativen. |

### Returvärde

Laddarbeskrivaren som stödjer den angivna *stream* och *loadOptions* eller null om ingen sådan beskrivare hittas.

## Anmärkningar

Den första laddarbeskrivaren kommer faktiskt att vara den sist registrerade.

### Se även

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


