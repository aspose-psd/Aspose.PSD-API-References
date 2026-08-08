---
title: "IPartialRawDataLoader"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "El cargador de datos parciales."
type: docs
weight: 133
url: /es/java/com.aspose.psd/ipartialrawdataloader/
---
```
public interface IPartialRawDataLoader
```

El cargador de datos parciales.
## Métodos

| Método | Descripción |
| --- | --- |
| [process(Rectangle rectangle, byte[] data, Point start, Point end)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-) | Procesa los datos cargados. |
| [process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)](#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-) | Procesa los datos cargados. |
### process(Rectangle rectangle, byte[] data, Point start, Point end) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end)
```


Procesa los datos cargados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de datos. |
| data | byte[] | Los datos sin procesar. |
| start | [Point](../../com.aspose.psd/point) | El punto de datos inicial. Si no es igual a (left,top) significa que no tenemos un rectángulo completo. |
| end | [Point](../../com.aspose.psd/point) | El punto de datos final. Si no es igual a (right,bottom) significa que no tenemos un rectángulo completo. |

### process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions) {#process-com.aspose.psd.Rectangle-byte---com.aspose.psd.Point-com.aspose.psd.Point-com.aspose.psd.LoadOptions-}
```
public abstract void process(Rectangle rectangle, byte[] data, Point start, Point end, LoadOptions loadOptions)
```


Procesa los datos cargados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | El rectángulo de datos. |
| data | byte[] | Los datos sin procesar. |
| start | [Point](../../com.aspose.psd/point) | El punto de datos inicial. Si no es igual a (left,top) significa que no tenemos un rectángulo completo. |
| end | [Point](../../com.aspose.psd/point) | El punto de datos final. Si no es igual a (right,bottom) significa que no tenemos un rectángulo completo. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Las opciones de carga. |

