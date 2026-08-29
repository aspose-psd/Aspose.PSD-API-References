---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptor"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método ImageLoadersRegistry. Obtiene el primer descriptor compatible encontrado adecuado para el *stream* especificado y opcionalmente los *loadOptions*"
type: docs
weight: 40
url: /es/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Obtiene el primer descriptor compatible encontrado que sea adecuado para el *stream* especificado y, opcionalmente, para los *loadOptions*.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo. |
| loadOptions | LoadOptions | Las opciones de carga. |

### Valor devuelto

El descriptor de cargador que soporta el *stream* y los *loadOptions* especificados o null si no se encuentra tal descriptor.

## Observaciones

El primer descriptor de cargador será en realidad el último registrado.

### Ver también

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


