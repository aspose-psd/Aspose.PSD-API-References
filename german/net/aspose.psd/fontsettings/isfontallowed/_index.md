---
title: "FontSettings.IsFontAllowed"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "FontSettings-Methode. Bestimmt, ob die angegebene Schriftart zulässig ist."
type: docs
weight: 90
url: /de/net/aspose.psd/fontsettings/isfontallowed/
---
{{< psd/tize >}}
## FontSettings.IsFontAllowed method

Bestimmt, ob [die Schriftart erlaubt] [der angegebene Schriftartname] ist.

```csharp
public static bool IsFontAllowed(string fontName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Name der Schriftart. |

### Rückgabewert

`true` wenn [is font allowed] [the specified font name]; andernfalls `false`.

## Beispiele

Der folgende Code demonstriert die Möglichkeit, Schriftarten programmgesteuert zu begrenzen.

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

### Siehe auch

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


