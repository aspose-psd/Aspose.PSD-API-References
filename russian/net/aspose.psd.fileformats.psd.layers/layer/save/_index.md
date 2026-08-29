---
title: "Layer.Save"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Layer. Сохраняет данные объекта в указанный поток"
type: docs
weight: 390
url: /ru/net/aspose.psd.fileformats.psd.layers/layer/save/
---
{{< psd/tize >}}
## Save(Stream) {#save_1}

Сохраняет данные объекта в указанный поток.

```csharp
public override void Save(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, в который сохраняются данные объекта. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentException | Не следует вызывать метод Save без параметров Image |

### См. также

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Сохраняет данные объекта в указанное расположение файла в указанном файловом формате в соответствии с параметрами сохранения.

```csharp
public override void Save(string filePath, ImageOptionsBase options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу. |
| опции | ImageOptionsBase | Опции. |

### См. также

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, bool) {#save_7}

Сохраняет данные объекта в указанное расположение файла.

```csharp
public override void Save(string filePath, bool overWrite)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу, в который сохраняются данные объекта. |
| overWrite | Boolean | если установлено `true`, перезаписывает содержимое файла, иначе будет выполнено добавление. |

### См. также

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Сохраняет данные изображения в указанный поток в указанном файловом формате в соответствии с параметрами сохранения.

```csharp
public override void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Поток, в который сохраняются данные изображения. |
| optionsBase | ImageOptionsBase | Параметры сохранения. |
| boundsRectangle | Rectangle | Прямоугольник границ целевого изображения. Установите пустой прямоугольник для использования границ источника. |

### См. также

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Сохраняет данные объекта в указанное расположение файла в указанном файловом формате в соответствии с параметрами сохранения.

```csharp
public override void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу. |
| опции | ImageOptionsBase | Опции. |
| boundsRectangle | Rectangle | Прямоугольник границ целевого изображения. Установите пустой прямоугольник для использования границ источника. |

### См. также

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


