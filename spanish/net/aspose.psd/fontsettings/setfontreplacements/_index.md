---
title: "FontSettings.SetFontReplacements"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "FontSettings method. Establece la lista de sustitución de fuentes. Si una fuente no está permitida, se buscará un reemplazo. La primera fuente de la lista se usará primero. Si también está restringida, se seleccionará la siguiente fuente de la lista. Si la fuente no tiene sustitutos o todos los sustitutos no están permitidos, se usará la primera fuente permitida de la lista de fuentes permitidas. Si no hay fuentes permitidas y disponibles, la biblioteca intentará usar la fuente predeterminada del sistema aunque no esté permitida."
type: docs
weight: 130
url: /es/net/aspose.psd/fontsettings/setfontreplacements/
---
{{< psd/tize >}}
## FontSettings.SetFontReplacements method

Establece la lista de sustituciones de fuentes. Si una fuente no está permitida, se buscará una sustitución. La primera fuente de la lista se usará primero. Si también está restringida, se seleccionará la siguiente fuente de la lista. Si la fuente no tiene sustituciones o todas las sustituciones no están permitidas, se usará la primera fuente permitida de la lista de fuentes permitidas. Si no hay fuentes permitidas y disponibles, la biblioteca intentará usar la fuente predeterminada del sistema aunque no esté permitida.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontToReplace | String | La fuente a reemplazar. |
| fontNames | String[] | Los nombres de fuentes de reemplazo en orden de similitud. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | La longitud de Font Array y Font Differences Array debe ser igual |

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


