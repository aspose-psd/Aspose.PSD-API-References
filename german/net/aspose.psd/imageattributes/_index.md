---
title: "Klasse ImageAttributes"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.ImageAttributes-Klasse. Ein ImageAttributes-Objekt enthält Informationen darüber, wie Bitmap- und Metafile-Farben während des Renderns manipuliert werden. Ein ImageAttributes-Objekt verwaltet mehrere Farbkorrektureinstellungen, einschließlich Farbkorrektur-Matrizen, Graustufen-Matrizen, Gamma-Korrekturwerte, Farbkartentabellen und Farbschwellenwerte. Beim Rendern können Farben korrigiert, abgedunkelt, aufgehellt und entfernt werden. Um solche Manipulationen anzuwenden, initialisieren Sie ein ImageAttributes-Objekt und übergeben den Pfad dieses ImageAttributes-Objekts zusammen mit dem Pfad eines Image an die DrawImage-Methode."
type: docs
weight: 5080
url: /de/net/aspose.psd/imageattributes/
---
{{< psd/tize >}}
## ImageAttributes class

Ein `ImageAttributes`-Objekt enthält Informationen darüber, wie Bitmap- und Metafile-Farben während des Renderns manipuliert werden. Ein `ImageAttributes`-Objekt verwaltet mehrere Farbkorrektureinstellungen, einschließlich Farbkorrektur-Matrizen, Graustufen-Matrizen, Gamma-Korrekturwerte, Farbkartentabellen und Farbschwellenwerte. Beim Rendern können Farben korrigiert, abgedunkelt, aufgehellt und entfernt werden. Um solche Manipulationen anzuwenden, initialisieren Sie ein `ImageAttributes`-Objekt und übergeben den Pfad dieses `ImageAttributes`-Objekts (zusammen mit dem Pfad eines [`Image`](../image/)) an die DrawImage-Methode.

```csharp
public sealed class ImageAttributes
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ImageAttributes](imageattributes/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Löscht die Farb-Remap-Tabelle des Pinsels dieses `ImageAttributes`-Objekts. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Löscht den Farbenschlüssel (Transparenzbereich) für die Standardkategorie. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Löscht den Farbschlüssel (Transparenzbereich) für eine angegebene Kategorie. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Löscht die Farbkorrekturmatrix für die Standardkategorie. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Löscht die Farbkorrekturmatrix für eine angegebene Kategorie. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Deaktiviert die Gammakorrektur für die Standardkategorie. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Deaktiviert die Gammakorrektur für eine angegebene Kategorie. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Löscht die NoOp-Einstellung für die Standardkategorie. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Löscht die NoOp-Einstellung für eine angegebene Kategorie. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Löscht die CMYK (Cyan-Magenta-Gelb-Schwarz) Ausgabekanal-Einstellung für die Standardkategorie. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Löscht die (Cyan-Magenta-Gelb-Schwarz) Ausgabekanal-Einstellung für eine angegebene Kategorie. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Löscht die Farbprofil-Einstellung des Ausgabekanals für die Standardkategorie. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Löscht die Farbprofil-Einstellung des Ausgabekanals für eine angegebene Kategorie. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Löscht die Farb-Remap-Tabelle für die Standardkategorie. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Löscht die Farb-Remap-Tabelle für eine angegebene Kategorie. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Löscht den Schwellenwert für die Standardkategorie. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Löscht den Schwellenwert für eine angegebene Kategorie. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Setzt die Farb-Remap-Tabelle für die Pinselkategorie. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Setzt den Farbschlüssel für die Standardkategorie. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Setzt den Farbschlüssel (Transparenzbereich) für eine angegebene Kategorie. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Setzt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für die Standardkategorie. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Setzt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für die Standardkategorie. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Setzt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für eine angegebene Kategorie. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Setzt die Farbkorrekturmatrix für die Standardkategorie. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Setzt die Farbkorrekturmatrix für die Standardkategorie. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Setzt die Farbkorrekturmatrix für eine angegebene Kategorie. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Setzt den Gammawert für die Standardkategorie. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Setzt den Gammawert für eine angegebene Kategorie. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Schaltet die Farbkorrektur für die Standardkategorie aus. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Deaktiviert die Farbanpassung für eine bestimmte Kategorie. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Legt den CMYK (cyan-magenta-yellow-black) Ausgabekanal für die Standardkategorie fest. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Legt den CMYK (cyan-magenta-yellow-black) Ausgabekanal für eine bestimmte Kategorie fest. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Legt die Farbprofildatei des Ausgabekanals für die Standardkategorie fest. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Legt die Farbprofildatei des Ausgabekanals für eine bestimmte Kategorie fest. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Legt die Farb-Remap-Tabelle für die Standardkategorie fest. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Legt die Farb-Remap-Tabelle für eine bestimmte Kategorie fest. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Legt den Schwellenwert (Transparenzbereich) für die Standardkategorie fest. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Legt den Schwellenwert (Transparenzbereich) für eine bestimmte Kategorie fest. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Legt den Wrap-Modus fest, der verwendet wird, um zu entscheiden, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie zu füllen, wenn die Textur kleiner ist als die zu füllende Form. |

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


