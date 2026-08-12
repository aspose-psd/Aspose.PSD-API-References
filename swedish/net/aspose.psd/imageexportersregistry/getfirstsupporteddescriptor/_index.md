---
title: "ImageExportersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ImageExportersRegistry-metoden. Hämtar den först hittade stödjande beskrivaren som är lämplig för de angivna sparalternativen och bilden"
type: docs
weight: 40
url: /sv/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageExportersRegistry.GetFirstSupportedDescriptor method

Hämtar den först hittade stödjade descriptor som är lämplig för de angivna sparalternativen och bilden.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | Image | Bilden som ska exporteras. |
| alternativ | ImageOptionsBase | Alternativen. |

### Returvärde

Exportörbeskrivaren som stödjer den angivna bilden och sparalternativen eller null om ingen sådan beskrivare hittas.

## Anmärkningar

Den första exportörbeskrivaren kommer i själva verket att vara den sist registrerade.

### Se även

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


