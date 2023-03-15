---
title: Enum ResizeType
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.ResizeType opsomming. Specificeert het type formaat wijzigen.
type: docs
weight: 5370
url: /nl/net/aspose.psd/resizetype/
---
## ResizeType enumeration

Specificeert het type formaat wijzigen.

```csharp
public enum ResizeType
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | `0` | De pixels blijven niet behouden tijdens het wijzigen van de grootte. |
| LeftTopToLeftTop | `1` | Linkerbovenpunt van de nieuwe afbeelding valt samen met het linkerbovenpunt van de originele afbeelding. Bijsnijden zal plaatsvinden indien nodig. |
| RightTopToRightTop | `2` | Het rechterbovenpunt van de nieuwe afbeelding valt samen met het rechterbovenpunt van de originele afbeelding. Bijsnijden zal plaatsvinden indien nodig. |
| RightBottomToRightBottom | `3` | Het rechteronderpunt van de nieuwe afbeelding valt samen met het rechteronderpunt van de originele afbeelding. Bijsnijden zal plaatsvinden indien nodig. |
| LeftBottomToLeftBottom | `4` | Linkeronderpunt van de nieuwe afbeelding valt samen met het linkeronderpunt van de originele afbeelding. Bijsnijden zal plaatsvinden indien nodig. |
| CenterToCenter | `5` | Het midden van de nieuwe afbeelding valt samen met het midden van de originele afbeelding. Bijsnijden zal plaatsvinden indien nodig. |
| LanczosResample | `6` | Resample met behulp van het lanczos-algoritme met a=3. |
| NearestNeighbourResample | `7` | Resample met algoritme voor dichtstbijzijnde buur. |
| AdaptiveResample | `8` | Resample met behulp van een adaptief algoritme op basis van gewogen en gemengde rationale functies en lanczos3-interpolatie-algoritmen. |
| BilinearResample | `9` | Opnieuw samplen met behulp van bilineaire interpolatie. Voorfiltering van afbeeldingen is toegestaan om de ruis te verwijderen voordat opnieuw wordt gesampled, indien nodig |
| HighQualityResample | `10` | De hoge kwaliteit resample |
| CatmullRom | `11` | De Catmull-Rom kubieke interpolatiemethode. |
| CubicConvolution | `12` | De kubieke convolutie-interpolatiemethode |
| CubicBSpline | `13` | De CubicBSpline kubieke interpolatiemethode |
| Mitchell | `14` | De Mitchell kubische interpolatiemethode |
| SinC | `15` | De Sinc (Lanczos3) kubische interpolatiemethode |
| Bell | `16` | De Bell-interpolatiemethode |

### Voorbeelden

De volgende code laat zien hoe u het formaat van een afbeelding kunt wijzigen met een nieuw SinC-type voor formaatwijziging.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Laad een bestaande afbeelding in een instantie van de PsdImage-klasse
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

De volgende code laat zien hoe u het formaat van een afbeelding kunt wijzigen met een nieuw type Bell-formaat.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Laad een bestaande afbeelding in een instantie van de PsdImage-klasse
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

De volgende code laat zien hoe u het formaat van een afbeelding kunt wijzigen met een nieuw type voor formaatwijziging van Mitchell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Laad een bestaande afbeelding in een instantie van de PsdImage-klasse
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

De volgende code laat zien hoe u het formaat van een afbeelding kunt wijzigen met een nieuw formaattype voor CatmullRom.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Laad een bestaande afbeelding in een instantie van de PsdImage-klasse
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

De volgende code laat zien hoe u het formaat van een afbeelding kunt wijzigen met een nieuw formaatwijzigingstype CubicBSpline.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Laad een bestaande afbeelding in een instantie van de PsdImage-klasse
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

De volgende code laat zien hoe u het formaat van een afbeelding kunt wijzigen met een nieuw wijzigingstype CubicConvolution.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Laad een bestaande afbeelding in een instantie van de PsdImage-klasse
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


