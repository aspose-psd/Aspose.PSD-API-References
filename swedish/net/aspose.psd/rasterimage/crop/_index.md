---
title: "RasterImage.Crop"
second_title: "Aspose.PSD för .NET API‑referens"
description: "RasterImage-metoden. Beskär den angivna rektangeln."
type: docs
weight: 240
url: /sv/net/aspose.psd/rasterimage/crop/
---
{{< psd/tize >}}
## Crop(Rectangle) {#crop}

Beskär den angivna rektangeln.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rektangel | Rectangle | Rektangeln. |

## Exempel

Följande kodexempel visar hur man beskär en bild och sparar den.

```csharp
[C#]

// Implementera korrekt Crop‑metod för PSD‑filer.
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
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Beskär bild med förskjutningar.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| leftShift | Int32 | Vänsterskiftet. |
| rightShift | Int32 | Högerskiftet. |
| topShift | Int32 | Toppskiftet. |
| bottomShift | Int32 | Bottneskiftet. |

### Se även

* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


