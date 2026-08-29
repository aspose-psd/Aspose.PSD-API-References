---
title: "FontSettings.SetAllowedFonts"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "FontSettings-Methode. Beschränkt die Verwendung von Schriftarten anhand einer Schriftartenliste. Bitte prüfen Sie die tatsächlichen Schriftartnamen vor der Einschränkung. Setzen Sie die zulässige Schriftartenliste auf Null, um Einschränkungen zu entfernen."
type: docs
weight: 120
url: /de/net/aspose.psd/fontsettings/setallowedfonts/
---
{{< psd/tize >}}
## FontSettings.SetAllowedFonts method

Beschränkt die Schriftart anhand einer Schriftartenliste. Bitte prüfen Sie die tatsächlichen Schriftartnamen vor der Einschränkung. Setzen Sie die zulässige Schriftartenliste auf Null, um Einschränkungen zu entfernen.

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontList | String[] | Die Schriftartenliste. |

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


