---
title: ImageExportersRegistry.GetFirstSupportedDescriptor
second_title: Referencia de API de Aspose.PSD para .NET
description: ImageExportersRegistry método. Obtiene el primer descriptor admitido adecuado para las opciones de guardado y la imagen especificados.
type: docs
weight: 40
url: /es/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
## ImageExportersRegistry.GetFirstSupportedDescriptor method

Obtiene el primer descriptor admitido adecuado para las opciones de guardado y la imagen especificados.

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| image | Image | La imagen a exportar. |
| options | ImageOptionsBase | Las opciones. |

### Valor_devuelto

El descriptor del exportador que admite la imagen especificada y las opciones de guardado o nulo si no se encuentra dicho descriptor.

### Observaciones

El primer descriptor de exportador será en realidad el último registrado.

### Ver también

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* espacio de nombres [Aspose.PSD](../../imageexportersregistry/)
* asamblea [Aspose.PSD](../../../)


