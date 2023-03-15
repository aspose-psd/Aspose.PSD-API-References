---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: Aspose.PSD per riferimento API .NET
description: ITextStyle proprietà. Ottiene o imposta lallineamento romano verticale standard. Basato sul valore della risorsa BaselineDirection si applica solo quando lorientamento del testo èVertical .
type: docs
weight: 170
url: /it/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Ottiene o imposta l'allineamento romano verticale standard. Basato sul valore della risorsa BaselineDirection, si applica solo quando l'orientamento del testo èVertical .

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

### Esempi

Il codice seguente illustra il supporto della nuova proprietà IsStandardVerticalRomanAlignmentEnabled.

```csharp
[C#]

// Il codice seguente dimostra la possibilità di modificare la nuova proprietà IsStandardVerticalRomanAlignmentEnabled.
// Questo non influisce sul rendering al momento, ma consente solo di modificare il valore della proprietà.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Lettura corretta
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
        // Lettura corretta
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### Guarda anche

* interface [ITextStyle](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* assemblea [Aspose.PSD](../../../)


