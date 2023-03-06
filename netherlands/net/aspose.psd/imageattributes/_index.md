---
title: Class ImageAttributes
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.ImageAttributes klas. EenImageAttributes object bevat informatie over hoe bitmap en metabestandkleuren worden gemanipuleerd tijdens het renderen. EenImageAttributes object onderhoudt verschillende kleuraanpassingsinstellingen waaronder kleuraanpassingsmatrices grijswaardenaanpassingsmatrices gammacorrectiewaarden kleurenkaarttabellen en kleurdrempelwaarden. Tijdens het renderen kunnen kleuren worden gecorrigeerd verdonkerd verlicht en verwijderd. Om dergelijke manipulaties toe te passen initialiseert u eenImageAttributesbezwaar maken en het pad daarvan passerenImageAttributes object samen met het pad van eenImage  naar de DrawImagemethode.
type: docs
weight: 4610
url: /nl/net/aspose.psd/imageattributes/
---
## ImageAttributes class

Een`ImageAttributes` object bevat informatie over hoe bitmap- en metabestandkleuren worden gemanipuleerd tijdens het renderen. Een`ImageAttributes` object onderhoudt verschillende kleuraanpassingsinstellingen, waaronder kleuraanpassingsmatrices, grijswaardenaanpassingsmatrices, gammacorrectiewaarden, kleurenkaarttabellen en kleurdrempelwaarden. Tijdens het renderen kunnen kleuren worden gecorrigeerd, verdonkerd, verlicht en verwijderd. Om dergelijke manipulaties toe te passen, initialiseert u een`ImageAttributes`bezwaar maken en het pad daarvan passeren`ImageAttributes` object (samen met het pad van een[`Image`](../image/) ) naar de DrawImage-methode.

```csharp
public sealed class ImageAttributes
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [ImageAttributes](imageattributes/)() | De standaard constructeur. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Hiermee wist u de tabel voor opnieuw toewijzen van penseelkleuren`ImageAttributes` object. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Wist de kleurtoets (transparantiebereik) voor de standaardcategorie. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Wist de kleurtoets (transparantiebereik) voor een opgegeven categorie. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Wist de kleuraanpassingsmatrix voor de standaardcategorie. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Wist de kleuraanpassingsmatrix voor een opgegeven categorie. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Schakelt gammacorrectie uit voor de standaardcategorie. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Schakelt gammacorrectie uit voor een opgegeven categorie. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Wist de NoOp-instelling voor de standaardcategorie. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Wist de NoOp-instelling voor een opgegeven categorie. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Wist de instelling van het CMYK-uitvoerkanaal (cyaan-magenta-geel-zwart) voor de standaardcategorie. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Wist de (cyaan-magenta-geel-zwart) uitvoerkanaalinstelling voor een gespecificeerde categorie. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Wist de instelling van het kleurprofiel van het uitvoerkanaal voor de standaardcategorie. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Wist de kleurprofielinstelling van het uitvoerkanaal voor een opgegeven categorie. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Wist de tabel met opnieuw toewijzen van kleuren voor de standaardcategorie. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Wist de kleur-hertoewijzingstabel voor een gespecificeerde categorie. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Wist de drempelwaarde voor de standaardcategorie. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Wist de drempelwaarde voor een opgegeven categorie. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Stelt de tabel voor opnieuw toewijzen van kleuren in voor de penseelcategorie. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Stelt de kleursleutel in voor de standaardcategorie. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Stelt de kleursleutel (transparantiebereik) in voor een opgegeven categorie. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Stelt de kleuraanpassingsmatrix en de grijswaardenaanpassingsmatrix in voor de standaardcategorie. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Stelt de kleuraanpassingsmatrix en de grijswaardenaanpassingsmatrix in voor de standaardcategorie. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Stelt de kleuraanpassingsmatrix en de grijswaardenaanpassingsmatrix in voor een gespecificeerde categorie. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Stelt de kleuraanpassingsmatrix in voor de standaardcategorie. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Stelt de kleuraanpassingsmatrix in voor de standaardcategorie. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Stelt de kleuraanpassingsmatrix in voor een opgegeven categorie. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Stelt de gammawaarde in voor de standaardcategorie. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Stelt de gammawaarde in voor een gespecificeerde categorie. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Schakelt kleuraanpassing uit voor de standaardcategorie. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Schakelt kleuraanpassing uit voor een opgegeven categorie. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Stelt het CMYK-uitvoerkanaal (cyaan-magenta-geel-zwart) in voor de standaardcategorie. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Stelt het CMYK-uitvoerkanaal (cyaan-magenta-geel-zwart) in voor een opgegeven categorie. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Stelt het kleurprofielbestand van het uitvoerkanaal in voor de standaardcategorie. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Stelt het kleurprofielbestand van het uitvoerkanaal in voor een opgegeven categorie. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Stelt de tabel voor opnieuw toewijzen van kleuren in voor de standaardcategorie. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Stelt de tabel voor opnieuw toewijzen van kleuren in voor een opgegeven categorie. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Stelt de drempel (transparantiebereik) in voor de standaardcategorie. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Stelt de drempel (transparantiebereik) in voor een opgegeven categorie. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Stelt de omloopmodus in die wordt gebruikt om te beslissen hoe een textuur over een vorm of langs vormgrenzen moet worden weergegeven. Een textuur wordt betegeld over een vorm om deze op te vullen wanneer de textuur kleiner is dan de vorm die deze vult. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Stelt de omloopmodus en kleur in die worden gebruikt om te beslissen hoe een textuur over een vorm of langs vormgrenzen moet worden weergegeven. Een textuur wordt betegeld over een vorm om deze op te vullen wanneer de textuur kleiner is dan de vorm die deze vult. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Stelt de omloopmodus en kleur in die worden gebruikt om te beslissen hoe een textuur over een vorm of langs vormgrenzen moet worden weergegeven. Een textuur wordt betegeld over een vorm om deze op te vullen wanneer de textuur kleiner is dan de vorm die deze vult. |

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


