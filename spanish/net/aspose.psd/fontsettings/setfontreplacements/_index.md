---
title: FontSettings.SetFontReplacements
second_title: Referencia de API de Aspose.PSD para .NET
description: FontSettings método. Establece la lista de sustitución de fuentes. Si la fuente no está permitida se buscará un reemplazo. La primera fuente de la lista se usará primero. Si también se restringió se seleccionará la siguiente fuente de la lista. Si la fuente no tiene reemplazos o no se permiten todos los reemplazos se usará la primera fuente permitida de la lista de fuentes permitidas. Si no hay fuentes permitidas y disponibles la biblioteca intente usar la fuente predeterminada del sistema incluso si no está permitida.
type: docs
weight: 110
url: /es/net/aspose.psd/fontsettings/setfontreplacements/
---
## FontSettings.SetFontReplacements method

Establece la lista de sustitución de fuentes. Si la fuente no está permitida, se buscará un reemplazo. La primera fuente de la lista se usará primero. Si también se restringió, se seleccionará la siguiente fuente de la lista. Si la fuente no tiene reemplazos o no se permiten todos los reemplazos, se usará la primera fuente permitida de la lista de fuentes permitidas. Si no hay fuentes permitidas y disponibles, la biblioteca intente usar la fuente predeterminada del sistema incluso si no está permitida.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontToReplace | String | La fuente a reemplazar. |
| fontNames | String[] | Los nombres de fuente de reemplazo en orden de similitud. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | La longitud de la matriz de fuentes y la matriz de diferencias de fuentes deben ser iguales |

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


