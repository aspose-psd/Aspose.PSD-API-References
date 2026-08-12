---
title: "Enum JustificationMode"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.JustificationMode enum. El modo de alineación de texto"
type: docs
weight: 1690
url: /es/net/aspose.psd.fileformats.psd/justificationmode/
---
{{< psd/tize >}}
## JustificationMode enumeration

El modo de alineación del texto.

```csharp
public enum JustificationMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Left | `0` | El texto alineado a la izquierda. En un modo de izquierda a derecha, la posición Left es Left. En un modo de derecha a izquierda, la posición Left es Right. |
| Right | `1` | El texto alineado a la derecha. En un modo de izquierda a derecha, la posición Right es Right. En un modo de derecha a izquierda, la posición Right es Left. |
| Center | `2` | El texto centrado. |

## Ejemplos

El siguiente código demuestra el soporte del enum JustificationMode para establecer la alineación de texto en porciones de texto.

```csharp
[C#]

string src = "source1107.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (var image = (PsdImage) Image.Load(src))
{
    var txtLayer = image.AddTextLayer("Text line1\rText line2\rText line3",
        new Rectangle(200, 200, 500, 500));
    var portions = txtLayer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Left;
    portions[1].Paragraph.Justification = JustificationMode.Right;
    portions[2].Paragraph.Justification = JustificationMode.Center;

    foreach (var portion in portions)
    {
        portion.Style.FontSize = 24;
    }

    txtLayer.TextData.UpdateLayerData();

    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Ver también

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


