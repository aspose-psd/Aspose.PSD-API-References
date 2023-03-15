---
title: Enum ResizeType
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.ResizeType uppräkning. Anger storleksändringstypen.
type: docs
weight: 5370
url: /sv/net/aspose.psd/resizetype/
---
## ResizeType enumeration

Anger storleksändringstypen.

```csharp
public enum ResizeType
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Pixlarna bevaras inte under storleksändring. |
| LeftTopToLeftTop | `1` | Vänster övre punkt på den nya bilden kommer att sammanfalla med den vänstra övre punkten på originalbilden. Beskärning sker vid behov. |
| RightTopToRightTop | `2` | Höger topppunkt på den nya bilden kommer att sammanfalla med den högra övre punkten på originalbilden. Beskärning sker vid behov. |
| RightBottomToRightBottom | `3` | Höger nedre punkt på den nya bilden kommer att sammanfalla med den högra nedre punkten på originalbilden. Beskärning sker vid behov. |
| LeftBottomToLeftBottom | `4` | Nedre vänstra punkten på den nya bilden kommer att sammanfalla med den nedre vänstra punkten på originalbilden. Beskärning sker vid behov. |
| CenterToCenter | `5` | Mitten av den nya bilden kommer att sammanfalla med mitten av originalbilden. Beskärning sker vid behov. |
| LanczosResample | `6` | Sampla om med lanczos algoritm med a=3. |
| NearestNeighbourResample | `7` | Sampla om med algoritmen närmaste granne. |
| AdaptiveResample | `8` | Sampla om med adaptiv algoritm baserad på viktad och blandad rationell funktion och lanczos3 interpolationsalgoritmer. |
| BilinearResample | `9` | Sampla om med bilinjär interpolation. Bildförfiltrering tillåts för att ta bort bruset före omsampling, vid behov |
| HighQualityResample | `10` | Resample av hög kvalitet |
| CatmullRom | `11` | Catmull-Rom kubisk interpolationsmetoden. |
| CubicConvolution | `12` | Cubic Convolution-interpolationsmetoden |
| CubicBSpline | `13` | CubicBSpline kubisk interpolationsmetod |
| Mitchell | `14` | Mitchells kubiska interpolationsmetod |
| SinC | `15` | Sinc (Lanczos3) kubisk interpolationsmetod |
| Bell | `16` | Bell-interpolationsmetoden |

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

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


