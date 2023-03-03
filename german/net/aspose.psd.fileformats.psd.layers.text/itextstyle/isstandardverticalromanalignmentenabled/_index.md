---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: Aspose.PSD für .NET-API-Referenz
description: ITextStyle eigendom. Ruft die standardmäßige vertikale römische Ausrichtung ab oder legt sie fest. Dies basiert auf dem Ressourcenwert BaselineDirection und gilt nur wenn die Textausrichtung aktiviert istVertical .
type: docs
weight: 170
url: /de/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Ruft die standardmäßige vertikale römische Ausrichtung ab oder legt sie fest. Dies basiert auf dem Ressourcenwert BaselineDirection und gilt nur, wenn die Textausrichtung aktiviert istVertical .

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

### Beispiele

Der folgende Code demonstriert die Unterstützung der neuen IsStandardVerticalRomanAlignmentEnabled-Eigenschaft.

```csharp
[C#]

// Der folgende Code demonstriert die Möglichkeit, die neue Eigenschaft IsStandardVerticalRomanAlignmentEnabled zu bearbeiten.
// Dies wirkt sich im Moment nicht auf das Rendern aus, sondern ermöglicht Ihnen nur, den Eigenschaftswert zu bearbeiten.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Richtiges Lesen
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
        // Richtiges Lesen
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### Siehe auch

* interface [ITextStyle](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* Montage [Aspose.PSD](../../../)


