---
title: PsdImage.GlobalAngle
second_title: Справочник по Aspose.PSD для .NET API
description: PsdImage свойство. Получает или задает глобальный угол.
type: docs
weight: 100
url: /ru/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
## PsdImage.GlobalAngle property

Получает или задает глобальный угол.

```csharp
public int GlobalAngle { get; set; }
```

### Примеры

Следующий код демонстрирует поддержку свойства PsdImage.GlobalAngle для изменения глобального значения угла.

```csharp
[C#]

// Когда свойство DropShadowEffect.UseGlobalLight равно 'true', тогда объект DropShadowEffect использует значение угла из свойства PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Смотрите также

* class [PsdImage](../)
* пространство имен [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* сборка [Aspose.PSD](../../../)


