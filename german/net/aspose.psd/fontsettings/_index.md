---
title: Class FontSettings
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FontSettings klas. Allgemeine RendererSchrifteinstellungen für PSDVektorformate.
type: docs
weight: 4290
url: /de/net/aspose.psd/fontsettings/
---
## FontSettings class

Allgemeine Renderer-Schrifteinstellungen für PSD-Vektorformate.

```csharp
public static class FontSettings
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | Ruft den Standardnamen der Schriftart ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | Löscht alle Schriftarten Ersetzungen |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | Ruft den Namen der Adobe-Schriftart nach Namen der Schriftfamilie ab. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | Ruft die Standardordner für Schriftarten ab. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | Ruft das Font-Ersetzungs-Array nach dem Font-Namen ab |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Ruft eine Kopie des Arrays ab, das die Liste der Ordner enthält, in denen Aspose.Words nach TrueType-Schriftarten sucht. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | Ruft die am besten geeignete Ersatzschriftart ab. Wenn nicht alle Ersetzungen zulässig sind, wird die zuerst zulässige und verfügbare Schriftart zurückgegeben. Wenn keine verfügbaren Schriftarten vorhanden sind, wird die Schriftart von argument zurückgegeben. |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | Bestimmt, ob [die Schriftart zulässig ist] [der angegebene Schriftartname]. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | Setzt den Schriftartenordner und den Namen der Standardschriftart auf die Systemvorgabe zurück. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | Schränkt die Verwendung von Schriftarten durch eine Liste von Schriftarten ein. Bitte überprüfen Sie die Namen der echten Schriftarten, bevor |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | Legt die Schriftersetzungsliste fest. Wenn die Schriftart nicht erlaubt ist, wird ein Ersatz gesucht. Die erste Schriftart in der Liste wird zuerst verwendet. Wenn es auch eingeschränkt ist, wird die nächste Schriftart aus der Liste ausgewählt. Wenn die Schriftart keine Ersetzungen hat oder alle Ersetzungen nicht zulässig sind, wird die erste zulässige Schriftart aus der Liste der zulässigen Schriftarten verwendet. Wenn es keine zulässigen und verfügbaren Schriftarten gibt, wird die Bibliothek dies tun Versuchen Sie, die Standardschriftart des Systems zu verwenden, auch wenn dies nicht zulässig ist. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | Dies ist eine Verknüpfung zu[`SetFontsFolders`](./setfontsfolders/) zum Festlegen nur eines Schriftartenverzeichnisses. Es werden keine Prüfungen für den Schriftartenordner durchgeführt. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | Legt die Ordner fest, aus denen TrueType-Schriftarten geladen werden, und löscht alle geladenen Schriftarten. Es werden keine Überprüfungen der Schriftartenordner durchgeführt. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | Aktualisiert den Font-Cache für PSD-Dateien, die Textebenen enthalten. Diese Methode garantiert, dass Schriftarten aus dem Ordner fontsFolder using Methode FontSettings.SetFontsFolder(fontsFolder) oder nach dem Zurücksetzen von Schriftarten mit FontSettings.Reset() bei der Verarbeitung von PSD-Dateien berücksichtigt werden. Bitte verwenden Sie diese Methode jedes Mal, wenn FontSettings.SetFontsFolder(fontsFolder) oder FontSettings.Reset() für PSD-Bilder aufgerufen wird. Ohne Aufruf dieser Methode gibt es keine Garantie, dass Schriftarten aktualisiert werden. |

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


