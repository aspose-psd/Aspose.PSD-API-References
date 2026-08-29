---
title: "IPartialRawDataLoader.Process"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método IPartialRawDataLoader. Procesa los datos cargados"
type: docs
weight: 10
url: /es/net/aspose.psd/ipartialrawdataloader/process/
---
{{< psd/tize >}}
## Process(Rectangle, byte[], Point, Point) {#process}

Procesa los datos cargados.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectángulo | Rectangle | El rectángulo de datos. |
| datos | Byte[] | Los datos sin procesar. |
| start | Punto | El punto de datos inicial. Si no es igual a (left,top) significa que no es un rectángulo completo. |
| fin | Punto | El punto de datos final. Si no es igual a (right,bottom) significa que no es un rectángulo completo. |

### Ver también

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Process(Rectangle, byte[], Point, Point, LoadOptions) {#process_1}

Procesa los datos cargados.

```csharp
public void Process(Rectangle rectangle, byte[] data, Point start, Point end, 
    LoadOptions loadOptions)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectángulo | Rectangle | El rectángulo de datos. |
| datos | Byte[] | Los datos sin procesar. |
| start | Punto | El punto de datos inicial. Si no es igual a (left,top) significa que no es un rectángulo completo. |
| fin | Punto | El punto de datos final. Si no es igual a (right,bottom) significa que no es un rectángulo completo. |
| loadOptions | LoadOptions | Las opciones de carga. |

### Ver también

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [LoadOptions](../../loadoptions/)
* interface [IPartialRawDataLoader](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


