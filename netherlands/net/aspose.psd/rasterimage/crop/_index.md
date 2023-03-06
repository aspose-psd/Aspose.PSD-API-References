---
title: RasterImage.Crop
second_title: Aspose.PSD voor .NET API-referentie
description: RasterImage methode. Snijdt de opgegeven rechthoek bij.
type: docs
weight: 240
url: /nl/net/aspose.psd/rasterimage/crop/
---
## Crop(Rectangle) {#crop}

Snijdt de opgegeven rechthoek bij.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rectangle | Rectangle | De rechthoek. |

### Voorbeelden

Het volgende codevoorbeeld laat zien hoe u een afbeelding bijsnijdt en opslaat.

```csharp
[C#]

// Implementeer de juiste Crop-methode voor PSD-bestanden.
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

### Zie ook

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* naamruimte [Aspose.PSD](../../rasterimage/)
* montage [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Afbeelding bijsnijden met verschuivingen.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| leftShift | Int32 | De linkse verschuiving. |
| rightShift | Int32 | De juiste verschuiving. |
| topShift | Int32 | De topploeg. |
| bottomShift | Int32 | De onderste verschuiving. |

### Zie ook

* class [RasterImage](../)
* naamruimte [Aspose.PSD](../../rasterimage/)
* montage [Aspose.PSD](../../../)


