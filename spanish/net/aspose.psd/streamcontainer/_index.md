---
title: "Clase StreamContainer"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.StreamContainer. Representa un contenedor de flujo que contiene el flujo y proporciona rutinas de procesamiento del flujo"
type: docs
weight: 6140
url: /es/net/aspose.psd/streamcontainer/
---
{{< psd/tize >}}
## StreamContainer class

Representa un contenedor de flujo que contiene el flujo y proporciona rutinas de procesamiento de flujo.

```csharp
public class StreamContainer : DisposableObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | Inicializa una nueva instancia de la clase `StreamContainer`. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | Inicializa una nueva instancia de la clase `StreamContainer`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Obtiene un valor que indica si el flujo admite lectura. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Obtiene un valor que indica si el flujo admite búsqueda. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Obtiene un valor que indica si el flujo admite escritura. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Obtiene un valor que indica si este flujo se elimina al cerrarse. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Obtiene o establece la longitud del flujo en bytes. Este valor es menor que la Length por la posición inicial del flujo pasada en el constructor de StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Obtiene o establece la posición actual dentro del flujo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Obtiene el flujo de datos. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Obtiene un objeto que puede usarse para sincronizar el acceso al recurso sincronizado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Limpia todos los búferes de este flujo y hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | Lee bytes para llenar el búfer de bytes especificado. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | Lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo en la cantidad de bytes leídos. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Lee un byte del flujo y avanza la posición dentro del flujo en un byte, o devuelve -1 si está al final del flujo. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | Guarda (copia) los datos del flujo al flujo especificado. Utiliza el tamaño de búfer predeterminado [`ReadWriteBytesCount`](./readwritebytescount/) y el valor del flujo [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | Guarda (copia) los datos del flujo al flujo especificado. Utiliza el tamaño de búfer predeterminado [`ReadWriteBytesCount`](./readwritebytescount/) y el valor del flujo [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | Guarda (copia) todos los datos del flujo al flujo especificado. Utiliza el valor del flujo [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | Guarda (copia) los datos del flujo al flujo especificado. Utiliza el valor del flujo [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | Guarda (copia) los datos del flujo al flujo especificado. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | Guarda (copia) los datos del flujo al flujo especificado. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Establece la posición dentro del flujo actual. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Establece la posición del flujo al inicio del mismo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | Convierte los datos del flujo a la matriz de bytes. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | Convierte los datos del flujo a la matriz de bytes. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | Escribe todos los bytes especificados al flujo. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | Escribe una secuencia de bytes al flujo actual y avanza la posición actual dentro de este flujo en la cantidad de bytes escritos. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Escribe un byte en la posición actual del flujo y avanza la posición dentro del flujo en un byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | Copia los datos contenidos a otro `StreamContainer`. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | Copia los datos contenidos a otro `StreamContainer`. |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | Realiza una conversión explícita de `StreamContainer` a Stream. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | Especifica la cantidad de bytes de lectura y escritura al leer secuencialmente. |

### Ver también

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


