---
title: "Image.GetFileFormat"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Image. Получает формат файла"
type: docs
weight: 270
url: /ru/net/aspose.psd/image/getfileformat/
---
{{< psd/tize >}}
## GetFileFormat(string) {#getfileformat_1}

Получает формат файла.

```csharp
public static FileFormat GetFileFormat(string filePath)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу. |

### Возвращаемое значение

Определённый формат файла.

## Примечания

Определённый формат файла не означает, что указанное изображение может быть загружено. Используйте одну из перегрузок метода CanLoad, чтобы определить, может ли файл быть загружен.

### См. также

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## GetFileFormat(Stream) {#getfileformat}

Получает формат файла.

```csharp
public static FileFormat GetFileFormat(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток. |

### Возвращаемое значение

Определённый формат файла.

## Примечания

Определённый формат файла не означает, что указанное изображение может быть загружено. Используйте одну из перегрузок метода CanLoad, чтобы определить, может ли поток быть загружен.

### См. также

* enum [FileFormat](../../fileformat/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


