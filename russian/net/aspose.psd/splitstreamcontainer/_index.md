---
title: "Класс SplitStreamContainer"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.SplitStreamContainer. Представляет контейнер разделённого потока, который содержит поток и предоставляет процедуры обработки потока"
type: docs
weight: 6130
url: /ru/net/aspose.psd/splitstreamcontainer/
---
{{< psd/tize >}}
## SplitStreamContainer class

Представляет контейнер разделённого потока, который содержит поток и предоставляет процедуры обработки потока.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer/#constructor_1)(Stream) | Инициализирует новый экземпляр класса `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor_2)(Stream, bool) | Инициализирует новый экземпляр класса `SplitStreamContainer`. |
| [SplitStreamContainer](splitstreamcontainer/#constructor)(StreamContainer, bool) | Инициализирует новый экземпляр класса `SplitStreamContainer`. |

## Свойства

| Имя | Описание |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread/) { get; } | Возвращает значение, указывающее, поддерживает ли поток чтение. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek/) { get; } | Возвращает значение, указывающее, поддерживает ли поток перемещение. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite/) { get; } | Возвращает значение, указывающее, поддерживает ли поток запись. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Получает значение, указывающее, освобожден ли этот экземпляр. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose/) { get; } | Возвращает значение, указывающее, будет ли этот поток освобождён при закрытии. |
| override [Length](../../aspose.psd/splitstreamcontainer/length/) { get; set; } | Получает или задаёт длину потока в байтах. Это значение меньше свойства Length на позицию начала потока, переданную в конструкторе StreamContainer. |
| override [Position](../../aspose.psd/splitstreamcontainer/position/) { get; set; } | Получает или задаёт текущую позицию в потоке. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream/) { get; } | Получает поток данных. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot/) { get; } | Получает объект, который можно использовать для синхронизации доступа к синхронизированному ресурсу. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Освобождает текущий экземпляр. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush/)() | Очищает все буферы этого потока и заставляет любые буферизованные данные записываться в базовое устройство. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert/)(int, StreamContainer, bool) | Вставляет контейнер потока в указанную позицию. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read)(byte[]) | Читает байты, чтобы заполнить указанный буфер байтов. |
| override [Read](../../aspose.psd/splitstreamcontainer/read/#read_1)(byte[], int, int) | Читает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte/)() | Читает один байт из потока и перемещает позицию в потоке на один байт, или возвращает -1, если достигнут конец потока. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) и значение потока [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию [`ReadWriteBytesCount`](../streamcontainer/readwritebytescount/) и значение потока [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(Stream, int) | Сохраняет (копирует) все данные потока в указанный поток. Использует значение потока [`Length`](../streamcontainer/length/). |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int) | Сохраняет (копирует) данные потока в указанный поток. Использует значение потока [`Length`](../streamcontainer/length/). |
| override [Save](../../aspose.psd/splitstreamcontainer/save/#save_2)(Stream, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| virtual [Save](../../aspose.psd/streamcontainer/save/)(string, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek/)(long, SeekOrigin) | Устанавливает позицию в текущем потоке. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin/)() | Устанавливает позицию потока в начало потока. Это значение представляет смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes)() | Преобразует данные потока в массив Byte. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes/#tobytes_1)(long, long) | Преобразует данные потока в массив Byte. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write)(byte[]) | Записывает все указанные байты в поток. |
| override [Write](../../aspose.psd/splitstreamcontainer/write/#write_1)(byte[], int, int) | Записывает последовательность байтов в текущий поток и перемещает текущую позицию в этом потоке на количество записанных байтов. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte/)(byte) | Записывает один байт в текущую позицию в потоке и перемещает позицию в потоке на один байт. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer) | Копирует содержащиеся данные в другой [`StreamContainer`](../streamcontainer/). |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto/)(StreamContainer, long) | Копирует содержащиеся данные в другой [`StreamContainer`](../streamcontainer/). |

### См. также

* class [StreamContainer](../streamcontainer/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


