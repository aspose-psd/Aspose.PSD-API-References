---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: Aspose.PSD for .NET API Referansı
description: ITextStyle mülk. Standart dikey Roma hizalamasını alır veya ayarlar. Bu BaselineDirection kaynak değerini temel alır yalnızca metin yönüVertical .
type: docs
weight: 170
url: /tr/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Standart dikey Roma hizalamasını alır veya ayarlar. Bu, BaselineDirection kaynak değerini temel alır, yalnızca metin yönüVertical .

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

### Örnekler

Aşağıdaki kod, yeni IsStandardVerticalRomanAlignmentEnabled özelliğinin desteğini gösterir.

```csharp
[C#]

// Aşağıdaki kod, yeni IsStandardVerticalRomanAlignmentEnabled özelliğini düzenleme yeteneğini gösterir.
// Bu, şu anda işlemeyi etkilemez, yalnızca özellik değerini düzenlemenize izin verir.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Doğru okuma
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }

    textPortion.Style.IsStandardVerticalRomanAlignmentEnabled = false;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (!textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Doğru okuma
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### Ayrıca bakınız

* interface [ITextStyle](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* toplantı [Aspose.PSD](../../../)


