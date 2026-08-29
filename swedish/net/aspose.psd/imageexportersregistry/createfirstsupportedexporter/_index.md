---
title: "ImageExportersRegistry.CreateFirstSupportedExporter"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ImageExportersRegistry-metoden. Skapar den först hittade exportören som är lämplig för de angivna sparalternativen och bilden"
type: docs
weight: 30
url: /sv/net/aspose.psd/imageexportersregistry/createfirstsupportedexporter/
---
{{< psd/tize >}}
## ImageExportersRegistry.CreateFirstSupportedExporter method

Skapar den först hittade exportören som är lämplig för de angivna sparalternativen och bilden.

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bild | Image | Bilden som ska exporteras. |
| alternativ | ImageOptionsBase | Sparalternativen att använda för export. |

### Returvärde

Exportören som stödjer den angivna bilden och sparalternativen eller null om ingen sådan exportör hittas.

## Anmärkningar

Den första exportören kommer i själva verket att vara den sist registrerade.

### Se även

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


