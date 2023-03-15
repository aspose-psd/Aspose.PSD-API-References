---
title: Class ImageAttributes
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.ImageAttributes klas. EinImageAttributes Objekt enthält Informationen darüber wie Bitmap und Metadateifarben während des Renderns manipuliert werden. EinImageAttributes Objekt verwaltet mehrere Farbanpassungseinstellungen darunter Farbanpassungsmatrizen Graustufenanpassungsmatrizen Gammakorrekturwerte Farbabbildungstabellen und Farbschwellenwerte. Während des Renderns können Farben korrigiert abgedunkelt aufgehellt und entfernt werden. Um solche Manipulationen anzuwenden initialisieren Sie eineImageAttributesObjekt und passiere den Weg davonImageAttributes Objekt zusammen mit dem Pfad einerImage  an die DrawImageMethode.
type: docs
weight: 4610
url: /de/net/aspose.psd/imageattributes/
---
## ImageAttributes class

Ein`ImageAttributes` -Objekt enthält Informationen darüber, wie Bitmap- und Metadateifarben während des Renderns manipuliert werden. Ein`ImageAttributes` -Objekt verwaltet mehrere Farbanpassungseinstellungen, darunter Farbanpassungsmatrizen, Graustufenanpassungsmatrizen, Gammakorrekturwerte, Farbabbildungstabellen und Farbschwellenwerte. Während des Renderns können Farben korrigiert, abgedunkelt, aufgehellt und entfernt werden. Um solche Manipulationen anzuwenden, initialisieren Sie eine`ImageAttributes`Objekt und passiere den Weg davon`ImageAttributes` Objekt (zusammen mit dem Pfad einer[`Image`](../image/) ) an die DrawImage-Methode.

```csharp
public sealed class ImageAttributes
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [ImageAttributes](imageattributes/)() | Default_Constructor |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Löscht die Pinselfarben-Neuzuordnungstabelle davon`ImageAttributes` Objekt. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Löscht den Farbschlüssel (Transparenzbereich) für die Standardkategorie. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Löscht den Farbschlüssel (Transparenzbereich) für eine bestimmte Kategorie. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Löscht die Farbanpassungsmatrix für die Standardkategorie. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Löscht die Farbanpassungsmatrix für eine bestimmte Kategorie. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Deaktiviert die Gammakorrektur für die Standardkategorie. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Deaktiviert die Gammakorrektur für eine bestimmte Kategorie. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Löscht die NoOp-Einstellung für die Standardkategorie. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Löscht die NoOp-Einstellung für eine bestimmte Kategorie. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Löscht die CMYK-Ausgabekanaleinstellung (Cyan-Magenta-Gelb-Schwarz) für die Standardkategorie. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Löscht die Ausgabekanaleinstellung (Cyan-Magenta-Gelb-Schwarz) für eine bestimmte Kategorie. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Löscht die Farbprofileinstellung des Ausgangskanals für die Standardkategorie. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Löscht die Farbprofileinstellung des Ausgangskanals für eine bestimmte Kategorie. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Löscht die Farbzuordnungstabelle für die Standardkategorie. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Löscht die Farbzuordnungstabelle für eine bestimmte Kategorie. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Löscht den Schwellenwert für die Standardkategorie. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Löscht den Schwellenwert für eine bestimmte Kategorie. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Legt die Farbneuzuordnungstabelle für die Pinselkategorie fest. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Legt den Farbschlüssel für die Standardkategorie fest. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Legt den Farbschlüssel (Transparenzbereich) für eine bestimmte Kategorie fest. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Legt die Farbanpassungsmatrix und die Graustufenanpassungsmatrix für die Standardkategorie fest. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Legt die Farbanpassungsmatrix und die Graustufenanpassungsmatrix für die Standardkategorie fest. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Legt die Farbanpassungsmatrix und die Graustufenanpassungsmatrix für eine bestimmte Kategorie fest. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Legt die Farbanpassungsmatrix für die Standardkategorie fest. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Legt die Farbanpassungsmatrix für die Standardkategorie fest. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Legt die Farbanpassungsmatrix für eine bestimmte Kategorie fest. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Legt den Gammawert für die Standardkategorie fest. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Legt den Gammawert für eine bestimmte Kategorie fest. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Deaktiviert die Farbanpassung für die Standardkategorie. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Deaktiviert die Farbanpassung für eine bestimmte Kategorie. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Legt den CMYK-Ausgabekanal (Cyan-Magenta-Gelb-Schwarz) für die Standardkategorie fest. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Legt den CMYK-Ausgabekanal (Cyan-Magenta-Gelb-Schwarz) für eine bestimmte Kategorie fest. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Legt die Farbprofildatei des Ausgabekanals für die Standardkategorie fest. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Legt die Farbprofildatei des Ausgabekanals für eine bestimmte Kategorie fest. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Legt die Farbzuordnungstabelle für die Standardkategorie fest. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Legt die Farbumwandlungstabelle für eine bestimmte Kategorie fest. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Legt den Schwellenwert (Transparenzbereich) für die Standardkategorie fest. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Legt den Schwellenwert (Transparenzbereich) für eine bestimmte Kategorie fest. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Legt den Umbruchmodus fest, der verwendet wird, um zu entscheiden, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie ausfüllt. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Legt den Umbruchmodus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie ausfüllt. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Legt den Umbruchmodus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie ausfüllt. |

### Siehe auch

* namensraum [Aspose.PSD](../../aspose.psd/)
* Montage [Aspose.PSD](../../)


