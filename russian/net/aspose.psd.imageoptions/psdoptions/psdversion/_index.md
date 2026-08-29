---
title: "PsdOptions.PsdVersion"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство PsdOptions. Получает или задает версию формата файла. Может быть PSD или PSB."
type: docs
weight: 70
url: /ru/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
{{< psd/tize >}}
## PsdOptions.PsdVersion property

Получает или задает версию формата файла. Это может быть PSD или PSB.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Property Value

Версия формата файла.

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

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


