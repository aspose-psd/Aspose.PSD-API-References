---
title: FontSettings.SetFontReplacements
second_title: Aspose.PSD für .NET-API-Referenz
description: FontSettings methode. Legt die Schriftersetzungsliste fest. Wenn die Schriftart nicht erlaubt ist wird ein Ersatz gesucht. Die erste Schriftart in der Liste wird zuerst verwendet. Wenn es auch eingeschränkt ist wird die nächste Schriftart aus der Liste ausgewählt. Wenn die Schriftart keine Ersetzungen hat oder alle Ersetzungen nicht zulässig sind wird die erste zulässige Schriftart aus der Liste der zulässigen Schriftarten verwendet. Wenn es keine zulässigen und verfügbaren Schriftarten gibt wird die Bibliothek dies tun Versuchen Sie die Standardschriftart des Systems zu verwenden auch wenn dies nicht zulässig ist.
type: docs
weight: 110
url: /de/net/aspose.psd/fontsettings/setfontreplacements/
---
## FontSettings.SetFontReplacements method

Legt die Schriftersetzungsliste fest. Wenn die Schriftart nicht erlaubt ist, wird ein Ersatz gesucht. Die erste Schriftart in der Liste wird zuerst verwendet. Wenn es auch eingeschränkt ist, wird die nächste Schriftart aus der Liste ausgewählt. Wenn die Schriftart keine Ersetzungen hat oder alle Ersetzungen nicht zulässig sind, wird die erste zulässige Schriftart aus der Liste der zulässigen Schriftarten verwendet. Wenn es keine zulässigen und verfügbaren Schriftarten gibt, wird die Bibliothek dies tun Versuchen Sie, die Standardschriftart des Systems zu verwenden, auch wenn dies nicht zulässig ist.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontToReplace | String | Die zu ersetzende Schriftart. |
| fontNames | String[] | Die Namen der Ersatzschriftarten in der Reihenfolge ihrer Ähnlichkeit. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Die Länge des Font-Arrays und des Font-Unterschiede-Arrays muss gleich sein |

### Beispiele

Der folgende Code demonstriert die Möglichkeit, die Verwendung von Schriftarten programmgesteuert einzuschränken.

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

### Siehe auch

* class [FontSettings](../)
* namensraum [Aspose.PSD](../../fontsettings/)
* Montage [Aspose.PSD](../../../)


