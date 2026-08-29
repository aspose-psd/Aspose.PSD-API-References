---
title: "FontSettings.GetReplacementFont"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método FontSettings. Obtiene la fuente de reemplazo más adecuada. Si todos los reemplazos no están permitidos, se devolverá la primera fuente permitida y disponible. Si no hay fuentes disponibles, se devolverá la fuente del argumento."
type: docs
weight: 80
url: /es/net/aspose.psd/fontsettings/getreplacementfont/
---
{{< psd/tize >}}
## FontSettings.GetReplacementFont method

Obtiene la fuente de sustitución más adecuada. Si todas las sustituciones no están permitidas, se devolverá la primera fuente permitida y disponible. Si no hay fuentes disponibles, se devolverá la fuente del argumento.

```csharp
public static string GetReplacementFont(string fontName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | String | Nombre de la fuente. |

### Valor devuelto

El nombre de la fuente reemplazada

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


