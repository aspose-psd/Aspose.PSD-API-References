---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: Aspose.PSD voor .NET API-referentie
description: ITextStyle eigendom. Hiermee wordt de standaard verticale Romeinse uitlijning opgehaald of ingesteld. Dit op basis van de bronwaarde BaselineDirection is alleen van toepassing wanneer de tekstoriëntatieVertical .
type: docs
weight: 170
url: /nl/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Hiermee wordt de standaard verticale Romeinse uitlijning opgehaald of ingesteld. Dit op basis van de bronwaarde BaselineDirection is alleen van toepassing wanneer de tekstoriëntatieVertical .

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

### Voorbeelden

De volgende code demonstreert de ondersteuning van de nieuwe eigenschap IsStandardVerticalRomanAlignmentEnabled.

```csharp
[C#]

// De volgende code demonstreert de mogelijkheid om de nieuwe eigenschap IsStandardVerticalRomanAlignmentEnabled te bewerken.
// Dit heeft op dit moment geen invloed op de weergave, maar u kunt alleen de eigenschapswaarde bewerken.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Correct lezen
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
        // Correct lezen
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### Zie ook

* interface [ITextStyle](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* montage [Aspose.PSD](../../../)


