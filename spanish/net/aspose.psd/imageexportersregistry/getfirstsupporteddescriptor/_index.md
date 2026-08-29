---
title: "ImageExportersRegistry.GetFirstSupportedDescriptor"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método ImageExportersRegistry. Obtiene el primer descriptor compatible encontrado adecuado para las opciones de guardado y la imagen especificadas."
type: docs
weight: 40
url: /es/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageExportersRegistry.GetFirstSupportedDescriptor method

Obtiene el primer descriptor compatible encontrado que sea adecuado para las opciones de guardado e imagen especificadas.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagen | Image | La imagen a exportar. |
| opciones | ImageOptionsBase | Las opciones. |

### Valor devuelto

El descriptor del exportador que admite la imagen y las opciones de guardado especificadas o null si no se encuentra dicho descriptor.

## Observaciones

El primer descriptor del exportador será en realidad el último registrado.

### Ver también

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


