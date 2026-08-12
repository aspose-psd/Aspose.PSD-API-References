---
title: "ImageLoadersRegistry.CreateFirstSupportedLoader"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método ImageLoadersRegistry. Crea el primer cargador encontrado adecuado para el *stream* especificado y, opcionalmente, los *loadOptions*."
type: docs
weight: 30
url: /es/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
{{< psd/tize >}}
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Crea el primer cargador encontrado que sea adecuado para el *stream* especificado y, opcionalmente, para los *loadOptions*.

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo. |
| loadOptions | LoadOptions | Las opciones de carga. |

### Valor devuelto

El cargador que soporta el *stream* y los *loadOptions* especificados o null si no se encuentra ningún cargador de ese tipo.

## Observaciones

El primer cargador será en realidad el último registrado.

### Ver también

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


