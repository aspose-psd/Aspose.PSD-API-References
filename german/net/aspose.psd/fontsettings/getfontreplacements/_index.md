---
title: FontSettings.GetFontReplacements
second_title: Aspose.PSD für .NET-API-Referenz
description: FontSettings methode. Ruft das FontErsetzungsArray nach dem FontNamen ab
type: docs
weight: 50
url: /de/net/aspose.psd/fontsettings/getfontreplacements/
---
## FontSettings.GetFontReplacements method

Ruft das Font-Ersetzungs-Array nach dem Font-Namen ab

```csharp
public static string[] GetFontReplacements(string fontName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | String | Name der Schriftart. |

### Rückgabewert

Array von Namen von Ersetzungen für bereitgestellte Schriftarten

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


