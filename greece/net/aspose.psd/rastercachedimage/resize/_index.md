---
title: RasterCachedImage.Resize
second_title: Aspose.PSD για Αναφορά API .NET
description: RasterCachedImage μέθοδος. Αλλάζει το μέγεθος της εικόνας.
type: docs
weight: 120
url: /el/net/aspose.psd/rastercachedimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Αλλάζει το μέγεθος της εικόνας.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | Int32 | Το νέο πλάτος. |
| newHeight | Int32 | Το νέο ύψος. |
| resizeType | ResizeType | Ο τύπος αλλαγής μεγέθους. |

### Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αλλάξετε το μέγεθος μιας εικόνας με νέο τύπο αλλαγής μεγέθους SinC.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Φόρτωση μιας υπάρχουσας εικόνας σε μια παρουσία της κλάσης PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

Ο παρακάτω κώδικας δείχνει πώς να αλλάξετε το μέγεθος μιας εικόνας με νέο τύπο αλλαγής μεγέθους Bell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Φόρτωση μιας υπάρχουσας εικόνας σε μια παρουσία της κλάσης PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

Ο παρακάτω κώδικας δείχνει πώς να αλλάξετε το μέγεθος μιας εικόνας με νέο τύπο αλλαγής μεγέθους Mitchell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Φόρτωση μιας υπάρχουσας εικόνας σε μια παρουσία της κλάσης PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

Ο παρακάτω κώδικας δείχνει πώς να αλλάξετε το μέγεθος μιας εικόνας με νέο τύπο αλλαγής μεγέθους CatmullRom.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Φόρτωση μιας υπάρχουσας εικόνας σε μια παρουσία της κλάσης PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Ο παρακάτω κώδικας δείχνει πώς να αλλάξετε το μέγεθος μιας εικόνας με έναν νέο τύπο αλλαγής μεγέθους CubicBSpline.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Φόρτωση μιας υπάρχουσας εικόνας σε μια παρουσία της κλάσης PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Ο παρακάτω κώδικας δείχνει πώς να αλλάξετε το μέγεθος μιας εικόνας με έναν νέο τύπο αλλαγής μεγέθους CubicConvolution.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Φόρτωση μιας υπάρχουσας εικόνας σε μια παρουσία της κλάσης PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Δείτε επίσης

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* χώρος ονομάτων [Aspose.PSD](../../rastercachedimage/)
* συνέλευση [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Αλλάζει το μέγεθος της εικόνας.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | Int32 | Το νέο πλάτος. |
| newHeight | Int32 | Το νέο ύψος. |
| settings | ImageResizeSettings | Οι ρυθμίσεις αλλαγής μεγέθους. |

### Δείτε επίσης

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* χώρος ονομάτων [Aspose.PSD](../../rastercachedimage/)
* συνέλευση [Aspose.PSD](../../../)


