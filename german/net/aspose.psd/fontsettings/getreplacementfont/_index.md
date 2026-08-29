---
title: "FontSettings.GetReplacementFont"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "FontSettings‑Methode. Gibt die am besten geeignete Ersatzschriftart zurück. Wenn alle Ersetzungen nicht erlaubt sind, wird die erste erlaubte und verfügbare Schriftart zurückgegeben. Gibt es keine verfügbaren Schriftarten, wird die Schriftart aus dem Argument zurückgegeben."
type: docs
weight: 80
url: /de/net/aspose.psd/fontsettings/getreplacementfont/
---
{{< psd/tize >}}
## FontSettings.GetReplacementFont method

Liefert die am besten geeignete Ersatzschriftart. Wenn alle Ersetzungen nicht zulässig sind, wird die zuerst zulässige und verfügbare Schriftart zurückgegeben. Gibt es keine verfügbaren Schriftarten, wird die Schriftart aus dem Argument zurückgegeben.

```csharp
public static string GetReplacementFont(string fontName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Name der Schriftart. |

### Rückgabewert

Der Name der ersetzten Schriftart.

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


