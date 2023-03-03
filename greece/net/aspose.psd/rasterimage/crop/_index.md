---
title: RasterImage.Crop
second_title: Aspose.PSD για Αναφορά API .NET
description: RasterImage μέθοδος. Περικόπτει το καθορισμένο ορθογώνιο.
type: docs
weight: 240
url: /el/net/aspose.psd/rasterimage/crop/
---
## Crop(Rectangle) {#crop}

Περικόπτει το καθορισμένο ορθογώνιο.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rectangle | Rectangle | Το ορθογώνιο. |

### Παραδείγματα

Το ακόλουθο παράδειγμα κώδικα δείχνει πώς να περικόψετε μια εικόνα και να την αποθηκεύσετε.

```csharp
[C#]

// Εφαρμογή σωστής μεθόδου περικοπής για αρχεία PSD.
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

### Δείτε επίσης

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* χώρος ονομάτων [Aspose.PSD](../../rasterimage/)
* συνέλευση [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Περικοπή εικόνας με μετατοπίσεις.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| leftShift | Int32 | Η αριστερή μετατόπιση. |
| rightShift | Int32 | Η σωστή μετατόπιση. |
| topShift | Int32 | Η μετατόπιση στην κορυφή. |
| bottomShift | Int32 | Η κάτω μετατόπιση. |

### Δείτε επίσης

* class [RasterImage](../)
* χώρος ονομάτων [Aspose.PSD](../../rasterimage/)
* συνέλευση [Aspose.PSD](../../../)


