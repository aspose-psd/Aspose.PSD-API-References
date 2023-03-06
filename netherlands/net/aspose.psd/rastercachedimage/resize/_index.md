---
title: RasterCachedImage.Resize
second_title: Aspose.PSD voor .NET API-referentie
description: RasterCachedImage methode. Pas de grootte van de afbeelding aan.
type: docs
weight: 120
url: /nl/net/aspose.psd/rastercachedimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Pas de grootte van de afbeelding aan.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | Int32 | De nieuwe breedte. |
| newHeight | Int32 | De nieuwe hoogte. |
| resizeType | ResizeType | Het type formaat wijzigen. |

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

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* naamruimte [Aspose.PSD](../../rastercachedimage/)
* montage [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Pas de grootte van de afbeelding aan.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newWidth | Int32 | De nieuwe breedte. |
| newHeight | Int32 | De nieuwe hoogte. |
| settings | ImageResizeSettings | De instellingen voor formaat wijzigen. |

### Zie ook

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* naamruimte [Aspose.PSD](../../rastercachedimage/)
* montage [Aspose.PSD](../../../)


