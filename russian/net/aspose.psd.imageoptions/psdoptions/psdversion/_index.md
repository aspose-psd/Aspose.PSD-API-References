---
title: PsdOptions.PsdVersion
second_title: Справочник по Aspose.PSD для .NET API
description: PsdOptions свойство. Получает или задает версию формата файла. Это может быть PSD или PSB.
type: docs
weight: 60
url: /ru/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
## PsdOptions.PsdVersion property

Получает или задает версию формата файла. Это может быть PSD или PSB.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Стоимость имущества

Версия формата файла.

### Примеры

В следующем примере показана возможность преобразования файла PSD в файл PSB и наоборот.

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

### Смотрите также

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* пространство имен [Aspose.PSD.ImageOptions](../../psdoptions/)
* сборка [Aspose.PSD](../../../)


