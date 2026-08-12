---
title: "JpegExifData.SerializeExifData"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод JpegExifData. Сериализует данные EXIF. Записывает значения тегов и их содержимое. Наибольшее влияние на размер оказывает содержимое тега Thumbnail."
type: docs
weight: 270
url: /ru/net/aspose.psd.exif/jpegexifdata/serializeexifdata/
---
{{< psd/tize >}}
## JpegExifData.SerializeExifData method

Сериализует данные EXIF. Записывает значения тегов и их содержимое. Наиболее влиятельный по размеру тег — содержимое тега миниатюры.

```csharp
public byte[] SerializeExifData()
```

### Возвращаемое значение

Сериализованные данные EXIF.

## Примечания

Общий размер сегмента должен быть меньше или равен MaxExifSegmentSize байт, чтобы получить корректное изображение jpeg. Совет: попробуйте уменьшить размер миниатюры или изменить её сжатие, если размер раздела EXIF слишком велик.

### См. также

* class [JpegExifData](../)
* namespace [Aspose.PSD.Exif](../../../aspose.psd.exif/)
* assembly [Aspose.PSD](../../../)


