---
title: "ITextStyle.IsStandardVerticalRomanAlignmentEnabled"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ITextStyle özelliği. Standart dikey Roma hizalamasını alır veya ayarlar. Bu, BaselineDirection kaynağı değerine dayanır ve yalnızca metin yönelimi Dikey olduğunda uygulanır"
type: docs
weight: 170
url: /tr/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
{{< psd/tize >}}
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Standart dikey Roman hizalamasını alır veya ayarlar. Bu, BaselineDirection kaynak değerine dayanır ve yalnızca metin yönelimi Dikey olduğunda uygulanır.

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

## Örnekler

Aşağıdaki kod, yeni IsStandardVerticalRomanAlignmentEnabled özelliğinin desteğini gösterir.

```csharp
[C#]

// Aşağıdaki kod, yeni IsStandardVerticalRomanAlignmentEnabled özelliğini düzenleme yeteneğini gösterir.
// Bu şu anda renderlemeyi etkilemez, ancak yalnızca özelliğin değerini düzenlemenize izin verir.

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

### Ayrıca Bakınız

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


