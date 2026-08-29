---
title: "Класс ProgressEventHandlerInfo"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo класс. Этот класс представляет информацию о прогрессе операций загрузки/сохранения/экспорта изображений, которую можно использовать во внешнем приложении для отображения прогресса конвертации конечному пользователю"
type: docs
weight: 5800
url: /ru/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
{{< psd/tize >}}
## ProgressEventHandlerInfo class

Этот класс представляет информацию о прогрессе операций загрузки/сохранения/экспорта изображений, которую можно использовать во внешнем приложении для отображения прогресса конвертации пользователю

```csharp
public class ProgressEventHandlerInfo
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | Получает описание события |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | Получает тип события. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | Получает верхний предел значения прогресса. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | Получает текущее значение прогресса. |

## Примеры

Следующий пример демонстрирует, что прогресс конвертации документа работает корректно и без исключений.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

### См. также

* namespace [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* assembly [Aspose.PSD](../../)


