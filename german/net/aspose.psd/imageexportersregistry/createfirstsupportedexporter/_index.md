---
title: "ImageExportersRegistry.CreateFirstSupportedExporter"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ImageExportersRegistry-Methode. Erstellt den zuerst gefundenen Exporter, der für die angegebenen Speicheroptionen und das Bild geeignet ist."
type: docs
weight: 30
url: /de/net/aspose.psd/imageexportersregistry/createfirstsupportedexporter/
---
{{< psd/tize >}}
## ImageExportersRegistry.CreateFirstSupportedExporter method

Erstellt den zuerst gefundenen Exporter, der für die angegebenen Speicheroptionen und das Bild geeignet ist.

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | Image | Das zu exportierende Bild. |
| Optionen | ImageOptionsBase | Die zu verwendenden Speicheroptionen für den Export. |

### Rückgabewert

Der Exporter, der das angegebene Bild und die Speicheroptionen unterstützt, oder null, falls kein solcher Exporter gefunden wird.

## Hinweise

Der zuerst gefundene Exporter ist tatsächlich der zuletzt registrierte.

### Siehe auch

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


