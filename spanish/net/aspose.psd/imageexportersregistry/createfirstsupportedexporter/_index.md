---
title: ImageExportersRegistry.CreateFirstSupportedExporter
second_title: Referencia de API de Aspose.PSD para .NET
description: ImageExportersRegistry método. Crea el primer exportador encontrado adecuado para las opciones de guardado y la imagen especificados.
type: docs
weight: 30
url: /es/net/aspose.psd/imageexportersregistry/createfirstsupportedexporter/
---
## ImageExportersRegistry.CreateFirstSupportedExporter method

Crea el primer exportador encontrado adecuado para las opciones de guardado y la imagen especificados.

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | Image | La imagen a exportar. |
| options | ImageOptionsBase | Las opciones de guardado que se usarán para la exportación. |

### Valor_devuelto

El exportador que admite la imagen especificada y las opciones de guardado o nulo si no se encuentra dicho exportador.

### Observaciones

El primer exportador será en realidad el último registrado.

### Ver también

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* espacio de nombres [Aspose.PSD](../../imageexportersregistry/)
* asamblea [Aspose.PSD](../../../)


