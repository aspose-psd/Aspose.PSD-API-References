---
title: Enum JustificationMode
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.JustificationMode enumeración. El modo de alineación de texto.
type: docs
weight: 1650
url: /es/net/aspose.psd.fileformats.psd/justificationmode/
---
## JustificationMode enumeration

El modo de alineación de texto.

```csharp
public enum JustificationMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Left | `0` | El texto alineado a la izquierda. |
| Right | `1` | El texto alineado a la derecha. |
| Center | `2` | El texto central. |

### Ejemplos

El siguiente código demuestra la compatibilidad con la enumeración JustificationMode para establecer la alineación del texto para las partes del texto.

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

* espacio de nombres [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* asamblea [Aspose.PSD](../../)


