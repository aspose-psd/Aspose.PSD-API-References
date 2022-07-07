---
title: SplitStreamContainer
second_title: Справочник по Aspose.PSD для .NET API
description: Представляет контейнер разделенного потока который содержит поток и предоставляет подпрограммы обработки потока.
type: docs
weight: 5510
url: /ru/net/aspose.psd/splitstreamcontainer/
---
## SplitStreamContainer class

Представляет контейнер разделенного потока, который содержит поток и предоставляет подпрограммы обработки потока.

```csharp
public class SplitStreamContainer : StreamContainer
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SplitStreamContainer](splitstreamcontainer#constructor_1)(Stream) | Инициализирует новый экземпляр класса[`SplitStreamContainer`](../splitstreamcontainer). |
| [SplitStreamContainer](splitstreamcontainer#constructor_2)(Stream, bool) | Инициализирует новый экземпляр класса[`SplitStreamContainer`](../splitstreamcontainer). |
| [SplitStreamContainer](splitstreamcontainer#constructor)(StreamContainer, bool) | Инициализирует новый экземпляр класса[`SplitStreamContainer`](../splitstreamcontainer). |

## Характеристики

| Имя | Описание |
| --- | --- |
| override [CanRead](../../aspose.psd/splitstreamcontainer/canread) { get; } | Получает значение, указывающее, поддерживает ли поток чтение. |
| override [CanSeek](../../aspose.psd/splitstreamcontainer/canseek) { get; } | Получает значение, указывающее, поддерживает ли поток поиск. |
| override [CanWrite](../../aspose.psd/splitstreamcontainer/canwrite) { get; } | Получает значение, указывающее, поддерживает ли поток запись. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose) { get; } | Получает значение, указывающее, удаляется ли этот поток при закрытии. |
| override [Length](../../aspose.psd/splitstreamcontainer/length) { get; set; } | Получает или задает длину потока в байтах. Это значение меньшеLengthна начальную позицию потока, переданную в конструкторе StreamContainer. |
| override [Position](../../aspose.psd/splitstreamcontainer/position) { get; set; } | Получает или задает текущую позицию в потоке. Это значение представляет собой смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| override [Stream](../../aspose.psd/splitstreamcontainer/stream) { get; } | Получает поток данных. |
| [SyncRoot](../../aspose.psd/splitstreamcontainer/syncroot) { get; } | Получает объект, который можно использовать для синхронизации доступа к синхронизируемому ресурсу. |

## Методы

| Имя | Описание |
| --- | --- |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| override [Flush](../../aspose.psd/splitstreamcontainer/flush)() | Очищает все буферы для этого потока и вызывает запись всех буферизованных данных на базовое устройство. |
| [Insert](../../aspose.psd/splitstreamcontainer/insert)(int, StreamContainer, bool) | Вставляет контейнер потока в указанную позицию. |
| override [Read](../../aspose.psd/splitstreamcontainer/read#read)(byte[]) | Считывает байты, чтобы заполнить указанный буфер байтов. |
| override [Read](../../aspose.psd/splitstreamcontainer/read#read_1)(byte[], int, int) | Считывает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| override [ReadByte](../../aspose.psd/splitstreamcontainer/readbyte)() | Считывает байт из потока и сдвигает позицию в потоке на один байт или возвращает -1, если в конце потока. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(Stream) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount)и значение stream[`Length`](../streamcontainer/length). |
| virtual [Save](../../aspose.psd/streamcontainer/save)(string) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount)и значение stream[`Length`](../streamcontainer/length). |
| virtual [Save](../../aspose.psd/streamcontainer/save)(Stream, int) | Сохраняет (копирует) все данные потока в указанный поток. Использует значение stream[`Length`](../streamcontainer/length). |
| virtual [Save](../../aspose.psd/streamcontainer/save)(string, int) | Сохраняет (копирует) данные потока в указанный поток. Использует значение stream[`Length`](../streamcontainer/length). |
| override [Save](../../aspose.psd/splitstreamcontainer/save#save_2)(Stream, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(string, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| override [Seek](../../aspose.psd/splitstreamcontainer/seek)(long, SeekOrigin) | Устанавливает позицию в текущем потоке. |
| override [SeekBegin](../../aspose.psd/splitstreamcontainer/seekbegin)() | Устанавливает позицию потока в начало потока. Это значение представляет собой смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes#tobytes)() | Преобразует данные потока в массивByte. |
| override [ToBytes](../../aspose.psd/splitstreamcontainer/tobytes#tobytes_1)(long, long) | Преобразует данные потока в массивByte. |
| override [Write](../../aspose.psd/splitstreamcontainer/write#write)(byte[]) | Записывает все указанные байты в поток. |
| override [Write](../../aspose.psd/splitstreamcontainer/write#write_1)(byte[], int, int) | Записывает последовательность байтов в текущий поток и продвигает текущую позицию в этом потоке на количество записанных байтов. |
| override [WriteByte](../../aspose.psd/splitstreamcontainer/writebyte)(byte) | Записывает байт в текущую позицию в потоке и перемещает позицию в потоке на один байт. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto)(StreamContainer) | Копирует содержащиеся данные в другой[`StreamContainer`](../streamcontainer). |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto)(StreamContainer, long) | Копирует содержащиеся данные в другой[`StreamContainer`](../streamcontainer). |

### Смотрите также

* class [StreamContainer](../streamcontainer)
* пространство имен [Aspose.PSD](../../aspose.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
