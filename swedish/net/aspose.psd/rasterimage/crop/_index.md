---
title: RasterImage.Crop
second_title: Aspose.PSD för .NET API-referens
description: RasterImage metod. Beskär den angivna rektangeln.
type: docs
weight: 240
url: /sv/net/aspose.psd/rasterimage/crop/
---
## Crop(Rectangle) {#crop}

Beskär den angivna rektangeln.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | Rectangle | Rektangeln. |

### Exempel

Följande kodexempel visar hur man beskär en bild och sparar den.

```csharp
[C#]

// Implementera korrekt beskärningsmetod för PSD-filer.
string sourceFileName = "1.psd";
string exportPathPsd = "CropTest.psd";
string exportPathPng = "CropTest.png";
using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Crop(new Rectangle(10, 30, 100, 100));
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Se även

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namnutrymme [Aspose.PSD](../../rasterimage/)
* hopsättning [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Beskär bilden med skiftningar.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| leftShift | Int32 | Vänsterskiftet. |
| rightShift | Int32 | Rätt skift. |
| topShift | Int32 | Det översta skiftet. |
| bottomShift | Int32 | Bottenskiftet. |

### Se även

* class [RasterImage](../)
* namnutrymme [Aspose.PSD](../../rasterimage/)
* hopsättning [Aspose.PSD](../../../)


