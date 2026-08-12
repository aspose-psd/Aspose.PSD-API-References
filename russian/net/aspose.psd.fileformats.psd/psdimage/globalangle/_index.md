---
title: "PsdImage.GlobalAngle"
second_title: "Справочник API Aspose.PSD для .NET"
description: "PsdImage свойство. Возвращает или задает глобальный угол"
type: docs
weight: 100
url: /ru/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
{{< psd/tize >}}
## PsdImage.GlobalAngle property

Получает или задает глобальный угол.

```csharp
public int GlobalAngle { get; set; }
```

## Примеры

Следующий код демонстрирует поддержку свойства PsdImage.GlobalAngle для изменения глобального значения угла.

```csharp
[C#]

// Когда свойство DropShadowEffect.UseGlobalLight имеет значение 'true', объект DropShadowEffect использует значение угла из свойства PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### См. также

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


