---
title: "AiImage.ActivePageIndex"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство AiImage. Возвращает или задает индекс активной страницы"
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.ai/aiimage/activepageindex/
---
{{< psd/tize >}}
## AiImage.ActivePageIndex property

Получает или задает индекс активной страницы.

```csharp
public int ActivePageIndex { get; set; }
```

### Property Value

Это свойство актуально только для AI‑изображений в формате PDF. Если изображение не в формате PDF или страниц нет, значение свойства будет -1. Это свойство показывает, какая страница AI‑изображения будет использоваться в качестве основы для рендеринга.

## Примеры

Следующий код демонстрирует поддержку возможности изменения активной страницы в Ai‑изображениях.

```csharp
[C#]

string sourceFile = "threePages.ai";
string firstPageOutputPng = "firstPageOutput.png";
string secondPageOutputPng = "secondPageOutput.png";
string thirdPageOutputPng = "thirdPageOutput.png";

// Загрузите AI‑изображение.
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    // По умолчанию ActivePageIndex равен 0.
    // Таким образом, если вы сохраните AI‑изображение, не изменив это свойство, будет отрисована и сохранена первая страница.
    image.Save(firstPageOutputPng, new PngOptions());

    // Измените индекс активной страницы на вторую страницу.
    image.ActivePageIndex = 1;

    // Сохраните вторую страницу AI‑изображения как PNG‑изображение.
    image.Save(secondPageOutputPng, new PngOptions());

    // Измените индекс активной страницы на третью страницу.
    image.ActivePageIndex = 2;

    // Сохраните третью страницу AI‑изображения как PNG‑изображение.
    image.Save(thirdPageOutputPng, new PngOptions());
}
```

### См. также

* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


