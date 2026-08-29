---
title: "Clase DataStreamSupporter"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.DataStreamSupporter. El contenedor de flujo de datos"
type: docs
weight: 750
url: /es/net/aspose.psd/datastreamsupporter/
---
{{< psd/tize >}}
## DataStreamSupporter class

El contenedor de flujo de datos.

```csharp
public abstract class DataStreamSupporter : DisposableObject
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Obtiene el flujo de datos del objeto. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Obtiene un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Almacena en caché los datos y garantiza que no se realizará una carga adicional de datos desde el subyacente [`DataStreamContainer`](./datastreamcontainer/). |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save)() | Guarda los datos del objeto en el `DataStreamSupporter` actual. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_1)(Stream) | Guarda los datos del objeto en el flujo especificado. |
| [Save](../../aspose.psd/datastreamsupporter/save/#save_2)(string) | Guarda los datos del objeto en la ubicación de archivo especificada. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/#save_3)(string, bool) | Guarda los datos del objeto en la ubicación de archivo especificada. |

### Ver también

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


