---
title: "Clase FileStreamContainer"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileStreamContainer. Ayudante para el procesamiento de flujos de archivo"
type: docs
weight: 4720
url: /es/net/aspose.psd/filestreamcontainer/
---
{{< psd/tize >}}
## FileStreamContainer class

Ayudante para el procesamiento de flujos de archivo.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Obtiene un valor que indica si el flujo admite lectura. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Obtiene un valor que indica si el flujo admite búsqueda. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Obtiene un valor que indica si el flujo admite escritura. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtiene un valor que indica si esta instancia está eliminada. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath/) { get; } | Obtiene la ruta del archivo. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated/) { get; } | Obtiene un valor que indica si el flujo se creó explícitamente. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Obtiene un valor que indica si este flujo se elimina al cerrarse. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal/) { get; set; } | Obtiene o establece un valor que indica si el flujo es temporal. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Obtiene o establece la longitud del flujo en bytes. Este valor es menor que la Length por la posición inicial del flujo pasada en el constructor de StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Obtiene o establece la posición actual dentro del flujo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Obtiene el flujo de datos. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Obtiene un objeto que puede usarse para sincronizar el acceso al recurso sincronizado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream/)(string, bool) | Crea un nuevo flujo de archivo. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream/)(string) | Abre un flujo de archivo existente. Si el flujo de archivo no existe, se lanza la excepción apropiada. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Descarta la instancia actual. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Limpia todos los búferes de este flujo y hace que cualquier dato almacenado en búfer se escriba en el dispositivo subyacente. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[]) | Lee bytes para llenar el búfer de bytes especificado. |
| virtual [Read](../../aspose.psd/streamcontainer/read/)(byte[], int, int) | Lee una secuencia de bytes del flujo actual y avanza la posición dentro del flujo en la cantidad de bytes leídos. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Lee un byte del flujo y avanza la posición dentro del flujo en un byte, o devuelve -1 si está al final del flujo. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Guarda (copia) los datos del flujo al flujo especificado. Utiliza el tamaño de búfer predeterminado [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) y el valor de [`Length`](../streamcontainer/length/) del flujo. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Guarda (copia) los datos del flujo al flujo especificado. Utiliza el tamaño de búfer predeterminado [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) y el valor de [`Length`](../streamcontainer/length/) del flujo. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Guarda (copia) todos los datos del flujo al flujo especificado. Utiliza el valor de [`Length`](../streamcontainer/length/) del flujo. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Guarda (copia) los datos del flujo al flujo especificado. Utiliza el valor de [`Length`](../streamcontainer/length/) del flujo. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int, long) | Guarda (copia) los datos del flujo al flujo especificado. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Guarda (copia) los datos del flujo al flujo especificado. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Establece la posición dentro del flujo actual. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Establece la posición del flujo al inicio del mismo. Este valor representa el desplazamiento desde la posición inicial del flujo pasada en el constructor de StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)() | Convierte los datos del flujo a la matriz de bytes. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/)(long, long) | Convierte los datos del flujo a la matriz de bytes. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[]) | Escribe todos los bytes especificados al flujo. |
| virtual [Write](../../aspose.psd/streamcontainer/write/)(byte[], int, int) | Escribe una secuencia de bytes al flujo actual y avanza la posición actual dentro de este flujo en la cantidad de bytes escritos. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Escribe un byte en la posición actual del flujo y avanza la posición dentro del flujo en un byte. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Copia los datos contenidos a otro [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Copia los datos contenidos a otro [`StreamContainer`](../streamcontainer/). |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit/#op_explicit_1) | Realiza una conversión explícita de `FileStreamContainer` a Stream. (2 operadores) |

### Ver también

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


