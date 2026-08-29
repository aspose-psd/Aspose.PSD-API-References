---
title: "Класс TiffDataType"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.FileFormats.Tiff.TiffDataType. Тип данных TIFF"
type: docs
weight: 4680
url: /ru/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
{{< psd/tize >}}
## TiffDataType class

Тип данных tiff.

```csharp
public abstract class TiffDataType : IComparable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Возвращает размер дополнительных данных в байтах (в случае, если 12 байт недостаточно для размещения данных тега). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Возвращает количество элементов. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Возвращает размер дополнительных данных в байтах (в случае, если 12 байт недостаточно для размещения данных тега). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Возвращает целочисленное представление идентификатора тега. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Возвращает значение, указывающее, действительны ли данные тега. Действительный тег содержит данные, которые могут быть сохранены. Недействительный тег не может быть сохранён. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Возвращает идентификатор тега. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Возвращает тип тега. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Получает или задает значение, содержащееся в этом типе данных. |

## Методы

| Имя | Описание |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Читает данные тега. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Сравнивает текущий экземпляр с другим объектом того же типа и возвращает целое число, указывающее, предшествует ли текущий экземпляр, следует за ним или находится в том же положении в порядке сортировки, что и другой объект. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Выполняет глубокое клонирование этого экземпляра. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | Возвращает строку, представляющую этот экземпляр. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Записывает дополнительные данные тега. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Записывает данные тега. |

### См. также

* namespace [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* assembly [Aspose.PSD](../../)


