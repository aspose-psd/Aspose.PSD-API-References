---
title: ImageExportersRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD für .NET-API-Referenz
description: ImageExportersRegistry methode. Ruft den ersten gefundenen unterstützten Deskriptor ab der für die angegebenen Speicheroptionen und das angegebene Bild geeignet ist.
type: docs
weight: 40
url: /de/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
## ImageExportersRegistry.GetFirstSupportedDescriptor method

Ruft den ersten gefundenen unterstützten Deskriptor ab, der für die angegebenen Speicheroptionen und das angegebene Bild geeignet ist.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | Image | Das zu exportierende Bild. |
| options | ImageOptionsBase | Die Optionen. |

### Rückgabewert

Der Exporter-Deskriptor, der das angegebene Bild und die Speicheroptionen unterstützt, oder null, wenn kein solcher Deskriptor gefunden wird.

### Bemerkungen

Der erste Exporteur-Deskriptor ist tatsächlich der letzte registrierte.

### Siehe auch

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namensraum [Aspose.PSD](../../imageexportersregistry/)
* Montage [Aspose.PSD](../../../)


