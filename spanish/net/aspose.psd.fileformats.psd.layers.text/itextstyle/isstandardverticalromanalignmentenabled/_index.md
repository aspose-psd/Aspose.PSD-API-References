---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: Referencia de API de Aspose.PSD para .NET
description: ITextStyle propiedad. Obtiene o establece la alineación romana vertical estándar. Esto basado en el valor del recurso BaselineDirection solo se aplica cuando la orientación del texto esVertical .
type: docs
weight: 170
url: /es/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Obtiene o establece la alineación romana vertical estándar. Esto, basado en el valor del recurso BaselineDirection, solo se aplica cuando la orientación del texto esVertical .

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

### Ejemplos

El siguiente código demuestra la compatibilidad con la nueva propiedad IsStandardVerticalRomanAlignmentEnabled.

```csharp
[C#]

// El siguiente código demuestra la capacidad de editar la nueva propiedad IsStandardVerticalRomanAlignmentEnabled.
// Esto no afecta el renderizado por el momento, pero solo le permite editar el valor de la propiedad.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Lectura correcta
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
        // Lectura correcta
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### Ver también

* interface [ITextStyle](../)
* espacio de nombres [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* asamblea [Aspose.PSD](../../../)


