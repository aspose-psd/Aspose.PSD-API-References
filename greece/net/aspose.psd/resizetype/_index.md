---
title: "Απαρίθμηση ResizeType"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Απαρίθμηση Aspose.PSD.ResizeType. Καθορίζει τον τύπο αλλαγής μεγέθους"
type: docs
weight: 5870
url: /el/net/aspose.psd/resizetype/
---
{{< psd/tize >}}
## ResizeType enumeration

Καθορίζει τον τύπο αλλαγής μεγέθους.

```csharp
public enum ResizeType
```

### Τιμές

| Όνομα | Τιμή | Περιγραφή |
| --- | --- | --- |
| None | `0` | Τα pixel δεν διατηρούνται κατά τη λειτουργία αλλαγής μεγέθους. |
| LeftTopToLeftTop | `1` | Το αριστερό άνω σημείο της νέας εικόνας θα συμπίπτει με το αριστερό άνω σημείο της αρχικής εικόνας. Η περικοπή θα γίνει εάν απαιτηθεί. |
| RightTopToRightTop | `2` | Το δεξί άνω σημείο της νέας εικόνας θα συμπίπτει με το δεξί άνω σημείο της αρχικής εικόνας. Η περικοπή θα γίνει εάν απαιτηθεί. |
| RightBottomToRightBottom | `3` | Το δεξί κάτω σημείο της νέας εικόνας θα συμπίπτει με το δεξί κάτω σημείο της αρχικής εικόνας. Η περικοπή θα γίνει εάν απαιτηθεί |
| LeftBottomToLeftBottom | `4` | Το αριστερό κάτω σημείο της νέας εικόνας θα συμπίπτει με το αριστερό κάτω σημείο της αρχικής εικόνας. Η περικοπή θα γίνει εάν απαιτείται. |
| CenterToCenter | `5` | Το κέντρο της νέας εικόνας θα συμπίπτει με το κέντρο της αρχικής εικόνας. Η περικοπή θα γίνει εάν απαιτείται. |
| LanczosResample | `6` | Αναδειγματοληψία χρησιμοποιώντας τον αλγόριθμο lanczos με a=3. |
| NearestNeighbourResample | `7` | Αναδειγματοληψία χρησιμοποιώντας τον αλγόριθμο πλησιέστερου γειτόνου. |
| AdaptiveResample | `8` | Αναδειγματοληψία χρησιμοποιώντας προσαρμοστικό αλγόριθμο βασισμένο σε σταθμισμένη και συνδυασμένη ρητή συνάρτηση και αλγόριθμους παρεμβολής lanczos3. |
| BilinearResample | `9` | Αναδειγματοληψία χρησιμοποιώντας διγραμμική παρεμβολή. Επιτρέπεται προ-φίλτρου εικόνας για την αφαίρεση του θορύβου πριν από την αναδειγματοληψία, όταν χρειάζεται. |
| HighQualityResample | `10` | Η υψηλής ποιότητας αναδειγματοληψία |
| CatmullRom | `11` | Η μέθοδος κυβικής παρεμβολής Catmull-Rom. |
| CubicConvolution | `12` | Η μέθοδος κυβικής συνέλιξης παρεμβολής |
| CubicBSpline | `13` | Η μέθοδος κυβικής παρεμβολής CubicBSpline |
| Mitchell | `14` | Η μέθοδος κυβικής παρεμβολής Mitchell |
| SinC | `15` | Η μέθοδος κυβικής παρεμβολής Sinc (Lanczos3) |
| Bell | `16` | Η μέθοδος παρεμβολής Bell |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να αλλάξετε το μέγεθος μιας εικόνας με νέο τύπο αλλαγής μεγέθους SinC.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Φορτώστε μια υπάρχουσα εικόνα σε μια παρουσία της κλάσης PsdImage
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

// Φορτώστε μια υπάρχουσα εικόνα σε μια παρουσία της κλάσης PsdImage
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

// Φορτώστε μια υπάρχουσα εικόνα σε μια παρουσία της κλάσης PsdImage
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

// Φορτώστε μια υπάρχουσα εικόνα σε μια παρουσία της κλάσης PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Ο παρακάτω κώδικας δείχνει πώς να αλλάξετε το μέγεθος μιας εικόνας με νέο τύπο αλλαγής μεγέθους CubicBSpline.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Φορτώστε μια υπάρχουσα εικόνα σε μια παρουσία της κλάσης PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Ο παρακάτω κώδικας δείχνει πώς να αλλάξετε το μέγεθος μιας εικόνας με νέο τύπο αλλαγής μεγέθους CubicConvolution.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Φορτώστε μια υπάρχουσα εικόνα σε μια παρουσία της κλάσης PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Δείτε επίσης

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


