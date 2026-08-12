---
title: "Класс XmpPacketWrapper"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Xmp.XmpPacketWrapper. Содержит сериализованный пакет xmp, включающий заголовок и трейлер"
type: docs
weight: 6790
url: /ru/net/aspose.psd.xmp/xmppacketwrapper/
---
{{< psd/tize >}}
## XmpPacketWrapper class

Содержит сериализованный пакет xmp, включающий заголовок и трейлер.

```csharp
public class XmpPacketWrapper
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | Инициализирует новый экземпляр класса `XmpPacketWrapper`. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Инициализирует новый экземпляр класса `XmpPacketWrapper`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | Получает инструкцию обработки заголовка. |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | Получает метаданные XMP. Необязательно. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | Получает массив [`XmpPackage`](../xmppackage/) внутри XMP. |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | Получает количество пакетов внутри структуры XMP. |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | Получает инструкцию обработки трейлера. |

## Методы

| Имя | Описание |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | Добавляет пакет. |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | Удаляет все [`XmpPackage`](../xmppackage/) внутри XMP. |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | Определяет, существует ли пакет в обёртке xmp. |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | Получает пакет по URI пространства имён. |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | Удаляет пакет XMP. |

## Примечания

Обёртка, состоящая из пары инструкций обработки XML (PI), может быть размещена вокруг элемента rdf:RDF.

### См. также

* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


