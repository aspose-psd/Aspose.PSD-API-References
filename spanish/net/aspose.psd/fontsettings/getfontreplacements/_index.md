---
title: FontSettings.GetFontReplacements
second_title: Referencia de API de Aspose.PSD para .NET
description: FontSettings método. Obtiene la matriz de reemplazos de fuente por el nombre de fuente
type: docs
weight: 50
url: /es/net/aspose.psd/fontsettings/getfontreplacements/
---
## FontSettings.GetFontReplacements method

Obtiene la matriz de reemplazos de fuente por el nombre de fuente

```csharp
public static string[] GetFontReplacements(string fontName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | Nombre de la fuente. |

### Valor_devuelto

Matriz de nombres de reemplazos para las fuentes proporcionadas

### Ejemplos

El siguiente código demuestra la capacidad de limitar mediante programación las fuentes usando.

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

    using (PsdImage image = (PsdImage)Image.Load(srcFile))
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
* espacio de nombres [Aspose.PSD](../../fontsettings/)
* asamblea [Aspose.PSD](../../../)


