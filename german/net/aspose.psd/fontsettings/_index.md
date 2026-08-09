---
title: "Class FontSettings"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.FontSettings-Klasse. Allgemeine Schriftarteinstellungen für den Renderer von PSD-Vektorformaten."
type: docs
weight: 4760
url: /de/net/aspose.psd/fontsettings/
---
{{< psd/tize >}}
## FontSettings class

Allgemeine Schriftarteinstellungen des Renderers für PSD-Vektorformate.

```csharp
public static class FontSettings
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Liest oder setzt den Standardnamen der Schriftart. |
| static [GetSystemAlternativeFont](../../aspose.psd/fontsettings/getsystemalternativefont/) { get; set; } | Liest oder setzt einen Wert, der angibt, ob [get alternative font]. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Löscht alle Schriftart-Ersetzungen. |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Liefert den Adobe-Schriftartnamen anhand des Schriftfamiliennamens. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Liefert die Standard-Schriftartenordner. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Liefert das Array der Schriftart-Ersetzungen anhand des Schriftartnamens |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Gibt eine Kopie des Arrays zurück, das die Liste der Ordner enthält, in denen Aspose.Words nach TrueType-Schriftarten sucht. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Liefert die am besten geeignete Ersatzschriftart. Wenn alle Ersetzungen nicht zulässig sind, wird die zuerst zulässige und verfügbare Schriftart zurückgegeben. Gibt es keine verfügbaren Schriftarten, wird die Schriftart aus dem Argument zurückgegeben. |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Bestimmt, ob [die Schriftart erlaubt] [der angegebene Schriftartname] ist. |
| static [RemoveFontCacheFile](../../aspose.psd/fontsettings/removefontcachefile/)() | Entfernt die Schriftarten-Cache-Datei. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Setzt den Schriftartenordner und den Standard-Schriftartnamen auf die Systemvorgabe zurück. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Beschränkt die Schriftart anhand einer Schriftartenliste. Bitte prüfen Sie die tatsächlichen Schriftartnamen vor der Einschränkung. Setzen Sie die zulässige Schriftartenliste auf Null, um Einschränkungen zu entfernen. |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Setzt die Liste der Schriftart-Ersetzungen. Wenn eine Schriftart nicht zulässig ist, wird eine Ersatzschriftart gefunden. Die erste Schriftart in der Liste wird zuerst verwendet. Wenn sie ebenfalls eingeschränkt ist, wird die nächste Schriftart aus der Liste ausgewählt. Hat die Schriftart keine Ersetzungen oder sind alle Ersetzungen nicht zulässig, wird die zuerst zulässige Schriftart aus der zulässigen Schriftartenliste verwendet. Gibt es keine zulässigen und verfügbaren Schriftarten, versucht die Bibliothek, die systemweite Standardschriftart zu verwenden, selbst wenn sie nicht zulässig ist. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Dies ist eine Abkürzung zu [`SetFontsFolders`](./setfontsfolders/) zum Festlegen eines einzigen Schriftartenverzeichnisses. Es werden keine Prüfungen des Schriftartenordners durchgeführt. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Legt die Ordner fest, aus denen TrueType-Schriftarten geladen werden, und löscht alle geladenen Schriftarten. Es werden keine Prüfungen der Schriftartenordner durchgeführt. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Aktualisiert den Schriftarten-Cache für PSD-Dateien, die Textebenen enthalten. Diese Methode stellt sicher, dass Schriftarten aus dem Ordner fontsFolder, die über die Methode FontSettings.SetFontsFolder(fontsFolder) oder nach einem Zurücksetzen der Schriftarten mittels FontSettings.Reset() festgelegt wurden, bei der Verarbeitung von PSD-Dateien berücksichtigt werden. Bitte verwenden Sie diese Methode jedes Mal, wenn FontSettings.SetFontsFolder(fontsFolder) oder FontSettings.Reset() für PSD-Bilder aufgerufen wird. Ohne Aufruf dieser Methode gibt es keine Garantie, dass die Schriftarten aktualisiert werden. |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


