---
title: "RasterImage.Crop"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "RasterImage-Methode. Schneidet das angegebene Rechteck zu."
type: docs
weight: 240
url: /de/net/aspose.psd/rasterimage/crop/
---
{{< psd/tize >}}
## Crop(Rectangle) {#crop}

Schneidet das angegebene Rechteck zu.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Rechteck | Rectangle | Das Rechteck. |

## Beispiele

Das folgende Codebeispiel zeigt, wie man ein Bild zuschneidet und speichert.

```csharp
[C#]

// Implementieren Sie die korrekte Crop‑Methode für PSD‑Dateien.
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
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Bild mit Verschiebungen zuschneiden.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftShift | Int32 | Die Linksverschiebung. |
| rightShift | Int32 | Die Rechtsverschiebung. |
| topShift | Int32 | Die Obenverschiebung. |
| bottomShift | Int32 | Die Untenverschiebung. |

### Siehe auch

* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


