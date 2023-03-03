---
title: Class StreamContainer
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.StreamContainer clase. Representa el contenedor de flujo que contiene el flujo y proporciona rutinas de procesamiento de flujo.
type: docs
weight: 5640
url: /es/net/aspose.psd/streamcontainer/
---
## StreamContainer class

Representa el contenedor de flujo que contiene el flujo y proporciona rutinas de procesamiento de flujo.

```csharp
public class StreamContainer : DisposableObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | Inicializa una nueva instancia del`StreamContainer` clase. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | Inicializa una nueva instancia del`StreamContainer` clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Obtiene un valor que indica si la secuencia admite la lectura. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Obtiene un valor que indica si la secuencia admite la búsqueda. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Obtiene un valor que indica si la secuencia admite escritura. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia se desecha. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Obtiene un valor que indica si esta secuencia se elimina al cerrar. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Obtiene o establece la longitud del flujo en bytes. Este valor es menor que elLengthpor la posición inicial de flujo pasada en el constructor StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Obtiene o establece la posición actual dentro de la secuencia. Este valor representa el desplazamiento desde la posición inicial de la secuencia pasada en el constructor StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Obtiene el flujo de datos. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Obtiene un objeto que se puede usar para sincronizar el acceso al recurso sincronizado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina la instancia actual. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Borra todos los búferes de esta secuencia y hace que los datos almacenados en el búfer se escriban en el dispositivo subyacente. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | Lee bytes para llenar el búfer de bytes especificado. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | Lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo según el número de bytes leídos. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Lee un byte de la secuencia y avanza la posición dentro de la secuencia en un byte, o devuelve -1 si está al final de la secuencia. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el tamaño de búfer predeterminado[`ReadWriteBytesCount`](./readwritebytescount/) y corriente[`Length`](./length/) valor. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | Guarda (copia) los datos del flujo en el flujo especificado. Utiliza el tamaño de búfer predeterminado[`ReadWriteBytesCount`](./readwritebytescount/) y corriente[`Length`](./length/) valor. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | Guarda (copia) todos los datos del flujo en el flujo especificado. corriente de usos[`Length`](./length/) valor. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | Guarda (copia) los datos del flujo en el flujo especificado. corriente de usos[`Length`](./length/) valor. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | Guarda (copia) los datos del flujo en el flujo especificado. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | Guarda (copia) los datos del flujo en el flujo especificado. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Establece la posición dentro de la secuencia actual. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Establece la posición de la transmisión al comienzo de la transmisión. Este valor representa el desplazamiento desde la posición inicial de la secuencia pasada en el constructor StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | Convierte los datos de flujo alByte matriz. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | Convierte los datos de flujo alByte matriz. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | Escribe todos los bytes especificados en la secuencia. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | Escribe una secuencia de bytes en el flujo actual y avanza la posición actual dentro de este flujo según el número de bytes escritos. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Escribe un byte en la posición actual en la secuencia y avanza la posición dentro de la secuencia en un byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | Copia los datos contenidos a otro`StreamContainer` . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | Copia los datos contenidos a otro`StreamContainer` . |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | Realiza una conversión explícita de`StreamContainer` aStream . |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | Especifica el recuento de bytes de lectura y escritura cuando se lee secuencialmente. |

### Ver también

* class [DisposableObject](../disposableobject/)
* espacio de nombres [Aspose.PSD](../../aspose.psd/)
* asamblea [Aspose.PSD](../../)


