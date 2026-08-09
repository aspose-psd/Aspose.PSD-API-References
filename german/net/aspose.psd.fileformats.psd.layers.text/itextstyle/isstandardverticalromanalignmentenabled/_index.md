---
title: "ITextStyle.IsStandardVerticalRomanAlignmentEnabled"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ITextStyle-Eigenschaft. Gibt den Standard‑Vertikal‑Roman‑Ausrichtung zurück oder legt ihn fest. Dieser, basierend auf dem BaselineDirection‑Ressourcenwert, gilt nur, wenn die Textausrichtung Vertikal ist."
type: docs
weight: 170
url: /de/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
{{< psd/tize >}}
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Liest oder setzt die standardmäßige vertikale römische Ausrichtung. Dieser, basierend auf dem BaselineDirection-Ressourcenwert, gilt nur, wenn die Textausrichtung vertikal ist.

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

## Beispiele

Der folgende Code demonstriert die Unterstützung der neuen IsStandardVerticalRomanAlignmentEnabled‑Eigenschaft.

```csharp
[C#]

// Der folgende Code demonstriert die Möglichkeit, die neue IsStandardVerticalRomanAlignmentEnabled‑Eigenschaft zu bearbeiten.
// Dies wirkt sich im Moment nicht auf das Rendern aus, ermöglicht jedoch nur das Bearbeiten des Eigenschaftswerts.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Korrektes Lesen
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
        // Korrektes Lesen
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### Siehe auch

* interface [ITextStyle](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Text](../../../aspose.psd.fileformats.psd.layers.text/)
* assembly [Aspose.PSD](../../../)


