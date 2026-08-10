---
title: "RasterImage.Crop"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Μέθοδος RasterImage. Κόβει το καθορισμένο ορθογώνιο."
type: docs
weight: 240
url: /el/net/aspose.psd/rasterimage/crop/
---
{{< psd/tize >}}
## Crop(Rectangle) {#crop}

Κόβει το καθορισμένο ορθογώνιο.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ορθογώνιο | Rectangle | Το ορθογώνιο. |

## Παραδείγματα

Το παρακάτω παράδειγμα κώδικα δείχνει πώς να κόψετε μια εικόνα και να την αποθηκεύσετε.

```csharp
[C#]

// Υλοποιήστε τη σωστή μέθοδο Crop για αρχεία PSD.
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
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Περικοπή εικόνας με μετατοπίσεις.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| leftShift | Int32 | Η αριστερή μετατόπιση. |
| rightShift | Int32 | Η δεξιά μετατόπιση. |
| topShift | Int32 | Η άνω μετατόπιση. |
| bottomShift | Int32 | Η κάτω μετατόπιση. |

### Δείτε επίσης

* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


