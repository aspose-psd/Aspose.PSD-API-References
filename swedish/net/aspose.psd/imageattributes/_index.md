---
title: Class ImageAttributes
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.ImageAttributes klass. AnImageAttributes objektet innehåller information om hur bitmapps och metafilfärger manipuleras under rendering. EnImageAttributes objektet har flera färgjusteringsinställningar inklusive färgjusteringsmatriser gråskalejusteringsmatriser gammakorrigeringsvärden färgkartatabeller och färgtröskelvärden. Under renderingen kan färger korrigeras mörkas ljusnas och tas bort. För att tillämpa sådana manipulationer initiera enImageAttributesobjekt och passera vägen för detImageAttributes objekt tillsammans med sökvägen för enImage  till DrawImagemetoden.
type: docs
weight: 4610
url: /sv/net/aspose.psd/imageattributes/
---
## ImageAttributes class

An`ImageAttributes` objektet innehåller information om hur bitmapps- och metafilfärger manipuleras under rendering. En`ImageAttributes` objektet har flera färgjusteringsinställningar, inklusive färgjusteringsmatriser, gråskalejusteringsmatriser, gammakorrigeringsvärden, färgkartatabeller och färgtröskelvärden. Under renderingen kan färger korrigeras, mörkas, ljusnas och tas bort. För att tillämpa sådana manipulationer, initiera en`ImageAttributes`objekt och passera vägen för det`ImageAttributes` objekt (tillsammans med sökvägen för en[`Image`](../image/) ) till DrawImage-metoden.

```csharp
public sealed class ImageAttributes
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [ImageAttributes](imageattributes/)() | Default_Constructor |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Rensar penselfärgombildningstabellen för detta`ImageAttributes` objekt. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Rensar färgnyckeln (transparensintervall) för standardkategorin. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Rensar färgnyckeln (transparensintervall) för en angiven kategori. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Rensar färgjusteringsmatrisen för standardkategorin. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Rensar färgjusteringsmatrisen för en angiven kategori. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Inaktiverar gammakorrigering för standardkategorin. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Inaktiverar gammakorrigering för en angiven kategori. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Rensar NoOp-inställningen för standardkategorin. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Rensar NoOp-inställningen för en angiven kategori. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Rensar utgångskanalinställningen för CMYK (cyan-magenta-gul-svart) för standardkategorin. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Rensar utgångskanalinställningen (cyan-magenta-gul-svart) för en angiven kategori. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Rensar utgångskanalens färgprofilinställning för standardkategorin. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Rensar utgångskanalens färgprofilinställning för en angiven kategori. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Rensar färgombildningstabellen för standardkategorin. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Rensar färgombildningstabellen för en angiven kategori. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Tar bort tröskelvärdet för standardkategorin. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Tar bort tröskelvärdet för en angiven kategori. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Ställer in färgombildningstabellen för penselkategorin. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Ställer in färgnyckeln för standardkategorin. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Ställer in färgnyckeln (transparensintervall) för en angiven kategori. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Ställer in färgjusteringsmatrisen och gråskalejusteringsmatrisen för standardkategorin. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Ställer in färgjusteringsmatrisen och gråskalejusteringsmatrisen för standardkategorin. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Ställer in färgjusteringsmatrisen och gråskalejusteringsmatrisen för en angiven kategori. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Ställer in färgjusteringsmatrisen för standardkategorin. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Ställer in färgjusteringsmatrisen för standardkategorin. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Ställer in färgjusteringsmatrisen för en angiven kategori. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Anger gammavärdet för standardkategorin. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Anger gammavärdet för en angiven kategori. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Stänger av färgjustering för standardkategorin. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Stänger av färgjustering för en angiven kategori. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Ställer in CMYK-utgångskanalen (cyan-magenta-gul-svart) för standardkategorin. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Ställer in CMYK-utgångskanalen (cyan-magenta-gul-svart) för en angiven kategori. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Ställer in utgångskanalens färgprofilfil för standardkategorin. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Ställer in utgångskanalens färgprofilfil för en angiven kategori. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Ställer in färgombildningstabellen för standardkategorin. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Ställer in färgombildningstabellen för en angiven kategori. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Ställer in tröskeln (transparensintervall) för standardkategorin. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Ställer in tröskeln (transparensintervall) för en angiven kategori. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Ställer in lindningsläget som används för att bestämma hur en textur ska kaklas över en form eller vid formgränser. En textur är sida vid sida över en form för att fylla i den när strukturen är mindre än formen den fyller. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Ställer in lindningsläget och färgen som används för att bestämma hur en textur ska kaklas över en form eller vid formgränser. En textur är sida vid sida över en form för att fylla i den när strukturen är mindre än formen den fyller. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Ställer in lindningsläget och färgen som används för att bestämma hur en textur ska kaklas över en form eller vid formgränser. En textur är sida vid sida över en form för att fylla i den när strukturen är mindre än formen den fyller. |

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


