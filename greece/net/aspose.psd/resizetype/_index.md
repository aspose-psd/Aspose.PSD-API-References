---
title: Enum ResizeType
second_title: Aspose.PSD για Αναφορά API .NET
description: Aspose.PSD.ResizeType αρίθμηση. Καθορίζει τον τύπο αλλαγής μεγέθους.
type: docs
weight: 5370
url: /el/net/aspose.psd/resizetype/
---
## ResizeType enumeration

Καθορίζει τον τύπο αλλαγής μεγέθους.

```csharp
public enum ResizeType
```

### Αξίες

| Ονομα | αξία | Περιγραφή |
| --- | --- | --- |
| None | `0` | Τα pixel δεν διατηρούνται κατά τη λειτουργία αλλαγής μεγέθους. |
| LeftTopToLeftTop | `1` | Το επάνω αριστερό σημείο της νέας εικόνας θα συμπίπτει με το αριστερό επάνω σημείο της αρχικής εικόνας. Η περικοπή θα πραγματοποιηθεί εάν απαιτείται. |
| RightTopToRightTop | `2` | Το επάνω δεξιό σημείο της νέας εικόνας θα συμπίπτει με το επάνω δεξιό σημείο της αρχικής εικόνας. Η περικοπή θα πραγματοποιηθεί εάν απαιτείται. |
| RightBottomToRightBottom | `3` | Το δεξιό κάτω σημείο της νέας εικόνας θα συμπίπτει με το δεξί κάτω σημείο της αρχικής εικόνας. Η περικοπή θα πραγματοποιηθεί εάν απαιτείται. |
| LeftBottomToLeftBottom | `4` | Το αριστερό κάτω σημείο της νέας εικόνας θα συμπίπτει με το αριστερό κάτω σημείο της αρχικής εικόνας. Η περικοπή θα πραγματοποιηθεί εάν απαιτείται. |
| CenterToCenter | `5` | Το κέντρο της νέας εικόνας θα συμπίπτει με το κέντρο της αρχικής εικόνας. Η περικοπή θα πραγματοποιηθεί εάν απαιτείται. |
| LanczosResample | `6` | Επαναδειγματοληψία χρησιμοποιώντας τον αλγόριθμο lanczos με a=3. |
| NearestNeighbourResample | `7` | Επαναδειγματοληψία χρησιμοποιώντας τον αλγόριθμο του πλησιέστερου γείτονα. |
| AdaptiveResample | `8` | Επαναδειγματοληψία χρησιμοποιώντας προσαρμοστικό αλγόριθμο που βασίζεται σε σταθμισμένη και μεικτή ορθολογική συνάρτηση και αλγόριθμους παρεμβολής lanczos3. |
| BilinearResample | `9` | Επαναδειγματοληψία χρησιμοποιώντας διγραμμική παρεμβολή. Το προφιλτράρισμα εικόνας επιτρέπεται για την αφαίρεση του θορύβου πριν από την εκ νέου δειγματοληψία, όταν χρειάζεται |
| HighQualityResample | `10` | Το υψηλής ποιότητας resample |
| CatmullRom | `11` | Η μέθοδος κυβικής παρεμβολής Catmull-Rom. |
| CubicConvolution | `12` | Μέθοδος παρεμβολής κυβικής συνέλιξης |
| CubicBSpline | `13` | Η μέθοδος κυβικής παρεμβολής CubicBSpline |
| Mitchell | `14` | Η μέθοδος της κυβικής παρεμβολής Mitchell |
| SinC | `15` | Η μέθοδος κυβικής παρεμβολής Sinc (Lanczos3) |
| Bell | `16` | Η μέθοδος παρεμβολής Bell |

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

* χώρος ονομάτων [Aspose.PSD](../../aspose.psd/)
* συνέλευση [Aspose.PSD](../../)


