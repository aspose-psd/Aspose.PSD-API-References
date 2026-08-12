---
title: "Enumeración LeadingType"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.LeadingType enum. Tipo de interlineado de Photoshop, distancia entre líneas."
type: docs
weight: 4030
url: /es/net/aspose.psd.fileformats.psd/leadingtype/
---
{{< psd/tize >}}
## LeadingType enumeration

Tipo de interlineado de Photoshop (tipo de distancia entre líneas).

```csharp
public enum LeadingType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| BottomToBottom | `0` | El interlineado de abajo a abajo. |
| TopToTop | `1` | El interlineado de arriba a arriba. |

## Ejemplos

El siguiente código demuestra el soporte de los modos de interlineado de abajo a abajo y de arriba a arriba desde la configuración de Párrafo.

```csharp
[C#]

string input = "leadingMode.psd";
string output = "output_leadingMode.png";

using (var psdImage = (PsdImage)Image.Load(input, new PsdLoadOptions()))
{
    IText text1 = ((TextLayer)psdImage.Layers[1]).TextData;
    foreach (var textPortion in text1.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.TopToTop; // Change LeadingType value   
    }
    text1.Items[8].Text = "TopToTop";
    text1.Items[8].Style.FillColor = Color.ForestGreen;
    text1.UpdateLayerData();

    IText text2 = ((TextLayer)psdImage.Layers[2]).TextData;
    foreach (var textPortion in text2.Items)
    {
        textPortion.Paragraph.LeadingType = LeadingType.BottomToBottom; // Change LeadingType value   
    }
    text2.Items[8].Text = "BottomToBottom";
    text2.Items[8].Style.FillColor = Color.ForestGreen;
    text2.UpdateLayerData();

    psdImage.Save(output, new PngOptions());
}
```

### Ver también

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


