---
title: "FontSettings.RemoveFontCacheFile"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод FontSettings. Удаляет файл кэша шрифтов"
type: docs
weight: 100
url: /ru/net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

Удаляет файл кэша шрифтов.

```csharp
public static void RemoveFontCacheFile()
```

## Примеры

Следующий код демонстрирует метод удаления файла кэша загруженных шрифтов.

```csharp
[C#]

string src = "SimpleText.psd";

FontSettings.RemoveFontCacheFile();

using (var psdImage = (PsdImage)Image.Load(src))
{
    foreach (var layer in psdImage.Layers)
    {
        if (layer is TextLayer textLayer)
        {
            textLayer.GetFonts();
        }
    }
}
```

### См. также

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


