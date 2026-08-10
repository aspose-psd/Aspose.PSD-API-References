---
title: "Image.Resize"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Image method. Αλλάζει το μέγεθος της εικόνας"
type: docs
weight: 200
url: /el/net/aspose.psd/image/resize/
---
{{< psd/tize >}}
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
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int) {#resize}

Αλλάζει το μέγεθος της εικόνας. Χρησιμοποιείται η προεπιλεγμένη μέθοδος NearestNeighbourResample.

```csharp
public void Resize(int newWidth, int newHeight)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| newWidth | Int32 | Το νέο πλάτος. |
| newHeight | Int32 | Το νέο ύψος. |

## Παραδείγματα

Το παρακάτω παράδειγμα δείχνει πώς να αλλάξετε το μέγεθος μιας εικόνας PSD και το αποτέλεσμα που λαμβάνουμε με το Aspose.PSD

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName, new PsdLoadOptions() { LoadEffectsResource = true }) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Δείτε επίσης

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

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
| ρυθμίσεις | ImageResizeSettings | Οι ρυθμίσεις αλλαγής μεγέθους. |

### Δείτε επίσης

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


