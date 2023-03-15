---
title: RasterImage.Crop
second_title: Aspose.PSD für .NET-API-Referenz
description: RasterImage methode. Beschneidet das angegebene Rechteck.
type: docs
weight: 240
url: /de/net/aspose.psd/rasterimage/crop/
---
## Crop(Rectangle) {#crop}

Beschneidet das angegebene Rechteck.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | Rectangle | Das Rechteck. |

### Beispiele

Das folgende Codebeispiel zeigt, wie Sie ein Bild zuschneiden und speichern.

```csharp
[C#]

// Richtige Crop-Methode für PSD-Dateien implementieren.
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

### Siehe auch

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namensraum [Aspose.PSD](../../rasterimage/)
* Montage [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Bild mit Verschiebungen zuschneiden.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftShift | Int32 | Die Linksverschiebung. |
| rightShift | Int32 | Die richtige Verschiebung. |
| topShift | Int32 | Die Top-Schicht. |
| bottomShift | Int32 | Die untere Schicht. |

### Siehe auch

* class [RasterImage](../)
* namensraum [Aspose.PSD](../../rasterimage/)
* Montage [Aspose.PSD](../../../)


