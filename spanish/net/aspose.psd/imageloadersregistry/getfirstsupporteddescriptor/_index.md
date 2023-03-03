---
title: ImageLoadersRegistry.GetFirstSupportedDescriptor
second_title: Referencia de API de Aspose.PSD para .NET
description: ImageLoadersRegistry método. Obtiene el primer descriptor compatible encontrado adecuado para el especificadostream y opcionalmente elloadOptions .
type: docs
weight: 40
url: /es/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Obtiene el primer descriptor compatible encontrado adecuado para el especificado*stream* y opcionalmente el*loadOptions* .

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | La corriente. |
| loadOptions | LoadOptions | Las opciones de carga. |

### Valor_devuelto

El descriptor del cargador que soporta el especificado*stream* y*loadOptions* o nulo si no se encuentra dicho descriptor.

### Observaciones

El primer descriptor del cargador será en realidad el último registrado.

### Ver también

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* espacio de nombres [Aspose.PSD](../../imageloadersregistry/)
* asamblea [Aspose.PSD](../../../)


