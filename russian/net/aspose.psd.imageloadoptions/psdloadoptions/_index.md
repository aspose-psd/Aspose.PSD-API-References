---
title: "Класс PsdLoadOptions"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.ImageLoadOptions.PsdLoadOptions class. Параметры загрузки Psd"
type: docs
weight: 5250
url: /ru/net/aspose.psd.imageloadoptions/psdloadoptions/
---
{{< psd/tize >}}
## PsdLoadOptions class

Параметры загрузки PSD

```csharp
public class PsdLoadOptions : LoadOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Конструктор по умолчанию. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AllowNonChangedLayerRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/) { get; set; } | Получает или задает, сохранять ли оригинальные пиксели слоёв во время рендеринга, если слой не был изменён. |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Получает или задает, сохранять ли с отрендеренным изображением, с искажением или без него. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Получает или задает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Получает или задает [`Image`](../../aspose.psd/image/) фон [`Color`](../../aspose.psd/color/). |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Получает или задает режим восстановления данных. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Получает или задает значение, указывающее, следует ли [ignore alpha channel]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Получает или задает значение, указывающее, будет ли фиксированная ширина текстового слоя PSD игнорироваться при выполнении операции UpdateText. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Получает или задает значение, указывающее, следует ли [load effects resource] (по умолчанию ресурс не загружается). При установке этой опции будут отрисованы только поддерживаемые эффекты в окончательное объединённое изображение. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Получает или задает обработчик события прогресса. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Получает или задает значение, указывающее, следует ли [use read only mode]. Это режим только для чтения, поддерживаемый для полной совместимости с Adobe Photoshop. Когда эта опция включена, все изменения, внесённые в слои, не сохраняются в окончательное изображение. Все данные берутся из раздела ImageData, поэтому они идентичны Photoshop. По умолчанию все загруженные изображения не полностью совместимы с Adobe Photoshop. |
| [ReadOnlyType](../../aspose.psd.imageloadoptions/psdloadoptions/readonlytype/) { get; set; } | Получает или задает режим только для чтения, используемый при загрузке PSD‑изображения. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Получает или задает значение, указывающее, следует ли [use disk for load effects resource] (по умолчанию используется диск для загрузки ресурсов эффектов, но можно использовать память, если её достаточно, установив это значение в false). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Получает или задает значение, указывающее, следует ли применять преобразование ICC‑профиля. |

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

* class [LoadOptions](../../aspose.psd/loadoptions/)
* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


