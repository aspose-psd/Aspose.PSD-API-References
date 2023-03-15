---
title: RasterCachedImage.Resize
second_title: Aspose.PSD för .NET API-referens
description: RasterCachedImage metod. Ändrar storlek på bilden.
type: docs
weight: 120
url: /sv/net/aspose.psd/rastercachedimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Ändrar storlek på bilden.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | Int32 | Den nya bredden. |
| newHeight | Int32 | Den nya höjden. |
| resizeType | ResizeType | Ändra storlek. |

### Exempel

Följande kod visar hur man ändrar storlek på en bild med en ny SinC storleksändringstyp.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Ladda en befintlig bild i en instans av klassen PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

Följande kod visar hur man ändrar storlek på en bild med en ny storleksändringstyp.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Ladda en befintlig bild i en instans av klassen PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

Följande kod visar hur man ändrar storlek på en bild med en ny Mitchell storleksändringstyp.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Ladda en befintlig bild i en instans av klassen PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

Följande kod visar hur man ändrar storlek på en bild med en ny CatmullRom storleksändringstyp.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Ladda en befintlig bild i en instans av klassen PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Följande kod visar hur man ändrar storlek på en bild med en ny storleksändringstyp för CubicBSpline.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Ladda en befintlig bild i en instans av klassen PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Följande kod visar hur man ändrar storlek på en bild med en ny storleksändringstyp CubicConvolution.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Ladda en befintlig bild i en instans av klassen PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Se även

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* namnutrymme [Aspose.PSD](../../rastercachedimage/)
* hopsättning [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Ändrar storlek på bilden.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newWidth | Int32 | Den nya bredden. |
| newHeight | Int32 | Den nya höjden. |
| settings | ImageResizeSettings | Ändra storleksinställningar. |

### Se även

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* namnutrymme [Aspose.PSD](../../rastercachedimage/)
* hopsättning [Aspose.PSD](../../../)


