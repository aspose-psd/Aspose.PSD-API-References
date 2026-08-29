---
title: "WarpSettings.WarpSettings"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Конструктор WarpSettings. Инициализирует новый экземпляр класса WarpSettings"
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

Инициализирует новый экземпляр класса [`WarpSettings`](../).

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| meshPoints | PointF[] | Точки сетки искажения |
| границы | Rectangle | Границы изображения искажения |

## Примеры

Следующий код демонстрирует поддержку свойства WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Получить настройки искажения
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Установить новый размер
    // Для Photoshop значение может быть от 1 до 50, и вы не можете корректно сохранить файл PSD.
    warpSettings.GridSize = new Size(100, 100);

    // Установить допустимое значение
    warpSettings.GridSize = new Size(3, 3);

    // Отрисовать пример файла с сеткой x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### См. также

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

Инициализирует новый экземпляр класса [`WarpSettings`](../).

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| meshPoints | PointF[] | Точки сетки искажения |
| границы | Rectangle | Границы изображения искажения |
| style | WarpStyles | Стиль искажения |

## Примеры

Следующий код демонстрирует поддержку свойства WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Получить настройки искажения
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Установить новый размер
    // Для Photoshop значение может быть от 1 до 50, и вы не можете корректно сохранить файл PSD.
    warpSettings.GridSize = new Size(100, 100);

    // Установить допустимое значение
    warpSettings.GridSize = new Size(3, 3);

    // Отрисовать пример файла с сеткой x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### См. также

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

Инициализирует новый экземпляр класса [`WarpSettings`](../).

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | Элементы PS с настройками искажения |
| границы | Rectangle | Границы изображения искажения |

### См. также

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

Инициализирует новый экземпляр класса [`WarpSettings`](../).

```csharp
public WarpSettings(PlacedResource placedResource)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| placedResource | PlacedResource | Ресурс с настройками искажения |

### См. также

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


