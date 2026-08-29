---
title: "FontSettings.SetAllowedFonts"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método FontSettings. Restringe el uso de fuentes mediante una lista de fuentes. Por favor, verifique los nombres reales de las fuentes antes de la restricción. Establezca la lista de fuentes permitidas a Null para eliminar las restricciones"
type: docs
weight: 120
url: /es/net/aspose.psd/fontsettings/setallowedfonts/
---
{{< psd/tize >}}
## FontSettings.SetAllowedFonts method

Restringe el uso de fuentes mediante una lista de fuentes. Por favor, verifique los nombres reales de las fuentes antes de la restricción. Establezca la lista de fuentes permitidas a Null para eliminar las restricciones.

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontList | String[] | La lista de fuentes. |

## Ejemplos

El siguiente código demuestra la capacidad de limitar fuentes programáticamente usando.

```csharp
[C#]

string srcFile = "fonts_com_updated.psd";
string output = "etalon_fonts_com_updated.psd.png";

try
{
    var fontList = new string[] { "Courier New", "Webdings", "Bookman Old Style" };
    FontSettings.SetAllowedFonts(fontList);

    var myriadReplacement = new string[] { "Courier New", "Webdings", "Bookman Old Style" };
    var calibriReplacement = new string[] { "Webdings", "Courier New", "Bookman Old Style" };
    var arialReplacement = new string[] { "Bookman Old Style", "Courier New", "Webdings" };
    var timesReplacement = new string[] { "Arial", "NotExistedFont", "Courier New" };

    FontSettings.SetFontReplacements("MyriadPro-Regular", myriadReplacement);
    FontSettings.SetFontReplacements("Calibri", calibriReplacement);
    FontSettings.SetFontReplacements("Arial", arialReplacement);
    FontSettings.SetFontReplacements("Times New Roman", timesReplacement);

    using (PsdImage image = (PsdImage)Image.Load(srcFile,
        new PsdLoadOptions() { AllowNonChangedLayerRepaint = true }))
    {
        image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
finally
{
    FontSettings.SetAllowedFonts(null);
    FontSettings.ClearFontReplacements();
}
```

### Ver también

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


