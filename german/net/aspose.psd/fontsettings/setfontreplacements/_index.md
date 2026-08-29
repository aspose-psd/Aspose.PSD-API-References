---
title: "FontSettings.SetFontReplacements"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "FontSettings-Methode. Legt die Liste der Schriftart-Ersetzungen fest. Wenn eine Schriftart nicht zulässig ist, wird eine Ersatzschriftart gesucht. Die erste Schriftart in der Liste wird zuerst verwendet. Ist diese ebenfalls eingeschränkt, wird die nächste Schriftart aus der Liste ausgewählt. Wenn eine Schriftart keine Ersetzungen hat oder alle Ersetzungen nicht zulässig sind, wird die erste zulässige Schriftart aus der erlaubten Schriftartenliste verwendet. Gibt es weder zulässige noch verfügbare Schriftarten, versucht die Bibliothek, die systemweite Standardschriftart zu verwenden, selbst wenn diese nicht zulässig ist."
type: docs
weight: 130
url: /de/net/aspose.psd/fontsettings/setfontreplacements/
---
{{< psd/tize >}}
## FontSettings.SetFontReplacements method

Setzt die Liste der Schriftart-Ersetzungen. Wenn eine Schriftart nicht zulässig ist, wird eine Ersatzschriftart gefunden. Die erste Schriftart in der Liste wird zuerst verwendet. Wenn sie ebenfalls eingeschränkt ist, wird die nächste Schriftart aus der Liste ausgewählt. Hat die Schriftart keine Ersetzungen oder sind alle Ersetzungen nicht zulässig, wird die zuerst zulässige Schriftart aus der zulässigen Schriftartenliste verwendet. Gibt es keine zulässigen und verfügbaren Schriftarten, versucht die Bibliothek, die systemweite Standardschriftart zu verwenden, selbst wenn sie nicht zulässig ist.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontToReplace | String | Die zu ersetzende Schriftart. |
| fontNames | String[] | Die Ersatz‑Schriftartnamen in Reihenfolge der Ähnlichkeit. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Die Länge des Font‑Arrays und des Font‑Differenzen‑Arrays muss gleich sein. |

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


