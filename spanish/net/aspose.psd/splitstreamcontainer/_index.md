---
title: "Clase SplitStreamContainer"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.SplitStreamContainer. Representa un contenedor de flujo dividido que contiene el flujo y proporciona rutinas de procesamiento de flujo"
type: docs
weight: 6130
url: /es/net/aspose.psd/splitstreamcontainer/
---
{{< psd/tize >}}
## SplitStreamContainer class

Representa un contenedor de flujo dividido que contiene el flujo y proporciona rutinas de procesamiento de flujo.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Inicializa una nueva instancia de la clase `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Inicializa una nueva instancia de la clase `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Inicializa una nueva instancia de la clase `SplitStreamContainer`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | Obtiene un valor que indica si el flujo admite lectura. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | Obtiene un valor que indica si el flujo admite búsqueda. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | Obtiene un valor que indica si el flujo admite escritura. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Obtiene un valor que indica si este flujo se elimina al cerrarse. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | Obtiene o establece la longitud del flujo en bytes. Este valor es menor que la Length por la posición inicial del flujo pasada en el constructor de StreamContainer. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | Obtiene o establece la posición actual dentro del flujo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | Obtiene el flujo de datos. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | Obtiene un objeto que puede usarse para sincronizar el acceso al recurso sincronizado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | Limpia todos los búferes de este flujo y hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Inserta el contenedor de flujo en la posición especificada. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | Lee bytes para llenar el búfer de bytes especificado. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | Lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo en la cantidad de bytes leídos. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | Lee un byte del flujo y avanza la posición dentro del flujo en un byte, o devuelve -1 si está al final del flujo. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Guarda (copia) los datos del flujo al flujo especificado. Utiliza el tamaño de búfer predeterminado [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) y el valor de [`Length`](../streamcontainer/length/) del flujo. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Guarda (copia) los datos del flujo al flujo especificado. Utiliza el tamaño de búfer predeterminado [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) y el valor de [`Length`](../streamcontainer/length/) del flujo. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Guarda (copia) todos los datos del flujo al flujo especificado. Utiliza el valor de [`Length`](../streamcontainer/length/) del flujo. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Guarda (copia) los datos del flujo al flujo especificado. Utiliza el valor de [`Length`](../streamcontainer/length/) del flujo. |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | Guarda (copia) los datos del flujo al flujo especificado. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Guarda (copia) los datos del flujo al flujo especificado. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | Establece la posición dentro del flujo actual. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | Establece la posición del flujo al inicio del mismo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | Convierte los datos del flujo a la matriz de bytes. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Convierte los datos del flujo a la matriz de bytes. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | Escribe todos los bytes especificados al flujo. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | Escribe una secuencia de bytes al flujo actual y avanza la posición actual dentro de este flujo en la cantidad de bytes escritos. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | Escribe un byte en la posición actual del flujo y avanza la posición dentro del flujo en un byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Copia los datos contenidos a otro [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Copia los datos contenidos a otro [`StreamContainer`](../streamcontainer/). |

### Ver también

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


