---
title: "Timeline.Save"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Timeline. Сохраняет PsdImages и данные Timeline в указанное файловое расположение в указанном формате согласно параметрам сохранения"
type: docs
weight: 70
url: /ru/net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

Сохраняет данные PsdImage и Timeline в указанное файловое расположение в указанном формате в соответствии с параметрами сохранения.

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| filePath | String | Путь к файлу. |
| опции | ImageOptionsBase | Опции. |

## Примеры

Следующий код демонстрирует поддержку экспорта Timeline в изображение Gif.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### См. также

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

Сохраняет данные PsdImage и Timeline в указанный поток в указанном формате в соответствии с параметрами сохранения.

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| outputStream | Stream | Выходной поток. |
| опции | ImageOptionsBase | Опции. |

## Примеры

Следующий код демонстрирует поддержку экспорта Timeline в изображение Gif.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### См. также

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


