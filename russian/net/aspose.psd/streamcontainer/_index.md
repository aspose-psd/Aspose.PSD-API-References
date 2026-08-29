---
title: "Класс StreamContainer"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.StreamContainer. Представляет контейнер потока, который содержит поток и предоставляет процедуры обработки потока"
type: docs
weight: 6140
url: /ru/net/aspose.psd/streamcontainer/
---
{{< psd/tize >}}
## StreamContainer class

Представляет контейнер потока, который содержит поток и предоставляет процедуры обработки потока.

```csharp
public class StreamContainer : DisposableObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [StreamContainer](streamcontainer/#constructor)(Stream) | Инициализирует новый экземпляр класса `StreamContainer`. |
| [StreamContainer](streamcontainer/#constructor_1)(Stream, bool) | Инициализирует новый экземпляр класса `StreamContainer`. |

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread/) { get; } | Возвращает значение, указывающее, поддерживает ли поток чтение. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek/) { get; } | Возвращает значение, указывающее, поддерживает ли поток перемещение. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite/) { get; } | Возвращает значение, указывающее, поддерживает ли поток запись. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Возвращает значение, указывающее, будет ли этот поток освобождён при закрытии. |
| virtual [Length](../../aspose.psd/streamcontainer/length/) { get; set; } | Получает или задаёт длину потока в байтах. Это значение меньше свойства Length на позицию начала потока, переданную в конструкторе StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position/) { get; set; } | Получает или задаёт текущую позицию в потоке. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream/) { get; } | Получает поток данных. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot/) { get; } | Получает объект, который можно использовать для синхронизации доступа к синхронизированному ресурсу. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush/)() | Очищает все буферы этого потока и заставляет любые буферизованные данные записываться в базовое устройство. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read)(byte[]) | Читает байты, чтобы заполнить указанный буфер байтов. |
| virtual [Read](../../aspose.psd/streamcontainer/read/#read_1)(byte[], int, int) | Читает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte/)() | Читает один байт из потока и перемещает позицию в потоке на один байт, или возвращает -1, если достигнут конец потока. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save)(Stream) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию [`ReadWriteBytesCount`](./readwritebytescount/) и значение потока [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_3)(string) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию [`ReadWriteBytesCount`](./readwritebytescount/) и значение потока [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_1)(Stream, int) | Сохраняет (копирует) все данные потока в указанный поток. Использует значение потока [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_4)(string, int) | Сохраняет (копирует) данные потока в указанный поток. Использует значение потока [`Length`](./length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_2)(Stream, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| virtual [Save](../../aspose.psd/streamcontainer/save/#save_5)(string, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek/)(long, SeekOrigin) | Устанавливает позицию в текущем потоке. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin/)() | Устанавливает позицию потока в начало потока. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes)() | Преобразует данные потока в массив Byte. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes/#tobytes_1)(long, long) | Преобразует данные потока в массив Byte. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write)(byte[]) | Записывает все указанные байты в поток. |
| virtual [Write](../../aspose.psd/streamcontainer/write/#write_1)(byte[], int, int) | Записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte/)(byte) | Записывает один байт в текущую позицию в потоке и перемещает позицию в потоке на один байт. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto)(StreamContainer) | Копирует содержащиеся данные в другой `StreamContainer`. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/#writeto_1)(StreamContainer, long) | Копирует содержащиеся данные в другой `StreamContainer`. |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit/) | Выполняет явное преобразование из `StreamContainer` в Stream. |

## Поля

| Имя | Описание |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount/) | Указывает количество байтов для чтения и записи при последовательном чтении. |

### См. также

* class [DisposableObject](../disposableobject/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


