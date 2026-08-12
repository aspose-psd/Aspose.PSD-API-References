---
title: "Klass ImageAttributes"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.ImageAttributes class. Ett ImageAttributes-objekt innehåller information om hur bitmap- och metafilfärger manipuleras under rendering. Ett ImageAttributes-objekt upprätthåller flera coloradjustment-inställningar, inklusive coloradjustment-matriser, grayscaleadjustment-matriser, gammacorrection-värden, colormap-tabeller och colorthreshold-värden. Under rendering kan färger korrigeras, mörkras, ljusas upp och tas bort. För att tillämpa sådana manipulationer, initiera ett ImageAttributes-objekt och skicka sökvägen till det ImageAttributes-objektet tillsammans med sökvägen till en Image till DrawImage-metoden."
type: docs
weight: 5080
url: /sv/net/aspose.psd/imageattributes/
---
{{< psd/tize >}}
## ImageAttributes class

Ett `ImageAttributes`-objekt innehåller information om hur bitmap- och metafilfärger manipuleras under rendering. Ett `ImageAttributes`-objekt upprätthåller flera color-adjustment-inställningar, inklusive color-adjustment-matriser, grayscale-adjustment-matriser, gamma-correction-värden, color-map-tabeller och color-threshold-värden. Under rendering kan färger korrigeras, mörkras, ljusas upp och tas bort. För att tillämpa sådana manipulationer, initiera ett `ImageAttributes`-objekt och skicka sökvägen till det `ImageAttributes`-objektet (tillsammans med sökvägen till en [`Image`](../image/)) till DrawImage-metoden.

```csharp
public sealed class ImageAttributes
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [ImageAttributes](imageattributes/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | Rensar brush color-remap-tabellen för detta `ImageAttributes`-objekt. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | Rensar färgnyckeln (transparensintervall) för standardkategorin. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | Rensar färgnyckeln (transparensintervall) för en specificerad kategori. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | Rensar color-adjustment-matrisen för standardkategorin. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | Rensar color-adjustment-matrisen för en specificerad kategori. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | Inaktiverar gamma correction för standardkategorin. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | Inaktiverar gamma correction för en specificerad kategori. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | Rensar NoOp‑inställningen för standardkategorin. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | Rensar NoOp‑inställningen för en specificerad kategori. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | Rensar CMYK (cyan-magenta-yellow-black) utkanalinställningen för standardkategorin. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | Rensar (cyan-magenta-yellow-black) utkanalinställningen för en specificerad kategori. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | Rensar färgprofilinställningen för utkanalen för standardkategorin. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Rensar färgprofilinställningen för utkanalen för en specificerad kategori. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | Rensar färg-omkartläggningstabellen för standardkategorin. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | Rensar färg-omkartläggningstabellen för en specificerad kategori. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | Rensar tröskelvärdet för standardkategorin. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | Rensar tröskelvärdet för en specificerad kategori. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | Ställer in färg-omkartläggningstabellen för penselkategorin. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | Ställer in färgnyckeln för standardkategorin. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | Ställer in färgnyckeln (transparentintervall) för en specificerad kategori. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för standardkategorin. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för standardkategorin. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Ställer in färgjusteringsmatrisen och gråskalajusteringsmatrisen för en specificerad kategori. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | Ställer in färgjusteringsmatrisen för standardkategorin. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Ställer in färgjusteringsmatrisen för standardkategorin. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Ställer in färgjusteringsmatrisen för en specificerad kategori. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | Ställer in gammavärdet för standardkategorin. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | Ställer in gammavärdet för en specificerad kategori. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | Stänger av färgjustering för standardkategorin. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | Stänger av färgjustering för en specificerad kategori. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | Ställer in CMYK (cyan-magenta-yellow-black) utkanalen för standardkategorin. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Ställer in CMYK (cyan-magenta-yellow-black) utkanalen för en specificerad kategori. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | Ställer in färgprofilfilen för utkanalen för standardkategorin. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Ställer in färgprofilfilen för utkanalen för en specificerad kategori. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | Ställer in färg-omkartläggningstabellen för standardkategorin. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | Ställer in färg-omkartläggningstabellen för en angiven kategori. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | Ställer in tröskelvärdet (transparentintervall) för standardkategorin. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | Ställer in tröskelvärdet (transparentintervall) för en angiven kategori. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | Ställer in wrap-läget som används för att bestämma hur en textur ska tileas över en form, eller vid formens gränser. En textur tileas över en form för att fylla den när texturen är mindre än formen den fyller. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | Ställer in wrap-läget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formens gränser. En textur tileas över en form för att fylla den när texturen är mindre än formen den fyller. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | Ställer in wrap-läget och färgen som används för att bestämma hur en textur ska tileas över en form, eller vid formens gränser. En textur tileas över en form för att fylla den när texturen är mindre än formen den fyller. |

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


