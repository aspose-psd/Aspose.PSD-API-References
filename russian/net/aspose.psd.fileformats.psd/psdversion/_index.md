---
title: "Перечисление PsdVersion"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Перечисление Aspose.PSD.FileFormats.Psd.PsdVersion. Версия формата файла"
type: docs
weight: 4060
url: /ru/net/aspose.psd.fileformats.psd/psdversion/
---
{{< psd/tize >}}
## PsdVersion enumeration

Версия формата файла

```csharp
public enum PsdVersion : byte
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Psd | `1` | Версия PSD по умолчанию. |
| Psb | `2` | Версия PSB. |

## Примеры

В следующем примере показана возможность конвертировать файл PSD в PSB и обратно.

```csharp
[C#]

string sourceFilePathPsb = "2layers.psb";
string outputFilePathPsd = "ConvertFromPsb.psd";
using (Image img = Image.Load(sourceFilePathPsb))
{
    var options = new PsdOptions((PsdImage)img) { PsdVersion = PsdVersion.Psd };
    img.Save(outputFilePathPsd, options);
}

string sourceFilePathPsd = "2layers.psd";
string outputFilePathPsb = "ConvertFromPsd.psb";
using (Image img = Image.Load(sourceFilePathPsd))
{
    var options = new PsdOptions((PsdImage)img) { PsdVersion = PsdVersion.Psb };
    img.Save(outputFilePathPsb, options);
}
```

### См. также

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


