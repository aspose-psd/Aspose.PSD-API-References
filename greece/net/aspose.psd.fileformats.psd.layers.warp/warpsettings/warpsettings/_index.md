---
title: "WarpSettings.WarpSettings"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Κατασκευαστής WarpSettings. Αρχικοποιεί μια νέα παρουσία της κλάσης WarpSettings"
type: docs
weight: 10
url: /el/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`WarpSettings`](../).

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| meshPoints | PointF[] | Τα σημεία πλέγματος της παραμόρφωσης |
| όρια | Rectangle | Τα όρια της εικόνας παραμόρφωσης |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της ιδιότητας WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Αποκτήστε ρυθμίσεις παραμόρφωσης
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Ορίστε νέο μέγεθος
    // Για το Photoshop η τιμή μπορεί να είναι μεταξύ 1 και 50 και δεν μπορείτε να αποθηκεύσετε σωστά το αρχείο PSD.
    warpSettings.GridSize = new Size(100, 100);

    // Ορίστε έγκυρη τιμή
    warpSettings.GridSize = new Size(3, 3);

    // Αποδώστε το παράδειγμα αρχείου με πλέγμα x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Δείτε επίσης

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`WarpSettings`](../).

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| meshPoints | PointF[] | Τα σημεία πλέγματος της παραμόρφωσης |
| όρια | Rectangle | Τα όρια της εικόνας παραμόρφωσης |
| style | WarpStyles | Το στυλ της παραμόρφωσης |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει την υποστήριξη της ιδιότητας WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Αποκτήστε ρυθμίσεις παραμόρφωσης
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Ορίστε νέο μέγεθος
    // Για το Photoshop η τιμή μπορεί να είναι μεταξύ 1 και 50 και δεν μπορείτε να αποθηκεύσετε σωστά το αρχείο PSD.
    warpSettings.GridSize = new Size(100, 100);

    // Ορίστε έγκυρη τιμή
    warpSettings.GridSize = new Size(3, 3);

    // Αποδώστε το παράδειγμα αρχείου με πλέγμα x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Δείτε επίσης

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`WarpSettings`](../).

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | Αντικείμενα PS με ρυθμίσεις παραμόρφωσης |
| όρια | Rectangle | Τα όρια της εικόνας παραμόρφωσης |

### Δείτε επίσης

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

Αρχικοποιεί μια νέα παρουσία της κλάσης [`WarpSettings`](../).

```csharp
public WarpSettings(PlacedResource placedResource)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| placedResource | PlacedResource | Ο πόρος με ρυθμίσεις παραμόρφωσης |

### Δείτε επίσης

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


