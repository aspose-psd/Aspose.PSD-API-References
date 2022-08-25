---
title: StreamContainer
second_title: Справочник по Aspose.PSD для .NET API
description: Представляет контейнер потока который содержит поток и предоставляет подпрограммы обработки потока.
type: docs
weight: 5570
url: /ru/net/aspose.psd/streamcontainer/
---
## StreamContainer class

Представляет контейнер потока, который содержит поток и предоставляет подпрограммы обработки потока.

```csharp
public class StreamContainer : DisposableObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [StreamContainer](streamcontainer#constructor)(Stream) | Инициализирует новый экземпляр[`StreamContainer`](../streamcontainer) класс. |
| [StreamContainer](streamcontainer#constructor_1)(Stream, bool) | Инициализирует новый экземпляр[`StreamContainer`](../streamcontainer) класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread) { get; } | Получает значение, указывающее, поддерживает ли поток чтение. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek) { get; } | Получает значение, указывающее, поддерживает ли поток поиск. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite) { get; } | Получает значение, указывающее, поддерживает ли поток запись. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose) { get; } | Получает значение, указывающее, удаляется ли этот поток при закрытии. |
| virtual [Length](../../aspose.psd/streamcontainer/length) { get; set; } | Получает или задает длину потока в байтах. Это значение меньше, чемLengthпо начальной позиции потока, переданной в конструкторе StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position) { get; set; } | Получает или задает текущую позицию в потоке. Это значение представляет собой смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream) { get; } | Получает поток данных. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot) { get; } | Получает объект, который можно использовать для синхронизации доступа к синхронизируемому ресурсу. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush)() | Очищает все буферы для этого потока и вызывает запись всех буферизованных данных на базовое устройство. |
| virtual [Read](../../aspose.psd/streamcontainer/read#read)(byte[]) | Считывает байты, чтобы заполнить указанный буфер байтов. |
| virtual [Read](../../aspose.psd/streamcontainer/read#read_1)(byte[], int, int) | Считывает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte)() | Считывает байт из потока и сдвигает позицию в потоке на один байт или возвращает -1, если в конце потока. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save)(Stream) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию[`ReadWriteBytesCount`](./readwritebytescount) и поток[`Length`](./length) значение. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save_3)(string) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию[`ReadWriteBytesCount`](./readwritebytescount) и поток[`Length`](./length) значение. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save_1)(Stream, int) | Сохраняет (копирует) все данные потока в указанный поток. Использует поток[`Length`](./length) значение. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save_4)(string, int) | Сохраняет (копирует) данные потока в указанный поток. Использует поток[`Length`](./length) значение. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save_2)(Stream, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| virtual [Save](../../aspose.psd/streamcontainer/save#save_5)(string, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek)(long, SeekOrigin) | Устанавливает позицию в текущем потоке. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin)() | Устанавливает позицию потока в начало потока. Это значение представляет собой смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes#tobytes)() | Преобразует потоковые данные вByte массив. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes#tobytes_1)(long, long) | Преобразует потоковые данные вByte массив. |
| virtual [Write](../../aspose.psd/streamcontainer/write#write)(byte[]) | Записывает все указанные байты в поток. |
| virtual [Write](../../aspose.psd/streamcontainer/write#write_1)(byte[], int, int) | Записывает последовательность байтов в текущий поток и продвигает текущую позицию в этом потоке на количество записанных байтов. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte)(byte) | Записывает байт в текущую позицию в потоке и перемещает позицию в потоке на один байт. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto#writeto)(StreamContainer) | Копирует содержащиеся данные в другой[`StreamContainer`](../streamcontainer) . |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto#writeto_1)(StreamContainer, long) | Копирует содержащиеся данные в другой[`StreamContainer`](../streamcontainer) . |
| [explicit operator](../../aspose.psd/streamcontainer/op_explicit) | Выполняет явное преобразование из[`StreamContainer`](../streamcontainer) кStream . |

## Поля

| Имя | Описание |
| --- | --- |
| const [ReadWriteBytesCount](../../aspose.psd/streamcontainer/readwritebytescount) | Указывает количество байтов для чтения и записи при последовательном чтении. |

### Смотрите также

* class [DisposableObject](../disposableobject)
* пространство имен [Aspose.PSD](../../aspose.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
