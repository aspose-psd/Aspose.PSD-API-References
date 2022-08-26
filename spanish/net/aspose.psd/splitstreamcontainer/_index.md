---
title: SplitStreamContainer
second_title: Referencia de API de Aspose.PSD para .NET
description: Representa el contenedor de flujo dividido que contiene el flujo y proporciona rutinas de procesamiento de flujo.
type: docs
weight: 5560
url: /es/net/aspose.psd/splitstreamcontainer/
---
## SplitStreamContainer class

Representa el contenedor de flujo dividido que contiene el flujo y proporciona rutinas de procesamiento de flujo.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer#constructor_1)(Stream) | Inicializa una nueva instancia del[`SplitStreamContainer`](../splitstreamcontainer) clase. |
| [SplitStreamContainer](splitstreamcontainer#constructor_2)(Stream, bool) | Inicializa una nueva instancia del[`SplitStreamContainer`](../splitstreamcontainer) clase. |
| [SplitStreamContainer](splitstreamcontainer#constructor)(StreamContainer, bool) | Inicializa una nueva instancia del[`SplitStreamContainer`](../splitstreamcontainer) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread) { get; } | Obtiene un valor que indica si la secuencia admite la lectura. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek) { get; } | Obtiene un valor que indica si la secuencia admite la búsqueda. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite) { get; } | Obtiene un valor que indica si la secuencia admite escritura. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose) { get; } | Obtiene un valor que indica si esta secuencia se elimina al cerrar. |
| override [Length](../../aspose.psd/splitstreamcontainer/length) { get; set; } | Obtiene o establece la longitud del flujo en bytes. Este valor es menor que elLengthpor la posición inicial de flujo pasada en el constructor StreamContainer. |
| override [Position](../../aspose.psd/splitstreamcontainer/position) { get; set; } | Obtiene o establece la posición actual dentro de la secuencia. Este valor representa el desplazamiento desde la posición inicial de la secuencia pasada en el constructor StreamContainer. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream) { get; } | Obtiene el flujo de datos. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot) { get; } | Obtiene un objeto que se puede usar para sincronizar el acceso al recurso sincronizado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina la instancia actual. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush)() | Borra todos los búferes de esta secuencia y hace que los datos almacenados en el búfer se escriban en el dispositivo subyacente. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert)(int, StreamContainer, bool) | Inserta el contenedor de flujo en la posición especificada. |
| override [Read](../../aspose.psd/splitstreamcontainer/read#read)(byte[]) | Lee bytes para llenar el búfer de bytes especificado. |
| override [Read](../../aspose.psd/splitstreamcontainer/read#read_1)(byte[], int, int) | Lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo según el número de bytes leídos. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte)() | Lee un byte de la secuencia y avanza la posición dentro de la secuencia en un byte, o devuelve -1 si está al final de la secuencia. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(Stream) | Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el tamaño de búfer predeterminado[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) y corriente[`Length`](../streamcontainer/length) valor. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(string) | Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el tamaño de búfer predeterminado[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount) y corriente[`Length`](../streamcontainer/length) valor. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(Stream, int) | Guarda (copia) todos los datos del flujo en el flujo especificado. corriente de usos[`Length`](../streamcontainer/length) valor. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(string, int) | Guarda (copia) los datos del flujo en el flujo especificado. corriente de usos[`Length`](../streamcontainer/length) valor. |
| override [Save](../../aspose.psd/splitstreamcontainer/save#save_2)(Stream, int, long) | Guarda (copia) los datos del flujo en el flujo especificado. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(string, int, long) | Guarda (copia) los datos del flujo en el flujo especificado. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek)(long, SeekOrigin) | Establece la posición dentro de la secuencia actual. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin)() | Establece la posición de la transmisión al comienzo de la transmisión. Este valor representa el desplazamiento desde la posición inicial de la secuencia pasada en el constructor StreamContainer. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes#tobytes)() | Convierte los datos de flujo alByte matriz. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes#tobytes_1)(long, long) | Convierte los datos de flujo alByte matriz. |
| override [Write](../../aspose.psd/splitstreamcontainer/write#write)(byte[]) | Escribe todos los bytes especificados en la secuencia. |
| override [Write](../../aspose.psd/splitstreamcontainer/write#write_1)(byte[], int, int) | Escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo según el número de bytes escritos. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte)(byte) | Escribe un byte en la posición actual en la secuencia y avanza la posición dentro de la secuencia en un byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto)(StreamContainer) | Copia los datos contenidos a otro[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto)(StreamContainer, long) | Copia los datos contenidos a otro[`StreamContainer`](../streamcontainer) . |

### Ver también

* class [StreamContainer](../streamcontainer)
* espacio de nombres [Aspose.PSD](../../aspose.psd)
* asamblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
