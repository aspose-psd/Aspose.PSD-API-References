---
title: Image.Resize
second_title: Aspose.PSD για Αναφορά API .NET
description: Image μέθοδος. Αλλάζει το μέγεθος της εικόνας. Η προεπιλεγμένηLeftTopToLeftTopχρησιμοποιείται.
type: docs
weight: 190
url: /el/net/aspose.psd/image/resize/
---
## Resize(int, int) {#resize}

Αλλάζει το μέγεθος της εικόνας. Η προεπιλεγμένηLeftTopToLeftTopχρησιμοποιείται.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | Int32 | Το νέο πλάτος. |
| newHeight | Int32 | Το νέο ύψος. |

### Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να αλλάξετε το μέγεθος της εικόνας PSD και το αποτέλεσμα που λαμβάνουμε από το Aspose.PSD

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Δείτε επίσης

* class [Image](../)
* χώρος ονομάτων [Aspose.PSD](../../image/)
* συνέλευση [Aspose.PSD](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

Αλλάζει το μέγεθος της εικόνας.

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | Int32 | Το νέο πλάτος. |
| newHeight | Int32 | Το νέο ύψος. |
| resizeType | ResizeType | Ο τύπος αλλαγής μεγέθους. |

### Δείτε επίσης

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* χώρος ονομάτων [Aspose.PSD](../../image/)
* συνέλευση [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Αλλάζει το μέγεθος της εικόνας.

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | Int32 | Το νέο πλάτος. |
| newHeight | Int32 | Το νέο ύψος. |
| settings | ImageResizeSettings | Οι ρυθμίσεις αλλαγής μεγέθους. |

### Δείτε επίσης

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* χώρος ονομάτων [Aspose.PSD](../../image/)
* συνέλευση [Aspose.PSD](../../../)


