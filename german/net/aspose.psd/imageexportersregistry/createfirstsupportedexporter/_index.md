---
title: ImageExportersRegistry.CreateFirstSupportedExporter
second_title: Aspose.PSD für .NET-API-Referenz
description: ImageExportersRegistry methode. Erstellt den ersten gefundenen Exporter der für die angegebenen Speicheroptionen und das angegebene Bild geeignet ist.
type: docs
weight: 30
url: /de/net/aspose.psd/imageexportersregistry/createfirstsupportedexporter/
---
## ImageExportersRegistry.CreateFirstSupportedExporter method

Erstellt den ersten gefundenen Exporter, der für die angegebenen Speicheroptionen und das angegebene Bild geeignet ist.

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | Image | Das zu exportierende Bild. |
| options | ImageOptionsBase | Die für den Export zu verwendenden Speicheroptionen. |

### Rückgabewert

Der Exporter, der das angegebene Bild und die Speicheroptionen unterstützt, oder null, wenn kein solcher Exporter gefunden wird.

### Bemerkungen

Der erste Exporteur wird tatsächlich der letzte registrierte sein.

### Siehe auch

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namensraum [Aspose.PSD](../../imageexportersregistry/)
* Montage [Aspose.PSD](../../../)


