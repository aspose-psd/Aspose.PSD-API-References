---
title: "ImageExportersRegistry.CreateFirstSupportedExporter"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método ImageExportersRegistry. Crea el primer exportador encontrado adecuado para las opciones de guardado y la imagen especificadas."
type: docs
weight: 30
url: /es/net/aspose.psd/imageexportersregistry/createfirstsupportedexporter/
---
{{< psd/tize >}}
## ImageExportersRegistry.CreateFirstSupportedExporter method

Crea el primer exportador encontrado que sea adecuado para las opciones de guardado e imagen especificadas.

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagen | Image | La imagen a exportar. |
| opciones | ImageOptionsBase | Las opciones de guardado a usar para la exportación. |

### Valor devuelto

El exportador que admite la imagen y las opciones de guardado especificadas o null si no se encuentra dicho exportador.

## Observaciones

El primer exportador será en realidad el último registrado.

### Ver también

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


