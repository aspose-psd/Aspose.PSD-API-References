---
title: FileStreamContainer
second_title: Справочник по Aspose.PSD для .NET API
description: Помощник для обработки файлового потока.
type: docs
weight: 4130
url: /ru/net/aspose.psd/filestreamcontainer/
---
## FileStreamContainer class

Помощник для обработки файлового потока.

```csharp
public sealed class FileStreamContainer : StreamContainer
```

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [CanRead](../../aspose.psd/streamcontainer/canread) { get; } | Получает значение, указывающее, поддерживает ли поток чтение. |
| virtual [CanSeek](../../aspose.psd/streamcontainer/canseek) { get; } | Получает значение, указывающее, поддерживает ли поток поиск. |
| virtual [CanWrite](../../aspose.psd/streamcontainer/canwrite) { get; } | Получает значение, указывающее, поддерживает ли поток запись. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Получает значение, указывающее, удален ли этот экземпляр. |
| [FilePath](../../aspose.psd/filestreamcontainer/filepath) { get; } | Получает путь к файлу. |
| [IsCreated](../../aspose.psd/filestreamcontainer/iscreated) { get; } | Получает значение, указывающее, был ли поток создан явно. |
| virtual [IsStreamDisposedOnClose](../../aspose.psd/streamcontainer/isstreamdisposedonclose) { get; } | Получает значение, указывающее, удаляется ли этот поток при закрытии. |
| [IsTemporal](../../aspose.psd/filestreamcontainer/istemporal) { get; set; } | Получает или задает значение, указывающее, является ли поток временным. |
| virtual [Length](../../aspose.psd/streamcontainer/length) { get; set; } | Получает или задает длину потока в байтах. Это значение меньшеLengthна начальную позицию потока, переданную в конструкторе StreamContainer. |
| virtual [Position](../../aspose.psd/streamcontainer/position) { get; set; } | Получает или задает текущую позицию в потоке. Это значение представляет собой смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| virtual [Stream](../../aspose.psd/streamcontainer/stream) { get; } | Получает поток данных. |
| [SyncRoot](../../aspose.psd/streamcontainer/syncroot) { get; } | Получает объект, который можно использовать для синхронизации доступа к синхронизируемому ресурсу. |

## Методы

| Имя | Описание |
| --- | --- |
| static [CreateFileStream](../../aspose.psd/filestreamcontainer/createfilestream)(string, bool) | Создает новый файловый поток. |
| static [OpenFileStream](../../aspose.psd/filestreamcontainer/openfilestream)(string) | Открывает существующий файловый поток. Если файловый поток не существует, выдается соответствующее исключение. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Удаляет текущий экземпляр. |
| virtual [Flush](../../aspose.psd/streamcontainer/flush)() | Очищает все буферы для этого потока и вызывает запись всех буферизованных данных на базовое устройство. |
| virtual [Read](../../aspose.psd/streamcontainer/read)(byte[]) | Считывает байты, чтобы заполнить указанный буфер байтов. |
| virtual [Read](../../aspose.psd/streamcontainer/read)(byte[], int, int) | Считывает последовательность байтов из текущего потока и перемещает позицию в потоке на количество прочитанных байтов. |
| virtual [ReadByte](../../aspose.psd/streamcontainer/readbyte)() | Считывает байт из потока и сдвигает позицию в потоке на один байт или возвращает -1, если в конце потока. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(Stream) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount)и значение stream[`Length`](../streamcontainer/length). |
| virtual [Save](../../aspose.psd/streamcontainer/save)(string) | Сохраняет (копирует) данные потока в указанный поток. Использует размер буфера по умолчанию[`ReadWriteBytesCount`](../streamcontainer/readwritebytescount)и значение stream[`Length`](../streamcontainer/length). |
| virtual [Save](../../aspose.psd/streamcontainer/save)(Stream, int) | Сохраняет (копирует) все данные потока в указанный поток. Использует значение stream[`Length`](../streamcontainer/length). |
| virtual [Save](../../aspose.psd/streamcontainer/save)(string, int) | Сохраняет (копирует) данные потока в указанный поток. Использует значение stream[`Length`](../streamcontainer/length). |
| virtual [Save](../../aspose.psd/streamcontainer/save)(Stream, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| virtual [Save](../../aspose.psd/streamcontainer/save)(string, int, long) | Сохраняет (копирует) данные потока в указанный поток. |
| virtual [Seek](../../aspose.psd/streamcontainer/seek)(long, SeekOrigin) | Устанавливает позицию в текущем потоке. |
| virtual [SeekBegin](../../aspose.psd/streamcontainer/seekbegin)() | Устанавливает позицию потока в начало потока. Это значение представляет собой смещение от начальной позиции потока, переданной в конструкторе StreamContainer. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes)() | Преобразует данные потока в массивByte. |
| virtual [ToBytes](../../aspose.psd/streamcontainer/tobytes)(long, long) | Преобразует данные потока в массивByte. |
| virtual [Write](../../aspose.psd/streamcontainer/write)(byte[]) | Записывает все указанные байты в поток. |
| virtual [Write](../../aspose.psd/streamcontainer/write)(byte[], int, int) | Записывает последовательность байтов в текущий поток и продвигает текущую позицию в этом потоке на количество записанных байтов. |
| virtual [WriteByte](../../aspose.psd/streamcontainer/writebyte)(byte) | Записывает байт в текущую позицию в потоке и перемещает позицию в потоке на один байт. |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto)(StreamContainer) | Копирует содержащиеся данные в другой[`StreamContainer`](../streamcontainer). |
| virtual [WriteTo](../../aspose.psd/streamcontainer/writeto)(StreamContainer, long) | Копирует содержащиеся данные в другой[`StreamContainer`](../streamcontainer). |
| [explicit operator](../../aspose.psd/filestreamcontainer/op_explicit#op_explicit_1) | Выполняет явное преобразование из[`FileStreamContainer`](../filestreamcontainer)вStream. (2 operators) |

### Смотрите также

* class [StreamContainer](../streamcontainer)
* пространство имен [Aspose.PSD](../../aspose.psd)
* сборка [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
