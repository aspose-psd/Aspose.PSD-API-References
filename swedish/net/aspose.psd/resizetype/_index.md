---
title: "Enum ResizeType"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.ResizeType‑enum. Anger storleksändringstypen"
type: docs
weight: 5870
url: /sv/net/aspose.psd/resizetype/
---
{{< psd/tize >}}
## ResizeType enumeration

Anger typ av storleksändring.

```csharp
public enum ResizeType
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | `0` | Pixlarna bevaras inte under storleksändringsoperationen. |
| LeftTopToLeftTop | `1` | Det vänstra övre punkten i den nya bilden kommer att sammanfalla med den vänstra övre punkten i originalbilden. Beskärning sker om det behövs. |
| RightTopToRightTop | `2` | Det högra övre punkten i den nya bilden kommer att sammanfalla med den högra övre punkten i originalbilden. Beskärning sker om det behövs. |
| RightBottomToRightBottom | `3` | Det högra nedre punkten i den nya bilden kommer att sammanfalla med den högra nedre punkten i originalbilden. Beskärning sker om det behövs. |
| LeftBottomToLeftBottom | `4` | Det vänstra nedre punkten i den nya bilden kommer att sammanfalla med den vänstra nedre punkten i originalbilden. Beskärning sker om det behövs. |
| CenterToCenter | `5` | Centrum av den nya bilden kommer att sammanfalla med centrum av originalbilden. Beskärning sker om det behövs. |
| LanczosResample | `6` | Omsampla med Lanczos-algoritmen med a=3. |
| NearestNeighbourResample | `7` | Omsampla med närmaste granne-algoritmen. |
| AdaptiveResample | `8` | Omsampla med adaptiv algoritm baserad på viktad och blandad rationell funktion samt Lanczos3‑interpolationsalgoritmer. |
| BilinearResample | `9` | Omsampla med bilinjär interpolering. Bildförfiltrering är tillåten för att ta bort brus före omsamplning, vid behov. |
| HighQualityResample | `10` | Den högkvalitativa omsamplingen |
| CatmullRom | `11` | Catmull-Rom‑kubisk interpoleringsmetod. |
| CubicConvolution | `12` | Kubisk konvolutionsinterpoleringsmetod |
| CubicBSpline | `13` | CubicBSpline‑kubisk interpoleringsmetod |
| Mitchell | `14` | Mitchells kubiska interpolationsmetod |
| SinC | `15` | Sinc (Lanczos3) kubiska interpolationsmetod |
| Bell | `16` | Bell interpolationsmetod |

## Exempel

Följande kod demonstrerar hur man ändrar storlek på en bild med en ny SinC‑storleksändringstyp.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Läs in en befintlig bild i en instans av klassen PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

Följande kod demonstrerar hur man ändrar storlek på en bild med en ny Bell‑storleksändringstyp.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Läs in en befintlig bild i en instans av klassen PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

Följande kod demonstrerar hur man ändrar storlek på en bild med en ny Mitchell‑storleksändringstyp.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Läs in en befintlig bild i en instans av klassen PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

Följande kod demonstrerar hur man ändrar storlek på en bild med en ny CatmullRom‑storleksändringstyp.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Läs in en befintlig bild i en instans av klassen PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Följande kod demonstrerar hur man ändrar storlek på en bild med en ny CubicBSpline‑storleksändringstyp.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Läs in en befintlig bild i en instans av klassen PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Följande kod demonstrerar hur man ändrar storlek på en bild med en ny CubicConvolution‑storleksändringstyp.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Läs in en befintlig bild i en instans av klassen PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


