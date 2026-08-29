---
title: "ImageExportersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ImageExportersRegistry-Methode. Gibt den zuerst gefundenen unterstützten Deskriptor zurück, der für die angegebenen Speicheroptionen und das Bild geeignet ist."
type: docs
weight: 40
url: /de/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageExportersRegistry.GetFirstSupportedDescriptor method

Liefert den zuerst gefundenen unterstützten Deskriptor, der für die angegebenen Speicheroptionen und das Bild geeignet ist.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | Image | Das zu exportierende Bild. |
| Optionen | ImageOptionsBase | Die Optionen. |

### Rückgabewert

Der Exporter-Deskriptor, der das angegebene Bild und die Speicheroptionen unterstützt, oder null, falls kein solcher Deskriptor gefunden wird.

## Hinweise

Der zuerst gefundene Exporter-Deskriptor ist tatsächlich der zuletzt registrierte.

### Siehe auch

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


