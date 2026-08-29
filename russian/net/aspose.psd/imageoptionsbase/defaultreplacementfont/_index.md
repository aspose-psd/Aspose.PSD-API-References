---
title: "ImageOptionsBase.DefaultReplacementFont"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство ImageOptionsBase. Получает или задает шрифт замены по умолчанию, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт слоя в файле PSD отсутствует в системе. Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily families  col.Families string defaultFontName  families0.Name PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName"
type: docs
weight: 20
url: /ru/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
{{< psd/tize >}}
## ImageOptionsBase.DefaultReplacementFont property

Получает или задает шрифт замены по умолчанию (шрифт, который будет использоваться для отрисовки текста при экспорте в растровый формат, если шрифт существующего слоя в файле PSD не присутствует в системе). Чтобы получить правильное имя шрифта по умолчанию, можно использовать следующий фрагмент кода: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### Property Value

Шрифт замены по умолчанию.

## Примеры

Следующий пример показывает, как использовать свойство DefaultReplacementFont для изменения шрифта замены по умолчанию.

```csharp
[C#]

// Пожалуйста, не устанавливайте шрифт Konstanting, потому что этот тест должен заменять шрифт, который не установлен
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions() { AllowNonChangedLayerRepaint = true }))
{
    // Таким образом, вы можете использовать разные шрифты для разных выводов.
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### См. также

* class [ImageOptionsBase](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


